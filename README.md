# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>Sample HTML5 Document</title>
    <link rel="stylesheet" href="styles.css">
</head>

<body>

    <header>
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
            <h1>Welcome to Our Website</h1>
            <p>We are glad to have you here. Explore our content and services.</p>
        </section>

        <section id="about">
            <h2>About Us</h2>
            <p>We are a team of professionals dedicated to providing top-notch services to our clients.</p>
        </section>

        <section id="services">
            <h2>Our Services</h2>
            <ul>
                <li>Consulting</li>
                <li>Design</li>
                <li>Development</li>
            </ul>
        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <p>If you have any questions, feel free to reach out to us!</p>
            <form action="#" method="POST">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required><br>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required><br>

                <

Happy Coding! 💻✨
