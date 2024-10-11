# mostafaessousy.githup.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name - Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Your Name</h1>
        <p>Primary School Teacher Candidate | Morocco</p>
    </header>
    
    <section id="about">
        <h2>About Me</h2>
        <p>Hello, I'm a passionate candidate preparing for the primary school teaching exam in Morocco...</p>
    </section>
    
    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>Curriculum Planning</li>
            <li>Classroom Management</li>
            <li>Lesson Preparation</li>
            <li>Communication Skills</li>
        </ul>
    </section>
    
    <section id="education">
        <h2>Education</h2>
        <p>Bachelor's Degree in Education, University of [Your University]</p>
    </section>
    
    <section id="experience">
        <h2>Experience</h2>
        <p>Internship at [School Name], City</p>
    </section>
    
    <section id="contact">
        <h2>Contact Me</h2>
        <p>Email: your.email@example.com</p>
    </section>
</body>
</html>
Sample style.css:
css
Copier le code
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #007acc;
    color: white;
    text-align: center;
    padding: 1em 0;
}

section {
    margin: 2em auto;
    padding: 1em;
    max-width: 800px;
    background-color: white;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

h1, h2 {
    color: #007acc;
}

ul {
    list-style-type: none;
    padding: 0;
}

ul li {
    background-color: #007acc;
    color: white;
    padding: 0.5em;
    margin-bottom: 0.5em;
    border-radius: 5px;
}
5. Push the Files to GitHub
You can use GitHub’s built-in file upload feature or use git to push files from your local computer.
If you’re familiar with the command line, here are the basic steps:
bash
Copier le code
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/yourusername/yourusername.github.io.git
git push -u origin main
