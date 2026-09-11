---
layout: home
title: About
---

<div class="hero-card">
  <h1 class="hero-title">Hi, I'm Raunav <span class="wave">👋</span></h1>
  <p class="hero-subtitle">
    I'm a computer vision and machine learning engineer focused on <strong>representation learning</strong>, <strong>signal processing</strong>, and <strong>first-principles machine learning</strong>. Currently working on driver behavior modeling from trajectories and video perception at scale.
  </p>
  <div class="badge-group">
    <a href="https://github.com/imraunav" target="_blank" rel="noopener noreferrer" class="social-badge">
      <svg viewBox="0 0 24 24"><path d="M12 0C5.37 0 0 5.37 0 12c0 5.31 3.435 9.795 8.205 11.385.6.105.825-.255.825-.57 0-.285-.015-1.23-.015-2.235-3.015.555-3.795-.735-4.035-1.41-.135-.345-.72-1.41-1.23-1.695-.42-.225-1.02-.78-.015-.795.945-.015 1.62.87 1.845 1.23 1.08 1.815 2.805 1.305 3.495.99.105-.78.42-1.305.765-1.605-2.67-.3-5.46-1.335-5.46-5.925 0-1.305.465-2.385 1.23-3.225-.12-.3-.54-1.53.12-3.18 0 0 1.005-.315 3.3 1.23.96-.27 1.98-.405 3-.405s2.04.135 3 .405c2.295-1.56 3.3-1.23 3.3-1.23.66 1.65.24 2.88.12 3.18.765.84 1.23 1.905 1.23 3.225 0 4.605-2.805 5.625-5.475 5.925.435.375.81 1.095.81 2.22 0 1.605-.015 2.895-.015 3.3 0 .315.225.69.825.57A12.02 12.02 0 0024 12c0-6.63-5.37-12-12-12z"/></svg>
      GitHub
    </a>
    <a href="https://linkedin.com/in/raunav" target="_blank" rel="noopener noreferrer" class="social-badge">
      <svg viewBox="0 0 24 24"><path d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"/></svg>
      LinkedIn
    </a>
    <a href="mailto:raunavghosh@gmail.com" class="social-badge">
      <svg viewBox="0 0 24 24"><path d="M0 3v18h24v-18h-24zm6.623 7.929l-4.623 5.712v-9.458l4.623 3.746zm-4.141-5.929h19.035l-9.517 7.713-9.518-7.713zm5.694 7.188l3.824 3.099 3.83-3.104 5.612 6.817h-18.779l5.513-6.812zm9.208-1.264l4.616-3.741v9.348l-4.616-5.607z"/></svg>
      Email
    </a>
  </div>
</div>

<div class="section-header">
  <span class="icon">💼</span>
  <span>Experience</span>
</div>

<div class="experience-list">
  <div class="timeline-card">
    <div class="timeline-header">
      <div>
        <h3 class="role-title">Senior Engineer</h3>
        <span class="company-name">Bosch Global Software Technologies</span>
      </div>
      <span class="timeline-date">December 2025 – Present</span>
    </div>
    <ul>
      <li><strong>Self-Supervised Trajectory Representation:</strong> Designed self-supervised learning backbones leveraging DINO-style self-distillation and contrastive objectives to model joint ego- and surrounding-agent spatio-temporal dynamics.</li>
      <li><strong>Transformer-Based Kinematic Architecture:</strong> Implemented a pure Transformer backbone with Rotary Position Embeddings (RoPE) to encode multi-agent kinematic and positional state sequences across discrete timesteps into compact scenario embeddings.</li>
      <li><strong>Large-Scale Scenario Mining &amp; Retrieval:</strong> Built embedding-based retrieval pipelines to query across ~10,000 hours of unlabelled driving logs, evaluating scenario discovery using Recall@25 across safety-critical maneuvers (e.g., aggressive cut-ins, hard braking, lane changes, and unprotected turns).</li>
      <li><strong>Automated Curation for Downstream AI:</strong> Structured embedding spaces that interface with vector indexing (Qdrant) to curate targeted corner-case datasets, feeding downstream behavioral prediction and Vision-Language-Action (VLA) modeling pipelines.</li>
      <li><strong>Multimodal Perception (In Progress):</strong> Developing video-based representation learning to enable cross-modal retrieval aligning temporal trajectories with visual scene dynamics.</li>
    </ul>
  </div>

  <div class="timeline-card">
    <div class="timeline-header">
      <div>
        <h3 class="role-title">Computer Vision Engineer</h3>
        <span class="company-name">Vehant Technologies Pvt Ltd.</span>
      </div>
      <span class="timeline-date">June 2024 – November 2025</span>
    </div>
    <ul>
      <li><strong>Streaming Image Quality Enhancement:</strong> Designed and deployed low-latency ISP algorithms tailored to real-time baggage line-scan detectors:
        <ul>
          <li>Adapted CLAHE for streaming line-scan data operating on 16-scanline sliding buffers, resolving spatial boundary artifacts and ensuring neighborhood photometric consistency across frames.</li>
          <li>Implemented edge-enhancement and high-frequency sharpening routines to preserve fine structural contours of complex, overlapping items.</li>
          <li>Developed deep-learning super-resolution models (leveraging EDSR and GAN-based architectures) to recover 4x high-frequency spatial details beyond physical sensor resolution limits.</li>
        </ul>
      </li>
      <li><strong>Dual-Energy Material Discrimination:</strong> Formulated algorithms leveraging high- and low-energy X-ray absorption profiles to discriminate material composition, providing physical material cues alongside geometric shapes for downstream threat identification.</li>
    </ul>
  </div>
</div>

<div class="section-header">
  <span class="icon">🎓</span>
  <span>Education</span>
</div>

<div class="education-grid">
  <div class="edu-card">
    <div class="edu-school">Indian Institute of Technology (IIT) Mandi</div>
    <div class="edu-degree">M.Tech in Communication and Signal Processing (Machine Learning Specialization)</div>
    <div class="edu-date">August 2022 – May 2024</div>
  </div>
  <div class="edu-card">
    <div class="edu-school">University of Engineering and Management (UEM), Kolkata</div>
    <div class="edu-degree">B.Tech in Electronics and Communications Engineering</div>
    <div class="edu-date">August 2017 – May 2021</div>
  </div>
</div>

<div class="section-header">
  <span class="icon">🛠️</span>
  <span>Technical Toolkit</span>
</div>

<div class="skills-container">
  <div class="skill-category">
    <div class="skill-label">Languages</div>
    <div class="skill-tags">
      <span class="skill-tag">Python</span>
      <span class="skill-tag">C++</span>
      <span class="skill-tag">Bash</span>
    </div>
  </div>
  <div class="skill-category" style="margin-top: 1rem;">
    <div class="skill-label">Frameworks &amp; Tools</div>
    <div class="skill-tags">
      <span class="skill-tag">PyTorch</span>
      <span class="skill-tag">OpenCV</span>
      <span class="skill-tag">Git</span>
      <span class="skill-tag">Linux</span>
      <span class="skill-tag">Qdrant</span>
      <span class="skill-tag">Transformers</span>
      <span class="skill-tag">Signal Processing</span>
    </div>
  </div>
</div>
