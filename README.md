# Bezawit-
“My first coding project as I learn to become a software engineer.”



<!DOCTYPE html>
<html>
<head>
    <title>My First Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <h1>Hi, I'm Bezawit 👋</h1>
    <p>I am learning coding and I want to be a software engineer 💻</p>

    <button onclick="showMessage()">Click Me</button>

    <p id="message"></p>

    <script>
        function showMessage() {
            document.getElementById("message").innerText = "Keep going! You can do it 💪";
        }
    </script>

</body>
</html>