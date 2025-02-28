<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Construction Company</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: white url('image.png') no-repeat center center fixed;
            background-size: cover;
        }
        header {
            background: cyan;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            text-align: center;
            padding: 10px;
            background: #444;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
            display: inline-block;
        }
        .container {
            width: 80%;
            margin: 20px auto;
            background: rgba(255, 255, 255, 0.9);
            padding: 20px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        footer {
            background: black;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .footer-logo {
            max-width: 100px;
            display: block;
            margin: 0 auto 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Our Construction Company</h1>
        <p>Building Your Future with Quality and Integrity</p>
    </header>
    <nav>
        <a href="#ongoing">On-going Projects</a>
        <a href="#completed">Completed Projects</a>
        <a href="#upcoming">Upcoming Projects</a>
        <a href="#services">Services</a>
        <a href="#contacts">Contact</a>
        <a href="#orgchart">Org Chart</a>
    </nav>
    <div class="container">
        <section id="ongoing">
            <h2>On-going Projects</h2>
            <p>Details about the ongoing projects.</p>
        </section>
        <section id="completed">
            <h2>Completed Projects</h2>
            <p>Details about completed projects.</p>
        </section>
        <section id="upcoming">
            <h2>Upcoming Projects</h2>
            <p>Details about upcoming projects.</p>
        </section>
        <section id="services">
            <h2>Services Offered</h2>
            <ul>
                <li>Residential & Commercial Construction</li>
                <li>Infrastructure & Land Development</li>
                <li>Renovations & Remodeling</li>
                <li>Project Management & Consulting</li>
            </ul>
        </section>
        <section id="contacts">
            <h2>Contact Us</h2>
            <p>Email: contact@constructioncompany.com</p>
            <p>Phone: +123 456 7890</p>
        </section>
        <section id="orgchart">
            <h2>Organizational Chart</h2>
            <p>Details about company structure.</p>
        </section>
    </div>
    <footer>
        <img src="logo.png" alt="Company Logo" class="footer-logo">
        <p>&copy; 2025 Construction Company. All rights reserved.</p>
    </footer>
</body>
</html>
