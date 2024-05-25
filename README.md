<!-- # Learn-HTML-CSS-and-Javascript

# Hands-On Lab: Introduction to HTML and CSS

## Objective
By the end of this lab, you will be able to:
- Understand the basic structure of an HTML document
- Create a simple web page using HTML
- Style the web page using CSS

## Prerequisites
- Basic understanding of web browsers and text editors
- No prior knowledge of HTML or CSS is required

## Tools Required
- A text editor (e.g., VSCode, Sublime Text, or Notepad++)
- A web browser (e.g., Chrome, Firefox, or Safari)

## Lab Steps

### Step 1: Setting Up Your Project
1. Create a new folder on your desktop named `MyFirstWebsite`.
2. Open your text editor and create a new file. Save it as `index.html` inside the `MyFirstWebsite` folder.

### Step 2: Basic HTML Structure
1. Open `index.html` in your text editor.
2. Add the following code to create the basic structure of an HTML document:

    ```html
    <!DOCTYPE html>
    <html>
    <head>
        <title>My First Website</title>
    </head>
    <body>
        <h1>Welcome to My First Website</h1>
        <p>This is my first paragraph.</p>
    </body>
    </html>
    ```

### Step 3: Creating Content with HTML
1. Add more content to your webpage:

    ```html
    <h2>About Me</h2>
    <p>My name is [Your Name]. I am learning HTML and CSS.</p>
    
    <h2>My Hobbies</h2>
    <ul>
        <li>Reading</li>
        <li>Coding</li>
        <li>Traveling</li>
    </ul>
    
    <h2>Contact Me</h2>
    <p>Email: <a href="mailto:yourname@example.com">yourname@example.com</a></p>
    ```

### Step 4: Adding Images and Links
1. Add an image and more links:

    ```html
    <h2>My Favorite Animal</h2>
    <img src="https://example.com/myfavoriteanimal.jpg" alt="My Favorite Animal">
    
    <h2>Useful Links</h2>
    <p>Visit <a href="https://www.w3schools.com">W3Schools</a> for more HTML tutorials.</p>
    ```

### Step 5: Styling with CSS
1. Create a new file in the `MyFirstWebsite` folder and save it as `styles.css`.
2. Link the CSS file in your `index.html`:

    ```html
    <head>
        <title>My First Website</title>
        <link rel="stylesheet" type="text/css" href="styles.css">
    </head>
    ```

3. Open `styles.css` in your text editor and add the following styles:

    ```css
    body {
        font-family: Arial, sans-serif;
        background-color: #f0f0f0;
        margin: 0;
        padding: 0;
    }

    h1, h2 {
        color: #333;
    }

    p {
        color: #666;
    }

    ul {
        list-style-type: square;
    }

    a {
        color: #0066cc;
        text-decoration: none;
    }

    a:hover {
        text-decoration: underline;
    }

    img {
        max-width: 100%;
        height: auto;
    }
    ```

### Step 6: Adding More Styles
1. Add more CSS to enhance your page's layout and design:

    ```css
    header {
        background-color: #4CAF50;
        color: white;
        text-align: center;
        padding: 1em 0;
    }

    nav {
        margin: 20px;
    }

    nav ul {
        padding: 0;
    }

    nav ul li {
        display: inline;
        margin-right: 10px;
    }

    footer {
        background-color: #333;
        color: white;
        text-align: center;
        padding: 10px 0;
        position: fixed;
        bottom: 0;
        width: 100%;
    }
    ```

2. Update your HTML to include the new elements:

    ```html
    <body>
        <header>
            <h1>Welcome to My First Website</h1>
        </header>
        
        <nav>
            <ul>
                <li><a href="#about">About Me</a></li>
                <li><a href="#hobbies">My Hobbies</a></li>
                <li><a href="#contact">Contact Me</a></li>
            </ul>
        </nav>

        <section id="about">
            <h2>About Me</h2>
            <p>My name is [Your Name]. I am learning HTML and CSS.</p>
        </section>
        
        <section id="hobbies">
            <h2>My Hobbies</h2>
            <ul>
                <li>Reading</li>
                <li>Coding</li>
                <li>Traveling</li>
            </ul>
        </section>
        
        <section id="contact">
            <h2>Contact Me</h2>
            <p>Email: <a href="mailto:yourname@example.com">yourname@example.com</a></p>
        </section>
        
        <footer>
            <p>&copy; 2024 My First Website</p>
        </footer>
    </body>
    ```

### Step 7: Making the Website Responsive
1. Add responsive design to your CSS:

    ```css
    @media only screen and (max-width: 600px) {
        nav ul li {
            display: block;
            margin-bottom: 10px;
        }

        header, footer {
            padding: 10px 0;
        }
    }
    ```

### Step 8: Viewing Your Website
1. Open the `index.html` file in a web browser to view your website.

## Conclusion
In this lab, you learned how to create a basic HTML document, add content and images, and style your webpage using CSS. You also learned how to make your website responsive. This foundational knowledge will help you as you continue to explore web development. -->


<!-- 
# Hands-On Lab: Building a Simple Web Page with HTML and CSS

## Prerequisites
- A text editor (like VS Code, Sublime Text, or Notepad++)
- A modern web browser (like Chrome, Firefox, or Edge)

## Part 1: Introduction to HTML

**Objective:** Create the basic structure of an HTML document.

### Steps:

1. **Create a new HTML file**
   - Open your text editor and create a new file named `index.html`.

2. **Add the basic HTML structure**
   - Type the following code into `index.html`:

    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>My First Web Page</title>
    </head>
    <body>
        <h1>Welcome to My Web Page</h1>
    </body>
    </html>
    ```

    **Explanation:**
    - `<!DOCTYPE html>` declares the document type and version.
    - `<html lang="en">` specifies the language of the document.
    - `<head>` contains meta-information about the document.
    - `<meta charset="UTF-8">` sets the character encoding for the document.
    - `<meta name="viewport" content="width=device-width, initial-scale=1.0">` makes the page responsive.
    - `<title>` sets the title of the web page (displayed on the browser tab).
    - `<body>` contains the content of the document.
    - `<h1>` is a heading element.

3. **Save and view your HTML file**
   - Save the file and open it in your web browser to see the result.

## Part 2: Adding More HTML Elements

**Objective:** Add text, images, and links to your web page.

### Steps:

1. **Add a paragraph**
   - Below the `<h1>` tag, add the following:

    ```html
    <p>This is my first web page. I am learning HTML and CSS!</p>
    ```

2. **Add an image**
   - Below the paragraph, add the following:

    ```html
    <img src="https://via.placeholder.com/150" alt="Placeholder Image">
    ```

    **Explanation:**
    - `<img>` tag is used to embed images.
    - `src` attribute specifies the image source URL.
    - `alt` attribute provides alternative text for the image.

3. **Add a link**
   - Below the image, add the following:

    ```html
    <a href="https://www.example.com">Visit Example.com</a>
    ```

    **Explanation:**
    - `<a>` tag is used to create hyperlinks.
    - `href` attribute specifies the destination URL.

## Part 3: Introduction to CSS

**Objective:** Apply basic CSS styles to your web page.

### Steps:

1. **Add a CSS file**
   - Create a new file named `styles.css` in the same directory as `index.html`.

2. **Link the CSS file to the HTML file**
   - Inside the `<head>` section of `index.html`, add the following line:

    ```html
    <link rel="stylesheet" href="styles.css">
    ```

3. **Add CSS styles**
   - Open `styles.css` and add the following:

    ```css
    body {
        font-family: Arial, sans-serif;
        background-color: #f0f0f0;
        margin: 0;
        padding: 0;
    }

    h1 {
        color: #333;
        text-align: center;
    }

    p {
        font-size: 18px;
        color: #666;
        text-align: center;
    }

    img {
        display: block;
        margin: 20px auto;
    }

    a {
        display: block;
        text-align: center;
        margin-top: 20px;
        color: #007BFF;
        text-decoration: none;
    }

    a:hover {
        text-decoration: underline;
    }
    ```

    **Explanation:**
    - `body` selector styles the body of the document.
    - `h1`, `p`, `img`, and `a` selectors style the respective elements.
    - `color` changes the text color.
    - `background-color` changes the background color.
    - `font-family` sets the font.
    - `text-align` centers the text.
    - `margin` and `padding` control spacing.
    - `display: block` makes elements block-level (takes up the full width).

4. **Save and refresh your HTML file**
   - Save both `index.html` and `styles.css`, then refresh your web browser to see the styled web page.

## Part 4: Adding More CSS Styling

**Objective:** Enhance the appearance of the web page with advanced CSS properties.

### Steps:

1. **Add a navigation bar**
   - Inside the `<body>` tag of `index.html`, at the top, add:

    ```html
    <nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>
    ```

2. **Style the navigation bar**
   - Add the following CSS to `styles.css`:

    ```css
    nav {
        background-color: #333;
        padding: 10px 0;
    }

    nav ul {
        list-style: none;
        padding: 0;
        margin: 0;
        text-align: center;
    }

    nav ul li {
        display: inline;
        margin: 0 15px;
    }

    nav ul li a {
        color: white;
        text-decoration: none;
        font-size: 18px;
    }

    nav ul li a:hover {
        text-decoration: underline;
    }
    ```

    **Explanation:**
    - `nav` styles the navigation bar container.
    - `ul` removes default list styling.
    - `li` makes list items display inline (horizontally).
    - `a` styles the links inside the navigation.

3. **Add a footer**
   - At the bottom of the `<body>` tag, add:

    ```html
    <footer>
        <p>&copy; 2024 My Web Page</p>
    </footer>
    ```

4. **Style the footer**
   - Add the following CSS to `styles.css`:

    ```css
    footer {
        background-color: #333;
        color: white;
        text-align: center;
        padding: 10px 0;
        position: fixed;
        width: 100%;
        bottom: 0;
    }
    ```

    **Explanation:**
    - `footer` styles the footer container.
    - `position: fixed` makes the footer stay at the bottom of the viewport.

## Part 5: Final Touches

**Objective:** Ensure the web page is responsive and visually appealing.

### Steps:

1. **Add media queries**
   - Add the following CSS to `styles.css` to make the page responsive:

    ```css
    @media (max-width: 600px) {
        h1 {
            font-size: 24px;
        }

        p {
            font-size: 16px;
        }

        nav ul li {
            display: block;
            margin: 10px 0;
        }
    }
    ```

    **Explanation:**
    - `@media (max-width: 600px)` applies styles for screens smaller than 600px.
    - Adjusts font sizes and navigation layout for better readability on small screens.

2. **Save and test your web page**
   - Save all files and refresh your web browser to see the final result. Resize the browser window to see the responsive design in action.

## Conclusion

By the end of this lab, you should have a basic understanding of HTML structure and how to apply CSS styles to create a simple, responsive web page. You can continue to experiment with more HTML elements and CSS properties to enhance your web design skills.

Feel free to ask any questions or request further explanations on specific parts of the lab. Happy coding! -->


# Hands-On Lab: Building a Simple Web Page with HTML and CSS

## Prerequisites
- A text editor (like VS Code, Sublime Text, or Notepad++)
- A modern web browser (like Chrome, Firefox, or Edge)

## Part 1: Introduction to HTML

**Objective:** Create the basic structure of an HTML document.

### Steps:

1. **Create a new HTML file**
   - Open your text editor and create a new file named `index.html`.

2. **Add the basic HTML structure**
   - Type the following code into `index.html`:

    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>My First Web Page</title>
        <link rel="stylesheet" href="styles.css">
    </head>
    <body>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Services</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
        <h1>Welcome to My Web Page</h1>
        <p>This is my first web page. I am learning HTML and CSS!</p>
        <img src="https://via.placeholder.com/150" alt="Placeholder Image">
        <a href="https://www.example.com">Visit Example.com</a>
        <footer>
            <p>&copy; 2024 My Web Page</p>
        </footer>
    </body>
    </html>
    ```

    **Explanation:**
    - `<!DOCTYPE html>` declares the document type and version.
    - `<html lang="en">` specifies the language of the document.
    - `<head>` contains meta-information about the document.
    - `<meta charset="UTF-8">` sets the character encoding for the document.
    - `<meta name="viewport" content="width=device-width, initial-scale=1.0">` makes the page responsive.
    - `<title>` sets the title of the web page (displayed on the browser tab).
    - `<link rel="stylesheet" href="styles.css">` links to the CSS file.
    - `<nav>` contains the navigation menu.
    - `<h1>` is a heading element.
    - `<p>` is a paragraph element.
    - `<img>` is an image element.
    - `<a>` is a hyperlink element.
    - `<footer>` contains the footer content.

3. **Save and view your HTML file**
   - Save the file and open it in your web browser to see the result.

## Part 2: Adding More HTML Elements

**Objective:** Add text, images, and links to your web page.

### Steps:

1. **Add a paragraph**
   - Below the `<h1>` tag, add the following:

    ```html
    <p>This is my first web page. I am learning HTML and CSS!</p>
    ```

2. **Add an image**
   - Below the paragraph, add the following:

    ```html
    <img src="https://via.placeholder.com/150" alt="Placeholder Image">
    ```

    **Explanation:**
    - `<img>` tag is used to embed images.
    - `src` attribute specifies the image source URL.
    - `alt` attribute provides alternative text for the image.

3. **Add a link**
   - Below the image, add the following:

    ```html
    <a href="https://www.example.com">Visit Example.com</a>
    ```

    **Explanation:**
    - `<a>` tag is used to create hyperlinks.
    - `href` attribute specifies the destination URL.

## Part 3: Introduction to CSS

**Objective:** Apply basic CSS styles to your web page.

### Steps:

1. **Add a CSS file**
   - Create a new file named `styles.css` in the same directory as `index.html`.

2. **Link the CSS file to the HTML file**
   - Inside the `<head>` section of `index.html`, add the following line:

    ```html
    <link rel="stylesheet" href="styles.css">
    ```

3. **Add CSS styles**
   - Open `styles.css` and add the following:

    ```css
    body {
        font-family: Arial, sans-serif;
        background-color: #f0f0f0;
        margin: 0;
        padding: 0;
        background-image: url('https://via.placeholder.com/1920x1080');
        background-size: cover;
        background-attachment: fixed;
    }

    nav {
        background-color: rgba(51, 51, 51, 0.8);
        padding: 10px 0;
        position: fixed;
        width: 100%;
        top: 0;
        z-index: 1000;
    }

    nav ul {
        list-style: none;
        padding: 0;
        margin: 0;
        text-align: center;
    }

    nav ul li {
        display: inline;
        margin: 0 15px;
    }

    nav ul li a {
        color: white;
        text-decoration: none;
        font-size: 18px;
        padding: 5px 10px;
    }

    nav ul li a:hover {
        background-color: rgba(255, 255, 255, 0.2);
        border-radius: 5px;
    }

    h1 {
        color: #333;
        text-align: center;
        margin-top: 100px;
    }

    p {
        font-size: 18px;
        color: #666;
        text-align: center;
    }

    img {
        display: block;
        margin: 20px auto;
    }

    a {
        display: block;
        text-align: center;
        margin-top: 20px;
        color: #007BFF;
        text-decoration: none;
    }

    a:hover {
        text-decoration: underline;
    }

    footer {
        background-color: #333;
        color: white;
        text-align: center;
        padding: 10px 0;
        position: fixed;
        width: 100%;
        bottom: 0;
    }
    ```

    **Explanation:**
    - `body` selector styles the body of the document and adds a background image.
    - `background-image` sets the background image.
    - `background-size: cover` makes sure the image covers the entire background.
    - `background-attachment: fixed` makes the background image fixed when scrolling.
    - `nav` styles the navigation bar and makes it fixed at the top.
    - `nav ul li a:hover` adds a hover effect to the navigation links.
    - Other selectors style the respective elements (heading, paragraph, image, link, footer).

4. **Save and refresh your HTML file**
   - Save both `index.html` and `styles.css`, then refresh your web browser to see the styled web page.

## Part 4: Adding More CSS Styling

**Objective:** Enhance the appearance of the web page with advanced CSS properties.

### Steps:

1. **Style the navigation bar**
   - Add the following CSS to `styles.css` (already included above):

    ```css
    nav {
        background-color: rgba(51, 51, 51, 0.8);
        padding: 10px 0;
        position: fixed;
        width: 100%;
        top: 0;
        z-index: 1000;
    }

    nav ul {
        list-style: none;
        padding: 0;
        margin: 0;
        text-align: center;
    }

    nav ul li {
        display: inline;
        margin: 0 15px;
    }

    nav ul li a {
        color: white;
        text-decoration: none;
        font-size: 18px;
        padding: 5px 10px;
    }

    nav ul li a:hover {
        background-color: rgba(255, 255, 255, 0.2);
        border-radius: 5px;
    }
    ```

    **Explanation:**
    - `nav` styles the navigation bar container.
    - `ul` removes default list styling.
    - `li` makes list items display inline (horizontally).
    - `a` styles the links inside the navigation.
    - `a:hover` adds a background color and rounded corners when hovering over the links.

2. **Add a footer**
   - At the bottom of the `<body>` tag in `index.html`, add:

    ```html
    <footer>
        <p>&copy; 2024 My Web Page</p>
    </footer>
    ```

3. **Style the footer**
   - Add the following CSS to `styles.css` (already included above):

    ```css
    footer {
        background-color: #333;
        color: white;
        text-align: center;
        padding: 10px 0;
        position: fixed;
        width: 100%;
        bottom: 0;
    }
    ```

    **Explanation:**
    - `footer` styles the footer container.
    - `position: fixed` makes the footer stay at the bottom of the viewport.

## Part 5: Final Touches

**Objective:** Ensure the web page is responsive and visually appealing.

### Steps:

1. **Add media queries**
   - Add the following CSS to `styles.css` to make the page responsive:

    ```css
    @media (max-width: 600px) {
        h1 {
            font-size: 24px;
        }

        p {
            font-size: 16px;
        }

        nav ul li {
            display: block;
            margin: 10px 0;
        }
    }
    ```

    **Explanation:**
    - `@media (max-width: 600px)` applies styles for screens smaller than 600px.
    - Adjusts font sizes and navigation layout for better readability on small screens.

2. **Save and test your web page**
   - Save all files and refresh your web browser to see the final result. Resize the browser window to see the responsive design in action.

## Conclusion

By the end of this lab, you should have a basic understanding of HTML structure and how to apply CSS styles to create a simple, responsive web page. You can continue to experiment with more HTML elements and CSS properties to enhance your web design skills.


