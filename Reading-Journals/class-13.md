# Local Storage

HTML5 Web Storage allows key/value pair data to be stored localy within the user's web browser. Data is stored per origin (which is comprised of a domain and protocol), allowing all pages on that origin can store and access the same data.

Browsers that support HTML Web Stroage include:

* Google Chrome v4+ and beyond
* Miscroft Edge v8+ and beyond
* Firefox v3.5+ and beyond
* Apple Safari v4+ and beyond
* Opera 11.5+ and beyond 

HTML web storage can store data in local storage or session storage. Local storage stores data within the client's browser with no expiration date. Session storage stores data within the client's browser and is lost when the session ends.
 To store data locally, the values must be a string.
  
  * JSON.stringify - converts a JavaScript object or value to a JSON string.
  getItem()

  Make sure the data persists across both browser refreshes and resets. Retrieve the products array from local storage and then utilize the JSON.Parse() function. 
   * JSON.parse - converts string to JSON

  Tool for viewing JSON objects: https://jsonformatter.org/json-parser

  Info about JSON from https://codebeautify.org/blog/json-full-form/

  ## Why JSON is so Popular
  JSON is easy to understand, read and write.
  All languages and browsers have parser for the JSON.
  JSON format can store any type of data such as Int, Boolean, String, Base64 String etc.
  
  ## Advantage of JSON data exchange format
  Human can read it better than XML , YAML or CSV format.
  JSON is light-weight competitor of XML.
  JSON is Simple and efficient than other data formats.
  It’s simple and self explanatory
  Best and Easy to use in AJAX based JavaScript based web application
  JSON provides flexibility for developers and it’s interoperable with other languages
