<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your YouTube Channel</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #ff0000;
            color: white;
            padding: 20px 10px;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        header .cta {
            margin-top: 10px;
            display: inline-block;
            padding: 10px 20px;
            background: white;
            color: #ff0000;
            text-decoration: none;
            border-radius: 5px;
        }
        main {
            padding: 20px;
        }
        section {
            margin-bottom: 30px;
        }
        section h2 {
            border-bottom: 2px solid #ff0000;
            display: inline-block;
            padding-bottom: 5px;
        }
        .video-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }
        .video-grid iframe {
            width: 100%;
            height: 200px;
            border: none;
        }
        form input, form textarea, form button {
            display: block;
            width: 100%;
            margin-bottom: 10px;
            padding: 10px;
        }
        form button {
            background-color: #ff0000;
            color: white;
            border: none;
            cursor: pointer;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #333;
            color: white;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to PixelPioneer 13, the place to get all the Tottenham updates and gaming entertainment in one channel.</p>
        </section>

        <section id="latest-videos">
            <h2>Latest Videos</h2>
            <div class="video-grid">
                <iframe src="https://www.youtube.com/embed/ROG4nB4MLcg" allowfullscreen></iframe>
                <iframe src="https://www.youtube.com/embed/example2" allowfullscreen></iframe>
                <iframe src="https://www.youtube.com/embed/example3" allowfullscreen></iframe>
            </div>
        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <form action="#" method="post">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
                <button type="submit">Send</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 PixelPioneer 13. All Rights Reserved.</p>
    </footer>
</body>
</html>
