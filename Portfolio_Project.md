# portfolio
## Basic HTML and CSS Portfolio Work
## HTML: 

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dhinesh Raj - Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Dhinesh Raj</h1>
        <img src="download (1).jpg" alt="Profile Picture">
        
        <h2>About Me</h2>
        <p>I'm Dhinesh Raj, an ECE Engineer, graduated from Saveetha Engineering College.</p>
        
        <h2>Skills</h2>
        <ul>
            <li>Java</li>
            <li>Python</li>
            <li>UI/UX Designing</li>
        </ul>
        
        <h2>Projects</h2>
        <div class="projects">
            <div class="project-card">
                <img src="link.jpg" alt="Project 1">
                <h3>Project 1</h3>
                <p>A full-stack job search website portal.</p>
            </div>
            <div class="project-card">
                <img src="e-commerce.jpg" alt="Project 2">
                <h3>Project 2</h3>
                <p>An E-commerce website.</p>
            </div>
        </div>
        
        <h2>Contact</h2>
        <form action="submit.php" method="post">
            <label for="name">Name</label>
            <input type="text" name="name" id="name" required>
            
            <label for="email">E-Mail</label>
            <input type="email" name="email" id="email" required>
            
            <label for="message">Message</label>
            <textarea name="message" id="message" rows="4" required></textarea>
            
            <button type="submit">Submit</button>
        </form>
    </div>
</body>
</html>
```

## CSS :

```
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 20px;
    background-color: #f9f9f9;
    text-align: center;
    color: #333;
}

.container {
    max-width: 800px;
    margin: auto;
    background: white;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

img {
    max-width: 150px;
    border-radius: 50%;
    margin-bottom: 15px;
}

ul {
    list-style-type: none;
    padding: 0;
}

li {
    background: #ececec;
    margin: 5px;
    padding: 10px;
    border-radius: 5px;
}

.projects {
    display: flex;
    flex-direction: column;
    align-items: center;
}

.project-card {
    background: #fff;
    padding: 15px;
    margin: 10px 0;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    width: 100%;
    text-align: left;
}

.project-card img {
    width: 100%;
    border-radius: 5px;
}

form {
    display: flex;
    flex-direction: column;
    align-items: center;
}

input, textarea {
    width: 90%;
    padding: 10px;
    margin: 5px 0;
    border: 1px solid #ccc;
    border-radius: 5px;
    font-size: 1rem;
}

button {
    padding: 10px 20px;
    background: #007BFF;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: background 0.3s;
}

button:hover {
    background: #0056b3;
}
```
