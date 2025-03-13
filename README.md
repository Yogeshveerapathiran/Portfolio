# Ex01 Portfolio
## Date:

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
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Yogesh V.S. - Portfolio</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <header>
      <div class="container">
        <h1>Yogesh V.S.</h1>
        <p>Web Developer | Cloud Enthusiast | AI/ML Researcher</p>
      </div>
    </header>

    <section class="about">
      <div class="container">
        <img src="image.jpg" alt="Yogesh V.S." class="profile-pic" />
        <p>
          Hello! I am Yogesh V.S., a passionate web developer and cloud
          enthusiast. I specialize in building web applications and exploring
          AI/ML innovations.
        </p>
      </div>
    </section>

    <section class="projects">
      <div class="container">
        <h2>Projects</h2>
        <ul>
          <li>
            <strong>Automated Fruit Grading System</strong> - AI-based fruit
            grading using machine learning.
          </li>
          <li>
            <strong>Personal Finance Dashboard</strong> - A Flask-based
            financial analysis tool.
          </li>
          <li>
            <strong>DTC Bus Scheduling App</strong> - Smart India Hackathon
            project for bus route optimization.
          </li>
        </ul>
      </div>
    </section>

    <section class="contact">
      <div class="container">
        <h2>Contact Me</h2>
        <p>
          Email:
          <a href="mailto:yogesh.v.s2004@gmail.com">yogesh.v.s2004@gmail.com</a>
        </p>
        <p>
          LinkedIn:
          <a href="www.linkedin.com/in/yogesh-v-s-5811831bb" target="_blank"
            >www.linkedin.com/in/yogesh-v-s-5811831bb</a
          >
        </p>
      </div>
    </section>
  </body>
</html>
```
```css
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f4f4f4;
  text-align: center;
}

header {
  background-color: #333;
  color: white;
  padding: 20px;
}

.container {
  width: 80%;
  margin: auto;
  padding: 20px;
}

.profile-pic {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  margin-top: 10px;
}

.about,
.projects,
.contact {
  background: white;
  margin: 20px auto;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
}

ul {
  list-style-type: none;
  padding: 0;
}

a {
  text-decoration: none;
  color: #0073e6;
}
```


## OUTPUT
![image](https://github.com/user-attachments/assets/e9cce2da-963c-4e85-8811-a43e6372b45b)
![image](https://github.com/user-attachments/assets/635c13d9-4f18-42b5-b9c7-243d79756420)


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
