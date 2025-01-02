<!DOCTYPE html>
<html dir="rtl" lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>الأكاديمية التعليمية</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Cairo', sans-serif;
        }

        body {
            background-color: #f5f5f5;
        }

        .header {
            background-color: #373c41;
            padding: 20px;
            color: white;
            
        }
        .h1{
            direction: rtl;
            text-align: right;
        }
        .h2{
            direction: ltr;
            text-align: left;
        }
        .main-content {
            margin: 20px auto;
            padding: 10px;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            display: flex;
            justify-content: space-around;
            align-items: center;
            background-color:#f5f5f5;
            border-top: 1px solid #ddd;
            display: grid;
    grid-template-columns: repeat(3, 1fr); 
    gap: 10px;
    text-align: center; 
        }
        .navbar {
            display: flex;
            justify-content: space-around;
            align-items: center;
            background-color: #f5f5f5;
            border-top: 1px solid #ddd;
            padding: 8px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
            box-shadow: 0 -2px 5px rgba(0, 0, 0, 0.1);
        }

        .navbar-item {
            text-align: center;
            color: #555;
            text-decoration: none;
            font-size: 14px;
        }

        .navbar-item img {
            display: block;
            margin: 0 auto 5px;
            width: 20px;
            height: 20px;
        }

        .navbar-item:hover {
            color: #000;
        }
        .course-card {
            background-color: white;
            border-radius: 10px;
            padding: 15px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        .course-card img {
            width: 150px;
            height: 150px;
            object-fit: cover;
            border-radius: 5px;
        }

        .course-card h3 {
            margin: 10px 0;
            color: #2c3e50;
        }

        .course-card p {
            color: black;
            margin-bottom: 20px;
        }

        .btn {
            background-color: #3498db;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            display: inline-block;
            text-decoration: none;
        }

        .btn:hover {
            background-color: #2980b9;
        }

        .footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }
        a{
            text-decoration: none;
            transition: 0.2s;
        }
        a:hover{
            font-size: 15px;

            
        }
    </style>
</head>
<body>
    <header class="header">
        <h2 class="h1">سهلناها</h1>
        <h2 class="h2">shlnaha</h1>
        <p></p>
    </header>

    <main class="main-content">
        <div class="course-card">
            <a href="#">
            <img src="C:\Users\user\Desktop\New folder (4)\stadi.png" alt="">
            
            <p style="font-family:tahoma; height: 5px;">حجز ملاعب</p>
            </a>
        </div>

        <div class="course-card">
            <a href="#">
            <img src="C:\Users\user\Desktop\New folder (4)\stad.png" alt="">
            
            <p style="font-family:tahoma; height: 5px;">حجز الأكاديمية</p>
            </a>
        </div>

        <div class="course-card">
            <a href="#">
            <img src="C:\Users\user\Desktop\New folder (4)\coach.png" alt="coach">
            
            <p style="font-family:tahoma; height: 5px;">حجز مدرب خاص</p>
            </a>
        </div>

        

        <div class="course-card">
            <a href="#">
            <img src="C:\Users\user\Desktop\New folder (4)\gym.png" alt="">
            
            <p style="font-family:tahoma; height: 5px;">اشتراك جيم</p>
            </a>
        </div>
    
    
        <div class="course-card">
            <a href="#">
            <img src="C:\Users\user\Desktop\New folder (4)\store.png" alt="">
            
            <p style="font-family:tahoma; height: 5px;">سهلناها store</p>
            </a>
        </div>
    
    
    
    
    
        <div class="course-card">
            <a href="#">
            <img src="C:\Users\user\Desktop\New folder (4)\wes.png" alt="">
            
            <p style="font-family:tahoma; height: 5px;">ذوي الاحتياجات الخاصة</p>
            </a>
        </div>
    
    
        <div class="course-card">
            <a href="#">
            <img src="C:\Users\user\Desktop\New folder (4)\med.png" alt="">
            
            <p style="font-family:tahoma; height: 5px;">العلاج الطبيعي</p>
            </a>
        </div>
    







        <div class="course-card">
            <a href="#">
            <img src="C:\Users\user\Desktop\New folder (4)\cup.png" alt="">
            
            <p style="font-family:tahoma; height: 5px;">البطولات</p>
            </a>
        </div>
    
    
    </main>
    <br>
    <br>
    

    <div class="navbar">
        <a href="#home" class="navbar-item">
            <img src="C:\Users\user\Desktop\New folder (4)\home icon.jpg" alt="My Bookings">

            الرئيسية
        </a>
        <a href="#reservations" class="navbar-item">
            <img src="C:\Users\user\Desktop\New folder (4)\file.png" alt="My Bookings">
            حجوزاتي
        </a>
        <a href="#alternatives" class="navbar-item">
            <img src="C:\Users\user\Desktop\New folder (4)\team icon.png" alt="Alternatives" style="height: 22px; width: 22px;">
            مباراتي بدل
        </a>
        <a href="#ads" class="navbar-item">
            <img src="C:\Users\user\Desktop\New folder (4)\ads.png" alt="Ads">
            الإعلانات
        </a>
        <a href="#account" class="navbar-item">
            <img src="C:\Users\user\Desktop\New folder (4)\account.png" alt="Account">
            الحساب
        </a>
    </div>
    </html>
