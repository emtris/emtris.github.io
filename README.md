<html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trang Web Cá Nhân</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
</head>
<body>

    <!-- Thanh điều hướng -->
    <header>
        <nav>
            <h1 class="logo">My<span>Web</span></h1>
            <ul>
                <li><a href="#home">Trang chủ</a></li>
                <li><a href="#about">Giới thiệu</a></li>
                <li><a href="#contact">Liên hệ</a></li>
            </ul>
        </nav>
    </header>

    <!-- Trang chủ -->
    <section id="home" class="hero">
        <h2>Xin chào, mình là <span>Minh Trí</span></h2>
        <p>Chào mừng bạn đến với website cá nhân của mình</p>
        <a href="#about" class="btn">Xem thêm</a>
    </section>

    <!-- Giới thiệu -->
    <section id="about" class="about">
        <h2>Về tôi</h2>
        <p>Mình là một người đam mê lập trình và thiết kế web. Trang web này được tạo với HTML, CSS và JavaScript cùng hiệu ứng hoạt hình.</p>
    </section>

    <!-- Liên hệ -->
    <section id="contact" class="contact">
        <h2>Liên hệ</h2>
        <form>
            <input type="text" placeholder="Họ và tên" required>
            <input type="email" placeholder="Email" required>
            <textarea placeholder="Lời nhắn" required></textarea>
            <button type="submit">Gửi</button>
        </form>
    </section>

    <footer>
        <p>© 2025 - Thiết kế bởi Minh Trí</p>
    </footer>

    <script src="script.js"></script>


