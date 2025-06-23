
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>منصة تداول متقدمة</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Font Awesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Cairo', sans-serif;
            background: linear-gradient(135deg, #1e3c72, #2a5298);
            color: #fff;
            overflow-x: hidden;
        }
        .hero-section {
            min-height: 10vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            background: url('https://source.unsplash.com/random/1920x1080/?finance') no-repeat center center/cover;
            position: relative;
        }
        .hero-section::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.6);
            z-index: 1;
        }
        .hero-content {
            position: relative;
            z-index: 2;
        }
        .hero-content h1 {
            font-size: 3rem;
            font-weight: 700;
            margin-bottom: 20px;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.5);
        }
        .hero-content p {
            font-size: 1.2rem;
            margin-bottom: 30px;
        }
        .btn-primary {
            background-color: #28a745;
            border: none;
            padding: 12px 30px;
            font-size: 1.1rem;
            border-radius: 50px;
            transition: all 0.3s ease;
        }
        .btn-primary:hover {
            background-color: #218838;
            transform: scale(1.05);
        }
        .features-section {
            padding: 80px 0;
            background: #fff;
            color: #333;
        }
        .feature-card {
            background: #f8f9fa;
            padding: 20px;
            border-radius: 15px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            text-align: center;
            height: 100%;
        }
        .feature-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
        }
        .feature-card i {
            font-size: 2.5rem;
            color: #28a745;
            margin-bottom: 15px;
        }
        .footer {
            background: #1e3c72;
            padding: 40px 0;
            text-align: center;
        }
        .footer a {
            color: #fff;
            margin: 0 10px;
            font-size: 1.5rem;
        }
        .footer a:hover {
            color: #28a745;
        }
        @media (max-width: 768px) {
            .hero-content h1 {
                font-size: 2rem;
            }
            .hero-content p {
                font-size: 1rem;
            }
        }
    </style>
</head>
<body>
    <!-- Hero Section -->
    <section class="hero-section">
        <div class="hero-content">
            <h1>ابدأ التداول مع منصتنا المتقدمة</h1>
            <p>تداول آمن وسريع على الفوركس، المعادن، النفط، المؤشرات، والعملات المشفرة</p>
            <a href="https://my.rannforex.com/en/auth/register/?fprc=cf22v1" class="btn btn-primary">سجل الآن</a>
        </div>
    </section>

    <!-- Features Section -->
    <section class="features-section">
        <div class="container">
            <h2 class="text-center mb-5">لماذا تختار منصتنا؟</h2>
            <div class="row g-4">
                <div class="col-md-4 col-sm-6">
                    <div class="feature-card">
                        <i class="fas fa-dollar-sign"></i>
                        <h4>إيداع وسحب سريع</h4>
                        <p>أقل إيداع وسحب 10$ خلال 30 ثانية فقط!</p>
                    </div>
                </div>
                <div class="col-md-4 col-sm-6">
                    <div class="feature-card">
                        <i class="fas fa-percentage"></i>
                        <h4>عمولة منخفضة</h4>
                        <p>استمتع بعمولات قليلة جدًا مع أسبريد من 0.3 إلى 1.2.</p>
                    </div>
                </div>
                <div class="col-md-4 col-sm-6">
                    <div class="feature-card">
                        <i class="fas fa-chart-line"></i>
                        <h4>رافعة مالية عالية</h4>
                        <p>رافعة مالية تصل إلى 1:500 لتحقيق أقصى استفادة.</p>
                    </div>
                </div>
                <div class="col-md-4 col-sm-6">
                    <div class="feature-card">
                        <i class="fas fa-shield-alt"></i>
                        <h4>تداول آمن</h4>
                        <p>أمان عالي مع توثيق 2FA وتداول على جميع الأزواج.</p>
                    </div>
                </div>
                <div class="col-md-4 col-sm-6">
                    <div class="feature-card">
                        <i class="fas fa-wallet"></i>
                        <h4>حسابات متنوعة</h4>
                        <p>4 أنواع من الحسابات: ميتا تريدر 5، بدون عمولة، كريبتو، وحسابات PAMM.</p>
                    </div>
                </div>
                <div class="col-md-4 col-sm-6">
                    <div class="feature-card">
                        <i class="fas fa-star"></i>
                        <h4>تقييم ممتاز</h4>
                        <p>تقييمات رائعة على TrustPilot، Myfxbook، WikiFX، وForex Peace Army.</p>
                    </div>
                </div>
                <div class="col-md-4 col-sm-6">
                    <div class="feature-card">
                        <i class="fas fa-bolt"></i>
                        <h4>تنفيذ فوري</h4>
                        <p>تنفيذ صفقات فوري مع انزلاق منخفض للغاية.</p>
                    </div>
                </div>
                <div class="col-md-4 col-sm-6">
                    <div class="feature-card">
                        <i class="fas fa-globe"></i>
                        <h4>توثيق عالمي</h4>
                        <p>دعم التوثيق من سوريا وجميع الدول الأخرى.</p>
                    </div>
                </div>
                <div class="col-md-4 col-sm-6">
                    <div class="feature-card">
                        <i class="fas fa-hand-holding-usd"></i>
                        <h4>سيولة عالية</h4>
                        <p>نموذج A-Book مع أفضل مزودي السيولة.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <p>منصة تداول موثوقة | © 2025 جميع الحقوق محفوظة</p>
            <div class="social-links">
                <a href="#"><i class="fab fa-facebook"></i></a>
                <a href="#"><i class="fab fa-twitter"></i></a>
                <a href="#"><i class="fab fa-instagram"></i></a>
            </div>
        </div>
    </footer>

    <!-- Bootstrap JS and Popper.js -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
    <!-- Animation on Scroll -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.js"></script>
    <script>
        AOS.init({
            duration: 1000,
            once: true
        });
    </script>
</body>
</html>
