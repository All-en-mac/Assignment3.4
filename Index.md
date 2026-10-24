
HTML
<!-- BEFORE: Non-semantic, div-heavy structure -->
<div class="header-wrapper">
    <div class="logo">Allen Macanige</div>
    <div class="menu">
        <a href="#">Home</a> | <a href="#">About</a>
    </div>
</div>
<div class="main-content">
    <div class="post-section">
        <div class="post-title">Understanding Semantic HTML</div>
        <div class="post-body">Content goes here...</div>
    </div>
</div>
<div class="sidebar">Related links...</div>
<div class="footer-wrapper">Copyright 2026</div>
Step 2: The "After" Code (Fully Semantic HTML)
Here is the refactored, highly accessible version using proper semantic tags (<header>, <nav>, <main>, <section>, <article>, <aside>, and <footer>):

HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Semantic Portfolio — Allen Macanige</title>
</head>
<body>

    <!-- Header & Navigation -->
    <header>
        <h1>Allen Macanige</h1>
        <p>Aspiring Full-Stack Web Developer</p>
        
        <nav aria-label="Main Navigation">
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#articles">Articles</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Main Content Area -->
    <main>
        <!-- About Section -->
        <section id="about">
            <h2>About Me</h2>
            <p>Welcome to my semantic portfolio website. This page is built using modern semantic HTML elements to ensure maximum accessibility, crystal-clear document structure, and SEO optimization.</p>
        </section>

        <!-- Articles Section -->
        <section id="articles">
            <h2>Latest Technical Articles</h2>
            
            <article>
                <h3>Understanding Semantic HTML</h3>
                <p><em>Published on October 20, 2026 by Allen Macanige</em></p>
                <p>Semantic HTML introduces meaning to the web page rather than just visual presentation. Tags like <code>&lt;article&gt;</code>, <code>&lt;section&gt;</code>, and <code>&lt;nav&gt;</code> help screen readers, assistive tech, and search engines understand the exact architecture of your content.</p>
            </article>
        </section>
    </main>

    <!-- Sidebar / Secondary Content -->
    <aside>
        <h3>Quick Resources</h3>
        <ul>
            <li><a href="https://developer.mozilla.org" target="_blank" rel="noopener noreferrer">MDN Web Docs</a></li>
            <li><a href="https://github.com" target="_blank" rel="noopener noreferrer">GitHub Profile</a></li>
        </ul>
    </aside>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2026 Allen Macanige. Built with semantic HTML.</p>
    </footer>

</body>
</html>

Take a screenshot of the old div-based code or its rendered preview.

Take a screenshot of the new semantic HTML code in VS Code showing the structured tags (<header>, <main>, <aside>, <footer>) and the rendered browser view.

Submit the updated semantic HTML file and your before/after screenshots!
