# Assignment Read: 01 - Introductory HTML and JavaScript

## About HTML

HTML uses tags to organize information on a web page. Tags are also referred to as markup or elements. They carry attributes that describe the content presented on the web page. The current version of HTML is HTML5. HTML5 uses can either be structural or semantic tags/elements. Examine the table below for the difference between structural markup and semantic markup.

| Command | Structural Markup | Semantic Markup
| --- | --- | --- |
| WHAT | Structural markup is used to describe headings and paragraphs | Semantic markup provides additional information about the structural markup presented on the page. |
| WHY | SStructural markup is intended to affect the structure of the webpage itself. | Semantic markup is used to customize html tags on a webpage. It is useful in providing additional context about the web page to external entities such as browsers and search engines. |
| HOW | Both structural and semantic markups make use of tags and attributes.| Both structural and semantic markups make use of tags and attributes. |
| EXAMPLE | ```<p>This text represents a paragraph<p>``` The example above is considered structural markup. | ```<p>``` This text represents a ```<i>paragraph</i><p>```

The italic tag ```<i>``` in the example above is considered semantic markup because it defines a portion of the paragraph as being italicized.|

## About CSS

While HTML is used to structure a webpage, CSS is used to style the structure of the webpages. For example, HTML can be used to define information on a webpage using elements such as a paragraph (```<p>```. However, CSS would be used to define the style of the elements on a page. For example, you can use CSS to define the color, font, size and so on of the paragraph ```<p>``` element. CSS styling can be either inline or external. Inline CSS exists in the element or tag itself. External CSS references an external CSS file from which it pulls its style. Inline styling exists within the html tag itself. See the table below for the visual difference between the two ways you can apply CSS styling. For example, in the table below, both inline and external CSS can be used to style a paragraph text to be display in red.

| Inline CSS | External CSS |
| --- | --- |
| ```<p style=”color:red;”>```| ```<link rel="stylesheet" href="mystyle.css">``` |

If  you decide to use an external CSS style sheet, the style sheet must contain the CSS styles you wish to apply to your HTML tags. The example below oul change every ```<p>``` element to red:

p {
color: red;

}


## What is Javascript?

Javascript is a programming language used to control the behavior of a webpage. Currently, ECMA20=015 is the latest version of Javascript. Win web development, we use Javascript to write scripts that define some kind of information processing. The example below highlights an example of inline Javascript using the ```script``` tag. In HTML, the ```script``` tag allows you to run scripts from your HTML webpage.

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <title>My Company Website</title>
  <link rel="stylesheet" href="css/my-custom-style.css">
</head>
<body>
  <h1>About Me</h1>
<script> alert("Welcome to my website") /script>
</body>
</html>[^1]
```

Alternatively, you can also reference an external Javascript file on your HTML page. Javascript files end with the ".js" extension. To reference and external javascript file, use the src attribute with the script tag to specify the file that contains your javascript. Referencing and external Javascript file would look something like this:

```html
<script src="\Myscripts\calculateTotal.js"></script>```

Most websites have a lot of Javascript code written to support it's function.

Javascript uses variables to stop data. Some examples of variables include string, integer, boolean and an array.

Before you decide to write Javascript, take the time to write down your goal and each step involved in completing a task. For example, if your goal is to create a quiz, your tasks might include:

//Create a quiz

1. Create questions and answers
2. Prompt user for input
3. Check/compare answers and determine if they are correct
4. Return the user's score
5. Store user results in another location (Optional)


## How does HTML, CSS and Javascript work together?

Together, HTML, CSS and Javascript are used to build and design beautiful websites. Understanding HTML and CSS helps you better communicate information to your web page visitors. HTML is used to create the structure of a web page. CSS is used to style an HTML page. And finally, Javascript handles any actions taken on HTML elements on a page.

### Tips for creating useful and beautiful webpages.

Before you use design a web page, consider your target audience's preference? For example, if you anticipate visitors to be mainly children, then it may make more sense of bright inviting colors to encourage interaction. Try to think about why users will visit your website. What are they trying to achieve? The easier you make it for your visitors to achieve their goal, the more likely they are to return and even refer other users to your site. Here are a few helpful tips for designing your website.

* Use sitemap- Sitemaps show how the pages should be organized. 
* Use Wireframes- Wireframes is a sketch of how you expect your site to look and depicts how you intend to organize information on your page.
* Keep the content on your webpage clear, concise and interactive. Don't overdo your page design with unnecessary features that may confuse your visitors.
