# Read 13 ~ Update/Delete
> By Abdallah obaid

**NAME**     | **URL**
------------ | -------------
Home         | [Home](https://abdallah-obaid.github.io/reading-notes-301/).
 Read 01     | [SMACSS and Responsive Web Design](https://abdallah-obaid.github.io/reading-notes-301/class-01).
 Read 02     | [jQuery, Events, and The DOM](https://abdallah-obaid.github.io/reading-notes-301/class-02).
 Read 03     | [Flexbox and Templating](https://abdallah-obaid.github.io/reading-notes-301/class-03).
 Read 04     | [Responsive Web Design and Regular Expressions](https://abdallah-obaid.github.io/reading-notes-301/class-04).
 Read 05     | [Heroku Deployment](https://abdallah-obaid.github.io/reading-notes-301/class-05).
 Read 06     | [Node, Express, and APIs](https://abdallah-obaid.github.io/reading-notes-301/class-06).
 Read 07     | [APIs continued](https://abdallah-obaid.github.io/reading-notes-301/class-07).
 Read 08     | [SQL](https://abdallah-obaid.github.io/reading-notes-301/class-08).
 Read 09     | [Refactoring](https://abdallah-obaid.github.io/reading-notes-301/class-09).
 Read 10     | [The Call Stack and Debugging](https://abdallah-obaid.github.io/reading-notes-301/class-10).
 Read 11     | [EJS](https://abdallah-obaid.github.io/reading-notes-301/class-11).
 Read 12     | [Components](https://abdallah-obaid.github.io/reading-notes-301/class-12).
 Read 13     | [Update/Delete](https://abdallah-obaid.github.io/reading-notes-301/class-13).
 Read 14a    | [DB Normalization](https://abdallah-obaid.github.io/reading-notes-301/class-14a).
 Read 14b    | [Project Ideas & APIs](https://abdallah-obaid.github.io/reading-notes-301/class-14b).
 Read 15     | [Diversity and Inclusion](https://abdallah-obaid.github.io/reading-notes-301/class-15).

 
----------------------------------
# Sending form data:-
----------------------------------
 * A client (usually a web browser) sends a request to a server (most of the time a web server like Apache, Nginx, IIS, Tomcat, etc.), using the HTTP protocol. The server answers the request using the same protocol.

 * **On the client side:** The <form> element defines how the data will be sent. All of its attributes are designed to let you configure the request to be sent when a user hits a submit button. The two most important attributes are action and method.
 * The **action** attribute defines where the data gets sent. Its value must be a valid relative or absolute URL. If this attribute isn't provided, the data will be sent to the URL of the page containing the form — the current page.
 * The **method** attribute defines how data is sent. The HTTP protocol provides several ways to perform a request; HTML form data can be transmitted via a number of different methods, the most common being the GET method and the POST method.
 * The **GET method** is the method used by the browser to ask the server to send back a given resource: "Hey server, I want to get this resource." In this case, the browser sends an empty body. Because the body is empty, if a form is sent using this method the data sent to the server is appended to the URL.
 * The **data** is **appended** to the **URL** as a series of **name/value** pairs. After the URL web address has ended, we include a question mark **(?)** followed by the name/value pairs, each one separated by an ampersand **(&)**.
 * The **POST method** is a little different. It's the method the browser uses to talk to the server when asking for a response that takes into account the data provided in the body of the HTTP request: "Hey server, take a look at this data and send me back an appropriate result." If a form is sent using this method, the data is appended to the body of the HTTP request.
 
 
 # EJS Options:-
----------------------------------
* cache Compiled functions are cached, requires filename
* filename Used by cache to key caches, and for includes
* context Function execution context
* compileDebug When false no debug instrumentation is compiled
* client Returns standalone compiled function
* delimiter Character to use with angle brackets for open/close
* debug Output generated function body
* _with Whether or not to use with() {} constructs. If false then the locals will be stored in the locals object.
* localsName Name to use for the object storing local variables when not using with Defaults to locals
* rmWhitespace Remove all safe-to-remove whitespace, including leading and trailing whitespace. It also enables a safer version of -%> line slurping for all scriptlet tags (it does not strip new lines of tags in the middle of a line).
* escape The escaping function used with <%= construct. It is used in rendering and is .toString()ed in the generation of client functions. (By default escapes XML).
* outputFunctionName Set to a string (e.g., 'echo' or 'print') for a function to print output inside scriptlet tags.
* async When true, EJS will use an async function for rendering. (Depends on async/await support in the JS runtime.
 
  ![Rest](./Img/rest.png)