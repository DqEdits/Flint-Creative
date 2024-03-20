<!DOCTYPE html>
<html>
<head>
    <style>
        header {
            background-color: #333;
            color: white;
            padding: 10px;
            text-align: center;
            border-bottom: 2px solid black; /* Adding a bar at the bottom */
            position: relative; /* To position the bar */
        }
        header::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 2px; /* Height of the bar */
            background-color: black; /* Color of the bar */
        }
    </style>
</head>
<body>

<header>
    This is the header with a bar
</header>

</body>
</html>

<!doctype html>

<html>

    <head>
        <meta charset="utf-8">

        <title>Blank template</title>

        <!-- Load external CSS styles -->
        <link rel="stylesheet" href="styles.css">

    </head>
    <body>

        <h1>Flint Creative</h1>
        
        <!-- Load external JavaScript -->
        <script src="scripts.js"></script>

    </body>


</html>
