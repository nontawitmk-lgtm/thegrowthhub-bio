<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Growth Hub | Link in Bio</title>
    <style>
        /* ตั้งค่าพื้นฐาน */
        body {
            margin: 0;
            padding: 0;
            font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
            background-color: #0a0e17; /* สีพื้นหลังสไตล์ Dark Mode */
            color: #e6edf3;
            display: flex;
            flex-direction: column;
            align-items: center;
            min-height: 100vh;
        }

        /* กล่องคอนเทนต์หลัก */
        .container {
            width: 100%;
            max-width: 400px;
            padding: 50px 20px;
            text-align: center;
            box-sizing: border-box;
        }

        /* รูปโปรไฟล์ */
        .profile-pic {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            background-color: #161b22;
            border: 3px solid #00ff66; /* สีเขียวเป้าเล็ง Sniper */
            margin: 0 auto 20px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 60px;
            box-shadow: 0 0 15px rgba(0, 255, 102, 0.2);
        }

        /* ชื่อช่อง */
        h1 {
            font-size: 26px;
            margin: 0 0 10px;
            color: #ffffff;
            letter-spacing: 1px;
        }

        /* คำโปรย / สโลแกน */
        p.bio {
            font-size: 15px;
            line-height: 1.6;
            margin-bottom: 35px;
            color: #8b949e;
        }

        /* การออกแบบปุ่มลิงก์ */
        .link-btn {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 100%;
            padding: 16px;
            margin-bottom: 16px;
            background-color: #1f2428;
            color: #ffffff;
            text-decoration: none;
            border-radius: 10px;
            font-size: 16px;
            font-weight: bold;
            border: 1px solid #30363d;
            transition: all 0.3s ease;
            box-sizing: border-box;
        }

        /* เอฟเฟกต์ตอนนำเมาส์ไปชี้ */
        .link-btn:hover {
            background-color: #00ff66;
            color: #0a0e17;
            border-color: #00ff66;
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(0, 255, 102, 0.3);
        }

        /* ไอคอนหน้าข้อความ */
        .icon {
            margin-right: 12px;
            font-size: 20px;
        }
        
        /* ซ่อนเครดิตให้ดูคลีน */
        .footer {
            margin-top: 40px;
            font-size: 12px;
            color: #484f58;
        }
    </style>
</head>
<body>
    <div class="container">
        
        <div class="profile-pic">🦅</div>
        
        <h1>The Growth Hub</h1>
        
        <p class="bio">
            กระชากหน้ากากกูรู เปิดโปงความจริงวอลล์สตรีท 📉<br>
            เลิกเป็นเหยื่อเจ้ามือ แล้วมาดักซุ่มล่ากำไรจากหุ้นเปลี่ยนโลก! 🎯
        </p>
        
        <!-- ลิงก์ช่องทางต่างๆ แบบกระชับ -->
        <a href="https://www.tiktok.com/@thegrowthhub.97" class="link-btn" target="_blank" rel="noopener noreferrer">
            <span class="icon">⚫</span> Tiktok
        </a>

        <a href="https://www.instagram.com/thegrowthhub.9x/" class="link-btn" target="_blank" rel="noopener noreferrer">
            <span class="icon">🟣</span> Instagram
        </a>

        <a href="https://www.youtube.com/channel/UCZFgTLiwoPYC8ifafHCkXRA" class="link-btn" target="_blank" rel="noopener noreferrer">
            <span class="icon">🔴</span> Youtube
        </a>
        
        <div class="footer">
            © 2026 The Growth Hub. All rights reserved.
        </div>
    </div>
</body>
</html>
