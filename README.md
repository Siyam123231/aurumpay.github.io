project/
│
├── index.html       (Home Page)
├── services.html    (Services Page)
├── pricing.html     (Pricing Page)
├── contact.html     (Contact Us Page)
├── style.css        (CSS Styling)
└── script.js        (Optional JavaScript, e.g., animations)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="AurumPay - Seamless Payment Processing Solutions for Businesses.">
    <title>AurumPay - Home</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">AurumPay</div>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="services.html">Services</a></li>
                <li><a href="pricing.html">Pricing</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <h1>Welcome to AurumPay</h1>
        <p>Secure and reliable payment processing for your business.</p>
        <a href="services.html" class="cta">Get Started</a>
    </section>

    <footer>
        <p>&copy; 2025 AurumPay. All Rights Reserved.</p>
    </footer>
</body>
</html>
body {
    margin: 0;
    font-family: 'Arial', sans-serif;
    color: #333;
    background-color: #f5f5f5;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #00274d;
    color: #fff;
    padding: 10px 20px;
}

header .logo {
    font-size: 24px;
    font-weight: bold;
    color: #ffd700;
}

header nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
}

header nav ul li a {
    text-decoration: none;
    color: #fff;
    font-weight: bold;
    transition: color 0.3s;
}

header nav ul li a:hover {
    color: #ffd700;
}

.hero {
    text-align: center;
    padding: 100px 20px;
    background: linear-gradient(to bottom, #00274d, #004080);
    color: #fff;
}

.hero h1 {
    font-size: 48px;
    margin: 0;
}

.hero p {
    font-size: 18px;
    margin: 20px 0;
}

.hero .cta {
    display: inline-block;
    padding: 10px 20px;
    background-color: #ffd700;
    color: #00274d;
    font-weight: bold;
    text-decoration: none;
    border-radius: 5px;
    transition: background-color 0.3s;
}

.hero .cta:hover {
    background-color: #e6c200;
}

footer {
    text-align: center;
    padding: 20px;
    background-color: #00274d;
    color: #fff;
}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AurumPay - Services</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">AurumPay</div>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="services.html">Services</a></li>
                <li><a href="pricing.html">Pricing</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section>
        <h1>Our Services</h1>
        <p>We provide a range of payment processing solutions for businesses of all sizes.</p>
        <ul>
            <li>Online payment processing</li>
            <li>In-person payment solutions</li>
            <li>Recurring billing and subscription management</li>
            <li>Advanced fraud protection</li>
        </ul>
    </section>

    <footer>
        <p>&copy; 2025 AurumPay. All Rights Reserved.</p>
    </footer>
</body>
</html>
// Optional: Add interactive elements or animations.
console.log("Welcome to AurumPay!");
