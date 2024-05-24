# Learn-HTML-CSS-and-Javascript

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
In this lab, you learned how to create a basic HTML document, add content and images, and style your webpage using CSS. You also learned how to make your website responsive. This foundational knowledge will help you as you continue to explore web development.
