<style>
  html, body {
    background-color:rgb(29, 30, 31);
    margin: 0;
    padding: 0;
    width: 100%;
    height: 50vh;
    overflow: hidden;
    position: fixed;
  }
  
  .line {
    border-top: 1px dashed #60a5fa;
    width: 100%;
    margin: 50px 0 0 0;
    padding: 0;
  }
  
  .line-bottom {
    border-bottom: 1px dashed #60a5fa;
    width: 100%;
    position: fixed;
    bottom: 410px;
    left: 0;
    padding: 0;
  }
  
  .line-left {
    border-left: 1px dashed #60a5fa;
    height: 50vh;
    position: fixed;
    left: 20px;
    top: 0;
    padding: 0;
  }
  
  .line-right {
    border-right: 1px dashed #60a5fa;
    height: 50vh;
    position: fixed;
    right: 20px;
    top: 0;
    padding: 0;
  }
  
  .corner-square {
    width: 8px;
    height: 8px;
    background-color: #60a5fa;
    position: fixed;
  }
  
  .name {
    font-family: "SupplyMono", monospace;
    color:rgb(255, 255, 255);
    position: fixed;
    left: 40px;
    top: 25px;
    transform: translateY(-50%);
    font-size: 20px;
    letter-spacing: 0.5px;
  }
  
  .contact-buttons {
    position: fixed;
    right: 40px;
    top: 25px;
    transform: translateY(-50%);
    display: flex;
    gap: 8px;
  }
  
  .contact-button {
    background-color: white;
    color:rgb(12, 48, 93);
    font-family: "SupplyMono", monospace;
    font-size: 11px;
    letter-spacing: 0.5px;
    padding: 6px 12px;
    text-decoration: none;
    transition: all 0.3s;
    border: none;
  }
  
  .contact-button:hover {
    background-color: #60a5fa;
    color: white;
  }
  
  .corner-top-left {
    left: 20px;
    top: 50px;
    transform: translate(-50%, -50%);
  }
  
  .corner-top-right {
    right: 20px;
    top: 50px;
    transform: translate(50%, -50%);
  }
  
  .corner-bottom-left {
    left: 20px;
    bottom: 410px;
    transform: translate(-50%, 50%);
  }
  
  .corner-bottom-right {
    right: 20px;
    bottom: 410px;
    transform: translate(50%, 50%);
  }
  
  .currently-listening {
    position: fixed;
    right: 50px;
    top: 250px;
    border: 1px dashed #60a5fa;
    padding: 8px;
    font-family: "SupplyMono", monospace;
    color: rgb(255, 255, 255);
    font-size: 10px;
    letter-spacing: 0.5px;
    width: auto;
    min-width: 200px;
    display: flex;
    flex-direction: row;
    align-items: center;
    gap: 10px;
  }
  
  .currently-listening-content {
    display: flex;
    flex-direction: column;
    gap: 1px;
    flex: 1;
  }
  
  .currently-listening-image {
    width: 50px;
    height: 50px;
    object-fit: cover;
    border-radius: 2px;
  }
  
  .currently-listening-label {
    font-size: 12px;
    color: rgba(255, 255, 255, 0.7);
    text-transform: uppercase;
  }
  
  .song-title {
    font-size: 12px;
    color: rgb(255, 255, 255);
  }
  
  .artist-name {
    font-size: 12px;
    color: rgba(255, 255, 255, 0.8);
  }
  
  .bio {
    position: fixed;
    left: 40px;
    top: 80px;
    font-family: "SupplyMono", monospace;
    color: rgba(255, 255, 255, 0.9);
    font-size: 14px;
    line-height: 1.2;
    max-width: 600px;
  }
  
  .bio-line {
    margin-bottom: 8px;
  }
  
  .bio a {
    color: #60a5fa;
    text-decoration: none;
    transition: color 0.3s;
    border-bottom: 1px dotted #60a5fa;
  }
  
  .bio a:hover {
    color: #93c5fd;
    border-bottom: 1px solid #93c5fd;
  }
  
  .birthday-play {
    margin-top: 10px;
    font-size: 12px;
    color:rgb(202, 226, 255);
    font-family: "SupplyMono", monospace;
    letter-spacing: 0.5px;
    line-height: 1;
  }
  
  .birthday-play-line {
    margin-bottom: 8px;
  }
  
  .tech-stack {
    margin-top: 10px;
    font-size: 14px;
    color: rgba(255, 255, 255, 0.9);
    font-family: "SupplyMono", monospace;
    line-height: 1.2;
  }
  
  .tech-stack-line {
    margin-bottom: 6px;
  }
  
  .tech-label {
    color:rgb(202, 226, 255);
  }
  
  .bio-ascii {
    position: fixed;
    right: -55px;
    top: 70px;
    font-family: "SupplyMono", monospace;
    font-size: 8px;
    line-height: 1.1;
    color: #60a5fa;
    white-space: pre;
    letter-spacing: 0;
  }
</style>

<div class="line"></div>
<div class="line-1"></div>
<div class="line-2"></div>
<div class="line-bottom"></div>
<div class="line-left"></div>
<div class="line-right"></div>
<div class="name">Pooja Kanala ⋆𐙚₊˚⊹♡</div>
<div class="contact-buttons">
  <a href="mailto:your.pk2921@nyu.edu" class="contact-button">EMAIL</a>
  <a href="https://www.linkedin.com/in/pooja-kanala/" class="contact-button">LINKEDIN</a>
</div>
  <div class="bio-ascii">⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢠⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⣧⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣿⣷⣄⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⡔⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠭⣿⣿⣿⣶⣄⣀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣀⣴⣾⡿⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠘⡿⣿⡿⣿⣿⣿⣿⣦⣴⣶⣶⣶⣶⣦⣤⣤⣀⣀⠀⠀⠀⠀⠀⢀⣀⣤⣲⣿⣿⣿⠟⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠐⡝⢿⣌⠿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⣶⣤⣾⣿⣿⣿⣿⣿⡿⠃⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠲⡝⡷⣮⣝⣻⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣛⣿⣿⠿⠃⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣴⣿⣦⣝⠓⠭⣿⡿⢿⣿⣿⣛⠻⣿⠿⠿⣿⣿⣿⣿⣿⣿⡿⣇⣇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣴⣿⣿⣿⣿⣿⣿⣤⡀⠈⠉⠚⠺⣿⠯⢽⣿⣷⣄⣶⣷⢾⣿⣯⣾⣿⠿⠃⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢠⣾⣿⣿⣿⣿⣿⣿⣿⣿⣧⠀⠀⠀⠀⡟⠀⠀⣴⣿⣿⣼⠈⠉⠃⠋⢹⠁⢀⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢠⢿⣿⡟⣿⣿⣿⣿⣿⣿⣿⣿⣷⣄⣀⣀⣀⣀⣴⣿⣿⡿⣿⠀⠀⠀⠀⠇⠀⣼⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠑⢿⢿⣾⣿⣿⡿⠿⠿⠿⢿⣿⣿⣿⣿⣿⣿⣿⣿⠟⠿⢿⡄⢦⣤⣤⣶⣿⣿⣷⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠙⠘⠛⠋⠁⠁⣀⢉⡉⢻⡻⣯⣻⣿⢻⣿⣀⠀⠀⠀⢠⣾⣿⣿⣿⣹⠉⣍⢁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣀⠠⠔⠒⠋⠀⡈⠀⠠⠤⠀⠓⠯⣟⣻⣻⠿⠛⠁⠀⠀⠣⢽⣿⡻⠿⠋⠰⠤⣀⡈⠒⢄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡀⠔⠊⠁⠀⣀⠔⠈⠁⠀⠀⠀⠀⠀⣶⠂⠀⠀⠀⢰⠆⠀⠀⠀⠈⠒⢦⡀⠉⠢⠀⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠊⠀⠀⠀⠀⠎⠁⠀⠀⠀⠀⠀⠀⠀⠀⠋⠀⠀⠀⠰⠃⠀⠀⠀⠀⠀⠀⠀⠈⠂⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣸⣄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀</div>
  <div class="bio">
    <div class="bio-line">Building at the intersection  of AI and Finance.</div>
    <div class="bio-line">Currently @NYU, teaching machines to understand money.</div>
    <div class="birthday-play">
      <div class="birthday-play-line">> Born of 4 dimensions and 14 layers [04.14.2003]</div>
      <div class="birthday-play-line">> Named with the 4th protocol² </div>
      <div class="birthday-play-line">> Optimizing the algorithm 0→1</div>
    </div>
    <div class="bio-line">Learning what algorithms <a href="https://www.youtube.com/watch?v=jG7dSXcfVqE" target="_blank">can't</a> compute.</div>
    <div class="bio-line">ʚ(｡˃ ᵕ ˂ )ɞ ────୨ৎ──── (*ᴗ͈ˬᴗ͈)ꕤ*.ﾟ</div>
    <div class="tech-stack">
      <div class="tech-stack-line"><span class="tech-label">Stack:</span> C++ | Python | Rust | PyTorch | CUDA</div>
      <div class="tech-stack-line"><span class="tech-label">Systems:</span> Linux | NumPy | Kafka</div>
    </div>
    <div class="bio-line">Recently released <a href="https://pypi.org/project/langchain-financial/" target="_blank">langchain-financial</a> on PyPI.</div>
    <div class="bio-line">Published in <a href="https://ieeexplore.ieee.org/document/10816924" target="_blank">IEEE</a>.</div>
  </div>
<div class="corner-square corner-top-left"></div>
<div class="corner-square corner-top-right"></div>
<div class="corner-square corner-bottom-left"></div>
<div class="corner-square corner-bottom-right"></div>
<div class="currently-listening">
  <div class="currently-listening-content">
    <div class="currently-listening-label">currently  </div>
    <div class="song-title"><a href="https://www.goodreads.com/book/show/24724602-flash-boys" target="_blank" style="color: rgb(255, 255, 255); text-decoration: none; border-bottom: 1px dotted #60a5fa;">Flash Boys</a></div>
    <div class="artist-name">Michael Lewis</div>
  </div>
  <img src="image.jpeg" alt="Michael Lewis" class="currently-listening-image">
</div>

