<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>10pm moments</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
        }

        .container {
            max-width: 600px;
            margin: 0 auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.2);
        }

        input[type="text"], textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
        }

        button {
            background-color: #333;
            color: #fff;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>dugay nana ko gusto iingon sa imoha ba</h1>
        <label for="name">Your Name:</label>
        <input type="text" id="name" placeholder="Enter your name">
        <button id="submitButton">Submit</button>
        <div id="output">
        </div>
    </div>

    <script>
        document.getElementById("submitButton").addEventListener("click", function() {
            const name = document.getElementById("name").value;
            const output = document.getElementById("output");
            output.innerHTML = `<p><strong></strong> hi ${name}</p><p><strong>pwede bang mahiram ballpen mo?</strong></p>`;
        });
    </script>
</body>
</html>
