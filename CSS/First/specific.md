# CSS Specificity Algorithm Explained

When multiple CSS rules target the same HTML element, **specificity** is the way the browser decides which rule to apply.

## 📘 What is Specificity?

Each CSS selector has a **specificity value**, calculated based on the types of selectors used. The browser compares these values to determine which style should be applied.

Specificity is written as a four-part value:
**(a, b, c, d)**

- **a** → Inline styles (e.g. `style="..."` in HTML)
- **b** → Number of ID selectors (`#id`)
- **c** → Number of class selectors (`.class`), attribute selectors (`[type="text"]`), and pseudo-classes (`:hover`, `:focus`, etc.)
- **d** → Number of element selectors (`div`, `h1`, etc.) and pseudo-elements (`::before`, `::after`)

---

## 📊 Specificity Examples

```css
/* Specificity: (0, 1, 0, 0) */
#header {
  color: red;
}

/* Specificity: (0, 0, 2, 0) */
.container .title {
  color: blue;
}

/* Specificity: (0, 0, 0, 1) */
h1 {
  color: green;
}

/* Inline styles have the highest specificity: (1, 0, 0, 0) */
<div style="color: purple;"></div>
```
