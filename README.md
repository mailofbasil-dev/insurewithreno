# insurewithreno

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Insirewithreno</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            line-height: 1.6;
            color: #333;
        }

        header {
            background: #003366;
            color: white;
            padding: 15px 50px;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        nav ul {
            list-style: none;
            display: flex;
        }

        nav ul li {
            margin-left: 20px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
        }

        .hero {
            background: linear-gradient(rgba(0,51,102,0.7), rgba(0,51,102,0.7)),
                        url('https://via.placeholder.com/1600x800') center/cover;
            color: white;
            text-align: center;
            padding: 120px 20px;
        }

        .hero h1 {
            font-size: 3rem;
            margin-bottom: 15px;
        }

        .hero p {
            font-size: 1.2rem;
            margin-bottom: 20px;
        }

        .btn {
            display: inline-block;
            background: #ff6600;
            color: white;
            padding: 12px 25px;
            text-decoration: none;
            border-radius: 5px;
        }

        .services {
            padding: 60px 20px;
            text-align: center;
        }

        .service-container {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }

        .card {
            width: 280px;
            padding: 20px;
            border: 1px solid #ddd;
            border-radius: 10px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
        }

        .contact {
            background: #f4f4f4;
            padding: 50px 20px;
            text-align: center;
        }

        .contact input,
        .contact textarea {
            width: 100%;
            max-width: 500px;
            padding: 10px;
            margin: 10px 0;
        }

        footer {
            background: #003366;
            color: white;
            text-align: center;
            padding: 15px;
        }
    </style>
</head>
<body>

    <header>
        <nav>
            <h2>SecureLife Insurance</h2>

            <ul>
                <li>#Home</a></li>
                <li>#Insurance Plans</a></li>
                <li>#Claims</a></li>
                <li>#About Us</a></li>
                <li>#Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <h1>Your Protection, Our Priority</h1>
        <p>Reliable insurance solutions for individuals, families, and businesses.</p>
        #Get a Free Quote</a>
    </section>

    <section class="services">
        <h2>Our Insurance Services</h2>
        <br>

        <div class="service-container">
            <div class="card">
                <h3>Life Insurance</h3>
                <p>Protect your family's financial future with our flexible life insurance plans.</p>
            </div>

            <div class="card">
                <h3>Health Insurance</h3>
                <p>Comprehensive health coverage to keep you and your loved ones secure.</p>
            </div>

            <div class="card">
                <h3>Vehicle Insurance</h3>
                <p>Affordable auto insurance with extensive coverage options.</p>
            </div>
        </div>
    </section>

    <section class="contact">
        <h2>Request a Quote</h2>

        <form>
            <input type="text" placeholder="Your Name" required><br>
            <input type="email" placeholder="Your Email" required><br>
            <textarea rows="5" placeholder="Tell us about your insurance needs"></textarea><br>
            <button class="btn" type="submit">Submit</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2026 Insurewithreno. All Rights Reserved.</p>
    </footer>

</body>
</html>