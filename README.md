<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About</title>
    <style>
        /* Reset styles for all elements */
        * {
            margin: 0; /* Remove default margin */
            padding: 0; /* Remove default padding */
            box-sizing: border-box; /* Include padding and border in total width/height */
        }

        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh; /* Fill the viewport height */
            background-color: #1a1a1a;
            color: white;
        }

        .container {
            text-align: center;
            background-color: #333;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
            width: 90%; /* Responsive width */
            max-width: 600px; /* Limit for larger screens */
            margin: 0; /* Center the container with no extra margins */
        }

        h1 {
            color: #f0f0f0;
            margin-bottom: 20px; /* Space below the heading */
        }

        ul {
            list-style-type: none;
            padding: 0; /* Remove padding */
            display: flex;
            flex-direction: column; /* Stack items vertically */
            align-items: center; /* Center items */
        }

        li {
            background-color: #444;
            margin: 10px 0; /* Space between list items */
            padding: 15px; /* Padding for list items */
            border-radius: 5px;
            text-align: center; /* Center text within list items */
            width: 100%; /* Full width of list items */
            max-width: 500px; /* Limit width of list items */
            transition: background-color 0.3s; /* Smooth transition for hover effect */
        }

        li:hover {
            background-color: #555; /* Change background on hover */
        }

        a {
            text-decoration: none;
            color: white; /* White link color */
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
            <li><a href="https://github.com/GlizzyMC">Github</a></li>
        </ul>
    </div>
</body>
</html>
