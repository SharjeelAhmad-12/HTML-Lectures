## Introduction to HTML: Tags, Elements, and Attributes

### What is an HTML Tag?

An **HTML tag** is a fundamental building block of an HTML document. It is used to define and enclose content within the HTML structure. Tags are written within angle brackets `< >`.

### Example of an HTML tag:

```html
<h1>Hello World</h1>
```

Here, `<h1>` is the opening tag, and `</h1>` is the closing tag. The content inside the tag (Hello World) is what's being affected or structured by the tag.

### What is an HTML Element?

An HTML element refers to everything between an opening tag and a closing tag, including the tags themselves. An element can contain text, attributes, and other nested elements.

Example of an HTML element:

```html
<a href="https://www.example.com">Visit Example</a>
```

In this case:

- `<a>` is the opening tag.
- `href`="https://www.example.com" is an attribute of the `<a>` element.
- `Visit Example` is the content inside the element.
- `</a>` is the closing tag.

The whole part from `<a href="...">` to `</a> `constitutes an HTML element

## What is an HTML Attribute?

An HTML attribute provides additional information about an element. Attributes are written inside the opening tag and usually consist of a name and a value.

### Example of an HTML element with an attribute:

```html
<img src="image.jpg" alt="A sample image" />
```

`src` is an attribute of the `<img>` element, specifying the source file for the image.
`alt` is another attribute that provides alternative text for the image, which is useful for accessibility purposes.

-----

In HTML, some tags consist of both opening and closing tags, such as `<p>` and `</p>` for paragraphs, while others have only an opening tag, like `<img>` for images.
