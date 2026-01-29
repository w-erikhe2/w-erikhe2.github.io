<!DOCTYPE html>
<html>
<head>
    <title>My Personal Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(to right, #4facfe, #00f2fe);
            color: white;
            text-align: center;
            padding: 50px;
        }
        .card {
            background: rgba(0,0,0,0.3);
            padding: 30px;
            border-radius: 15px;
            display: inline-block;
        }
        a {
            color: yellow;
            text-decoration: none;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div class="card">
        <h1>Hello, I'm YOUR NAME</h1>
        <p>Welcome to my personal website 👋</p>
        <p>I am learning coding and building cool projects 🚀</p>
        <p>
            <a href="https://github.com/YOURUSERNAME">Visit my GitHub</a>
        </p>
    </div>
</body>
</html># w-erikhe2.github.io
my website 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name | Portfolio</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
            background: #0f172a;
            color: #f1f5f9;
        }

        header {
            text-align: center;
            padding: 40px 20px;
            background: linear-gradient(135deg, #2563eb, #7c3aed);
        }

        header img {
            width: 140px;
            height: 140px;
            border-radius: 50%;
            border: 4px solid white;
            object-fit: cover;
        }

        header h1 {
            margin: 15px 0 5px;
        }

        header p {
            margin: 5px 0;
            font-size: 18px;
        }

        section {
            max-width: 900px;
            margin: auto;
            padding: 40px 20px;
        }

        h2 {
            border-bottom: 2px solid #334155;
            padding-bottom: 10px;
            margin-bottom: 20px;
        }

        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .card {
            background: #1e293b;
            padding: 20px;
            border-radius: 12px;
            transition: transform 0.2s ease;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        .socials a {
            margin: 0 10px;
            color: #38bdf8;
            text-decoration: none;
            font-weight: bold;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: #020617;
            font-size: 14px;
            color: #94a3b8;
        }
    </style>
</head>
<body>

<header>
    <!-- 🔁 REPLACE photo.jpg with your image file name -->
    <img src="photo.jpg" alt="Profile Photo">
    <h1>Your Name</h1>
    <p>Aspiring Developer | Student | Tech Enthusiast</p>

    <div class="socials">
        <!-- 🔁 Replace links with your real profiles -->
        <a href="https://github.com/yourusername" target="_blank">GitHub</a>
        <a href="https://linkedin.com/in/yourusername" target="_blank">LinkedIn</a>
        <a href="https://twitter.com/yourusername" target="_blank">Twitter</a>
    </div>
</header>

<section>
    <h2>👋 About Me</h2>
    <p>
        Hello! I'm a student passionate about technology and learning how to build
        websites and software. I enjoy solving problems and turning ideas into real projects.
    </p>
</section>

<section>
    <h2>🚀 Projects</h2>
    <div class="projects">

        <div class="card">
            <h3>Personal Website</h3>
            <p>This portfolio website built using HTML and CSS and hosted on GitHub Pages.</p>
        </div>

        <div class="card">
            <h3>Project Coming Soon</h3>
            <p>I am currently working on more coding projects. Stay tuned!</p>
        </div>

        <div class="card">
            <h3>Future App Idea</h3>
            <p>A future application I plan to build as I grow my programming skills.</p>
        </div>

    </div>
</section>

<footer>
    © 2026 Your Name | Built with GitHub Pages
</footer>

</body>
</html>