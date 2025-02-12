<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ซองจดหมายสุขสันต์วันวาเลนไทน์</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f8f8f8;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .envelope {
            width: 300px;
            height: 180px;
            background-color: #ff6f61;
            border-radius: 15px;
            position: relative;
            overflow: hidden;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .envelope::before {
            content: "";
            position: absolute;
            top: -10px;
            left: 0;
            width: 100%;
            height: 20px;
            background-color: #ff3e2f;
            border-radius: 10px;
        }
        .heart {
            position: absolute;
            top: 30%;
            left: 50%;
            transform: translateX(-50%);
            font-size: 60px;
            color: white;
        }
        .message {
            position: absolute;
            bottom: 10px;
            left: 50%;
            transform: translateX(-50%);
            font-size: 18px;
            color: white;
            text-align: center;
            width: 80%;
        }
    </style>
</head>
<body>
    <div class="envelope">
        <div class="heart">&#10084;</div>
        <div class="message">
            <p>สุขสันต์วันวาเลนไทน์!</p>
            <p>ขอให้คุณมีความสุขและความรักที่ยั่งยืน</p>
        </div>
    </div>
</body>
</html>
