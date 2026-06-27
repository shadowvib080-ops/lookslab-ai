<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LooksLab AI</title>

    <link rel="stylesheet" href="style.css">

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
</head>

<body>

<nav class="navbar">

    <div class="logo">
        LooksLab <span>AI</span>
    </div>

    <ul class="nav-links">
        <li><a href="#">Home</a></li>
        <li><a href="#">Features</a></li>
        <li><a href="#">Premium</a></li>
        <li><a href="#">Login</a></li>
    </ul>

</nav>

<section class="hero">

    <h1>Become the Best Version of Yourself</h1>

    <p>
        AI-powered appearance coaching that helps you improve your grooming,
        skincare, hairstyle, fashion and confidence.
    </p>

    <label class="upload-btn">

        Upload Selfie

        <input
            type="file"
            id="photo"
            accept="image/*"
            hidden>

    </label>

    <div id="preview">

        <div class="placeholder">

            📷

            <p>No photo selected</p>

        </div>

    </div>

    <button id="analyzeBtn">
        Analyze Face
    </button>

</section>

<section class="features">

    <div class="card">

        <h2>🤖 AI Analysis</h2>

        <p>
            Receive personalized appearance feedback.
        </p>

    </div>

    <div class="card">

        <h2>📈 Progress</h2>

        <p>
            Track your improvement over time.
        </p>

    </div>

    <div class="card">

        <h2>💎 Premium</h2>

        <p>
            Unlock advanced reports and hairstyle previews.
        </p>

    </div>

</section>

<footer>

    <h3>LooksLab AI</h3>

    <p>
        Become the Best Version of Yourself.
    </p>

</footer>

<script src="script.js"></script>

</body>
</html>
