<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PK XD Zero Gravity 2026 - Fan Countdown</title>
    <style>
        /* Modern Space & Neon Theme */
        body {
            background: linear-gradient(135deg, #0f051d, #291147, #005f73);
            background-size: 400% 400%;
            animation: gradientBG 12s ease infinite;
            color: #ffffff;
            font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
            margin: 0;
            padding: 20px;
            box-sizing: border-box;
            text-align: center;
        }

        @keyframes gradientBG {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        .container {
            background: rgba(15, 5, 29, 0.75);
            padding: 40px 30px;
            border-radius: 24px;
            box-shadow: 0 0 30px rgba(0, 210, 255, 0.2), 0 0 60px rgba(255, 0, 127, 0.1);
            backdrop-filter: blur(12px);
            border: 2px solid rgba(255, 255, 255, 0.08);
            max-width: 100%;
            width: 540px; /* كبرنا الحاوية شوية حتى تكفي الـ 5 صناديق براحتها */
            box-sizing: border-box;
        }

        h1 {
            font-size: 2.5rem;
            margin: 0 0 5px 0;
            text-transform: uppercase;
            letter-spacing: 2px;
            background: linear-gradient(to right, #00ffff, #ff007f);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            filter: drop-shadow(0 0 8px rgba(0, 255, 255, 0.6));
        }

        .subtitle {
            font-size: 1.1rem;
            color: #b0a4c2;
            margin-bottom: 10px;
            font-weight: 500;
            letter-spacing: 1px;
        }

        .timezone-badge {
            display: inline-block;
            background: rgba(0, 210, 255, 0.15);
            color: #00ffff;
            padding: 4px 12px;
            border-radius: 20px;
            font-size: 0.8rem;
            font-weight: bold;
            margin-bottom: 30px;
            border: 1px solid rgba(0, 210, 255, 0.3);
        }

        /* Countdown Boxes Setup - هسة صارت 5 صناديق متناسقة */
        .countdown {
            display: flex;
            justify-content: space-between;
            margin-bottom: 35px;
            gap: 8px;
        }

        .time-box {
            background: rgba(255, 255, 255, 0.05);
            padding: 15px 5px;
            border-radius: 14px;
            flex: 1;
            border: 1px solid rgba(0, 255, 255, 0.3);
            box-shadow: 0 0 15px rgba(0, 255, 255, 0.1);
            transition: transform 0.3s ease;
        }

        .time-box:hover {
            transform: translateY(-5px);
            border-color: #ff007f;
            box-shadow: 0 0 15px rgba(255, 0, 127, 0.3);
        }

        .time-box span {
            display: block;
            font-size: 1.8rem; /* صغرنا الخط سكة صغيرة حتى يقعد بالصناديق الـ 5 بشكل مريح بالمويايل */
            font-weight: 800;
            font-family: monospace;
            color: #ffffff;
            text-shadow: 0 0 10px rgba(255, 255, 255, 0.5);
        }

        .time-box .label {
            font-size: 0.7rem;
            color: #00ffff;
            text-transform: uppercase;
            margin-top: 8px;
            font-weight: 700;
            letter-spacing: 1px;
        }

        /* Social Media Buttons Layout */
        .social-links {
            display: flex;
            flex-direction: column;
            gap: 10px;
            margin-bottom: 25px;
        }

        .btn {
            display: block;
            padding: 12px;
            border-radius: 12px;
            text-decoration: none;
            font-weight: bold;
            font-size: 0.95rem;
            transition: all 0.3s ease;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        .btn-youtube {
            background: #ff0000;
            color: #ffffff;
            box-shadow: 0 4px 15px rgba(255, 0, 0, 0.3);
        }
        .btn-youtube:hover {
            background: #cc0000;
            transform: scale(1.02);
        }

        .btn-website {
            background: #9d4edd;
            color: #ffffff;
            box-shadow: 0 4px 15px rgba(157, 78, 221, 0.4);
            border: 1px solid #e0aaff;
        }
        .btn-website:hover {
            background: #7b2cbf;
            transform: scale(1.02);
            box-shadow: 0 4px 20px rgba(224, 170, 255, 0.6);
        }

        .btn-instagram {
            background: linear-gradient(45deg, #f09433, #e6683c, #dc2743, #cc2366, #bc1888);
            color: #ffffff;
            box-shadow: 0 4px 15px rgba(220, 39, 67, 0.3);
        }
        .btn-instagram:hover {
            transform: scale(1.02);
            filter: brightness(1.1);
        }

        .btn-discord {
            background: #5865F2;
            color: #ffffff;
            box-shadow: 0 4px 15px rgba(88, 101, 242, 0.3);
        }
        .btn-discord:hover {
            background: #4752C4;
            transform: scale(1.02);
        }

        /* Credits Footer */
        .footer {
            margin-top: 15px;
            font-size: 0.9rem;
            color: #b0a4c2;
            font-weight: 500;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            padding-top: 15px;
        }

        .footer .brand {
            color: #ff007f;
            font-weight: 700;
            text-shadow: 0 0 8px rgba(255, 0, 127, 0.6);
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Main Titles -->
        <h1>Zero Gravity 2026</h1>
        <div class="subtitle">PK XD Fan Countdown Timer</div>
        <div class="timezone-badge">🇧🇷 June 11, 2026 - 10:00 AM (BRT)</div>

        <!-- The Display Boxes (هنا ضفنا صندوق الأشهر Months) -->
        <div class="countdown">
            <div class="time-box">
                <span id="months">00</span>
                <div class="label">Months</div>
            </div>
            <div class="time-box">
                <span id="days">00</span>
                <div class="label">Days</div>
            </div>
            <div class="time-box">
                <span id="hours">00</span>
                <div class="label">Hours</div>
            </div>
            <div class="time-box">
                <span id="minutes">00</span>
                <div class="label">Min</div>
            </div>
            <div class="time-box">
                <span id="seconds">00</span>
                <div class="label">Sec</div>
            </div>
        </div>

        <!-- Links Links Links -->
        <div class="social-links">
            <a href="https://www.youtube.com/@sophiegamer01" target="_blank" class="btn btn-youtube">📺 Visit My YouTube Channel</a>
            <a href="https://linkbio.co/sophiegamer" target="_blank" class="btn btn-website">🌐 Visit My Main Website</a>
            <a href="https://www.instagram.com/sophiegamer01/" target="_blank" class="btn btn-instagram">📸 Follow Me on Instagram</a>
            <a href="https://discord.gg/9AZb9XaUBK" target="_blank" class="btn btn-discord">💬 Join My Discord Server</a>
        </div>

        <!-- Global Rights -->
        <div class="footer">
            All Rights Reserved © 2026 | Created by <span class="brand">Sophie Gamer</span>
        </div>
    </div>

    <!-- JavaScript Engine (Calculates Months, Days, Hours, Minutes, Seconds) -->
    <script>
        // Target Date set strictly to June 11, 2026, 10:00:00 AM Brazil Time (GMT-0300)
        const targetDate = new Date("June 11, 2026 10:00:00 GMT-0300");

        const timerEngine = setInterval(function() {
            const now = new Date();
            const timeDifference = targetDate.getTime() - now.getTime();

            if (timeDifference < 0) {
                clearInterval(timerEngine);
                document.querySelector(".countdown").innerHTML = "<h2 style='color:#ff007f; text-shadow: 0 0 10px #ff007f;'>🚀 THE EVENT IS LIVE! 🚀</h2>";
                return;
            }

            // الحسابات البرمجة المتقدمة لتفكيك الوقت إلى أشهر وأيام بدقة عالية
            let currentYear = now.getFullYear();
            let currentMonth = now.getMonth();
            
            // حساب الأشهر المتبقية التقريبية
            let months = (targetDate.getFullYear() - currentYear) * 12 + (targetDate.getMonth() - currentMonth);
            
            // نسخة من تاريخ اليوم مضافاً إليها عدد الأشهر المتبقية لضبط الأيام الباقية بدقة
            let checkDate = new Date(now);
            checkDate.setMonth(checkDate.getMonth() + months);
            
            // إذا تجاوزنا اليوم المحدد للشهر الحالي، ننقص شهر ونعيد الحساب
            if (checkDate > targetDate) {
                months--;
                checkDate = new Date(now);
                checkDate.setMonth(checkDate.getMonth() + months);
            }

            // الحسابات الرياضية الدقيقة لباقي الوحدات الزمنية
            const remainingTime = targetDate.getTime() - checkDate.getTime();
            
            const d = Math.floor(remainingTime / (1000 * 60 * 60 * 24));
            const h = Math.floor((timeDifference % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
            const m = Math.floor((timeDifference % (1000 * 60 * 60)) / (1000 * 60));
            const s = Math.floor((timeDifference % (1000 * 60)) / 1000);

            // عرض البيانات داخل الـ 5 صناديق مع إضافة صفر إذا كان الرقم مفرد
            document.getElementById("months").innerHTML = months < 10 ? "0" + months : months;
            document.getElementById("days").innerHTML = d < 10 ? "0" + d : d;
            document.getElementById("hours").innerHTML = h < 10 ? "0" + h : h;
            document.getElementById("minutes").innerHTML = m < 10 ? "0" + m : m;
            document.getElementById("seconds").innerHTML = s < 10 ? "0" + s : s;

        }, 1000);
    </script>

</body>
</html>
