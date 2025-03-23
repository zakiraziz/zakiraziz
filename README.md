
<div style="background: linear-gradient(135deg, #0F2027, #203A43, #2C5364); padding: 30px; border-radius: 20px; box-shadow: 0px 5px 25px rgba(0, 0, 0, 0.3); font-family: 'Poppins', sans-serif; color: #F1FAEE;">
  <div style="text-align: center; margin-bottom: 25px;">
    <img src="https://img.freepik.com/free-vector/programmer-concept-illustration_114360-2285.jpg" style="width: 80%; border-radius: 20px; margin-bottom: 20px; box-shadow: 0px 4px 15px rgba(0, 0, 0, 0.2);" />
  </div>

  <h1 align="center" style="font-size: 3.5em; font-weight: bold;">
    <span id="typing"></span><span style="color: #E63946;">|</span> 🚀
  </h1>

  <script>
    const textArray = ["Hello, I'm Zakir Aziz!", "Creative Developer & Coder", "Building Awesome Projects! 🚀"];
    let textIndex = 0;
    let charIndex = 0;
    const typingElement = document.getElementById("typing");
    function typeText() {
      if (charIndex < textArray[textIndex].length) {
        typingElement.innerHTML += textArray[textIndex][charIndex];
        charIndex++;
        setTimeout(typeText, 100);
      } else {
        setTimeout(() => {
          typingElement.innerHTML = "";
          charIndex = 0;
          textIndex = (textIndex + 1) % textArray.length;
          typeText();
        }, 2000);
      }
    }
    typeText();
  </script>

  <h3 align="center" style="color: #A8DADC; font-weight: 600;">Innovative Programmer from Pakistan</h3>      
  <hr style="border: 1px solid #A8DADC; width: 80%; margin: 20px auto;" />

  <p align="center">
    <img src="https://komarev.com/ghpvc/?username=zakiraziz&label=Profile%20Views&color=E63946&style=flat" alt="Profile Views" />
  </p>

  <div align="center">
    <a href="https://github.com/zakiraziz" style="font-size: 1.4em; color: #F77F00; text-decoration: none; font-weight: bold; transition: 0.3s;" onmouseover="this.style.color='#FFD166'" onmouseout="this.style.color='#F77F00'">
      🌟 Explore My GitHub Projects
    </a>
  </div>

  <h3 align="center" style="font-weight: bold; color: #F1FAEE;">🏆 Achievements & Certifications</h3>
  <div align="center">
    <img src="https://img.shields.io/badge/-Python%20Certified-3776AB?style=for-the-badge&logo=python&logoColor=white" style="margin: 5px;" />
    <img src="https://img.shields.io/badge/-JavaScript%20Mastery-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" style="margin: 5px;" />
    <img src="https://img.shields.io/badge/-HTML%20CSS%20Pro-1572B6?style=for-the-badge&logo=css3&logoColor=white" style="margin: 5px;" />
  </div>

  <h3 align="center" style="font-weight: bold; color: #F1FAEE;">✨ Featured Projects ✨</h3>
  <div align="center">
    <a href="https://github.com/zakiraziz/some-awesome-project">
      <img src="https://img.shields.io/badge/-Awesome%20Project%201-E63946?style=for-the-badge" style="margin: 5px;" />
    </a>
    <a href="https://github.com/zakiraziz/another-cool-project">
      <img src="https://img.shields.io/badge/-Cool%20Project%202-457B9D?style=for-the-badge" style="margin: 5px;" />
    </a>
  </div>

  <h3 align="center" style="font-weight: bold; color: #F1FAEE;">📬 Connect with Me</h3>
  <div align="center">
    <a href="https://www.linkedin.com/in/zakiraziz" target="_blank">
      <img src="https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" style="margin: 5px;" />
    </a>
    <a href="https://twitter.com/zakiraziz" target="_blank">
      <img src="https://img.shields.io/badge/-Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" style="margin: 5px;" />
    </a>
    <a href="mailto:zakiraziz@example.com">
      <img src="https://img.shields.io/badge/-Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" style="margin: 5px;" />
    </a>
  </div>

  <footer style="text-align: center; margin-top: 40px; color: #A8DADC; font-style: italic; font-size: 1.2em;">
    "Creativity is intelligence having fun!" 🚀
  </footer>
</div>
