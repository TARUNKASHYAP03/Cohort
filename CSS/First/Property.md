**complete and clean Markdown document** for `block`, `inline`, and `inline-block` in CSS — fully written, properly formatted, and easy to understand for any beginner or intermediate developer.

---

```md
# CSS Display: `block` vs `inline` vs `inline-block`

In CSS, the `display` property defines how an HTML element should behave in the layout. The three most commonly used display types are:

- `block`
- `inline`
- `inline-block`

Each of them behaves differently in terms of width, height, line flow, and spacing.

---

## 🧱 1. `display: block`

Block-level elements start on a **new line** and take up the **full width** of their parent container by default.

### ✅ Key Characteristics:
- Always starts on a new line
- Expands to fill the full width available
- Allows setting of `width`, `height`, `margin`, and `padding`
- Can contain other block or inline elements

### 📦 Common Examples:
- `<div>`
- `<p>`
- `<h1>` to `<h6>`
- `<section>`, `<article>`, `<header>`, `<footer>`

### 💡 Example:
```html
<div style="background-color: lightblue; width: 300px;">I am a block element</div>
```

---

## 🧵 2. `display: inline`

Inline elements do **not** start on a new line. They flow along with the surrounding text and only take up as much width as their content requires.

### ✅ Key Characteristics:
- Does not break to a new line
- Width and height cannot be manually set
- Only horizontal margin and padding are respected
- Used mainly for text formatting

### 📦 Common Examples:
- `<span>`
- `<a>`
- `<strong>`, `<em>`, `<b>`, `<i>`

### 💡 Example:
```html
<span style="background-color: yellow;">I am an inline element</span>
```

---

## 🔀 3. `display: inline-block`

`inline-block` combines the best features of `inline` and `block`.

It does **not** start on a new line like `inline`, but **you can set** `width`, `height`, `padding`, and `margin` just like a block-level element.

### ✅ Key Characteristics:
- Stays in line with surrounding text (like inline)
- Supports full box model (like block)
- Useful for layouting items side-by-side with size control

### 📦 Common Use Cases:
- Custom buttons
- Cards or badges
- Icons with labels

### 💡 Example:
```html
<div style="display: inline-block; width: 150px; background-color: pink;">Inline-block element</div>
```

---

## 📊 Comparison Table

| Feature/Behavior         | `block`         | `inline`        | `inline-block`    |
|--------------------------|------------------|------------------|--------------------|
| Starts on new line       | ✅ Yes           | ❌ No            | ❌ No              |
| Takes full width         | ✅ Yes           | ❌ No            | ❌ No              |
| Can set `width`/`height` | ✅ Yes           | ❌ No            | ✅ Yes             |
| Respects all padding     | ✅ Yes           | ❌ Partial        | ✅ Yes             |
| Can contain block elements | ✅ Yes         | ❌ No            | ✅ Yes             |
| Best for                 | Page structure/layout | Text formatting | Buttons, cards, badges |

---

## 📝 Summary

- Use **`block`** when you want elements to break to a new line and fill their container — great for layout sections.
- Use **`inline`** for styling small pieces of text that stay within the line flow.
- Use **`inline-block`** when you need the layout flexibility of `block` but want to keep elements on the same line.

---

Understanding these display types helps you structure your webpage effectively and style elements with proper control over spacing and alignment.
```

---

✅