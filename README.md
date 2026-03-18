<h3>1.1 What is HTML?</h3>
     HTML stands for Hyper Text Markup Language.<br>
     HTML is the standard markup language for creating Web pages.<br>
     HTML describes the structure of a Web page.<br>
     HTML consists of a series of elements.<br>
     HTML elements tell the browser how to display the content.<br>
     Basic structure of every website is created using HTML Language.<br>
     We can create a static website by HTML only.<br>

<h3>1.2 What is a Web Page</h3>
   A web page is a document on the internet that is written in HTML and displayed in a browser.<br>
<b>Example</b>:<br>
  1.Home page of a website<br>
  2.Contact page<br>
  3.About page<br>

<h3>1.3 What is a Web Browser</h3>
   A web browser is software that reads HTML code and displays the web page.<br>
<b>Examples of browsers:</b><br>
     1.Google Chrome<br>
     2.Microsoft Edge<br>
     3.Mozilla Firefox<br>
     4.Safari<br>

<h3>1.4 History of HTML</h3>
     HTML was created by <b>Tim Berners-Lee</b>.<br>
 <b>* Important versions:</b><br>
| Year | Version      |<br>
| ---- | ------------ |<br>
| 1991 | HTML created |<br>
| 1993 | HTML 1.0     |<br>
| 1995 | HTML 2.0     |<br>
| 1999 | HTML 4.01    |<br>
| 2012 | HTML5        |<br>

 <b>HTML5</b> is the latest and most used version.<br>

<h3>1.5 Advantages and Disadvantages of HTML Advantages</h3>
 <b>Advantages:</b><br>
    ✔ Easy to learn<br>
    ✔ Supported by all browsers<br>
    ✔ Used to create websites<br>

<b>Disadvantages:</b><br>
   ❌ Creates only static pages<br>
   ❌ Needs CSS and JavaScript for design and functionality<br>

<h3>1.6 Basic Structure of HTML Page</h3>
     Every HTML page has a basic structure.<br>
# Basic HTML Structure

```html
<!DOCTYPE html>
<html>
<head>
    <title>My First Page</title>
</head>
<body>

    <h1>Hello World</h1>
    <p>This is my first HTML page.</p>

</body>
</html>
```
<b>Explanation:</b><br>
| Tag | Meaning |
|-----|---------|
| `<html>` | Main HTML document |
| `<head>` | Information about webpage |
| `<title>` | Title in browser tab |
| `<body>` | Visible content |

<br>


<h3>1.7 HTML Tags</h3>
   HTML tags are keywords inside angle brackets < > used to create elements.<br>
<b>Example:</b><br>

`<h1>Heading</h1>`<br>
`<p>Paragraph</p>`

Here<br>
`<h1>` and `<p>` are HTML tags.

<br>

<h3>1.8 HTML Elements</h3>
    An HTML element includes:<br>
        Start tag + Content + End tag.<br>

<b>Example:</b>

`<p>This is a paragraph</p>`

<b>Explanation:</b>
     | Part | Meaning |
|------|---------|
| `<p>` | Start tag |
| Text | Content |
| `</p>` | End tag |<br>


<h3>1.9 Empty Tags</h3>
   Empty tags do not have a closing tag because they contain no content.<br>
<b>Examples:</b><br>
  1. &lt;br&gt;<br>
2. &lt;hr&gt;<br>
3. &lt;img&gt;<br>
<b>Example:</b>

```html
<p>Hello<br>Students</p>
<hr>
```
<b>Output:</b><br>
Hello<br>
Students
<br>

<h3>1.10 HTML Basic Content Tags</h3>
    Common tags used to display content.<br>
| Tag      | Use             |<br>
| -------- | ---------- |<br>
| &lt h1 > | Heading         |<br>
| &lt p >  | Paragraph       |<br>
| &lt br > | Line break      |<br>
| &lt hr > | Horizontal line |<br>

<b>Example:</b><br>
```html
<h1>HTML Class</h1>
<p>This is paragraph.</p>
<br>
<hr>
```
<br>

<h3>Lecture 02:<h3>
     
<h3>2.1 What is Attribute</h3>
    An attribute provides extra information about an HTML tag.<br>
    Attributes are written inside the start tag.<br>

<b>Example:</b><br>

```html
<a href="https://google.com">Google</a>
```

Here<br>
<b>href</b> is an attribute.
<br>

<h3>2.2 HTML Attributes</h3>
Attributes are always written as:<br>
name="value"<br>
<b>Example:</b>

```html
<img src="image.jpg" alt="photo" width="200">
```


<b>Explanation:</b><br>
1. src : image location<br>
2. alt : image description<br>
3. width:image size<br>

<h3>2.3HTML Formatting Tags:</h3>
Used to style text.<br>

| Tag        | Use                        |
|------------|----------------------------|
| `<b>`      | Bold text                  |
| `<strong>` | Important (bold) text      |
| `<i>`      | Italic text                |
| `<em>`     | Emphasized text            |
| `<u>`      | Underline                  |
| `<mark>`   | Highlight text             |
| `<small>`  | Small text                 |
<br>
 <h3>✅ Example</h3><br>

```html
<p>This is <b>bold</b> text</p><br>
<p>This is <i>italic</i> text</p><br>
<p>This is <u>underline</u> text</p><br>
<p>This is <mark>highlight</mark> text</p><br>
```
<h3>2.4HTML Comments</h3>
Used to <b>write notes in code (not visible in browser)</b><br>

<h3>✅ Example</h3><br>
## 💬 Comment Example

```html
<!-- This is a comment -->
<p>Hello Students</p>
```

<h3>2.5HTML Links</h3>
Used to<b> connect one page to another</b><br>
Tag: `<a>` <br>
Attributes:<br>
    `href`→ link address<br>
   `target="_blank"` → open in new tab<br>

<h3>✅ Example:</h3>

```html
<a href="https://google.com">Open Google</a><br>
<a href="https://google.com" target="_blank">Open in New Tab</a>
```
<br>

<h3>2.6 HTML Images</h3>
<b></b>Used to display images</b><br>

<h3></h3> 🖼️ Image Tag</h3><br>
Tag: &lt;img&gt; (empty tag)<br>

<h3>📌 Attributes:</h3>

| Attribute        | Use               |
|------------------|-------------------|
| `src`            | Image path        |
| `alt`            | Description       |
| `width`          | Image width       |
| `height`         | Image height      |
