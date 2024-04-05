
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ex1</title>
    <style>
        body {
            text-align: center;
            background-image: url(https://t3.ftcdn.net/jpg/04/17/74/38/360_F_417743870_L1BkKKcwGkmj0iT4FHg0Ck6QOwDlG5MS.jpg);
            background-repeat: no-repeat;
            background-size: 100%;
        }
        h1 {
            font-style: oblique;
            font-size: xx-large;
        }
        p {
            font-size: larger;
        }
    </style>
</head>
<body>
    <h1>JAVASCRIPT FUNCTIONS</h1>
    <p>Invoke (call) a funtions that converts form Fahrenheit to Celsius:</p>
    <p id="demo"></p>
    <script>
        function toCelcius(f) {
            return (5/9) * (f-32);
        }
        let value = toCelcius(77);
        document.getElementById("demo").innerHTML = value;
    </script>
</body>
</html>
