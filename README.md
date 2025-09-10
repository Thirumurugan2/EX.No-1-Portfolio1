# Ex01 Portfolio
## Date: 10-09-2025

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
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kailash Kumar - Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 40px;
            background-color: #f0f8ff;
            color: #333;
        }

        header {
            background-color: #f0f8ff;
            padding: 20px;
            border-radius: 8px;
        }

        .header-container {
            display: flex;
            align-items: center;
            gap: 20px;
        }

        .profile-pic {
            width: 150px;
            height: 180px;
            object-fit: cover;
            border-radius: 8px;
            border: 2px solid #0077b6;
        }

        .header-text h1 {
            margin: 0;
            font-size: 2em;
            color: #023e8a;
        }

        .header-text p {
            margin: 5px 0;
            font-size: 0.95em;
            color: #444;
        }

        section {
            margin: 20px 0;
            background: white;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0px 2px 5px rgba(0,0,0,0.1);
        }

        h2 {
            color: #0077b6;
            border-bottom: 2px solid #0077b6;
            padding-bottom: 5px;
        }

        a {
            color: #0077b6;
            text-decoration: none;
            font-weight: bold;
        }

        a:hover {
            text-decoration: underline;
            color: #03045e;
        }

        @media (max-width: 600px) {
            .header-container {
                flex-direction: column;
                text-align: center;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="header-container">
            <img src="kailash.jpg" alt="Kailash Kumar" class="profile-pic">
            <div class="header-text">
                <h1>Kailash Kumar</h1>
                <p>Computer Science Student</p>
                <p>Phone: 9876543210 | Email: kailash@example.com</p>
                <p>
                    <a href="https://github.com/yourgithub" target="_blank">GitHub</a> | 
                    <a href="https://linkedin.com/in/yourlinkedin" target="_blank">LinkedIn</a>
                </p>
            </div>
        </div>
    </header>

    <section>
        <h2>About Me</h2>
        <p>Passionate Computer Science student with strong problem-solving skills. 
        Interested in software development, data management, and participating in hackathons. 
        Skilled in multiple programming languages and enthusiastic about real-world problem solving.</p>
    </section>

    <section>
        <h2>Education</h2>
        <ul>
            <li>B.E. Computer Science Engineering, [SAVEETHA ENGINEERING COLLEGE], Chennai (2023–2027)</li>
            <li>Higher Secondary Schooling, [SSV] (Completed 2023)</li>
        </ul>
    </section>

    <section>
        <h2>Hackathon Experience</h2>
        <ul>
            <li>Participated in <b>Smart India Hackathon</b> at <b>Anna University, Chennai</b></li>
            <li>Developed innovative project idea during hackathon at <b>SRM Institute of Science & Technology, Chennai</b></li>
            <li>Contributed in a team project on problem-solving during hackathon at <b>Saveetha Engineering College, Chennai</b></li>
        </ul>
    </section>

    <section>
        <h2>Skills</h2>
        <ul>
            <li>Python</li>
            <li>Object Oriented Programming (OOPs)</li>
            <li>JavaScript</li>
            <li>SQL</li>
            <li>C Programming</li>
        </ul>
    </section>

    <section>
        <h2>Projects</h2>
        <ul>
            <li>Portfolio Website using HTML & CSS</li>
            <li>SQL Database for Student Management</li>
            <li>OOP-based Mini Applications in Python</li>
            <li>JavaScript Calculator and To-Do List</li>
        </ul>
    </section>

    <section>
        <h2>Contact</h2>
        <p>Email: kailash@example.com</p>
        <p>Phone: 9876543210</p>
    </section>
</body>
</html>

```

## OUTPUT
<img width="1869" height="913" alt="Screenshot 2025-09-10 152738" src="https://github.com/user-attachments/assets/301d0a19-b090-4b6c-b10b-a9e9167e5826" />
<img width="1774" height="525" alt="Screenshot 2025-09-10 152801" src="https://github.com/user-attachments/assets/5660bec9-78e6-4320-9fed-b95a5d6c68fe" />



## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
