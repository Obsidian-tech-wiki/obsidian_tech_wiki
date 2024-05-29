---
authors:
  - "0x4248"
tags:
  - Software
  - Markup_language
aliases:
  - hyper text markup language
  - html
  - Hyper text markup language
Filetype extensions:
  - "[[Wiki/Software/File types/Programming/html|.html]]"
---
**HTML** (Hyper text markup language) is the standard [[Markup language|markup language]] for webpages. HTML is the main structure of a web page and can consist of [[image|images]], [[Video|video]] and [[Text|text]]. A [[Web browser|web browser]] parses the web page and renders it on the screen. HTML can also include scripts that run on the page to add functionality. The scripts are written in [[JavaScript|javascript]].

## Versions
HTML has had many versions and revisions over the years with the latest version being HTML5.

- HTML 1.0 - 1993
- HTML 2.0 - 1995
- HTML 3.2 - 1997
- HTML 4.0 - 1997
	- HTML 4.01 - 1999
- HTML 5.0 - 2014
	- HTML 5.1 - 2016
	- HTML 5.2 - 2017
## Markup
HTML uses tags to define the structure of a webpage. Tags are enclosed in angle brackets and are usually in pairs. An example of a tag is `<p>` which defines a paragraph. The closing tag is `</p>`. Tags can also have attributes inside them. An example of an attribute is `class` which can be used to style the element with [[Cascade Style Sheets|CSS]].

An example of a simple HTML page is shown below:
```html
<!DOCTYPE html>
<html>
<head>
  <title>Page Title</title>
</head>
<body>
    <h1>This is a Heading</h1>
    <p>This is a paragraph.</p>
</body>  
```
<div>
	<!-- TEMPLATE: CC-0 Code license -->
	<p style="color:gray;margin:0;">Code shown licensed under the <strong>public domain</strong> (CC-0) <a style="color:gray;" href="https://creativecommons.org/public-domain/cc0/">More info</a></p>
</div>
### Key elements
- `<!DOCTYPE html>` - This is the document type declaration and tells the browser that the document is an HTML5 document.
- `<html>` - This is the root element of the document.
- `<head>` - This element contains meta-information about the document.
- `<title>` - This element sets the title of the document.
- `<body>` - This element contains the content of the document.
- `<h1>` - This element defines a heading with the highest priority.
	- `<h2>` - This element is a subheading of `<h1>`.
	- This is continued up to `<h6>` which is the lowest priority heading.
- `<p>` - This element defines a paragraph of text.
- `<a>` - This element defines a hyperlink to another webpage.
- `<br>` - This element creates a line break.
- `<img>` - This element defines an image on the page.
- `<button>`- This element defines a button.
- `<script>` - This element defines a script that runs on the page.

#### Paragraphs
Paragraphs are rendered as blocks of text with a space between them. They are defined with the `<p>` tag.

```html
<p>This is a paragraph.</p>
```

#### Headings
Headings are used to define the structure of the page. They are defined with the `<h1>` to `<h6>` tags.

```html
<h1>This is a heading</h1>
<h2>This is a smaller heading</h2>
<h3>This is an even smaller heading</h3>
<h4>This is an even more of a smaller heading</h4>
<h5>This is an even even more of a smaller heading</h5>
<h6>This is the smallest heading</h6>
```
#### Links
Links allow you to link one page to another and give the user the option to navigate to the linked page. Links are defined with the `<a>` tag.

```html
<a href="https://example.com">This is a link</a>
```

Links can be also put within a paragraph.

```html
<p>Visit my <a href="https://example.com">website</a></p>
```

#### Images
Images can be added to a webpage using the `<img>` tag. The `src` attribute is used to define the source of the image.

```html
<img src="image.jpg" alt="This is an image">
```

#### Line breaks
Line breaks can be added to a webpage using the `<br>` tag. A line break will add a new line to the page.

```html
<p>This is a paragraph.<br>This is a new line.</p>
```

They can also be used to add space between elements.

```html
<p>This is a paragraph.</p>
<br>
<p>This is a new paragraph.</p>
```

#### Buttons
Buttons can be added to a webpage using the `<button>` tag. A button commonly will have an `onclick` attribute that will run a script when the button is clicked.

```html
<button onclick="alert('Hello World!')">Click me</button>
```

#### Scripts
Scripts can be used to add functionality to the HTML page. Scripts are written in JavaScript and are defined with the `<script>` tag.

```html
<p id="test">Hello world</p>
<button onclick="myFunction()">Click me</button>
<script>
let changed = false;
function myFunction(){
	if (changed){
    document.getElementById("test").innerHTML = "Hello world";
    changed = false;
  } else {
    document.getElementById("test").innerHTML = "Hello JavaScript!";
    changed = true;
  })
}
```
<div>
	<!-- TEMPLATE: CC-0 Code license -->
	<p style="color:gray;margin:0;">Code shown licensed under the <strong>public domain</strong> (CC-0) <a style="color:gray;" href="https://creativecommons.org/public-domain/cc0/">More info</a></p>
</div>

The script on the page will change the text to "Hello JavaScript!" when the button is clicked. If the text is already "Hello JavaScript!" it will change it back to "Hello world".

## HTML and HTTP
[[Hypertext Transfer Protocol|HTTP]] is a protocol used to transfer HTML documents over the internet. When a user requests a webpage from a server, the server will send the HTML document to the user's browser. The browser will then parse the HTML and render the page on the screen.

---
## See also
- [[Internet]]
- [[World wide web]]
- [[JavaScript]]
- [[CSS]]
## References
- [W3C HTML5 specification](https://www.w3.org/TR/html52/)
- [Wikipedia - HTML](https://en.wikipedia.org/wiki/HTML)