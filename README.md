# Web-Page<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Web Page</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            text-align: center;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #007BFF;
            color: white;
            padding: 20px;
        }

        .container {
            margin-top: 50px;
        }

        button {
            background-color: #28a745;
            color: white;
            border: none;
            padding: 12px 20px;
            font-size: 16px;
            border-radius: 5px;
            cursor: pointer;
        }

        button:hover {
            background-color: #218838;
        }

        footer {
            margin-top: 50px;
            background-color: #333;
            color: white;
            padding: 10px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Welcome to My Website</h1>
    </header>

    <div class="container">
        <h2>Hello, Everyone!</h2>
        <p>This is my first web page created using HTML and CSS.</p>

        <button onclick="showMessage()">Click Me</button>
    </div>

    <footer>
        <p>&copy; 2026 My Website</p>
    </footer>

    <script>
        function showMessage() {
            alert("Welcome! Thanks for visiting my website.");
        }
    </script>

</body>
</html>
