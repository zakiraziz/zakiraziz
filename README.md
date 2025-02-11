<div style="background-color: #F1FAEE; padding: 20px; border-radius: 15px; box-shadow: 0px 4px 15px rgba(0, 0, 0, 0.1);">
  <div style="text-align: center; margin-bottom: 20px;">
    <img src="https://files.oaiusercontent.com/file-CkNvebYhfEJWe7EpdPMDVR?se=2025-02-11T15%3A49%3A24Z&sp=r&sv=2024-08-04&sr=b&rscc=max-age%3D604800%2C%20immutable%2C%20private&rscd=attachment%3B%20filename%3D7fc38e23-9f9f-4631-926b-f689f1005ed3.webp&sig=OlESCr/yPcyi0TfVFcQMa0wMAlIePUuZzDWZcacVssY%3D" alt="Banner Image 1" style="width: 100%; border-radius: 10px; margin-bottom: 15px;" />
    <img src="https://via.placeholder.com/150" alt="Profile Picture" 
         style="border-radius: 50%; width: 150px; height: 150px; border: 3px solid #1D3557;" />
    <img src="https://files.oaiusercontent.com/file-PvLxFhXGuxUPFwVocyaB1U?se=2025-02-11T15%3A50%3A18Z&sp=r&sv=2024-08-04&sr=b&rscc=max-age%3D604800%2C%20immutable%2C%20private&rscd=attachment%3B%20filename%3Dd0638351-7fec-4455-b58e-48a281349a91.webp&sig=owBb/i%2BlC4Ds4zk%2B7HAwIplzC0TXjBbAcS8pxAvuxsU%3D" alt="Banner Image 2" style="width: 100%; border-radius: 10px; margin-top: 15px;" />
  </div>

  <h1 align="center" style="font-size: 3em; color: #1D3557; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; margin: 0;">
    <span id="typing"></span> 👋
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

  <h3 align="center" style="font-weight: 400; color: #457B9D; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; margin-top: 10px;">
    A Passionate Programmer from Pakistan
  </h3>      

  <p align="center" style="margin: 20px 0;">
    <img src="https://komarev.com/ghpvc/?username=zakiraziz&label=Profile%20views&color=1D3557&style=flat" alt="Profile Views" />
  </p>

  <div align="center" style="margin-bottom: 30px;">
    <a href="https://github.com/zakiraziz" 
       style="font-size: 1.2em; color: #E63946; text-decoration: none; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; font-weight: bold; transition: 0.3s;">
      🔗 Explore My Projects on GitHub
    </a>
  </div>

  <h3 align="center" style="font-weight: bold; color: #1D3557;">Achievements & Certifications</h3>
  <div align="center" style="margin: 20px;">
    <img src="https://img.shields.io/badge/-Python%20Certified-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python Certification" style="margin: 5px;" />
    <img src="https://img.shields.io/badge/-JavaScript%20Mastery-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white" alt="JavaScript Certification" style="margin: 5px;" />
    <img src="https://img.shields.io/badge/-HTML%20CSS%20Pro-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="HTML CSS Badge" style="margin: 5px;" />
  </div>

  <h3 align="center" style="font-weight: bold; color: #1D3557;">✨ Highlights ✨</h3>
  <div align="center" style="margin: 20px;">
    <a href="https://github.com/zakiraziz/some-awesome-project" style="text-decoration: none;">
      <img src="https://img.shields.io/badge/-Some%20Awesome%20Project%201-E63946?style=for-the-badge" alt="Project Badge 1" style="margin: 5px;" />
    </a>
    <a href="https://github.com/zakiraziz/another-cool-project" style="text-decoration: none;">
      <img src="https://img.shields.io/badge/-Another%20Cool%20Project%202-457B9D?style=for-the-badge" alt="Project Badge 2" style="margin: 5px;" />
    </a>
  </div>

  <footer style="text-align: center; margin-top: 40px; color: #457B9D; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">
    <em>"Code is like humor. When you have to explain it, it’s bad."</em>
  </footer>
</div>
