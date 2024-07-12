3. **Head Section**
   ```html
   <head></head>
   ```
   - Contains metadata, the document title, links to stylesheets, scripts, and other resources.

   - **Metadata Elements**
     ```html
     <meta charset="UTF-8">
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
     ```
     - `<meta charset="UTF-8">`: Defines the character set.
     - `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Ensures proper rendering and touch zooming on mobile devices.

   - **Title Element**
     ```html
     <title>Your Page Title</title>
     ```
     - Sets the title of the document, shown in the browser tab.

   - **Link to Stylesheet**
     ```html
     <link rel="stylesheet" href="styles.css">
     ```
     - Links an external CSS file.

   - **Script Tag**
     ```html
     <script src="script.js" defer></script>
     ```
     - Links an external JavaScript file.
     - `defer` attribute ensures the script is executed after the document has been parsed.