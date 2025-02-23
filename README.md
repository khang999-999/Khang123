<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PKhang iOS - Login</title>
    <style>
        body {
            background: url('https://source.unsplash.com/1600x900/?stars,galaxy') no-repeat center center fixed;
            background-size: cover;
            color: white;
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            flex-direction: column;
            text-align: center;
        }
        .container {
            background: rgba(0, 0, 0, 0.7);
            padding: 20px;
            border-radius: 10px;
        }
        input, button {
            padding: 10px;
            margin: 10px;
            border: none;
            border-radius: 5px;
        }
        button {
            background-color: #ffcc00;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>PKhang iOS - Đăng Nhập</h2>
        <input type="text" id="key" placeholder="Nhập Key">
        <button onclick="checkKey()">Đăng Nhập</button>
    </div>
    
    <script>
        function checkKey() {
            let key = document.getElementById('key').value;
            if (key === "PKhang100K") {
                window.location.href = "menu.html"; // Chuyển qua menu chức năng
            } else {
                alert("Key không hợp lệ!");
            }
        }
    </script>
</body>
</html>
# Khang123
