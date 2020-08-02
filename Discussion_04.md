# Structuring Webpages with HTML

## Process & Design
Before a developer enters the coding for a website, they first need to know who their customer is & what they're looking for; what are their motivations & goals? Once you know what needs to appear on your site, you can organize this by using _Site Maps_ and _Wireframes_.

* _**Site Maps**__ : allow you to plan the structure of the site
* _**Wireframes**__ : organizes the information that needs to go on each page.

Afterwards you will want to apply various sizes, colors & styles of fonts to differentiate information. You can also use grouping & similarity to help simplify the information you present.

## Structure
HTML code is made up of characters that exist inside angled brackets- these are called HTML **_elements_**. We apply these elements in a container-like manner so that information is visually structured in titles, headers and paragraphs on our webpages. The important part of learning html is not to remember all tags, but to remember the rules of structuring the code.

## HTML5 Layout
HTML5 is a new set of HTML elements that helps better categorize webpage structure. Without it, HTML elements are more generalized with `<div>` tags instead of being more specific with tags such as `<header>`, `<article>`, `<main>`, `<hgroup>` tags and many more. Older browsers need to be told which elements are block elements & require extra Javascript.

## Extra Markup
- `<!DOCTYPE html>` is located at the top of an html file to let the browser know what version of HTML is it using.
- `<!-- comment goes here-->` is used for developers to leave notes in their code for other developers. The browser ignores this for that reason.
- `<div id= unique identifier>` this attribute uniquely identifies an html element, used to uniquely identify that element from other elements on the page.
- `<div class= group identifier>` this attribute identifies several html elements to be uniquely identified from others, rather than just one.
- **Block elements** are elements that always appear to start on a new line in the browser window. Examples include: `<h1>`, `<p>`, `<ul>` and `<li>`.
- **Inline elements** are elements that always continue on teh same line as their neighboring elements. Examples include: `<a>`, `<b>`, `<em>` and `<img>`.
- `<div>` and `<span>` tags are block & inline elements grouped together as content.
- `<iframe>` displays a smaller window on our page of another website. This can be used to display youtube videos or google maps on your page. The _src_ attribute included sources the page you want to use and _height_ & _width_ attributes specify the size of this window.
- `<meta>` is inside the `<head>` element which contains information about that web page. It can be used to tell search engines about your page, who created it and whether or not it is time sensitive.

Escape characters are characters that we may want to include on our webpages. They need special code to render correctly on the webpage. Such as `< and >`. The special code for these are `&lt;` and `&gt;`. You can put a &copy; copyright symbol by using `&copy;`. &cent; can be displayed by using `&cent;`. &trade; to display a trademark you use `&trade;`. There are also many more you can use.


- [Return To Home - 102](/README.md)

