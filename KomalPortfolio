<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Komal Sai Raj Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>

<body>
    <div class="cursor"></div>

    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About Me</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#certifications">Certifications</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact Me</a></li>
        </ul>
    </nav>

    <section id="home">
        <h1>Welcome to Komal Sai Raj's Portfolio</h1>
    </section>

    <section id="about">
        <h2>About Me</h2>
        <p>Write about yourself here.</p>
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>Skill 1</li>
            <li>Skill 2</li>
            <li>Skill 3</li>
        </ul>
    </section>

    <section id="certifications">
        <h2>Certifications</h2>
        <ul>
            <li>Certification 1</li>
            <li>Certification 2</li>
            <li>Certification 3</li>
        </ul>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <ul>
            <li>Project 1</li>
            <li>Project 2</li>
            <li>Project 3</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <p>Email: yourname@example.com</p>
    </section>

    <script src="scripts.js"></script>
</body>

</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
    background-color: #f4f4f4;
}

nav {
    background-color: #333;
    padding: 10px 0;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
}

nav ul li {
    margin: 0 20px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-size: 18px;
}

section {
    padding: 60px 20px;
    text-align: center;
}

#home {
    background-color: #4CAF50;
    color: white;
}

#about, #skills, #certifications, #projects, #contact {
    background-color: #f9f9f9;
    margin-top: 10px;
}

.cursor {
    width: 20px;
    height: 20px;
    background-color: #000;
    border-radius: 50%;
    position: absolute;
    transform: translate(-50%, -50%);
    pointer-events: none;
    z-index: 1000;
}

const cursor = document.querySelector('.cursor');

document.addEventListener('mousemove', (e) => {
    cursor.style.left = e.clientX + 'px';
    cursor.style.top = e.clientY + 'px';
});

document.addEventListener('click', () => {
    cursor.classList.add('expand');

    setTimeout(() => {
        cursor.classList.remove('expand');
    }, 500);
});
