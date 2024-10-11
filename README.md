<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Circle and Rectangle</title>
    <style>
        /* Container to position both shapes */
        .container {
            position: relative;
            width: 200px;
            height: 200px;
        }

        /* Rectangle styles */
        .rectangle {
            width: 150px;
            height: 150px;
            background-color: blue;
            position: absolute;
            top: 20px;
            left: 20px;
        }

        /* Circle styles */
        .circle {
            width: 100px;
            height: 100px;
            background-color: yellow;
            border: 5px solid red; /* Add a red border */
            border-radius: 50%; /* Makes it a circle */
            position: absolute;
            top: 40px;
            left: 60px;
        }
    </style>
</head>
<body>

    <div class="container">
        <div class="rectangle"></div>
        <div class="circle"></div>
    </div>

</body>
</html>
