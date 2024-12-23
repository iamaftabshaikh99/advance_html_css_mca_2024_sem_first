## **Table of Contents**
1. [What is CSS? Explain types of CSS.](#1-what-is-css-explain-types-of-css)
2. [Explain Anchor Tag with Example.](#2-explain-anchor-tag-with-example)
3. [Explain Ordered and Unordered Lists with Examples.](#3-explain-ordered-and-unordered-lists-with-examples)

---

### **1. What is CSS? Explain types of CSS.**

**Definition:**
CSS (Cascading Style Sheets) is a language used to style and layout web pages, including adjusting colors, fonts, and positioning elements. CSS separates content (HTML) from design, enhancing the flexibility and maintainability of web design.

**Types of CSS:**
1. **Inline CSS**: Applied directly to an HTML element using the `style` attribute.
2. **Internal CSS**: Defined within a `<style>` tag in the HTML `<head>`.
3. **External CSS**: Written in a separate file with a `.css` extension and linked to the HTML.

**HTML Script:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Types</title>
    <style>
        /* Internal CSS */
        p.internal {
            color: blue;
        }
    </style>
</head>
<body>
    <!-- Inline CSS -->
    <p style="color: red;">This is Inline CSS.</p>

    <!-- Internal CSS -->
    <p class="internal">This is Internal CSS.</p>

    <!-- External CSS -->
    <link rel="stylesheet" href="styles.css">
    <p class="external">This is External CSS (styles.css file required).</p>
</body>
</html>
```

**Output:**
1. The first paragraph appears in red (inline styling).
2. The second paragraph appears in blue (internal styling).
3. The third paragraph relies on the external stylesheet.

⇧ [Back to Table of Contents](#table-of-contents)

---

### **2. Explain Anchor Tag with Example.**

**Definition:**
The `<a>` (anchor) tag in HTML is used to create hyperlinks that connect to other web pages, files, or locations within the same page. It can also open email links or download files.

**Key Attributes:**
- `href`: Specifies the URL or path of the link.
- `target`: Determines where the link opens (e.g., `_blank` for a new tab).

**HTML Script:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anchor Tag Example</title>
</head>
<body>
    <a href="https://www.w3schools.com" target="_blank">Visit W3Schools</a>
    <br>
    <a href="mailto:example@mail.com">Send an Email</a>
</body>
</html>
```

**Output:**
1. The first link opens the W3Schools website in a new tab.
2. The second link opens the user’s email client to send an email.

⇧ [Back to Table of Contents](#table-of-contents)

---

### **3. Explain Ordered and Unordered Lists with Examples.**

**Definition:**
HTML lists are used to group related items. An ordered list displays items in a specific sequence using numbers, while an unordered list uses bullet points for items without sequence.

**HTML Script:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lists Example</title>
</head>
<body>
    <h3>Ordered List</h3>
    <ol>
        <li>Step 1</li>
        <li>Step 2</li>
    </ol>

    <h3>Unordered List</h3>
    <ul>
        <li>Item A</li>
        <li>Item B</li>
    </ul>
</body>
</html>
```

**Output:**
1. The ordered list displays items numbered as `1, 2`.
2. The unordered list displays items with bullets.

⇧ [Back to Table of Contents](#table-of-contents)

---
