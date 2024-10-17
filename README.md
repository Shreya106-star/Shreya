
<!DOCTYPE html>
<html>
<head>
  <title>My First Webpage</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1>Welcome to my webpage!</h1>
  <p>This is a paragraph of text.</p>
  <img src="image.jpg" alt="An image">
  <a href="https://www.example.com">Link to Example Website</a>
  <button onclick="showAlert()">Click me</button>
  <script src="script.js"></script>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  background-color: #f0f0f0;
  margin: 20px;
}

h1 {
  color: #333;
  text-align: center;
}

p {
  line-height: 1.5;
}

img {
  width: 200px;
  height: auto;
  display: block;
  margin: 0 auto;
}

a {
  color: blue;
  text-decoration: none;
}

button {
  padding: 10px 20px;
  background-color: #4CAF50;
  color: white;
  border: none;
  cursor: pointer;
}
function showAlert() {
  alert("You clicked the button!");
}
