# CSS Selectors - Exercises

## Table of Contents

1. [Type Selector](#type-selector)
2. [Class Selector](#class-selector)
3. [Percentage Width](#percentage-width)
4. [Nested Divs](#nested-divs)
5. [Pixel Width](#pixel-width)
6. [Pixel vs Percentage Width](#pixel-vs-percentage-width)
7. [EM Units](#em-units)
8. [REM Units](#rem-units)
9. [Specificity](#specificity)
10. [ID Selector](#id-selector)
11. [Attribute Selector](#attribute-selector)
12. [Universal Selector](#universal-selector)
13. [Descendant Combinator](#descendant-combinator)
14. [Combinator Comparison](#combinator-comparison)
15. [Selector List](#selector-list)
16. [Child Combinator](#child-combinator)
17. [Box Model](#box-model)
18. [Display Property](#display-property)
19. [Width Properties](#width-properties)
20. [Height Properties](#height-properties)
21. [Margin, Border, Padding](#margin-border-padding)

---

## Type Selector

Define a CSS rule to style all paragraph elements to have blue text and bold font weight:

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Type Selector Exercise</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <p>This is a paragraph.</p>
    <p>Style me with CSS!</p>
</body>
</html>
```

```css
p {
    /* Write your rule here */
}
```

Define a type selector to style all heading elements to have green text:

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Type Selector Exercise</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1>This is a heading.</h1>
    <h2>This is a subheading.</h2>
</body>
</html>
```

```css
h1, h2 {
    
}
```

Style different HTML elements (`h1`, `p`, `div`) using type selectors:

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Type Selector Exercise</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1>Heading 1</h1>
    <p>Paragraph text.</p>
    <div>Div content.</div>
</body>
</html>
```

```css
h1 {
    
}

p {
    
}

div {
    
}
```

---

## Class Selector

Use a class selector to change the color of text inside elements with a specific class to red:

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Class Selector Exercise</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="highlight">This text should be red.</div>
    <p class="highlight">This text should also be red.</p>
    <p class="not-highlight">This should not be red.</p>
    <p>This text should not be red.</p>
</body>
</html>
```

```css
.highlight {
    
}
```

Write an example CSS rule using a class selector to change the background color of elements with a specific class:

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Class Selector Exercise</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="highlight">This should have a background color.</div>
    <p class="highlight">This too!</p>
    <p class="red">This is just a text!</p>
</body>
</html>
```

```css
.highlight {
    
}
```

Apply a common style to multiple elements using a class selector:

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Class Selector Exercise</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="common-style">Element 1</div>
    <p class="common-style">Element 2</p>
    <p>Element 3</p>
</body>
</html>
```

```css
.common-style {
    
}
```

Change the background color of elements with a specific class:

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Class Selector Exercise</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="highlight">This should have a different background color.</div>
    <p class="highlight">So should this!</p>
    <p>Hello World!</p>
</body>
</html>
```

```css
.highlight {
    
}
```

---

## Percentage Width

Set the width of a div to 50% and observe how it changes with the browser window size:

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Percentage Width Exercise</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="percentage-width">Resize the window to see me change!</div>
</body>
</html>
```

```css
.percentage-width {
    
}
```

---

## Nested Divs

Create a parent div with 60% width and a child div with 50% width of its parent. Apply some colors to better see the difference:

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nested Divs Exercise</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="parent">
        <div class="child">I'm 50% of my parent.</div>
    </div>
</body>
</html>
```

---

## Pixel Width

Set the width of a div to 300px and observe its behavior when resizing the browser:

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pixel Width Exercise</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="fixed-width">I have a fixed width of 300px.</div>
</body>
</html>
```

```css
.fixed-width {
    /* Set width to 300px */
}
```

---

## Pixel vs Percentage Width

Create two divs, one with a width set in pixels and the other in percentages:

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pixel vs Percentage Width Exercise</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="pixel-width">I have a fixed width of 300px.</div>
    <div class="percentage-width">I have a width of 50%.</div>
</body>
</html>
```

```css
.pixel-width {
    /* Set width to 300px */
}

.percentage-width {
    /* Set width to 50% */
}
```

---

## EM Units

Set the font-size of a parent div to 20px and a child div to 1.5em:

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EM Units Exercise</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="parent">
        <div class="child">I am 1.5em of my parent.</div>
    </div>
</body>
</html>
```

```css
.parent {
    /* Set font-size to 20px */
}

.child {
    /* Set font-size to 1.5em */
}
```

Change the parent div's font-size to 10px and observe the change in the child div's font-size:

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EM Units Exercise</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="parent">
        <div class="child">I am 1.5em of my parent.</div>
    </div>
</body>
</html>
```

```css
.parent {
    /* Set font-size to 10px */
}

.child {
    /* Set font-size to 1.5em */
}
```

---

## REM Units

Set the root element's font-size to 16px and a div element's font-size to 2rem:

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>REM Units Exercise</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="rem-size">I am 2rem.</div>
</body>
</html>
```

```css
html {
    /* Set font-size to 16px */
}

.rem-size {
    /* Set font-size to 2rem */
}
```

Change the root element's font-size to 20px and observe the change in the div element's font-size:

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>REM Units Exercise</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="rem-size">I am 2rem.</div>
</body>
</html>
```

---

## Specificity

Use a class and a type selector on the same element and see which style is applied:

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Specificity Exercise</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <p class="highlight">This is a paragraph.</p>
</body>
</html>
```

```css
p {
    /* Style for type selector */
}

.highlight {
    /* Style for class selector */
}
```

Apply both a class and an ID selector to the same element and see which style takes precedence:

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Specificity Exercise</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <p id="unique" class="highlight">This is a paragraph.</p>
</body>
</html>
```

```css
#unique {
    /* Style for ID selector */
}

.highlight {
    /* Style for class selector */
}
```

---

## ID Selector

Style elements with unique IDs:

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ID Selector Exercise</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div id="unique-element">Unique Element</div>
    <div>Element</div>
</body>
</html>
```

---

## Attribute Selector

Style input elements based on their type attribute:

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Attribute Selector Exercise</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <input type="text" placeholder="Text input">
    <input type="submit" value="Submit">
</body>
</html>
```

```css
input[type="text"] {
    /* Style for text input */
}

input[type="submit"] {
    /* Style for submit input */
}
```

Change the text color of links with a specific href attribute:

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Attribute Selector Exercise</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <a href="https://example.com">Example Link</a>
    <a href="https://another.com">Another Link</a>
</body>
</html>
```

```css
a[href="https://example.com"] {
    
}
```

---

## Universal Selector

Use the universal selector to set a default margin and padding for all elements:

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Universal Selector Exercise</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div>Content with default margin and padding.</div>
</body>
</html>
```

```css
* {
    
}
```

Use the universal selector to set a default font-family and color for all elements:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Universal Selector Exercise</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div>Content with default font and color.</div>
</body>
</html>
```

---

## Descendant Combinator

Style nested elements using a descendant combinator:

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Descendant Combinator Exercise</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div>
        <p>Descendant of div</p>
    </div>
</body>
</html>
```

```css
div p {
    
}
```

---

## Combinator Comparison
Compare descendant combinator and child combinator.

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Combinator Comparison Exercise</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div>
        <p>Descendant</p>
        <div>
            <p>Child</p>
        </div>
    </div>
</body>
</html>
```

```css
div p {
    /* Style for descendant combinator */
}

div > p {
    /* Style for child combinator */
}
```

## Selector List
Use a selector list to apply the same style to multiple elements.

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Selector List Exercise</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1>Heading</h1>
    <p>Paragraph</p>
    <div>Div content</div>
</body>
</html>
```

```css
h1, p, div {
    /* Common style */
}
```

## Child Combinator
Use a child combinator to style direct children of a div element.

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Child Combinator Exercise</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div>
        <p>Direct child of div</p>
        <div>
            <p>Nested child</p>
        </div>
    </div>
</body>
</html>
```

```css
div > p {
    /* Style for direct children */
}
```

## Box Model
Use CSS to demonstrate the box model by setting margin, border, padding, and content area values.

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Box Model Exercise</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="box">Box Model Example</div>
</body>
</html>
```

```css
.box {
    width: 200px;
    padding: 20px;
    border: 5px solid black;
    margin: 10px;
}
```

## Display Property
Set different display properties (block, inline, inline-block) for elements.

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Display Property Exercise</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="block">Block element</div>
    <span class="inline">Inline element</span>
    <div class="inline-block">Inline-block element</div>
</body>
</html>
```

```css
.block {
    display: block;
}

.inline {
    display: inline;
}

.inline-block {
    display: inline-block;
}
```

## Width Properties
Set the width, min-width, and max-width of a div element.

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Width Properties Exercise</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="width-example">Resize the window to see me change!</div>
</body>
</html>
```

```css
.width-example {
    width: 50%;
    min-width: 300px;
    max-width: 600px;
}
```

## Height Properties
Set the height, min-height, and max-height of a div element.

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Height Properties Exercise</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="height-example">Resize the window to see me change!</div>
</body>
</html>
```

```css
.height-example {
    height: 100px;
    min-height: 50px;
    max-height: 150px;
}
```

## Margin, Border, Padding
Set different margin, border, and padding values for a div element.

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Margin, Border, Padding Exercise</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="box-model">Box Model Example</div>
</body>
</html>
```

```css
.box-model {
    margin: 15px;
    padding: 10px;
    border: 3px solid #000;
}
