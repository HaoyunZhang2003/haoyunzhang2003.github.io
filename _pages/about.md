---
permalink: /
author_profile: true
stylesheets:
  - /assets/css/home.css
redirect_from:
  - /about/
  - /about.html
---

<section class="intro" id="about">
  <p class="eyebrow">Biomedical AI · Multimodal Learning · Computational Biology</p>
  <h1>Developing reliable and interpretable AI across <span>biological</span> and <span>clinical</span> data.</h1>
  <p class="intro-copy">I am an M.S. student in Biomedical Engineering at the <a href="https://bme.umich.edu/" target="_blank" rel="noopener">University of Michigan</a>. My research spans multimodal learning, single-cell bioinformatics, computational pathology, and medical imaging.</p>
  <p class="intro-copy">Across five research experiences, I have worked with data ranging from patient records and CT scans to histology and single cells, with the goal of building computational methods that remain biologically meaningful and clinically useful.</p>
  <div class="intro-actions">
    <a class="button button-primary" href="#research">Explore my research <span aria-hidden="true">↓</span></a>
    <a class="button button-quiet" href="/files/Haoyun_Zhang_CV.pdf">Download CV</a>
  </div>
  <div class="focus-strip" aria-label="Research focus areas">
    <div><span>01</span><strong>Multimodal learning</strong><small>Aligning heterogeneous biomedical data</small></div>
    <div><span>02</span><strong>Computational genomics</strong><small>Single-cell and spatial molecular analysis</small></div>
    <div><span>03</span><strong>Clinical translation</strong><small>Interpretable models for real clinical problems</small></div>
  </div>
</section>

<section class="section" id="news">
  <div class="section-heading">
    <p class="section-kicker">Now</p>
    <h2>Recent updates</h2>
  </div>
  <div class="news-list">
    <article><time>2025.08</time><p>Began the M.S. in Biomedical Engineering at the University of Michigan.</p></article>
    <article><time>2025.06</time><p>Began a new research direction on patient similarity and retrieval with Prof. Joyce Yanran Wang.</p></article>
    <article><time>2025.05</time><p>Our multicenter, multimodal IPF prognosis study was presented in <em>AJRCCM</em>.</p></article>
    <article><time>2024.11</time><p><em>easySCF</em> was published in <em>Bioinformatics</em>.</p></article>
  </div>
</section>

<section class="section" id="research">
  <div class="section-heading split-heading">
    <div><p class="section-kicker">Five experiences</p><h2>Research experience</h2></div>
    <p>My work connects machine learning with biomedical questions across clinical data, single-cell omics, histopathology, and medical imaging.</p>
  </div>

  <div class="research-grid">
    <article class="research-card research-new">
      <div class="research-body">
        <p class="research-meta">University of Michigan · 2025—Present</p>
        <h3>Patient Similarity & Retrieval <span class="status-badge">New direction</span></h3>
        <p>I recently began exploring patient similarity and retrieval under the supervision of Prof. Joyce Yanran Wang. This project is still at an early stage; more details will be added as the work develops.</p>
      </div>
    </article>

    <article class="research-card">
      <div class="research-visual cell-visual" aria-hidden="true">
        <div class="cell-orbit orbit-one"></div><div class="cell-orbit orbit-two"></div><div class="cell-core">64</div>
        <span class="module m1"></span><span class="module m2"></span><span class="module m3"></span><span class="module m4"></span><span class="module m5"></span><span class="module m6"></span>
      </div>
      <div class="research-body">
        <p class="research-meta">University of Michigan · 2025—Present</p>
        <h3>Biology-Informed Multimodal Alignment</h3>
        <p>FineCLS decomposes each cell into 64 biology-defined modules, producing interpretable embeddings and calibrated confidence signals for cross-modal retrieval.</p>
        <div class="tags"><span>Single-cell foundation models</span><span>Multimodal alignment</span></div>
      </div>
    </article>

    <article class="research-card">
      <img class="research-image research-image-contain" src="/images/histology-cnv.png" alt="Spatial clustering and phylogenetic analysis used in histology-based CNV inference">
      <div class="research-body">
        <p class="research-meta">Garmire Group, University of Michigan · 2024</p>
        <h3>GNN-Based Inference of CNV from Histopathology</h3>
        <p>Investigated copy-number variation inferred from H&amp;E images through spatial clustering, phylogenetic trees, cell trajectories, and pathway analysis.</p>
        <div class="tags"><span>Computational pathology</span><span>Spatial analysis</span><span>Cancer genomics</span></div>
      </div>
    </article>

    <article class="research-card">
      <img class="research-image" src="/images/ipf-prognosis.png" alt="ROC curves for one-, two-, and three-year IPF survival prediction">
      <div class="research-body">
        <p class="research-meta">SJTU & Shanghai Chest Hospital · 2023—2025</p>
        <h3>Multimodal Prognostic Modeling for IPF</h3>
        <p>Combined clinical indicators with CT imaging features to improve one-, two-, and three-year survival prediction, in close collaboration with physicians.</p>
        <div class="tags"><span>Survival analysis</span><span>3D imaging</span><span>Clinical translation</span></div>
      </div>
    </article>

    <article class="research-card">
      <img class="research-image research-image-contain" src="/images/easyscf-workflow.jpg" alt="easySCF cross-language single-cell data workflow and timing comparison">
      <div class="research-body">
        <p class="research-meta">Shanghai Jiao Tong University · 2023—2024</p>
        <h3>Development of Single-Cell Bioinformatics Packages</h3>
        <p>Developed a unified, efficient data format for moving large single-cell datasets between R and Python workflows, leading to the first-authored <em>easySCF</em> publication.</p>
        <div class="tags"><span>R / Python</span><span>Tool building</span><span>Scalable bioinformatics</span></div>
      </div>
    </article>
  </div>
</section>

<section class="section" id="publications">
  <div class="section-heading split-heading">
    <div><p class="section-kicker">Scholarship</p><h2>Publications</h2></div>
    <a class="text-link" href="https://scholar.google.com/citations?user=cYJ8e80AAAAJ" target="_blank" rel="noopener">Google Scholar ↗</a>
  </div>
  <div class="publication-list">
    <article class="publication-item featured-publication">
      <div class="pub-year">2024</div>
      <div class="pub-content">
        <p class="pub-venue">Bioinformatics · First author</p>
        <h3>easySCF: A Tool for Enhancing Interoperability Between R and Python for Efficient Single-Cell Data Analysis</h3>
        <p><strong>Haoyun Zhang*</strong>, Wentao Zhang*, Shuai Zhao, Guangyu Xu, Yi Shen, Feng Jiang, An Qin, Lei Cui.</p>
        <a href="https://doi.org/10.1093/bioinformatics/btae710" target="_blank" rel="noopener">Paper ↗</a>
        <a href="https://github.com/xleizi/easySCF" target="_blank" rel="noopener">Code ↗</a>
      </div>
    </article>
    <article class="publication-item">
      <div class="pub-year">2025</div>
      <div class="pub-content">
        <p class="pub-venue">American Journal of Respiratory and Critical Care Medicine</p>
        <h3>The Prognosis of Idiopathic Pulmonary Fibrosis in Chinese Patients: A Multi-Center and Multi-Modal Cohort Study</h3>
        <p>Feng Li, Zeyu Chen, <strong>Haoyun Zhang</strong>, et al.</p>
        <a href="https://doi.org/10.1164/ajrccm.2025.211.Abstracts.A1749" target="_blank" rel="noopener">Abstract ↗</a>
      </div>
    </article>
    <article class="publication-item">
      <div class="pub-year">2024</div>
      <div class="pub-content">
        <p class="pub-venue">Therapeutic Advances in Respiratory Disease</p>
        <h3>The Applications of CT with Artificial Intelligence in the Prognostic Model of Idiopathic Pulmonary Fibrosis</h3>
        <p>Zeyu Chen*, Zheng Lin*, Zihan Lin, Qi Zhang, <strong>Haoyun Zhang</strong>, et al.</p>
        <a href="https://doi.org/10.1177/17534666241282538" target="_blank" rel="noopener">Paper ↗</a>
      </div>
    </article>
    <article class="publication-item muted-publication">
      <div class="pub-year">Active</div>
      <div class="pub-content">
        <p class="pub-venue">Manuscripts under review / in preparation</p>
        <h3>Histology-to-spatial CNV prediction, interstitial lung abnormality outcomes, and multimodal IPF prognosis</h3>
        <p>Current collaborative manuscripts spanning computational pathology and pulmonary imaging.</p>
      </div>
    </article>
  </div>
  <p class="footnote">* Equal contribution.</p>
</section>

<section class="section" id="experience">
  <div class="section-heading"><p class="section-kicker">Trajectory</p><h2>Experience & education</h2></div>
  <div class="timeline">
    <article>
      <div class="timeline-date">2025—2027</div><div class="timeline-mark maize">M</div>
      <div><h3>University of Michigan</h3><p>M.S. in Biomedical Engineering · GPA 4.0/4.0</p><small>Research with Prof. Joyce Yanran Wang and Prof. Jie Liu</small></div>
    </article>
    <article>
      <div class="timeline-date">2025</div><div class="timeline-mark fosun">F</div>
      <div><h3>Fosun</h3><p>Algorithm Engineer Intern · Deep Learning for Ultrasound</p><small>Lung-ultrasound video models, TensorRT deployment, and edge inference</small></div>
    </article>
    <article>
      <div class="timeline-date">2024</div><div class="timeline-mark michigan">M</div>
      <div><h3>Garmire Group, University of Michigan</h3><p>Research Assistant · Computational Pathology</p><small>CNV inference from H&amp;E histology and downstream biological analysis</small></div>
    </article>
    <article>
      <div class="timeline-date">2021—2025</div><div class="timeline-mark sjtu">SJ</div>
      <div><h3>Shanghai Jiao Tong University</h3><p>B.Eng. in Biomedical Engineering · Minor in Mathematics & Applied Mathematics</p><small>Research across clinical AI, single-cell bioinformatics, and medical imaging</small></div>
    </article>
  </div>
</section>

<section class="section" id="honors">
  <div class="section-heading"><p class="section-kicker">Recognition</p><h2>Selected honors</h2></div>
  <div class="honors-grid">
    <article><strong>Top 0.01%</strong><h3>National Gold Medal</h3><p>China International College Students’ Innovation Competition · 2024</p></article>
    <article><strong>Top 1.5%</strong><h3>Honorable Mention</h3><p>World AI for Science Prize, Life Science Track</p></article>
    <article><strong>Top 2%</strong><h3>Chen Yazhu Scholarship</h3><p>Shanghai Jiao Tong University · 2024</p></article>
    <article><strong>International</strong><h3>Honorable Mention</h3><p>Mathematical Contest in Modeling · 2022</p></article>
  </div>
</section>

<section class="contact-panel" id="contact">
  <p class="section-kicker">Let’s connect</p>
  <h2>Interested in reliable AI for biomedical discovery?</h2>
  <p>I welcome conversations about multimodal learning, single-cell foundation models, computational pathology, medical imaging, and computational medicine.</p>
  <div class="intro-actions">
    <a class="button button-light" href="mailto:haoyunzh@umich.edu">haoyunzh@umich.edu</a>
    <a class="button button-outline-light" href="https://www.linkedin.com/in/haoyun-zhang-1278622bb" target="_blank" rel="noopener">LinkedIn ↗</a>
  </div>
</section>
