<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ปลาวาฬพิกเซลที่คลิกเพื่อเคลื่อนที่</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            overflow: hidden;
            background-color: #a8e0e8; /* สีฟ้าเพื่อให้ดูเหมือนน้ำ */
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        #whale {
            width: 60px;
            height: 60px;
            background-color: #3a6b8b; /* สีของปลาวาฬ */
            clip-path: polygon(20% 0%, 80% 0%, 100% 50%, 80% 100%, 20% 100%, 0% 50%);
            position: absolute;
            transition: transform 0.5s ease-out; /* เพิ่มความนุ่มนวลในการเคลื่อนที่ */
        }

    </style>
</head>
<body>

    <div id="whale"></div>

    <script>
        // การทำให้ปลาวาฬเคลื่อนที่ตามการคลิก
        const whale = document.getElementById('whale');

        document.body.addEventListener('click', function(event) {
            // คำนวณตำแหน่งของ mouse pointer
            const x = event.clientX - whale.offsetWidth / 2;
            const y = event.clientY - whale.offsetHeight / 2;

            // เปลี่ยนตำแหน่งปลาวาฬ
            whale.style.transform = `translate(${x}px, ${y}px)`;
        });
    </script>

</body>
</html>
