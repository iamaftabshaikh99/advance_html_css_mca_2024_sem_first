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
17. [Explain Position Property with Examples.](#17-explain-position-property-with-examples)
18. [Explain Text Decoration in CSS with Example.](#18-explain-text-decoration-in-css-with-example)
19. [Explain Attribute Selectors with Examples.](#19-explain-attribute-selectors-with-examples)
20. [Explain GET and POST with Examples.](#20-explain-get-and-post-with-examples)
21. [Explain Difference Between Inline, Block, and Inline-Block Elements.](#21-explain-difference-between-inline-block)
22. [Explain Box Model in CSS with Example.](#22-explain-box-model-in-css-with-example)  
23. [Explain the Difference Between Absolute and Relative Positioning in CSS.](#23-explain-the-difference-between-absolute-and-relative-positioning-in-css)  
24. [Explain Float Property in CSS with Example.](#24-explain-float-property-in-css-with-example)  
25. [Explain Difference Between Class and ID Selectors with Examples.](#25-explain-difference-between-class-and-id-selectors-with-examples)
26. [Explain Inline, Internal, and External CSS with Examples.](#26-explain-inline-internal-and-external-css-with-examples)  
27. [Explain Transition Property in CSS with Example.](#27-explain-transition-property-in-css-with-example)  
28. [Explain Difference Between Relative and Fixed Positioning in CSS.](#28-explain-difference-between-relative-and-fixed-positioning-in-css)  
29. [Explain Hover Effects with Examples.](#29-explain-hover-effects-with-examples)
30. [Explain Pseudo-Classes with Examples.](#30-explain-pseudo-classes-with-examples)  
31. [Explain Flexbox and Its Properties with Examples.](#31-explain-flexbox-and-its-properties-with-examples)  
32. [Explain Media Queries with Examples.](#32-explain-media-queries-with-examples)  
33. [Explain Difference Between Em and Rem Units in CSS.](#33-explain-difference-between-em-and-rem-units-in-css)  
34. [Explain Grid Layout in CSS with Examples.](#34-explain-grid-layout-in-css-with-examples)  
35. [Explain Difference Between Visibility and Display in CSS.](#35-explain-difference-between-visibility-and-display-in-css)  
36. [Explain CSS Animations with Examples.](#36-explain-css-animations-with-examples)  
37. [Explain Difference Between Inline and Block Elements.](#37-explain-difference-between-inline-and-block-elements)  




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


### **19. Explain Attribute Selectors with Examples.**

**Definition:**
CSS Attribute Selectors target HTML elements based on the presence, value, or pattern of their attributes.

**Types of Attribute Selectors:**
1. **[attr]**: Selects elements with the specified attribute.
2. **[attr=value]**: Selects elements where the attribute matches the specified value.
3. **[attr~=value]**: Selects elements where the attribute contains the specified word.
4. **[attr|=value]**: Selects elements with a specific value or starting with it.
5. **[attr^=value]**: Selects elements where the attribute starts with the specified value.
6. **[attr$=value]**: Selects elements where the attribute ends with the specified value.
7. **[attr*=value]**: Selects elements where the attribute contains the specified value.

**HTML Script:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Attribute Selectors Example</title>
    <style>
        [title] { color: blue; } /* Any element with a title attribute */
        [title="specific"] { font-weight: bold; } /* Title matches "specific" */
        [href^="https"] { text-decoration: underline; } /* Links starting with "https" */
        [class*="highlight"] { background-color: yellow; } /* Class containing "highlight" */
    </style>
</head>
<body>
    <p title="general">This is a paragraph with a title.</p>
    <p title="specific">This is a bold paragraph.</p>
    <a href="https://example.com">Secure Link</a>
    <p class="text-highlight">Highlighted Text</p>
</body>
</html>
```

**Output:**
1. The first `<p>` with a title attribute is styled in blue.
2. The second `<p>` with the title "specific" is bold.
3. Links starting with `https` are underlined.
4. Text with "highlight" in its class has a yellow background.

⇧ [Back to Table of Contents](#table-of-contents)

---

### **20. Explain GET and POST with Examples.**

This question is already addressed in [11. Explain GET and POST Methods with Examples.](#11-explain-get-and-post-methods-with-examples).

---


### **21. Explain Difference Between Inline, Block, and Inline-Block Elements.**

**Definition:**
HTML elements are categorized into three types based on their default display behavior: **inline**, **block**, and **inline-block**.

| **Property**      | **Inline**                        | **Block**                             | **Inline-Block**                     |
|--------------------|-----------------------------------|---------------------------------------|--------------------------------------|
| **Default Behavior** | Does not start on a new line.    | Always starts on a new line.          | Does not start on a new line.        |
| **Width/Height**   | Cannot set width/height.         | Can set width/height.                | Can set width/height.                |
| **Use Case**       | Styling parts of text.           | Grouping large content sections.      | Combining inline and block behavior. |

**Examples:**
- **Inline**: `<span>`, `<a>`, `<strong>`
- **Block**: `<div>`, `<p>`, `<section>`
- **Inline-Block**: `<button>`, `<img>`

**HTML Script:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Inline, Block, and Inline-Block</title>
    <style>
        .inline { display: inline; background-color: lightblue; }
        .block { display: block; background-color: lightgreen; margin-bottom: 10px; }
        .inline-block { display: inline-block; background-color: lightcoral; width: 100px; height: 50px; }
    </style>
</head>
<body>
    <span class="inline">Inline Element</span>
    <div class="block">Block Element</div>
    <span class="inline-block">Inline-Block Element</span>
</body>
</html>
```

**Output:**
1. The **inline element** appears inline with surrounding text.
2. The **block element** starts on a new line and takes full width.
3. The **inline-block element** appears inline but respects width and height properties.

⇧ [Back to Table of Contents](#table-of-contents)

---

### **22. Explain Box Model in CSS with Example.**

**Definition:**
The **Box Model** in CSS is a fundamental concept that explains how elements are wrapped with a combination of **content**, **padding**, **border**, and **margin**.

**Components of the Box Model:**
1. **Content**: The actual content area.
2. **Padding**: The space between the content and the border.
3. **Border**: The boundary surrounding the padding.
4. **Margin**: The outermost spacing around the element.

**Formula:**
Total Width = Content Width + Padding (left + right) + Border (left + right) + Margin (left + right)  
Total Height = Content Height + Padding (top + bottom) + Border (top + bottom) + Margin (top + bottom)

**HTML Script:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Box Model Example</title>
    <style>
        .box {
            width: 150px;
            height: 100px;
            padding: 20px;
            border: 5px solid black;
            margin: 15px;
            background-color: lightblue;
        }
    </style>
</head>
<body>
    <div class="box">Box Model</div>
</body>
</html>
```

**Output:**
1. The element has a total width of `150px` (content) + `40px` (padding) + `10px` (border) + `30px` (margin) = **230px**.
2. The height is calculated similarly.

⇧ [Back to Table of Contents](#table-of-contents)

---

### **23. Explain the Difference Between Absolute and Relative Positioning in CSS.**

| **Property**        | **Absolute Position**                     | **Relative Position**                     |
|----------------------|-------------------------------------------|-------------------------------------------|
| **Position**         | Relative to the nearest positioned ancestor. | Relative to its normal position in the document flow. |
| **Document Flow**    | Removed from the normal document flow.   | Remains part of the document flow.        |
| **Use Case**         | Ideal for tooltips, modals, or overlays.  | Best for slightly shifting an element from its original position. |

**HTML Script:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Absolute vs Relative Position</title>
    <style>
        .relative {
            position: relative;
            top: 20px;
            left: 10px;
            background-color: lightgreen;
        }
        .absolute {
            position: absolute;
            top: 50px;
            left: 30px;
            background-color: lightcoral;
        }
    </style>
</head>
<body>
    <div class="relative">Relative Position</div>
    <div class="absolute">Absolute Position</div>
</body>
</html>
```

**Output:**
1. The relative element is shifted 20px down and 10px right from its original position.
2. The absolute element is placed at (50px, 30px) relative to the parent or document body.

⇧ [Back to Table of Contents](#table-of-contents)

---

### **24. Explain Float Property in CSS with Example.**

**Definition:**
The `float` property in CSS is used to position an element to the left or right within its container, allowing text or inline elements to wrap around it.

**Values:**
1. **left**: Floats the element to the left.
2. **right**: Floats the element to the right.
3. **none**: Default value, no floating.

**HTML Script:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Float Property Example</title>
    <style>
        .float-left {
            float: left;
            margin-right: 10px;
            width: 100px;
            height: 100px;
            background-color: lightblue;
        }
        .float-right {
            float: right;
            margin-left: 10px;
            width: 100px;
            height: 100px;
            background-color: lightgreen;
        }
    </style>
</head>
<body>
    <div class="float-left">Left Float</div>
    <div class="float-right">Right Float</div>
    <p>This text will wrap around the floated elements.</p>
</body>
</html>
```

**Output:**
- The first div floats to the left, with text wrapping around it.
- The second div floats to the right.

⇧ [Back to Table of Contents](#table-of-contents)

---

### **25. Explain Difference Between Class and ID Selectors with Examples.**

| **Aspect**          | **Class Selector (`.class`)**            | **ID Selector (`#id`)**                 |
|----------------------|------------------------------------------|-----------------------------------------|
| **Uniqueness**       | Can be reused for multiple elements.     | Must be unique for a single element.    |
| **Syntax**           | Starts with a period (`.`).              | Starts with a hash (`#`).               |
| **Use Case**         | Common styling for a group of elements.  | Specific styling for a unique element.  |

**HTML Script:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Class vs ID Selector</title>
    <style>
        .common {
            color: blue;
            font-weight: bold;
        }
        #unique {
            color: red;
            font-style: italic;
        }
    </style>
</head>
<body>
    <p class="common">This is a common style.</p>
    <p id="unique">This is a unique style.</p>
</body>
</html>
```

**Output:**
1. The paragraph with the `common` class is styled in bold blue.
2. The paragraph with the `unique` ID is styled in italic red.

⇧ [Back to Table of Contents](#table-of-contents)

---

### **26. Explain Inline, Internal, and External CSS with Examples.**

**Definition:**
CSS can be applied in three ways:
1. **Inline CSS**: Directly within the HTML element using the `style` attribute.
2. **Internal CSS**: Defined within a `<style>` tag in the HTML document’s `<head>`.
3. **External CSS**: Written in a separate file and linked to the HTML document.

**HTML Script:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Types Example</title>
    <!-- External CSS -->
    <link rel="stylesheet" href="styles.css">
    <style>
        /* Internal CSS */
        .internal {
            color: green;
            font-style: italic;
        }
    </style>
</head>
<body>
    <!-- Inline CSS -->
    <p style="color: red;">This is styled using Inline CSS.</p>
    
    <!-- Internal CSS -->
    <p class="internal">This is styled using Internal CSS.</p>
    
    <!-- External CSS -->
    <p class="external">This is styled using External CSS.</p>
</body>
</html>
```

**Output:**
1. Inline CSS styles the first paragraph in red.
2. Internal CSS styles the second paragraph in green and italic.
3. External CSS applies styles from the linked stylesheet to the third paragraph.

⇧ [Back to Table of Contents](#table-of-contents)

---

### **27. Explain Transition Property in CSS with Example.**

**Definition:**
The `transition` property in CSS allows for smooth changes between property values over a specified duration.

**Key Properties:**
1. `transition-property`: Specifies the property to transition (e.g., `background-color`).
2. `transition-duration`: Duration of the transition (e.g., `1s`).
3. `transition-timing-function`: Specifies the speed curve (e.g., `ease`, `linear`).
4. `transition-delay`: Time before the transition starts (e.g., `0.5s`).

**HTML Script:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Transition Property Example</title>
    <style>
        .box {
            width: 100px;
            height: 100px;
            background-color: blue;
            transition: background-color 1s ease, transform 0.5s;
        }
        .box:hover {
            background-color: red;
            transform: scale(1.2);
        }
    </style>
</head>
<body>
    <div class="box"></div>
</body>
</html>
```

**Output:**
When you hover over the blue box, it changes to red and scales up slightly, with a smooth transition effect.

⇧ [Back to Table of Contents](#table-of-contents)

---

### **28. Explain Difference Between Relative and Fixed Positioning in CSS.**

| **Property**        | **Relative Position**                     | **Fixed Position**                       |
|----------------------|-------------------------------------------|------------------------------------------|
| **Position**         | Relative to its normal position.          | Relative to the viewport.                |
| **Scrolling**        | Moves along with the document.            | Stays fixed, even during scrolling.      |
| **Use Case**         | Shifting elements slightly.               | Sticky headers, floating elements.       |

**HTML Script:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Relative vs Fixed Position</title>
    <style>
        .relative {
            position: relative;
            top: 20px;
            left: 10px;
            background-color: lightblue;
        }
        .fixed {
            position: fixed;
            top: 0;
            right: 0;
            background-color: lightcoral;
            padding: 10px;
        }
    </style>
</head>
<body>
    <div class="relative">Relative Position</div>
    <div class="fixed">Fixed Position</div>
</body>
</html>
```

**Output:**
1. The **relative element** is shifted 20px down and 10px right from its normal position.
2. The **fixed element** remains in the top-right corner of the viewport, even when scrolling.

⇧ [Back to Table of Contents](#table-of-contents)

---

### **29. Explain Hover Effects with Examples.**

**Definition:**
The `:hover` pseudo-class in CSS is used to apply styles to an element when the user hovers over it with a mouse.

**HTML Script:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hover Effects Example</title>
    <style>
        .button {
            padding: 10px 20px;
            background-color: blue;
            color: white;
            text-decoration: none;
            transition: background-color 0.3s ease;
        }
        .button:hover {
            background-color: darkblue;
        }
    </style>
</head>
<body>
    <a href="#" class="button">Hover Me</a>
</body>
</html>
```

**Output:**
When hovering over the button, the background color smoothly changes to dark blue.

⇧ [Back to Table of Contents](#table-of-contents)

---

## **Table of Contents (Updated)**

30. [Explain Pseudo-Classes with Examples.](#30-explain-pseudo-classes-with-examples)  
31. [Explain Flexbox and Its Properties with Examples.](#31-explain-flexbox-and-its-properties-with-examples)  
32. [Explain Media Queries with Examples.](#32-explain-media-queries-with-examples)  
33. [Explain Difference Between Em and Rem Units in CSS.](#33-explain-difference-between-em-and-rem-units-in-css)  

---

### **30. Explain Pseudo-Classes with Examples.**

**Definition:**
Pseudo-classes in CSS define the special state of an element. They allow you to style elements based on user interaction, their position in the document, or specific conditions.

**Examples of Pseudo-Classes:**
1. **`:hover`**: Applies styles when the user hovers over an element.
2. **`:focus`**: Applies styles when an element gains focus (e.g., input fields).
3. **`:nth-child()`**: Targets specific children of a parent element.
4. **`:first-child` and `:last-child`**: Styles the first or last child of a parent.

**HTML Script:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pseudo-Classes Example</title>
    <style>
        a:hover {
            color: red;
        }
        input:focus {
            border: 2px solid blue;
        }
        li:nth-child(2) {
            background-color: lightgray;
        }
    </style>
</head>
<body>
    <a href="#">Hover over me</a>
    <br><br>
    <input type="text" placeholder="Focus on me">
    <ul>
        <li>First Item</li>
        <li>Second Item</li>
        <li>Third Item</li>
    </ul>
</body>
</html>
```

**Output:**
1. The link changes color when hovered.
2. The input field’s border turns blue when focused.
3. The second list item is styled with a gray background.

⇧ [Back to Table of Contents](#table-of-contents)

---

### **31. Explain Flexbox and Its Properties with Examples.**

**Definition:**
The **Flexible Box Layout (Flexbox)** in CSS is a layout model designed for efficient alignment and distribution of items within a container, even when their sizes are dynamic.

**Key Flexbox Properties:**
1. **`display: flex`**: Defines a flex container.
2. **`flex-direction`**: Defines the direction of the main axis (row, column).
3. **`justify-content`**: Aligns items along the main axis (center, space-between).
4. **`align-items`**: Aligns items along the cross axis (stretch, center).
5. **`flex-wrap`**: Wraps items onto multiple lines if necessary.

**HTML Script:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flexbox Example</title>
    <style>
        .container {
            display: flex;
            flex-direction: row;
            justify-content: space-around;
            align-items: center;
            height: 200px;
            background-color: lightblue;
        }
        .item {
            width: 50px;
            height: 50px;
            background-color: coral;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="item">1</div>
        <div class="item">2</div>
        <div class="item">3</div>
    </div>
</body>
</html>
```

**Output:**
The three items are spaced evenly along the main axis and aligned at the center of the container.

⇧ [Back to Table of Contents](#table-of-contents)

---

### **32. Explain Media Queries with Examples.**

**Definition:**
Media queries in CSS enable responsive design by applying styles based on the screen’s size, resolution, or orientation.

**Syntax:**
```css
@media (condition) {
    /* CSS rules */
}
```

**HTML Script:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Media Queries Example</title>
    <style>
        body {
            background-color: lightblue;
        }
        @media (max-width: 600px) {
            body {
                background-color: lightgreen;
            }
        }
    </style>
</head>
<body>
    <h1>Resize the window to see the effect!</h1>
</body>
</html>
```

**Output:**
The background color changes to light green when the viewport width is 600px or smaller.

⇧ [Back to Table of Contents](#table-of-contents)

---

### **33. Explain Difference Between Em and Rem Units in CSS.**

| **Aspect**        | **Em Unit**                               | **Rem Unit**                              |
|--------------------|-------------------------------------------|-------------------------------------------|
| **Definition**     | Relative to the font size of the parent.  | Relative to the root element's font size. |
| **Dependency**     | Depends on the parent element.            | Consistent throughout the document.       |
| **Use Case**       | Useful for nested scaling.                | Preferred for consistent scaling.         |

**HTML Script:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Em vs Rem</title>
    <style>
        html {
            font-size: 16px; /* 1rem = 16px */
        }
        .parent {
            font-size: 20px; /* 1em = 20px */
        }
        .child-em {
            font-size: 1.5em; /* 1.5 * 20px = 30px */
        }
        .child-rem {
            font-size: 1.5rem; /* 1.5 * 16px = 24px */
        }
    </style>
</head>
<body>
    <div class="parent">
        Parent (20px)
        <div class="child-em">Child with Em (30px)</div>
        <div class="child-rem">Child with Rem (24px)</div>
    </div>
</body>
</html>
```

**Output:**
1. The em-based child scales relative to the parent’s font size.
2. The rem-based child scales consistently relative to the root font size.

⇧ [Back to Table of Contents](#table-of-contents)

---


### **30. Explain Pseudo-Classes with Examples.**

**Definition:**
Pseudo-classes in CSS define the special state of an element. They allow you to style elements based on user interaction, their position in the document, or specific conditions.

**Examples of Pseudo-Classes:**
1. **`:hover`**: Applies styles when the user hovers over an element.
2. **`:focus`**: Applies styles when an element gains focus (e.g., input fields).
3. **`:nth-child()`**: Targets specific children of a parent element.
4. **`:first-child` and `:last-child`**: Styles the first or last child of a parent.

**HTML Script:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pseudo-Classes Example</title>
    <style>
        a:hover {
            color: red;
        }
        input:focus {
            border: 2px solid blue;
        }
        li:nth-child(2) {
            background-color: lightgray;
        }
    </style>
</head>
<body>
    <a href="#">Hover over me</a>
    <br><br>
    <input type="text" placeholder="Focus on me">
    <ul>
        <li>First Item</li>
        <li>Second Item</li>
        <li>Third Item</li>
    </ul>
</body>
</html>
```

**Output:**
1. The link changes color when hovered.
2. The input field’s border turns blue when focused.
3. The second list item is styled with a gray background.

⇧ [Back to Table of Contents](#table-of-contents)

---

### **31. Explain Flexbox and Its Properties with Examples.**

**Definition:**
The **Flexible Box Layout (Flexbox)** in CSS is a layout model designed for efficient alignment and distribution of items within a container, even when their sizes are dynamic.

**Key Flexbox Properties:**
1. **`display: flex`**: Defines a flex container.
2. **`flex-direction`**: Defines the direction of the main axis (row, column).
3. **`justify-content`**: Aligns items along the main axis (center, space-between).
4. **`align-items`**: Aligns items along the cross axis (stretch, center).
5. **`flex-wrap`**: Wraps items onto multiple lines if necessary.

**HTML Script:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flexbox Example</title>
    <style>
        .container {
            display: flex;
            flex-direction: row;
            justify-content: space-around;
            align-items: center;
            height: 200px;
            background-color: lightblue;
        }
        .item {
            width: 50px;
            height: 50px;
            background-color: coral;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="item">1</div>
        <div class="item">2</div>
        <div class="item">3</div>
    </div>
</body>
</html>
```

**Output:**
The three items are spaced evenly along the main axis and aligned at the center of the container.

⇧ [Back to Table of Contents](#table-of-contents)

---

### **32. Explain Media Queries with Examples.**

**Definition:**
Media queries in CSS enable responsive design by applying styles based on the screen’s size, resolution, or orientation.

**Syntax:**
```css
@media (condition) {
    /* CSS rules */
}
```

**HTML Script:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Media Queries Example</title>
    <style>
        body {
            background-color: lightblue;
        }
        @media (max-width: 600px) {
            body {
                background-color: lightgreen;
            }
        }
    </style>
</head>
<body>
    <h1>Resize the window to see the effect!</h1>
</body>
</html>
```

**Output:**
The background color changes to light green when the viewport width is 600px or smaller.

⇧ [Back to Table of Contents](#table-of-contents)

---

### **33. Explain Difference Between Em and Rem Units in CSS.**

| **Aspect**        | **Em Unit**                               | **Rem Unit**                              |
|--------------------|-------------------------------------------|-------------------------------------------|
| **Definition**     | Relative to the font size of the parent.  | Relative to the root element's font size. |
| **Dependency**     | Depends on the parent element.            | Consistent throughout the document.       |
| **Use Case**       | Useful for nested scaling.                | Preferred for consistent scaling.         |

**HTML Script:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Em vs Rem</title>
    <style>
        html {
            font-size: 16px; /* 1rem = 16px */
        }
        .parent {
            font-size: 20px; /* 1em = 20px */
        }
        .child-em {
            font-size: 1.5em; /* 1.5 * 20px = 30px */
        }
        .child-rem {
            font-size: 1.5rem; /* 1.5 * 16px = 24px */
        }
    </style>
</head>
<body>
    <div class="parent">
        Parent (20px)
        <div class="child-em">Child with Em (30px)</div>
        <div class="child-rem">Child with Rem (24px)</div>
    </div>
</body>
</html>
```

**Output:**
1. The em-based child scales relative to the parent’s font size.
2. The rem-based child scales consistently relative to the root font size.

⇧ [Back to Table of Contents](#table-of-contents)

---

### **34. Explain Grid Layout in CSS with Examples.**

**Definition:**
CSS Grid Layout is a powerful layout system designed for two-dimensional (rows and columns) web layouts. It allows the placement of items in a grid with explicit control over rows, columns, and gaps.

**Key Properties:**
1. **`display: grid`**: Defines a grid container.
2. **`grid-template-rows` and `grid-template-columns`**: Define the size of rows and columns.
3. **`gap`**: Specifies the spacing between grid items.
4. **`grid-area`**: Allows an item to span multiple rows or columns.

**HTML Script:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Grid Layout Example</title>
    <style>
        .grid-container {
            display: grid;
            grid-template-columns: 1fr 2fr;
            grid-template-rows: auto 100px;
            gap: 10px;
            background-color: lightgray;
        }
        .grid-item {
            background-color: coral;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>
<body>
    <div class="grid-container">
        <div class="grid-item">1</div>
        <div class="grid-item">2</div>
        <div class="grid-item">3</div>
        <div class="grid-item">4</div>
    </div>
</body>
</html>
```

**Output:**
1. A grid layout with two columns, where the second column is twice as wide as the first.
2. Items are spaced with a 10px gap.

⇧ [Back to Table of Contents](#table-of-contents)

---

### **35. Explain Difference Between Visibility and Display in CSS.**

| **Aspect**        | **Visibility**                              | **Display**                               |
|--------------------|---------------------------------------------|-------------------------------------------|
| **Definition**     | Determines if an element is visible or hidden. | Controls if an element is rendered or removed from the layout. |
| **Values**         | `visible`, `hidden`.                       | `block`, `none`, `inline`, etc.           |
| **Effect**         | Hidden elements still occupy space.         | Elements set to `none` do not occupy space. |

**HTML Script:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Visibility vs Display</title>
    <style>
        .visible {
            visibility: hidden;
        }
        .display {
            display: none;
        }
    </style>
</head>
<body>
    <p class="visible">I am hidden but still occupy space.</p>
    <p class="display">I am not rendered at all.</p>
</body>
</html>
```

**Output:**
1. The first paragraph is invisible but still affects layout spacing.
2. The second paragraph is entirely removed from the document flow.

⇧ [Back to Table of Contents](#table-of-contents)

---

### **36. Explain CSS Animations with Examples.**

**Definition:**
CSS animations enable dynamic transitions between states without requiring JavaScript. They are defined using `@keyframes` and applied with animation-related properties.

**Key Properties:**
1. **`@keyframes`**: Defines the animation sequence.
2. **`animation-name`**: Specifies the name of the animation.
3. **`animation-duration`**: Defines the duration of the animation.
4. **`animation-iteration-count`**: Specifies the number of times the animation should repeat.

**HTML Script:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Animations Example</title>
    <style>
        @keyframes move {
            0% {
                transform: translateX(0);
            }
            50% {
                transform: translateX(50px);
            }
            100% {
                transform: translateX(0);
            }
        }
        .box {
            width: 50px;
            height: 50px;
            background-color: coral;
            animation: move 2s infinite;
        }
    </style>
</head>
<body>
    <div class="box"></div>
</body>
</html>
```

**Output:**
The box moves horizontally back and forth in a loop.

⇧ [Back to Table of Contents](#table-of-contents)

---

### **37. Explain Difference Between Inline and Block Elements.**

| **Aspect**        | **Inline Elements**                         | **Block Elements**                       |
|--------------------|---------------------------------------------|------------------------------------------|
| **Display**        | Stays inline with surrounding content.      | Starts on a new line.                    |
| **Width**          | Width depends on content.                  | Takes full width of the parent.          |
| **Examples**       | `<span>`, `<a>`, `<strong>`.                | `<div>`, `<p>`, `<section>`.             |

**HTML Script:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Inline vs Block</title>
    <style>
        .block {
            background-color: lightblue;
        }
        .inline {
            background-color: coral;
        }
    </style>
</head>
<body>
    <div class="block">Block Element</div>
    <span class="inline">Inline Element</span>
</body>
</html>
```

**Output:**
1. The block element spans the full width of the container.
2. The inline element stays within its content width.

⇧ [Back to Table of Contents](#table-of-contents)

---




