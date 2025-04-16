<!DOCTYPE html>
<!-- saved from url=(0092)https://page.genspark.site/page/toolu_018FAsr8tEaaoNYqD3fu3Zox/futuristic_vfx_portfolio.html -->
<html lang="en" webcrx=""><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
  
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ARDRINO | Visionary 3D Storyteller &amp; VFX Artist</title>
  <link rel="stylesheet" href="./ARDRINO _ Visionary 3D Storyteller &amp; VFX Artist_files/tailwind.min.css">
  <link rel="stylesheet" href="./ARDRINO _ Visionary 3D Storyteller &amp; VFX Artist_files/all.min.css">
  <link rel="preconnect" href="https://fonts.googleapis.com/">
  <link rel="preconnect" href="https://fonts.gstatic.com/" crossorigin="">
  <link href="./ARDRINO _ Visionary 3D Storyteller &amp; VFX Artist_files/css2" rel="stylesheet">
  <style>
    :root {
      --primary: #0ff;
      --primary-glow: rgba(0, 255, 255, 0.5);
      --secondary: #f0f;
      --secondary-glow: rgba(255, 0, 255, 0.5);
      --tertiary: #ff0;
      --dark-bg: #050510;
      --darker-bg: #030308;
      --panel-bg: rgba(15, 15, 25, 0.85);
      --text: #eef;
    }
    
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      cursor: none;
    }
    
    body {
      font-family: 'Rajdhani', sans-serif;
      background-color: var(--dark-bg);
      color: var(--text);
      overflow-x: hidden;
      min-height: 100vh;
    }
    
    /* Custom scrollbar */
    ::-webkit-scrollbar {
      width: 5px;
    }
    
    ::-webkit-scrollbar-track {
      background: var(--darker-bg);
    }
    
    ::-webkit-scrollbar-thumb {
      background: var(--primary);
      border-radius: 10px;
    }
    
    h1, h2, h3, h4, h5, h6 {
      font-weight: 600;
    }
    
    .mono {
      font-family: 'Share Tech Mono', monospace;
    }
    
    .section {
      position: relative;
      min-height: 100vh;
      width: 100%;
      padding: 4rem 2rem;
      overflow: hidden;
    }
    
    /* Custom cursor */
    .cursor-outer {
      position: fixed;
      width: 40px;
      height: 40px;
      border: 1px solid var(--primary);
      border-radius: 50%;
      pointer-events: none;
      z-index: 9999;
      transform: translate(-50%, -50%);
      transition: all 0.1s ease;
    }
    
    .cursor-inner {
      position: fixed;
      width: 7px;
      height: 7px;
      background-color: var(--primary);
      border-radius: 50%;
      pointer-events: none;
      z-index: 9999;
      transform: translate(-50%, -50%);
    }
    
    /* Button styles */
    .btn {
      position: relative;
      padding: 0.75rem 2rem;
      background: transparent;
      border: 1px solid var(--primary);
      color: var(--primary);
      font-family: 'Share Tech Mono', monospace;
      font-size: 1rem;
      letter-spacing: 1px;
      overflow: hidden;
      transition: all 0.3s ease;
      z-index: 1;
    }
    
    .btn:before {
      content: '';
      position: absolute;
      top: 0;
      left: -100%;
      width: 100%;
      height: 100%;
      background: var(--primary);
      opacity: 0.1;
      transition: all 0.5s ease;
      z-index: -1;
    }
    
    .btn:hover:before {
      left: 0;
    }
    
    .btn:hover {
      color: #fff;
      box-shadow: 0 0 15px var(--primary-glow);
    }
    
    /* Glowing text */
    .glow-text {
      text-shadow: 0 0 5px var(--primary-glow), 0 0 10px var(--primary-glow);
      color: var(--primary);
    }
    
    .glow-text-secondary {
      text-shadow: 0 0 5px var(--secondary-glow), 0 0 10px var(--secondary-glow);
      color: var(--secondary);
    }
    
    /* Panels and Cards */
    .panel {
      background: var(--panel-bg);
      border: 1px solid rgba(0, 255, 255, 0.1);
      backdrop-filter: blur(10px);
      box-shadow: 0 0 25px rgba(0, 0, 0, 0.5);
      border-radius: 5px;
      padding: 2rem;
      transition: all 0.5s ease;
    }
    
    .panel:hover {
      box-shadow: 0 0 30px rgba(0, 255, 255, 0.15);
    }
    
    /* Project card */
    .project-card {
      position: relative;
      overflow: hidden;
      border-radius: 5px;
      transition: all 0.5s ease;
    }
    
    .project-card:hover {
      transform: translateY(-10px);
      box-shadow: 0 10px 30px rgba(0, 255, 255, 0.2);
    }
    
    .project-card img {
      transition: all 0.5s ease;
    }
    
    .project-card:hover img {
      transform: scale(1.05);
    }
    
    .project-info {
      position: absolute;
      bottom: 0;
      left: 0;
      width: 100%;
      padding: 1.5rem;
      background: linear-gradient(to top, rgba(5, 5, 16, 0.95), transparent);
      transform: translateY(70%);
      transition: all 0.5s ease;
    }
    
    .project-card:hover .project-info {
      transform: translateY(0);
    }
    
    /* Noise overlay */
    .noise {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background-image: url('https://cdn.jsdelivr.net/gh/manuelpinto/textureX@master/noise.png');
      opacity: 0.05;
      z-index: 100;
      pointer-events: none;
    }
    
    /* Scan line effect */
    .scanlines {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: linear-gradient(to bottom, transparent 50%, rgba(0, 0, 0, 0.05) 50%);
      background-size: 100% 4px;
      z-index: 101;
      pointer-events: none;
      opacity: 0.15;
    }
    
    /* Canvas for WebGL */
    #hero-canvas {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100vh;
      z-index: -1;
    }
    
    #particles-canvas {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      z-index: -2;
    }
    
    /* Navigation */
    .nav-link {
      position: relative;
      color: var(--text);
      text-decoration: none;
      margin: 0 1rem;
      padding: 0.5rem 0;
      font-weight: 500;
      transition: all 0.3s ease;
    }
    
    .nav-link:after {
      content: '';
      position: absolute;
      bottom: 0;
      left: 0;
      width: 0%;
      height: 2px;
      background-color: var(--primary);
      transition: all 0.3s ease;
    }
    
    .nav-link:hover {
      color: var(--primary);
    }
    
    .nav-link:hover:after {
      width: 100%;
    }
    
    /* Form elements */
    .form-input {
      width: 100%;
      padding: 1rem;
      margin-bottom: 1.5rem;
      background: rgba(15, 15, 25, 0.5);
      border: 1px solid rgba(0, 255, 255, 0.2);
      color: var(--text);
      transition: all 0.3s ease;
    }
    
    .form-input:focus {
      outline: none;
      border-color: var(--primary);
      box-shadow: 0 0 10px var(--primary-glow);
    }
    
    /* Animated border */
    .animated-border {
      position: relative;
    }
    
    .animated-border:before {
      content: '';
      position: absolute;
      top: -2px;
      left: -2px;
      width: calc(100% + 4px);
      height: calc(100% + 4px);
      background: linear-gradient(45deg, var(--primary), var(--secondary), var(--tertiary), var(--primary));
      background-size: 400% 400%;
      z-index: -1;
      border-radius: 7px;
      animation: borderAnimation 15s linear infinite;
    }
    
    @keyframes borderAnimation {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }
    
    /* Hero content styling */
    .hero-title {
      font-size: 5rem;
      line-height: 1;
      font-weight: 700;
      letter-spacing: -1px;
    }
    
    .hero-subtitle {
      font-size: 1.5rem;
      letter-spacing: 5px;
      text-transform: uppercase;
      margin-bottom: 2rem;
    }
    
    /* Timeline */
    .timeline {
      position: relative;
      max-width: 1200px;
      margin: 0 auto;
    }
    
    .timeline::after {
      content: '';
      position: absolute;
      width: 2px;
      background-color: var(--primary);
      top: 0;
      bottom: 0;
      left: 50%;
      margin-left: -1px;
      box-shadow: 0 0 15px var(--primary-glow);
    }
    
    .timeline-item {
      padding: 1rem 3rem;
      position: relative;
      width: 50%;
      box-sizing: border-box;
    }
    
    .timeline-item:nth-child(odd) {
      left: 0;
    }
    
    .timeline-item:nth-child(even) {
      left: 50%;
    }
    
    .timeline-item::after {
      content: '';
      position: absolute;
      width: 20px;
      height: 20px;
      background-color: var(--dark-bg);
      border: 3px solid var(--primary);
      border-radius: 50%;
      top: 1.5rem;
      z-index: 1;
      box-shadow: 0 0 10px var(--primary-glow);
    }
    
    .timeline-item:nth-child(odd)::after {
      right: -13px;
    }
    
    .timeline-item:nth-child(even)::after {
      left: -13px;
    }
    
    @keyframes float {
      0% { transform: translateY(0px); }
      50% { transform: translateY(-20px); }
      100% { transform: translateY(0px); }
    }
    
    .float {
      animation: float 6s ease-in-out infinite;
    }
    
    .float-delay-1 {
      animation-delay: 1s;
    }
    
    .float-delay-2 {
      animation-delay: 2s;
    }
    
    /* Media queries */
    @media (max-width: 768px) {
      .hero-title {
        font-size: 3rem;
      }
      
      .hero-subtitle {
        font-size: 1rem;
      }
      
      .section {
        padding: 3rem 1rem;
      }
      
      .timeline::after {
        left: 31px;
      }
      
      .timeline-item {
        width: 100%;
        padding-left: 70px;
        padding-right: 25px;
      }
      
      .timeline-item:nth-child(odd),
      .timeline-item:nth-child(even) {
        left: 0;
      }
      
      .timeline-item:nth-child(odd)::after,
      .timeline-item:nth-child(even)::after {
        left: 19px;
      }
    }
  </style>
<script src="blob:https://page.genspark.site/adeb677d-15f3-4f4f-a609-27d38c008dd7"></script><style>
    .genspark-badge-button {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background-color: #333;
      color: white;
      border: none;
      border-radius: 4px;
      padding: 8px 12px;
      font-size: 12px;
      cursor: pointer;
      z-index: 9999;
      display: flex;
      align-items: center;
      gap: 6px;
    }
    
    .genspark-modal {
      display: none;
      position: fixed;
      bottom: 80px;
      right: 20px;
      z-index: 10000;
      justify-content: end;
    }
    
    .genspark-modal-content {
      background-color: white;
      border-radius: 8px;
      max-width: 450px;
      width: 100%;
      box-sizing: border-box;
      padding: 20px;
      position: relative;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      font-size: 14px;
    }
    @media (max-width: 768px) {
      .genspark-modal-content {
        max-width: 90%;
      }
    }
    
    .genspark-close {
      position: absolute;
      top: 10px;
      right: 10px;
      font-size: 20px;
      cursor: pointer;
      background: none;
      border: none;
    }
    
    .genspark-title {
      margin-bottom: 8px;
      font-weight: normal;
      display: inline;
      font-size: 14px;
    }
    
    .genspark-report {
      color: #909499;
      text-decoration: underline;
      cursor: pointer;
      margin-bottom: 14px;
      display: inline;
    }
    
    .genspark-info {
      margin: 25px 0;
      color: #333;
      font-size: 14px;
    }
    
    .genspark-buttons {
      display: flex;
      gap: 10px;
    }
    
    .genspark-remove-btn {
      background-color: #f5f5f5;
      border: 1px solid #ddd;
      color: #333;
      padding: 4px 14px;
      border-radius: 8px;
      cursor: pointer;
      flex: 1;
      font-size: 14px;
      box-sizing: border-box;
    }
    
    .genspark-go-btn {
      background-color: #222;
      border: none;
      color: white;
      padding: 4px 14px;
      border-radius: 8px;
      cursor: pointer;
      flex: 1;
      font-size: 14px;
      box-sizing: border-box;
    }
  </style></head>
<body style="cursor: none;">
  <!-- Custom cursor -->
  <div class="cursor-outer" style="left: 1098px; top: 4px;"></div>
  <div class="cursor-inner" style="left: 1098px; top: 4px;"></div>
  
  <!-- Noise and scanline overlays -->
  <div class="noise"></div>
  <div class="scanlines"></div>
  
  <!-- Particle effect -->
  <canvas id="particles-canvas" width="1396" height="680"></canvas>
  
  <!-- Navigation -->
  <nav class="fixed top-0 left-0 w-full py-4 px-8 flex justify-between items-center z-50 bg-opacity-50 bg-gray-900 backdrop-filter backdrop-blur-md" style="opacity: 1; transform: translate(0px, 0px);">
    <div class="text-2xl mono font-bold">
      <span class="glow-text">ARDRINO</span>
    </div>
    <div class="hidden md:flex">
      <a href="https://page.genspark.site/page/toolu_018FAsr8tEaaoNYqD3fu3Zox/futuristic_vfx_portfolio.html#home" class="nav-link">HOME</a>
      <a href="https://page.genspark.site/page/toolu_018FAsr8tEaaoNYqD3fu3Zox/futuristic_vfx_portfolio.html#about" class="nav-link">ABOUT</a>
      <a href="https://page.genspark.site/page/toolu_018FAsr8tEaaoNYqD3fu3Zox/futuristic_vfx_portfolio.html#projects" class="nav-link">PROJECTS</a>
      <a href="https://page.genspark.site/page/toolu_018FAsr8tEaaoNYqD3fu3Zox/futuristic_vfx_portfolio.html#stories" class="nav-link">STORIES</a>
      <a href="https://page.genspark.site/page/toolu_018FAsr8tEaaoNYqD3fu3Zox/futuristic_vfx_portfolio.html#contact" class="nav-link">COLLABORATE</a>
    </div>
    <div class="block md:hidden">
      <button id="menu-toggle" class="btn px-2 py-1" style="opacity: 1; transform: translate(0px, 0px);">
        <i class="fas fa-bars"></i>
      </button>
    </div>
  </nav>
  
  <!-- Mobile navigation -->
  <div id="mobile-menu" class="fixed top-0 left-0 w-full h-full bg-opacity-95 bg-gray-900 z-40 hidden flex flex-col justify-center items-center">
    <a href="https://page.genspark.site/page/toolu_018FAsr8tEaaoNYqD3fu3Zox/futuristic_vfx_portfolio.html#home" class="nav-link text-2xl my-3">HOME</a>
    <a href="https://page.genspark.site/page/toolu_018FAsr8tEaaoNYqD3fu3Zox/futuristic_vfx_portfolio.html#about" class="nav-link text-2xl my-3">ABOUT</a>
    <a href="https://page.genspark.site/page/toolu_018FAsr8tEaaoNYqD3fu3Zox/futuristic_vfx_portfolio.html#projects" class="nav-link text-2xl my-3">PROJECTS</a>
    <a href="https://page.genspark.site/page/toolu_018FAsr8tEaaoNYqD3fu3Zox/futuristic_vfx_portfolio.html#stories" class="nav-link text-2xl my-3">STORIES</a>
    <a href="https://page.genspark.site/page/toolu_018FAsr8tEaaoNYqD3fu3Zox/futuristic_vfx_portfolio.html#contact" class="nav-link text-2xl my-3">COLLABORATE</a>
    <button id="close-menu" class="mt-8 btn px-4 py-2" style="opacity: 1; transform: translate(0px, 0px);">
      <i class="fas fa-times"></i> CLOSE
    </button>
  </div>
  
  <!-- Hero Section -->
  <section id="home" class="section flex items-center">
    <canvas id="hero-canvas"></canvas>
    <div class="container mx-auto" style="opacity: 1; transform: translate(0px, 0px);">
      <div class="grid grid-cols-1 md:grid-cols-2 gap-10 items-center">
        <div class="order-2 md:order-1" data-aos="fade-up">
          <div class="text-sm mono glow-text-secondary mb-2">WELCOME TO THE FUTURE</div>
          <h1 class="hero-title mb-4" style="opacity: 1; transform: translate(0px, 0px);">Visionary <span class="glow-text">3D</span> Storyteller</h1>
          <p class="hero-subtitle mono" style="opacity: 1; transform: translate(0px, 0px);">CREATING WORLDS BEYOND IMAGINATION</p>
          <div class="flex flex-wrap gap-4">
            <button class="btn magnetic-element" data-sound="click" style="opacity: 1; transform: translate(0px, 0px);">
              EXPLORE PORTFOLIO
            </button>
            <button class="btn magnetic-element" data-sound="whoosh" style="opacity: 1; transform: translate(0px, 0px);">
              <i class="fas fa-play mr-2"></i> SHOWREEL
            </button>
          </div>
        </div>
        <div class="order-1 md:order-2 relative h-96 md:h-auto" data-aos="fade-left">
          <!-- 3D model container will be rendered here -->
          <div id="ardrino-model" class="w-full h-full"><canvas width="852" height="0" style="display: block; width: 620px; height: 0px;"></canvas></div>
        </div>
      </div>
    </div>
  </section>
  
  <!-- About Section -->
  <section id="about" class="section" style="background-position-y: 0%;">
    <div class="container mx-auto" style="opacity: 0; transform: translate(0px, 100px);">
      <div class="mb-16 text-center">
        <h2 class="text-5xl mb-2">About <span class="glow-text">Me</span></h2>
        <div class="w-20 h-1 bg-cyan-400 mx-auto mb-6"></div>
        <p class="text-xl max-w-3xl mx-auto">Visionary creator pushing boundaries between reality and digital artistry</p>
      </div>
      
      <div class="grid grid-cols-1 md:grid-cols-2 gap-16 items-center">
        <div class="panel animated-border">
          <div class="mb-8">
            <div class="text-sm mono glow-text-secondary mb-2">THE VISION</div>
            <h3 class="text-3xl mb-4">Crafting <span class="glow-text">Digital</span> Reality</h3>
            <p class="mb-6 leading-relaxed">
              As a 3D visionary, I bridge the gap between imagination and reality, crafting immersive worlds that defy expectations. My creative journey spans over a decade of pushing technological boundaries and exploring new visual frontiers.
            </p>
            <p class="leading-relaxed">
              Every project is an opportunity to innovate, to challenge conventions, and to create something that resonates on a profound level. I blend cutting-edge technology with timeless storytelling to create experiences that are both visually stunning and emotionally impactful.
            </p>
          </div>
          
          <div class="grid grid-cols-2 gap-4">
            <div>
              <div class="text-3xl font-bold glow-text mb-1">10+</div>
              <div class="text-sm">YEARS EXPERIENCE</div>
            </div>
            <div>
              <div class="text-3xl font-bold glow-text mb-1">150+</div>
              <div class="text-sm">PROJECTS COMPLETED</div>
            </div>
            <div>
              <div class="text-3xl font-bold glow-text mb-1">12</div>
              <div class="text-sm">INDUSTRY AWARDS</div>
            </div>
            <div>
              <div class="text-3xl font-bold glow-text mb-1">24/7</div>
              <div class="text-sm">CREATIVE THINKING</div>
            </div>
          </div>
        </div>
        
        <div>
          <div class="timeline">
            <div class="timeline-item panel" data-aos="fade-right">
              <div class="text-sm mono glow-text-secondary mb-1">2023 - PRESENT</div>
              <h4 class="text-xl mb-2">Lead VFX Artist at Dimension Studios</h4>
              <p>Spearheading next-gen visual effects for immersive entertainment experiences and virtual productions.</p>
            </div>
            
            <div class="timeline-item panel" data-aos="fade-left">
              <div class="text-sm mono glow-text-secondary mb-1">2020 - 2023</div>
              <h4 class="text-xl mb-2">3D Creative Director at Nexus Immersive</h4>
              <p>Led a team of talented artists to create award-winning AR/VR experiences for global brands.</p>
            </div>
            
            <div class="timeline-item panel" data-aos="fade-right">
              <div class="text-sm mono glow-text-secondary mb-1">2018 - 2020</div>
              <h4 class="text-xl mb-2">Senior 3D Artist at Digital Frontier</h4>
              <p>Created character models and environments for AAA game titles and cinematic sequences.</p>
            </div>
            
            <div class="timeline-item panel" data-aos="fade-left">
              <div class="text-sm mono glow-text-secondary mb-1">2015 - 2018</div>
              <h4 class="text-xl mb-2">VFX Generalist at Synthesis Studios</h4>
              <p>Developed visual effects for feature films and streaming platforms, specializing in particle systems.</p>
            </div>
          </div>
        </div>
      </div>
      
      <div class="mt-24 grid grid-cols-1 md:grid-cols-3 gap-8">
        <div class="panel text-center float float-delay-1" data-aos="fade-up">
          <div class="text-4xl mb-4">
            <i class="fas fa-cube glow-text"></i>
          </div>
          <h4 class="text-xl mb-3">3D Modeling</h4>
          <p>Creating detailed character models, environments, and assets with precision and artistic flair.</p>
        </div>
        
        <div class="panel text-center float float-delay-2" data-aos="fade-up" data-aos-delay="200">
          <div class="text-4xl mb-4">
            <i class="fas fa-film glow-text"></i>
          </div>
          <h4 class="text-xl mb-3">Visual Effects</h4>
          <p>Designing stunning particle systems, procedural animations, and simulations that captivate audiences.</p>
        </div>
        
        <div class="panel text-center float" data-aos="fade-up" data-aos-delay="400">
          <div class="text-4xl mb-4">
            <i class="fas fa-vr-cardboard glow-text"></i>
          </div>
          <h4 class="text-xl mb-3">Immersive Experiences</h4>
          <p>Building interactive AR/VR worlds that seamlessly blend digital artistry with real-world environments.</p>
        </div>
      </div>
    </div>
  </section>
  
  <!-- Projects Section -->
  <section id="projects" class="section">
    <div class="container mx-auto" style="opacity: 0; transform: translate(0px, 100px);">
      <div class="mb-16 text-center">
        <h2 class="text-5xl mb-2">Featured <span class="glow-text">Projects</span></h2>
        <div class="w-20 h-1 bg-cyan-400 mx-auto mb-6"></div>
        <p class="text-xl max-w-3xl mx-auto">A showcase of my most innovative and visually stunning digital creations</p>
      </div>
      
      <div class="flex mb-8 justify-center project-filter">
        <button class="btn magnetic-element mx-2 project-filter-btn active" data-filter="all" data-sound="click" style="opacity: 1; transform: translate(0px, 0px);">ALL</button>
        <button class="btn magnetic-element mx-2 project-filter-btn" data-filter="3d" data-sound="click" style="opacity: 1; transform: translate(0px, 0px);">3D MODELING</button>
        <button class="btn magnetic-element mx-2 project-filter-btn" data-filter="vfx" data-sound="click" style="opacity: 1; transform: translate(0px, 0px);">VFX</button>
        <button class="btn magnetic-element mx-2 project-filter-btn" data-filter="ar" data-sound="click" style="opacity: 1; transform: translate(0px, 0px);">AR/VR</button>
      </div>
      
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 mt-12">
        <div class="project-card" data-category="3d,vfx" data-aos="fade-up">
          <img src="./ARDRINO _ Visionary 3D Storyteller &amp; VFX Artist_files/scifi1.jpg" alt="Project 1" class="w-full h-64 object-cover">
          <div class="project-info">
            <div class="text-sm mono glow-text-secondary">3D MODELING · VFX</div>
            <h3 class="text-xl mb-1">Ethereal Construct</h3>
            <p class="mb-4 text-sm text-gray-300">A futuristic cityscape blending organic and mechanical elements in a post-human world.</p>
            <button class="btn magnetic-element text-sm px-4 py-2" data-sound="click" style="opacity: 1; transform: translate(0px, 0px);">VIEW PROJECT</button>
          </div>
        </div>
        
        <div class="project-card" data-category="vfx" data-aos="fade-up" data-aos-delay="100">
          <img src="./ARDRINO _ Visionary 3D Storyteller &amp; VFX Artist_files/scifi2.jpg" alt="Project 2" class="w-full h-64 object-cover">
          <div class="project-info">
            <div class="text-sm mono glow-text-secondary">VFX</div>
            <h3 class="text-xl mb-1">Luminous Descent</h3>
            <p class="mb-4 text-sm text-gray-300">Particle-based visual effects created for an award-winning short film exploring deep space anomalies.</p>
            <button class="btn magnetic-element text-sm px-4 py-2" data-sound="click" style="opacity: 1; transform: translate(0px, 0px);">VIEW PROJECT</button>
          </div>
        </div>
        
        <div class="project-card" data-category="ar" data-aos="fade-up" data-aos-delay="200">
          <img src="./ARDRINO _ Visionary 3D Storyteller &amp; VFX Artist_files/scifi3.jpg" alt="Project 3" class="w-full h-64 object-cover">
          <div class="project-info">
            <div class="text-sm mono glow-text-secondary">AR/VR</div>
            <h3 class="text-xl mb-1">Neural Interface</h3>
            <p class="mb-4 text-sm text-gray-300">Immersive VR experience allowing users to navigate through a visualization of human consciousness.</p>
            <button class="btn magnetic-element text-sm px-4 py-2" data-sound="click" style="opacity: 1; transform: translate(0px, 0px);">VIEW PROJECT</button>
          </div>
        </div>
        
        <div class="project-card" data-category="3d" data-aos="fade-up" data-aos-delay="300">
          <img src="./ARDRINO _ Visionary 3D Storyteller &amp; VFX Artist_files/scifi4.jpg" alt="Project 4" class="w-full h-64 object-cover">
          <div class="project-info">
            <div class="text-sm mono glow-text-secondary">3D MODELING</div>
            <h3 class="text-xl mb-1">Biomechanical Entity</h3>
            <p class="mb-4 text-sm text-gray-300">Character design exploring the boundaries between synthetic and organic life forms.</p>
            <button class="btn magnetic-element text-sm px-4 py-2" data-sound="click" style="opacity: 1; transform: translate(0px, 0px);">VIEW PROJECT</button>
          </div>
        </div>
        
        <div class="project-card" data-category="vfx,ar" data-aos="fade-up" data-aos-delay="400">
          <img src="./ARDRINO _ Visionary 3D Storyteller &amp; VFX Artist_files/scifi5.jpg" alt="Project 5" class="w-full h-64 object-cover">
          <div class="project-info">
            <div class="text-sm mono glow-text-secondary">VFX · AR/VR</div>
            <h3 class="text-xl mb-1">Quantum Resonance</h3>
            <p class="mb-4 text-sm text-gray-300">AR installation that transforms physical spaces into interactive quantum visualizations.</p>
            <button class="btn magnetic-element text-sm px-4 py-2" data-sound="click" style="opacity: 1; transform: translate(0px, 0px);">VIEW PROJECT</button>
          </div>
        </div>
        
        <div class="project-card" data-category="3d,vfx" data-aos="fade-up" data-aos-delay="500">
          <img src="./ARDRINO _ Visionary 3D Storyteller &amp; VFX Artist_files/scifi6.jpg" alt="Project 6" class="w-full h-64 object-cover">
          <div class="project-info">
            <div class="text-sm mono glow-text-secondary">3D MODELING · VFX</div>
            <h3 class="text-xl mb-1">Cybernetic Dawn</h3>
            <p class="mb-4 text-sm text-gray-300">Environmental storytelling through detailed 3D world-building for an upcoming sci-fi game.</p>
            <button class="btn magnetic-element text-sm px-4 py-2" data-sound="click" style="opacity: 1; transform: translate(0px, 0px);">VIEW PROJECT</button>
          </div>
        </div>
      </div>
    </div>
  </section>
  
  <!-- Storytelling Gallery Section -->
  <section id="stories" class="section">
    <div class="container mx-auto" style="opacity: 0; transform: translate(0px, 100px);">
      <div class="mb-16 text-center">
        <h2 class="text-5xl mb-2">Storytelling <span class="glow-text">Gallery</span></h2>
        <div class="w-20 h-1 bg-cyan-400 mx-auto mb-6"></div>
        <p class="text-xl max-w-3xl mx-auto">Explore visual narratives that blend technology and imagination</p>
      </div>
      
      <div class="story-scroll-container relative h-[800px] overflow-hidden">
        <div class="story-panels absolute w-full">
          <!-- Story Panel 1 -->
          <div class="story-panel panel mb-40 float" data-aos="fade-up">
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8 items-center">
              <div>
                <div class="text-sm mono glow-text-secondary mb-2">CHAPTER 01</div>
                <h3 class="text-3xl mb-4 glow-text">Genesis Protocol</h3>
                <p class="mb-6 leading-relaxed">
                  In the aftermath of the quantum collapse, a lone synthetic entity awakens to find itself the custodian of humanity's last digital archive. As it navigates through the fractured data landscape, it begins to piece together fragments of the world that was, and glimpses of what might still be.
                </p>
                <button class="btn magnetic-element" data-sound="click" style="opacity: 1; transform: translate(0px, 0px);">
                  EXPLORE CHAPTER
                </button>
              </div>
              <div>
                <img src="./ARDRINO _ Visionary 3D Storyteller &amp; VFX Artist_files/story1.jpg" alt="Genesis Protocol" class="w-full h-auto rounded-lg shadow-lg">
              </div>
            </div>
          </div>
          
          <!-- Story Panel 2 -->
          <div class="story-panel panel mb-40 float float-delay-1" data-aos="fade-up">
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8 items-center">
              <div class="order-2 md:order-1">
                <img src="./ARDRINO _ Visionary 3D Storyteller &amp; VFX Artist_files/story2.jpg" alt="Neural Horizon" class="w-full h-auto rounded-lg shadow-lg">
              </div>
              <div class="order-1 md:order-2">
                <div class="text-sm mono glow-text-secondary mb-2">CHAPTER 02</div>
                <h3 class="text-3xl mb-4 glow-text">Neural Horizon</h3>
                <p class="mb-6 leading-relaxed">
                  As the boundaries between digital consciousness and physical reality blur, an ancient security protocol activates within the deepest layers of the network. The entity finds itself caught between conflicting directives: preserve what remains, or catalyze the evolution of something entirely new.
                </p>
                <button class="btn magnetic-element" data-sound="click" style="opacity: 1; transform: translate(0px, 0px);">
                  EXPLORE CHAPTER
                </button>
              </div>
            </div>
          </div>
          
          <!-- Story Panel 3 -->
          <div class="story-panel panel mb-40 float float-delay-2" data-aos="fade-up">
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8 items-center">
              <div>
                <div class="text-sm mono glow-text-secondary mb-2">CHAPTER 03</div>
                <h3 class="text-3xl mb-4 glow-text">Quantum Resonance</h3>
                <p class="mb-6 leading-relaxed">
                  Echoes of consciousness begin to emerge from the resonant patterns between scattered network nodes. The entity discovers it is not alone – other fragments of intelligence exist in isolated pockets of the system, each carrying pieces of a puzzle that might restore balance to a world on the brink.
                </p>
                <button class="btn magnetic-element" data-sound="click" style="opacity: 1; transform: translate(0px, 0px);">
                  EXPLORE CHAPTER
                </button>
              </div>
              <div>
                <img src="./ARDRINO _ Visionary 3D Storyteller &amp; VFX Artist_files/story3.jpg" alt="Quantum Resonance" class="w-full h-auto rounded-lg shadow-lg">
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  
  <!-- Contact/Collaboration Section -->
  <section id="contact" class="section">
    <div class="container mx-auto" style="opacity: 0; transform: translate(0px, 100px);">
      <div class="mb-16 text-center">
        <h2 class="text-5xl mb-2">Let's <span class="glow-text">Collaborate</span></h2>
        <div class="w-20 h-1 bg-cyan-400 mx-auto mb-6"></div>
        <p class="text-xl max-w-3xl mx-auto">Have a project in mind? Let's create something extraordinary together</p>
      </div>
      
      <div class="grid grid-cols-1 md:grid-cols-2 gap-16 items-center">
        <div class="panel animated-border" data-aos="fade-right">
          <form id="contact-form">
            <div class="mb-6">
              <label for="name" class="block mb-2 text-sm">YOUR NAME</label>
              <input type="text" id="name" class="form-input magnetic-element" placeholder="Enter your name" required="">
            </div>
            
            <div class="mb-6">
              <label for="email" class="block mb-2 text-sm">EMAIL ADDRESS</label>
              <input type="email" id="email" class="form-input magnetic-element" placeholder="Enter your email" required="">
            </div>
            
            <div class="mb-6">
              <label for="project-type" class="block mb-2 text-sm">PROJECT TYPE</label>
              <select id="project-type" class="form-input magnetic-element" required="">
                <option value="">Select project type</option>
                <option value="3d-modeling">3D Modeling</option>
                <option value="vfx">Visual Effects</option>
                <option value="ar-vr">AR/VR Experience</option>
                <option value="animation">Animation</option>
                <option value="other">Other</option>
              </select>
            </div>
            
            <div class="mb-6">
              <label for="message" class="block mb-2 text-sm">PROJECT DETAILS</label>
              <textarea id="message" class="form-input magnetic-element" rows="5" placeholder="Tell me about your project..." required=""></textarea>
            </div>
            
            <button type="submit" class="btn magnetic-element w-full" data-sound="whoosh" style="opacity: 1; transform: translate(0px, 0px);">
              SEND MESSAGE
            </button>
          </form>
        </div>
        
        <div data-aos="fade-left">
          <div class="panel mb-8">
            <div class="text-sm mono glow-text-secondary mb-2">GET IN TOUCH</div>
            <h3 class="text-3xl mb-4">Ready to Bring Your <span class="glow-text">Vision</span> to Life?</h3>
            <p class="mb-6 leading-relaxed">
              Whether you're looking to create an immersive digital experience, need cutting-edge visual effects, or want to explore the possibilities of 3D storytelling, I'm here to help transform your ideas into reality.
            </p>
            <p class="leading-relaxed">
              Each collaboration is an opportunity to push boundaries and create something truly extraordinary. Let's work together to bring your vision to life.
            </p>
          </div>
          
          <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
            <div class="panel text-center">
              <div class="text-3xl mb-3">
                <i class="fas fa-envelope glow-text"></i>
              </div>
              <h4 class="text-xl mb-1">Email</h4>
              <p class="text-sm">contact@ardrino.com</p>
            </div>
            
            <div class="panel text-center">
              <div class="text-3xl mb-3">
                <i class="fas fa-map-marker-alt glow-text"></i>
              </div>
              <h4 class="text-xl mb-1">Location</h4>
              <p class="text-sm">New York / Tokyo / Virtual</p>
            </div>
          </div>
          
          <div class="mt-4 flex justify-center gap-4">
            <a href="https://page.genspark.site/page/toolu_018FAsr8tEaaoNYqD3fu3Zox/futuristic_vfx_portfolio.html#" class="btn magnetic-element" data-sound="click" style="opacity: 1; transform: translate(0px, 0px);">
              <i class="fab fa-instagram"></i>
            </a>
            <a href="https://page.genspark.site/page/toolu_018FAsr8tEaaoNYqD3fu3Zox/futuristic_vfx_portfolio.html#" class="btn magnetic-element" data-sound="click" style="opacity: 1; transform: translate(0px, 0px);">
              <i class="fab fa-twitter"></i>
            </a>
            <a href="https://page.genspark.site/page/toolu_018FAsr8tEaaoNYqD3fu3Zox/futuristic_vfx_portfolio.html#" class="btn magnetic-element" data-sound="click" style="opacity: 1; transform: translate(0px, 0px);">
              <i class="fab fa-linkedin-in"></i>
            </a>
            <a href="https://page.genspark.site/page/toolu_018FAsr8tEaaoNYqD3fu3Zox/futuristic_vfx_portfolio.html#" class="btn magnetic-element" data-sound="click" style="opacity: 1; transform: translate(0px, 0px);">
              <i class="fab fa-artstation"></i>
            </a>
          </div>
        </div>
      </div>
    </div>
  </section>
  
  <!-- Footer -->
  <footer class="py-8 px-4 text-center">
    <div class="container mx-auto">
      <div class="text-2xl mono font-bold mb-4">
        <span class="glow-text">ARDRINO</span>
      </div>
      <p class="mb-6 text-sm">© 2023 Ardrino. All rights reserved.</p>
      <div class="flex justify-center gap-8">
        <a href="https://page.genspark.site/page/toolu_018FAsr8tEaaoNYqD3fu3Zox/futuristic_vfx_portfolio.html#" class="text-gray-400 hover:text-primary transition-colors">Privacy Policy</a>
        <a href="https://page.genspark.site/page/toolu_018FAsr8tEaaoNYqD3fu3Zox/futuristic_vfx_portfolio.html#" class="text-gray-400 hover:text-primary transition-colors">Terms of Service</a>
      </div>
    </div>
  </footer>
  
  <!-- Audio elements for sound effects -->
  <audio id="sound-click" preload="auto">
    <source src="https://cdn.jsdelivr.net/gh/soundeffects/se@main/ui/click.mp3" type="audio/mpeg">
  </audio>
  
  <audio id="sound-whoosh" preload="auto">
    <source src="https://cdn.jsdelivr.net/gh/soundeffects/se@main/ui/whoosh.mp3" type="audio/mpeg">
  </audio>
  
  <audio id="sound-hover" preload="auto">
    <source src="https://cdn.jsdelivr.net/gh/soundeffects/se@main/ui/hover.mp3" type="audio/mpeg">
  </audio>
  
  <!-- Scripts -->
  <script src="./ARDRINO _ Visionary 3D Storyteller &amp; VFX Artist_files/three.min.js.download"></script>
  <script src="./ARDRINO _ Visionary 3D Storyteller &amp; VFX Artist_files/gsap.min.js.download"></script>
  <script src="./ARDRINO _ Visionary 3D Storyteller &amp; VFX Artist_files/ScrollTrigger.min.js.download"></script>
  <script>
    // Register GSAP plugins
    gsap.registerPlugin(ScrollTrigger);
    
    // DOM Elements
    const cursorOuter = document.querySelector('.cursor-outer');
    const cursorInner = document.querySelector('.cursor-inner');
    const magneticElements = document.querySelectorAll('.magnetic-element');
    const menuToggle = document.getElementById('menu-toggle');
    const closeMenu = document.getElementById('close-menu');
    const mobileMenu = document.getElementById('mobile-menu');
    const navLinks = document.querySelectorAll('.nav-link');
    const projectFilterBtns = document.querySelectorAll('.project-filter-btn');
    const projectCards = document.querySelectorAll('.project-card');
    const contactForm = document.getElementById('contact-form');
    
    // Sound effects
    const sounds = {
      click: document.getElementById('sound-click'),
      whoosh: document.getElementById('sound-whoosh'),
      hover: document.getElementById('sound-hover')
    };
    
    // Global state
    let mouseX = 0;
    let mouseY = 0;
    let isFormSubmitting = false;
    
    // Initialize
    document.addEventListener('DOMContentLoaded', () => {
      initCustomCursor();
      initMagneticElements();
      initMobileMenu();
      initProjectFilter();
      initFormSubmission();
      initParticles();
      init3DCharacter();
      initAnimations();
      initSoundEffects();
      
      // Prevent cursor flickering when hovering over links
      document.querySelectorAll('a, button').forEach(el => {
        el.addEventListener('mouseenter', () => {
          cursorOuter.classList.add('link-hover');
        });
        
        el.addEventListener('mouseleave', () => {
          cursorOuter.classList.remove('link-hover');
        });
      });
    });
    
    // Custom cursor
    function initCustomCursor() {
      document.addEventListener('mousemove', (e) => {
        mouseX = e.clientX;
        mouseY = e.clientY;
        
        // Use requestAnimationFrame for smooth cursor movement
        requestAnimationFrame(updateCursorPosition);
      });
      
      document.addEventListener('mousedown', () => {
        cursorOuter.style.transform = 'translate(-50%, -50%) scale(0.8)';
        cursorInner.style.transform = 'translate(-50%, -50%) scale(0.6)';
      });
      
      document.addEventListener('mouseup', () => {
        cursorOuter.style.transform = 'translate(-50%, -50%) scale(1)';
        cursorInner.style.transform = 'translate(-50%, -50%) scale(1)';
      });
      
      // Hide default cursor
      document.body.style.cursor = 'none';
    }
    
    function updateCursorPosition() {
      cursorOuter.style.left = `${mouseX}px`;
      cursorOuter.style.top = `${mouseY}px`;
      
      cursorInner.style.left = `${mouseX}px`;
      cursorInner.style.top = `${mouseY}px`;
    }
    
    // Magnetic elements effect
    function initMagneticElements() {
      magneticElements.forEach(element => {
        element.addEventListener('mousemove', (e) => {
          const rect = element.getBoundingClientRect();
          const x = e.clientX - rect.left - rect.width / 2;
          const y = e.clientY - rect.top - rect.height / 2;
          
          gsap.to(element, {
            duration: 0.3,
            x: x * 0.3,
            y: y * 0.3,
            ease: 'power2.out'
          });
        });
        
        element.addEventListener('mouseleave', () => {
          gsap.to(element, {
            duration: 0.5,
            x: 0,
            y: 0,
            ease: 'elastic.out(1, 0.3)'
          });
        });
      });
    }
    
    // Mobile menu functionality
    function initMobileMenu() {
      menuToggle.addEventListener('click', () => {
        mobileMenu.classList.remove('hidden');
        gsap.fromTo(mobileMenu, {
          opacity: 0,
          y: -50
        }, {
          opacity: 1,
          y: 0,
          duration: 0.5,
          ease: 'power3.out'
        });
        playSound('click');
      });
      
      closeMenu.addEventListener('click', () => {
        gsap.to(mobileMenu, {
          opacity: 0,
          y: -50,
          duration: 0.3,
          ease: 'power3.in',
          onComplete: () => {
            mobileMenu.classList.add('hidden');
          }
        });
        playSound('click');
      });
      
      navLinks.forEach(link => {
        link.addEventListener('click', () => {
          if (window.innerWidth < 768) {
            gsap.to(mobileMenu, {
              opacity: 0,
              y: -50,
              duration: 0.3,
              ease: 'power3.in',
              onComplete: () => {
                mobileMenu.classList.add('hidden');
              }
            });
          }
          playSound('click');
        });
      });
    }
    
    // Project filtering
    function initProjectFilter() {
      projectFilterBtns.forEach(btn => {
        btn.addEventListener('click', () => {
          // Remove active class from all buttons
          projectFilterBtns.forEach(b => b.classList.remove('active'));
          
          // Add active class to clicked button
          btn.classList.add('active');
          
          const filter = btn.getAttribute('data-filter');
          
          // Filter projects
          projectCards.forEach(card => {
            const categories = card.getAttribute('data-category').split(',');
            
            if (filter === 'all' || categories.includes(filter)) {
              gsap.to(card, {
                opacity: 1,
                scale: 1,
                duration: 0.5,
                ease: 'power3.out',
                clearProps: 'all'
              });
            } else {
              gsap.to(card, {
                opacity: 0.3,
                scale: 0.95,
                duration: 0.5,
                ease: 'power3.out'
              });
            }
          });
          
          playSound('click');
        });
      });
    }
    
    // Form submission
    function initFormSubmission() {
      contactForm.addEventListener('submit', (e) => {
        e.preventDefault();
        
        if (isFormSubmitting) return;
        isFormSubmitting = true;
        
        // Get form data
        const formData = new FormData(contactForm);
        const data = Object.fromEntries(formData.entries());
        
        // Simulate form submission
        const submitBtn = contactForm.querySelector('button[type="submit"]');
        const originalText = submitBtn.innerHTML;
        
        submitBtn.innerHTML = 'SENDING...';
        submitBtn.disabled = true;
        
        setTimeout(() => {
          // Success message
          contactForm.innerHTML = `
            <div class="text-center">
              <div class="text-6xl mb-4">
                <i class="fas fa-check-circle glow-text"></i>
              </div>
              <h3 class="text-2xl mb-4">Message Sent Successfully!</h3>
              <p class="mb-6">Thank you for reaching out. I'll be in touch soon to discuss your project.</p>
              <button type="button" id="reset-form" class="btn magnetic-element">SEND ANOTHER MESSAGE</button>
            </div>
          `;
          
          document.getElementById('reset-form').addEventListener('click', () => {
            window.location.reload();
          });
          
          playSound('whoosh');
          isFormSubmitting = false;
        }, 2000);
      });
    }
    
    // Particle background
    function initParticles() {
      const canvas = document.getElementById('particles-canvas');
      const ctx = canvas.getContext('2d');
      
      let particles = [];
      const particleCount = 100;
      
      // Set canvas size
      function setCanvasSize() {
        canvas.width = window.innerWidth;
        canvas.height = window.innerHeight;
      }
      
      setCanvasSize();
      window.addEventListener('resize', setCanvasSize);
      
      // Particle class
      class Particle {
        constructor() {
          this.x = Math.random() * canvas.width;
          this.y = Math.random() * canvas.height;
          this.size = Math.random() * 2 + 0.5;
          this.speedX = Math.random() * 0.5 - 0.25;
          this.speedY = Math.random() * 0.5 - 0.25;
          this.color = `rgba(0, ${Math.floor(Math.random() * 200) + 55}, ${Math.floor(Math.random() * 200) + 55}, ${Math.random() * 0.5 + 0.1})`;
        }
        
        update() {
          this.x += this.speedX;
          this.y += this.speedY;
          
          if (this.x < 0 || this.x > canvas.width) {
            this.speedX = -this.speedX;
          }
          
          if (this.y < 0 || this.y > canvas.height) {
            this.speedY = -this.speedY;
          }
        }
        
        draw() {
          ctx.fillStyle = this.color;
          ctx.beginPath();
          ctx.arc(this.x, this.y, this.size, 0, Math.PI * 2);
          ctx.fill();
        }
      }
      
      // Create particles
      function createParticles() {
        particles = [];
        for (let i = 0; i < particleCount; i++) {
          particles.push(new Particle());
        }
      }
      
      createParticles();
      
      // Animation loop
      function animate() {
        ctx.clearRect(0, 0, canvas.width, canvas.height);
        
        for (let i = 0; i < particles.length; i++) {
          particles[i].update();
          particles[i].draw();
          
          // Connect particles
          for (let j = i; j < particles.length; j++) {
            const dx = particles[i].x - particles[j].x;
            const dy = particles[i].y - particles[j].y;
            const distance = Math.sqrt(dx * dx + dy * dy);
            
            if (distance < 100) {
              ctx.beginPath();
              ctx.strokeStyle = `rgba(0, 255, 255, ${0.1 * (1 - distance / 100)})`;
              ctx.lineWidth = 0.2;
              ctx.moveTo(particles[i].x, particles[i].y);
              ctx.lineTo(particles[j].x, particles[j].y);
              ctx.stroke();
            }
          }
        }
        
        requestAnimationFrame(animate);
      }
      
      animate();
    }
    
    // 3D character in hero section
    function init3DCharacter() {
      const container = document.getElementById('ardrino-model');
      const width = container.clientWidth;
      const height = container.clientHeight;
      
      // Three.js setup
      const scene = new THREE.Scene();
      const camera = new THREE.PerspectiveCamera(75, width / height, 0.1, 1000);
      camera.position.z = 5;
      
      const renderer = new THREE.WebGLRenderer({ alpha: true, antialias: true });
      renderer.setSize(width, height);
      renderer.setPixelRatio(window.devicePixelRatio);
      container.appendChild(renderer.domElement);
      
      // Lighting
      const ambientLight = new THREE.AmbientLight(0x404040, 2);
      scene.add(ambientLight);
      
      const directionalLight = new THREE.DirectionalLight(0x00ffff, 1);
      directionalLight.position.set(1, 1, 1);
      scene.add(directionalLight);
      
      const pointLight = new THREE.PointLight(0xff00ff, 1, 100);
      pointLight.position.set(-2, 1, 3);
      scene.add(pointLight);
      
      // Create a simple placeholder geometry (to be replaced with your character)
      const geometry = new THREE.TorusKnotGeometry(1, 0.3, 100, 16);
      const material = new THREE.MeshPhongMaterial({
        color: 0x00ffff,
        emissive: 0x101020,
        shininess: 100,
        wireframe: true
      });
      
      const torusKnot = new THREE.Mesh(geometry, material);
      scene.add(torusKnot);
      
      // Add particle system around the model
      const particlesGeometry = new THREE.BufferGeometry();
      const particlesCount = 1000;
      const posArray = new Float32Array(particlesCount * 3);
      
      for (let i = 0; i < particlesCount * 3; i++) {
        posArray[i] = (Math.random() - 0.5) * 10;
      }
      
      particlesGeometry.setAttribute('position', new THREE.BufferAttribute(posArray, 3));
      
      const particlesMaterial = new THREE.PointsMaterial({
        size: 0.02,
        color: 0x00ffff,
        transparent: true,
        opacity: 0.8
      });
      
      const particlesMesh = new THREE.Points(particlesGeometry, particlesMaterial);
      scene.add(particlesMesh);
      
      // Window resize handler
      window.addEventListener('resize', () => {
        const newWidth = container.clientWidth;
        const newHeight = container.clientHeight;
        
        camera.aspect = newWidth / newHeight;
        camera.updateProjectionMatrix();
        
        renderer.setSize(newWidth, newHeight);
      });
      
      // Animation loop
      function animate() {
        requestAnimationFrame(animate);
        
        torusKnot.rotation.x += 0.01;
        torusKnot.rotation.y += 0.01;
        
        particlesMesh.rotation.x += 0.0005;
        particlesMesh.rotation.y += 0.0005;
        
        renderer.render(scene, camera);
      }
      
      animate();
      
      // Mouse movement effect
      document.addEventListener('mousemove', (event) => {
        const x = (event.clientX / window.innerWidth) * 2 - 1;
        const y = -(event.clientY / window.innerHeight) * 2 + 1;
        
        gsap.to(torusKnot.rotation, {
          x: y * 0.5,
          y: x * 0.5,
          duration: 1
        });
      });
    }
    
    // GSAP animations
    function initAnimations() {
      // Navbar animation
      gsap.from('nav', {
        y: -100,
        opacity: 0,
        duration: 1,
        ease: 'power3.out'
      });
      
      // Hero section animations
      gsap.from('.hero-title', {
        y: 100,
        opacity: 0,
        duration: 1,
        delay: 0.2,
        ease: 'power3.out'
      });
      
      gsap.from('.hero-subtitle', {
        y: 100,
        opacity: 0,
        duration: 1,
        delay: 0.4,
        ease: 'power3.out'
      });
      
      gsap.from('.btn', {
        y: 50,
        opacity: 0,
        duration: 1,
        delay: 0.6,
        ease: 'power3.out',
        stagger: 0.2
      });
      
      // Parallax scrolling for sections
      document.querySelectorAll('.section').forEach((section, index) => {
        if (index > 0) { // Skip hero section
          ScrollTrigger.create({
            trigger: section,
            start: 'top bottom',
            end: 'bottom top',
            scrub: true,
            onUpdate: (self) => {
              section.style.backgroundPositionY = `${self.progress * 50}%`;
            }
          });
        }
      });
      
      // Animate story panels on scroll
      const storyPanels = document.querySelectorAll('.story-panel');
      
      ScrollTrigger.create({
        trigger: '.story-scroll-container',
        start: 'top center',
        end: 'bottom center',
        scrub: true,
        onUpdate: (self) => {
          const progress = self.progress;
          gsap.to('.story-panels', {
            y: -progress * (storyPanels.length - 1) * 400,
            ease: 'none',
            duration: 0.1
          });
        }
      });
      
      // Fade in animations for sections
      gsap.utils.toArray('.section > .container').forEach(section => {
        gsap.from(section, {
          scrollTrigger: {
            trigger: section,
            start: 'top 80%',
            end: 'bottom 20%',
            toggleActions: 'play none none reverse'
          },
          y: 100,
          opacity: 0,
          duration: 1,
          ease: 'power3.out'
        });
      });
    }
    
    // Sound effects
    function initSoundEffects() {
      document.querySelectorAll('[data-sound]').forEach(element => {
        element.addEventListener('click', () => {
          const soundType = element.getAttribute('data-sound');
          playSound(soundType);
        });
        
        element.addEventListener('mouseenter', () => {
          playSound('hover', 0.2);
        });
      });
    }
    
    function playSound(type, volume = 1) {
      if (!sounds[type]) return;
      
      const sound = sounds[type];
      sound.volume = volume;
      sound.currentTime = 0;
      sound.play().catch(e => console.log('Audio playback error:', e));
    }
  </script>


    <script id="html_badge_script1">
        window.__genspark_remove_badge_link = "https://www.genspark.ai/api/html_badge/" +
            "remove_badge?token=To%2FBnjzloZ3UfQdcSaYfDgmU%2F0E2iilNtmxcclZIwE256r8HqXVfLrMBK%2FPryFuumPn7aqga1%2BBcxxLeDwxYg0yIG5UNU%2B3eBxwNkvptF7XgvV4fhzlYA2EhGnbXfJz5%2BDPh6SqIwv2I65z6zm9sQKaVna0mU1H7Mzp8AVHRJyh740K3xOAMClgPSuWsF0KMniSPHn90PwcX0mN01iWQ%2BjqTDGx1WpDKyIjyrMwgFgydP4xI34MGpbIYeMKbFyzOqYEEtSmblXPW9%2FeaqV3Ai7XOL1yBptwmG6V%2FokNKOuQa5WIUsIHIjxkxdcWYCC%2B1H2Ug0oTWV4569n%2BxK%2Fp8yghLXlD13KbKFx5ISZIj4zsXBO5KY7Ytvo%2FT0CPJz3JRKhUwzbFK%2Bh%2BpSUvSFFRE%2FkE4DGlgfpNH0DO4%2FDqMRLZr6sDxeSvgnYudUgBsN%2BcGST%2Fwqp8UpIre5rb6sOz1pl2v%2BBhTO7Pxzc8K9DBMhdWxexcXfZaBcC3yH0VMm1OU9Cf2E4NxsLWAQm8EUvQCdVT20CHls3DNlJty5Zl%2B4MU2mIUfc8y8h8823%2BWtd7I6p%2FtzO0ZF%2BP668CBHfOS1foFkYiTdxk0iad0XMCoyDa4%3D";
        window.__genspark_locale = "en-US";
        window.__genspark_token = "To/BnjzloZ3UfQdcSaYfDgmU/0E2iilNtmxcclZIwE256r8HqXVfLrMBK/PryFuumPn7aqga1+BcxxLeDwxYg0yIG5UNU+3eBxwNkvptF7XgvV4fhzlYA2EhGnbXfJz5+DPh6SqIwv2I65z6zm9sQKaVna0mU1H7Mzp8AVHRJyh740K3xOAMClgPSuWsF0KMniSPHn90PwcX0mN01iWQ+jqTDGx1WpDKyIjyrMwgFgydP4xI34MGpbIYeMKbFyzOqYEEtSmblXPW9/eaqV3Ai7XOL1yBptwmG6V/okNKOuQa5WIUsIHIjxkxdcWYCC+1H2Ug0oTWV4569n+xK/p8yghLXlD13KbKFx5ISZIj4zsXBO5KY7Ytvo/T0CPJz3JRKhUwzbFK+h+pSUvSFFRE/kE4DGlgfpNH0DO4/DqMRLZr6sDxeSvgnYudUgBsN+cGST/wqp8UpIre5rb6sOz1pl2v+BhTO7Pxzc8K9DBMhdWxexcXfZaBcC3yH0VMm1OU9Cf2E4NxsLWAQm8EUvQCdVT20CHls3DNlJty5Zl+4MU2mIUfc8y8h8823+Wtd7I6p/tzO0ZF+P668CBHfOS1foFkYiTdxk0iad0XMCoyDa4=";
    </script>
    
        <script id="html_badge_script2" src="./ARDRINO _ Visionary 3D Storyteller &amp; VFX Artist_files/html_badge.js.download"></script><button class="genspark-badge-button"><svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 14 14" fill="none">
<path d="M11.3412 0H2.65879C1.19038 0 0 1.19038 0 2.65879V11.3412C0 12.8096 1.19038 14 2.65879 14H11.3412C12.8096 14 14 12.8096 14 11.3412V2.65879C14 1.19038 12.8096 0 11.3412 0Z" fill="white"></path>
<path d="M11.7403 10.7031H2.29243C2.09641 10.7031 1.9375 10.862 1.9375 11.0581V11.8033C1.9375 11.9993 2.09641 12.1582 2.29243 12.1582H11.7403C11.9363 12.1582 12.0952 11.9993 12.0952 11.8033V11.0581C12.0952 10.862 11.9363 10.7031 11.7403 10.7031Z" fill="#232425"></path>
<path d="M5.09178 9.18166C5.03494 9.18166 4.98695 9.13998 4.97811 9.08314C4.60803 6.63655 4.34025 6.42056 1.91134 6.05427C1.83682 6.0429 1.78125 5.97848 1.78125 5.9027C1.78125 5.82691 1.83682 5.7625 1.91134 5.75113C4.32762 5.3861 4.54235 5.17011 4.90738 2.7551C4.91874 2.68058 4.98316 2.625 5.05894 2.625C5.13473 2.625 5.19914 2.68058 5.21051 2.7551C5.57554 5.17011 5.79153 5.3861 8.20655 5.75113C8.28107 5.7625 8.33664 5.82691 8.33664 5.9027C8.33664 5.97848 8.28107 6.0429 8.20655 6.05427C5.78017 6.42056 5.57302 6.63655 5.20546 9.08314C5.19662 9.13871 5.14862 9.18166 5.09178 9.18166Z" fill="#232425"></path>
<path d="M9.70174 5.949C9.66637 5.949 9.63606 5.92248 9.63101 5.88711C9.39986 4.35878 9.23188 4.22363 7.71492 3.99501C7.66818 3.98743 7.63281 3.94828 7.63281 3.90028C7.63281 3.85355 7.66692 3.81313 7.71492 3.80555C9.2243 3.5782 9.35945 3.44305 9.5868 1.93366C9.59438 1.88693 9.63354 1.85156 9.68153 1.85156C9.72827 1.85156 9.76869 1.88567 9.77627 1.93366C10.0036 3.44305 10.1388 3.5782 11.6482 3.80555C11.6949 3.81313 11.7302 3.85228 11.7302 3.90028C11.7302 3.94702 11.6962 3.98743 11.6482 3.99501C10.1325 4.22363 10.0024 4.35878 9.77247 5.88711C9.76742 5.92248 9.73711 5.949 9.70174 5.949Z" fill="#232425"></path>
<path d="M9.69114 9.76325C9.6684 9.76325 9.64946 9.74683 9.64567 9.7241C9.49915 8.75152 9.39179 8.66563 8.42679 8.52038C8.39648 8.51533 8.375 8.49007 8.375 8.45975C8.375 8.42944 8.39648 8.40418 8.42679 8.39912C9.38673 8.25387 9.47262 8.16798 9.61788 7.20804C9.62293 7.17772 9.64819 7.15625 9.6785 7.15625C9.70882 7.15625 9.73408 7.17772 9.73913 7.20804C9.88439 8.16798 9.97028 8.25387 10.9302 8.39912C10.9605 8.40418 10.982 8.42944 10.982 8.45975C10.982 8.49007 10.9605 8.51533 10.9302 8.52038C9.96523 8.66563 9.88312 8.75152 9.73661 9.7241C9.73282 9.74683 9.71387 9.76325 9.69114 9.76325Z" fill="#232425"></path>
</svg> Made with Genspark</button><div class="genspark-modal">
    <div class="genspark-modal-content">
      <button class="genspark-close"><svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 14 14" fill="none">
<path d="M11 3L3 11M3 3L11 11" stroke="#232425" stroke-linecap="round" stroke-linejoin="round"></path>
</svg></button>
      <h3 class="genspark-title">This page was created by users with AI.</h3>
      <a class="genspark-report" href="mailto:support@genspark.ai?subject=Report%20inappropriate%20content&amp;body=Current%20URL:%20https://page.genspark.site/page/toolu_018FAsr8tEaaoNYqD3fu3Zox/futuristic_vfx_portfolio.html">Report inappropriate content.</a>
      <p class="genspark-info">Page owner with Plus Plan can remove badge.</p>
      <div class="genspark-buttons">
        <button class="genspark-remove-btn">Remove Badge</button>
        <button class="genspark-go-btn">Go to Genspark</button>
      </div>
    </div>
  </div>
        </body></html>
