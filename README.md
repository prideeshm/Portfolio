# Ex01 Portfolio
## Date:13.08.2025

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
```
## INDEX.HTML

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    
    <header>
        <nav>
            <h1 class="logo">MyPortfolio</h1>
            <ul class="nav-links">
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <h2>Hello, I'm <span>PRIDEESH</span></h2>
        <p>Aspiring Machine Learning & Web Developer</p>
        <a href="#projects" class="btn">View My Work</a>
    </section>

    <section id="about" class="about">
        <img src="prideesh.jpg" alt="My Photo">
        <h2>About Me</h2>
        <p>
            I'm a passionate developer who loves building interactive web apps and AI-powered projects.
            Skilled in HTML, CSS, JavaScript, Python, and Machine Learning frameworks.
        </p>
    </section>

    <section id="projects" class="projects">
        <h2>Projects</h2>
        <div class="project-grid">
            <a href="https://github.com/username/healthcare-prediction-app" target="_blank" class="project-link">
                <div class="project-card">
                    <h3>Healthcare Prediction App</h3>
                    <p>ML-powered app to predict diseases and suggest precautions.</p>
                </div>
            </a>
            <a href="https://github.com/username/stock-price-predictor" target="_blank" class="project-link">
                <div class="project-card">
                    <h3>Stock Price Predictor</h3>
                    <p>Flask-based app predicting stock prices using Keras models.</p>
                </div>
            </a>
            <a href="https://github.com/username/number-plate-recognition" target="_blank" class="project-link">
                <div class="project-card">
                    <h3>Number Plate Recognition</h3>
                    <p>YOLOv5 and OCR-based vehicle number plate detection.</p>
                </div>
            </a>
        </div>
    </section>

    <section id="contact" class="contact">
        <h2>Contact Me</h2>
        <p>Email: <a href="mailto:prideesh1926@gmail.com">prideesh1926@gmail.com</a></p>
        <p>
            <a href="https://github.com/prideeshm" target="_blank">GitHub</a> 
        </p>
    </section>

    <footer>
        <p>&copy; 2025 Prideesh. All Rights Reserved.</p>
    </footer>
</body>
</html>



## STYLE.CSS

html {
    scroll-behavior: smooth;
}

body {
    font-family: Arial, sans-serif;
    margin: 0;
    background-color: #f4f4f4;
    color: #333;
    padding-top: 60px;
}


header {
    background: #222;
    padding: 15px 0;
    position: fixed;
    width: 100%;
    top: 0;
    z-index: 1000;
}
nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    max-width: 1100px;
    margin: auto;
    padding: 0 20px;
}
.logo {
    color: #fff;
    font-size: 1.5em;
}
.nav-links {
    list-style: none;
    display: flex;
}
.nav-links li {
    margin-left: 20px;
}
.nav-links a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
}
.nav-links a:hover {
    color: #00bcd4;
}


.hero {
    background: linear-gradient(to right, #00bcd4, #009688);
    color: #fff;
    text-align: center;
    padding: 100px 20px;
}
.hero h2 {
    font-size: 2.5em;
}
.hero span {
    color: #ffeb3b;
}
.hero .btn {
    display: inline-block;
    margin-top: 15px;
    padding: 10px 20px;
    background: #ffeb3b;
    color: #333;
    text-decoration: none;
    font-weight: bold;
    border-radius: 5px;
}
.hero .btn:hover {
    background: #ffc107;
}


.about {
    padding: 50px 20px;
    max-width: 800px;
    margin: auto;
    text-align: center;
}
.about img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    object-fit: cover;
    border: 4px solid #00bcd4;
    margin-bottom: 15px;
}


.projects {
    background: #fff;
    padding: 50px 20px;
}
.project-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
}
.project-card {
    background: #fafafa;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    text-align: center;
    transition: 0.3s ease;
}
.project-card:hover {
    transform: scale(1.05);
    box-shadow: 0 5px 15px rgba(0,0,0,0.2);
}


.contact {
    background: #02b4cb;
    color: #fff;
    padding: 50px 20px;
    text-align: center;
}
.contact a {
    color: #ffeb3b;
    text-decoration: none;
}
.contact a:hover {
    text-decoration: underline;
}


footer {
    background: #222;
    color: #fff;
    padding: 15px;
    text-align: center;
}


@media (max-width: 600px) {
    .hero h2 {
        font-size: 1.8em;
    }
}


```

## OUTPUT

<img width="1911" height="1073" alt="Screenshot 2025-08-13 094722" src="https://github.com/user-attachments/assets/769bf601-d32d-4a4f-bdeb-14beac47d4c7" />

<img width="1912" height="1079" alt="Screenshot 2025-08-13 094751" src="https://github.com/user-attachments/assets/054eb1d0-9e49-4ff1-a95f-1972e8a5b3f9" />


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
