<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lewis Hamilton</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Navbar -->
    <nav>
        <div class="logo">Lewis Hamilton</div>
        <ul class="nav-links">
            <li><a href="#about">About</a></li>
            <li><a href="#career">Career</a></li>
            <li><a href="#gallery">Gallery</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <!-- Main Section -->
    <main>
        <section id="about" class="about">
            <h1>About Lewis Hamilton</h1>
            <p>Lewis Hamilton is a seven-time Formula 1 World Champion, known for his speed, skill, and determination on and off the track. His influence transcends racing, making him a global icon in the sport.</p>
        </section>

        <!-- Image Slider Section -->
        <section id="gallery" class="slider">
            <div class="slides">
                <input type="radio" name="radio-btn" id="slide1" checked>
                <input type="radio" name="radio-btn" id="slide2">
                <input type="radio" name="radio-btn" id="slide3">
                <input type="radio" name="radio-btn" id="slide4">

                <div class="slide first">
                    <img src="image1.jpg" alt="Lewis Hamilton Image 1">
                </div>
                <div class="slide">
                    <img src="image2.jpg" alt="Lewis Hamilton Image 2">
                </div>
                <div class="slide">
                    <img src="image3.jpg" alt="Lewis Hamilton Image 3">
                </div>
                <div class="slide">
                    <img src="image4.jpg" alt="Lewis Hamilton Image 4">
                </div>

                <div class="navigation-auto">
                    <div class="auto-btn1"></div>
                    <div class="auto-btn2"></div>
                    <div class="auto-btn3"></div>
                    <div class="auto-btn4"></div>
                </div>

                <div class="manual-navigation">
                    <label for="slide1" class="manual-btn"></label>
                    <label for="slide2" class="manual-btn"></label>
                    <label for="slide3" class="manual-btn"></label>
                    <label for="slide4" class="manual-btn"></label>
                </div>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Lewis Hamilton Fan Page. All Rights Reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
