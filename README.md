<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gửi Đến Người Yêu</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #ffcccb; /* Màu hồng mặc định */
            color: white;
            text-align: center;
            padding: 50px;
            margin: 0;
        }
        h1 {
            font-size: 48px;
            margin-bottom: 20px;
            color: #ff4757;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
        }
        p {
            font-size: 24px;
            margin-bottom: 20px;
            text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.5);
        }
        .heart {
            font-size: 150px;
            color: #ff6b6b;
            animation: beat 1s infinite;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.7);
        }
        @keyframes beat {
            0%, 100% {
                transform: scale(1);
            }
            50% {
                transform: scale(1.2);
            }
        }
        .button {
            display: inline-block;
            background-color: #ff4757;
            color: white;
            padding: 15px 30px;
            font-size: 18px;
            text-decoration: none;
            border-radius: 8px;
            margin-top: 30px;
            box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.3);
            transition: background-color 0.3s ease, box-shadow 0.3s ease;
        }
        .button:hover {
            background-color: #ff6f61;
            box-shadow: 3px 3px 8px rgba(0, 0, 0, 0.5);
        }
        img {
            display: none; /* Ẩn hình ảnh mặc định */
            margin-top: 20px;
            max-width: 100%; /* Điều chỉnh kích thước hình ảnh cho vừa */
        }
    </style>
</head>
<body>
    <h1>Gửi Đến Bé Yêu Của Anh</h1>
    <div class="heart">❤️</div>
    <p>Trái tim này mãi mãi thuộc về em.</p>
    <a href="img/hihi.png" class="button" onclick="showImage()">Click vào đây để xem ảnh hihi</a>
    
 

<a href="img/cat.png" class="button" onclick="addImage(event)">Click here</a>


    <script>
        function showImage() {
            const image = document.getElementById('loveImage');
            image.src = 'link_ảnh_của_bạn'; // Thay link này bằng ảnh 
            image.style.display = 'block'; // Hiện hình ảnh
        }
    </script>
</body>
</html>
