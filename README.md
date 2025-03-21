<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Abhay Singh - GitHub Profile</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #0d1117;
            color: #c9d1d9;
            text-align: center;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 80%;
            margin: auto;
            padding: 20px;
        }
        h1 {
            font-size: 2.5rem;
        }
        .profile-pic {
            width: 150px;
            border-radius: 50%;
            margin: 20px;
        }
        .social-links a {
            margin: 10px;
            color: #58a6ff;
            font-size: 1.5rem;
            transition: 0.3s;
        }
        .social-links a:hover {
            color: #1f6feb;
        }
        .skills, .projects, .learning, .current, .profile-views {
            margin-top: 30px;
        }
        .skills div, .projects div {
            display: inline-block;
            margin: 10px;
            padding: 15px;
            background: #161b22;
            border-radius: 10px;
            width: 30%;
        }
        .progress-bar {
            width: 100%;
            background: #21262d;
            border-radius: 5px;
            overflow: hidden;
            margin-top: 5px;
        }
        .progress-bar span {
            display: block;
            height: 10px;
            background: #58a6ff;
            width: 80%; /* Adjust per skill */
        }
        .profile-views img {
            width: 80%;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>🚀 Hey there! I'm Abhay Singh</h1>
        <img src="profile.jpg" alt="Profile Picture" class="profile-pic">
        <p>Engineering Student | AI/ML Developer | Robotics & Computer Vision Enthusiast</p>

        <div class="social-links">
            <h2>🌍 Where You Can Find Me</h2>
            <a href="https://github.com/Abhay-Singh312" target="_blank"><i class="fab fa-github"></i></a>
            <a href="https://www.linkedin.com/in/abhay-singh312/" target="_blank"><i class="fab fa-linkedin"></i></a>
            <a href="mailto:abhayr24564@gmail.com"><i class="fas fa-envelope"></i></a>
            <p><a href="#">Portfolio (Coming Soon)</a> - A showcase of my projects and ideas!</p>
        </div>

        <div class="skills">
            <h2>🛠️ Tech Stack</h2>
            <div><b>Python & AI</b><div class="progress-bar"><span style="width: 90%;"></span></div></div>
            <div><b>Computer Vision</b><div class="progress-bar"><span style="width: 85%;"></span></div></div>
            <div><b>Cybersecurity</b><div class="progress-bar"><span style="width: 75%;"></span></div></div>
        </div>

        <div class="learning">
            <h2>📚 Learning & Experimenting</h2>
            <p>🔹 Deep Learning & AI: Training LSTMs, CNNs, and NLP models.</p>
            <p>🔹 Computer Vision & Robotics: Developing automation solutions using OpenCV and PyTorch.</p>
            <p>🔹 Cybersecurity & Ethical Hacking: Exploring security tools and AI-driven defense mechanisms.</p>
        </div>

        <div class="projects">
            <h2>🚀 Featured Projects</h2>
            <div><b>Real-Time Sign Language Recognition</b><p>LSTM-based model for recognizing sign language gestures.</p></div>
            <div><b>HandGestureAutomation</b><p>Control your computer using hand gestures via webcam tracking.</p></div>
            <div><b>Jarvis-Desktop-Assistance</b><p>A Python-based voice assistant with GUI integration.</p></div>
        </div>

        <div class="profile-views">
            <h2>📊 Profile Views</h2>
            <img src="https://github-readme-streak-stats.herokuapp.com/?user=Abhay-Singh312&theme=dark" alt="GitHub Streak">
        </div>

        <div class="current">
            <h2>👀 Currently Seeking</h2>
            <p>Opportunities in <b>AI, Robotics, and Computer Vision</b>—whether it's research, open-source contributions, or industry projects. If you're working on something exciting, I'd love to collaborate!</p>
        </div>
    </div>
</body>
</html>
