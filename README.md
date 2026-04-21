<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>مستشفى الشفاء</title>
    <style>
        body {
            font-family: Tahoma, Arial;
            margin: 0;
            background-color: #f0f8ff;
        }
        .header {
            background-color: #0077b6;
            color: white;
            padding: 20px;
            text-align: center;
        }
        .nav {
            background-color: #023e8a;
            padding: 10px;
            text-align: center;
        }
        .nav a {
            color: white;
            margin: 15px;
            text-decoration: none;
            font-weight: bold;
        }
        .content {
            padding: 30px;
            max-width: 800px;
            margin: auto;
        }
        .card {
            background: white;
            padding: 20px;
            margin: 15px 0;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .footer {
            background-color: #0077b6;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 30px;
        }
        .btn {
            background-color: #00b4d8;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            font-size: 16px;
        }
    </style>
</head>
<body>

    <div class="header">
        <h1>مستشفى الشفاء التخصصي</h1>
        <p>صحتكم أولويتنا - خدمة 24 ساعة</p>
    </div>

    <div class="nav">
        <a href="#">الرئيسية</a>
        <a href="#about">من نحن</a>
        <a href="#services">الأقسام</a>
        <a href="#contact">اتصل بنا</a>
    </div>

    <div class="content">
        <div class="card" id="about">
            <h2>من نحن</h2>
            <p>مستشفى الشفاء التخصصي يقدم خدمات طبية متكاملة بأحدث الأجهزة وأمهر الأطباء. نعمل على مدار 24 ساعة لخدمتكم.</p>
        </div>

        <div class="card" id="services">
            <h2>أقسامنا الطبية</h2>
            <ul>
                <li><b>قسم الطوارئ</b> - شغال 24 ساعة</li>
                <li><b>قسم الأطفال</b> - رعاية متخصصة</li>
                <li><b>قسم الجراحة</b> - غرف عمليات مجهزة</li>
                <li><b>العيادات الخارجية</b> - جميع التخصصات</li>
                <li><b>المعمل والأشعة</b> - نتائج سريعة ودقيقة</li>
            </ul>
        </div>

        <div class="card" id="contact">
            <h2>اتصل بنا</h2>
            <p><b>العنوان:</b> الخرطوم، أمدرمان - شارع الوادي</p>
            <p><b>هاتف الطوارئ:</b> 1234</p>
            <p><b>الحجز:</b> 0912345678</p>
            <p><b>الإيميل:</b> info@alshifa-hospital.com</p>
            <button class="btn">احجز موعد الآن</button>
        </div>
    </div>

    <div class="footer">
        <p>© 2026 مستشفى الشفاء التخصصي - جميع الحقوق محفوظة</p>
    </div>

</body>
</html>
