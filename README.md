<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>اولین سایت من</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #6a11cb 0%, #2575fc 100%);
            color: #333;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }
        
        .container {
            background-color: rgba(255, 255, 255, 0.9);
            border-radius: 20px;
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.2);
            padding: 40px;
            text-align: center;
            max-width: 600px;
            width: 100%;
            transition: transform 0.3s ease;
        }
        
        .container:hover {
            transform: translateY(-10px);
        }
        
        h1 {
            color: #2575fc;
            margin-bottom: 20px;
            font-size: 2.5rem;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.1);
        }
        
        p {
            font-size: 1.2rem;
            line-height: 1.8;
            margin-bottom: 30px;
            color: #444;
        }
        
        .emoji {
            font-size: 4rem;
            margin: 20px 0;
            animation: bounce 2s infinite;
        }
        
        @keyframes bounce {
            0%, 100% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-20px);
            }
        }
        
        .btn {
            display: inline-block;
            background: linear-gradient(to right, #6a11cb, #2575fc);
            color: white;
            padding: 12px 30px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: bold;
            font-size: 1.1rem;
            transition: all 0.3s ease;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }
        
        .btn:hover {
            transform: scale(1.05);
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.3);
        }
        
        .features {
            display: flex;
            justify-content: space-around;
            margin-top: 40px;
            flex-wrap: wrap;
        }
        
        .feature {
            flex: 1;
            min-width: 150px;
            margin: 10px;
            padding: 15px;
            background-color: rgba(37, 117, 252, 0.1);
            border-radius: 10px;
        }
        
        .feature h3 {
            color: #2575fc;
            margin-bottom: 10px;
        }
        
        @media (max-width: 600px) {
            .container {
                padding: 20px;
            }
            
            h1 {
                font-size: 2rem;
            }
            
            .features {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="emoji">🚀</div>
        <h1>اولین سایت من</h1>
        <p>به اولین سایت من خوش آمدید! این یک صفحه ساده و زیبا است که با HTML و CSS طراحی شده است. من در حال یادگیری توسعه وب هستم و این اولین قدم من در این مسیر هیجان‌انگیز است.</p>
        <p>امیدوارم از دیدن این صفحه لذت ببرید و این الهام‌بخش شما برای شروع سفر خود در دنیای برنامه‌نویسی وب باشد.</p>
        <a href="#" class="btn">شروع کنید</a>
        
        <div class="features">
            <div class="feature">
                <h3>ساده</h3>
                <p>طراحی تمیز و کاربرپسند</p>
            </div>
            <div class="feature">
                <h3>واکنش‌گرا</h3>
                <p>سازگار با تمام دستگاه‌ها</p>
            </div>
            <div class="feature">
                <h3>مدرن</h3>
                <p>استفاده از جدیدترین تکنیک‌ها</p>
            </div>
        </div>
    </div>
</body>
</html>
