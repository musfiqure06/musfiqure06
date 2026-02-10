<div align="center">

<!-- Matrix Background Effect -->
<div id="matrix-bg" style="position: fixed; top: 0; left: 0; width: 100%; height: 100%; z-index: -1; pointer-events: none;"></div>

<!-- Main Container with Glowing Border -->
<div style="
  position: relative;
  padding: 40px;
  margin: 20px;
  border-radius: 30px;
  background: rgba(10, 10, 26, 0.9);
  border: 2px solid transparent;
  background-clip: padding-box;
  box-shadow: 
    0 0 50px rgba(0, 212, 255, 0.3),
    0 0 100px rgba(0, 255, 170, 0.2),
    0 0 150px rgba(138, 43, 226, 0.1);
  animation: border-glow 6s infinite alternate;
">

<!-- Animated Name with Glitch Effect -->
<h1 align="center" style="margin-bottom: 30px;">
  <span id="glitch-name" style="
    font-family: 'Orbitron', sans-serif;
    font-weight: 900;
    font-size: 3.5rem;
    background: linear-gradient(45deg, 
      #00D4FF 0%, 
      #00FFAA 25%, 
      #8A2BE2 50%, 
      #FF6B6B 75%, 
      #00D4FF 100%);
    background-size: 400% 400%;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    animation: gradient-move 8s ease infinite, glitch-effect 5s infinite;
    display: inline-block;
    padding: 20px;
    text-shadow: 
      0 0 20px rgba(0, 212, 255, 0.5),
      0 0 40px rgba(0, 255, 170, 0.3);
  ">MD. MUSFIQUE RAHMAN KOUSHIK</span>
</h1>

<!-- Animated Title -->
<h2 align="center" style="margin-bottom: 40px;">
  <span style="
    font-family: 'Orbitron', sans-serif;
    font-size: 2.2rem;
    background: linear-gradient(90deg, #FF6B6B, #00D4FF);
    -webkit-background-clip: text;
    background-clip: text;
    color: transparent;
    padding: 15px 30px;
    border: 2px solid #00D4FF;
    border-radius: 15px;
    display: inline-block;
    animation: title-pulse 3s infinite, float 6s ease-in-out infinite;
    box-shadow: 0 0 30px rgba(0, 212, 255, 0.4);
  ">⚡ FULL STACK QUANTUM DEVELOPER ⚡</span>
</h2>

<!-- Status Grid -->
<div style="
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 25px;
  margin: 40px 0;
  padding: 20px;
">

<div style="
  background: rgba(0, 212, 255, 0.1);
  border: 1px solid #00D4FF;
  border-radius: 15px;
  padding: 25px;
  text-align: center;
  backdrop-filter: blur(10px);
  animation: card-float 4s ease-in-out infinite;
  position: relative;
  overflow: hidden;
">
  <div style="font-size: 2.5rem; margin-bottom: 10px; animation: spin 10s linear infinite;">⚡</div>
  <h3 style="color: #00D4FF;">STATUS</h3>
  <p style="color: #00FFAA; font-weight: bold; font-size: 1.2rem;">ACTIVE & BUILDING</p>
</div>

<div style="
  background: rgba(138, 43, 226, 0.1);
  border: 1px solid #8A2BE2;
  border-radius: 15px;
  padding: 25px;
  text-align: center;
  backdrop-filter: blur(10px);
  animation: card-float 4s ease-in-out infinite 0.5s;
">
  <div style="font-size: 2.5rem; margin-bottom: 10px; animation: bounce 2s infinite;">📍</div>
  <h3 style="color: #8A2BE2;">LOCATION</h3>
  <p style="color: #00D4FF; font-weight: bold; font-size: 1.2rem;">DHAKA, BANGLADESH</p>
</div>

<div style="
  background: rgba(255, 107, 107, 0.1);
  border: 1px solid #FF6B6B;
  border-radius: 15px;
  padding: 25px;
  text-align: center;
  backdrop-filter: blur(10px);
  animation: card-float 4s ease-in-out infinite 1s;
">
  <div style="font-size: 2.5rem; margin-bottom: 10px; animation: pulse 2s infinite;">💼</div>
  <h3 style="color: #FF6B6B;">AVAILABILITY</h3>
  <p style="color: #FF6B6B; font-weight: bold; font-size: 1.2rem;">IMMEDIATE HIRE</p>
</div>

<div style="
  background: rgba(0, 255, 170, 0.1);
  border: 1px solid #00FFAA;
  border-radius: 15px;
  padding: 25px;
  text-align: center;
  backdrop-filter: blur(10px);
  animation: card-float 4s ease-in-out infinite 1.5s;
">
  <div style="font-size: 2.5rem; margin-bottom: 10px; animation: glow 2s infinite;">🎯</div>
  <h3 style="color: #00FFAA;">FOCUS</h3>
  <p style="color: #00FFAA; font-weight: bold; font-size: 1.2rem;">AI INTEGRATION</p>
</div>

</div>

<!-- GitHub Stats -->
<h2 style="
  color: #00D4FF;
  font-family: 'Orbitron', sans-serif;
  font-size: 2.5rem;
  margin: 60px 0 30px 0;
  text-align: center;
  animation: text-glow 3s infinite alternate;
">📊 GITHUB QUANTUM STATS</h2>

<div style="
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 30px;
  margin: 40px 0;
  padding: 20px;
">

<!-- Stats Card 1 -->
<div style="
  background: linear-gradient(135deg, rgba(0, 212, 255, 0.2), rgba(0, 255, 170, 0.2));
  border-radius: 20px;
  padding: 30px;
  border: 2px solid #00D4FF;
  animation: card-glow 3s infinite;
">
  <h3 style="color: white; margin-bottom: 20px; text-align: center;">⚡ ACTIVITY METRICS</h3>
  <div style="
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 20px;
    text-align: center;
  ">
    <div>
      <div class="counter" data-target="150" style="font-size: 2.5rem; font-weight: 900; color: #00FFAA;">0</div>
      <div style="color: #ccc;">Repositories</div>
    </div>
    <div>
      <div class="counter" data-target="2500" style="font-size: 2.5rem; font-weight: 900; color: #00D4FF;">0</div>
      <div style="color: #ccc;">Commits</div>
    </div>
    <div>
      <div class="counter" data-target="50" style="font-size: 2.5rem; font-weight: 900; color: #8A2BE2;">0</div>
      <div style="color: #ccc;">Projects</div>
    </div>
    <div>
      <div class="counter" data-target="98" style="font-size: 2.5rem; font-weight: 900; color: #FF6B6B;">0</div>
      <div style="color: #ccc;">% Active</div>
    </div>
  </div>
</div>

<!-- Stats Card 2 -->
<div style="
  background: linear-gradient(135deg, rgba(138, 43, 226, 0.2), rgba(255, 107, 107, 0.2));
  border-radius: 20px;
  padding: 30px;
  border: 2px solid #8A2BE2;
  animation: card-glow 3s infinite 1s;
">
  <h3 style="color: white; margin-bottom: 20px; text-align: center;">🚀 PERFORMANCE</h3>
  <img src="https://github-readme-stats.vercel.app/api?username=musfiqurekoushik&show_icons=true&theme=radical&hide_border=true&bg_color=0d1117&title_color=00D4FF&icon_color=00FFAA&text_color=ffffff&include_all_commits=true" 
       alt="GitHub Stats" 
       style="width: 100%; border-radius: 10px; animation: stats-float 5s ease-in-out infinite;" />
</div>

</div>

<!-- Tech Stack -->
<h2 style="
  color: #00FFAA;
  font-family: 'Orbitron', sans-serif;
  font-size: 2.5rem;
  margin: 60px 0 30px 0;
  text-align: center;
  animation: text-glow 3s infinite alternate;
">🚀 TECH SUPERPOWERS</h2>

<!-- Frontend -->
<div style="
  background: rgba(0, 212, 255, 0.1);
  border-radius: 15px;
  padding: 30px;
  margin: 20px 0;
  border: 2px solid #00D4FF;
  animation: pulse-border 3s infinite;
">
  <h3 style="color: #00D4FF; margin-bottom: 20px; text-align: center;">🖥️ FRONTEND UNIVERSE</h3>
  <div style="display: flex; flex-wrap: wrap; gap: 15px; justify-content: center;">
    <span class="tech-tag" style="background: #61DAFB; animation-delay: 0s;">React 18</span>
    <span class="tech-tag" style="background: #000000; animation-delay: 0.2s;">Next.js 14</span>
    <span class="tech-tag" style="background: #007ACC; animation-delay: 0.4s;">TypeScript</span>
    <span class="tech-tag" style="background: #06B6D4; animation-delay: 0.6s;">TailwindCSS</span>
    <span class="tech-tag" style="background: #000000; animation-delay: 0.8s;">Three.js</span>
  </div>
</div>

<!-- Backend -->
<div style="
  background: rgba(0, 255, 170, 0.1);
  border-radius: 15px;
  padding: 30px;
  margin: 20px 0;
  border: 2px solid #00FFAA;
  animation: pulse-border 3s infinite 1s;
">
  <h3 style="color: #00FFAA; margin-bottom: 20px; text-align: center;">⚙️ BACKEND GALAXY</h3>
  <div style="display: flex; flex-wrap: wrap; gap: 15px; justify-content: center;">
    <span class="tech-tag" style="background: #339933; animation-delay: 1s;">Node.js</span>
    <span class="tech-tag" style="background: #000000; animation-delay: 1.2s;">Express</span>
    <span class="tech-tag" style="background: #47A248; animation-delay: 1.4s;">MongoDB</span>
    <span class="tech-tag" style="background: #D62828; animation-delay: 1.6s;">Redis</span>
    <span class="tech-tag" style="background: #3776AB; animation-delay: 1.8s;">Python</span>
  </div>
</div>

<!-- AI/ML -->
<div style="
  background: rgba(138, 43, 226, 0.1);
  border-radius: 15px;
  padding: 30px;
  margin: 20px 0;
  border: 2px solid #8A2BE2;
  animation: pulse-border 3s infinite 2s;
">
  <h3 style="color: #8A2BE2; margin-bottom: 20px; text-align: center;">🤖 AI & ML COSMOS</h3>
  <div style="display: flex; flex-wrap: wrap; gap: 15px; justify-content: center;">
    <span class="tech-tag" style="background: #FF6F00; animation-delay: 2s;">TensorFlow</span>
    <span class="tech-tag" style="background: #412991; animation-delay: 2.2s;">OpenAI API</span>
    <span class="tech-tag" style="background: #00A67E; animation-delay: 2.4s;">LangChain</span>
    <span class="tech-tag" style="background: #EE4C2C; animation-delay: 2.6s;">PyTorch</span>
  </div>
</div>

<!-- Current Projects -->
<h2 style="
  color: #FF6B6B;
  font-family: 'Orbitron', sans-serif;
  font-size: 2.5rem;
  margin: 60px 0 30px 0;
  text-align: center;
  animation: text-glow 3s infinite alternate;
">🚀 CURRENT MISSIONS</h2>

<div style="
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 30px;
  margin: 40px 0;
  padding: 20px;
">

<!-- Project 1 -->
<div class="project-card" style="
  background: rgba(0, 0, 0, 0.5);
  border-radius: 20px;
  padding: 30px;
  border: 2px solid #00D4FF;
  position: relative;
  overflow: hidden;
  animation: project-glow 4s infinite;
">
  <div class="project-glow" style="
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: radial-gradient(circle at center, rgba(0, 212, 255, 0.1), transparent 70%);
    opacity: 0.5;
  "></div>
  <h3 style="color: #00D4FF; margin-bottom: 15px;">🧠 Learn With Musfiq AI</h3>
  <p style="color: #ccc; margin-bottom: 20px;">AI-powered educational platform with personalized learning paths and real-time analytics</p>
  <div style="display: flex; gap: 10px; margin-bottom: 20px; flex-wrap: wrap;">
    <span style="padding: 5px 15px; background: rgba(0, 212, 255, 0.2); border-radius: 15px; font-size: 0.9rem;">Next.js</span>
    <span style="padding: 5px 15px; background: rgba(0, 255, 170, 0.2); border-radius: 15px; font-size: 0.9rem;">OpenAI</span>
    <span style="padding: 5px 15px; background: rgba(138, 43, 226, 0.2); border-radius: 15px; font-size: 0.9rem;">LangChain</span>
  </div>
  <div style="display: flex; align-items: center; color: #00FFAA;">
    <div style="width: 10px; height: 10px; background: #00FFAA; border-radius: 50%; margin-right: 10px; animation: blink 1s infinite;"></div>
    <span>IN PROGRESS</span>
  </div>
</div>

<!-- Project 2 -->
<div class="project-card" style="
  background: rgba(0, 0, 0, 0.5);
  border-radius: 20px;
  padding: 30px;
  border: 2px solid #8A2BE2;
  position: relative;
  overflow: hidden;
  animation: project-glow 4s infinite 2s;
">
  <div class="project-glow" style="
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: radial-gradient(circle at center, rgba(138, 43, 226, 0.1), transparent 70%);
    opacity: 0.5;
  "></div>
  <h3 style="color: #8A2BE2; margin-bottom: 15px;">🔗 Quantum Portfolio</h3>
  <p style="color: #ccc; margin-bottom: 20px;">Blockchain-based credential verification with NFT certificates and decentralized storage</p>
  <div style="display: flex; gap: 10px; margin-bottom: 20px; flex-wrap: wrap;">
    <span style="padding: 5px 15px; background: rgba(138, 43, 226, 0.2); border-radius: 15px; font-size: 0.9rem;">Web3</span>
    <span style="padding: 5px 15px; background: rgba(255, 107, 107, 0.2); border-radius: 15px; font-size: 0.9rem;">Solidity</span>
    <span style="padding: 5px 15px; background: rgba(0, 255, 170, 0.2); border-radius: 15px; font-size: 0.9rem;">IPFS</span>
  </div>
  <div style="display: flex; align-items: center; color: #8A2BE2;">
    <div style="width: 10px; height: 10px; background: #8A2BE2; border-radius: 50%; margin-right: 10px; animation: blink 1s infinite 0.5s;"></div>
    <span>PLANNING</span>
  </div>
</div>

</div>

<!-- Contact Section -->
<h2 style="
  color: #00FFAA;
  font-family: 'Orbitron', sans-serif;
  font-size: 2.5rem;
  margin: 60px 0 30px 0;
  text-align: center;
  animation: text-glow 3s infinite alternate;
">📡 CONNECT WITH ME</h2>

<div style="
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 20px;
  margin: 40px 0;
  padding: 20px;
">

<a href="mailto:musfiqurerahman.eub@gmail.com" class="contact-btn" style="
  background: linear-gradient(135deg, rgba(255,107,107,0.2), rgba(255,107,107,0.1));
  border: 2px solid #FF6B6B;
  border-radius: 15px;
  padding: 25px;
  text-decoration: none;
  color: white;
  text-align: center;
  transition: all 0.3s ease;
  animation: btn-float 3s infinite;
">
  <div style="font-size: 2.5rem; margin-bottom: 10px;">✉️</div>
  <div style="font-weight: bold;">Email</div>
  <div style="font-size: 0.9rem; opacity: 0.8;">musfiqurerahman.eub@gmail.com</div>
</a>

<a href="https://wa.me/8801778375642" class="contact-btn" style="
  background: linear-gradient(135deg, rgba(0,255,170,0.2), rgba(0,255,170,0.1));
  border: 2px solid #00FFAA;
  border-radius: 15px;
  padding: 25px;
  text-decoration: none;
  color: white;
  text-align: center;
  transition: all 0.3s ease;
  animation: btn-float 3s infinite 0.5s;
">
  <div style="font-size: 2.5rem; margin-bottom: 10px;">💬</div>
  <div style="font-weight: bold;">WhatsApp</div>
  <div style="font-size: 0.9rem; opacity: 0.8;">+880 1778-375642</div>
</a>

<a href="https://linkedin.com/in/musfiqurekoushik" class="contact-btn" style="
  background: linear-gradient(135deg, rgba(0,212,255,0.2), rgba(0,212,255,0.1));
  border: 2px solid #00D4FF;
  border-radius: 15px;
  padding: 25px;
  text-decoration: none;
  color: white;
  text-align: center;
  transition: all 0.3s ease;
  animation: btn-float 3s infinite 1s;
">
  <div style="font-size: 2.5rem; margin-bottom: 10px;">💼</div>
  <div style="font-weight: bold;">LinkedIn</div>
  <div style="font-size: 0.9rem; opacity: 0.8;">/musfiqurekoushik</div>
</a>

<a href="https://github.com/musfiqurekoushik" class="contact-btn" style="
  background: linear-gradient(135deg, rgba(138,43,226,0.2), rgba(138,43,226,0.1));
  border: 2px solid #8A2BE2;
  border-radius: 15px;
  padding: 25px;
  text-decoration: none;
  color: white;
  text-align: center;
  transition: all 0.3s ease;
  animation: btn-float 3s infinite 1.5s;
">
  <div style="font-size: 2.5rem; margin-bottom: 10px;">⚡</div>
  <div style="font-weight: bold;">GitHub</div>
  <div style="font-size: 0.9rem; opacity: 0.8;">@musfiqurekoushik</div>
</a>

</div>

<!-- Footer -->
<div style="
  margin-top: 60px;
  padding-top: 30px;
  border-top: 2px solid rgba(0,212,255,0.3);
  text-align: center;
">
  <p style="color: #00FFAA; font-size: 1.1rem; margin-bottom: 10px;">
    <i>"Code with Purpose, Build with Passion, Innovate with AI."</i>
  </p>
  <div id="visitor-counter" style="
    font-size: 2rem;
    font-weight: bold;
    font-family: 'Orbitron', sans-serif;
    color: #00D4FF;
    margin: 20px 0;
    animation: counter-glow 2s infinite;
  ">Loading...</div>
  <p style="color: #ccc; font-size: 0.9rem;">
    <strong>Let's build the future, one commit at a time! 🚀</strong>
  </p>
</div>

</div> <!-- End Main Container -->

</div> <!-- End Center Align -->

<style>
  @keyframes gradient-move {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
  }

  @keyframes glitch-effect {
    0% { transform: translate(0); }
    20% { transform: translate(-2px, 2px); }
    40% { transform: translate(-2px, -2px); }
    60% { transform: translate(2px, 2px); }
    80% { transform: translate(2px, -2px); }
    100% { transform: translate(0); }
  }

  @keyframes title-pulse {
    0%, 100% { transform: scale(1); box-shadow: 0 0 30px rgba(0, 212, 255, 0.4); }
    50% { transform: scale(1.02); box-shadow: 0 0 50px rgba(0, 212, 255, 0.6); }
  }

  @keyframes float {
    0%, 100% { transform: translateY(0); }
    50% { transform: translateY(-10px); }
  }

  @keyframes card-float {
    0%, 100% { transform: translateY(0); }
    50% { transform: translateY(-15px); }
  }

  @keyframes border-glow {
    0% { box-shadow: 0 0 50px rgba(0, 212, 255, 0.3), 0 0 100px rgba(0, 255, 170, 0.2); }
    50% { box-shadow: 0 0 80px rgba(0, 212, 255, 0.5), 0 0 150px rgba(138, 43, 226, 0.3); }
    100% { box-shadow: 0 0 50px rgba(0, 212, 255, 0.3), 0 0 100px rgba(255, 107, 107, 0.2); }
  }

  @keyframes spin {
    from { transform: rotate(0deg); }
    to { transform: rotate(360deg); }
  }

  @keyframes bounce {
    0%, 100% { transform: translateY(0); }
    50% { transform: translateY(-10px); }
  }

  @keyframes pulse {
    0%, 100% { transform: scale(1); opacity: 1; }
    50% { transform: scale(1.1); opacity: 0.8; }
  }

  @keyframes glow {
    0%, 100% { text-shadow: 0 0 10px currentColor; }
    50% { text-shadow: 0 0 20px currentColor, 0 0 30px currentColor; }
  }

  @keyframes text-glow {
    0% { text-shadow: 0 0 10px currentColor; }
    100% { text-shadow: 0 0 20px currentColor, 0 0 30px currentColor; }
  }

  @keyframes card-glow {
    0%, 100% { box-shadow: 0 0 20px rgba(0, 212, 255, 0.3); }
    50% { box-shadow: 0 0 40px rgba(0, 212, 255, 0.6); }
  }

  @keyframes stats-float {
    0%, 100% { transform: translateY(0); }
    50% { transform: translateY(-5px); }
  }

  @keyframes pulse-border {
    0%, 100% { border-color: rgba(0, 212, 255, 0.7); }
    50% { border-color: rgba(0, 212, 255, 1); }
  }

  @keyframes tech-bounce {
    0%, 100% { transform: translateY(0); }
    50% { transform: translateY(-5px); }
  }

  @keyframes project-glow {
    0%, 100% { box-shadow: 0 0 20px rgba(0, 212, 255, 0.3); }
    33% { box-shadow: 0 0 30px rgba(0, 255, 170, 0.4); }
    66% { box-shadow: 0 0 40px rgba(138, 43, 226, 0.5); }
  }

  @keyframes blink {
    0%, 100% { opacity: 1; }
    50% { opacity: 0; }
  }

  @keyframes btn-float {
    0%, 100% { transform: translateY(0); }
    50% { transform: translateY(-5px); }
  }

  @keyframes counter-glow {
    0%, 100% { filter: brightness(1); }
    50% { filter: brightness(1.5); }
  }

  @keyframes matrix-fall {
    from { transform: translateY(-100px); }
    to { transform: translateY(100vh); }
  }

  /* Tech Tag Styles */
  .tech-tag {
    padding: 12px 24px;
    color: white;
    border-radius: 25px;
    font-weight: bold;
    animation: tech-bounce 2s infinite;
    box-shadow: 0 0 20px currentColor;
    transition: all 0.3s ease;
  }

  .tech-tag:hover {
    transform: scale(1.1);
    box-shadow: 0 0 30px currentColor;
  }

  /* Contact Button Hover */
  .contact-btn:hover {
    transform: translateY(-10px) scale(1.05);
    box-shadow: 0 15px 30px rgba(0, 0, 0, 0.3);
  }

  /* Project Card Hover */
  .project-card:hover {
    transform: translateY(-10px);
    transition: transform 0.3s ease;
  }

  /* Responsive Design */
  @media (max-width: 768px) {
    #glitch-name { font-size: 2.5rem; }
    h2 span { font-size: 1.8rem; }
    .tech-tag { padding: 8px 16px; font-size: 0.9rem; }
  }
</style>

<script>
  // Matrix Background
  function createMatrix() {
    const chars = '01';
    const bg = document.getElementById('matrix-bg');
    
    function createStream() {
      const stream = document.createElement('div');
      stream.style.cssText = `
        position: absolute;
        top: -100px;
        left: ${Math.random() * 100}vw;
        color: #0f0;
        font-size: 16px;
        font-family: 'Courier New', monospace;
        opacity: ${Math.random() * 0.2 + 0.1};
        animation: matrix-fall ${Math.random() * 5 + 3}s linear infinite;
        pointer-events: none;
        z-index: -1;
      `;
      
      let text = '';
      for(let i = 0; i < 15; i++) {
        text += chars.charAt(Math.floor(Math.random() * chars.length)) + '<br>';
      }
      
      stream.innerHTML = text;
      bg.appendChild(stream);
      
      setTimeout(() => {
        stream.remove();
      }, 5000);
    }
    
    // Start matrix streams
    setInterval(createStream, 100);
  }

  // Animated Counters
  function animateCounters() {
    const counters = document.querySelectorAll('.counter');
    
    counters.forEach(counter => {
      const target = parseInt(counter.getAttribute('data-target'));
      let current = 0;
      const increment = target / 100;
      
      const updateCounter = () => {
        if (current < target) {
          current += increment;
          counter.textContent = Math.floor(current);
          setTimeout(updateCounter, 20);
        } else {
          counter.textContent = target;
        }
      };
      
      updateCounter();
    });
  }

  // Visitor Counter
  function updateVisitorCounter() {
    const counter = document.getElementById('visitor-counter');
    const baseVisitors = 1528; // Starting point
    const randomVisitors = Math.floor(Math.random() * 100);
    const totalVisitors = baseVisitors + randomVisitors;
    
    let current = 0;
    const increment = totalVisitors / 50;
    
    const update = () => {
      if (current < totalVisitors) {
        current += increment;
        counter.textContent = Math.floor(current);
        setTimeout(update, 20);
      } else {
        counter.textContent = totalVisitors.toLocaleString();
      }
    };
    
    update();
  }

  // Initialize everything when page loads
  document.addEventListener('DOMContentLoaded', () => {
    createMatrix();
    animateCounters();
    updateVisitorCounter();
    
    // Add hover effects
    document.querySelectorAll('.contact-btn').forEach(btn => {
      btn.addEventListener('mouseenter', function() {
        this.style.transform = 'translateY(-10px) scale(1.05)';
      });
      btn.addEventListener('mouseleave', function() {
        this.style.transform = 'translateY(0) scale(1)';
      });
    });
  });
</script>

<!-- SEO Keywords -->
<!-- 
Full Stack Developer | MERN Stack Expert | Next.js Specialist | AI Integration Developer | 
Machine Learning Enthusiast | React Developer | Node.js Developer | TypeScript Expert | 
MongoDB Developer | Bangladesh Developer | Dhaka Programmer | Available for Hire | 
Tech Lead | Software Architect | Web Development | Quantum Developer | Animated Portfolio
-->
