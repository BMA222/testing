<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        /* Basic reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
        }
        /* Navigation bar styling */
        .navbar {
            background-color: #ffba43;
            overflow: hidden;
            position: fixed;
            top: 0;
            width: 100%;
            z-index: 1000;
        }
        .navbar a {
            float: left;
            display: block;
            color: rgb(0, 0, 0);
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
            font-size: 20px;
        }
        .navbar a:hover {
            background-color: #e97676;
        }
        /* Hero section styling */
        .hero {
            height: 150vh;
            background: url('img/fox.jpg') no-repeat center center/cover;
            display: flex;
            justify-content: center;
            padding-top: 60px;
            align-items: center ;
            color: #000000;
            text-align: center;
            font-family: Arial, sans-serif;
        }
        .hero h1 {
            margin-top: 100px;
            font-size: 50px;
        }
        .hero h2 {
            font-size: 50px;
            margin-bottom: 500px;
        }
        /* About Me section */
        .about {
            padding: 50px;
            background-color: #000000;
            color:#ffffff
        }
        .about h2 {
            margin-bottom: 20px;
        }
        /* Work Experience section */
        .work-experience {
            padding: 50px;
            background-color: #fff;
        }
        .work-experience h2 {
            margin-bottom: 20px;
        }
        /* Contact section */
        .contact {
            padding: 50px;
            background-color: #f4f4f4;
        }
        .contact h2 {
            margin-bottom: 20px;
        }
        .contact form {
            display: flex;
            flex-direction: column;
        }
        .contact input, .contact textarea {
            margin-bottom: 10px;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .contact button {
            padding: 10px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .contact button:hover {
            background-color: #45a049;
        }
        /* Footer */
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px 0;
        }
        footer p {
            margin: 0;
        }
    </style>
</head>
<body>
    <!-- Top Navigation Bar -->
    <div class="navbar">
        <a href="#hero">Home</a>
        <a href="#about">About Me</a>
        <a href="#work-experience">Work Experience</a>
        <a href="#contact">Contact</a>
    </div>
    <!-- Hero Section -->
    <section id="hero" class="hero">
        <div>
            <h1>Hi, my name is Barsa</h1>
            <h2>Welcome to my Portfolio</h2>
        </div>
    </section>
    <!-- Content Wrapper to avoid overlap with navbar -->
    <div class="content">
        <!-- About Me Section -->
        <section id="about" class="about">
            <h2>About Me</h2>
            <p>Hello my name is Barsa and I am a second year student of software engineering at Western university.</p>
        </section>
        <!-- Work Experience Section -->
        <section id="work-experience" class="work-experience">
            <h2>Work Experience</h2>
            <ul>
                <li><strong>Call center assistant</strong> - Myinsurancebroker (2023-2024)</li>
                <p>Assisted people by guiding their calls into the correct department.</p>
                <li><strong>processing admin</strong> - Myinsurancebroker (2024 - present)</li>
                <p>Assisted filling out and insuring quality on insurance policies.</p>
            </ul>
        </section>
        <!-- Contact Section -->
        <section id="contact" class="contact">
            <h2>Contact Me</h2>
            <form action="#">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
                <button type="submit">Send Message</button>
            </form>
        </section>
    </div>
    <!-- Footer Section -->
    <footer>
        <p>&copy; Contact me at: Instagram: n/a X: n/a Facebook: n/a </p>
    </footer>
</body>
</html>
