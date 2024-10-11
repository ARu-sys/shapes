<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web Programming Exercise 11</title>
    <style>
        canvas {
            border: 1px solid black;
        }
    </style>
</head>
<body>
    <canvas id="myCanvas" width="400" height="300"></canvas>

    <script>
        const canvas = document.getElementById('myCanvas');
        const ctx = canvas.getContext('2d');
        
        ctx.fillStyle = 'blue';
        ctx.fillRect(50, 50, 100, 100);

        ctx.beginPath();
        ctx.arc(150, 100, 40, 0, 2 * Math.PI);
        ctx.fillStyle = 'yellow';
        ctx.fill();
    </script>
</body>
</html>
