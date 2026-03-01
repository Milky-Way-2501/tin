<!DOCTYPE html>
<html lang="vi">
<head>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Cá Nhân - Thanh Hồng</title>
    <style>
        * {margin: 0;padding: 0;box-sizing: border-box;font-family: "Segoe UI", Arial, sans-serif;}
        body {font-family: 'Poppins', sans-serif;font-style: italic; background: linear-gradient(120deg, #ff9a9e, #fad0c4, #fbc2eb); background-size: 300% 300%; animation: bgMove 10s infinite alternate; min-height: 100vh;overflow-x: hidden;}
        @keyframes bgMove {from { background-position: 0% 50%; }to { background-position: 100% 50%; } }
        header { background: rgba(255,255,255,0.95); padding: 15px 30px;   display: flex; justify-content: space-between;align-items: center;   position: fixed;  width: 100%;   top: 0;  z-index: 1000;box-shadow: 0 2px 10px rgba(0,0,0,0.15);}
        header h2 { color: #e53935; }
        nav a {margin-left: 15px;text-decoration: none;color: #333; font-weight: 500;transition: 0.3s;}
        nav a:hover { color: #e53935; }
        .container {max-width: 900px;margin: 120px auto 50px; background: white;border-radius: 20px;padding: 35px;box-shadow: 0 8px 25px rgba(0,0,0,0.2);}
        .reveal {opacity: 0;transform: translateY(40px);transition: all 1s ease;}
        .reveal.active {opacity: 1;transform: translateY(0);}
        .hero { text-align: center; }
        .hero img { width: 180px;height: 180px;border-radius: 50%;border: 5px solid #e53935; object-fit: cover;margin: 20px 0;transition: 0.4s; }
        .hero img:hover { transform: scale(1.1) rotate(3deg); }
        .hero h1 { color: #e53935; }
        .typing { font-size: 18px; margin-top: 10px; min-height: 25px; color: #444; }
        section { margin-top: 50px; }
        section h3 {text-align: center;color: #e53935;margin-bottom: 20px; font-size: 24px;}
        .info{max-width:600px; margin:0 auto; padding:20px 25px;background:#fff8f8;border-radius:12px;box-shadow:0 4px 10px rgba(0,0,0,0.1);}
.info p{ margin:12px 0;font-size:17px;text-align:left;line-height:1.6;}
        .dream {    background: #fff5f5;    padding: 25px;   border-radius: 15px;  text-align: center;  font-size: 18px; animation: pulse 2s infinite alternate; }
        @keyframes pulse {  from { transform: scale(1); } to { transform: scale(1.03); } }
        .social { text-align: center; }
        .social a {  display: inline-block;      margin: 8px; padding: 10px 18px; background: #e53935;  color: white;  text-decoration: none; border-radius: 25px; transition: 0.3s; }
        .social a:hover {  background: #c62828; transform: translateY(-3px) scale(1.05); }
        form { max-width: 500px;  margin: auto;}
        form input, form textarea {width: 100%;  padding: 10px; margin: 8px 0;border: 1px solid #ccc;   border-radius: 8px; font-size: 15px; }
        form button {  width: 100%;  padding: 12px; background: #e53935; color: white; border: none; border-radius: 8px;font-size: 16px;cursor: pointer;transition: 0.3s; }
        form button:hover { background: #c62828; }
        .video-box { position: relative; padding-bottom: 56.25%;height: 0; overflow: hidden; border-radius: 15px;box-shadow: 0 5px 15px rgba(0,0,0,0.2); }
        .video-box iframe { position: absolute; top: 0;left: 0; width: 100%;height: 100%;}
        .heart {position: fixed;top: -10px;font-size: 20px;color: pink;animation: fall linear forwards;z-index: 9999;}
        @keyframes fall {to {transform: translateY(110vh);opacity: 0;}}
        footer {text-align: center;margin-top: 40px;color: #555;font-size: 14px;}
        @media (max-width: 600px) {header { flex-direction: column; }nav { margin-top: 8px; }}
    </style>
</head>
<body>
<header>
    <h2>Thanh Hồng</h2>
    <nav>
        <a href="#home">Trang chủ</a>
        <a href="#about">Giới thiệu</a>
        <a href="#dream">Ước mơ</a>
        <a href="#video">Video</a>
        <a href="#social">Liên hệ</a>
    </nav>
</header>
<div class="container" id="home">
    <div class="hero reveal">
        <img src="https://png.pngtree.com/thumb_back/fh260/background/20230804/pngtree-pink-rose-wallpaper-flowers-beautiful-image_13002486.jpg" alt="Ảnh đại diện">
        <h1>Trần Thị Thanh Hồng</h1>
        <div class="typing" id="typing"></div>
    </div>
    <section id="about" class="reveal">
        <h3>Giới thiệu</h3>
        <div class="info">
            <p>📅 Ngày sinh: 16/5/2008</p>
            <p>🏫 Trường: THPT Số 2 Tư Nghĩa</p>
            <p>🎓 Nghề nghiệp: Học sinh</p>
            <p>🏠 Địa chỉ: Trà Giang, Tư Nghĩa, Quảng Ngãi</p>
            <p>🎯 Sở thích: Nghe nhạc, đọc sách</p>
            <p>🌱 Mục tiêu: Phấn đấu trở thành công dân có ích cho xã hội</p>
            <p>📱 Zalo: 0327748643</p>
        </div>
   </section>
   <section id="dream">
        <h3>Ước mơ</h3>
        <div class="dream">
            ✨ Ước mơ của mình là: <b>Sống không thiếu tiền</b> 💸💖<br>
            Luôn cố gắng học tập và phát triển bản thân để đạt được điều đó 🌟
        </div>
   </section>
   <section id="social" class="reveal">
        <h3>Kết nối với mình</h3>
        <div class="social">
            <a href="https://www.facebook.com/thanh.hong.607741/?locale=vi_VN" target="_blank">Facebook</a>
            <a href="https://locket.camera/links/5MLa2bLV4FkXHc7FA" target="_blank">Locket</a>
            <a href="https://www.tiktok.com/@hong1650?_r=1&_t=ZS-94JYGQXQSuK" target="_blank">TikTok</a>
        </div>
   </section>
   <section id="contact">
        <h3>Gửi tin nhắn cho mình</h3>
        <form>
            <input type="text" placeholder="Tên của bạn" required>
            <input type="email" placeholder="Email" required>
            <textarea rows="4" placeholder="Nội dung"></textarea>
            <button type="submit">Gửi</button>
        </form>
    </section>
</div>
<script>
    const text = "Học sinh | Yêu công nghệ | Thích nghe nhạc & đọc sách 💖";
    let index = 0;
    const speed = 80;
    function typeEffect() {
        if (index < text.length) {document.getElementById("typing").innerHTML += text.charAt(index);index++;setTimeout(typeEffect, speed);}}
    typeEffect();
    function reveal() {const reveals = document.querySelectorAll(".reveal");for (let i = 0; i < reveals.length; i++) {const windowHeight = window.innerHeight;const elementTop = reveals[i].getBoundingClientRect().top;const elementVisible = 100;if (elementTop < windowHeight - elementVisible) {reveals[i].classList.add("active");}}}window.addEventListener("scroll", reveal);reveal();
    function createHeart() {const heart = document.createElement("div");heart.classList.add("heart");heart.innerHTML = "💗";heart.style.left = Math.random() * 100 + "vw";heart.style.animationDuration = Math.random() * 3 + 2 + "s";document.body.appendChild(heart);setTimeout(() => {heart.remove();}, 5000);}setInterval(createHeart, 500);
</script>
</body>
</html>
