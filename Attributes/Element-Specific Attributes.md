### Element-Specific Attributes
These attributes are specific to certain HTML elements.

1. **src (for images)**
   - Specifies the path to the image source.
   ```html
   <img src="image.jpg" alt="Description of image">
   ```

2. **href (for links)**
   - Specifies the URL of the page the link goes to.
   ```html
   <a href="https://example.com">Visit Example.com</a>
   ```

3. **alt (for images)**
   - Provides alternative text for an image if it cannot be displayed.
   ```html
   <img src="image.jpg" alt="Description of image">
   ```

4. **type (for inputs)**
   - Specifies the type of input element.
   ```html
   <input type="text" name="username">
   ```

#### Element-Specific Attributes Example
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Element-Specific Attributes Example</title>
</head>
<body>
    <h2>Image Example</h2>
    <img src="image.jpg" alt="A beautiful scenery">

    <h2>Link Example</h2>
    <a href="https://example.com">Visit Example.com</a>

    <h2>Input Example</h2>
    <form action="/submit" method="post">
        <label for="username">Username:</label>
        <input type="text" id="username" name="username">
        <button type="submit">Submit</button>
    </form>
</body>
</html>
```