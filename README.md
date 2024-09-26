<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chrome Background with Buttons</title>
    <style>
        body {
            margin: 0;
            height: 100vh;
            background: linear-gradient(135deg, #d1d1d1, #e8e8e8);
            display: flex;
            justify-content: center;
            align-items: center;
            font-family: Arial, sans-serif;
        }
        .button {
            background-color: #ffffff;
            border: 1px solid #ccc;
            border-radius: 5px;
            padding: 10px 20px;
            margin: 10px;
            cursor: pointer;
            transition: background-color 0.3s, transform 0.2s;
        }
        .button:hover {
            background-color: #f0f0f0;
            transform: scale(1.05);
        }
    </style>
</head>
<body>
    <div>
        <button class="button">Button 1</button>
        <button class="button">Button 2</button>
        <button class="button">Button 3</button>
    </div>
</body>
</html>
