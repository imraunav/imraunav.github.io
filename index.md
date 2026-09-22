---
layout: home
---

<div class="hero-status">
  <span class="status-indicator"></span>
  <span>Senior Engineer at Bosch · Applied Computer Vision</span>
</div>

# Hi, I'm Raunav

I'm a computer vision and machine learning engineer focused on **representation learning**, **signal processing**, and **first-principles machine learning**. Currently working on driver behavior modeling from trajectories and video perception at scale.

<div class="social-pills">
  <a class="social-pill" href="https://github.com/imraunav" target="_blank" rel="noopener noreferrer">
    <svg viewBox="0 0 24 24"><path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"></path></svg>
    <span>GitHub</span>
  </a>
  <a class="social-pill" href="https://linkedin.com/in/raunav" target="_blank" rel="noopener noreferrer">
    <svg viewBox="0 0 24 24"><path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"></path><rect x="2" y="9" width="4" height="12"></rect><circle cx="4" cy="4" r="2"></circle></svg>
    <span>LinkedIn</span>
  </a>
  <a class="social-pill" href="mailto:raunavghosh@gmail.com">
    <svg viewBox="0 0 24 24"><path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"></path><polyline points="22,6 12,13 2,6"></polyline></svg>
    <span>Email</span>
  </a>
</div>

<h2 class="section-heading">
  <span class="section-icon">
    <svg viewBox="0 0 24 24"><rect x="2" y="7" width="20" height="14" rx="2" ry="2"></rect><path d="M16 21V5a2 2 0 0 0-2-2h-4a2 2 0 0 0-2 2v16"></path></svg>
  </span>
  <span>Experience</span>
</h2>

<div class="entry-row">
  <a class="entry-logo-link" href="https://www.linkedin.com/company/bosch-global-software-technologies/" target="_blank" rel="noopener noreferrer" title="Bosch Global Software Technologies on LinkedIn">
    <img src="/assets/images/logos/bosch.svg" alt="Bosch Global Software Technologies" class="entry-logo" />
  </a>
  <div class="entry-content">
    <div class="item-header">
      <h3>Senior Engineer — <a href="https://www.linkedin.com/company/bosch-global-software-technologies/" target="_blank" rel="noopener noreferrer" class="org-link">Bosch Global Software Technologies</a></h3>
      <span class="date-badge">December 2025 – Present</span>
    </div>
  </div>
</div>

<ul class="experience-list">
  <li><strong>Self-Supervised Trajectory Representation:</strong> Designed self-supervised learning backbones leveraging DINO-style self-distillation and contrastive objectives to model joint ego- and surrounding-agent spatio-temporal dynamics.</li>
  <li><strong>Transformer-Based Kinematic Architecture:</strong> Implemented a pure Transformer backbone with Rotary Position Embeddings (RoPE) to encode multi-agent kinematic and positional state sequences across discrete timesteps into compact scenario embeddings.</li>
  <li><strong>Large-Scale Scenario Mining &amp; Retrieval:</strong> Built embedding-based retrieval pipelines to query across ~10,000 hours of unlabelled driving logs, evaluating scenario discovery using Recall@25 across safety-critical maneuvers (e.g., aggressive cut-ins, hard braking, lane changes, and unprotected turns).</li>
  <li><strong>Automated Curation for Downstream AI:</strong> Structured embedding spaces that interface with vector indexing (Qdrant) to curate targeted corner-case datasets, feeding downstream behavioral prediction and Vision-Language-Action (VLA) modeling pipelines.</li>
  <li><strong>Multimodal Perception (In Progress):</strong> Developing video-based representation learning to enable cross-modal retrieval aligning temporal trajectories with visual scene dynamics.</li>
</ul>

<div class="entry-row">
  <a class="entry-logo-link" href="https://www.linkedin.com/company/vehant/" target="_blank" rel="noopener noreferrer" title="Vehant Technologies on LinkedIn">
    <img src="/assets/images/logos/vehant.webp" alt="Vehant Technologies" class="entry-logo" />
  </a>
  <div class="entry-content">
    <div class="item-header">
      <h3>Computer Vision Engineer — <a href="https://www.linkedin.com/company/vehant/" target="_blank" rel="noopener noreferrer" class="org-link">Vehant Technologies</a></h3>
      <span class="date-badge">June 2024 – November 2025</span>
    </div>
  </div>
</div>

<ul class="experience-list">
  <li><strong>Streaming Image Quality Enhancement:</strong> Designed and deployed low-latency ISP algorithms tailored to real-time baggage line-scan detectors:
    <ul>
      <li>Adapted CLAHE for streaming line-scan data operating on 16-scanline sliding buffers, resolving spatial boundary artifacts and ensuring neighborhood photometric consistency across frames.</li>
      <li>Implemented edge-enhancement and high-frequency sharpening routines to preserve fine structural contours of complex, overlapping items.</li>
      <li>Developed deep-learning super-resolution models (leveraging EDSR and GAN-based architectures) to recover 4x high-frequency spatial details beyond physical sensor resolution limits.</li>
    </ul>
  </li>
  <li><strong>Dual-Energy Material Discrimination:</strong> Formulated algorithms leveraging high- and low-energy X-ray absorption profiles to discriminate material composition, providing physical material cues alongside geometric shapes for downstream threat identification.</li>
</ul>

<h2 class="section-heading">
  <span class="section-icon">
    <svg viewBox="0 0 24 24"><path d="M22 10v6M2 10l10-5 10 5-10 5z"></path><path d="M6 12v5c3 3 9 3 12 0v-5"></path></svg>
  </span>
  <span>Education</span>
</h2>

<div class="entry-row">
  <a class="entry-logo-link" href="https://www.linkedin.com/school/indian-institute-of-technology-mandi/" target="_blank" rel="noopener noreferrer" title="IIT Mandi on LinkedIn">
    <img src="/assets/images/logos/iitmandi.png" alt="Indian Institute of Technology (IIT) Mandi" class="entry-logo" />
  </a>
  <div class="entry-content">
    <div class="item-header">
      <h3><a href="https://www.linkedin.com/school/indian-institute-of-technology-mandi/" target="_blank" rel="noopener noreferrer" class="org-link">Indian Institute of Technology (IIT) Mandi</a></h3>
      <span class="date-badge">August 2022 – May 2024</span>
    </div>
    <div class="item-subtitle">M.Tech in Communication and Signal Processing (Machine Learning Specialization)</div>
  </div>
</div>

<div class="honors-list">
  <span class="honor-tag">
    <svg viewBox="0 0 24 24"><circle cx="12" cy="8" r="7"></circle><polyline points="8.21 13.89 7 23 12 20 17 23 15.79 13.88"></polyline></svg>
    Outstanding Academic Achievement Award
  </span>
  <span class="honor-tag">
    <svg viewBox="0 0 24 24"><circle cx="12" cy="8" r="7"></circle><polyline points="8.21 13.89 7 23 12 20 17 23 15.79 13.88"></polyline></svg>
    Vehant Research Fellowship
  </span>
</div>

<div class="entry-row">
  <a class="entry-logo-link" href="https://www.linkedin.com/school/university-of-engineering-management-uem/" target="_blank" rel="noopener noreferrer" title="UEM Kolkata on LinkedIn">
    <img src="/assets/images/logos/uem.png" alt="University of Engineering and Management (UEM), Kolkata" class="entry-logo" />
  </a>
  <div class="entry-content">
    <div class="item-header">
      <h3><a href="https://www.linkedin.com/school/university-of-engineering-management-uem/" target="_blank" rel="noopener noreferrer" class="org-link">University of Engineering and Management (UEM), Kolkata</a></h3>
      <span class="date-badge">August 2017 – May 2021</span>
    </div>
    <div class="item-subtitle">B.Tech in Electronics and Communications Engineering</div>
  </div>
</div>

<h2 class="section-heading">
  <span class="section-icon">
    <svg viewBox="0 0 24 24"><polyline points="4 17 10 11 4 5"></polyline><line x1="12" y1="19" x2="20" y2="19"></line></svg>
  </span>
  <span>Technical Toolkit</span>
</h2>

<div class="skill-category">
  <div class="skill-label">Languages</div>
  <div class="skill-tags">
    <span class="skill-tag">Python</span>
    <span class="skill-tag">C++</span>
    <span class="skill-tag">Bash</span>
  </div>
</div>

<div class="skill-category">
  <div class="skill-label">Core &amp; Frameworks</div>
  <div class="skill-tags">
    <span class="skill-tag">PyTorch</span>
    <span class="skill-tag">OpenCV</span>
    <span class="skill-tag">Docker</span>
    <span class="skill-tag">Git</span>
    <span class="skill-tag">Linux</span>
  </div>
</div>