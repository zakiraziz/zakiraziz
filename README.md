<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zakir Aziz - GitHub Profile</title>
    <style>
        body {
            background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
            font-family: 'Poppins', sans-serif;
            color: #ffffff;
            text-align: center;
            padding: 20px;
            scroll-behavior: smooth;
        }
        .container {
            max-width: 800px;
            margin: auto;
            background: rgba(255, 255, 255, 0.1);
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.3);
            animation: fadeIn 1.5s ease-in-out;
        }
        h1 {
            font-size: 2.5em;
            font-weight: bold;
            margin-bottom: 10px;
        }
        #typing {
            font-size: 1.5em;
            color: #f39c12;
            font-weight: bold;
        }
        .btn {
            display: inline-block;
            margin: 10px;
            padding: 10px 20px;
            background: #e74c3c;
            color: white;
            border-radius: 10px;
            text-decoration: none;
            transition: 0.3s;
        }
        .btn:hover {
            background: #c0392b;
            transform: scale(1.1);
        }
        .badges img {
            margin: 5px;
        }
        .profile-pic {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            border: 4px solid white;
            transition: transform 0.3s;
        }
        .profile-pic:hover {
            transform: rotate(10deg) scale(1.1);
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }
    </style>
</head>
<body>
    <div class="container">
        <img src="https://via.placeholder.com/120" alt="Profile Picture" class="profile-pic">
        <h1>Zakir Aziz 👋</h1>
        <p id="typing"></p>
        <script>
            const textArray = ["Hi there, I'm Zakir Aziz!", "A Passionate Programmer!", "Always Learning and Building."];
            let textIndex = 0;
            let charIndex = 0;
            const typingElement = document.getElementById("typing");
            function typeText() {
                if (charIndex < textArray[textIndex].length) {
                    typingElement.textContent += textArray[textIndex][charIndex];
                    charIndex++;
                    setTimeout(typeText, 100);
                } else {
                    setTimeout(() => {
                        typingElement.textContent = "";
                        charIndex = 0;
                        textIndex = (textIndex + 1) % textArray.length;
                        typeText();
                    }, 2000);
                }
            }
            typeText();
        </script>
        
        <h2>🌟 About Me</h2>
        <p>A Passionate Programmer from Pakistan, dedicated to learning and building innovative projects.</p>
        
        <h2>📌 Featured Projects</h2>
        <a href="#" class="btn">Awesome Project 1</a>
        <a href="#" class="btn">Cool Project 2</a>
        
        <h2>🏆 Achievements & Certifications</h2>
        <div class="badges">
            <img src="https://img.shields.io/badge/-Python%20Certified-3776AB?style=for-the-badge&logo=python&logoColor=white" />
            <img src="https://img.shields.io/badge/-JavaScript%20Mastery-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white" />
            <img src="https://img.shields.io/badge/-HTML%20CSS%20Pro-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
        </div>
        
        <h2>📬 Connect with Me</h2>
        <a href="#" class="btn">LinkedIn</a>
        <a href="#" class="btn">Twitter</a>
        <a href="#" class="btn">Email</a>
        
        <footer style="margin-top: 20px; font-style: italic;">"Code is like humor. When you have to explain it, it’s bad."</footer>
    </div>
</body>
</html>
