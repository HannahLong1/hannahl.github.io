# hannahl.github.io
git clone https://github.com/hannahl/hannahl.github.io
cd username.github.io

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
        <h1>Welcome to My Portfolio</h1>
    </header>
    <section>
        <h2>About Me</h2>
        <p>Brief introduction about yourself.</p>
    </section>
    <section>
        <h2>Projects</h2>
        <ul>
            <li><a href="https://github.com/username/project1">Project 1</a></li>
            <li><a href="https://github.com/username/project2">Project 2</a></li>
        </ul>
    </section>
    <footer>
        <p>Contact: your-email@example.com</p>
    </footer>
</body>
</html>

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
}
header {
    background: #333;
    color: #fff;
    padding: 1rem;
    text-align: center;
}
section {
    padding: 1rem;
    margin: 1rem;
}
footer {
    text-align: center;
    margin-top: 2rem;
}

git add .
git commit -m "Initial portfolio"
git push origin main
