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
  min-height: 85vh;
  display: flex;
  align-items: center;
  padding: 30px 20px;
  position: relative;
  overflow: hidden;
  background: var(--theme);
}

/* Hero section background */
.hero-section {
  background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%);
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
  gap: 40px;
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
  margin-bottom: 10px;
  letter-spacing: -2px;
  background: var(--gradient-primary);
  background-size: 200% 200%;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  animation: gradientShift 5s ease infinite;
  position: relative;
  line-height: 1.1;
}

.hero-subtitle {
  font-size: 1.4em;
  color: var(--secondary);
  margin-bottom: 20px;
  line-height: 1.5;
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
  gap: 12px;
  flex-wrap: wrap;
  margin-top: 20px;
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
  margin-bottom: 60px;
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
  margin-bottom: 30px;
  padding-bottom: 12px;
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
  gap: 16px;
  margin-bottom: 30px;
}

.stat-card {
  text-align: center;
  padding: 24px 16px;
  background: rgba(255, 255, 255, 0.7);
  backdrop-filter: blur(10px);
  border: 1px solid rgba(0, 0, 0, 0.1);
  border-radius: 20px;
  transition: all 0.3s var(--animation-smooth);
  cursor: pointer;
  position: relative;
  overflow: hidden;
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
  font-size: 1.1em;
  line-height: 1.6;
  color: var(--secondary);
  margin-bottom: 30px;
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
  gap: 24px;
  margin-top: 35px;
}

.research-item {
  padding: 28px;
  background: rgba(255, 255, 255, 0.8);
  backdrop-filter: blur(15px);
  border-radius: var(--border-radius-lg);
  border: 1px solid rgba(0, 0, 0, 0.08);
  transition: all 0.4s var(--animation-smooth);
  position: relative;
  overflow: hidden;
  cursor: pointer;
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
  margin-bottom: 14px;
  line-height: 1.3;
}

.research-item p {
  font-size: 0.95em;
  line-height: 1.5;
  margin: 0;
  opacity: 0.92;
  color: var(--secondary);
}

.news-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 20px;
  margin-top: 30px;
}

.news-card {
  padding: 24px;
  background: linear-gradient(135deg, rgba(102, 126, 234, 0.03) 0%, rgba(245, 87, 108, 0.03) 100%);
  border-radius: 20px;
  border: 1px solid rgba(0, 0, 0, 0.08);
  position: relative;
  overflow: hidden;
  transition: all 0.3s var(--animation-smooth);
  cursor: pointer;
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
  margin-bottom: 8px;
  text-transform: uppercase;
  letter-spacing: 1px;
}

.news-title {
  font-weight: 700;
  font-size: 1.1em;
  margin-bottom: 8px;
  line-height: 1.3;
  color: var(--primary);
}

.news-desc {
  font-size: 0.9em;
  color: var(--secondary);
  line-height: 1.5;
  opacity: 0.9;
}

.publications-list {
  display: flex;
  flex-direction: column;
  gap: 20px;
  margin-top: 30px;
}

.pub-item {
  padding: 24px;
  background: rgba(255, 255, 255, 0.9);
  backdrop-filter: blur(10px);
  border-radius: 20px;
  border: 1px solid rgba(0, 0, 0, 0.08);
  position: relative;
  overflow: hidden;
  transition: all 0.4s var(--animation-smooth);
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
  margin-bottom: 10px;
  line-height: 1.4;
  color: var(--primary);
}

.pub-authors {
  font-size: 0.9em;
  color: var(--secondary);
  margin-bottom: 6px;
  opacity: 0.9;
}

.pub-venue {
  font-size: 0.9em;
  font-style: italic;
  background: var(--gradient-accent);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  margin-bottom: 12px;
  font-weight: 500;
}

.pub-links {
  display: flex;
  gap: 10px;
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
  background: linear-gradient(135deg, rgba(102, 126, 234, 0.05) 0%, rgba(245, 87, 108, 0.05) 100%);
  padding: 40px 30px;
  border-radius: 30px;
  text-align: center;
  margin-top: 40px;
  position: relative;
  overflow: hidden;
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
  font-size: 1.1em;
  line-height: 1.6;
  margin-bottom: 24px;
  position: relative;
  z-index: 1;
  opacity: 0.9;
}

.view-more-link {
  display: inline-block;
  margin-top: 24px;
  padding: 10px 24px;
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
    min-height: 80vh;
    padding: 16px;
  }
  
  .hero-container {
    grid-template-columns: 1fr;
    text-align: center;
    gap: 30px;
    max-width: 100%;
  }
  
  .hero-content h1 {
    font-size: 2.5em;
    line-height: 1.1;
    margin-bottom: 8px;
  }
  
  .hero-subtitle {
    font-size: 1.1em;
    margin-bottom: 16px;
    line-height: 1.4;
  }
  
  .hero-links {
    justify-content: center;
    gap: 8px;
    margin-top: 16px;
  }
  
  .hero-link {
    padding: 8px 16px;
    font-size: 0.9em;
  }
  
  .main-content {
    padding: 0 16px;
  }
  
  .section {
    margin-bottom: 40px;
  }
  
  .section-header {
    margin-bottom: 20px;
    padding-bottom: 10px;
  }
  
  .section-title {
    font-size: 1.8em;
  }
  
  .stats-row {
    grid-template-columns: repeat(2, 1fr);
    gap: 12px;
    margin-bottom: 24px;
  }
  
  .stat-card {
    padding: 20px 12px;
  }
  
  .stat-number {
    font-size: 2em;
  }
  
  .stat-label {
    font-size: 0.85em;
  }
  
  .about-text {
    font-size: 1em;
    line-height: 1.5;
    margin-bottom: 24px;
    padding-left: 16px;
  }
  
  .research-areas {
    grid-template-columns: 1fr;
    gap: 16px;
    margin-top: 24px;
  }
  
  .research-item {
    padding: 20px;
  }
  
  .research-item h3 {
    font-size: 1.2em;
    margin-bottom: 10px;
  }
  
  .research-item p {
    font-size: 0.9em;
    line-height: 1.4;
  }
  
  .news-grid {
    grid-template-columns: 1fr;
    gap: 16px;
    margin-top: 24px;
  }
  
  .news-card {
    padding: 20px;
  }
  
  .news-title {
    font-size: 1em;
    margin-bottom: 6px;
  }
  
  .news-desc {
    font-size: 0.85em;
  }
  
  .publications-list {
    gap: 16px;
    margin-top: 24px;
  }
  
  .pub-item {
    padding: 20px;
  }
  
  .pub-title {
    font-size: 1em;
    margin-bottom: 8px;
  }
  
  .pub-authors,
  .pub-venue {
    font-size: 0.85em;
  }
  
  .contact-box {
    padding: 32px 20px;
    margin-top: 32px;
  }
  
  .contact-text {
    font-size: 1em;
    margin-bottom: 20px;
  }
  
  /* Enhanced mobile achievements section */
  .achievements-section {
    margin-top: 32px !important;
    padding: 28px 16px !important;
  }
  
  .achievement-title {
    font-size: 1.3em !important;
    margin-bottom: 24px !important;
  }
  
  .achievements-grid {
    grid-template-columns: 1fr !important;
    gap: 16px !important;
  }
  
  .achievement-card {
    flex-direction: column !important;
    text-align: center !important;
    gap: 16px !important;
    padding: 20px 16px !important;
  }
  
  .achievement-icon {
    font-size: 2.8em !important;
  }
  
  .achievement-content h4 {
    font-size: 1.1em !important;
    margin-bottom: 10px !important;
  }
  
  .achievement-content p,
  .achievement-content div {
    font-size: 0.9em !important;
    text-align: center !important;
    line-height: 1.4 !important;
  }
  
  /* Enhanced mobile styling for academic medals */
  .university-gold-card,
  .institute-silver-card {
    border-width: 1px !important;
    box-shadow: 0 4px 16px rgba(255, 193, 7, 0.15) !important;
  }
  
  .institute-silver-card {
    box-shadow: 0 4px 16px rgba(169, 169, 169, 0.15) !important;
  }
  
  .academic-summary {
    margin-top: 24px !important;
    padding: 16px !important;
  }
  
  .academic-summary p {
    font-size: 0.95em !important;
    line-height: 1.5 !important;
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

/* Smooth scrolling for anchor links */
html {
  scroll-behavior: smooth;
}

/* Adjust scroll padding to account for fixed header */
section {
  scroll-margin-top: 80px;
}

/* Header styling */
.header {
  background: rgba(255, 255, 255, 0.95);
  border-bottom: 1px solid rgba(0, 0, 0, 0.1);
  backdrop-filter: blur(10px);
  position: sticky;
  top: 0;
  z-index: 100;
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
        Senior Research Scientist (AI), Fujitsu Research of Europe<br>
        <strong>Machine Learning Security</strong> • <strong>LLM/LMM Safety & Security</strong> • <strong>Trustworthy Multimodal AI</strong> • <strong>Adversarial Robustness</strong>
      </p>
      <div class="hero-links">
        <a href="https://scholar.google.com/citations?user=eoxiMqQAAAAJ&hl=en" class="hero-link">Google Scholar</a>
        <a href="https://github.com/intherejeet" class="hero-link">GitHub</a>
        <a href="https://www.linkedin.com/in/intherejeet/" class="hero-link">LinkedIn</a>
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
      I am a Senior Research Scientist (AI) at Fujitsu Research of Europe, UK, with close to 6 years of experience developing cutting-edge methodologies for <strong>machine learning security</strong> and <strong>trustworthy artificial intelligence</strong>. 
      My research addresses fundamental theoretical and practical challenges in <strong>large language/multimodal model safety</strong>, <strong>multimodal retrieval-augmented generation systems</strong>, and <strong>adversarial robustness</strong> across computer vision and natural language processing domains. 
      I develop formal verification frameworks, automated assessment methodologies, and safety architectures that provide theoretical guarantees for AI systems in safety-critical applications. 
      My work has resulted in <strong>10+ filed patents</strong> (including granted US patent 12183118) and publications in premier venues including ACL 2025, BMVC 2024 (Oral presentation, <3% acceptance rate), ECCV 2024, and ACML 2024. 
      Previously at NEC Labs Japan (2019-2023), I established foundational contributions to adversarial machine learning and AI system security assessment methodologies.
    </p>
    
    <div class="stats-row">
      <div class="stat-card">
        <div class="stat-number">10+</div>
        <div class="stat-label">Patents Filed</div>
      </div>
      <div class="stat-card">
        <div class="stat-number">12+</div>
        <div class="stat-label">Publications</div>
      </div>
      <div class="stat-card">
        <div class="stat-number">6</div>
        <div class="stat-label">Years Research</div>
      </div>
      <div class="stat-card">
        <div class="stat-number">40K+</div>
        <div class="stat-label">Safety Benchmarks</div>
      </div>
    </div>
    
    <!-- Enhanced Academic & Sports Excellence Section -->
    <div class="achievements-section" style="margin-top: 40px; padding: 40px 32px; background: linear-gradient(135deg, rgba(37, 99, 235, 0.05) 0%, rgba(139, 92, 246, 0.05) 100%); border-radius: var(--border-radius-xl); position: relative; overflow: hidden; border: 1px solid rgba(255, 255, 255, 0.1); animation: fadeInUp 1s ease-out 0.6s both; box-shadow: var(--shadow-research);">
      <div class="achievement-bg-decoration" style="position: absolute; top: -100px; right: -100px; width: 300px; height: 300px; background: radial-gradient(circle, rgba(37, 99, 235, 0.1) 0%, transparent 70%); animation: float 10s ease-in-out infinite;"></div>
      <div class="achievement-bg-decoration-2" style="position: absolute; bottom: -50px; left: -50px; width: 200px; height: 200px; background: radial-gradient(circle, rgba(139, 92, 246, 0.08) 0%, transparent 70%); animation: float 12s ease-in-out infinite reverse;"></div>
      
      <h3 class="achievement-title" style="font-size: 1.6em; margin-bottom: 30px; background: var(--gradient-primary); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text; font-weight: 700; text-align: center; position: relative; z-index: 2;">Academic Excellence & Leadership</h3>
      
      <div class="achievements-grid" style="display: grid; grid-template-columns: repeat(auto-fit, minmax(350px, 1fr)); gap: 24px; position: relative; z-index: 2;">
        <!-- University Gold Medal Achievement -->
        <div class="achievement-card university-gold-card" style="display: flex; align-items: center; gap: 20px; padding: 24px; background: linear-gradient(135deg, rgba(255, 215, 0, 0.15) 0%, rgba(255, 193, 7, 0.08) 100%); backdrop-filter: blur(15px); border-radius: var(--border-radius-lg); transition: all 0.4s ease; cursor: pointer; border: 2px solid rgba(255, 193, 7, 0.3); position: relative; overflow: hidden; box-shadow: 0 8px 32px rgba(255, 193, 7, 0.2);" onmouseover="this.style.transform='translateY(-8px) scale(1.02)'; this.style.boxShadow='0 20px 50px rgba(255, 193, 7, 0.35)'; this.style.borderColor='rgba(255, 193, 7, 0.5)'" onmouseout="this.style.transform='translateY(0) scale(1)'; this.style.boxShadow='0 8px 32px rgba(255, 193, 7, 0.2)'; this.style.borderColor='rgba(255, 193, 7, 0.3)'">
          <div class="achievement-icon" style="font-size: 4em; filter: drop-shadow(0 8px 16px rgba(255, 193, 7, 0.3)); transition: transform 0.3s ease; animation: pulse 3s ease-in-out infinite;" onmouseover="this.style.transform='rotate(15deg) scale(1.15)'" onmouseout="this.style.transform='rotate(0deg) scale(1)'">🥇</div>
          <div class="achievement-content">
            <h4 style="background: linear-gradient(135deg, #ffd700 0%, #ffb700 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text; font-size: 1.35em; font-weight: 700; margin-bottom: 10px; line-height: 1.3;">University Gold Medal</h4>
            <p style="font-size: 1em; color: var(--secondary); line-height: 1.6; opacity: 0.95; margin: 0;"><strong style="color: #d4a017;">Highest Grade in University</strong><br/>Bachelor of Technology, Agricultural Engineering<br/>Vasantrao Naik Marathwada Krishi Vidyapeeth (2013-2017)</p>
          </div>
        </div>
        
        <!-- Institute Silver Medal Achievement -->
        <div class="achievement-card institute-silver-card" style="display: flex; align-items: center; gap: 20px; padding: 24px; background: linear-gradient(135deg, rgba(192, 192, 192, 0.15) 0%, rgba(169, 169, 169, 0.08) 100%); backdrop-filter: blur(15px); border-radius: var(--border-radius-lg); transition: all 0.4s ease; cursor: pointer; border: 2px solid rgba(169, 169, 169, 0.4); position: relative; overflow: hidden; box-shadow: 0 8px 32px rgba(169, 169, 169, 0.2);" onmouseover="this.style.transform='translateY(-8px) scale(1.02)'; this.style.boxShadow='0 20px 50px rgba(169, 169, 169, 0.35)'; this.style.borderColor='rgba(169, 169, 169, 0.6)'" onmouseout="this.style.transform='translateY(0) scale(1)'; this.style.boxShadow='0 8px 32px rgba(169, 169, 169, 0.2)'; this.style.borderColor='rgba(169, 169, 169, 0.4)'">
          <div class="achievement-icon" style="font-size: 4em; filter: drop-shadow(0 8px 16px rgba(169, 169, 169, 0.3)); transition: transform 0.3s ease; animation: pulse 3s ease-in-out infinite 1s;" onmouseover="this.style.transform='rotate(-15deg) scale(1.15)'" onmouseout="this.style.transform='rotate(0deg) scale(1)'">🥈</div>
          <div class="achievement-content">
            <h4 style="background: linear-gradient(135deg, #c0c0c0 0%, #a9a9a9 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text; font-size: 1.35em; font-weight: 700; margin-bottom: 10px; line-height: 1.3;">Institute Silver Medal</h4>
            <p style="font-size: 1em; color: var(--secondary); line-height: 1.6; opacity: 0.95; margin: 0;"><strong style="color: #708090;">Highest Grade in Postgraduate Batch</strong><br/>Master of Technology, Industrial Engineering & Operations Research<br/>Indian Institute of Technology Bombay (2017-2019)</p>
          </div>
        </div>
        
        <!-- Badminton Achievement -->
        <div class="achievement-card badminton-card" style="display: flex; align-items: center; gap: 20px; padding: 24px; background: rgba(255, 255, 255, 0.07); backdrop-filter: blur(15px); border-radius: var(--border-radius-lg); transition: all 0.4s ease; cursor: pointer; border: 1px solid rgba(37, 99, 235, 0.1); position: relative; overflow: hidden;" onmouseover="this.style.transform='translateY(-8px) scale(1.02)'; this.style.boxShadow='0 15px 40px rgba(37, 99, 235, 0.25)'; this.style.borderColor='rgba(37, 99, 235, 0.3)'" onmouseout="this.style.transform='translateY(0) scale(1)'; this.style.boxShadow='none'; this.style.borderColor='rgba(37, 99, 235, 0.1)'">
          <div class="achievement-icon" style="font-size: 3.5em; filter: drop-shadow(0 8px 16px rgba(0,0,0,0.15)); transition: transform 0.3s ease;" onmouseover="this.style.transform='rotate(10deg) scale(1.1)'" onmouseout="this.style.transform='rotate(0deg) scale(1)'">🏸</div>
          <div class="achievement-content">
            <h4 style="background: var(--gradient-primary); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text; font-size: 1.3em; font-weight: 700; margin-bottom: 10px; line-height: 1.3;">Badminton Nationals</h4>
            <p style="font-size: 1em; color: var(--secondary); line-height: 1.6; opacity: 0.9; margin: 0;">Played at National West Zone and Inter-Zonal Championships, demonstrating sustained excellence in competitive athletics at senior level (2015-16)</p>
          </div>
        </div>
        
        <!-- Sports Medals Achievement -->
        <div class="achievement-card medals-card" style="display: flex; align-items: center; gap: 20px; padding: 24px; background: rgba(255, 255, 255, 0.07); backdrop-filter: blur(15px); border-radius: var(--border-radius-lg); transition: all 0.4s ease; cursor: pointer; border: 1px solid rgba(139, 92, 246, 0.1); position: relative; overflow: hidden;" onmouseover="this.style.transform='translateY(-8px) scale(1.02)'; this.style.boxShadow='0 15px 40px rgba(139, 92, 246, 0.25)'; this.style.borderColor='rgba(139, 92, 246, 0.3)'" onmouseout="this.style.transform='translateY(0) scale(1)'; this.style.boxShadow='none'; this.style.borderColor='rgba(139, 92, 246, 0.1)'">
          <div class="achievement-icon" style="font-size: 3.5em; filter: drop-shadow(0 8px 16px rgba(0,0,0,0.15)); transition: transform 0.3s ease;" onmouseover="this.style.transform='rotate(-10deg) scale(1.1)'" onmouseout="this.style.transform='rotate(0deg) scale(1)'">🏆</div>
          <div class="achievement-content">
            <h4 style="background: var(--gradient-accent); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text; font-size: 1.3em; font-weight: 700; margin-bottom: 10px; line-height: 1.3;">Athletic Achievement Awards</h4>
            <div style="font-size: 1em; color: var(--secondary); line-height: 1.6; opacity: 0.9;">
              <div style="margin-bottom: 6px;"><span style="color: #ffd700; font-weight: 600;">🥇 Gold Medal:</span> Kho-Kho Championship (Udghosh-2017, IIT Kanpur)</div>
              <div><span style="color: #c0c0c0; font-weight: 600;">🥈 Silver Medals (2×):</span> Badminton Inter-Collegiate Championships (2015-17)</div>
            </div>
          </div>
        </div>
      </div>
      
      <!-- Academic Excellence Summary -->
      <div class="academic-summary" style="margin-top: 30px; text-align: center; padding: 20px; background: rgba(255, 255, 255, 0.03); border-radius: var(--border-radius-lg); position: relative; z-index: 2;">
        <p style="font-size: 1em; color: var(--secondary); line-height: 1.6; opacity: 0.9; max-width: 700px; margin: 0 auto;">
          The discipline and strategic thinking developed through competitive athletics have been instrumental in my research methodology—fostering 
          <strong style="color: var(--academic-blue);">systematic problem-solving</strong>, 
          <strong style="color: var(--academic-purple);">rigorous performance evaluation</strong>, and 
          <strong style="color: var(--academic-teal);">effective collaborative research</strong> 
          in machine learning and AI safety.
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
        <h3>Trustworthy Multimodal Agentic Systems</h3>
        <p>Investigating theoretical foundations and empirical methodologies for enhancing reliability and safety in multimodal agentic frameworks. Research focuses on developing trust mechanisms, safety architectures, and automated red-teaming methodologies for complex reasoning systems. Work includes comprehensive safety benchmark development with large-scale adversarial example generation for systematic evaluation.</p>
      </div>
      
      <div class="research-item">
        <h3>Large Language/Multimodal Model Security</h3>
        <p>Developing formal verification frameworks and automated vulnerability assessment methodologies for large language and multimodal models. Research encompasses systematic approaches to guardrail architectures, inference-time safety enhancement mechanisms, and distributed learning frameworks with privacy preservation for model fine-tuning.</p>
      </div>
      
      <div class="research-item">
        <h3>Adversarial Robustness and Deep Metric Learning</h3>
        <p>Advancing theoretical understanding and practical implementations of adversarial robustness in deep metric learning architectures. Research demonstrates state-of-the-art performance improvements (+2.95% Recall@1 under clean conditions, 2.12× robustness enhancement) across multi-distribution scenarios with applications to production-scale image retrieval systems.</p>
      </div>
      
      <div class="research-item">
        <h3>Algorithmic Disparity Assessment</h3>
        <p>Developing computational frameworks for systematic auditing and quantitative assessment of disparities in large language models. Research focuses on establishing theoretical foundations for bias detection through novel token-focused probing methodologies and developing principled mitigation strategies for equitable AI system behavior.</p>
      </div>
      
      <div class="research-item">
        <h3>Computer Vision Security</h3>
        <p>Investigating adversarial vulnerabilities and defense mechanisms in practical computer vision systems, with emphasis on face recognition and biometric authentication. Research encompasses physical-world attack methodologies, transferability analysis, and robustness enhancement techniques for real-world deployment scenarios.</p>
      </div>
      
      <div class="research-item">
        <h3>Training Data Attribution and Copyright Protection</h3>
        <p>Developing attribution methodologies for generative models to address copyright protection and intellectual property concerns. Research focuses on training data influence estimation, model provenance tracking, and automated monitoring frameworks for diffusion-based generative systems.</p>
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
        <div class="news-title">ACL 2025 Acceptance: LLM Safety Enhancement</div>
        <div class="news-desc">Research on lightweight inference-time safety mechanisms for language models accepted at the Annual Meeting of the Association for Computational Linguistics, addressing fundamental challenges in real-time LLM safety enhancement.</div>
      </div>
      
      <div class="news-card">
        <div class="news-date">2024</div>
        <div class="news-title">Patent Grant: US12183118</div>
        <div class="news-desc">Received patent grant for simultaneous adversarial attacks on multiple face recognition system components, establishing foundational intellectual property in AI security methodologies (September 30, 2024).</div>
      </div>
      
      <div class="news-card">
        <div class="news-date">2024</div>
        <div class="news-title">BMVC 2024 Acceptance: Oral Presentation</div>
        <div class="news-desc">Delivered oral presentation on multimodal robustness framework achieving state-of-the-art performance in image search applications at the British Machine Vision Conference (acceptance rate <3%).</div>
      </div>
      
      <div class="news-card">
        <div class="news-date">2024</div>
        <div class="news-title">ECCV 2024 Acceptance: Generative Model Attribution</div>
        <div class="news-desc">Contributed to research on training data attribution for generative diffusion models accepted at the European Conference on Computer Vision, addressing copyright protection in AI-generated content.</div>
      </div>
      
      <div class="news-card">
        <div class="news-date">2024</div>
        <div class="news-title">ACML 2024 Acceptance: Adversarial Robustness</div>
        <div class="news-desc">Presented theoretical advances in deep metric learning robustness with demonstrated improvements of +2.95% Recall@1 and 2.12× robustness enhancement at the Asian Conference on Machine Learning.</div>
      </div>
      
      <div class="news-card">
        <div class="news-date">2024</div>
        <div class="news-title">ACM ICSE Workshop Acceptance: LLM Vulnerability Analysis</div>
        <div class="news-desc">Published comprehensive analysis of existing LLM vulnerability scanning frameworks at the ACM International Conference on Software Engineering workshop on Responsible AI in Engineering.</div>
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
          <a href="https://arxiv.org/abs/2501.00000" target="_blank">Paper</a>
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
          <a href="https://arxiv.org/abs/2410.00000" target="_blank">Paper</a>
        </div>
      </div>
      
      <div class="pub-item">
        <div class="pub-title">
          MONTRAGE: Monitoring Training for Attribution of Generative Diffusion Models
        </div>
        <div class="pub-authors">J Brokman, O Hofman, R Vainshtein, A Giloni, T Shimizu, I Singh, O Rachmil, A Zolfi, A Shabtai, Y Unno, H Kojima</div>
        <div class="pub-venue">ECCV 2024 - European Conference on Computer Vision</div>
        <div class="pub-links">
          <a href="https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/09513.pdf" target="_blank">Paper</a>
        </div>
      </div>
      
      <div class="pub-item">
        <div class="pub-title">
          Advancing Deep Metric Learning With Adversarial Robustness
          <span class="award-badge">Long Talk</span>
        </div>
        <div class="pub-authors">I Singh*, K Kakizaki, T Araki</div>
        <div class="pub-venue">ACML 2024 - Asian Conference on Machine Learning</div>
        <div class="pub-links">
          <a href="https://arxiv.org/abs/2410.00000" target="_blank">Paper</a>
        </div>
      </div>
      
      <div class="pub-item">
        <div class="pub-title">
          Insights and Current Gaps in Open-Source LLM Vulnerability Scanners: A Comparative Analysis
        </div>
        <div class="pub-authors">J Brokman, O Hofman, O Rachmil, I Singh, PRS Aishvariya, V Pahuja, A Giloni, R Vainshtein, H Kojima</div>
        <div class="pub-venue">ACM ICSE 2024 - Workshop on Responsible AI in Engineering</div>
        <div class="pub-links">
          <a href="https://arxiv.org/abs/2404.00000" target="_blank">Paper</a>
        </div>
      </div>
      
      <div class="pub-item">
        <div class="pub-title">
          Simultaneous Adversarial Attacks On Multiple Face Recognition System Components
        </div>
        <div class="pub-authors">I Singh*, K Kakizaki, T Araki</div>
        <div class="pub-venue">arXiv preprint | Patent: US12183118 (Granted)</div>
        <div class="pub-links">
          <a href="https://arxiv.org/abs/2304.05048" target="_blank">Paper</a>
          <a href="https://patents.google.com/patent/US12183118B2" target="_blank">Patent</a>
        </div>
      </div>
      
      <div class="pub-item">
        <div class="pub-title">
          Powerful Physical Adversarial Examples Against Practical Face Recognition Systems
        </div>
        <div class="pub-authors">I Singh*, T Araki, K Kakizaki</div>
        <div class="pub-venue">WACV 2022 - IEEE/CVF Winter Conference on Applications of Computer Vision</div>
        <div class="pub-links">
          <a href="https://openaccess.thecvf.com/content/WACV2022/papers/Singh_Powerful_Physical_Adversarial_Examples_Against_Practical_Face_Recognition_Systems_WACV_2022_paper.pdf" target="_blank">Paper</a>
        </div>
      </div>
      
      <div class="pub-item">
        <div class="pub-title">
          Evaluating the Cybersecurity Risk of Real-world, Machine Learning Production Systems
        </div>
        <div class="pub-authors">R Bitton*, N Maman*, I Singh*, S Momiyama, Y Elovici, A Shabtai</div>
        <div class="pub-venue">ACM Computing Surveys 2023</div>
        <div class="pub-links">
          <a href="https://doi.org/10.1145/3558106" target="_blank">Paper</a>
        </div>
      </div>
      
      <div class="pub-item">
        <div class="pub-title">
          On Brightness Agnostic Adversarial Examples Against Face Recognition Systems
        </div>
        <div class="pub-authors">I Singh*, S Momiyama, K Kakizaki, T Araki</div>
        <div class="pub-venue">BIOSIG 2021 - International Conference of the Biometrics Special Interest Group</div>
        <div class="pub-links">
          <a href="https://ieeexplore.ieee.org/document/9548302" target="_blank">Paper</a>
        </div>
      </div>
    </div>
    
    <a href="https://scholar.google.com/citations?user=eoxiMqQAAAAJ&hl=en" target="_blank" class="view-more-link">Complete Publication List on Google Scholar →</a>
  </section>

  <!-- Contact -->
  <section class="section" id="contact">
    <div class="contact-box">
      <h2 style="font-size: 1.8em; margin-bottom: 20px;">Research Collaboration & Expertise</h2>
      <p class="contact-text">
        I am interested in collaborative research opportunities that advance fundamental understanding in machine learning security, 
        trustworthy AI systems, and adversarial robustness. My expertise encompasses theoretical foundations in large language/multimodal model safety, 
        multimodal retrieval-augmented generation systems, formal verification approaches for AI safety, and automated red-teaming methodologies. 
        Current research interests include developing principled frameworks for AI system safety assessment, scalable vulnerability detection mechanisms, 
        and theoretical guarantees for trustworthy AI deployment in safety-critical applications.
      </p>
      <div style="margin-top: 20px; padding: 20px; background: rgba(37, 99, 235, 0.1); border-radius: 12px; border-left: 4px solid var(--primary);">
        <h3 style="margin: 0 0 10px 0; color: var(--primary);">Key Research Areas for Collaboration</h3>
        <ul style="margin: 0; padding-left: 20px; color: var(--secondary);">
          <li>Large Language/Multimodal Model Safety and Security</li>
          <li>Trustworthy Multimodal Agentic Systems</li>
          <li>Adversarial Robustness in Deep Learning</li>
          <li>Automated Red-teaming and Safety Benchmarking</li>
          <li>AI System Disparity Assessment and Mitigation</li>
        </ul>
      </div>
    </div>
  </section>
</div>

<script>
// Enhanced JavaScript with animations
document.addEventListener('DOMContentLoaded', function() {
  // Smooth scrolling for navigation (only internal links)
  const internalLinks = document.querySelectorAll('a[href^="#"]:not([href^="https"]):not([href^="http"]):not([target="_blank"])');
  
  internalLinks.forEach(link => {
    link.addEventListener('click', function(e) {
      // Only prevent default for internal navigation links
      if (this.getAttribute('href').startsWith('#') && !this.getAttribute('href').includes('http')) {
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