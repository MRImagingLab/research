---
layout: default
title: People
permalink: /people
---
<style>
.person-card{display:flex;flex-wrap:wrap;gap:20px;align-items:flex-start;margin:24px 0}
.person-left{flex:0 0 220px;max-width:240px;text-align:center}
.person-left img{display:block;width:180px!important;max-width:180px!important;height:auto;border-radius:8px}
.person-right{flex:1 1 520px;min-width:280px}
@media (max-width:768px){
  .person-card{flex-direction:column;align-items:center}
  .person-left{max-width:100%}
  .person-left img{width:140px!important;max-width:140px!important}
  .person-right{width:100%}
}
</style>

<section class="people-section">
  <h2>Faculty</h2>

  <div class="person-card">
    <!-- LEFT: photo + short intro -->
    <div class="person-left">
      <img src="{{ site.baseurl }}/assets/Sun_Changyu.jpg" alt="Dr. Changyu Sun">
      <h3>Dr. Changyu Sun</h3>
      <p><strong>Assistant Professor, NextGen Precision Health Investigator</strong></p>
      <p>Email: <a href="mailto:csyfc@missouri.edu">csyfc@missouri.edu</a></p>
      <p><strong>Office:</strong><br>
        1101 Hospital Drive, NextGen Precision Health Institute<br>
        Columbia, MO 65211, United States
      </p>
    </div>

    <!-- RIGHT: details -->
    <div class="person-right">
      <p><strong>Research Summary</strong><br>
      Dr. Sun is an MRI researcher focused on developing novel strategies for rapid MRI acquisition, accurate reconstruction, and quantitative analysis. His current research emphasizes novel physics‑ and data‑driven methods using deep learning, parallel imaging, non‑Cartesian sampling, and compressed sensing for cardiopulmonary applications. The ultimate goal is to enable fast, accurate, and automated MRI workflows for diagnosing and treating cardiopulmonary diseases.</p>

      <p><strong>Research Interests</strong><br>
      Data‑driven and physics‑driven MRI methods; Diagnosis and treatment of cardiopulmonary diseases</p>

      <p><strong>Areas of Expertise</strong><br>
      Magnetic Resonance Imaging (MRI); Artificial Intelligence in medical imaging; Image reconstruction and analysis; Rapid MRI; Cardiac MRI</p>

      <p><strong>Education & Training</strong><br>
      PhD, INSA de Lyon (2015) · Research Scientist, University of Virginia (2021) · Visiting faculty, King’s College London (2024)</p>

      <p><strong>Current Teaching</strong><br>
      Medical Image Processing — Biomedical Engineering Department, University of Missouri</p>
    </div>
  </div>
</section>


<section class="people-section">
  <h2>Trainees &amp; Staff</h2>

  <div class="person-card">
    <div class="person-left">
      <img src="{{ site.baseurl }}/assets/Nathan_Bresette.jpg" alt="Nathan Bresette">
      <h3>Nathan Bresette</h3>
      <p><strong>PhD Student</strong></p>
    </div>
    <div class="person-right">
      <p>Nathan Bresette</p>
    </div>
  </div>
</section>
