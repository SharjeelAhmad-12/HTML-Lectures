# Inline and Block-Level Elements in HTML

## Block-Level Elements

Block-level elements take up the full width of their container and start on a new line. These elements can contain other block-level and inline elements.

### Common Block-Level Elements:

- `<div>` — A generic container for grouping content.
- `<p>` — Defines a paragraph of text.
- `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, `<h6>` — Define headings (with `<h1>` being the most important).
- `<section>` — Represents a section of content that has its own theme.
- `<article>` — Represents independent content, like a blog post or news article.
- `<header>` — Represents a header section of a document or a section.
- `<footer>` — Represents the footer section of a document or a section.
- `<nav>` — Represents a navigation section, typically links to other pages or sections.
- `<aside>` — Represents content that is tangentially related to the content around it (like a sidebar).
- `<main>` — Represents the main content of the document, excluding headers, footers, and sidebars.
- `<form>` — Defines an HTML form used to collect user input.
- `<table>` — Defines a table.
- `<ul>`, `<ol>`, `<li>` — Define unordered (bulleted) and ordered (numbered) lists.
- `<dl>`, `<dt>`, `<dd>` — Define a description list, description term, and description definition, respectively.
- `<blockquote>` — Represents a block of text quoted from another source.
- `<hr>` — Represents a thematic break (horizontal rule), often used to separate content.
- `<address>` — Represents contact information.
- `<figure>`, `<figcaption>` — Represents a figure (e.g., an image) and its caption.
- `<details>`, `<summary>` — Represents a disclosure widget from which the user can obtain additional information.

## Inline Elements

Inline elements do not start on a new line and take up only as much width as necessary. They are used for styling or modifying specific parts of content within block-level elements.

### Common Inline Elements:

- `<a>` — Defines a hyperlink.
- `<span>` — A generic container used to style a part of a text or content.
- `<img>` — Embeds an image.
- `<strong>` — Defines important text, typically rendered in bold.
- `<em>` — Defines emphasized text, typically rendered in italics.
- `<b>` — Defines bold text (without emphasizing importance).
- `<i>` — Defines italicized text (without emphasizing importance).
- `<u>` — Defines underlined text.
- `<code>` — Defines a piece of computer code.
- `<s>` — Defines text that is no longer relevant or accurate (strikethrough).
- `<sub>` — Defines subscript text.
- `<sup>` — Defines superscript text.
- `<small>` — Defines smaller text.
- `<mark>` — Defines highlighted text.
- `<q>` — Defines a short inline quotation.
- `<abbr>` — Defines an abbreviation or acronym.
- `<cite>` — Defines the title of a creative work.
- `<dfn>` — Represents a term being defined.
- `<time>` — Represents a specific time or date.
- `<var>` — Represents a variable in programming or mathematical expressions.
- `<wbr>` — Defines a possible line break opportunity within text.
- `<span>` — A generic inline container for styling purposes.

## How to Check if an Element is Inline or Block-Level

### 1. **Using Browser Developer Tools:**

- Open the browser's developer tools (usually by pressing `F12` or `Right-click > Inspect`).
- Select the element you want to inspect.
- In the **Elements** tab, check the `display` property of the element in the **Styles** pane.
- **Block-level elements** will have `display: block` (or similar, like `display: flex` or `display: grid`).
- **Inline elements** will have `display: inline`.
