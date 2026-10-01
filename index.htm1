<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FL!P | شكراً لتسوقك</title>
    <link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@400;700;900&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Tajawal', sans-serif;
        }
        body {
            background-color: #050814;
            color: #ffffff;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
            overflow-x: hidden;
            position: relative;
        }
        body::before {
            content: '';
            position: absolute;
            width: 300px;
            height: 300px;
            background: radial-gradient(circle, rgba(13, 27, 42, 0.8) 0%, rgba(5, 8, 20, 0) 70%);
            top: -50px;
            right: -50px;
            z-index: -1;
        }
        .container {
            width: 100%;
            max-width: 420px;
            background: rgba(13, 27, 42, 0.6);
            backdrop-filter: blur(16px);
            border: 1px solid rgba(255, 255, 255, 0.1);
            border-radius: 24px;
            padding: 35px 25px;
            text-align: center;
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.6);
            animation: fadeIn 0.8s ease-out;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        .logo-area {
            margin-bottom: 25px;
        }
        .logo-area h1 {
            font-size: 38px;
            font-weight: 900;
            letter-spacing: 3px;
            color: #ffffff;
            text-shadow: 0 0 15px rgba(255, 255, 255, 0.3);
        }
        .logo-area h1 span {
            color: #3b82f6;
        }
        .welcome-msg h2 {
            font-size: 22px;
            font-weight: 700;
            margin-bottom: 10px;
            color: #f8fafc;
        }
        .welcome-msg p {
            font-size: 14px;
            color: #94a3b8;
            line-height: 1.6;
            margin-bottom: 25px;
        }
        .coupon-box {
            background: rgba(255, 255, 255, 0.05);
            border: 2px dashed rgba(59, 130, 246, 0.5);
            border-radius: 16px;
            padding: 20px;
            margin-bottom: 25px;
            transition: all 0.3s ease;
        }
        .coupon-box:hover {
            border-color: #3b82f6;
            background: rgba(59, 130, 246, 0.05);
        }
        .coupon-title {
            font-size: 13px;
            color: #94a3b8;
            margin-bottom: 8px;
            text-transform: uppercase;
            letter-spacing: 1px;
        }
        .coupon-code {
            font-size: 26px;
            font-weight: 900;
            color: #3b82f6;
            letter-spacing: 2px;
            margin-bottom: 15px;
        }
        .copy-btn {
            background: #3b82f6;
            color: white;
            border: none;
            width: 100%;
            padding: 12px;
            border-radius: 10px;
            font-size: 15px;
            font-weight: 700;
            cursor: pointer;
            transition: all 0.2s ease;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 8px;
        }
        .copy-btn:active {
            transform: scale(0.97);
        }
        .copy-btn.copied {
            background: #10b981;
        }
        .links-list {
            display: flex;
            flex-direction: column;
            gap: 12px;
        }
        .social-link {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
            background: rgba(255, 255, 255, 0.07);
            color: #ffffff;
            text-decoration: none;
            padding: 14px;
            border-radius: 12px;
            font-size: 15px;
            font-weight: 700;
            transition: all 0.3s ease;
            border: 1px solid rgba(255, 255, 255, 0.05);
        }
        .social-link:hover {
            background: rgba(255, 255, 255, 0.15);
            transform: translateY(-2px);
            border-color: rgba(255, 255, 255, 0.2);
        }
        .social-link i {
            font-size: 18px;
        }
        .footer-note {
            margin-top: 25px;
            font-size: 12px;
            color: #64748b;
            letter-spacing: 1px;
        }
    </style>
</head>
<body>

    <div class="container">
        <div class="logo-area">
            <h1>FL<span>!</span>P</h1>
        </div>

        <div class="welcome-msg">
            <h2>شكراً لانضمامك إلى عالمنا 🌌</h2>
            <p>نحن فخورون بكونك جزءاً من رحلة FL!P. تقديراً لثقتك، جهزنا لك هذا الخصم الحصري لطلبك القادم.</p>
        </div>

        <div class="coupon-box">
            <div class="coupon-title">كود الخصم الخاص بك</div>
            <div class="coupon-code" id="codeText">FLIP15</div>
            <button class="copy-btn" id="copyBtn" onclick="copyCoupon()">
                <i class="fa-regular fa-copy"></i> نسخ الكود
            </button>
        </div>

        <div class="links-list">
            <a href="https://salla.sa" target="_blank" class="social-link">
                <i class="fa-solid fa-store"></i> متجرنا الإلكتروني
            </a>
            <a href="https://instagram.com" target="_blank" class="social-link">
                <i class="fa-brands fa-instagram"></i> انستقرام
            </a>
            <a href="https://tiktok.com" target="_blank" class="social-link">
                <i class="fa-brands fa-tiktok"></i> تيك توك
            </a>
        </div>

        <div class="footer-note">
            FL!P STREETWEAR © 2026
        </div>
    </div>

    <script>
        function copyCoupon() {
            const code = document.getElementById('codeText').innerText;
            navigator.clipboard.writeText(code);
            const btn = document.getElementById('copyBtn');
            btn.innerHTML = '<i class="fa-solid fa-check"></i> تم النسخ بنجاح!';
            btn.classList.add('copied');
            
            setTimeout(() => {
                btn.innerHTML = '<button class="copy-btn"><i class="fa-regular fa-copy"></i> نسخ الكود</button>';
                btn.innerHTML = '<i class="fa-regular fa-copy"></i> نسخ الكود';
                btn.classList.remove('copied');
            }, 2500);
        }
    </script>
</body>
</html>
