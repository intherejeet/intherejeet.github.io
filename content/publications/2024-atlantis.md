---
title: "ATLANTIS: A Framework for Automated Targeted Language-guided Augmentation Training for Robust Image Search"
date: 2024-11-28
draft: true
tags: ["Computer Vision", "Deep Learning", "CBIR", "Data Augmentation", "LLM", "Multimodal"]
categories: ["Conference Papers"]
venue: "BMVC 2024 (Oral)"
type: "conference"
---

{{< rawhtml >}}
<div class="publication-year">2024</div>

<div class="publication-item" data-type="conference">
  <div class="publication-title">
    ATLANTIS: A Framework for Automated Targeted Language-guided Augmentation Training for Robust Image Search
  </div>
  
  <div class="publication-authors">
    <strong>I Singh*</strong>, R Vainshtein, A Zolfi, A Shabtai, J Brokman, O Hofman, K Fumiyoshi, T Kentarou, H Kojima
  </div>
  
  <div class="publication-venue">
    British Machine Vision Conference (BMVC) 2024 - <strong>Oral Presentation</strong> (Acceptance rate: <3%)
  </div>
  
  <div class="publication-abstract">
    <details>
      <summary>Abstract</summary>
      <p>
      Recent image search or content-based image retrieval (CBIR) systems rely on deep metric learning (DML) for extracting representative image features; however, their generalisation is limited by the dependency on large volumes of high-quality, diverse and unbiased training data. We introduce ATLANTIS, a framework with a novel methodology that automatically identifies training data deficiencies and then performs targeted and controlled synthetic data augmentation. Our framework comprises a Data Insight Generator for extracting contextual insights and the deficiencies from the existing training data, an Augmentation Protocol Selector to define dynamic, context-aware augmentation strategies, and an Outlier Removal and Diversity Control module to control the synthetic data's semantic coherence and diversity. ATLANTIS leverages image-to-text transformations, large language models, and text-to-image synthesis to iteratively generate and refine synthetic data while ensuring alignment with the original data and augmenting training data diversity in a controlled manner. Our comprehensive empirical evaluations reveal that ATLANTIS surpasses state-of-art in challenging domain-scarce and class imbalanced data scenarios while also enhancing adversarial robustness, thus underscoring the generalisation gains. ATLANTIS also sets new benchmarks in standard balanced DML tasks, thereby establishing it as a robust and scalable framework for CBIR.
      </p>
    </details>
  </div>
  
  <div class="publication-links">
    <a href="https://scholar.google.com/citations?user=eoxiMqQAAAAJ&hl=en" target="_blank">Google Scholar</a>
    <a href="#" class="coming-soon">Paper (Coming Soon)</a>
    <a href="#" class="coming-soon">Patent (Filed)</a>
  </div>
</div>
{{< /rawhtml >}} 