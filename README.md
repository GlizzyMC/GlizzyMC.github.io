<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0; /* Remove body margin */
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh; /* Ensures it fills the viewport */
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
            box-sizing: border-box; /* Include padding in width calculation */
            margin: 0; /* Center container */
        }

        h1 {
            color: #f0f0f0;
            margin-bottom: 20px; /* Space below the heading */
        }

        ul {
            list-style-type: none;
            padding: 0;
            margin: 0; /* Remove margin to prevent extra space */
            display: flex;
            flex-direction: column; /* Stack items vertically */
            align-items: center; /* Center items */
        }

        li {
            background-color: #444;
            margin: 10px 0;
            padding: 15px; /* Increased padding for better touch area and aesthetics */
            border-radius: 5px;
            text-align: center; /* Center align text within list items */
            transition: background-color 0.3s; /* Smooth transition for hover effect */
            width: 100%; /* Make list items full width */
            max-width: 500px; /* Limit width of list items */
        }

        li:hover {
            background-color: #555; /* Slightly change background on hover */
        }

        a {
            text-decoration: none;
            color: white; /* Ensure link text is white */
        }

        .personal-details p {
            margin: 5px 0;
            font-size: 1.1em;
        }

        @media (max-width: 600px) {
            .container {
                width: 100%; /* Full width on small screens */
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
            <li><a href="https://github.com/GlizzyMC">Github</a></li>
        </ul>
    </div>
</body>
</html>
