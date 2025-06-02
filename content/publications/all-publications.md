---
title: "All Publications"
date: 2024-01-01
layout: "single"
draft: true
---

{{< rawhtml >}}
<style>
.publications-container {
  max-width: 900px;
  margin: 0 auto;
  padding: 40px 20px;
}

.back-link {
  display: inline-block;
  margin-bottom: 40px;
  color: var(--primary);
  text-decoration: none;
  font-weight: 500;
}

.back-link:hover {
  text-decoration: underline;
}

.year-section {
  margin-bottom: 60px;
}

.year-header {
  font-size: 2em;
  font-weight: 300;
  color: var(--primary);
  margin-bottom: 30px;
  padding-bottom: 10px;
  border-bottom: 2px solid var(--primary);
}

.publication-entry {
  margin-bottom: 40px;
  padding-left: 20px;
  border-left: 3px solid transparent;
  transition: all 0.3s ease;
}

.publication-entry:hover {
  border-left-color: var(--primary);
}

.pub-title {
  font-size: 1.1em;
  font-weight: 600;
  margin-bottom: 8px;
  line-height: 1.4;
}

.pub-authors {
  color: var(--secondary);
  margin-bottom: 8px;
  line-height: 1.4;
}

.pub-venue {
  font-style: italic;
  margin-bottom: 12px;
  color: var(--primary);
}

.pub-abstract {
  font-size: 0.95em;
  line-height: 1.6;
  color: var(--secondary);
  margin-bottom: 12px;
}

.pub-links {
  display: flex;
  gap: 15px;
  flex-wrap: wrap;
}

.pub-links a {
  font-size: 0.9em;
  color: var(--primary);
  text-decoration: none;
  padding: 5px 12px;
  border: 1px solid var(--border);
  border-radius: 3px;
  transition: all 0.3s ease;
}

.pub-links a:hover {
  background: var(--primary);
  color: var(--theme);
}

.pub-award {
  display: inline-block;
  background: var(--primary);
  color: var(--theme);
  padding: 3px 10px;
  border-radius: 3px;
  font-size: 0.85em;
  margin-left: 10px;
}
</style>

<div class="publications-container">
  <a href="/" class="back-link">← Back to Home</a>
  
  <h1 style="font-size: 3em; font-weight: 300; margin-bottom: 20px;">Publications</h1>
  <p style="font-size: 1.2em; color: var(--secondary); margin-bottom: 50px;">
    A comprehensive list of my research contributions across LLM/LMM Safety, AI Security, Computer Vision, and Trustworthy AI. For the complete list, please visit my <a href="https://scholar.google.com/citations?user=eoxiMqQAAAAJ&hl=en" style="color: var(--primary);">Google Scholar</a> profile.
  </p>

  <!-- 2025 Publications -->
  <div class="year-section">
    <h2 class="year-header">2025</h2>
    
    <div class="publication-entry">
      <div class="pub-title">
        DIESEL: A Lightweight Inference-Time Safety Enhancement for Language Models
      </div>
      <div class="pub-authors">
        B Ganon, A Zolfi, O Hofman, <strong>I Singh</strong>, H Kojima, Y Elovici, A Shabtai
      </div>
      <div class="pub-venue">
        ACL 2025 - Annual Meeting of the Association for Computational Linguistics
      </div>
      <div class="pub-abstract">
        DIESEL provides a lightweight framework for enhancing LLM safety at inference time through dynamic token re-ranking based on semantic similarity to negative/adversarial concepts.
      </div>
      <div class="pub-links">
        <a href="#">Paper</a>
        <a href="#">Code</a>
        <a href="#">BibTeX</a>
      </div>
    </div>
  </div>

  <!-- 2024 Publications -->
  <div class="year-section">
    <h2 class="year-header">2024</h2>
    
    <div class="publication-entry">
      <div class="pub-title">
        ATLANTIS: A Framework for Automated Targeted Language-guided Augmentation Training for Robust Image Search
        <span class="pub-award">Oral Presentation</span>
      </div>
      <div class="pub-authors">
        <strong>I Singh*</strong>, R Vainshtein, A Zolfi, A Shabtai, J Brokman, O Hofman, K Fumiyoshi, T Kentarou, H Kojima
      </div>
      <div class="pub-venue">
        BMVC 2024 - British Machine Vision Conference (Acceptance rate: <3%)
      </div>
      <div class="pub-abstract">
        ATLANTIS is a unified multimodal framework for automated, language-guided augmentation to enhance image search robustness. Patent filed.
      </div>
      <div class="pub-links">
        <a href="#">Paper</a>
        <a href="#">Code</a>
        <a href="#">Slides</a>
        <a href="#">Patent</a>
      </div>
    </div>
    
    <div class="publication-entry">
      <div class="pub-title">
        MONTRAGE: Monitoring Training for Attribution of Generative Diffusion Models
      </div>
      <div class="pub-authors">
        J Brokman, O Hofman, R Vainshtein, A Giloni, T Shimizu, <strong>I Singh</strong>, O Rachmil, A Zolfi, A Shabtai, Y Unno, H Kojima
      </div>
      <div class="pub-venue">
        ECCV 2024 - European Conference on Computer Vision
      </div>
      <div class="pub-abstract">
        MONTRAGE provides training data attribution for text-to-image diffusion models, enabling copyright protection and data provenance tracking. Patent filed.
      </div>
      <div class="pub-links">
        <a href="#">Paper</a>
        <a href="#">Code</a>
        <a href="#">Patent</a>
      </div>
    </div>
    
    <div class="publication-entry">
      <div class="pub-title">
        Insights and Current Gaps in Open-Source LLM Vulnerability Scanners: A Comparative Analysis
      </div>
      <div class="pub-authors">
        J Brokman, O Hofman, O Rachmil, <strong>I Singh</strong>, PRS Aishvariya, V Pahuja, A Giloni, R Vainshtein, H Kojima
      </div>
      <div class="pub-venue">
        ACM ICSE RAIE 2024 - International Conference on Software Engineering, Research Advances in AI Engineering
      </div>
      <div class="pub-abstract">
        A comprehensive review and comparative analysis of existing open-source LLM vulnerability scanning frameworks, identifying key gaps and proposing improvements for LLM safety assessment.
      </div>
      <div class="pub-links">
        <a href="#">Paper</a>
        <a href="#">Preprint</a>
      </div>
    </div>
    
    <div class="publication-entry">
      <div class="pub-title">
        Advancing Deep Metric Learning With Adversarial Robustness
        <span class="pub-award">Long Talk</span>
      </div>
      <div class="pub-authors">
        <strong>I Singh*</strong>, K Kakizaki, T Araki
      </div>
      <div class="pub-venue">
        ACML 2024 - Asian Conference on Machine Learning
      </div>
      <div class="pub-abstract">
        MDProp achieves SOTA performance in deep metric learning with +2.95% Recall@1 (clean), 2.12x robustness (multi-distribution), and +9.98% Recall@1 for NEC Retail Product Recognition Engine.
      </div>
      <div class="pub-links">
        <a href="#">Paper</a>
        <a href="#">Code</a>
        <a href="#">Slides</a>
        <a href="#">Patents: US3350013577, US3350013654, JP3350013655</a>
      </div>
    </div>
  </div>

  <!-- 2023 Publications -->
  <div class="year-section">
    <h2 class="year-header">2023</h2>
    
    <div class="publication-entry">
      <div class="pub-title">
        Simultaneous Adversarial Attacks On Multiple Face Recognition System Components
        <span class="pub-award">Patent Granted</span>
      </div>
      <div class="pub-authors">
        <strong>I Singh*</strong>, K Kakizaki, T Araki
      </div>
      <div class="pub-venue">
        arXiv 2023
      </div>
      <div class="pub-abstract">
        Novel approach for simultaneous adversarial attacks on multiple components of face recognition systems, demonstrating vulnerabilities in real-world deployments.
      </div>
      <div class="pub-links">
        <a href="#">Paper</a>
        <a href="#">arXiv</a>
        <a href="#">Patent: US12183118 (Granted)</a>
      </div>
    </div>
  </div>

  <!-- Patents Section -->
  <div class="year-section">
    <h2 class="year-header">Patents</h2>
    <p style="margin-bottom: 20px; color: var(--secondary);">
      <strong>10+ patents filed</strong>, with first grant recently received. Selected patents with associated publications are listed above.
    </p>
    <ul style="list-style-type: none; padding-left: 0;">
      <li style="margin-bottom: 10px;">• <strong>US12183118</strong> (Granted) - Simultaneous Adversarial Attacks on Face Recognition Systems</li>
      <li style="margin-bottom: 10px;">• <strong>US3350013577, US3350013654, JP3350013655</strong> - Deep Metric Learning with Adversarial Robustness</li>
      <li style="margin-bottom: 10px;">• Patent filed for ATLANTIS framework</li>
      <li style="margin-bottom: 10px;">• Patent filed for MONTRAGE framework</li>
      <li style="margin-bottom: 10px;">• Additional patents in AI Security and Computer Vision (details under NDA)</li>
    </ul>
  </div>

  <!-- Note -->
  <div style="margin-top: 60px; padding: 30px; background: var(--code-bg); border-radius: 8px;">
    <p style="text-align: center; color: var(--secondary); margin: 0;">
      * denotes equal contribution or first author<br>
      For a complete list of publications and citations, please visit my <a href="https://scholar.google.com/citations?user=eoxiMqQAAAAJ&hl=en" style="color: var(--primary);">Google Scholar</a> profile.
    </p>
  </div>
</div>

{{< /rawhtml >}} 