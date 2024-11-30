<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thi?p Cu?i</title>
    <style>
        body {
            margin: 0;
            font-family: 'Times New Roman', serif;
            background-color: #fce4ec;
            color: #5a2e2e;
            text-align: center;
        }

        .container {
            max-width: 900px;
            margin: auto;
            padding: 20px;
        }

        .header {
            position: relative;
        }

        .header img {
            width: 100%;
            max-height: 400px;
            object-fit: cover;
            opacity: 0.8;
        }

        .header h1 {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            font-size: 50px;
            color: #fff;
            text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.7);
        }

        .invitation {
            margin-top: 20px;
            padding: 20px;
            background-color: #fff;
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .invitation h2 {
            font-size: 24px;
            margin-bottom: 10px;
        }

        .names {
            font-size: 30px;
            font-weight: bold;
            margin: 10px 0;
        }

        .names span {
            font-size: 25px;
            color: #d81b60;
        }

        .guest-name {
            font-size: 20px;
            font-style: italic;
            margin: 10px 0;
        }

        .wedding-details h3 {
            font-size: 28px;
            margin: 20px 0;
            color: #d81b60;
        }

        .date {
            font-size: 24px;
            font-weight: bold;
            color: #5a2e2e;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Header -->
        <div class="header">
            <img src="bride_groom.jpg" alt="?nh Cô Dâu Chú R?">
            <h1>Save the Date</h1>
        </div>

        <!-- Invitation -->
        <div class="invitation">
            <h2>L? cu?i c?a</h2>
            <div class="names">
                <p>Ð?c Th?ng</p>
                <span>&</span>
                <p>Huy?n Trang</p>
            </div>
            <p>Ch? còn n?a thôi!</p>
            <p class="guest-name">Trân tr?ng kính m?i <strong>b?n Minh</strong></p>
            <p>Ð?n d? bu?i ti?c chung vui cùng chúng mình</p>
            <div class="wedding-details">
                <h3>Ti?c Cu?i</h3>
                <p>Ti?c cu?i du?c t? ch?c vào h?i</p>
                <p><strong>16 gi? 30 | Th? B?y</strong></p>
                <p class="date">12.10.2024</p>
                <p>(T?c ngày 10 tháng 9 nam Giáp Thìn)</p>
                <p>T?i: Tu Gia Nhà Trai</p>
                <p>Thôn Nhu Phu?ng Thu?ng, xã Long Hung, Van Giang, Hung Yên</p>
            </div>
        </div>
    </div>
</body>
</html>
