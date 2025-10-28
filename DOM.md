# DOM

In this section, we will start writing the DOM tree of an HTML document or file. DOM stands for _Document Object Model_. The DOM is structure like a true. It starts with an html root element followed by head and body. The head and the body are the immediate children of the root element, html. Before the root element, there is a declaration.

## Declaration

Before the root element, there is a declaration. This declaration tells the browser that the document is an HTML. Therefore, the browser render it to the way an HTML suppose to be rendered.
This is the code to declare an HTML. The declaration is not part of the DOM tree.

Basicly, it shows that you use HTML 5 version.
```html
<!DOCTYPE html>
```
## Root Element

The html element is the root of the DOM tree and is the parent of **head** and **body**.
The DOM try has to be wrapped by the html tag.
```html
<!DOCTYPE html>
<html></html>
```

The html tag with two children, head and body.
```html
<!DOCTYPE html>
<html>
  <head>

  </head>
  <body>
    content goes here
  </body>
</html>
```
Create folder on the desktop and give it any name and inside this folder create an index.html file. Every HTML file has to end with a .html extension. And it is good to have at least on index.html or test.html file in the a project and the reset of the file will have different names.
This a simplistic DOM structure that contains html, head, title, body, h1 elements.
```html
<!DOCTYPE html>
<html>
  <head>
    <title>My first page</title>
  </head>
  <body>
    Hello world!
  </body>
</html>
```
