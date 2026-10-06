# the-wizard-study-centre-
the wizard study centre 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Wizard Study Center</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background: #f4f7fb;
            color: #222;
        }

        header {
            background: linear-gradient(135deg, #071952, #088395);
            color: white;
            text-align: center;
            padding: 35px 15px;
        }

        header h1 {
            font-size: 32px;
            margin-bottom: 8px;
        }

        header p {
            font-size: 17px;
        }

        nav {
            background: #fff;
            padding: 15px;
            text-align: center;
            box-shadow: 0 2px 8px #aaa;
            position: sticky;
            top: 0;
            z-index: 10;
        }

        nav a {
            text-decoration: none;
            color: #071952;
            font-weight: bold;
            margin: 0 8px;
        }

        .hero {
            text-align: center;
            padding: 55px 20px;
            background: linear-gradient(135deg, #e8f9ff, #ffffff);
        }

        .hero h2 {
            color: #071952;
            font-size: 30px;
            margin-bottom: 15px;
        }

        .hero p {
            font-size: 18px;
            line-height: 1.6;
        }

        .btn {
            display: inline-block;
            margin-top: 20px;
            padding: 13px 25px;
            background: #e63946;
            color: white;
            text-decoration: none;
            border-radius: 25px;
            font-weight: bold;
        }

        section {
            padding: 40px 20px;
            text-align: center;
        }

        section h2 {
            color: #071952;
            margin-bottom: 25px;
            font-size: 28px;
        }

        .cards {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 18px;
        }

        .card {
            background: white;
            width: 280px;
            padding: 25px;
            border-radius: 15px;
            box-shadow: 0 5px 15px #ccc;
        }

        .card h3 {
            color: #088395;
            margin-bottom: 10px;
        }

        .features {
            background: #071952;
            color: white;
        }

        .features h2 {
            color: white;
        }

        .feature-box {
            background: white;
            color: #222;
            width: 220px;
            padding: 20px;
            border-radius: 12px;
            font-weight: bold;
        }

        .contact {
            background: #e8f9ff;
        }

        .contact p {
            margin: 10px;
            font-size: 17px;
        }

        footer {
            background: #071952;
            color: white;
            text-align: center;
            padding: 20px;
        }

        @media (max-width: 600px) {
            header h1 {
                font-size: 26px;
            }

            .hero h2 {
                font-size: 25px;
            }

            nav a {
                font-size: 13px;
                margin: 3px;
            }

            .card,
            .feature-box {
                width: 100%;
                max-width: 330px;
            }
        }
    </style>
</head>

<body>

<header>
    <h1>📚 The Wizard Study Center</h1>
    <p>Run by:- Sonu Sir</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#courses">Courses</a>
    <a href="#features">Features</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
</nav>

<section class="hero" id="home">
    <h2>Welcome to The Wizard Study Center</h2>

    <p>
        बेहतर शिक्षा • बेहतर तैयारी • बेहतर भविष्य
        <br>
        आपकी सफलता हमारी प्राथमिकता है।
    </p>

    <a href="#contact" class="btn">Contact Us</a>
</section>

<section id="courses">
    <h2>🎓 Our Courses</h2>

    <div class="cards">

        <div class="card">
            <h3>ITI Preparation</h3>
            <p>ITI प्रवेश परीक्षा की बेहतर तैयारी।</p>
        </div>

        <div class="card">
            <h3>Navodaya</h3>
            <p>Navodaya entrance exam की तैयारी।</p>
        </div>

        <div class="card">
            <h3>Polytechnic</h3>
            <p>Polytechnic entrance की विशेष तैयारी।</p>
        </div>

        <div class="card">
            <h3>Sainik School</h3>
            <p>Sainik School entrance exam preparation.</p>
        </div>

        <div class="card">
            <h3>Punjab SLIET</h3>
            <p>SLIET entrance की focused preparation.</p>
        </div>

    </div>
</section>

<section class="features" id="features">
    <h2>⭐ Our Special Features</h2>

    <div class="cards">

        <div class="feature-box">📝 Weekly Test</div>
        <div class="feature-box">📊 Monthly Test</div>
        <div class="feature-box">📚 Extra Classes</div>
        <div class="feature-box">👨‍👩‍👦 PTM</div>

    </div>
</section>

<section id="about">
    <h2>🏫 About Us</h2>

    <p>
        The Wizard Study Center विद्यार्थियों को प्रतियोगी परीक्षाओं
        के लिए बेहतर मार्गदर्शन और गुणवत्तापूर्ण शिक्षा प्रदान करने
        के उद्देश्य से बनाया गया है।
    </p>
</section>

<section class="contact" id="contact">
    <h2>📞 Contact Us</h2>

    <p><b>Director:</b> Sonu Sir</p>
    <p><b>Contact:</b> +91 76318 23485</p>
    <p><b>Address:</b> Murarpur Road, Ward No 7, Moti Pur, Muzaffarpur</p>

    <a class="btn" href="tel:+917631823485">
        📞 Call Now
    </a>
</section>

<footer>
    <p>© 2026 The Wizard Study Center</p>
    <p>Learn Today • Lead Tomorrow 🚀</p>
</footer>

</body>
</html>