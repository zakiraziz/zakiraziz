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
