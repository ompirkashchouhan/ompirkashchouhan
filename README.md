<!-- Typing + Changing Text (Pure SVG, no JS) -->
<p align="center">
  <svg width="600" height="80" viewBox="0 0 600 80" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Typing animation">
    <!-- Background (optional) -->
    <rect x="0" y="0" width="600" height="80" rx="12" fill="#0d1117"/>
    
    <!-- Title (optional) -->
    <text x="300" y="24" text-anchor="middle" font-family="Inter, Segoe UI, Roboto, Arial, sans-serif" font-size="14" fill="#9da7b3">
      Welcome to my GitHub
    </text>

    <!-- Phrase 1 -->
    <defs>
      <clipPath id="clip1">
        <rect x="120" y="36" width="0" height="30">
          <!-- Type -->
          <animate attributeName="width" values="0;420" dur="2s" begin="0s;erase3.end+0.5s" fill="freeze"/>
          <!-- Hold -->
          <animate attributeName="width" values="420;420" dur="0.7s" begin="type1.end" fill="freeze" id="hold1"/>
          <!-- Erase -->
          <animate attributeName="width" values="420;0" dur="0.3s" begin="hold1.end" fill="freeze" id="erase1"/>
        </rect>
      </clipPath>
    </defs>
    <text x="120" y="58" font-family="Fira Code, Menlo, Consolas, monospace" font-size="22" fill="#e6edf3" clip-path="url(#clip1)">
      Hi, I'm Ompirkash — Frontend Web Developer.
    </text>
    <!-- Cursor 1 -->
    <rect x="120" y="36" width="2" height="30" fill="#58a6ff">
      <animate attributeName="x" values="120;540" dur="2s" begin="0s;erase3.end+0.5s" fill="freeze" id="type1"/>
      <animate attributeName="opacity" values="1;0;1;0;1" dur="0.8s" repeatCount="indefinite" begin="0s"/>
      <animate attributeName="x" values="540;120" dur="0.3s" begin="hold1.end" fill="freeze"/>
    </rect>

    <!-- Phrase 2 -->
    <defs>
      <clipPath id="clip2">
        <rect x="120" y="36" width="0" height="30">
          <animate attributeName="width" values="0;420" dur="2s" begin="erase1.end+0.2s" fill="freeze"/>
          <animate attributeName="width" values="420;420" dur="0.7s" begin="type2.end" fill="freeze" id="hold2"/>
          <animate attributeName="width" values="420;0" dur="0.3s" begin="hold2.end" fill="freeze" id="erase2"/>
        </rect>
      </clipPath>
    </defs>
    <text x="120" y="58" font-family="Fira Code, Menlo, Consolas, monospace" font-size="22" fill="#e6edf3" clip-path="url(#clip2)">
      I build clean UI with React & Next.js.
    </text>
    <!-- Cursor 2 -->
    <rect x="120" y="36" width="2" height="30" fill="#58a6ff">
      <animate attributeName="x" values="120;540" dur="2s" begin="erase1.end+0.2s" fill="freeze" id="type2"/>
      <animate attributeName="opacity" values="1;0;1;0;1" dur="0.8s" repeatCount="indefinite" begin="0s"/>
      <animate attributeName="x" values="540;120" dur="0.3s" begin="hold2.end" fill="freeze"/>
    </rect>

    <!-- Phrase 3 -->
    <defs>
      <clipPath id="clip3">
        <rect x="120" y="36" width="0" height="30">
          <animate attributeName="width" values="0;420" dur="2s" begin="erase2.end+0.2s" fill="freeze"/>
          <animate attributeName="width" values="420;420" dur="0.7s" begin="type3.end" fill="freeze" id="hold3"/>
          <animate attributeName="width" values="420;0" dur="0.3s" begin="hold3.end" fill="freeze" id="erase3"/>
        </rect>
      </clipPath>
    </defs>
    <text x="120" y="58" font-family="Fira Code, Menlo, Consolas, monospace" font-size="22" fill="#e6edf3" clip-path="url(#clip3)">
      Performance-focused, pixel-perfect, responsive.
    </text>
    <!-- Cursor 3 -->
    <rect x="120" y="36" width="2" height="30" fill="#58a6ff">
      <animate attributeName="x" values="120;540" dur="2s" begin="erase2.end+0.2s" fill="freeze" id="type3"/>
      <animate attributeName="opacity" values="1;0;1;0;1" dur="0.8s" repeatCount="indefinite" begin="0s"/>
      <animate attributeName="x" values="540;120" dur="0.3s" begin="hold3.end" fill="freeze"/>
    </rect>

    <!-- Subtext -->
    <text x="300" y="74" text-anchor="middle" font-family="Inter, Segoe UI, Roboto, Arial, sans-serif" font-size="12" fill="#9da7b3">
      HTML • CSS • JavaScript • React • Next.js
    </text>
  </svg>
</p>



<h3 align="center">A passionate Frontend Developer from Pakistan 🇵🇰</h3>

<!-- Coding GIF -->
<img align="right" alt="Coding" width="360" src="https://user-images.githubusercontent.com/74038190/212749447-bfb7e725-6987-49d9-ae85-2015e3e7cc41.gif"/>

---------------------------

### 🌟 About Me
Welcome to my GitHub profile. I'm a passionate **Front-end Web Developer** from Pakistan . 

- 🌍 **Location:** Pakistan, Mithi Tharparkar.
- 💻 **Expertise:** HTML, CSS, Bootstrap, JavaScript, Firebase, React.js, Next.js, Supabase, Git, Api-Integration.
- 🎨 **UI Libraries:** Bootstrap, Tailwind CSS, Material UI.

---

### 🔗 Connect With Me
<p align="left">
  <a href="https://www.linkedin.com/in/ompirkash-chouhan-a1683b273/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://web.facebook.com/om.pirkash.5855" target="_blank">
    <img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white"/>
  </a>
</p>

---

### 🚀 Languages & Tools
<p align="left">
  <!-- Core -->
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"/>
  
  <!-- Styling -->
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white"/>
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white"/>

  <!-- Backend / Database -->
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black"/>
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white"/>

  <!-- Tools -->
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
</p>
<h5 align="center">❤️🙏 Thanks for reading the readme. 🙏❤️</h5>
