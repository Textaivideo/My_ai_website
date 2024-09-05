<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Create AI-Powered Videos</title>
  <style>
    /* General Styling */
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #2C3E50, #4CA1AF);
      color: #fff;
      scroll-behavior: smooth;
    }

    /* Header Styling */
    header {
      text-align: center;
      padding: 50px;
      background-color: rgba(0, 0, 0, 0.6);
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }

    header h1 {
      font-size: 3rem;
      margin: 0;
      color: #f5f5f5;
    }

    header p {
      font-size: 1.2rem;
      color: #ddd;
    }

    /* Discount and Start Button */
    .start-section {
      background-color: #e74c3c;
      padding: 15px;
      border-radius: 5px;
      text-align: center;
      margin-bottom: 30px;
    }

    .start-section a {
      font-size: 1.8rem;
      color: white;
      font-weight: bold;
      text-decoration: none;
    }

    .start-section a:hover {
      color: #f39c12;
    }

    .discount {
      background-color: #27ae60;
      padding: 10px;
      font-size: 1.2rem;
      color: #fff;
      margin-top: 10px;
      display: inline-block;
      border-radius: 10px;
    }

    /* Main Section Styling */
    main {
      max-width: 1000px;
      margin: 50px auto;
      padding: 20px;
      text-align: center;
      background-color: rgba(255, 255, 255, 0.1);
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }

    .cta-button {
      background-color: #f39c12;
      color: white;
      padding: 15px 30px;
      font-size: 1.2rem;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      transition: 0.3s;
    }

    .cta-button:hover {
      background-color: #e67e22;
    }

    /* Video & Image Styling */
    .video-section, .image-section {
      margin: 30px 0;
      text-align: center;
    }

    .image-section img {
      width: 100%;
      max-width: 1000px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    }

    .video-section video {
      width: 100%;
      height: 500px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    }

    /* YouTube Video Styling */
    .youtube-video {
      text-align: center;
      margin: 30px 0;
    }

    .youtube-video iframe {
      width: 100%;
      max-width: 700px;
      height: 350px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    }

    /* Form Styling */
    form input {
      padding: 10px;
      margin: 10px 0;
      font-size: 1.1rem;
      width: 80%;
      max-width: 400px;
      border: 2px solid #fff;
      border-radius: 5px;
      display: block;
      margin-left: auto;
      margin-right: auto;
    }

    form input[type="submit"] {
      background-color: #2ecc71;
      color: white;
      cursor: pointer;
      border: none;
      transition: background-color 0.3s ease;
    }

    form input[type="submit"]:hover {
      background-color: #27ae60;
    }

    /* Get Started Button */
    .get-started {
      display: inline-block;
      background-color: #e74c3c;
      color: white;
      padding: 15px 40px;
      font-size: 1.5rem;
      margin-top: 20px;
      text-decoration: none;
      border-radius: 5px;
      transition: 0.3s;
    }

    .get-started:hover {
      background-color: #c0392b;
    }

  </style>
</head>
<body>

  <!-- YouTube Video Section -->
  <div class="youtube-video">
    <iframe src="https://www.youtube.com/embed/ZsHr52mHoF8?autoplay=1&mute=1" allow="autoplay; encrypted-media" allowfullscreen></iframe>
  </div>

  <!-- Header Section -->
  <header>
    <h1>Start Creating Videos with AI</h1>
    <p>No experience needed. AI handles it all!</p>
  </header>

  <!-- 95% Discount Section -->
  <div class="start-section">
    <a href="#register">Start for just ₹6</a>
    <div class="discount"><a href="#register" style="color: white;">Get 95% OFF Now!</a></div>
  </div>

  <!-- Main Content Section -->
  <main>
    <!-- AI Visual Image from External URL -->
    <div class="image-section">
      <img src="https://assets-static.invideo.io/images/large/Graphic_0ac83b971a.webp" alt="AI Visual Image">
    </div>

    <!-- Video Section 1 (Autoplay and Loop) -->
    <div class="video-section">
      <video src="https://assets-static.invideo.io/files/Landing_Page_Banner_09_08_2023_7a66e00aa8.mp4" autoplay muted loop playsinline></video>
    </div>

    <!-- AI Powered Text-to-Video Maker -->
    <h2>AI powered text-to-video maker</h2>
    <p>Convert Text to Video with AI. The easiest way to turn text to video with AI is here. Create videos for YouTube, Instagram and TikTok with simple text prompts. Just type in your idea to generate a video with stock footage.</p>

    <!-- AI Visual Image 2 -->
    <div class="image-section">
      <img src="https://ik.imagekit.io/sb8yfmfebk/tr:w-800/images/large/Export_0311407e78.webp" alt="AI Visual Image 2">
    </div>

    <!-- Video Section 2 (Autoplay and Loop) -->
    <div class="video-section">
      <video src="https://assets-static.invideo.io/files/Stock_Footage2x_V2_78c7e1c798.mp4" autoplay muted loop playsinline></video>
    </div>
  </main>

  <!-- Registration Section -->
  <section id="register" style="text-align:center; margin: 50px;">
    <h2>Register for Just ₹6</h2>
    <form action="https://rzp.io/i/KlqFjVdhn" method="GET">
      <input type="text" name="name" placeholder="Your Name" required><br>
      <input type="email" name="email" placeholder="Your Email" required><br>
      <input type="password" name="password" placeholder="Create Password" required><br>
      <input type="submit" class="cta-button" value="Get Started for ₹6">
    </form>

    <!-- Created 2024 AI Information -->
    <p>Created 2024 - AI Powered Platform</p>
  </section>

</body>
</html>
