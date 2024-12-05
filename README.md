<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Giới Thiệu Thành Viên Nhóm</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
        }
        h1 {
            margin-top: 20px;
            color: #333;
        }
        .team {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            width: 90%;
            max-width: 800px;
            margin: 20px auto;
        }
        .member {
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            text-align: center;
            padding: 20px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .member:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 10px rgba(0, 0, 0, 0.15);
        }
        .member img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            object-fit: cover;
            margin-bottom: 10px;
        }
        .member h3 {
            margin: 10px 0 5px;
            font-size: 18px;
            color: #007BFF;
        }
        .member a {
            text-decoration: none;
            color: #555;
            font-size: 14px;
        }
        .member a:hover {
            color: #007BFF;
        }
    </style>
</head>
<body>
    <a>Thành Viên Nhóm</a>
    <div class="team">
        <!-- Thành viên 1 -->
        <div class="member">
            <h3>Huỳnh Thiên KIm</h3>
            <a href="https://tructamcute.github.io/ProfileThienKim/" target="_blank">Giới thiệu học sinh</a>
        </div>
        <!-- Thành viên 2 -->
        <div class="member">
            <h3>Nguyễn Thị Yến Vy</h3>
            <a href="https://tructamcute.github.io/ProfileYenVy/" target="_blank">Giới thiệu học sinh</a>
        </div>
        <!-- Thành viên 3 -->
        <div class="member">
            <h3>Phan Anh Khoa</h3>
            <a href="https://tructamcute.github.io/ProfileAnhKhoa/" target="_blank">Giới thiệu học sinh</a>
        </div>
        <!-- Thành viên 4 -->
        <div class="member">
            <h3>Huỳnh Phát</h3>
            <a href="https://tructamcute.github.io/ProfileHuynhPhat/" target="_blank">Giới thiệu học sinh</a>
        </div>
        <!-- Thành viên 5 -->
        <div class="member">
            <h3>Trần Trung Nguyên</h3>
            <a href="https://tructamcute.github.io/ProfileTrungNguyen/" target="_blank">Giới thiệu học sinh</a>
        </div>
    </div>
    <a href="https://tructamcute.github.io/nhom6_12L/">Quay lại trang chủ</a>
</body>
</html>
