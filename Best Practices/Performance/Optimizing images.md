2. **Optimizing Images**
   - Optimize images by compressing them and using appropriate formats (e.g., JPEG for photographs, PNG for graphics with transparency, SVG for vector images).
   - Use responsive images to serve different sizes based on the user's device.
   ```html
   <img src="image-small.jpg" srcset="image-large.jpg 1024w, image-medium.jpg 640w, image-small.jpg 320w" alt="Optimized image">
   ```

### Example Combining Best Practices

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Best Practices Example</title>
    <meta name="description" content="This is an example webpage following best practices for accessibility, SEO, and performance.">
    <meta name="keywords" content="HTML, best practices, accessibility, SEO, performance">
    <meta name="author" content="Your Name">
</head>
<body>
    <header role="banner">
        <h1>My Website</h1>
    </header>
    <nav role="navigation">
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <main role="main">
        <section id="home">
            <h2>Home</h2>
            <p>Welcome to my website.</p>
            <img src="image-small.jpg" srcset="image-large.jpg 1024w, image-medium.jpg 640w, image-small.jpg 320w" alt="A beautiful scenery">
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
    <footer role="contentinfo">
        <p>&copy; 2024 Your Name. All rights reserved.</p>
    </footer>
</body>
</html>
```

By following these best practices, you can create web pages that are more accessible, SEO-friendly, and performant, leading to a better user experience and improved visibility in search engines.