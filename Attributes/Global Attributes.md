### Global Attributes
Global attributes can be used on any HTML element.

1. **id**
   - Provides a unique identifier for an HTML element.
   - Useful for targeting elements with CSS and JavaScript.
   ```html
   <p id="unique-paragraph">This is a unique paragraph.</p>
   ```

2. **class**
   - Assigns one or more class names to an element.
   - Useful for targeting multiple elements with the same class using CSS and JavaScript.
   ```html
   <p class="text">This paragraph has a class.</p>
   ```

3. **style**
   - Allows inline CSS styles to be applied directly to an element.
   ```html
   <p style="color: blue;">This paragraph is blue.</p>
   ```

4. **title**
   - Provides additional information about the element, typically displayed as a tooltip when hovering over the element.
   ```html
   <p title="This is a tooltip.">Hover over this paragraph to see the tooltip.</p>
   ```

#### Global Attributes Example
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Global Attributes Example</title>
    <style>
        .highlight {
            background-color: yellow;
        }
    </style>
</head>
<body>
    <p id="unique-paragraph" class="highlight" style="font-weight: bold;" title="This is a unique paragraph.">This paragraph has several global attributes.</p>
</body>
</html>
```