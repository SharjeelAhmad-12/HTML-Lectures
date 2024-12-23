# Introduction to HTML

## What is HTML?

HTML stands for `HyperText Markup Language`. It is the standard language used to create and structure content on the web. Think of HTML as the foundation of every website; it tells the browser how to display text, images, links, and other elements on a webpage.

- It is not a programing language Like C++,C#,C,Phyton,Java it is a markup language

- `HyperText:` This is text that has links to other pages or places. When you click on a link in a webpage, it takes you to another page or to a specific part of the same page. It's what allows you to easily jump from one page to another on the internet.

- `Markup Language:` This is a system that uses special codes to tell the computer how to display text and other things like images or videos. It's like giving the computer instructions on how to organize and show everything on a webpage. These instructions, called "tags," help define things like headings, paragraphs, and links.

## Why Do We Use HTML?

 HTML is essential for making websites . Here's why:

### 1. **Organize Content:** 
HTML helps arrange everything on a webpage, like headings, paragraphs, and lists, so it looks neat and easy to read.

### 2. **Add Media:** 
HTML lets you add pictures, videos, music, and other media to make the page more interesting.

### 3. **Create Links:**
 HTML allows you to add clickable links (like buttons or text) that take you to other pages or websites.

### 4. **Make Pages Interactive:** 
While HTML on its own is not interactive, it works with other technologies like CSS (for style) and JavaScript (for action) to make pages more engaging.

### 5. **Works Everywhere:** 
HTML is supported on all devices and browsers, whether you’re on a computer, tablet, or phone.

### 6. **Helps with Search Engines:** 
Well-organized HTML helps search engines like Google understand and find your content, so people can easily find your website.

---


# **Background of HTML**

- **Inventor of HTML:** Tim Berners-Lee in 1991.
- **Purpose of HTML:**
  - Designed to structure documents for sharing on the World Wide Web.
  - Allows users to navigate content using links.
- **Evolution of HTML:**
  - **HTML 1.0 (1993):** The first version, very basic.
  - **HTML 2.0 (1995):** Added forms and more tags.
  - **HTML 4.01 (1999):** Improved multimedia and table features.
  - **HTML5 (2014):** Modern standard that introduced new features like video, audio, and canvas support.
---

## **Why HTML?**

1. **Web Foundation:** All websites use HTML for their basic structure.
2. **Cross-Platform:** HTML works on all devices (mobile, desktop, etc.).
3. **Easy to Learn:** Simple syntax makes it beginner-friendly.
4. **Universal Browser Support:** HTML is compatible with all modern browsers.
5. **Integration:** HTML is the starting point for further web development involving interactivity (JavaScript) or design (CSS).
---

HTML consists of **elements** represented by **tags** that define how content should appear in a web browser.

## Key Features of HTML

### 1. **Markup Language**:
 HTML uses "tags" to define elements. Tags are special keywords enclosed in angle brackets (`< >`) that tell the browser how to interpret the content.
### Example: 
`<p>` for paragraphs, `<h1>` for headings.
   
### 2. **Plain Text**: 
HTML files are written in plain text and can be created using any text editor.

### 3. **Open Standard**: 
HTML is maintained by the World Wide Web Consortium (W3C), ensuring it is free and accessible for everyone.

---

## Basic Structure of an HTML Document

Every HTML document follows a basic structure:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Page Title</title>
  </head>
  <body>
    <h1>Welcome to HTML</h1>
    <p>This is a paragraph.</p>
  </body>
</html>
```

## Output:
 Displays "Welcome to HTML" as a heading and "This is a paragraph." as a paragraph in a browser.


## Key Features of HTML

### 3. **Not Case-Sensitive**: 
HTML is not case-sensitive, so `<H1>` is the same as `<h1>`. However, it is a good practice to write tags in lowercase for consistency.
   
### 4. **Plain Text Format**: 
HTML files are simple text files with the `.html` or `.htm` extension. You can edit them with any text editor.

### 5. **Extensible**: 
HTML evolves with web standards. Modern versions, like HTML5, support advanced features like multimedia playback and semantic elements.

### 6. **Free and Open**: 
HTML is free to use and maintained by the World Wide Web Consortium (W3C), making it accessible to everyone.

---

## Basic Structure of an HTML Document

A simple HTML document follows this structure:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Page Title</title>
  </head>
  <body>
    <H1>Welcome to HTML</H1>
    <P>This is a paragraph explaining HTML.</P>
    <a href="https://example.com">Click here to learn more!</a>
  </body>
</html>
```

## Output: 
Displays "Welcome to HTML" as a heading and "This is a paragraph explaining HTML." as a paragraph in a browser.

## HTML Boilerplate Code

A boilerplate is a standard, reusable template that helps set up the basic structure of a web page. It includes the essential elements needed to create a well-formed HTML document and serves as a starting point for most webpages.

Basic HTML Boilerplate Code:

- In index.html file the shortcutkey for Boilerplate Code is press(shift+!) when we press this the boilerplate code shown here same as this

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page Title</title>
</head>
<body>

    <h1>Welcome to TFT</h1>
    <p>This is an example of an HTML page using the boilerplate code.</p>

</body>
</html>
```

## Output: 
Displays "Welcome to TFT" as a heading and "This is an example of an HTML page using the boilerplate code." as a paragraph in a browser.

## Explanation of Boilerplate Elements:

### 1.`<!DOCTYPE html>:`
This declaration defines the document type and version. It tells the browser that the page is written in HTML5, which is the latest standard for HTML.

### 2.`<html lang="en">:`
The opening <html> tag starts the HTML document. The lang="en" attribute specifies that the page content is in English (this helps with search engine optimization and accessibility).

### 3.`<head>:`
The `<head>` section contains meta-information about the page, such as its title, character encoding, and linked resources (like CSS and JavaScript files).

### 4.`<meta charset="UTF-8">`:
 Specifies the character encoding used by the document. UTF-8 is a popular encoding that supports most characters and symbols from different languages.

### 5.`<meta name="viewport" content="width=device-width, initial-scale=1.0">:`
 This meta tag makes the page mobile-friendly by controlling the layout on mobile devices. It sets the width of the viewport to match the device’s screen width.

### 6.`<title>`:
This tag specifies the title of the webpage, which appears in the browser tab. The title is also used by search engines.

### 7.`<link rel="stylesheet" href="styles.css">`:
This tag links an external CSS stylesheet (in this case, styles.css) that controls the appearance and layout of the webpage. It's placed in the <head> section.

### 8.`<body>`:
The `<body>` tag contains the visible content of the webpage (like text, images, and other elements). It is the main section where all the content displayed to the user goes.


## Conclusion

HTML is an essential building block for creating web pages. It defines the structure and content of a webpage, which can then be styled using CSS and made interactive using JavaScript. Understanding HTML’s syntax and conventions is fundamental to web development, and using the proper boilerplate code ensures that your web pages have a solid foundation. By writing HTML in a clear and consistent manner, you create pages that are easy to maintain, readable, and accessible to all users.

This document provides an overview of the key concepts and syntax of HTML, offering a solid introduction to anyone looking to understand web development better.