---
title: "Inderjeet Singh"
---

{{< rawhtml >}}
<style>
/* Modern CSS Variables - Enhanced for AI Research Scientist */
:root {
  --gradient-primary: linear-gradient(135deg, #2563eb 0%, #1e40af 100%);
  --gradient-secondary: linear-gradient(135deg, #06b6d4 0%, #0891b2 100%);
  --gradient-accent: linear-gradient(135deg, #8b5cf6 0%, #7c3aed 100%);
  --gradient-research: linear-gradient(135deg, #059669 0%, #047857 100%);
  --shadow-soft: 0 10px 40px rgba(0, 0, 0, 0.08);
  --shadow-hover: 0 20px 60px rgba(0, 0, 0, 0.15);
  --shadow-research: 0 8px 32px rgba(37, 99, 235, 0.15);
  --animation-smooth: cubic-bezier(0.4, 0, 0.2, 1);
  --border-radius-lg: 24px;
  --border-radius-xl: 32px;
  --academic-blue: #1e40af;
  --academic-teal: #0891b2;
  --academic-purple: #7c3aed;
  --academic-green: #047857;
}

/* Global Animations */
@keyframes fadeInUp {
  from {
    opacity: 0;
    transform: translateY(30px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

@keyframes float {
  0%, 100% { transform: translateY(0); }
  50% { transform: translateY(-10px); }
}

@keyframes gradientShift {
  0% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
  100% { background-position: 0% 50%; }
}

@keyframes pulse {
  0%, 100% { transform: scale(1); opacity: 1; }
  50% { transform: scale(1.05); opacity: 0.9; }
}

/* Enhanced Hero Section */
.hero-section {
  min-height: 100vh;
  display: flex;
  align-items: center;
  padding: 40px 20px;
  position: relative;
  overflow: hidden;
  background: var(--theme);
}

/* Better background for light mode */
[data-theme="light"] .hero-section {
  background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%);
}

[data-theme="dark"] .hero-section {
  background: linear-gradient(135deg, var(--theme) 0%, var(--code-bg) 100%);
}

.hero-section::before {
  content: '';
  position: absolute;
  top: -50%;
  right: -50%;
  width: 200%;
  height: 200%;
  background: radial-gradient(circle, rgba(102, 126, 234, 0.1) 0%, transparent 70%);
  animation: float 20s ease-in-out infinite;
}

.hero-container {
  max-width: 1600px;
  margin: 0 auto;
  display: grid;
  grid-template-columns: 1fr 2fr;
  gap: 60px;
  align-items: center;
  position: relative;
  z-index: 1;
  animation: fadeInUp 1s ease-out;
}

.hero-image {
  text-align: center;
  animation: fadeInUp 1s ease-out 0.2s both;
}

.hero-image img {
  width: 240px;
  height: 240px;
  border-radius: 50%;
  object-fit: cover;
  border: 4px solid transparent;
  background: linear-gradient(var(--theme), var(--theme)) padding-box,
              var(--gradient-primary) border-box;
  box-shadow: var(--shadow-soft);
  transition: all 0.5s var(--animation-smooth);
  animation: float 6s ease-in-out infinite;
}

.hero-image img:hover {
  transform: scale(1.05) rotate(5deg);
  box-shadow: var(--shadow-hover);
}

.hero-content {
  animation: fadeInUp 1s ease-out 0.4s both;
}

.hero-content h1 {
  font-size: 3.5em;
  font-weight: 700;
  margin-bottom: 15px;
  letter-spacing: -2px;
  background: var(--gradient-primary);
  background-size: 200% 200%;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  animation: gradientShift 5s ease infinite;
  position: relative;
}

.hero-subtitle {
  font-size: 1.4em;
  color: var(--secondary);
  margin-bottom: 25px;
  line-height: 1.7;
  opacity: 0.95;
  font-weight: 400;
}

.hero-subtitle strong {
  color: var(--primary);
  position: relative;
  display: inline-block;
}

.hero-subtitle strong::after {
  content: '';
  position: absolute;
  bottom: -2px;
  left: 0;
  width: 0;
  height: 2px;
  background: var(--gradient-accent);
  transition: width 0.3s ease;
}

.hero-subtitle strong:hover::after {
  width: 100%;
}

.hero-links {
  display: flex;
  gap: 15px;
  flex-wrap: wrap;
  margin-top: 30px;
}

.hero-link {
  padding: 12px 24px;
  border: 2px solid transparent;
  background: linear-gradient(var(--theme), var(--theme)) padding-box,
              var(--gradient-primary) border-box;
  color: var(--primary);
  text-decoration: none;
  border-radius: 30px;
  font-size: 0.95em;
  font-weight: 500;
  transition: all 0.3s var(--animation-smooth);
  position: relative;
  overflow: hidden;
}

.hero-link::before {
  content: '';
  position: absolute;
  top: 0;
  left: -100%;
  width: 100%;
  height: 100%;
  background: var(--gradient-primary);
  transition: left 0.3s ease;
  z-index: -1;
}

.hero-link:hover {
  color: white;
  transform: translateY(-2px);
  box-shadow: 0 10px 30px rgba(102, 126, 234, 0.3);
}

.hero-link:hover::before {
  left: 0;
}

.main-content {
  max-width: 1600px;
  margin: 0 auto;
  padding: 0 40px;
}

.section {
  margin-bottom: 80px;
  opacity: 0;
  transform: translateY(30px);
  transition: all 0.8s var(--animation-smooth);
}

.section.visible {
  opacity: 1;
  transform: translateY(0);
}

.section-header {
  display: flex;
  align-items: center;
  margin-bottom: 40px;
  padding-bottom: 15px;
  position: relative;
}

.section-header::after {
  content: '';
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100px;
  height: 3px;
  background: var(--gradient-primary);
  border-radius: 2px;
  transition: width 0.5s ease;
}

.section:hover .section-header::after {
  width: 200px;
}

.section-title {
  font-size: 2.2em;
  font-weight: 600;
  background: var(--gradient-primary);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  margin: 0;
}

.stats-row {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 20px;
  margin-bottom: 40px;
}

.stat-card {
  text-align: center;
  padding: 30px 20px;
  background: rgba(255, 255, 255, 0.05);
  backdrop-filter: blur(10px);
  border: 1px solid rgba(255, 255, 255, 0.1);
  border-radius: 20px;
  transition: all 0.3s var(--animation-smooth);
  cursor: pointer;
  position: relative;
  overflow: hidden;
}

/* Light mode adjustments */
[data-theme="light"] .stat-card {
  background: rgba(255, 255, 255, 0.7);
  border: 1px solid rgba(0, 0, 0, 0.1);
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.05);
}

.stat-card::before {
  content: '';
  position: absolute;
  top: -50%;
  left: -50%;
  width: 200%;
  height: 200%;
  background: radial-gradient(circle, rgba(102, 126, 234, 0.1) 0%, transparent 70%);
  opacity: 0;
  transition: opacity 0.3s ease;
}

.stat-card:hover {
  transform: translateY(-10px) scale(1.05);
  box-shadow: var(--shadow-hover);
}

.stat-card:hover::before {
  opacity: 1;
}

.stat-number {
  font-size: 2.5em;
  font-weight: 700;
  background: var(--gradient-primary);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  margin-bottom: 10px;
  animation: pulse 2s ease-in-out infinite;
}

.stat-label {
  font-size: 0.95em;
  color: var(--secondary);
  font-weight: 500;
  text-transform: uppercase;
  letter-spacing: 1px;
}

.about-text {
  font-size: 1.2em;
  line-height: 1.8;
  color: var(--secondary);
  margin-bottom: 40px;
  position: relative;
  padding-left: 20px;
}

.about-text::before {
  content: '';
  position: absolute;
  left: 0;
  top: 0;
  width: 3px;
  height: 100%;
  background: var(--gradient-primary);
  border-radius: 2px;
}

.research-areas {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 30px;
  margin-top: 50px;
}

.research-item {
  padding: 35px;
  background: rgba(255, 255, 255, 0.04);
  backdrop-filter: blur(15px);
  border-radius: var(--border-radius-lg);
  border: 1px solid rgba(255, 255, 255, 0.12);
  transition: all 0.4s var(--animation-smooth);
  position: relative;
  overflow: hidden;
  cursor: pointer;
  box-shadow: var(--shadow-soft);
}

[data-theme="light"] .research-item {
  background: rgba(255, 255, 255, 0.8);
  border: 1px solid rgba(0, 0, 0, 0.08);
  box-shadow: 0 2px 15px rgba(0, 0, 0, 0.04);
}

.research-item::before {
  content: '';
  position: absolute;
  top: 0;
  left: -100%;
  width: 100%;
  height: 100%;
  background: linear-gradient(90deg, transparent, rgba(102, 126, 234, 0.1), transparent);
  transition: left 0.6s ease;
}

.research-item:hover {
  transform: translateY(-8px) scale(1.02);
  box-shadow: 0 25px 50px rgba(37, 99, 235, 0.25);
  border-color: rgba(37, 99, 235, 0.4);
}

.research-item:hover::before {
  left: 100%;
}

.research-item h3 {
  font-size: 1.3em;
  font-weight: 700;
  background: var(--gradient-primary);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  margin-bottom: 18px;
  line-height: 1.4;
}

.research-item p {
  font-size: 1em;
  line-height: 1.7;
  margin: 0;
  opacity: 0.92;
  color: var(--secondary);
}

.news-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 25px;
  margin-top: 40px;
}

.news-card {
  padding: 30px;
  background: linear-gradient(135deg, rgba(102, 126, 234, 0.05) 0%, rgba(245, 87, 108, 0.05) 100%);
  border-radius: 20px;
  border: 1px solid rgba(255, 255, 255, 0.1);
  position: relative;
  overflow: hidden;
  transition: all 0.3s var(--animation-smooth);
  cursor: pointer;
}

[data-theme="light"] .news-card {
  background: linear-gradient(135deg, rgba(102, 126, 234, 0.03) 0%, rgba(245, 87, 108, 0.03) 100%);
  border: 1px solid rgba(0, 0, 0, 0.08);
}

.news-card::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 4px;
  height: 100%;
  background: var(--gradient-primary);
  transform: translateX(-4px);
  transition: transform 0.3s ease;
}

.news-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 15px 40px rgba(102, 126, 234, 0.15);
}

.news-card:hover::before {
  transform: translateX(0);
}

.news-date {
  font-size: 0.85em;
  font-weight: 600;
  background: var(--gradient-accent);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  margin-bottom: 12px;
  text-transform: uppercase;
  letter-spacing: 1px;
}

.news-title {
  font-weight: 700;
  font-size: 1.1em;
  margin-bottom: 10px;
  line-height: 1.4;
  color: var(--primary);
}

.news-desc {
  font-size: 0.95em;
  color: var(--secondary);
  line-height: 1.6;
  opacity: 0.9;
}

.publications-list {
  display: flex;
  flex-direction: column;
  gap: 25px;
  margin-top: 40px;
}

.pub-item {
  padding: 30px;
  background: rgba(255, 255, 255, 0.02);
  backdrop-filter: blur(10px);
  border-radius: 20px;
  border: 1px solid rgba(255, 255, 255, 0.1);
  position: relative;
  overflow: hidden;
  transition: all 0.4s var(--animation-smooth);
}

[data-theme="light"] .pub-item {
  background: rgba(255, 255, 255, 0.9);
  border: 1px solid rgba(0, 0, 0, 0.08);
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.03);
}

.pub-item::before {
  content: '';
  position: absolute;
  top: -100%;
  left: -100%;
  width: 300%;
  height: 300%;
  background: radial-gradient(circle, rgba(102, 126, 234, 0.05) 0%, transparent 60%);
  transition: all 0.6s ease;
}

.pub-item:hover {
  transform: translateY(-5px);
  box-shadow: 0 15px 40px rgba(102, 126, 234, 0.15);
  border-color: rgba(102, 126, 234, 0.3);
}

.pub-item:hover::before {
  top: -50%;
  left: -50%;
}

.pub-title {
  font-weight: 700;
  font-size: 1.1em;
  margin-bottom: 12px;
  line-height: 1.5;
  color: var(--primary);
}

.pub-authors {
  font-size: 0.95em;
  color: var(--secondary);
  margin-bottom: 8px;
  opacity: 0.9;
}

.pub-venue {
  font-size: 0.95em;
  font-style: italic;
  background: var(--gradient-accent);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  margin-bottom: 15px;
  font-weight: 500;
}

.pub-links {
  display: flex;
  gap: 12px;
  flex-wrap: wrap;
}

.pub-links a {
  font-size: 0.85em;
  padding: 6px 16px;
  border: 2px solid transparent;
  background: linear-gradient(var(--theme), var(--theme)) padding-box,
              var(--gradient-primary) border-box;
  color: var(--primary);
  text-decoration: none;
  border-radius: 20px;
  font-weight: 600;
  transition: all 0.3s var(--animation-smooth);
}

.pub-links a:hover {
  background: var(--gradient-primary);
  color: white;
  transform: translateY(-2px);
  box-shadow: 0 5px 15px rgba(102, 126, 234, 0.3);
}

.award-badge {
  display: inline-block;
  background: var(--gradient-secondary);
  color: white;
  padding: 4px 12px;
  border-radius: 20px;
  font-size: 0.8em;
  font-weight: 600;
  margin-left: 10px;
  animation: pulse 2s ease-in-out infinite;
}

.contact-box {
  background: linear-gradient(135deg, rgba(102, 126, 234, 0.1) 0%, rgba(245, 87, 108, 0.1) 100%);
  padding: 60px 40px;
  border-radius: 30px;
  text-align: center;
  margin-top: 60px;
  position: relative;
  overflow: hidden;
  border: 1px solid rgba(255, 255, 255, 0.1);
}

[data-theme="light"] .contact-box {
  background: linear-gradient(135deg, rgba(102, 126, 234, 0.05) 0%, rgba(245, 87, 108, 0.05) 100%);
  border: 1px solid rgba(0, 0, 0, 0.08);
}

.contact-box::before {
  content: '';
  position: absolute;
  top: -50%;
  left: -50%;
  width: 200%;
  height: 200%;
  background: radial-gradient(circle, rgba(255, 255, 255, 0.1) 0%, transparent 70%);
  animation: float 15s ease-in-out infinite;
}

.contact-box h2 {
  position: relative;
  z-index: 1;
}

.contact-text {
  font-size: 1.2em;
  line-height: 1.8;
  margin-bottom: 30px;
  position: relative;
  z-index: 1;
  opacity: 0.9;
}

.view-more-link {
  display: inline-block;
  margin-top: 30px;
  padding: 12px 30px;
  background: var(--gradient-primary);
  color: white;
  text-decoration: none;
  font-weight: 600;
  border-radius: 30px;
  transition: all 0.3s var(--animation-smooth);
  position: relative;
  overflow: hidden;
}

.view-more-link::before {
  content: '';
  position: absolute;
  top: 50%;
  left: 50%;
  width: 0;
  height: 0;
  background: rgba(255, 255, 255, 0.2);
  border-radius: 50%;
  transform: translate(-50%, -50%);
  transition: width 0.6s, height 0.6s;
}

.view-more-link:hover {
  transform: translateY(-3px);
  box-shadow: 0 10px 30px rgba(102, 126, 234, 0.3);
}

.view-more-link:hover::before {
  width: 300px;
  height: 300px;
}

/* Special styling for contact button */
.contact-button {
  display: inline-block;
  padding: 14px 32px;
  background: var(--gradient-primary);
  color: white !important;
  text-decoration: none;
  border-radius: 30px;
  font-size: 1em;
  font-weight: 600;
  transition: all 0.3s var(--animation-smooth);
  position: relative;
  overflow: hidden;
  border: none;
}

.contact-button:hover {
  transform: translateY(-3px);
  box-shadow: 0 10px 30px rgba(102, 126, 234, 0.3);
  color: white !important;
}

/* Enhanced Mobile Responsiveness */
@media (max-width: 768px) {
  .hero-section {
    min-height: 100vh;
    padding: 20px;
  }
  
  .hero-container {
    grid-template-columns: 1fr;
    text-align: center;
    gap: 40px;
    max-width: 100%;
  }
  
  .hero-content h1 {
    font-size: 2.5em;
    line-height: 1.2;
  }
  
  .hero-subtitle {
    font-size: 1.1em;
    margin-bottom: 20px;
  }
  
  .hero-links {
    justify-content: center;
    gap: 10px;
  }
  
  .hero-link {
    padding: 10px 20px;
    font-size: 0.9em;
  }
  
  .main-content {
    padding: 0 20px;
  }
  
  .stats-row {
    grid-template-columns: repeat(2, 1fr);
    gap: 15px;
    margin-bottom: 30px;
  }
  
  .stat-card {
    padding: 25px 15px;
  }
  
  .stat-number {
    font-size: 2.2em;
  }
  
  .stat-label {
    font-size: 0.9em;
  }
  
  .research-areas,
  .news-grid {
    grid-template-columns: 1fr;
    gap: 20px;
  }
  
  .section-title {
    font-size: 1.8em;
  }
  
  .pub-item {
    padding: 20px;
  }
  
  .contact-box {
    padding: 40px 20px;
  }
  
  /* Enhanced mobile achievements section */
  .achievements-section {
    margin-top: 40px !important;
    padding: 35px 20px !important;
  }
  
  .achievement-title {
    font-size: 1.4em !important;
    margin-bottom: 30px !important;
  }
  
  .achievements-grid {
    grid-template-columns: 1fr !important;
    gap: 20px !important;
  }
  
  .achievement-card {
    flex-direction: column !important;
    text-align: center !important;
    gap: 20px !important;
    padding: 25px 20px !important;
  }
  
  .achievement-icon {
    font-size: 3em !important;
  }
  
  .achievement-content h4 {
    font-size: 1.2em !important;
    margin-bottom: 12px !important;
  }
  
  .achievement-content p,
  .achievement-content div {
    font-size: 0.95em !important;
    text-align: center !important;
  }
  
  .academic-summary {
    margin-top: 30px !important;
    padding: 20px !important;
  }
  
  .academic-summary p {
    font-size: 1em !important;
    line-height: 1.6 !important;
  }
}

/* Tablet optimizations */
@media (min-width: 769px) and (max-width: 1024px) {
  .hero-container {
    max-width: 95%;
    gap: 50px;
  }
  
  .main-content {
    max-width: 95%;
    padding: 0 30px;
  }
  
  .stats-row {
    grid-template-columns: repeat(4, 1fr);
    gap: 18px;
  }
  
  .research-areas {
    grid-template-columns: repeat(2, 1fr);
    gap: 22px;
  }
  
  .news-grid {
    grid-template-columns: repeat(2, 1fr);
    gap: 22px;
  }
}

/* Large desktop optimizations */
@media (min-width: 1400px) {
  .hero-container {
    max-width: 1800px;
  }
  
  .main-content {
    max-width: 1800px;
  }
  
  .stats-row {
    grid-template-columns: repeat(4, 1fr);
    gap: 25px;
  }
  
  .research-areas {
    grid-template-columns: repeat(3, 1fr);
  }
  
  .news-grid {
    grid-template-columns: repeat(3, 1fr);
  }
}

/* Smooth Scrollbar */
::-webkit-scrollbar {
  width: 10px;
}

::-webkit-scrollbar-track {
  background: var(--theme);
}

::-webkit-scrollbar-thumb {
  background: var(--gradient-primary);
  border-radius: 5px;
}

::-webkit-scrollbar-thumb:hover {
  background: var(--gradient-secondary);
}
</style>

<!-- Hero Section with Profile -->
<section class="hero-section">
  <div class="hero-container">
    <div class="hero-image">
      <img src="/images/profile.png" alt="Inderjeet Singh">
    </div>
    <div class="hero-content">
      <h1>Inderjeet Singh</h1>
      <p class="hero-subtitle">
        Senior AI Research Scientist at Fujitsu Research of Europe<br>
        Pioneering <strong>Trustworthy AI Systems</strong> • <strong>LLM/LMM Safety</strong> • <strong>Agentic RAG</strong> • <strong>Vision Robustness</strong>
      </p>
      <div class="hero-links">
        <a href="https://scholar.google.com/citations?user=eoxiMqQAAAAJ&hl=en" class="hero-link">Google Scholar</a>
        <a href="https://github.com/intherejeet" class="hero-link">GitHub</a>
        <a href="https://www.linkedin.com/in/intherejeet/" class="hero-link">LinkedIn</a>
        <a href="mailto:inderjeet.ieor@gmail.com" class="hero-link">Email</a>
      </div>
    </div>
  </div>
</section>

<div class="main-content">
  <!-- About & Stats -->
  <section class="section" id="about">
    <div class="section-header">
      <h2 class="section-title">About</h2>
    </div>
    
    <p class="about-text">
      I am a Senior AI Research Scientist at Fujitsu Research of Europe with <strong>6+ years</strong> of experience advancing the frontiers of AI Security and Trustworthy AI systems. 
      My research specializes in <strong>LLM/LMM safety</strong>, <strong>Agentic RAG architectures</strong>, and <strong>adversarial robustness</strong> for vision systems. 
      I develop formal security guarantees and safety frameworks that enable reliable AI deployment in mission-critical environments. 
      With <strong>10+ patents</strong> (including 1 granted: US12183118) and publications in premier venues (ACL'25, BMVC'24 Oral, ECCV'24, ACML'24), 
      I translate cutting-edge theoretical advances into practical, enterprise-ready solutions. Currently seeking opportunities to lead transformative trustworthy-AI initiatives.
    </p>
    
    <div class="stats-row">
      <div class="stat-card">
        <div class="stat-number">10+</div>
        <div class="stat-label">Patents Filed</div>
      </div>
      <div class="stat-card">
        <div class="stat-number">10+</div>
        <div class="stat-label">Publications</div>
      </div>
      <div class="stat-card">
        <div class="stat-number">2</div>
        <div class="stat-label">Academic Medals</div>
      </div>
      <div class="stat-card">
        <div class="stat-number">AIR 2</div>
        <div class="stat-label">GATE 2017</div>
      </div>
    </div>
    
    <!-- Enhanced Academic & Sports Excellence Section -->
    <div class="achievements-section" style="margin-top: 50px; padding: 50px 40px; background: linear-gradient(135deg, rgba(37, 99, 235, 0.05) 0%, rgba(139, 92, 246, 0.05) 100%); border-radius: var(--border-radius-xl); position: relative; overflow: hidden; border: 1px solid rgba(255, 255, 255, 0.1); animation: fadeInUp 1s ease-out 0.6s both; box-shadow: var(--shadow-research);">
      <div class="achievement-bg-decoration" style="position: absolute; top: -100px; right: -100px; width: 300px; height: 300px; background: radial-gradient(circle, rgba(37, 99, 235, 0.1) 0%, transparent 70%); animation: float 10s ease-in-out infinite;"></div>
      <div class="achievement-bg-decoration-2" style="position: absolute; bottom: -50px; left: -50px; width: 200px; height: 200px; background: radial-gradient(circle, rgba(139, 92, 246, 0.08) 0%, transparent 70%); animation: float 12s ease-in-out infinite reverse;"></div>
      
      <h3 class="achievement-title" style="font-size: 1.8em; margin-bottom: 40px; background: var(--gradient-primary); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text; font-weight: 700; text-align: center; position: relative; z-index: 2;">Beyond Research: Leadership & Excellence</h3>
      
      <div class="achievements-grid" style="display: grid; grid-template-columns: repeat(auto-fit, minmax(350px, 1fr)); gap: 30px; position: relative; z-index: 2;">
        <!-- Badminton Achievement -->
        <div class="achievement-card badminton-card" style="display: flex; align-items: center; gap: 25px; padding: 30px; background: rgba(255, 255, 255, 0.07); backdrop-filter: blur(15px); border-radius: var(--border-radius-lg); transition: all 0.4s ease; cursor: pointer; border: 1px solid rgba(37, 99, 235, 0.1); position: relative; overflow: hidden;" onmouseover="this.style.transform='translateY(-8px) scale(1.02)'; this.style.boxShadow='0 15px 40px rgba(37, 99, 235, 0.25)'; this.style.borderColor='rgba(37, 99, 235, 0.3)'" onmouseout="this.style.transform='translateY(0) scale(1)'; this.style.boxShadow='none'; this.style.borderColor='rgba(37, 99, 235, 0.1)'">
          <div class="achievement-icon" style="font-size: 3.5em; filter: drop-shadow(0 8px 16px rgba(0,0,0,0.15)); transition: transform 0.3s ease;" onmouseover="this.style.transform='rotate(10deg) scale(1.1)'" onmouseout="this.style.transform='rotate(0deg) scale(1)'">🏸</div>
          <div class="achievement-content">
            <h4 style="background: var(--gradient-primary); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text; font-size: 1.3em; font-weight: 700; margin-bottom: 10px; line-height: 1.3;">National Level Badminton</h4>
            <p style="font-size: 1em; color: var(--secondary); line-height: 1.6; opacity: 0.9; margin: 0;">Represented university at National West & Inter-Zonal Tournaments, demonstrating competitive excellence at the highest collegiate level (2015-16)</p>
          </div>
        </div>
        
        <!-- Sports Medals Achievement -->
        <div class="achievement-card medals-card" style="display: flex; align-items: center; gap: 25px; padding: 30px; background: rgba(255, 255, 255, 0.07); backdrop-filter: blur(15px); border-radius: var(--border-radius-lg); transition: all 0.4s ease; cursor: pointer; border: 1px solid rgba(139, 92, 246, 0.1); position: relative; overflow: hidden;" onmouseover="this.style.transform='translateY(-8px) scale(1.02)'; this.style.boxShadow='0 15px 40px rgba(139, 92, 246, 0.25)'; this.style.borderColor='rgba(139, 92, 246, 0.3)'" onmouseout="this.style.transform='translateY(0) scale(1)'; this.style.boxShadow='none'; this.style.borderColor='rgba(139, 92, 246, 0.1)'">
          <div class="achievement-icon" style="font-size: 3.5em; filter: drop-shadow(0 8px 16px rgba(0,0,0,0.15)); transition: transform 0.3s ease;" onmouseover="this.style.transform='rotate(-10deg) scale(1.1)'" onmouseout="this.style.transform='rotate(0deg) scale(1)'">🏅</div>
          <div class="achievement-content">
            <h4 style="background: var(--gradient-accent); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text; font-size: 1.3em; font-weight: 700; margin-bottom: 10px; line-height: 1.3;">Championship Medals</h4>
            <div style="font-size: 1em; color: var(--secondary); line-height: 1.6; opacity: 0.9;">
              <div style="margin-bottom: 6px;"><span style="color: #ffd700; font-weight: 600;">🥇 Gold:</span> Kho-Kho Championship (Udghosh-2017, IIT Kanpur)</div>
              <div><span style="color: #c0c0c0; font-weight: 600;">🥈 2x Silver:</span> Badminton Inter-Collegiate (2015-17)</div>
            </div>
          </div>
        </div>
      </div>
      
      <!-- Academic Excellence Summary -->
      <div class="academic-summary" style="margin-top: 40px; text-align: center; padding: 25px; background: rgba(255, 255, 255, 0.03); border-radius: var(--border-radius-lg); position: relative; z-index: 2;">
        <p style="font-size: 1.1em; color: var(--secondary); line-height: 1.7; opacity: 0.9; max-width: 800px; margin: 0 auto;">
          Balancing competitive sports excellence with academic rigor has shaped my approach to research—bringing 
          <strong style="color: var(--academic-blue);">strategic thinking</strong>, 
          <strong style="color: var(--academic-purple);">performance optimization</strong>, and 
          <strong style="color: var(--academic-teal);">collaborative leadership</strong> 
          to every AI research challenge.
        </p>
      </div>
    </div>
  </section>

  <!-- Research Areas -->
  <section class="section" id="research">
    <div class="section-header">
      <h2 class="section-title">Research Focus</h2>
    </div>
    
    <div class="research-areas">
      <div class="research-item">
        <h3>Trustworthy Multimodal Agentic RAG</h3>
        <p>Exploring advanced Retrieval Augmented Generation (RAG) systems that integrate multimodal information and agentic capabilities. This work aims to enhance the trustworthiness and safety of these systems through innovative approaches, without compromising their performance in complex information retrieval and generation tasks.</p>
      </div>
      
      <div class="research-item">
        <h3>LLM/LMM Security & Safety</h3>
        <p>Developing LLM/LMM Vulnerability Scanner & Guardrail Framework for safety control in LLM applications. Created first safety benchmark (43k+ attacks) via novel auto red-teaming.</p>
      </div>
      
      <div class="research-item">
        <h3>AI Robustness & Adversarial ML</h3>
        <p>Advanced Deep Metric Learning with adversarial robustness, achieving SOTA with +2.95% Recall@1 (clean), 2.12x robustness (multi-distribution) for real-world deployments.</p>
      </div>
      
      <div class="research-item">
        <h3>LLM Disparity Assessment</h3>
        <p>Investigating novel methodologies for efficiently auditing and identifying disparities in Large Language Models to promote fairness and ethical AI. This research focuses on developing techniques for nuanced disparity assessment.</p>
      </div>
    </div>
  </section>

  <!-- Recent Highlights -->
  <section class="section" id="news">
    <div class="section-header">
      <h2 class="section-title">Recent Highlights</h2>
    </div>
    
    <div class="news-grid">
      <div class="news-card">
        <div class="news-date">2025</div>
        <div class="news-title">Paper Accepted at ACL 2025</div>
        <div class="news-desc">DIESEL: A Lightweight Inference-Time Safety Enhancement for Language Models accepted at the premier NLP conference.</div>
      </div>
      
      <div class="news-card">
        <div class="news-date">2024</div>
        <div class="news-title">Oral Presentation at BMVC 2024</div>
        <div class="news-desc">Presented ATLANTIS framework for automated targeted language-guided augmentation training (acceptance rate <3%).</div>
      </div>
      
      <div class="news-card">
        <div class="news-date">2024</div>
        <div class="news-title">Paper at ECCV 2024</div>
        <div class="news-desc">MONTRAGE: Monitoring Training for Attribution of Generative Diffusion Models accepted.</div>
      </div>
      
      <div class="news-card">
        <div class="news-date">2024</div>
        <div class="news-title">Long Talk at ACML 2024</div>
        <div class="news-desc">Presented work on Advancing Deep Metric Learning With Adversarial Robustness.</div>
      </div>
    </div>
  </section>

  <!-- Selected Publications -->
  <section class="section" id="publications">
    <div class="section-header">
      <h2 class="section-title">Selected Publications</h2>
    </div>
    
    <div class="publications-list">
      <div class="pub-item">
        <div class="pub-title">
          DIESEL: A Lightweight Inference-Time Safety Enhancement for Language Models
        </div>
        <div class="pub-authors">B Ganon, A Zolfi, O Hofman, I Singh, H Kojima, Y Elovici, A Shabtai</div>
        <div class="pub-venue">ACL 2025 - Annual Meeting of the Association for Computational Linguistics</div>
        <div class="pub-links">
          <a href="#">Paper</a>
        </div>
      </div>
      
      <div class="pub-item">
        <div class="pub-title">
          ATLANTIS: A Framework for Automated Targeted Language-guided Augmentation Training for Robust Image Search
          <span class="award-badge">Oral</span>
        </div>
        <div class="pub-authors">I Singh*, R Vainshtein, A Zolfi, A Shabtai, J Brokman, O Hofman, K Fumiyoshi, T Kentarou, H Kojima</div>
        <div class="pub-venue">BMVC 2024 - British Machine Vision Conference</div>
        <div class="pub-links">
          <a href="#">Paper</a>
          <a href="#">Code</a>
        </div>
      </div>
      
      <div class="pub-item">
        <div class="pub-title">
          MONTRAGE: Monitoring Training for Attribution of Generative Diffusion Models
        </div>
        <div class="pub-authors">J Brokman, O Hofman, R Vainshtein, A Giloni, T Shimizu, I Singh, O Rachmil, A Zolfi, A Shabtai, Y Unno, H Kojima</div>
        <div class="pub-venue">ECCV 2024 - European Conference on Computer Vision</div>
        <div class="pub-links">
          <a href="#">Paper</a>
        </div>
      </div>
    </div>
    
    <a href="https://scholar.google.com/citations?user=eoxiMqQAAAAJ&hl=en" target="_blank" class="view-more-link">View All Publications on Google Scholar →</a>
  </section>

  <!-- Contact -->
  <section class="section" id="contact">
    <div class="contact-box">
      <h2 style="font-size: 1.8em; margin-bottom: 20px;">Let's Collaborate</h2>
      <p class="contact-text">
        I welcome opportunities to collaborate on challenges at the intersection of AI advancement and responsible deployment. 
        With expertise in LLM/LMM safety, Agentic RAG, and trustworthy AI systems, let's explore how we can push boundaries 
        while maintaining the highest standards of safety and reliability.
      </p>
      <a href="mailto:inderjeet.ieor@gmail.com" class="contact-button">Get in Touch</a>
    </div>
  </section>
</div>

<script>
// Enhanced JavaScript with animations
document.addEventListener('DOMContentLoaded', function() {
  // Smooth scrolling for navigation
  const links = document.querySelectorAll('a[href^="#"]');
  
  links.forEach(link => {
    link.addEventListener('click', function(e) {
      e.preventDefault();
      const targetId = this.getAttribute('href').substring(1);
      const targetElement = document.getElementById(targetId);
      
      if (targetElement) {
        const headerOffset = 80;
        const elementPosition = targetElement.getBoundingClientRect().top;
        const offsetPosition = elementPosition + window.pageYOffset - headerOffset;
        
        window.scrollTo({
          top: offsetPosition,
          behavior: 'smooth'
        });
      }
    });
  });
  
  // Intersection Observer for scroll animations
  const observerOptions = {
    threshold: 0.1,
    rootMargin: '0px 0px -50px 0px'
  };
  
  const observer = new IntersectionObserver(function(entries) {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        entry.target.classList.add('visible');
      }
    });
  }, observerOptions);
  
  // Observe all sections
  const sections = document.querySelectorAll('.section');
  sections.forEach(section => {
    observer.observe(section);
  });
  
  // Parallax effect for hero image only
  const heroImage = document.querySelector('.hero-image img');
  const heroBefore = document.querySelector('.hero-section::before');
  
  window.addEventListener('scroll', () => {
    const scrolled = window.pageYOffset;
    
    if (scrolled < window.innerHeight) {
      // Only animate the image, not the entire section
      heroImage.style.transform = `scale(${1 + scrolled * 0.0002})`;
      
      // Move the background decoration
      if (heroBefore) {
        heroBefore.style.transform = `translateY(${scrolled * 0.3}px)`;
      }
    }
  });
  
  // Add loading animation
  document.body.style.opacity = '0';
  window.addEventListener('load', () => {
    document.body.style.transition = 'opacity 1s ease';
    document.body.style.opacity = '1';
  });
  
  // Dynamic gradient movement on mouse move
  const gradientElements = document.querySelectorAll('.hero-content h1, .section-title');
  
  document.addEventListener('mousemove', (e) => {
    const x = e.clientX / window.innerWidth;
    const y = e.clientY / window.innerHeight;
    
    gradientElements.forEach(el => {
      el.style.backgroundPosition = `${x * 100}% ${y * 100}%`;
    });
  });
});
</script>

{{< /rawhtml >}} 