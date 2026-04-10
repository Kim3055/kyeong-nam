<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gyeongnam Snap - Osaka Photographer</title>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        /* 기본 스타일 */
        body {
            margin: 0;
            font-family: 'Noto Sans KR', sans-serif;
            background-color: #ffffff;
            color: #333;
        }
        header {
            padding: 60px 20px;
            text-align: center;
        }
        header h1 {
            font-size: 2rem;
            letter-spacing: 5px;
            font-weight: 300;
            margin-bottom: 10px;
        }
        header p {
            font-size: 0.9rem;
            color: #888;
        }
        nav {
            margin-bottom: 40px;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #555;
            font-size: 0.85rem;
            text-transform: uppercase;
        }

        /* 사진 갤러리 그리드 */
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 10px;
            padding: 10px;
            max-width: 1200px;
            margin: 0 auto;
        }
        .gallery-item {
            position: relative;
            overflow: hidden;
            aspect-ratio: 3 / 4; /* 세로형 스냅 감성 */
            background-color: #f0f0f0;
        }
        .gallery-item img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.5s ease;
        }
        .gallery-item:hover img {
            transform: scale(1.05);
        }
        .gallery-item .location-tag {
            position: absolute;
            bottom: 20px;
            left: 20px;
            color: white;
            text-shadow: 0 0 5px rgba(0,0,0,0.5);
            font-weight: 400;
        }

        /* 하단 푸터 */
        footer {
            padding: 100px 20px;
            text-align: center;
            border-top: 1px solid #eee;
            margin-top: 50px;
        }
        .contact-btn {
            display: inline-block;
            padding: 12px 30px;
            border: 1px solid #333;
            text-decoration: none;
            color: #333;
            transition: 0.3s;
            margin-bottom: 30px;
        }
        .contact-btn:hover {
            background-color: #333;
            color: #fff;
        }
        .footer-info {
            font-size: 0.8rem;
            color: #999;
        }
    </style>
</head>
<body>

<header>
    <h1>경남 (GYEONGNAM)</h1>
    <p>Osaka · Kyoto · Kobe · Nara Snap Photographer</p>
    <nav>
        <a href="#">Portfolio</a>
        <a href="https://www.instagram.com/mainichi_photosnap" target="_blank">Instagram</a>
        <a href="#">Contact</a>
    </nav>
</header>

<div class="gallery">
    <div class="gallery-item">
        <img src="https://via.placeholder.com/600x800" alt="Osaka Snap">
        <div class="location-tag">OSAKA</div>
    </div>
    <div class="gallery-item">
        <img src="https://via.placeholder.com/600x800" alt="Kyoto Snap">
        <div class="location-tag">KYOTO</div>
    </div>
    <div class="gallery-item">
        <img src="https://via.placeholder.com/600x800" alt="Kobe Snap">
        <div class="location-tag">KOBE</div>
    </div>
    <div class="gallery-item">
        <img src="https://via.placeholder.com/600x800" alt="Nara Snap">
        <div class="location-tag">NARA</div>
    </div>
</div>

<footer>
    <a href="https://www.instagram.com/mainichi_photosnap" class="contact-btn">문의하기 (Instagram)</a>
    <div class="footer-info">
        <p>© GYEONGNAM. ALL RIGHTS RESERVED.</p>
        <p>Insta: @mainichi_photosnap</p>
    </div>
</footer>

</body>
</html>
