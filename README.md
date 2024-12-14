# portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }

        nav a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
            display: block;
        }

        nav a:hover {
            background-color: #575757;
        }

        .hero {
            background-color: #f4f4f4;
            padding: 60px 20px;
            text-align: center;
        }

        .hero h1 {
            margin-bottom: 20px;
            font-size: 2.5em;
        }

        .hero p {
            font-size: 1.2em;
            color: #555;
        }

        .sections {
            display: flex;
            flex-direction: column;
            gap: 40px;
            padding: 20px;
            align-items: center;
        }

        .section {
            background-color: #ddd;
            border-radius: 8px;
            padding: 20px;
            width: 80%;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
        }

        .section h2 {
            margin-bottom: 10px;
            color: #333;
        }

        .section p {
            color: #666;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }

        .about img {
            max-width: 150px;
            border-radius: 50%;
            margin-bottom: 20px;
        }

        .skills ul {
            list-style: none;
            padding: 0;
        }

        .skills ul li {
            background: #4CAF50;
            color: white;
            margin: 5px 0;
            padding: 10px;
            border-radius: 5px;
        }

        .projects img {
            max-width: 100%;
            border-radius: 8px;
        }

        .resume a {
            display: inline-block;
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
        }

        .resume a:hover {
            background-color: #45a049;
        }

        @media (max-width: 768px) {
            .section {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Suraj Tripathi</h1>
        <p>Creative Developer & Designer</p>
    </header>
    <nav>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#resume">Resume</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="hero">
        <h1>Welcome to My Portfolio</h1>
        <p>Discover my work, skills, and passion for development and design.</p>
    </div>
    <div class="sections">
        <div class="section about" id="about">
            <h2>About Me</h2>
            <img src="https://via.placeholder.com/150" alt="Suraj Tripathi">
            <p>Hi, I'm Suraj, a creative developer with a passion for building visually appealing and user-friendly websites. With expertise in HTML, CSS, and JavaScript, I bring ideas to life.</p>
        </div>
        <div class="section skills" id="skills">
            <h2>Skills</h2>
            <ul>
                <li>HTML & CSS</li>
                <li>JavaScript</li>
                <li>Responsive Design</li>
                <li>UI/UX Design</li>
                <li>Version Control (Git)</li>
            </ul>
        </div>
        <div class="section projects" id="projects">
            <h2>Projects</h2>
            <p>Here are some of my recent projects:</p>
            <img src="https://via.placeholder.com/300" alt="Project Image">
            <p><strong>Project 1:</strong> Portfolio Website </p>
            <img src=""C:\Users\SURAJ TRIPATHI\OneDrive\Desktop\WhatsApp Image 2024-12-15 at 00.16.31_283df6ec.jpg" alt="Project Image">
            <p><strong>Project 2:</strong> calculater</p>
        </div>
        <div class="section resume" id="resume">
            <h2>Resume</h2>
            <p>Download my resume to learn more about my experience and qualifications.</p>
            <a href="https://drive.google.com/file/d/1JUx9gBufSVF8mQbjCqPwjdPAfbflS7K6/view?usp=drivesdk" download>Download Resume</a>
        </div>
        <div class="section contact" id="contact">
            <h2>Contact</h2>
            <p>Email: surajtripathi7254@gmail.com</p>
            <p>Phone: 8303003824</p>
        </div>
    </div>
    <footer>
        <p>&copy; 2024 Suraj Tripathi. All rights reserved.</p>
    </footer>
</body>
</html>
