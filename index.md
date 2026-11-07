---
layout: default
title: Robotics Research
---

<section id="about" class="intro">
  <p class="eyebrow">Robot learning · Control · Hardware</p>
  <h2>Learning to move.<br>Learning to interact.</h2>
  <p>I'm <strong>Arhaan Jain</strong>, a robotics master's student at the <strong>University of Pennsylvania</strong> and a research assistant in the <strong>Figueroa Robotics Lab</strong>, where I work on making manipulation policies human-interactive.</p>
  <p>I'm interested in how robots learn to move and interact with the physical world. My work spans sim-to-real reinforcement learning, whole-body loco-manipulation, human-motion transfer across robot morphologies, and soft robotic systems.</p>
  <p>Previously, I studied mechanical engineering at the <strong>National University of Singapore</strong> and worked with the <strong>Multi-Agent Robotic Motion (MARMot) Lab</strong>. I enjoy connecting learning and control with the practical work of building, testing, and deploying robots.</p>
  <ul class="topics" aria-label="Research interests"><li>Robot learning</li><li>Whole-body control</li><li>Sim-to-real transfer</li><li>Soft robotics</li></ul>
</section>

<section id="research">
  <div class="section-heading"><h2>Selected research</h2><span>Preprints &amp; manuscripts under review</span></div>
  <article class="research-item">
    <a class="research-image" href="https://arxiv.org/abs/2606.30290"><img src="{{ '/assets/images/x-morph.png' | relative_url }}" alt="X-Morph transfers human walking, squatting, and arm movements to quadruped and hexapod robots." loading="lazy" width="980" height="443"></a>
    <div>
      <h3>X-Morph: Human Motion Priors for Scalable Robot Learning Across Morphologies</h3>
      <p class="authors">Ritwik Sharma, Shivam Sood, <strong>Arhaan Jain</strong>, Shyam Charan Kesavamoorthi, Chengyang He, Guillaume Sartoretti</p>
      <p class="meta">arXiv:2606.30290 · 2026 · Under review</p>
      <p>Transferring human motion into executable behaviors for quadrupeds, hexapods, and quadruped manipulators. I developed and deployed a reference-conditioned tracking policy for motion transfer across these morphologies.</p>
      <div class="resource-links"><a href="https://arxiv.org/abs/2606.30290">arXiv</a><a href="{{ '/assets/files/x-morph.pdf' | relative_url }}">Paper (PDF)</a><a href="https://maker-rat.github.io/morph/">Project &amp; demos ↗</a></div>
    </div>
  </article>
  <article class="research-item">
    <a class="research-image" href="https://arxiv.org/abs/2509.23651"><img src="{{ '/assets/images/helom.png' | relative_url }}" alt="HeLoM hexapod pushing boxes and other objects in simulation and real-world experiments." loading="lazy" width="741" height="564"></a>
    <div>
      <h3>HeLoM: Hierarchical Learning for Whole-Body Loco-Manipulation by a Hexapod Robot</h3>
      <p class="authors">Xinrong Yang, Peizhuo Li, Hongyi Li, Yifeng Peng, <strong>Arhaan Jain</strong>, Junkai Lu, Linnan Chang, Yuhong Cao, Yifeng Zhang, Ge Sun, Guillaume Sartoretti</p>
      <p class="meta">arXiv:2509.23651 · 2025, revised 2026 · Under review</p>
      <p>A hierarchical learning framework that coordinates a hexapod's forelegs and supporting limbs to push objects while maintaining balance. My related work at MARMot focused on actuator-network-based sim-to-real training and deployment on the HEBI Daisy hexapod.</p>
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
  <article class="experience-item"><p class="meta">Sep 2026–present</p><div><h3>Figueroa Robotics Lab</h3><p class="position">Research Assistant · University of Pennsylvania</p><p>Working on making state-of-the-art manipulation policies human-interactive.</p></div></article>
  <article class="experience-item"><p class="meta">Jul 2025–Jul 2026</p><div><h3>Multi-Agent Robotic Motion Lab</h3><p class="position">Robotics Research Assistant · National University of Singapore</p><p>Developed sim-to-real pipelines for hierarchical reinforcement learning and reference-conditioned motion tracking across legged robot morphologies, with contributions to HeLoM and X-Morph.</p></div></article>
  <article class="experience-item"><p class="meta">Jul–Nov 2025</p><div><h3>Evolution Innovation Lab (Raye Lab)</h3><p class="position">Research Intern</p><p>Designed and built a PID-regulated fluidic controller with a touchscreen interface for programmable soft-robot actuation.</p></div></article>
  <article class="experience-item"><p class="meta">Aug–Dec 2024</p><div><h3>Wearable fabric electronics</h3><p class="position">Undergraduate Research · NUS · Supervised by Prof. Tural Khudiyev</p><p>Developed a soldering-based fabrication method for one-dimensional circuits with 96 micro-LEDs, and validated connectivity with an Arduino. Awarded a $5,000 project grant.</p></div></article>
</section>

<section id="skills">
  <div class="section-heading"><h2>Technical skills</h2></div>
  <dl class="skill-list">
    <dt>Learning &amp; control</dt><dd>Reinforcement learning, PPO, actor–critic methods, actuator modeling, motion tracking, PID control</dd>
    <dt>Robotics &amp; simulation</dt><dd>ROS, MuJoCo, Isaac Lab, Gazebo, Unitree SDK, HEBI SDK</dd>
    <dt>Programming</dt><dd>Python, C/C++, MATLAB, SQL, R</dd>
    <dt>Design &amp; fabrication</dt><dd>SolidWorks, Fusion 360, 3D printing, CNC machining, silicone actuator fabrication</dd>
    <dt>Embedded hardware</dt><dd>Arduino, ESP32, sensor integration, soldering, pneumatics</dd>
  </dl>
</section>

<section id="education">
  <div class="section-heading"><h2>Education</h2></div>
  <article class="experience-item"><p class="meta">Aug 2026–May 2028<br>(expected)</p><div><h3>University of Pennsylvania</h3><p class="position">Master's in Robotics</p><p>Coursework: Machine Learning, Machine Perception.</p></div></article>
  <article class="experience-item"><p class="meta">Aug 2022–Jul 2026</p><div><h3>National University of Singapore</h3><p class="position">B.Eng. in Mechanical Engineering · Highest Distinction</p><p>Robotics specialization · Minor in Management · GPA 4.68/5.00.<br>Dean's List (AY2025/26, Semester 1) and NUS College President's Honor Roll.</p></div></article>
</section>

<p class="more-link">Beyond research: assistive technology, engineering internships, community projects, and filmmaking. <a href="{{ '/more/' | relative_url }}">Explore more about me →</a></p>
