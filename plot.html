<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Heart Plotter</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f0f0f0;
        }
        #canvasContainer {
            border: 2px solid #333;
            padding: 20px;
            background-color: #fff;
            border-radius: 10px;
        }
        canvas {
            border: 1px solid black;
            cursor: pointer;
        }
        p {
            font-family: Arial, sans-serif;
            font-size: 16px;
            color: #333;
            margin-top: 10px;
            text-align: center;
        }
        .equation {
            font-style: italic;
            font-size: 14px;
            color: #666;
        }
        /* Add this style for the colored background */
        .colored-background {
            background-color: #87CEEB; /* Sky Blue */
        }
    </style>
</head>
<body class="colored-background"> <!-- Add the class to the body -->
    <div id="canvasContainer">
        <canvas id="plotCanvas" width="400" height="300"></canvas>
        <p>Click the canvas to reveal the heart plot.</p>
        <p class="equation">The equation for the heart plot is: <br> 
        \(x = 16 \times \sin^3(t)\) <br> 
        \(y = 13 \times \cos(t) - 5 \times \cos(2t) - 2 \times \cos(3t) - \cos(4t)\)</p>
    </div>
    <script>
        window.onload = function() {
            const canvas = document.getElementById('plotCanvas');
            const ctx = canvas.getContext('2d');

            function drawAxes() {
                ctx.beginPath();
                ctx.strokeStyle = '#666';
                ctx.moveTo(canvas.width / 2, 0);
                ctx.lineTo(canvas.width / 2, canvas.height);
                ctx.moveTo(0, canvas.height / 2);
                ctx.lineTo(canvas.width, canvas.height / 2);
                ctx.stroke();
            }

            function drawHeart() {
                ctx.clearRect(0, 0, canvas.width, canvas.height);
                drawAxes();
                ctx.beginPath();
                ctx.strokeStyle = 'red';
                for (let angle = 0; angle <= Math.PI * 2; angle += 0.01) {
                    const x = 16 * Math.pow(Math.sin(angle), 3);
                    const y = 13 * Math.cos(angle) - 5 * Math.cos(2 * angle) - 2 * Math.cos(3 * angle) - Math.cos(4 * angle);
                    const scaledX = (x + 16) * 5; // scale heart
                    const scaledY = (y + 13) * 5;
                    ctx.lineTo(canvas.width / 2 + scaledX, canvas.height / 2 - scaledY); // center heart
                }
                ctx.stroke();
            }

            canvas.addEventListener('click', function() {
                drawHeart();
            });

            // Listeners for scrolling and zooming
            window.addEventListener('keydown', function(event) {
                switch(event.key) {
                    case 'w':
                        window.scrollBy(0, -10);
                        break;
                    case 's':
                        window.scrollBy(0, 10);
                        break;
                    case 'a':
                        window.scrollBy(-10, 0);
                        break;
                    case 'd':
                        window.scrollBy(10, 0);
                        break;
                    case 'p':
                        canvas.width *= 1.1;
                        canvas.height *= 1.1;
                        drawHeart();
                        break;
                    case 'm':
                        canvas.width *= 0.9;
                        canvas.height *= 0.9;
                        drawHeart();
                        break;
                    case 'r':
                        canvas.width = 400;
                        canvas.height = 300;
                        drawHeart();
                        break;
                    case 'h':
                        alert('Help: Use WASD to scroll, P to zoom in, M to zoom out, R to reset, and click the canvas to reveal the heart plot.');
                        break;
                    default:
                        break;
                }
            });

            drawAxes(); // Draw axes initially
        };
    </script>
</body>
</html>
