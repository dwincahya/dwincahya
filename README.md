<h1 align="center">
  <span id="animated-text" style="color: grey;"></span>
</h1>

<script>
  // JavaScript code for text animation
  const textArray = ["Dwi Nur Cahya", "Web Developer", "Software Engineer"];
  let currentIndex = 0;
  let letterIndex = 0;
  const typingSpeed = 100;  // Typing speed in milliseconds
  const pauseBetween = 2000;  // Pause between texts in milliseconds
  const element = document.getElementById("animated-text");

  function typeEffect() {
    if (letterIndex < textArray[currentIndex].length) {
      element.innerHTML += textArray[currentIndex].charAt(letterIndex);
      letterIndex++;
      setTimeout(typeEffect, typingSpeed);
    } else {
      setTimeout(eraseEffect, pauseBetween);
    }
  }

  function eraseEffect() {
    if (letterIndex > 0) {
      element.innerHTML = textArray[currentIndex].substring(0, letterIndex - 1);
      letterIndex--;
      setTimeout(eraseEffect, typingSpeed);
    } else {
      currentIndex = (currentIndex + 1) % textArray.length;
      setTimeout(typeEffect, typingSpeed);
    }
  }

  document.addEventListener("DOMContentLoaded", typeEffect);
</script>

### Stats Section

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=dwincahya&hide_title=false&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=dracula&locale=en&hide_border=false" height="150" alt="stats graph"  />
  <img src="https://streak-stats.demolab.com?user=dwincahya&locale=en&mode=daily&theme=dracula&hide_border=false&border_radius=5" height="150" alt="streak graph"  />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=dwincahya&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=dracula&hide_border=false" height="150" alt="languages graph"  />
</div>

### Tech Skills

<img align="right" height="130" src="https://media.tenor.com/BHaRmO7b-bMAAAAj/hsr-honkai-star-rail.gif"  />

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="30" alt="react logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="30" alt="html5 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-original-wordmark.svg" height="30" alt="tailwindcss logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="30" alt="css3 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" height="30" alt="bootstrap logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="30" alt="python logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="30" alt="typescript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" height="30" alt="nextjs logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/laravel/laravel-original.svg" height="30" alt="laravel logo"  />
</div>

### Social Links

<div align="left">
  <a href="https://www.instagram.com/dwiccah/" target="_blank">
    <img src="https://img.shields.io/static/v1?message=@dwiccah&logo=instagram&label=&color=E4405F&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="instagram logo"  />
  </a>
  <a href="mailto:dwincahya8@gmail.com" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Gmail&logo=gmail&label=&color=D14836&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="gmail logo"  />
  </a>
  <a href="https://www.linkedin.com/in/dwiccah/" target="_blank">
    <img src="https://img.shields.io/static/v1?message=dwiccah&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="linkedin logo"  />
  </a>
</div>

<br clear="both">

### Snake Animation

<img src="https://raw.githubusercontent.com/dwincahya/dwincahya/output/snake.svg" alt="Snake animation" />
