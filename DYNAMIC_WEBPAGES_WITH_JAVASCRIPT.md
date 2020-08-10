# Dynamic Webpages With Javascript

There are 3 languages used to program web pages: HTML, CSS & Javascript. HTML is the content layer of the web page, CSS visually presents the page and Javascript is the layer that tells the page how to behave when a user interacts with it. All 3 are kept in separate files. These 3 layers working together are a popular approach used when building web pages called __*progressive enhancement*__.

Javascript files are generally kept in their own js file & have a .js extention at the end of the file name. To use a javascript with a web page, you use the `<script>` element in the HTML file to tell the browser it's reading a script. It's "src" attribute tells where it is stored.

Javascript can be added between two script tags, but that could also slow down your page, so that it why is it better to be kept in a separate file that the script tags on your html page just link to.


## Reading & Writing Javascript

- It is important to note that javascript is case sensitive.
- A script is a series of instructions that a computer can follow one-by-one. Each individual instruction or step is known as a __*statement*__. Statements should end with a semicolon`(;)`.
- Statements are instructions and each one starts on a new line.
- Some statements are surrounded by curly braces, these are known as __*code blocks*__. The closing curly bracket is not followed by a semicolon.
- To write a comment that stretches over more than one line, you use a __*multi-line*__ comment, starting with `/*` and ending with `*/`. Anything in between will not be processed by javascript.
- In a __*single-line*__ comment, anything that follows the two forward slash characters // on that line will not be processed.
- A script will temporarily store the bits of information it needs to do it's job, it can store data in __*variables*__. A variable is a good name for this concept because data stored in a variable can change or vary each time a script is run.
- When scripts can use variables to find the information it needs when running with different data, the result is said to be calculated or computed using the data stored in the variables.
- __*var*__ is an example of what programmers call a keyword. In order to use the variable, you must give it a name (in this case the variable is called __*quantity*__).
- If a variable name is more than one word, it is usually written in camelCase. This means the first word is all lowercase and any subsequent words have their first letter capitalized.
- When you set a value to a variable, it is called quantity. The = sign is an assignment operator meaning you are setting a value to the variable.
- Until you set a value to a variable, it is __*undefined*__.
- Javascript distinguishes between numbers, strings and true or false values known as __*Booleans*__.



- [Return To Home - 102](/README.md)