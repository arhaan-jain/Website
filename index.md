---
layout: default
title: Robotics Research
---

<section id="about" class="intro">
  <p>I'm Arhaan Jain, a robotics master's student at the <strong>University of Pennsylvania</strong> and a research assistant in the <strong><a href="https://figueroa.seas.upenn.edu">Figueroa Robotics Lab</a></strong>, where I am working on making manipulation policies human-interactive.</p>
  <p>Previously, I studied mechanical engineering at the <strong>National University of Singapore</strong> and worked with the <strong><a href="https://www.marmotlab.org">Multi-Agent Robotic Motion (MARMot) Lab</a></strong> and <strong><a href="https://www.rayelab.org">Raye Lab</a></strong>.</p>
  <p> I’m particularly interested in how robots can learn and transfer skills across different morphologies while incorporating human feedback and adapting to evolving human intent.
  </p>
</section>

<section id="research">
  <div class="section-heading"><h2>Publications</h2></div>
  <article class="research-item">
    <a class="research-image" href="https://arxiv.org/abs/2606.30290"><img src="{{ '/assets/images/x-morph.png' | relative_url }}" alt="X-Morph transfers human walking, squatting, and arm movements to quadruped and hexapod robots." loading="lazy" width="980" height="443"></a>
    <div>
      <h3>X-Morph: Human Motion Priors for Scalable Robot Learning Across Morphologies</h3>
      <p class="authors">Ritwik Sharma, Shivam Sood, <strong>Arhaan Jain</strong>, Shyam Charan Kesavamoorthi, Chengyang He, Guillaume Sartoretti</p>
      <p class="meta">arXiv:2606.30290 · 2026 · Under review</p>
      <p>Transferring human motion into executable behaviors for quadrupeds, hexapods, and quadruped manipulators. I developed and deployed a reference-conditioned tracking policy for motion transfer across these morphologies.</p>
      <p class="tags">Cross-morphology motion retargeting · Reference-conditioned reinforcement learning · Teacher–student distillation · Physics-aware motion correction</p>
      <div class="resource-links"><a href="https://arxiv.org/abs/2606.30290">arXiv</a><a href="{{ '/assets/files/x-morph.pdf' | relative_url }}">Paper (PDF)</a><a href="https://maker-rat.github.io/morph/">Project &amp; demos ↗</a></div>
    </div>
  </article>
  <article class="research-item">
    <a class="research-image" href="https://arxiv.org/abs/2509.23651"><img src="{{ '/assets/images/helom.png' | relative_url }}" alt="HeLoM hexapod pushing boxes and other objects in simulation and real-world experiments." loading="lazy" width="741" height="564"></a>
    <div>
      <h3>HeLoM: Hierarchical Learning for Whole-Body Loco-Manipulation by a Hexapod Robot</h3>
      <p class="authors">Xinrong Yang, Peizhuo Li, Hongyi Li, Yifeng Peng, <strong>Arhaan Jain</strong>, Junkai Lu, Linnan Chang, Yuhong Cao, Yifeng Zhang, Ge Sun, Guillaume Sartoretti</p>
      <p class="meta">arXiv:2509.23651 · 2025, revised 2026 · Under review</p>
      <p>A hierarchical learning framework that coordinates a hexapod's forelegs and supporting limbs to push objects while maintaining balance. My related work at <a href="https://www.marmotlab.org">MARMot</a> focused on actuator-network-based sim-to-real training and deployment on the HEBI Daisy hexapod.</p>
      <p class="tags">Hierarchical reinforcement learning · PPO · Whole-body loco-manipulation · Learned actuator dynamics · Sim-to-real transfer</p>
      <div class="resource-links"><a href="https://arxiv.org/abs/2509.23651">arXiv</a><a href="{{ '/assets/files/helom.pdf' | relative_url }}">Paper (PDF)</a></div>
    </div>
  </article>
</section>

<section id="projects">
  <div class="section-heading"><h2>Selected projects</h2><span>From simulation to working hardware</span></div>
  <div class="project-grid">
    {% for project in site.data.projects %}
      {% include project.html project=project %}
    {% endfor %}
  </div>
</section>

<section id="experience">
  <div class="section-heading"><h2>Research experience</h2></div>
  <article class="experience-item"><p class="meta">Sep 2026–present</p><div><h3><a href="https://figueroa.seas.upenn.edu">Figueroa Robotics Lab</a></h3><p class="position">Research Assistant · University of Pennsylvania</p><p class="supervision">Supervised by Professor <a href="https://figueroa.seas.upenn.edu/people/">Nadia Figueroa</a></p><p>Working on making state-of-the-art manipulation policies human-interactive.</p></div></article>
  <article class="experience-item"><p class="meta">Jul 2025–Jul 2026</p><div><h3><a href="https://www.marmotlab.org">Multi-Agent Robotic Motion Lab</a></h3><p class="position">Robotics Research Assistant · National University of Singapore</p><p class="supervision">Supervised by Professor <a href="https://www.marmotlab.org/people.html">Guillaume Sartoretti</a></p><p>Developed sim-to-real pipelines for hierarchical reinforcement learning and reference-conditioned motion tracking across legged robot morphologies, with contributions to HeLoM and X-Morph.</p></div></article>
  <article class="experience-item"><p class="meta">Jul–Nov 2025</p><div><h3><a href="https://www.rayelab.org">Evolution Innovation Lab (Raye Lab)</a></h3><p class="position">Research Intern · National University of Singapore</p><p class="supervision">Supervised by Professor <a href="https://www.rayelab.org/rayeyeow">Raye Yeow</a></p><p>Designed and built a PID-regulated fluidic controller with a touchscreen interface for programmable soft-robot actuation.</p></div></article>
  <article class="experience-item"><p class="meta">Aug–Dec 2024</p><div><h3>NUS Materials Science and Engineering</h3><p class="position">Undergraduate Research Assistant · National University of Singapore</p><p class="supervision">Supervised by Professor Tural Khudiyev</p><p>Developed a soldering-based fabrication method for one-dimensional circuits with 96 micro-LEDs, and validated connectivity with an Arduino. Awarded a $5,000 project grant.</p></div></article>
</section>

<section id="education">
  <div class="section-heading"><h2>Education</h2></div>
  <article class="experience-item"><p class="meta">Aug 2026–May 2028<br>(expected)</p><div><h3>University of Pennsylvania</h3><p class="position">Master's in Robotics</p><p>Coursework: Machine Learning, Machine Perception.</p></div></article>
  <article class="experience-item"><p class="meta">Aug 2022–Jul 2026</p><div><h3>National University of Singapore</h3><p class="position">B.Eng. in Mechanical Engineering · Highest Distinction</p><p>Robotics specialization · Minor in Management · GPA 4.68/5.00.<br>Dean's List (AY2025/26, Semester 1) and NUS College President's Honor Roll.</p></div></article>
</section>

<section id="beyond-robotics">
  <div class="section-heading"><h2>Beyond robotics</h2></div>
  <p>I enjoy badminton, football, squash, scuba diving, and filmmaking. I co-created a short documentary about the Singapore Turf Club, <a href="https://youtu.be/mcHM3d-Wybg"><em>The Last Lap</em></a>.</p>
</section>
