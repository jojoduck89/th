<!DOCTYPE html>
<html>
    <head>
        <title>Home01</title>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">

       
        <style>
            button {
                width: 400px; /* Button width */
                height: 200px; /* Button height */
                font-size: 50px; /* Font size inside button */
                padding: 10px; /* Internal spacing */
                border-radius: 10px; /* Rounded corners */
                color: rgb(158, 56, 78); /* Text color */
            }
            .size {
                text-align: center; /* Center align the content */
                margin-top: 50px; /* Space from the top */
            }
        </style>

<script>
    function sendValue(value, targetUrl) {
        localStorage.setItem('selectedName', value); // เก็บค่าใน Local Storage
        location.href = targetUrl; // ไปที่ URL ที่กำหนด
    }
</script>

    </head>

    <body>
        <div class="size">
            <h1>WHAT is your Name?</h1>
            <br>
            <button onclick="sendValue('Stang','/HBD01/home01.html')">Stang</button>
            <button onclick="sendValue('Peerada', '/HBD01/Home01.html')">peerada</button>
            <br>
            <button onclick="sendValue('Da', '/HBD01/Home01.html')">Da</button>
            <button onclick="sendValue('P nut', '/HBD01/Home01.html')">P nut</button>
           
        </div>
    </body>
</html>
