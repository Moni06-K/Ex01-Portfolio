# Ex01-Portfolio

## Date:30.10.2026
## NAME:MONISHA.A.K
## REGISTER NUMBER:212225230187

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
### index.html
```
<!DOCTYPE html>
<html>
<head>
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Navigation Bar -->
    <nav>
        <h2>My Portfolio</h2>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <!-- Home Section -->
    <section id="home">
        <h1>Hello, I'm Abinaya!</h1>
        <h3>AI & Data Science Student</h3>
        <p>Welcome to my personal portfolio website.</p>
    </section>

    <!-- About Section -->
    <section id="about">
        <h2>About Me</h2>
        <p>
            I am a B.Tech Artificial Intelligence and
            Data Science student. I am interested in
            Data Analytics, Artificial Intelligence and
            Web Development.
        </p>
    </section>

    <!-- Skills Section -->
    <section id="skills">
        <h2>My Skills</h2>
        <p>Python | C | HTML | CSS | SQL</p>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <h2>My Projects</h2>
        <h3>Portfolio Website</h3>
        <p>A personal website created using HTML and CSS.</p>

        <h3>Call Centre Performance Metrics</h3>
        <p>A data analytics project to analyze call centre performance.</p>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Me</h2>
        <p>Email: yourmail@gmail.com</p>
        <p>Location: Chennai, Tamil Nadu</p>
    </section>

    <footer>
        <p>© 2026 Abinaya. All Rights Reserved.</p>
    </footer>

</body>
</html>
```

 ### Style.css
```

/* Global Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
}

/* Navigation Bar */
nav {
    background-color: #222;
    color: white;
    padding: 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

nav ul {
    display: flex;
    list-style: none;
    gap: 20px;
}

nav a {
    color: white;
    text-decoration: none;
}

nav a:hover {
    color: orange;
}

/* Sections */
section {
    padding: 60px;
    text-align: center;
}

#home {
    background-color: #dceeff;
    padding: 100px 20px;
}

h1 {
    font-size: 40px;
    margin-bottom: 15px;
}

h2 {
    margin-bottom: 20px;
    color: #222;
}

p {
    line-height: 1.8;
}

/* Projects */
#projects {
    background-color: white;
}

/* Hover Effect */
section:hover {
    transition: 0.3s;
}

/* Footer */
footer {
    background-color: #222;
    color: white;
    text-align: center;
    padding: 20px;
}
```

### OUTPUT
<img width="1881" height="956" alt="image" src="https://github.com/user-attachments/assets/1557c2c8-c18d-4366-a1cd-59fdf7c9d989" />




## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
