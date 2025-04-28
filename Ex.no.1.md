# Ex01 Portfolio
## Date: 04.03.2025

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
index.html

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Karthickkumar R - Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Karthickkumar R</h1>
        <p>Web Developer | UI/UX Designer | Tech Enthusiast</p>
    </header>

    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#testimonials">Testimonials</a></li>
            <li><a href="#blog">Blog</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <div class="container">
        <section id="about" class="about">
            <h2>About Me</h2>
            <p>Hi, I'm <span class="highlight">Karthickkumar R</span>, a passionate web developer with a knack for creating <span class="highlight">visually stunning</span> and <span class="highlight">highly functional</span> websites. With over 6 years of experience, I specialize in crafting digital experiences that are both intuitive and engaging.</p>
            <p>My journey in web development began with a curiosity for how the internet works, leading me to master front-end technologies like HTML, CSS, and JavaScript. I thrive on solving complex problems and transforming ideas into reality through clean, efficient code.</p>
            <p>Beyond coding, I enjoy sharing my knowledge through tech blogs, mentoring budding developers, and staying updated with the latest industry trends. My goal is to build websites that not only meet client expectations but also leave a lasting impression on users.</p>
        </section>

        <section id="projects" class="projects">
            <h2>My Projects</h2>
            <div class="projects-grid">
                <div class="project-card">
                    <h3>Personal Portfolio</h3>
                    <p>A responsive portfolio showcasing my skills, projects, and achievements using HTML and CSS.</p>
                    <a href="#">View Project</a>
                </div>
                <div class="project-card">
                    <h3>Online Learning Platform</h3>
                    <p>A user-friendly e-learning site with course listings, quizzes, and progress tracking.</p>
                    <a href="#">View Project</a>
                </div>
                <div class="project-card">
                    <h3>Event Management System</h3>
                    <p>A web app for organizing events, managing registrations, and sending notifications.</p>
                    <a href="#">View Project</a>
                </div>
                <div class="project-card">
                    <h3>Travel Blog</h3>
                    <p>A vibrant blog platform for sharing travel experiences with a clean, modern design.</p>
                    <a href="#">View Project</a>
                </div>
                <div class="project-card">
                    <h3>Fitness Tracker</h3>
                    <p>A web-based tool to track workouts, set fitness goals, and monitor progress.</p>
                    <a href="#">View Project</a>
                </div>
            </div>
        </section>

        <section id="skills" class="skills">
            <h2>Technical Skills</h2>
            <div class="skills-list">
                <span class="skill">HTML5</span>
                <span class="skill">CSS3</span>
                <span class="skill">JavaScript</span>
                <span class="skill">Responsive Design</span>
                <span class="skill">SASS/SCSS</span>
                <span class="skill">Git & GitHub</span>
                <span class="skill">UI/UX Design</span>
                <span class="skill">Web Accessibility</span>
                <span class="skill">SEO Optimization</span>
                <span class="skill">Bootstrap</span>
            </div>
        </section>

        <section id="testimonials" class="testimonials">
            <h2>What People Say</h2>
            <div class="testimonials-grid">
                <div class="testimonial-card">
                    <p>"Karthickkumar's work on our website was phenomenal. His creativity and professionalism made the process seamless."</p>
                    <p class="author">Priya Sharma, CEO of InnovateTech</p>
                </div>
                <div class="testimonial-card">
                    <p>"He revamped our outdated platform into a modern, responsive site. His attention to detail is unmatched."</p>
                    <p class="author">Arun Kumar, Founder of NextGen Solutions</p>
                </div>
                <div class="testimonial-card">
                    <p>"Karthickkumar's expertise in UI/UX design transformed our user experience. Highly recommended!"</p>
                    <p class="author">Meera Patel, Marketing Head at GrowEasy</p>
                </div>
                <div class="testimonial-card">
                    <p>"His ability to deliver projects on time without compromising quality is impressive. A true professional."</p>
                    <p class="author">Vikram Singh, CTO of TechTrend</p>
                </div>
            </div>
        </section>

        <section id="blog" class="blog-preview">
            <h2>Recent Blog Posts</h2>
            <div class="blog-preview-grid">
                <div class="blog-card">
                    <h3>Top Web Development Trends for 2025</h3>
                    <p>Discover how AI, PWAs, and voice search are shaping the future of the web.</p>
                    <a href="#">Read More</a>
                </div>
                <div class="blog-card">
                    <h3>Building Responsive Layouts with CSS Grid</h3>
                    <p>A beginner-friendly guide to creating flexible, responsive designs.</p>
                    <a href="#">Read More</a>
                </div>
                <div class="blog-card">
                    <h3>Why Accessibility is Key to Modern Web Design</h3>
                    <p>Learn practical tips to make your websites inclusive for everyone.</p>
                    <a href="#">Read More</a>
                </div>
                <div class="blog-card">
                    <h3>Optimizing Websites for SEO in 2025</h3>
                    <p>Strategies to boost your site's visibility on search engines.</p>
                    <a href="#">Read More</a>
                </div>
            </div>
        </section>

        <section id="contact" class="contact">
            <h2>Get in Touch</h2>
            <div class="contact-info">
                <p>Email: <a href="mailto:karthickkumar@example.com">karthickkumar@example.com</a></p>
                <p>Phone: <a href="tel:+919876543210">+91 98765 43210</a></p>
                <p>LinkedIn: <a href="#">linkedin.com/in/karthickkumar-r</a></p>
                <p>GitHub: <a href="#">github.com/karthickkumar-r</a></p>
                <p>Twitter: <a href="#">twitter.com/karthickkumar_r</a></p>
            </div>
        </section>
    </div>

    <footer>
        <p>© 2025 Karthickkumar R. Crafted with dedication and innovation.</p>
    </footer>
</body>
</html>
```

style.css
```
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

body {
    line-height: 1.6;
    color: #333;
    background: #f4f4f4;
}

header {
    background: linear-gradient(to right, #1a3c5e, #3b7a9e);
    color: white;
    text-align: center;
    padding: 3.5rem 1rem;
}

header h1 {
    font-size: 3.2rem;
    margin-bottom: 0.6rem;
}

header p {
    font-size: 1.3rem;
    opacity: 0.9;
}

nav {
    background: #2c3e50;
    padding: 1rem;
    position: sticky;
    top: 0;
    z-index: 100;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    gap: 2.5rem;
}

nav a {
    color: white;
    text-decoration: none;
    font-weight: 600;
    font-size: 1.1rem;
}

nav a:hover {
    color: #1abc9c;
    border-bottom: 2px solid #1abc9c;
    padding-bottom: 0.3rem;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 2rem;
}

section {
    margin-bottom: 4rem;
    background: white;
    padding: 2.5rem;
    border-radius: 10px;
    box-shadow: 0 5px 12px rgba(0,0,0,0.1);
}

section h2 {
    color: #2c3e50;
    margin-bottom: 1.5rem;
    font-size: 2.2rem;
    border-bottom: 3px solid #1abc9c;
    padding-bottom: 0.6rem;
}

.about p {
    margin-bottom: 1.2rem;
    font-size: 1.1rem;
}

.about .highlight {
    color: #1abc9c;
    font-weight: bold;
}

.projects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
}

.project-card {
    background: #f9f9f9;
    padding: 1.8rem;
    border-radius: 10px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    text-align: center;
    transition: transform 0.3s, box-shadow 0.3s;
}

.project-card:hover {
    transform: translateY(-8px);
    box-shadow: 0 6px 15px rgba(0,0,0,0.15);
}

.project-card h3 {
    color: #2c3e50;
    margin-bottom: 1rem;
    font-size: 1.5rem;
}

.project-card p {
    font-size: 1rem;
    margin-bottom: 1.2rem;
}

.project-card a {
    color: #1abc9c;
    text-decoration: none;
    font-weight: bold;
}

.project-card a:hover {
    text-decoration: underline;
}

.skills-list {
    display: flex;
    flex-wrap: wrap;
    gap: 1rem;
}

.skill {
    background: #1abc9c;
    color: white;
    padding: 0.7rem 1.4rem;
    border-radius: 25px;
    font-size: 1rem;
}

.testimonials-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 2rem;
}

.testimonial-card {
    background: #f9f9f9;
    padding: 1.8rem;
    border-radius: 10px;
    text-align: center;
    font-style: italic;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
}

.testimonial-card p {
    margin-bottom: 1.2rem;
}

.testimonial-card .author {
    font-weight: bold;
    color: #2c3e50;
    font-style: normal;
}

.blog-preview-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
}

.blog-card {
    background: #f9f9f9;
    padding: 1.8rem;
    border-radius: 10px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
}

.blog-card h3 {
    color: #2c3e50;
    margin-bottom: 1rem;
    font-size: 1.4rem;
}

.blog-card a {
    color: #1abc9c;
    text-decoration: none;
    font-weight: bold;
}

.blog-card a:hover {
    text-decoration: underline;
}

.contact-info {
    text-align: center;
    font-size: 1.2rem;
}

.contact-info a {
    color: #1abc9c;
    text-decoration: none;
}

.contact-info a:hover {
    text-decoration: underline;
}

.contact-info p {
    margin-bottom: 1rem;
}

footer {
    background: #2c3e50;
    color: white;
    text-align: center;
    padding: 2rem;
    width: 100%;
}

footer p {
    font-size: 1.1rem;
}

@media (max-width: 768px) {
    header h1 {
        font-size: 2.5rem;
    }

    header p {
        font-size: 1.1rem;
    }

    nav ul {
        flex-direction: column;
        gap: 1.2rem;
        text-align: center;
    }

    .container {
        padding: 1.5rem;
    }

    section {
        padding: 2rem;
    }

    .project-card, .testimonial-card, .blog-card {
        padding: 1.5rem;
    }
}
```


## OUTPUT
Home
![Screenshot 2025-04-29 000405](https://github.com/user-attachments/assets/8aba6340-8e03-46f6-b7a0-a7f0e8e5594b)

Projects
![Screenshot 2025-04-29 000413](https://github.com/user-attachments/assets/4566f578-71ad-43ec-a785-df477f67cc38)

Skills
![Screenshot 2025-04-29 000424](https://github.com/user-attachments/assets/d8cb00e1-21b9-4e19-bffd-272498f53b9e)

Blog
![Screenshot 2025-04-29 000433](https://github.com/user-attachments/assets/792b1e6a-cf89-492d-94e5-8e55cba8fbc8)

Contacts
![Screenshot 2025-04-29 000441](https://github.com/user-attachments/assets/6b297951-f0f4-4e00-abb8-e5d2d5590122)


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
