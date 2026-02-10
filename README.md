# connorbell133
# Welcome

<div style={{ padding: '20px', backgroundColor: 'lightgrey' }}>
  This is a **Markdown** paragraph inside a <div>.
</div>

---

## Markdown basics

**Bold**, *italic*, ~~strikethrough~~, `inline code`, and a [link](https://example.com).

- Unordered list item 1
- Unordered list item 2

1. Ordered list item 1
2. Ordered list item 2

> Blockquote: MDX combines Markdown with JSX.

---

## HTML elements

<details>
<summary>Click to expand (details/summary)</summary>
Hidden content inside a `<details>` element.
</details>

<table>
  <thead>
    <tr><th>Col A</th><th>Col B</th></tr>
  </thead>
  <tbody>
    <tr><td>Cell 1</td><td>Cell 2</td></tr>
    <tr><td>Cell 3</td><td>Cell 4</td></tr>
  </tbody>
</table>

<p>Plain <strong>HTML</strong> paragraph with <em>nested</em> tags and <code>code</code>.</p>

<span style="color: blue;">Colored span</span> and <kbd>keyboard</kbd> text.

---

## MDX / JSX

Inline expression: {2 + 2} is 4.

<div className="callout">
  JSX with **Markdown** inside and expression: {"hello".toUpperCase()}.
</div>

<div style={{ padding: 16, border: '1px solid #ccc', borderRadius: 8 }}>
  Inline style object: padding and border.
</div>

<ul>
  <li>List from HTML</li>
  <li>Another item</li>
</ul>

---

## Code blocks

```js
const greet = (name) => `Hello, ${name}!`;
greet('MDX');
```

```html
<!-- Raw HTML in fenced block -->
<p>Fenced code block</p>
```