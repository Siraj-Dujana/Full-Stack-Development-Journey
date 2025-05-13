# Day 03 – Inline vs Block, div & span, Semantic HTML, Entities, Emmet


📌 **Topics Covered**
- Inline vs Block Elements
- `<div>` and `<span>`
- Semantic vs Non-Semantic Tags
- HTML Entities
- Emmet Abbreviations



## 🧠 Notes

### 1. Inline vs Block Elements

**Block-level Elements**
- Start on a new line and take up full width.
- Common block elements: `<div>`, `<p>`, `<h1>` to `<h6>`, `<ul>`, `<ol>`, `<li>`, `<section>`, etc.

**Inline Elements**
- Do not start on a new line. They only take up as much width as needed.
- Common inline elements: `<span>`, `<a>`, `<strong>`, `<em>`, `<img>`, etc.

📌 *Tip*: Block elements can contain inline elements, but not vice versa (in most cases).


### 2. `<div>` and `<span>`

 **`<div>`**: A generic **block-level** container used for layout or grouping elements.
  ```html
  <div class="container">
    <p>This is inside a div.</p>
  </div>
````

* **`<span>`**: A generic **inline-level** container used to style parts of text.

  ```html
  <p>This is a <span style="color:red;">red</span> word.</p>
  ```

---

### 3. Semantic vs Non-Semantic Tags

* **Semantic Tags**: Clearly describe their meaning.
  Examples: `<header>`, `<footer>`, `<article>`, `<section>`, `<nav>`, `<main>`, `<aside>`

* **Non-Semantic Tags**: Do not convey meaning.
  Examples: `<div>`, `<span>`

✅ *Why use semantic tags?*

* Better accessibility
* SEO friendly
* Easier to maintain and understand

---

### 4. HTML Entities

Used to display reserved characters in HTML.

| Character   | Entity Code | Description        |
| ----------- | ----------- | ------------------ |
| `<`         | `&lt;`      | Less than          |
| `>`         | `&gt;`      | Greater than       |
| `&`         | `&amp;`     | Ampersand          |
| `"`         | `&quot;`    | Double quote       |
| `'`         | `&apos;`    | Single quote       |
| `©`         | `&copy;`    | Copyright          |
| `®`         | `&reg;`     | Registered mark    |
| ` ` (space) | `&nbsp;`    | Non-breaking space |

---

### 5. Emmet Abbreviations

**Emmet** is a shorthand syntax used in code editors like VS Code to quickly write HTML.

| Emmet Abbreviation | Output                                 |
| ------------------ | -------------------------------------- |
| `div`              | `<div></div>`                          |
| `ul>li*3`          | `<ul><li></li><li></li><li></li></ul>` |
| `p{Hello}`         | `<p>Hello</p>`                         |
| `.class`           | `<div class="class"></div>`            |
| `#id`              | `<div id="id"></div>`                  |
| `a:link`           | `<a href="http://"></a>`               |

✅ *Use Emmet to boost productivity when writing HTML structure.*

---
