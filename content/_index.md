---
title: "Inderjeet Singh"
description: "Inderjeet Singh is a Principal Researcher in AI Security at Fujitsu Research of Europe, working on physical AI security for robotic and space systems and on the security of language models, agents, and computer vision."
---

<section class="bio" aria-labelledby="intro-name">
  <img class="portrait" src="/images/profile-illustration.webp" width="200" height="200" alt="Illustrated portrait of Inderjeet Singh" fetchpriority="high">
  <div class="bio-text">
    <h1 id="intro-name">Inderjeet Singh</h1>
    <p class="affiliation">Principal Researcher, AI Security<br>Fujitsu Research of Europe</p>
    <p>I work on AI security and adversarial machine learning. My primary focus is now physical AI security, where I study the security of AI-enabled robotic and space systems. I continue to work on the security of large language models, agentic retrieval-augmented generation (RAG), and computer vision.</p>
    <p>Before joining Fujitsu in 2023, I spent almost four years at NEC Secure System Platform Laboratories in Japan, working on digital and physical adversarial attacks against face recognition. I hold an M.Tech in Industrial Engineering and Operations Research from IIT Bombay, where I received the Institute Silver Medal.</p>
    <p class="profile-links"><a href="https://scholar.google.com/citations?user=eoxiMqQAAAAJ&amp;hl=en">Google Scholar</a> <span aria-hidden="true">/</span> <a href="https://github.com/intherejeet">GitHub</a> <span aria-hidden="true">/</span> <a href="https://www.linkedin.com/in/intherejeet/">LinkedIn</a> <span aria-hidden="true">/</span> <a href="/publications/">Publications</a></p>
  </div>
</section>

<section class="home-section" id="news" aria-labelledby="news-title">
  <h2 id="news-title">News</h2>
  <ul class="news">
    <li><span class="news-date">Jun 2026</span><span>Presented <a href="https://arxiv.org/abs/2606.26793">MIRROR</a> as an oral at IJCNN 2026 (IEEE WCCI) in Maastricht. The <a href="https://github.com/FujitsuResearch/mirror">code</a> and the <a href="https://huggingface.co/datasets/Fujitsu/agentic-rag-redteam-bench">ART-SafeBench</a> benchmark are public.</span></li>
    <li><span class="news-date">Jun 2026</span><span>New preprint on <a href="https://arxiv.org/abs/2606.18532">threat models and measurement for AI sandboxes</a>.</span></li>
    <li><span class="news-date">Feb 2026</span><span>New preprint on <a href="https://arxiv.org/abs/2602.21447">stateful trust inference for multimodal agentic RAG</a>.</span></li>
    <li><span class="news-date">Jan 2026</span><span><a href="https://ojs.aaai.org/index.php/AAAI/article/view/39742">Peer-to-peer LLM federation</a> at AAAI 2026.</span></li>
    <li><span class="news-date">Nov 2025</span><span><a href="https://aclanthology.org/2025.emnlp-main.1250/">TFDP</a>, on token-efficient disparity audits for LLMs, at EMNLP 2025.</span></li>
    <li><span class="news-date">Jul 2025</span><span><a href="https://aclanthology.org/2025.findings-acl.1223/">DIESEL</a>, an inference-time safety method for language models, in Findings of ACL 2025.</span></li>
    <li><span class="news-date">Dec 2024</span><span>Granted <a href="https://patents.google.com/patent/US12183118B2/en">US patent 12,183,118</a> on adversarial patches for face recognition.</span></li>
    <li><span class="news-date">Nov 2024</span><span><a href="https://bmvc2024.org/proceedings/584/">ATLANTIS</a> presented as an oral at BMVC 2024.</span></li>
  </ul>
</section>

<section class="home-section" id="research" aria-labelledby="research-title">
  <h2 id="research-title">Research</h2>
  <p>My research asks how AI systems fail when an adversary is part of their environment, and what evidence is needed before we call a system secure. My main current direction applies this question to physical AI, especially robotic and space systems, where a compromised model can cause physical effects. My published work on language models concerns agentic RAG, where an attacker can act through a poisoned document, an image, a user query, or the orchestration layer. <a href="https://arxiv.org/abs/2606.26793">MIRROR</a> searches these attack surfaces automatically, and the released benchmark makes the resulting attacks reproducible. On defence, I model adversarial intent as a latent state that a trust agent infers across retrieval, planning, and generation, and I have worked on inference-time safety for language models.</p>
  <p>My earlier work at NEC studied physical adversarial examples against face recognition, attacks that remain effective under changes in lighting, and adversarial robustness for deep metric learning and image retrieval. I am also interested in how security claims for AI systems should be evaluated, a question my recent preprint develops for AI sandboxes.</p>
</section>

<section class="home-section" id="publications" aria-labelledby="selected-title">
  <div class="section-heading"><h2 id="selected-title">Selected publications</h2><a href="/publications/">Full list</a></div>
  <ol class="pubs">
    <li>
      <a class="pub-title" href="https://arxiv.org/abs/2606.26793">MIRROR: Novelty-Constrained Memory-Guided MCTS Red-Teaming for Agentic RAG</a>
      <span class="pub-authors"><strong>Inderjeet Singh</strong>, Andrés Murillo, Motoyoshi Sekiya, Yuki Unno, Junichi Suga</span>
      <span class="pub-meta"><em>IJCNN 2026</em> <span class="award">Oral</span> <span class="pub-links"><a href="https://arxiv.org/abs/2606.26793">arXiv</a> <a href="https://github.com/FujitsuResearch/mirror">code</a> <a href="https://huggingface.co/datasets/Fujitsu/agentic-rag-redteam-bench">benchmark</a></span></span>
    </li>
    <li>
      <a class="pub-title" href="https://arxiv.org/abs/2602.21447">Adversarial Intent is a Latent Variable: Stateful Trust Inference for Securing Multimodal Agentic RAG</a>
      <span class="pub-authors"><strong>Inderjeet Singh</strong>, Vikas Pahuja, Aishvariya Priya Rathina Sabapathy, Chiara Picardi, et al.</span>
      <span class="pub-meta"><em>Preprint, 2026</em> <span class="pub-links"><a href="https://arxiv.org/abs/2602.21447">arXiv</a></span></span>
    </li>
    <li>
      <a class="pub-title" href="https://ojs.aaai.org/index.php/AAAI/article/view/39742">Learning to Collaborate: An Orchestrated-Decentralized Framework for Peer-to-Peer LLM Federation</a>
      <span class="pub-authors"><strong>Inderjeet Singh</strong>, Eleonore Vissol-Gaudin, Andikan Otung, Motoyoshi Sekiya</span>
      <span class="pub-meta"><em>AAAI 2026</em> <span class="pub-links"><a href="https://ojs.aaai.org/index.php/AAAI/article/view/39742">paper</a> <a href="https://github.com/FujitsuResearch/knexa-fl">code</a></span></span>
    </li>
    <li>
      <a class="pub-title" href="https://aclanthology.org/2025.emnlp-main.1250/">TFDP: Token-Efficient Disparity Audits for Autoregressive LLMs via Single-Token Masked Evaluation</a>
      <span class="pub-authors"><strong>Inderjeet Singh</strong>, Ramya Srinivasan, Roman Vainshtein, Hisashi Kojima</span>
      <span class="pub-meta"><em>EMNLP 2025</em> <span class="pub-links"><a href="https://aclanthology.org/2025.emnlp-main.1250/">paper</a> <a href="https://huggingface.co/datasets/Fujitsu/PDD-Extended-Bench">data</a></span></span>
    </li>
    <li>
      <a class="pub-title" href="https://aclanthology.org/2025.findings-acl.1223/">DIESEL: A Lightweight Inference-Time Safety Enhancement for Language Models</a>
      <span class="pub-authors">Ben Ganon, Alon Zolfi, Omer Hofman, <strong>Inderjeet Singh</strong>, Hisashi Kojima, Yuval Elovici, Asaf Shabtai</span>
      <span class="pub-meta"><em>Findings of ACL 2025</em> <span class="pub-links"><a href="https://aclanthology.org/2025.findings-acl.1223/">paper</a></span></span>
    </li>
    <li>
      <a class="pub-title" href="https://bmvc2024.org/proceedings/584/">ATLANTIS: A Framework for Automated Targeted Language-guided Augmentation Training for Robust Image Search</a>
      <span class="pub-authors"><strong>Inderjeet Singh</strong>, Roman Vainshtein, Alon Zolfi, Asaf Shabtai, et al.</span>
      <span class="pub-meta"><em>BMVC 2024</em> <span class="award">Oral</span> <span class="pub-links"><a href="https://bmvc2024.org/proceedings/584/">paper</a> <a href="https://github.com/intherejeet/ATLANTIS">code</a></span></span>
    </li>
    <li>
      <a class="pub-title" href="https://proceedings.mlr.press/v222/singh24a.html">Advancing Deep Metric Learning With Adversarial Robustness</a>
      <span class="pub-authors"><strong>Inderjeet Singh</strong>, Kazuya Kakizaki, Toshinori Araki</span>
      <span class="pub-meta"><em>ACML 2023</em> <span class="pub-links"><a href="https://proceedings.mlr.press/v222/singh24a.html">paper</a> <a href="https://github.com/intherejeet/MDProp">code</a></span></span>
    </li>
    <li>
      <a class="pub-title" href="https://doi.org/10.1109/WACVW54805.2022.00036">Powerful Physical Adversarial Examples Against Practical Face Recognition Systems</a>
      <span class="pub-authors"><strong>Inderjeet Singh</strong>, Toshinori Araki, Kazuya Kakizaki</span>
      <span class="pub-meta"><em>WACV Workshops 2022</em> <span class="pub-links"><a href="https://doi.org/10.1109/WACVW54805.2022.00036">paper</a></span></span>
    </li>
  </ol>
</section>

<section class="home-section" id="service" aria-labelledby="service-title">
  <h2 id="service-title">Service</h2>
  <p>Program committee: AAAI 2026, IJCNN 2026 (IEEE WCCI).<br>Reviewer: IEEE Transactions on Pattern Analysis and Machine Intelligence, Neurocomputing.</p>
  <p>For research correspondence, please <a href="https://www.linkedin.com/in/intherejeet/">contact me on LinkedIn</a>.</p>
</section>
