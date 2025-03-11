
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Akil & Yopi's Wedding Invitation</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>Akil & Yopi's Wedding Invitation</h1>
        <p>You are cordially invited to the wedding of</p>
        <h2>Akil & Yopi</h2>
        <p>Date: [Insert Date]</p>
        <p>Time: [Insert Time]</p>
        <p>Location: [Insert Location]</p>
        <button id="rsvp-button">RSVP</button>
        <div id="rsvp-message" style="display: none;"></div>
    </div>
    <script src="script.js"></script>
</body>
</html>
```

CSS:
```
body {
    font-family: Arial, sans-serif;
    background-color: #f2f2f2;
}

.container {
    width: 80%;
    margin: 40px auto;
    text-align: center;
    background-color: #fff;
    padding: 20px;
    border: 1px solid #ddd;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

h1 {
    font-size: 36px;
    color: #333;
}

h2 {
    font-size: 24px;
    color: #666;
}

button {
    background-color: #4CAF50;
    color: #fff;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background-color: #3e8e41;
}

#rsvp-message {
    margin-top: 20px;
    font-size: 18px;
    color: #666;
}
```

JavaScript:
```
document.getElementById("rsvp
