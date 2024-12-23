## **Table of Contents**
1. [What is CSS? Explain types of CSS.](#1-what-is-css-explain-types-of-css)
2. [Explain Anchor Tag with Example.](#2-explain-anchor-tag-with-example)
3. [Explain Ordered and Unordered Lists with Examples.](#3-explain-ordered-and-unordered-lists-with-examples)
4. [Explain Background-Image in CSS with Example.](#4-explain-background-image-in-css-with-example)
5. [Explain Text Decoration Property in CSS with Example.](#5-explain-text-decoration-property-in-css-with-example)
6. [Explain Z-Index with Example.](#6-explain-z-index-with-example)
7. [What is HREF? Demonstrate how to traverse between pages.](#7-what-is-href-demonstrate-how-to-traverse-between-pages)
8. [Explain Padding and Margin with Examples.](#8-explain-padding-and-margin-with-examples)
9. [Explain Client & Server-Side Image Mapping with Examples.](#9-explain-client-server-side-image-mapping-with-examples)
10. [Explain Border Property with Examples.](#10-explain-border-property-with-examples)
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


## **Table of Contents**
1. [What is CSS? Explain types of CSS.](#1-what-is-css-explain-types-of-css)
2. [Explain Anchor Tag with Example.](#2-explain-anchor-tag-with-example)
3. [Explain Ordered and Unordered Lists with Examples.](#3-explain-ordered-and-unordered-lists-with-examples)


---

### **4. Explain Background-Image in CSS with Example.**

**Definition:**
The `background-image` property in CSS is used to set an image as the background for an HTML element. It can be customized with additional properties like `background-repeat`, `background-size`, and `background-position` to control how the image is displayed.

**HTML Script:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Background Image Example</title>
    <style>
        body {
            background-image: url("background.jpg");
            background-repeat: no-repeat;
            background-size: cover;
        }
    </style>
</head>
<body>
    <h1>Background Image Example</h1>
</body>
</html>
```

**Output:**
The webpage background will display the image (`background.jpg`) stretched to fill the viewport with no repetition.

⇧ [Back to Table of Contents](#table-of-contents)

---

### **5. Explain Text Decoration Property in CSS with Example.**

**Definition:**
The `text-decoration` property specifies how text should appear, such as adding underlines, overlines, line-throughs, or no decoration at all.

**HTML Script:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Text Decoration Example</title>
    <style>
        .underline {
            text-decoration: underline;
        }
        .line-through {
            text-decoration: line-through;
        }
        .none {
            text-decoration: none;
        }
    </style>
</head>
<body>
    <p class="underline">This text is underlined.</p>
    <p class="line-through">This text has a line through it.</p>
    <p class="none">This text has no decoration.</p>
</body>
</html>
```

**Output:**
1. The first paragraph has an underline.
2. The second paragraph has a line through it.
3. The third paragraph has no decoration.

⇧ [Back to Table of Contents](#table-of-contents)

---

### **6. Explain Z-Index with Example.**

**Definition:**
The `z-index` property in CSS specifies the stack order of elements. Elements with a higher `z-index` value will appear in front of those with a lower value when they overlap.

**HTML Script:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Z-Index Example</title>
    <style>
        .box1 {
            position: absolute;
            z-index: 2;
            background-color: red;
            width: 100px;
            height: 100px;
        }
        .box2 {
            position: absolute;
            z-index: 1;
            background-color: blue;
            width: 100px;
            height: 100px;
            top: 20px;
            left: 20px;
        }
    </style>
</head>
<body>
    <div class="box1"></div>
    <div class="box2"></div>
</body>
</html>
```

**Output:**
The red box appears on top of the blue box because it has a higher `z-index` value.

⇧ [Back to Table of Contents](#table-of-contents)

---

### **7. What is HREF? Demonstrate how to traverse between pages.**

**Definition:**
The `href` attribute in the `<a>` tag specifies the URL or path to a destination. It can link to other pages, external websites, or specific sections of the same page.

**HTML Script:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HREF Example</title>
</head>
<body>
    <a href="about.html">Go to About Page</a>
    <a href="#section1">Jump to Section 1</a>

    <h2 id="section1">Section 1</h2>
    <p>This is Section 1 of the same page.</p>
</body>
</html>
```

**Output:**
1. The first link navigates to the `about.html` page.
2. The second link scrolls to Section 1 of the current page.

⇧ [Back to Table of Contents](#table-of-contents)

---



### **8. Explain Padding and Margin with Examples.**

**Definition:**
- **Padding**: The space between the content of an element and its border.
- **Margin**: The space outside the border of an element, separating it from other elements.

**HTML Script:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Padding and Margin</title>
    <style>
        .box {
            border: 2px solid black;
            padding: 20px;
            margin: 10px;
        }
    </style>
</head>
<body>
    <div class="box">This box has padding and margin.</div>
</body>
</html>
```

**Output:**
- Padding creates a space of 20px inside the border, around the content.
- Margin creates a 10px gap outside the border.

⇧ [Back to Table of Contents](#table-of-contents)

---

### **9. Explain Client & Server-Side Image Mapping with Examples.**

**Definition:**
- **Client-Side Mapping**: Defines clickable areas on an image that link to different destinations using the `<map>` and `<area>` tags. Handled by the browser.
- **Server-Side Mapping**: Relies on server scripts to process the click and redirect appropriately.

**HTML Script for Client-Side Mapping:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Mapping</title>
</head>
<body>
    <img src="image.jpg" usemap="#map" alt="Mapped Image">
    <map name="map">
        <area shape="rect" coords="34,44,270,350" href="page1.html" alt="Page 1">
        <area shape="circle" coords="337,300,44" href="page2.html" alt="Page 2">
    </map>
</body>
</html>
```

**Output:**
- Clicking on specific regions of the image redirects to different pages (`page1.html` and `page2.html`).

⇧ [Back to Table of Contents](#table-of-contents)

---

### **10. Explain Border Property with Examples.**

**Definition:**
The `border` property in CSS is used to define the style, width, and color of an element's border.

**HTML Script:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Border Example</title>
    <style>
        .box {
            border: 5px solid red;
            width: 200px;
            height: 100px;
        }
    </style>
</head>
<body>
    <div class="box">This box has a red border.</div>
</body>
</html>
```

**Output:**
The element displays a red border with a width of 5px.

⇧ [Back to Table of Contents](#table-of-contents)

---


