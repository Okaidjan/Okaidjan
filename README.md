
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ampekrom M/A Basic Form</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Ampekrom M/A Basic Form</h1>
    </header>
    <main>
        <form id="ampekrom-form">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="phone">Phone Number:</label>
            <input type="tel" id="phone" name="phone" required>

            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit">Submit</button>
        </form>
    </main>
    <footer>
        <p>View our GitHub repository: <a href="(link unavailable)">Ampekrom M/A Basic</a></p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
```
*CSS (style.css)*
```
body {
    font-family: Arial, sans-serif;
    margin: 20px;
}

header {
    background-color: #f0f0f0;
    padding: 20px;
    text-align: center;
}

main {
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 20px;
}

form {
    width: 50%;
    padding: 20px;
    border: 1px solid #ccc;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

label {
    display: block;
    margin-bottom: 10px;
}

input, textarea {
    width: 100%;
    padding: 10px;
    margin-bottom: 20px;
    border: 1px solid #ccc;
}

button[type="submit"] {
    background-color: #4CAF50;
    color: #fff;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

button[type="submit"]:hover {
    background-color: #3e8e41;
}

footer {
    text-align: center;
    padding: 20px;
}
```
*JavaScript (script.js)*
```
const form = document.getElementById('ampekrom-form');

form.addEventListener('submit', (e) => {
    e.preventDefault();
    const name = document.getElementById('name').value;
    const email = document.getElementById('email').value;
    const phone = document.getElementById('phone').value;
    const message = document.getElementById('message').value;

    // Add your form submission logic here
    console.log('Form submitted:', { name, email, phone, message });
});
```
*Linking to GitHub Repository*

In the HTML file, I added a link to your GitHub repository in the footer section:
```
<footer>
    <p>View our GitHub repository: <a href="(link unavailable)">Ampekrom M/A Basic</a></p>
</footer>
```

