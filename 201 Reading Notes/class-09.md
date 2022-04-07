# Read: 09 - Forms and Events

## Lists, Tables & Forms

### Forms
Forms allow you  to collect data from your user(s). Forms are comprised of form controls that allow your user to interact with your form. Some form control examples include text input, radio boxes, drop-downs and so on. The form control you decide to use will depend largely on what kind of data you are collecting. For example, if you wish to collect an attachment such as a photo or a pdf, you will utilize file upload.
When a user fills out and submits a form, That information is processed (and in most cases stored). Usually the user experience ends with the user being notified that their data was received.

Here is an example of a code that generates a simple form that collects a user’s name and plan preference:

```html
<form action="https://switchcode.io/login.php"
<p> Name:
<input type="text" name='Name' size="14" maxlength="25"/>
</p>
<p>Please select your plan
<input type="radio" name'plan' value="Basic Plan" /> Basic Plan
<input type="radio" name'plan' value="Silver Plan" /> Silver Plan
<input type="radio" name'plan' value="Gold Plan" checked='checked'/> Gold Plan
</p>
</form>
```
This would render the folloing form:
![](imgs/form1.png)

### Lists
Lists are useful for displaying ordered (i.e., numbered) or unordered (i.e., bullet points) data. In html, lists are made of using ul an li elements.

### Tables
Tables allow you to display data on your webpage in a cell-based format, using td and tr elements. Like all other html elements, you can use CSS to style the look of your table and create a suitable visual experience for your user. 
### Events
Events allow you to use DOM (Document Object Model) tree nodes to trigger events, It allows your written JS code to response to users and create interactions on your web page. When JavaScript code is triggered by interaction with your web page, this is called event handling. There are three types of event handlers:
* HTML Event Handlers 
* Traditional DOM Event Handlers
* DOM Level 2 Events Handlers

HTML Event Handlers  is no longer used. Traditional DOM Event Handlers support all major browsers. However only one (1) function can be attached per event. DOM Level 2 Events Handlers support the ability to trigger multiple functions per event. However, keep in mind that it does not support IE8 or earlier browsers.
