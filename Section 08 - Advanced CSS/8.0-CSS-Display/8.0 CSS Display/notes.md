
# CSS Display Properties: `inline`, `block`, and `inline-block`

CSS provides different `display` properties to control how elements are rendered on a webpage. Let’s explore three common display types:

## 1. **`inline`**
- **What is it?**  
  An element with `display: inline;` is laid out **in a line**, like text. It does not start on a new line, and it only takes up as much width as its content.
  
- **Key Features:**
  - Does **not** start on a new line.
  - Width and height properties **don't work**.
  - Margins and paddings **work only horizontally** (left and right).

- **Example:**
  ```html
  <span style="display: inline;">This is inline.</span>
  ```

- **Use Case:**  
  Best for text-like elements, such as `<span>`, `<a>`, or `<strong>`.

## 2. **`block`**
- **What is it?**  
  An element with `display: block;` takes up the **full width** of its container, starting on a new line. It stretches horizontally as far as it can.

- **Key Features:**
  - Always starts on a new line.
  - You can set **width** and **height**.
  - Margins and paddings work in all directions (top, right, bottom, left).

- **Example:**
  ```html
  <div style="display: block;">This is a block element.</div>
  ```

- **Use Case:**  
  Best for structural elements, such as `<div>`, `<header>`, or `<footer>`.

## 3. **`inline-block`**
- **What is it?**  
  An element with `display: inline-block;` combines features of both inline and block elements. It is laid out in a line like `inline`, but you can set its width and height like `block`.

- **Key Features:**
  - Does **not** start on a new line.
  - You can set **width** and **height**.
  - Margins and paddings work in all directions.

- **Example:**
  ```html
  <div style="display: inline-block;">This is inline-block.</div>
  ```

- **Use Case:**  
  Best for elements that you want to sit side by side but still control their size, like buttons or images.

---
With these display properties, you can control the layout of your elements effectively.
