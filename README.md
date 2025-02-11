<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            background: url('online-security-dark-background-3d-illustration.jpg') no-repeat center center fixed;
            background-size: cover;
            font-family: Arial, sans-serif;
            color: white;
            text-align: center;
        }
        header {
            padding: 20px;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        section {
            margin: 50px 0;
        }
        .qualifications {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }
        .rectangle {
            background: rgba(0, 0, 0, 0.7);
            padding: 20px;
            border-radius: 10px;
            width: 200px;
            height: 100px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 18px;
        }
        .contact a {
            color: blue; 
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Portfolio</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="about">
        <h2>About Me</h2>
        <p>Certified in Autonomous Technology, currently studying Cybersecurity.</p>
    </section>
    
    <section id="projects">
        <h2>Projects</h2>
        <p>Here are some projects I’ve worked on. I've made a Minecraft server and a Plex server with old laptops.</p>
    </section>
    
    <section id="certs">
        <h2>Certifications</h2>
        <div class="qualifications">
            <div class="rectangle">Cert II in Autonomous Technology</div>
            <div class="rectangle">Cyber Security (Ongoing)</div>
        </div>
    </section>
    
    <section id="contact">
        <h2>Contact</h2>
        <p>Email: <a href="mailto:mail@willemc.me" >mail@willemc.me</a></p>
        <p>Phone: <a href="tel:+1234567890" >+Will add later</a></p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/willem-cashion-0bb144331/" >Willem's LinkedIn</a></p>
        <p>GitHub: <a href="https://github.com/willstar7222" >GitHub</a></p>
    </section>
</body>
</html>
