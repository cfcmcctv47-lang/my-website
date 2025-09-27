# my-website
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>عالم كرة القدم - موقع متكامل</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: #f0f8ff;
            color: #333;
            line-height: 1.6;
        }
        
        .container {
            width: 95%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 15px;
        }
        
        /* كل الأنماط السابقة تبقى كما هي */
        /* ... */
        
        .deploy-section {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 50px 20px;
            text-align: center;
            border-radius: 15px;
            margin: 40px 0;
        }
        
        .deploy-steps {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin: 30px 0;
        }
        
        .deploy-step {
            background: rgba(255, 255, 255, 0.1);
            padding: 20px;
            border-radius: 10px;
            backdrop-filter: blur(10px);
        }
        
        .deploy-step-number {
            background: #ffd700;
            color: #333;
            width: 40px;
            height: 40px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
            margin: 0 auto 15px;
        }
    </style>
</head>
<body>
    <!-- المحتوى الحالي لموقعك -->
    
    <!-- قسم النشر على الإنترنت -->
    <section class="deploy-section">
        <div class="container">
            <h2>نشر موقعك على الإنترنت</h2>
            <p>اجعل موقعك متاحاً للعالم أجمع بهذه الخطوات البسيطة</p>
            
            <div class="deploy-steps">
                <div class="deploy-step">
                    <div class="deploy-step-number">1</div>
                    <h3>احفظ الكود</h3>
                    <p>احفظ هذه الصفحة كملف index.html على جهازك</p>
                </div>
                <div class="deploy-step">
                    <div class="deploy-step-number">2</div>
                    <h3>اذهب إلى Netlify</h3>
                    <p>افتح <a href="https://netlify.com" style="color: #ffd700;">netlify.com</a> وسجل حساباً</p>
                </div>
                <div class="deploy-step">
                    <div class="deploy-step-number">3</div>
                    <h3>انشر الموقع</h3>
                    <p>اسحب ملف index.html وأسقطه في Netlify</p>
                </div>
                <div class="deploy-step">
                    <div class="deploy-step-number">4</div>
                    <h3>شارك الرابط</h3>
                    <p>احصل على رابطك المجاني وشاركه مع العالم</p>
                </div>
            </div>
            
            <div style="margin-top: 30px;">
                <a href="https://app.netlify.com/drop" class="btn" style="background: #ffd700; color: #333; padding: 12px 30px; font-size: 18px;" target="_blank">
                    <i class="fas fa-cloud-upload-alt"></i> انشر موقعك الآن على Netlify
                </a>
            </div>
        </div>
    </section>

    <!-- باقي محتوى موقعك -->
</body>
</html>
