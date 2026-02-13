<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>أحمد – Portfolio</title>
<link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap" rel="stylesheet">
<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Cairo', sans-serif;
}
body {
    background: #f0f2f5;
    color: #333;
    scroll-behavior: smooth;
}
header {
    background: #0d1117;
    color: #fff;
    padding: 60px 20px;
    text-align: center;
}
header h1 {
    font-size: 48px;
    margin-bottom: 10px;
}
header p {
    font-size: 20px;
    color: #c9d1d9;
}
nav {
    background: #161b22;
    display: flex;
    justify-content: center;
    padding: 15px 0;
}
nav a {
    color: #c9d1d9;
    text-decoration: none;
    margin: 0 20px;
    font-weight: bold;
    transition: 0.3s;
}
nav a:hover {
    color: #58a6ff;
}
section {
    padding: 80px 20px;
    text-align: center;
}
.hero {
    background: linear-gradient(135deg, #58a6ff, #1f6feb);
    color: white;
    padding: 120px 20px;
}
.hero h1 {
    font-size: 48px;
    margin-bottom: 20px;
}
.hero p {
    font-size: 22px;
}
.btn {
    display: inline-block;
    margin-top: 30px;
    padding: 12px 30px;
    background: #fff;
    color: #1f6feb;
    text-decoration: none;
    font-weight: bold;
    border-radius: 30px;
    transition: 0.3s;
}
.btn:hover {
    background: #1f6feb;
    color: #fff;
}
.cards {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
    margin-top: 40px;
}
.card {
    background: #fff;
    padding: 25px;
    width: 280px;
    border-radius: 12px;
    box-shadow: 0 10px 20px rgba(0,0,0,0.08);
    transition: 0.3s;
}
.card:hover {
    transform: translateY(-5px);
    box-shadow: 0 15px 25px rgba(0,0,0,0.15);
}
.card h3 {
    margin-bottom: 10px;
    color: #1f6feb;
}
input, textarea {
    width: 80%;
    padding: 12px;
    margin: 10px 0;
    border-radius: 8px;
    border: 1px solid #ccc;
}
button {
    padding: 12px 25px;
    background: #1f6feb;
    color: #fff;
    border: none;
    border-radius: 25px;
    cursor: pointer;
    transition: 0.3s;
}
button:hover {
    background: #0d4ec7;
}
footer {
    background: #0d1117;
    color: #c9d1d9;
    padding: 25px 20px;
    text-align: center;
}
.whatsapp-btn {
    position: fixed;
    bottom: 20px;
    right: 20px;
    background: #25d366;
    color: white;
    padding: 15px 20px;
    border-radius: 50px;
    font-weight: bold;
    text-decoration: none;
    box-shadow: 0 5px 15px rgba(0,0,0,0.3);
    transition: 0.3s;
}
.whatsapp-btn:hover {
    background: #1ebe57;
}
@media(max-width:768px){
    .cards{
        flex-direction: column;
        align-items: center;
    }
}
</style>
</head>
<body>

<header>
    <h1>أحمد</h1>
    <p>مبرمج شغوف بالبرمجيات، أحب تطوير الحلول الرقمية وإنشاء مواقع وتطبيقات مبتكرة.</p>
</header>

<nav>
    <a href="#about">عني</a>
    <a href="#services">خدماتي</a>
    <a href="#portfolio">أعمالي</a>
    <a href="#contact">تواصل</a>
</nav>

<section class="hero">
    <h1>مرحبًا بك في موقعي</h1>
    <p>أعرض هنا خدماتي وأعمالي الرقمية</p>
    <a href="#contact" class="btn">تواصل معي</a>
</section>

<section id="about">
    <h2>من أنا</h2>
    <p>أنا مبرمج شغوف بالبرمجيات، أحب تطوير الحلول الرقمية وإنشاء مواقع وتطبيقات مبتكرة تساعد المستخدمين على تحسين حياتهم الرقمية.</p>
</section>

<section id="services">
    <h2>خدماتي</h2>
    <div class="cards">
        <div class="card">
            <h3>تطوير مواقع ويب</h3>
            <p>تصميم وبرمجة مواقع ويب احترافية متجاوبة مع جميع الأجهزة.</p>
        </div>
        <div class="card">
            <h3>برمجة تطبيقات</h3>
            <p>إنشاء تطبيقات سطح المكتب والموبايل باستخدام أحدث التقنيات.</p>
        </div>
        <div class="card">
            <h3>تصميم واجهات مستخدم</h3>
            <p>تصميم واجهات جميلة وسهلة الاستخدام لتجربة مستخدم ممتازة.</p>
        </div>
    </div>
</section>

<section id="portfolio">
    <h2>أعمالي</h2>
    <div class="cards">
        <div class="card">
            <h3>مشروع ويب شخصي</h3>
            <p>موقع تعريفي لعرض أعمالي ومهاراتي في البرمجة والتصميم.</p>
        </div>
        <div class="card">
            <h3>تطبيق لإدارة المهام</h3>
            <p>تطبيق لتسهيل تنظيم المهام اليومية وزيادة الإنتاجية.</p>
        </div>
        <div class="card">
            <h3>لعبة بسيطة</h3>
            <p>مشروع تعليمي لتعلم البرمجة بطريقة تفاعلية وممتعة.</p>
        </div>
    </div>
</section>

<section id="contact">
    <h2>تواصل معي</h2>
    <form>
        <input type="text" placeholder="اسمك" required><br>
        <input type="email" placeholder="بريدك الإلكتروني" required><br>
        <textarea rows="5" placeholder="رسالتك"></textarea><br>
        <button type="submit">إرسال</button>
    </form>
</section>

<a href="https://wa.me/967713844416" class="whatsapp-btn" target="_blank">واتساب</a>

<footer>
    <p>© 2026 جميع الحقوق محفوظة | البريد: u7309224908@gmail.com</p>
</footer>

</body>
</html>
