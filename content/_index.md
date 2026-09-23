---
title: "Inderjeet Singh"
description: "Inderjeet Singh, Principal Researcher in AI Security at Fujitsu Research of Europe. Research on adversarial machine learning, agentic AI security, and robustness."
---

<section class="intro" aria-labelledby="intro-name">
  <div class="intro-copy">
    <p class="eyebrow">AI security researcher</p>
    <h1 id="intro-name">Inderjeet Singh</h1>
    <p class="appointment">Principal Researcher, AI Security<br>Fujitsu Research of Europe</p>
    <p class="research-statement">I study how AI systems fail under adversarial pressure and how to evaluate and defend them. My recent work examines attacks on agentic retrieval systems and language models, with earlier work on physical attacks and robust visual recognition.</p>
    <p class="profile-links"><a href="https://scholar.google.com/citations?user=eoxiMqQAAAAJ&amp;hl=en">Google Scholar</a><a href="/publications/">Publications</a><a href="https://github.com/intherejeet">GitHub</a><a href="https://www.linkedin.com/in/intherejeet/">LinkedIn</a></p>
  </div>
  <img class="portrait" src="/images/profile-2025.webp" width="200" height="200" alt="Portrait of Inderjeet Singh" fetchpriority="high">
</section>

<section class="home-section" id="publications" aria-labelledby="selected-title">
  <div class="section-heading"><h2 id="selected-title">Selected work</h2><a href="/publications/">All publications</a></div>
  <ol class="paper-list">
    <li class="paper">
      <span class="paper-venue">IJCNN 2026, oral</span>
      <h3><a href="https://arxiv.org/abs/2606.26793">MIRROR: Novelty-Constrained Memory-Guided MCTS Red-Teaming for Agentic RAG</a></h3>
      <p class="paper-authors"><strong>Inderjeet Singh</strong>, Andrés Murillo, Motoyoshi Sekiya, Yuki Unno, Junichi Suga</p>
      <p>Memory-guided search tests text, image, query, and orchestrator attack surfaces in agentic RAG.</p>
      <p class="paper-links"><a href="https://arxiv.org/abs/2606.26793">Paper</a><a href="https://github.com/FujitsuResearch/mirror">Code</a><a href="https://huggingface.co/datasets/Fujitsu/agentic-rag-redteam-bench">Benchmark</a></p>
    </li>
    <li class="paper">
      <span class="paper-venue">Preprint, 2026</span>
      <h3><a href="https://arxiv.org/abs/2602.21447">Adversarial Intent is a Latent Variable: Stateful Trust Inference for Securing Multimodal Agentic RAG</a></h3>
      <p class="paper-authors"><strong>Inderjeet Singh</strong>, Vikas Pahuja, Aishvariya Priya Rathina Sabapathy, Chiara Picardi, et al.</p>
      <p>A trust agent tracks evidence across retrieval, planning, and generation instead of judging each stage in isolation.</p>
      <p class="paper-links"><a href="https://arxiv.org/abs/2602.21447">Preprint</a></p>
    </li>
    <li class="paper">
      <span class="paper-venue">AAAI 2026</span>
      <h3><a href="https://ojs.aaai.org/index.php/AAAI/article/view/39742">Learning to Collaborate: An Orchestrated-Decentralized Framework for Peer-to-Peer LLM Federation</a></h3>
      <p class="paper-authors"><strong>Inderjeet Singh</strong>, Eleonore Vissol-Gaudin, Andikan Otung, Motoyoshi Sekiya</p>
      <p>Peer-to-peer knowledge exchange between language-model agents without sharing raw training data.</p>
      <p class="paper-links"><a href="https://ojs.aaai.org/index.php/AAAI/article/view/39742">Paper</a><a href="https://github.com/FujitsuResearch/knexa-fl">Code</a></p>
    </li>
    <li class="paper">
      <span class="paper-venue">EMNLP 2025</span>
      <h3><a href="https://aclanthology.org/2025.emnlp-main.1250/">TFDP: Token-Efficient Disparity Audits for Autoregressive LLMs via Single-Token Masked Evaluation</a></h3>
      <p class="paper-authors"><strong>Inderjeet Singh</strong>, Ramya Srinivasan, Roman Vainshtein, Hisashi Kojima</p>
      <p>Targeted token queries and contrastive probes measure disparities in language-model behaviour.</p>
      <p class="paper-links"><a href="https://aclanthology.org/2025.emnlp-main.1250/">Paper</a><a href="https://huggingface.co/datasets/Fujitsu/PDD-Extended-Bench">Data</a></p>
    </li>
    <li class="paper">
      <span class="paper-venue">ACL Findings 2025</span>
      <h3><a href="https://aclanthology.org/2025.findings-acl.1223/">DIESEL: A Lightweight Inference-Time Safety Enhancement for Language Models</a></h3>
      <p class="paper-authors">Ben Ganon, Alon Zolfi, Omer Hofman, <strong>Inderjeet Singh</strong>, et al.</p>
      <p>Inference-time token reranking steers generation away from predefined unsafe concepts.</p>
      <p class="paper-links"><a href="https://aclanthology.org/2025.findings-acl.1223/">Paper</a></p>
    </li>
    <li class="paper">
      <span class="paper-venue">BMVC 2024, oral</span>
      <h3><a href="https://bmvc2024.org/proceedings/584/">ATLANTIS: A Framework for Automated Targeted Language-guided Augmentation Training for Robust Image Search</a></h3>
      <p class="paper-authors"><strong>Inderjeet Singh</strong>, Roman Vainshtein, Alon Zolfi, Asaf Shabtai, et al.</p>
      <p>Targeted synthetic augmentation addresses gaps in image-retrieval training data and improves robustness.</p>
      <p class="paper-links"><a href="https://bmvc2024.org/proceedings/584/">Paper</a><a href="https://github.com/intherejeet/ATLANTIS">Code</a></p>
    </li>
  </ol>
  <p class="more-link"><a href="/publications/">More papers, preprints, datasets, and patents</a></p>
</section>

<section class="home-section" id="research" aria-labelledby="research-title">
  <h2 id="research-title">Research</h2>
  <div class="research-lines">
    <div><h3>Attacking and evaluating AI systems</h3><p>I study prompt injection, retrieval poisoning, and failures across the components of tool-using agents. MIRROR and the open ART-SafeBench benchmark make these attacks testable across multiple surfaces.</p></div>
    <div><h3>Defenses under adaptive pressure</h3><p>My work includes stateful trust inference for agentic RAG and inference-time safety for language models. The central question is whether a defense still works when an attacker can change tactics.</p></div>
    <div><h3>Adversarial robustness beyond language</h3><p>Earlier work examined physical attacks on face recognition and robust image retrieval. I also study how to measure the security claims made for AI sandboxes and physical AI.</p></div>
  </div>
</section>

<section class="home-section" id="about" aria-labelledby="about-title">
  <h2 id="about-title">About</h2>
  <p>I am a Principal Researcher in AI Security at Fujitsu Research of Europe. Before joining Fujitsu, I worked on adversarial machine learning at NEC in Japan. I hold an M.Tech from IIT Bombay and a B.Tech from Vasantrao Naik Marathwada Krishi Vidyapeeth. I am an inventor on a <a href="https://patents.google.com/patent/US12183118B2/en">granted US patent</a> for adversarial patch adjustment in face recognition.</p>
  <p>For research correspondence, <a href="https://www.linkedin.com/in/intherejeet/">reach me on LinkedIn</a>. My <a href="https://scholar.google.com/citations?user=eoxiMqQAAAAJ&amp;hl=en">Google Scholar profile</a> lists further work.</p>
</section>
