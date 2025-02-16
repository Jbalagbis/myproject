# myproject
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Me</title>
    <link rel="stylesheet" href="styles.css">
</head>
    <style>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    text-align: center;
    background-color: #f4f4f4;
}

header {
    background-color: #0073e6;
    color: white;
    padding: 15px;
    font-size: 24px;
    font-weight: bold;
}

.container {
    max-width: 600px;
    margin: 20px auto;
    padding: 10px;
    background: skyblue;
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
    border-radius: 10px;
}

img {
    width: 150px;
    border-radius: 50%;
}

h1 {
    color: #333;
}

p {
    color: #666;
}

.social-links a {
    margin: 10px;
    text-decoration: none;
    color: #0073e6;
    font-weight: bold;
}

.buttons {
    margin-top: 20px;
}

.buttons button {
    margin: 5px;
    padding: 10px 20px;
    font-size: 16px;
    border: none;
    background-color: #0073e6;
    color: white;
    cursor: pointer;
    border-radius: 5px;
}

.buttons button:hover {
    background-color: #005bb5;
}

footer {
    margin-top: 50px;
    background-color: #333;
    color: white;
    padding: 10px;
    font-size: 14px;
}
</style>
<header>
        <div class="buttons">
            <button onclick="location.href='index.html'">Home</button>
            <button onclick="alert('Settings feature coming soon!')">Settings</button>
            <button onclick="alert('Others feature coming soon!')">Others</button>
        </div>
</header>
<body>
    <div class="container">
        <img src="j.jpg" alt="Profile Picture">
        <h1>Joel F. Balagbis</h1>
        <p>Hello! I'm Joel F. Balagbis, a passionate BSIT student who loves technology and innovation. Welcome to my personal website!</p>
        <div class="social-links">
            <a href="https://github.com/Jbalagbis">GitHub</a> 
        </div>

    </div>
</body>
</html>
