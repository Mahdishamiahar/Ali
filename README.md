# Ali
<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>سایت </title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #6a11cb 0%, #2575fc 100%);
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            color: #fff;
            text-align: center;
            overflow: hidden;
            position: relative;
        }
        
        .container {
            max-width: 800px;
            padding: 30px;
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            border-radius: 20px;
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.2);
            border: 1px solid rgba(255, 255, 255, 0.2);
            z-index: 10;
            animation: fadeIn 1.5s ease-out;
        }
        
        h1 {
            font-size: 3.5rem;
            margin-bottom: 20px;
            text-shadow: 2px 2px 10px rgba(0, 0, 0, 0.3);
        }
        
        p {
            font-size: 1.5rem;
            margin-bottom: 30px;
            line-height: 1.6;
        }
        
        .highlight {
            color: #FFD700;
            font-weight: bold;
        }
        
        .decoration {
            position: absolute;
            border-radius: 50%;
            background: rgba(255, 255, 255, 0.1);
        }
        
        .decoration:nth-child(1) {
            width: 300px;
            height: 300px;
            top: -150px;
            left: -150px;
        }
        
        .decoration:nth-child(2) {
            width: 200px;
            height: 200px;
            bottom: -100px;
            right: -100px;
        }
        
        .decoration:nth-child(3) {
            width: 150px;
            height: 150px;
            top: 50%;
            left: 40%;
        }
        
        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        
        @media (max-width: 768px) {
            h1 {
                font-size: 2.5rem;
            }
            
            p {
                font-size: 1.2rem;
            }
            
            .container {
                margin: 20px;
                padding: 20px;
            }
        }
    </style>
</head>
<body>
    <div class="decoration"></div>
    <div class="decoration"></div>
    <div class="decoration"></div>
    
    <div class="container">
        <h1>به سایت علیرضا خوش آمدید</h1>
        <p></p>
    </div>

    <script>
        // اسکریپت ساده برای افکت‌های تعاملی
        document.addEventListener('DOMContentLoaded', function() {
            const container = document.querySelector('.container');
            
            // افکت هنگام هاور روی container
            container.addEventListener('mouseenter', function() {
                this.style.transform = 'scale(1.02)';
                this.style.transition = 'transform 0.3s ease';
            });
            
            container.addEventListener('mouseleave', function() {
                this.style.transform = 'scale(1)';
            });
        });
    </script>
</body>
</html>
