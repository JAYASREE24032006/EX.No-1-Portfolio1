# EX01 - PORTOFOLIO

## DATE : 04.03.2025

## AIM :
To create a Portfolio using HTML and CSS.

## ALGORITHM :
### STEP 1 :
Create an HTML file (new.html)

### STEP 2 :
Create a CSS file (style1.css)

### STEP 3 :
Include a navigation bar with links to different sections.

### STEP 4 :
Add structured sections for introduction, about, projects, and contact details.

### STEP 5 :
Define global styles for fonts, colors, and layout.

### STEP 6 :
Style the header, navigation bar, and sections.

### STEP 7 :
Use Flexbox or CSS Grid for layout design.

### STEP 8 :
Add hover effects and transitions for interactivity.

### STEP 9 :
Add Images and Media.

### STEP 10 :
Use optimized images for a professional look.

### STEP 11 :
Open the HTML file in a browser to check layout and functionality.

### STEP 12 :
Fix styling issues and refine content placement.

### STEP 13 :
Deploy the Portfolio.

### STEP 14 :
Upload to GitHub Pages for free hosting.

## PROGRAM :

### new.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <title>R. Jayasree – Portfolio</title>
    <link rel="stylesheet" href="style1.css" />
</head>
<body>

<header>
    <nav class="navbar">
        <div class="logo">R. Jayasree</div>
        <ul class="nav-links">
            <li><a href="#about">About</a></li>
            <li><a href="#education">Education</a></li>
            <li><a href="#experience">Experience</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
</header>

<main class="main-content">
  <section id="about" class="hero about-section">
    <div class="about-grid">
        <div class="profile-photo">
            <img src="photo.png" alt="R. Jayasree">
        </div>
        <div class="hero-text">
            <h1>Hello, I'm R. Jayasree</h1>
            <p>Computer Science & Data Science Enthusiast</p>
            <a href="https://www.linkedin.com/in/your-linkedin-id" target="_blank" class="linkedin-btn">Visit my LinkedIn</a>
            <a href="jayasree2403206@gmail.com" class="linkedin-btn">jayasree2403206@gmail.com</a>
        </div>
    </div>
</section>


    <section id="education" class="content-section">
      <div>
        <h1 style="background-color: #2c3e50;color: white;text-align: center;">Education</h1>
      </div>

        <ul class="grid-list">
            <li><strong>B.E. in Computer Science and Engineering</strong> – Saveetha Engineering College, Chennai</li>
            <li><strong>B.Sc. in Data Science and Applications</strong> – IIT Madras (Online Degree Program)</li>
            <li><strong>12th Grade</strong> – 89% (2nd Rank), Chennai Higher Secondary School</li>
            <li><strong>11th Grade</strong> – 90% (1st Rank), Chennai Higher Secondary School</li>
        </ul>
    </section>

    <section id="experience" class="content-section">
      <div>
        <h1 style="background-color: #2c3e50;color: white;text-align: center;">Internship & Experience</h1>
      </div>
        <ul class="grid-list">
            <li><strong>Certified Ethical Hacker Intern</strong> – Zybeak Technologies</li>
            <li><strong>Web Developer Intern</strong> – Computational Intelligence and Technology</li>
            <li><strong>Volunteer & Scholar</strong> – Team Everest NGO</li>
            <li><strong>Online Internship</strong> – Oracle – Job Readiness Skills for Girls</li>
            <li><strong>Project</strong> – Recipe App developed during in-plant training</li>
        </ul>
    </section>

    <section id="skills" class="content-section">
      <div>
        <h1 style="background-color: #2c3e50;color: white;text-align: center;">SKills</h1>
      </div>
        <ul>
            <li><strong>Programming Languages:</strong> Python, C++</li><br>
            <li><strong>Web Technologies:</strong> HTML5, CSS3, JavaScript</li><br>
            <li><strong>Frameworks & Tools:</strong> Firebase, VS Code, Git</li><br>
            <li><strong>Data Science:</strong> Machine Learning, Data Analysis</li><br>
            <li><strong>Soft Skills:</strong> Problem Solving, Team Collaboration</li>
        </ul>
    </section>

    <section id="certifications" class="content-section">
      <div>
        <h1 style="background-color: #2c3e50;color: white;text-align: center;">Certifications</h1>
      </div>
      <div class="cert-grid">
          <div class="cert-card">
              <img src="cirf.jpg" alt="Web Dev Internship Certificate - CIRF">
              <p><strong>Web Development Inplant Training</strong><br>Computational Intelligence Research Foundation – July 2024</p>
          </div>
          <div class="cert-card">
              <img src="intern.jpg" alt="Ethical Hacking Internship - Zybeak">
              <p><strong>Cybersecurity-Ethical Hacking Internship</strong><br>Zybeak Technologies – Jan 2025</p>
          </div>
          <div class="cert-card">
              <img src="iitm.jpg" alt="IITM Foundation Certificate">
              <p><strong>IIT Madras Foundation Level</strong><br>B.Sc. Data Science – Dec 2024</p>
              <a href="iitm.pdf" download class="download-btn">Download PDF</a>
          </div>
      </div>
  </section>
  

    <section id="contact" class="content-section contact-section">
      <div>
        <h1 style="background-color: #2c3e50;color: white;text-align: center;">Contact</h1>
      </div>
        <form action="#" method="POST" class="contact-form">
            <input type="text" name="name" placeholder="Your Name" required />
            <input type="email" name="email" placeholder="Your Email" required />
            <textarea name="message" rows="5" placeholder="Your Message"></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>
</main>




<footer>
    <p>&copy; 2025 R. Jayasree. All rights reserved.</p>
</footer>

</body>
</html>

```


### style1.css


```
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', sans-serif;
  line-height: 1.6;
  background-color: #f9f9f9;
  color: #333;
}

header {
  background-color: #2c3e50;
  padding: 1rem 2rem;
}

.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap;
}

.logo {
  color: #fff;
  font-size: 1.5rem;
  font-weight: bold;
}

.nav-links {
  display: flex;
  list-style: none;
  gap: 1rem;
}

.nav-links li a {
  color: #fff;
  text-decoration: none;
  font-weight: 500;
}

.nav-links li a:hover {
  text-decoration: underline;
}


.hero {
  background-color: #ecf0f1;
  padding: 4rem 2rem;
  text-align: center;
}

.hero-text h1 {
  font-size: 2.5rem;
  color: #2c3e50;
}

.hero-text p {
  font-size: 1.2rem;
  color: #34495e;
}

.content-section {
  padding: 2rem;
  background-color: #fff;
  margin: 1rem auto;
  max-width: 1000px;
  border-radius: 10px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.content-section h2 {
  margin-bottom: 1rem;
  color: #2c3e50;
}


.grid-list {
  display: grid;
  grid-template-columns: 1fr;
  gap: 1rem;
}




.contact-form {
  display: grid;
  gap: 1rem;
  max-width: 600px;
  margin: 0 auto;
}

.contact-form input,
.contact-form textarea {
  padding: 0.75rem;
  border: 1px solid #ccc;
  border-radius: 5px;
  font-size: 1rem;
}

.contact-form button {
  padding: 0.75rem;
  background-color: #2c3e50;
  color: white;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

.contact-form button:hover {
  background-color: #34495e;
}


footer {
  text-align: center;
  padding: 1rem;
  background-color: #2c3e50;
  color: white;
}

.cert-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 2rem;
  margin-top: 1.5rem;
}

.cert-card {
  background: #fff;
  border-radius: 10px;
  overflow: hidden;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
  text-align: center;
  padding: 1rem;
  transition: transform 0.3s, box-shadow 0.3s;
}

.cert-card img {
  width: 100%;
  height: 200px;
  object-fit: cover;
  border-radius: 8px;
}

.cert-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 16px rgba(0,0,0,0.2);
}

.cert-card p {
  margin-top: 0.5rem;
  font-size: 0.95rem;
  color: #2c3e50;
}

.download-btn {
  display: inline-block;
  margin-top: 0.75rem;
  padding: 0.5rem 1rem;
  background-color: #2c3e50;
  color: #fff;
  text-decoration: none;
  border-radius: 5px;
  transition: background-color 0.3s;
}

.download-btn:hover {
  background-color: #34495e;
}

.about-grid {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
  gap: 2rem;
  text-align: center;
}

.profile-photo img {
  width: 200px;
  height: 240px;
  object-fit: cover;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

.linkedin-btn {
  display: inline-block;
  margin-top: 1rem;
  padding: 0.6rem 1.2rem;
  background-color: #0077b5;
  color: white;
  text-decoration: none;
  border-radius: 5px;
  transition: background 0.3s;
}

.linkedin-btn:hover {
  background-color: #005a8c;
}

```


## OUTPUT :

![image](https://github.com/user-attachments/assets/b8e85111-9f00-4b9c-b1b7-a3b422489383)
![image](https://github.com/user-attachments/assets/936ca938-027c-49c7-8d03-e074b775fc3a)
![image](https://github.com/user-attachments/assets/2dcfc24b-3088-45d1-a91c-bcc26c1f83f8)
![image](https://github.com/user-attachments/assets/dd88bfd4-3cb5-4d0d-9cf6-84c6490ba30a)


## RESULT :
Thus the Portofolio is created successfully using HTML and CSS






## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
