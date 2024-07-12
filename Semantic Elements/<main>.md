7. **<main>**
   - Represents the dominant content of the <body> of a document. There is only one <main> element per document.
   ```html
   <main>
       <section>
           <h2>Main Content Heading</h2>
           <p>This is the primary content of the webpage.</p>
       </section>
   </main>
   ```

### Examples

#### Full Semantic HTML Example
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Semantic Elements Example</title>
</head>
<body>
    <header>
        <h1>My Website</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="home">
            <h2>Home</h2>
            <p>Welcome to my website.</p>
        </section>

        <section id="about">
            <h2>About</h2>
            <article>
                <h3>Our Story</h3>
                <p>Information about the company.</p>
            </article>
        </section>

        <section id="services">
            <h2>Services</h2>
            <article>
                <h3>Service One</h3>
                <p>Details about the first service offered.</p>
            </article>
            <article>
                <h3>Service Two</h3>
                <p>Details about the second service offered.</p>
            </article>
        </section>

        <aside>
            <h2>Related Information</h2>
            <p>This section contains related information or ads.</p>
        </aside>
    </main>

    <footer>
        <p>&copy; 2024 Your Name. All rights reserved.</p>
    </footer>
</body>
</html>
```

These semantic elements help improve the accessibility of the web page and provide better SEO by giving meaning to the structure of the content.