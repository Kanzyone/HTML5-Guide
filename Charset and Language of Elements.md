# Charset and Language of Elements

The other important thing <meta charset="UTF-8" />, with this tag, we specify the standard character set of the files and we do not get a character error.

```html
<!DOCTYPE html>
<head>
    <meta charset="UTF-8" /> <!-- character encoding for the HTML document -->

    <title>My first page</title>
</head>
<body>
    Hello world!
</body>
</html>
```
Helps define the language of an element: the language that non-editable elements are in, or the language that editable elements should be written in by the user. The attribute contains one “language tag” (made of hyphen-separated “language subtags”) in the format defined in Tags for Identifying Languages (BCP47). xml:lang has priority over it.
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My first page</title>
</head>
<body>
    Hello world!
</body>
</html>
```
