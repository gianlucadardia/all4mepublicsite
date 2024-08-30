<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Left Navigation Pane</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
        }
        .nav-pane {
            height: 100%;
            width: 250px;
            position: fixed;
            top: 0;
            left: 0;
            background-color: #111;
            padding-top: 20px;
        }
        .nav-pane a {
            padding: 10px 15px;
            text-decoration: none;
            font-size: 18px;
            color: white;
            display: block;
        }
        .nav-pane a:hover {
            background-color: #575757;
        }
        .main-content {
            margin-left: 260px;
            padding: 20px;
        }
    </style>
</head>
<body>
    <div class="nav-pane">
        <a href="#home">Home</a>
        <a href="#services">Services</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
        <a href="https://example.com">External Link</a> <!-- Added external link -->
    </div>
    <div class="main-content">
        <h1>Welcome to My Website</h1>
        <p>This is the main content area.</p>
    </div>
</body>
</html>