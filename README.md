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
11. [Explain GET and POST Methods with Examples.](#11-explain-get-and-post-methods-with-examples)
12. [Explain Overflow in CSS with Example.](#12-explain-overflow-in-css-with-example)
13. [Explain Vertical Align in CSS with Example.](#13-explain-vertical-align-in-css-with-example)
14. [Explain Background-Repeat in CSS with Example.](#14-explain-background-repeat-in-css-with-example)
15. [Explain CSS Selectors with Examples.](#15-explain-css-selectors-with-examples)
16. [Explain Difference Between Div and Span.](#16-explain-difference-between-div-and-span)
    

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

Here’s the continuation with detailed answers following the priority set in the question bank. I'll focus on high-priority questions first and ensure the answers are comprehensive and detailed.

---

### **11. Explain GET and POST Methods with Examples.**

**Definition:**
The `GET` and `POST` methods are HTTP request methods used to send data from the client to the server.

1. **GET Method**:
   - Sends data as part of the URL.
   - Typically used for retrieving data.
   - Not secure, as data is visible in the URL.
   - Limited data size.

2. **POST Method**:
   - Sends data in the HTTP request body.
   - Typically used for submitting data (e.g., forms).
   - More secure than `GET`, as data is not visible in the URL.
   - Allows sending large amounts of data.

**HTML Script for GET Method:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GET Method Example</title>
</head>
<body>
    <form method="GET" action="submit.php">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name">
        <button type="submit">Submit</button>
    </form>
</body>
</html>
```

**HTML Script for POST Method:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>POST Method Example</title>
</head>
<body>
    <form method="POST" action="submit.php">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name">
        <button type="submit">Submit</button>
    </form>
</body>
</html>
```

**Output:**
1. The `GET` form sends data as a query string (e.g., `submit.php?name=John`).
2. The `POST` form sends data securely in the request body.

⇧ [Back to Table of Contents](#table-of-contents)

---

### **12. Explain Overflow in CSS with Example.**

**Definition:**
The `overflow` property in CSS controls how content is displayed when it exceeds the size of its container. It defines whether the overflowed content should be clipped, scrolled, or visible.

**Values:**
1. **visible** (default): Content overflows outside the container.
2. **hidden**: Overflowing content is clipped.
3. **scroll**: Adds scrollbars for overflowing content.
4. **auto**: Automatically adds scrollbars if needed.

**HTML Script:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Overflow Example</title>
    <style>
        .box {
            width: 200px;
            height: 100px;
            border: 2px solid black;
            overflow: scroll;
        }
    </style>
</head>
<body>
    <div class="box">
        This is a long paragraph that exceeds the size of its container. Scrollbars will appear to view the hidden content.
    </div>
</body>
</html>
```

**Output:**
A box with scrollbars appears, allowing the user to scroll and view hidden content.

⇧ [Back to Table of Contents](#table-of-contents)

---


### **13. Explain Vertical Align in CSS with Example.**

**Definition:**
The `vertical-align` property in CSS controls the vertical alignment of inline or table-cell elements.

**Common Values:**
1. **baseline**: Default. Aligns with the baseline of the parent element.
2. **top**: Aligns the top of the element with the top of the parent element.
3. **middle**: Aligns the element in the middle of the parent element.
4. **bottom**: Aligns the bottom of the element with the bottom of the parent element.

**HTML Script:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vertical Align Example</title>
    <style>
        .box {
            display: inline-block;
            width: 100px;
            height: 100px;
            background-color: lightblue;
            vertical-align: middle;
        }
        .text {
            display: inline-block;
            vertical-align: middle;
        }
    </style>
</head>
<body>
    <div class="box"></div>
    <span class="text">Aligned Middle</span>
</body>
</html>
```

**Output:**
The box and text are vertically aligned in the middle of their parent container.

⇧ [Back to Table of Contents](#table-of-contents)

---

### **14. Explain Background-Repeat in CSS with Example.**

**Definition:**
The `background-repeat` property in CSS specifies if and how a background image repeats within an element.

**Values:**
1. **repeat** (default): The background image repeats both horizontally and vertically.
2. **no-repeat**: The background image does not repeat.
3. **repeat-x**: The background image repeats horizontally.
4. **repeat-y**: The background image repeats vertically.
5. **space**: The background image is repeated without being clipped, adding spacing between repetitions.
6. **round**: The background image is stretched or shrunk to fit the element without gaps.

**HTML Script:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Background Repeat Example</title>
    <style>
        .box {
            width: 300px;
            height: 200px;
            background-image: url("pattern.png");
            background-repeat: repeat-x;
        }
    </style>
</head>
<body>
    <div class="box">Background repeats horizontally.</div>
</body>
</html>
```

**Output:**
The background image repeats horizontally across the width of the box.

⇧ [Back to Table of Contents](#table-of-contents)

---

### **15. Explain CSS Selectors with Examples.**

**Definition:**
CSS Selectors are patterns used to select and style specific HTML elements.

**Types of Selectors:**
1. **Universal Selector (`*`)**: Targets all elements.
2. **Type Selector (`element`)**: Targets elements by their tag name (e.g., `p` for all `<p>` tags).
3. **Class Selector (`.class`)**: Targets elements with a specific class attribute.
4. **ID Selector (`#id`)**: Targets a specific element with a unique ID.
5. **Group Selector (`A, B`)**: Targets multiple elements.
6. **Descendant Selector (`A B`)**: Targets elements nested within another element.
7. **Attribute Selector (`[attr=value]`)**: Targets elements with specific attributes.

**HTML Script:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Selectors Example</title>
    <style>
        * { margin: 0; padding: 0; } /* Universal Selector */
        h1 { color: blue; } /* Type Selector */
        .highlight { background-color: yellow; } /* Class Selector */
        #unique { font-weight: bold; } /* ID Selector */
        p, span { color: green; } /* Group Selector */
        div span { font-style: italic; } /* Descendant Selector */
        a[href="https://example.com"] { text-decoration: underline; } /* Attribute Selector */
    </style>
</head>
<body>
    <h1>Type Selector Example</h1>
    <p class="highlight">Class Selector Example</p>
    <p id="unique">ID Selector Example</p>
    <div>
        <span>Descendant Selector Example</span>
    </div>
    <a href="https://example.com">Attribute Selector Example</a>
</body>
</html>
```

**Output:**
- All elements have `margin` and `padding` set to `0`.
- The `<h1>` tag is styled in blue.
- The `<p>` with class `highlight` has a yellow background.
- The `<p>` with ID `unique` is bold.
- `<p>` and `<span>` tags are green.
- `<span>` inside `<div>` is italic.
- Links to `https://example.com` are underlined.

⇧ [Back to Table of Contents](#table-of-contents)

---

### **16. Explain Difference Between Div and Span.**

**Definition:**
- `<div>`: A block-level element used to group content into sections.
- `<span>`: An inline-level element used to style parts of a text.

| **Aspect**       | **<div>**                                  | **<span>**                                |
|-------------------|--------------------------------------------|-------------------------------------------|
| **Type**          | Block-level element                       | Inline-level element                      |
| **Use Case**      | Grouping larger sections of content        | Styling small portions of text            |
| **Default Behavior** | Starts on a new line                     | Continues on the same line                |
| **Example**       | `<div>` for containers or layout sections. | `<span>` for inline text formatting.      |

**HTML Script:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Div vs Span Example</title>
    <style>
        div { border: 1px solid black; margin: 10px; padding: 10px; }
        span { color: red; font-weight: bold; }
    </style>
</head>
<body>
    <div>
        This is a <span>block-level</span> container.
    </div>
    <p>
        Inline text with a <span>highlighted word</span>.
    </p>
</body>
</html>
```

**Output:**
- The `<div>` creates a bordered container with padding and margin.
- The `<span>` applies inline styling (red color, bold text) to specific words.

⇧ [Back to Table of Contents](#table-of-contents)

---

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
11. [Explain GET and POST Methods with Examples.](#11-explain-get-and-post-methods-with-examples)
12. [Explain Overflow in CSS with Example.](#12-explain-overflow-in-css-with-example)
13. [Explain Vertical Align in CSS with Example.](#13-explain-vertical-align-in-css-with-example)
14. [Explain Background-Repeat in CSS with Example.](#14-explain-background-repeat-in-css-with-example)
15. [Explain CSS Selectors with Examples.](#15-explain-css-selectors-with-examples)
16. [Explain Difference Between Div and Span.](#16-explain-difference-between-div-and-span)


---

### **17. Explain Position Property with Examples.**

**Definition:**
The `position` property in CSS specifies the type of positioning method used for an element. It determines how an element is placed in the document flow and whether it responds to scrolling.

**Values:**
1. **static**: Default positioning; the element is positioned according to the normal flow.
2. **relative**: Positioned relative to its normal position.
3. **absolute**: Positioned relative to the nearest positioned ancestor.
4. **fixed**: Positioned relative to the viewport and does not move when scrolling.
5. **sticky**: Switches between relative and fixed positioning based on the scroll position.

**HTML Script:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Position Property Example</title>
    <style>
        .static { position: static; background-color: lightgray; }
        .relative { position: relative; top: 20px; background-color: lightblue; }
        .absolute { position: absolute; top: 50px; left: 50px; background-color: lightgreen; }
        .fixed { position: fixed; top: 0; right: 0; background-color: lightcoral; }
    </style>
</head>
<body>
    <div class="static">Static Position</div>
    <div class="relative">Relative Position</div>
    <div class="absolute">Absolute Position</div>
    <div class="fixed">Fixed Position</div>
</body>
</html>
```

**Output:**
1. **Static**: Positioned normally within the document flow.
2. **Relative**: Positioned 20px lower than its original position.
3. **Absolute**: Positioned at (50px, 50px) relative to the nearest positioned ancestor.
4. **Fixed**: Always visible at the top-right of the viewport.

⇧ [Back to Table of Contents](#table-of-contents)

---

### **18. Explain Text Decoration in CSS with Example.**

**Definition:**
The `text-decoration` property specifies how text is styled in terms of underlining, overlining, line-through (strikethrough), or none.

**Values:**
1. **none**: Removes all decorations.
2. **underline**: Adds a line below the text.
3. **overline**: Adds a line above the text.
4. **line-through**: Adds a strikethrough.
5. **blink** (deprecated): Makes text blink.

**HTML Script:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Text Decoration Example</title>
    <style>
        .underline { text-decoration: underline; }
        .overline { text-decoration: overline; }
        .line-through { text-decoration: line-through; }
        .none { text-decoration: none; }
    </style>
</head>
<body>
    <p class="underline">This text is underlined.</p>
    <p class="overline">This text has an overline.</p>
    <p class="line-through">This text has a line-through.</p>
    <p class="none">This text has no decoration.</p>
</body>
</html>
```

**Output:**
1. The first paragraph has an underline.
2. The second paragraph has an overline.
3. The third paragraph has a strikethrough.
4. The fourth paragraph has no decoration.

⇧ [Back to Table of Contents](#table-of-contents)

---


