<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh; /* Changed to min-height to allow scrolling if needed */
            background-color: #1a1a1a;
            color: white;
        }

        .container {
            text-align: center;
            background-color: #333;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
            width: 90%; /* Make it responsive */
            max-width: 600px; /* Limit the width for larger screens */
        }

        h1 {
            color: #f0f0f0;
        }

        ul {
            list-style-type: none;
            padding: 0;
        }

        li {
            background-color: #444;
            margin: 10px 0;
            padding: 10px;
            border-radius: 5px;
        }

        a {
            text-decoration: none;
        }

        .personal-details p {
            margin: 5px 0;
            font-size: 1.1em;
        }

        /* Ensure container takes full width on small screens */
        @media (max-width: 600px) {
            .container {
                width: 100%;
                padding: 20px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1><strong>Who am I?</strong></h1>
        <ul>
            <li>Thank you for scanning this QR code and wasting your time.</li>
            <li><strong>Name:</strong> Minuka Mandinu</li>
            <li><strong>Phone Number:</strong> (+94) 717 800 713</li>
            <li><strong>Email:</strong> minukamandinu@gmail.com</li>
            <li><a href="https://github.com/GlizzyMC"><font color="white">Github</font></a></li>
        </ul>
    </div>
</body>
</html>
