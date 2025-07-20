# web
# Save the provided HTML code into an HTML file

html_code = """
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Learn with Me</title>
  <style>
    body {
      margin: 0; font-family: sans-serif; background: #f4f4f4; color: #333;
    }
    header {
      background: black;white: white; text-align: center; padding: 30px 10px;
    }
    nav a {
      color: white; text-decoration: none; margin: 0 10px; font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    main {
      max-width: 800px; margin: 30px auto; padding: 20px; background: #fff; text-align: center;p
      box-shadow: 0 0 10px rgba(0,0,0,0.1); border-radius: 6px;
    }
    footer {
      text-align: center; background:black; color: white; padding: 15px; margin-top: 30px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Hi, Learn with Me</h1>
    <p>Just for learning</p>
    <nav>
      <a href="#">Home</a>
      <a href="#">Dashboard</a>
      <a href="#">profile</a>
      <a href="#">support</a>
    </nav>
  </header>
  <main>
    <h2>Welcome!</h2>
    <p>Let’s explore and learn together.</p>
  </main>
  <footer>
    &copy; 2025 Developer Dave and sons❤️📌
  </footer>
</body>
</html>
"""

# Save to file
file_path = "/mnt/data/index.html"
with open(file_path, "w", encoding="utf-8") as f:
    f.write(html_code)

file_path
