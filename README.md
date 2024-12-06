<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Create CVs & Presentations</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4CAF50; /* Green color */
            color: white;
            text-align: center;
            padding: 20px;
        }
        header h1 {
            animation: fadeIn 2s ease-in-out;
        }
        .secure-mark {
            font-size: 14px;
            color: #4CAF50;
            text-align: center;
            margin-top: 20px;
        }
        .main-content {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            margin-top: 30px;
        }
        .card {
            background-color: #ffffff;
            margin: 10px;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
            width: 300px;
            text-align: center;
            animation: slideUp 1s ease-out;
        }
        .card img {
            width: 100%;
            height: auto;
            border-radius: 8px;
        }
        .card h3 {
            color: #333;
        }
        .card p {
            color: #555;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        /* Animation */
        @keyframes fadeIn {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }
        @keyframes slideUp {
            0% { transform: translateY(50px); opacity: 0; }
            100% { transform: translateY(0); opacity: 1; }
        }
    </style>
</head>
<body>

<header>
    <h1>Create Stunning CVs & Presentations</h1>
</header>

<div class="secure-mark">
    <p>🔒 Secure Website - Your Data is Safe with Us</p>
</div>

<div class="main-content">
    <!-- Example Card: CV Creation -->
    <div class="card">
        <img src="cv-example.jpg" alt="CV Example">
        <h3>Create Your CV</h3>
        <p>Professional templates and easy-to-use tools to craft the perfect CV.</p>
    </div>

    <!-- Example Card: Presentation Design -->
    <div class="card">
        <img src="presentation-example.jpg" alt="Presentation Example">
        <h3>Design Presentations</h3>
        <p>Create visually appealing presentations for work or school.</p>
    </div>
</div>

<!-- Embedded Video Section -->
<div style="text-align: center; margin-top: 40px;">
    <h2>Watch Our Tutorial</h2>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/YOUR_VIDEO_ID" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<footer>
    <p>© 2024 Create CV & Presentations - All Rights Reserved</p>
</footer>

</body>
</html>
