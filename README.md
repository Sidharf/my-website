# my-website
Creating a template for my website
my-website/
├── index.html
└── styles.css
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My GitHub Pages Site</title>
    <link rel="stylesheet" href="styles.css">
  </head>
  <body>
    <header>
      <h1>Welcome to My GitHub Pages Website</h1>
    </header>
    <main>
      <p>This is a simple static website hosted on GitHub Pages!</p>
      <a href="https://github.com" target="_blank">Visit GitHub</a>
    </main>
    <footer>
      <p>&copy; 2024 My GitHub Pages Site</p>
    </footer>
  </body>
</html>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f4f4f4;
}

header {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 20px;
}

main {
  padding: 20px;
  text-align: center;
}

footer {
  text-align: center;
  background-color: #333;
  color: white;
  padding: 10px;
}

a {
  color: #0077cc;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}
git clone https://github.com/username/my-website.git
cd my-website
git add .
git commit -m "Add website files"
git push origin main
