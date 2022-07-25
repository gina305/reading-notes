## Classes and Objects

### Classes

You can access class variables and function using dot '.'  notation.
For example:

```python
#Define a car class (you can think of a class as a "blueprint" for creating objects
class Car(color):
    color = color,
    make = "Ford",
    model = "F-150",
    monthly_payment = 450,
    months = 60,
    
my_car = Car("blue")
print(Car.model)
# Expected Output: "F-150"
```
You can create multiple, different objects that are of the same class(have the same variables and functions defined). However, each object contains their own variables 

Classes have a built-in __init__() function which is used to assign values to object properties or carry out other operations.
### Objects

In this example, we use the __init__ function to calculate the totaly cost of the vehicle over the default term of 36 months.

```python
class Person:
  def __init__(self, name, age):
    self.name = name
    self.age = age

p1 = Person("John", 36)

print(p1.name)
print(p1.age)
```


## Fixtures

Fixtures are useful for making common objects or variables available to all of your tests. Those objects contain data you want to share across tests. This is very useful in reducing code and simplifying the creation of test suites.` Using pytest,  you can define fixtures. To define a fixture, use pytest.fixture decorator along with a function definition. Fixtures help set up resource before and after each test is ran. 

For example, the following test_fixture.py
```python
#Define a fixture
@fixture()
def case_prompt():
    print("Running...")
    yield
    print('test case completed.')

from pytest import mark, fixture
@mark.test_fixture
def test_case1(case_prompt):
    print("Test case 1 ran")

@mark.test_fixture
def test_case2(case_prompt):
    print("Test case 2 ran")

# To run the tests: pytest -m test_fixture
```

### Definitions to know
* Recursion means a defined function can call itself. It is useful for looping through data to reach a result. Be careful not to slip into an endless loop.
* Iteration means to loop through a defined variable (ie tuple, string, dictionary, etc)

### Tools/Modules
pytest - a library for testing Python code. Great for TDD (Test-Driven Development)
