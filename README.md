<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background-color: #0078D7;
            color: #fff;
            text-align: center;
            padding: 1.5rem 0;
        }
        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }
        header p {
            margin: 0.5rem 0 0;
            font-size: 1.2rem;
        }
        nav {
            background-color: #005bb5;
            display: flex;
            justify-content: center;
            padding: 0.5rem 0;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 1rem;
            font-size: 1rem;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .content {
            max-width: 800px;
            margin: 2rem auto;
            padding: 1rem;
            background: #fff;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .section {
            margin-bottom: 2rem;
        }
        .section h2 {
            border-bottom: 2px solid #0078D7;
            padding-bottom: 0.5rem;
            margin-bottom: 1rem;
        }
        footer {
            text-align: center;
            padding: 1rem 0;
            background-color: #0078D7;
            color: #fff;
        }
        footer a {
            color: #fff;
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>My Portfolio</h1>
        <p>Welcome to my personal website</p>
    </header>
    <nav>
        <a href="#about">About</a>
        <a href="#resume">Resume</a>
        <a href="#publications">Publications</a>
        <a href="#contact">Contact</a>
    </nav>
    <main class="content">
        <section id="about" class="section">
            <h2>About Me</h2>
            <p>Hello! I am [Your Name], a [Your Profession/Role] passionate about [Your Interests/Expertise]. This website showcases my work, publications, and contact information.</p>
        </section>
        <section id="resume" class="section">
            <h2>Resume</h2>
            <p>You can download my resume <a href="resume.pdf" target="_blank">here</a>.</p>
        </section>
        <section id="publications" class="section">
            <h2>Publications</h2>
            <ul>
                <li><strong>"Title of Publication 1"</strong> - <em>Journal Name</em>, Year</li>
                <li><strong>"Title of Publication 2"</strong> - <em>Journal Name</em>, Year</li>
                <li><strong>"Title of Publication 3"</strong> - <em>Conference Name</em>, Year</li>
            </ul>
        </section>
        <section id="contact" class="section">
            <h2>Contact</h2>
            <p>Feel free to reach out via email at <a href="mailto:your.email@example.com">your.email@example.com</a> or connect with me on <a href="https://linkedin.com/in/yourprofile" target="_blank">LinkedIn</a>.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 [Your Name]. Built with GitHub Pages. <a href="https://github.com/yourusername/your-repo">View Source</a></p>
    </footer>
</body>
</html>
