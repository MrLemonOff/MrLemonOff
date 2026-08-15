<!-- 
  Welcome to my GitHub profile README! 
  Customized with HTML, CSS styling, and interactive JavaScript elements.
-->

<div align="center">
  
  <!-- Glowing Title Header -->
  <h1 align="center" style="font-weight: 800; font-size: 2.5rem; letter-spacing: 2px;">
    👋 Hey, I'm <span class="highlight">LMN</span>
  </h1>

  <p align="center">
    <strong>Master in Programming &bull; Multi-Disciplinary Developer &bull; Creator</strong>
  </p>

  <!-- Interactive Stats Banner -->
  <p align="center">
    <img src="https://img.shields.io/badge/TikTok-150K%2B%20Followers-black?style=for-the-badge&logo=tiktok&logoColor=white" alt="TikTok Followers" />
    <img src="https://img.shields.io/badge/Discord-MrLemonOff-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" />
    <img src="https://img.shields.io/badge/Projects-700%2B-ff6b6b?style=for-the-badge&logo=git&logoColor=white" alt="Projects" />
  </p>

</div>

<hr />

<!-- CSS Styling Block -->
<style>
  :root {
    --bg-color: #0d1117;
    --card-bg: #161b22;
    --border-color: #30363d;
    --text-primary: #c9d1d9;
    --accent-color: #58a6ff;
    --highlight-color: #ff7b72;
  }

  .profile-container {
    background-color: var(--card-bg);
    border: 1px solid var(--border-color);
    border-radius: 12px;
    padding: 24px;
    margin-bottom: 20px;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
    color: var(--text-primary);
  }

  .highlight {
    color: var(--highlight-color);
  }

  .accent {
    color: var(--accent-color);
  }

  .grid-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 16px;
    margin-top: 16px;
  }

  .card {
    background: rgba(22, 27, 34, 0.6);
    border: 1px solid var(--border-color);
    border-radius: 8px;
    padding: 16px;
    transition: transform 0.2s ease, border-color 0.2s ease;
  }

  .card:hover {
    transform: translateY(-3px);
    border-color: var(--accent-color);
  }

  .lang-selector-box {
    background: #21262d;
    border: 1px solid var(--border-color);
    border-radius: 8px;
    padding: 16px;
    text-align: center;
    margin-top: 20px;
  }

  .lang-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
    justify-content: center;
    margin-top: 12px;
  }

  .lang-pill {
    background: #30363d;
    color: #c9d1d9;
    padding: 6px 12px;
    border-radius: 20px;
    font-size: 0.85rem;
    cursor: pointer;
    border: 1px solid transparent;
    transition: all 0.2s;
  }

  .lang-pill.selected {
    background: rgba(88, 166, 255, 0.15);
    border-color: var(--accent-color);
    color: var(--accent-color);
  }

  .terminal-box {
    background: #010409;
    border: 1px solid var(--border-color);
    border-radius: 6px;
    padding: 12px;
    font-family: monospace;
    font-size: 0.9rem;
    color: #7ee787;
    margin-top: 10px;
  }
</style>

<!-- About Section -->
<div class="profile-container">
  <h2>🚀 About Me</h2>
  <p>
    I am <strong>LMN</strong>, a master in programming with an extensive background spanning over <strong>700 projects</strong> across diverse technical fields. Whether it's deep system architecture, full-stack applications, game development, or scripting, I live and breathe code.
  </p>
  <p>
    Outside of coding, I create content and build communities with an audience of over <strong>150K followers</strong> on TikTok (<a href="https://www.tiktok.com/@MrLemonOff" target="_blank">@MrLemonOff</a>).
  </p>
</div>

<!-- Dynamic Language Hub (Interactive Component) -->
<div class="profile-container">
  <h2>💻 Programming Ecosystem (100+ Languages Mastered)</h2>
  <p><em>Click on the language pills below to toggle them based on your exact stack fit:</em></p>
  
  <div class="lang-selector-box">
    <strong>Toggle Languages in My Stack:</strong>
    <div class="lang-grid" id="languagePills">
      <!-- Generated via JS below -->
    </div>
    <div class="terminal-box" id="stackOutput">
      Active Stack Count: 100+ Languages Loaded
    </div>
  </div>
</div>

<!-- Fields & Projects Section -->
<div class="profile-container">
  <h2>🌐 700+ Projects Across Fields</h2>
  <div class="grid-container">
    <div class="card">
      <h3>🎮 Game Development</h3>
      <p>Building immersive mechanics, custom engines, scripts, and high-performance gameplay structures.</p>
    </div>
    <div class="card">
      <h3>⚡ Full-Stack & Web</h3>
      <p>Developing lightning-fast frontends, robust backends, and scalable distributed architectures.</p>
    </div>
    <div class="card">
      <h3>🤖 Automation & Systems</h3>
      <p>Creating custom bots, automation tools, web scrapers, and complex backend utilities.</p>
    </div>
  </div>
</div>

<!-- Connect Section -->
<div class="profile-container" align="center">
  <h2>📬 Connect With Me</h2>
  <p>Let's build something epic together or talk tech!</p>
  <p>
    <a href="https://www.tiktok.com/@MrLemonOff" target="_blank">
      <img src="https://img.shields.io/badge/TikTok-%40MrLemonOff-000000?style=for-the-badge&logo=tiktok&logoColor=white" alt="TikTok" />
    </a>
    <a href="https://discord.com/users/MrLemonOff" target="_blank">
      <img src="https://img.shields.io/badge/Discord-MrLemonOff-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" />
    </a>
  </p>
</div>

<!-- GitHub Stats & Trophies -->
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=MrLemonOff&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub Stats" />
  <br><br>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=MrLemonOff&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</div>

<!-- Interactive JavaScript Engine -->
<script>
  // Comprehensive list of 100+ popular and specialized programming languages
  const allLanguages = [
    "Python", "JavaScript", "TypeScript", "C", "C++", "C#", "Java", "Go", "Rust", "PHP",
    "Ruby", "Swift", "Kotlin", "HTML5", "CSS3", "SQL", "Shell", "Bash", "Assembly", "Lua",
    "Perl", "R", "Scala", "Dart", "Haskell", "Elixir", "Clojure", "Erlang", "Objective-C", "Matlab",
    "Groovy", "TypeScript", "Solidity", "Vyper", "ActionScript", "Ada", "Algol", "Apex", "Arduino", "AWK",
    "B4X", "Batch", "Boo", "Brainfuck", "Chapel", "Cirru", "Clarion", "Clean", "COBOL", "CoffeeScript",
    "Common Lisp", "Crystal", "CUDA", "Curry", "D", "Dart", "Delphi", "Eiffel", "Elm", "Emacs Lisp",
    "Factor", "Fancy", "Fantom", "Forth", "Fortran", "FreeBasic", "F#", "GameMaker Language", "GAMS", "GDScript",
    "Gnuplot", "Go", "Gosu", "Groovy", "Hack", "Harbour", "Haxe", "Idris", "Io", "J",
    "JADE", "Julia", "Jupyter Notebook", "LabVIEW", "Lasso", "Lean", "LiveScript", "Logtalk", "LOLCODE", "LookML",
    "LSL", "Mathematica", "Matlab", "Max", "Mercury", "Metal", "Mirah", "Modula-2", "Modula-3", "Monkey",
    "MoonScript", "Nemerle", "NetLogo", "Nim", "Nix", "Nu", "Ocaml", "Opal", "OpenEdge ABL", "Oz",
    "Pascal", "Pawn", "PHP", "PigLatin", "Pike", "PL/SQL", "PostScript", "PowerShell", "Prolog", "PureScript",
    "Python", "QML", "R", "Racket", "Raku", "Reason", "Rebol", "Red", "Rexx", "Ring",
    "RobotFramework", "RPG", "Ruby", "Rust", "SAS", "Scala", "Scheme", "Scratch", "Sed", "Self",
    "Shell", "Simula", "Slash", "Smalltalk", "Smarty", "SMT", "Snobol", "Solidity", "SourcePawn", "SQF"
  ];

  const pillContainer = document.getElementById("languagePills");
  const stackOutput = document.getElementById("stackOutput");
  
  // Keep track of active languages (default all selected, click to toggle off)
  let activeLangs = new Set(allLanguages);

  function renderPills() {
    pillContainer.innerHTML = "";
    allLanguages.forEach(lang => {
      const pill = document.createElement("span");
      pill.className = "lang-pill selected";
      pill.innerText = lang;
      pill.onclick = () => {
        if (activeLangs.has(lang)) {
          activeLangs.delete(lang);
          pill.classList.remove("selected");
        } else {
          activeLangs.add(lang);
          pill.classList.add("selected");
        }
        stackOutput.innerText = `Active Stack: ${activeLangs.size} languages selected.`;
      };
      pillContainer.appendChild(pill);
    });
  }

  renderPills();
</script>
