# my_portfolio-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anupam Sarkar's Info</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #2c3e50;
            background-image: linear-gradient(to bottom right, #2c3e50, #34495e);
            color: #ecf0f1;
            overflow: hidden; /* Prevent scrolling */
        }
        header {
            background-color: #2980b9; /* Header background */
            padding: 10px 0;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
        }
        nav a {
            color: #ecf0f1;
            text-decoration: none;
            padding: 15px;
            font-weight: 700;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            width: 100%;
            max-width: 800px;
            margin: 50px auto;
            background-color: #34495e;
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.4);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .container:hover {
            transform: translateY(-5px);
            box-shadow: 0px 0px 20px rgba(0, 0, 0, 0.5);
        }
        h1, h2 {
            text-align: center;
            color: #ecf0f1;
            margin-bottom: 10px;
        }
        h1 {
            font-size: 2.5em;
            transition: color 0.3s ease;
        }
        h2 {
            font-size: 1.8em;
            color: #95a5a6; /* Lighter color for subheading */
        }
        p {
            font-size: 18px;
            line-height: 1.6;
            margin: 10px 0;
            transition: color 0.3s ease;
        }
        strong {
            color: #3498db; /* Bright color for emphasis */
        }
        .movable-name {
            display: inline-block;
            position: relative;
            animation: move 5s infinite alternate;
            font-size: 1.5em;
            cursor: pointer;
            color: #e74c3c; /* Bright color for the name */
            transition: transform 0.3s ease, color 0.3s ease;
        }
        .movable-name:hover {
            transform: scale(1.2);
            color: #f39c12; /* Change color on hover */
        }
        @keyframes move {
            0% { transform: translateX(0); }
            50% { transform: translateX(30px); }
            100% { transform: translateX(0); }
        }
        footer {
            text-align: center;
            margin-top: 40px;
            font-size: 16px;
            color: #95a5a6; /* Lighter color for footer */
        }
    </style>
</head>
<body>

    <header>
        <nav>
            <a href="#">Home</a>
            <a href="#">About</a>
            <a href="#">Contact</a>
        </nav>
    </header>

    <div class="container">
        <h1>Institute of Engineering and Management, Kolkata</h1>
        <h2>Newtown Campus</h2>

        <p><strong>Degree Name:</strong> B.Tech in Electronics and Communication Engineering</p>
        <p><strong>Year:</strong> 1st Year (1st Semester)</p>
        <p><strong>Name:</strong> <span class="movable-name">Anupam Sarkar</span></p>
        <p><strong>Roll Number:</strong> 20</p>
        <p><strong>Section:</strong> P</p>
    </div>

    <footer>
        &copy; 2024 Anupam Sarkar
    </footer>

</body>
</html>
