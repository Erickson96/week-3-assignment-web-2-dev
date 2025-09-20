<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CSS Box Model Demo</title>
  <!-- Link to external stylesheet -->
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Welcome to My Webpage</h1>
    <p class="subtitle">A simple demo of the CSS Box Model</p>
  </header>

  <main>
    <section class="card">
      <h2>About</h2>
      <p>
        This section demonstrates the box model. Notice the padding around
        the text, the border surrounding the box, and the margin spacing it
        from other elements.
      </p>
    </section>

    <section class="card">
      <h2>Features</h2>
      <ul>
        <li>Padding inside boxes</li>
        <li>Margins between boxes</li>
        <li>Borders around boxes</li>
        <li>Consistent spacing and layout</li>
      </ul>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 My Website</p>
  </footer>
</body>
</html>
/* General reset */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f4f4f9;
  color: #333;
  line-height: 1.6;
}

/* Header styling */
header {
  background-color: #4CAF50;
  color: white;
  text-align: center;
  padding: 20px;
  margin-bottom: 20px;
}

.subtitle {
  font-size: 1.2em;
  margin-top: 10px;
}

/* Card section using the box model */
.card {
  background-color: #fff;
  border: 2px solid #ccc;
  padding: 20px;   /* space inside the border */
  margin: 20px;    /* space outside the border */
  border-radius: 8px;
  max-width: 600px;
  box-shadow: 2px 2px 8px rgba(0,0,0,0.1);
}

/* Headings */
h1, h2 {
  margin: 0 0 10px 0;
}

/* Footer */
footer {
  text-align: center;
  padding: 15px;
  background-color: #333;
  color: #fff;
  margin-top: 20px;
}
