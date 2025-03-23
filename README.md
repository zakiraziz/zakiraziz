<div style="background: linear-gradient(135deg, #F1FAEE, #A8DADC); padding: 25px; border-radius: 20px; box-shadow: 0px 5px 20px rgba(0, 0, 0, 0.15); font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">
  <div style="text-align: center; margin-bottom: 25px;">
    <img src="https://files.oaiusercontent.com/file-CkNvebYhfEJWe7EpdPMDVR?se=2025-02-11T15%3A49%3A24Z&sp=r&sv=2024-08-04&sr=b&rscc=max-age%3D604800%2C%20immutable%2C%20private&rscd=attachment%3B%20filename%3D7fc38e23-9f9f-4631-926b-f689f1005ed3.webp&sig=OlESCr/yPcyi0TfVFcQMa0wMAlIePUuZzDWZcacVssY%3D" style="width: 100%; border-radius: 15px; margin-bottom: 20px; box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);" />
    <img src="https://files.oaiusercontent.com/file-PvLxFhXGuxUPFwVocyaB1U?se=2025-02-11T15%3A50%3A18Z&sp=r&sv=2024-08-04&sr=b&rscc=max-age%3D604800%2C%20immutable%2C%20private&rscd=attachment%3B%20filename%3Dd0638351-7fec-4455-b58e-48a281349a91.webp&sig=owBb/i%2BlC4Ds4zk%2B7HAwIplzC0TXjBbAcS8pxAvuxsU%3D" alt="Profile Picture" 
         style="border-radius: 50%; width: 160px; height: 160px; border: 5px solid #1D3557; transition: transform 0.3s, box-shadow 0.3s;" 
         onmouseover="this.style.transform='scale(1.1)'; this.style.boxShadow='0px 0px 20px rgba(0, 0, 0, 0.2)';" 
         onmouseout="this.style.transform='scale(1)'; this.style.boxShadow='none';" />
  </div>

  <h1 align="center" style="font-size: 3em; color: #1D3557; font-weight: bold;">
    <span id="typing"></span><span style="color: #E63946;">|</span> 👋
  </h1>

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

  <h3 align="center" style="color: #457B9D; font-weight: 600;">A Passionate Programmer from Pakistan</h3>      
  <hr style="border: 1px solid #A8DADC; width: 80%; margin: 20px auto;" />

  <p align="center">
    <img src="https://komarev.com/ghpvc/?username=zakiraziz&label=Profile%20views&color=1D3557&style=flat" alt="Profile Views" />
  </p>

  <div align="center">
    <a href="https://github.com/zakiraziz" 
       style="font-size: 1.3em; color: #E63946; text-decoration: none; font-weight: bold; transition: 0.3s;"
       onmouseover="this.style.color='#F77F00'"
       onmouseout="this.style.color='#E63946'">
      🔗 Explore My Projects on GitHub
    </a>
  </div>

  <h3 align="center" style="font-weight: bold; color: #1D3557;">Achievements & Certifications</h3>
  <div align="center">
    <img src="https://img.shields.io/badge/-Python%20Certified-3776AB?style=for-the-badge&logo=python&logoColor=white" style="margin: 5px;" />
    <img src="https://img.shields.io/badge/-JavaScript%20Mastery-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white" style="margin: 5px;" />
    <img src="https://img.shields.io/badge/-HTML%20CSS%20Pro-1572B6?style=for-the-badge&logo=css3&logoColor=white" style="margin: 5px;" />
  </div>

  <h3 align="center" style="font-weight: bold; color: #1D3557;">✨ Featured Projects ✨</h3>
  <div align="center">
    <a href="https://github.com/zakiraziz/some-awesome-project">
      <img src="https://img.shields.io/badge/-Awesome%20Project%201-E63946?style=for-the-badge" style="margin: 5px;" />
    </a>
    <a href="https://github.com/zakiraziz/another-cool-project">
      <img src="https://img.shields.io/badge/-Cool%20Project%202-457B9D?style=for-the-badge" style="margin: 5px;" />
    </a>
  </div>

  <h3 align="center" style="font-weight: bold; color: #1D3557;">📬 Connect with Me</h3>
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

  <footer style="text-align: center; margin-top: 40px; color: #457B9D; font-style: italic;">
    "Code is like humor. When you have to explain it, it’s bad."
  </footer>
</div>
