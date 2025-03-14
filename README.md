# Ex01 Portfolio
## Date:14/03/2025

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About Me</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h1>Welcome to My Portfolio</h1>
        <p>Welcome to my portfolio! Here, you can find a collection of projects that showcase my skills and passion for web development.</p>
    </section>

    <section id="about">
        <h2>About Me</h2>
        <img src="vasavi.jpg" alt="Profile Picture" width="250" id="photo" >
        <p>Hi, I am Dappili Vasavi i am currently pursuing B.E second year in the department of Computer Science and Engineering,in Saveetha Engineering College.My goal is to keep improving, learn new techniques, and build even more complex projects in the future.</p>
    </section>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <p>Here are a few of the projects I've worked on:</p>
        <ul>
            <li>Project 1: Personal Portfolio Website</li>
            <li>Project 2: Recipe Book</li>
            <li>Project 3: Contact Form</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>Contact Me:</p>
        <ul>
            <li>Email: vasavireddy123@gmail.com</li>
            <li>LinkedIn:  linkedin.com/in/VasaviReddy</li>
            <li>GitHub: github.com/VasaviDappili</li>
            <li>Phone No: 1234567890</li>

        </ul>
    </section>

    <footer>
        <p>&copy; 2025 Your Name. All Rights Reserved.</p>
    </footer>
</body>
</html>
```

##Style.CSS

```
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color:grey;
    line-height: 1.6;
}

header {
    background-color: #333;
    color: #fff;
    padding: 10px 0;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}


section {
    padding: 40px;
    margin: 20px 0;
    background-color: #fff;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

section h1, section h2 {
    color: #333;
}


nav ul li a:hover {
    color: #ff6347;
    transition: color 0.3s ease;
}


#about img {
    max-width: 100%;
    border-radius: 8px;
    margin-top: 20px;
}


footer {
    background-color: #333;
    color: white;
    padding: 20px;
    text-align: center;
}


body {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: flex-start;
}

header, footer {
    width: 100%;
}

section {
    width: 80%;
    max-width: 900px;
    margin: 20px 0;
}
#photo{

    margin-left: 290px;
   
}
#home{
    background-color: #ffcbcb;
}
#about{
    background-color: #ffcbcb;
}
#projects{
    background-color: #ffcbcb;
}
#contact{
    background-color: #ffcbcb;
}


```
  


## OUTPUT
![Screenshot (209)](https://github.com/user-attachments/assets/6160b36a-742e-4106-a935-2ddcae461a71)
![Screenshot (210)](https://github.com/user-attachments/assets/81515d9a-cd9e-4d83-a748-aa3c1d053ddf)
![Screenshot (211)](https://github.com/user-attachments/assets/92703518-e36a-4be4-8f98-afada2371a04)
![Screenshot (215)](https://github.com/user-attachments/assets/fe95cc4d-a81e-49a0-a0d1-d7e37368f23b)






## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
