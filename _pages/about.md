---
layout: page
title: Home
permalink: /
nav: false
_styles: |
  @import url("/assets/css/research-home.css");
---

<div class="research-site">
  <nav class="research-nav" aria-label="Primary navigation">
    <div class="research-inner research-nav-inner">
      <a class="research-brand" href="#home">Yixuan Feng</a>
      <div class="research-nav-links">
        <a href="#home">Home</a>
        <a href="#projects">Projects</a>
        <a href="#publications">Publications</a>
        <a href="#about-me">About me</a>
        <a href="#contact">Contact</a>
      </div>
    </div>
  </nav>

  <section class="research-section research-hero" id="home" aria-labelledby="home-title">
    <div class="research-inner research-hero-inner">
      <div>
        <div class="research-name-line">
          <h1 id="home-title">Yixuan Feng</h1>
          <span class="research-name-native" lang="zh">冯艺漩</span>
        </div>
        <p class="research-lead">PhD candidate in Hydraulic Engineering at Tsinghua University.</p>
        <p class="research-muted">My research lies at the intersection of environmental clay science and physical chemistry, combining molecular simulation and machine learning potentials with multiscale analysis of collective molecular behavior to understand the structure and reactivity of mineral–water interfaces.</p>
      </div>
      <img class="research-portrait" src="{{ '/assets/img/yixuan-feng-portrait.jpg' | relative_url }}" alt="Portrait of Yixuan Feng" width="640" height="640">
    </div>
  </section>

  <section class="research-section" id="projects" aria-labelledby="projects-title">
    <div class="research-inner">
      <h2 id="projects-title">Projects</h2>
      <div class="research-project">
        <div class="research-project-image" aria-hidden="true"><span>Proton transfer</span></div>
        <div>
          <h3>Dynamic proton transfer at clay edges</h3>
          <p class="research-muted">How do clay edges exchange protons with water, and how does pH change their surface charge?</p>
          <details><summary>Research overview</summary><p>Using molecular dynamics driven by machine learning potentials with first-principles accuracy, this work examines montmorillonite nanoparticles across acidic, neutral, and basic conditions. The simulations show that edge sites respond to pH and can transfer protons through direct and solvent-mediated pathways, demonstrating that montmorillonite edges are not static arrays of hydroxyl groups but dynamic, proton-conducting networks.</p></details>
          <p class="research-project-link"><a href="https://doi.org/10.1021/acs.jpclett.5c03748">Read the paper <span aria-hidden="true">↗</span></a></p>
        </div>
      </div>
      <div class="research-project">
        <div class="research-project-image" aria-hidden="true"><span>Interfacial water</span></div>
        <div>
          <h3>Water networks at charged clay interfaces</h3>
          <p class="research-muted">Looking beyond water layering to understand how hydrogen-bond networks reorganize near mineral surfaces.</p>
          <details><summary>Research overview</summary><p>This study combines conventional molecular descriptors with hierarchical analysis of hydrogen-bond connectivity at montmorillonite–NaCl interfaces. It characterizes the local density and orientational ordering of interfacial water, together with the cooperative organization of its hydrogen-bond network. By tracking the spatial evolution of medium-range structures across different electrolyte concentrations and surface charge densities, the analysis divides the interface into distinct structural regions and identifies a consistent boundary approximately 7.8 Å from the surface.</p></details>
          <p class="research-project-link"><a href="https://doi.org/10.1063/5.0311238">Read the paper <span aria-hidden="true">↗</span></a></p>
        </div>
      </div>
      <div class="research-project">
        <div class="research-project-image" aria-hidden="true"><span>Hydrogen-bond networks</span></div>
        <div>
          <h3>Mapping hydrogen-bond networks in salt solutions</h3>
          <p class="research-muted">A graph-based view of how salt reshapes water structures across several length scales.</p>
          <details><summary>Research overview</summary><p>We developed a hierarchical clustering approach that describes hydrogen-bonded water as rings, fragments, and larger clusters. Applied to NaCl solutions, it reveals how increasing salt concentration changes the size, connectivity, and lifetime of these structures, linking local ion hydration to broader network behavior.</p></details>
          <p class="research-project-link"><a href="https://doi.org/10.1039/d2cp00099g">Read the paper <span aria-hidden="true">↗</span></a></p>
        </div>
      </div>
    </div>
  </section>

  <section class="research-section" id="publications" aria-labelledby="publications-title">
    <div class="research-inner">
      <h2 id="publications-title">Publications</h2>
      <div class="research-publications">
        {% bibliography %}
      </div>
    </div>
  </section>

  <section class="research-section" id="about-me" aria-labelledby="about-title">
    <div class="research-inner">
      <h2 id="about-title">About me</h2>
      <div class="research-about">
        <div class="research-about-intro">
          <p>My work has evolved from studying environmental transport at the continuum scale to investigating structure and reactivity at mineral–water interfaces at the molecular scale. Across these areas, I am interested in connecting microscopic mechanisms with macroscopic environmental behavior.</p>
        </div>
        <div class="research-journey">
          <h3 id="journey-title">Academic journey</h3>
          <div class="research-timeline" aria-labelledby="journey-title">
            <div class="research-timeline-item">
              <p class="research-timeline-date">2020–present</p>
              <div>
                <h4>PhD Candidate in Hydraulic Engineering</h4>
                <p>Department of Hydraulic Engineering, Tsinghua University, China</p>
              </div>
            </div>
            <div class="research-timeline-item">
              <p class="research-timeline-date">2024–2025</p>
              <div>
                <h4>Visiting Graduate Student</h4>
                <p>Department of Physics, University of Cambridge, United Kingdom</p>
              </div>
            </div>
            <div class="research-timeline-item">
              <p class="research-timeline-date">2016–2020</p>
              <div>
                <h4>Bachelor of Engineering in Harbour, Waterway and Coastal Engineering</h4>
                <p>Ocean College, Zhejiang University, China</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="research-section" id="contact" aria-labelledby="contact-title">
    <div class="research-inner">
      <h2 id="contact-title">Contact</h2>
      <div class="research-contact">
        <div><strong>Email</strong><a href="mailto:feng-yx20@mails.tsinghua.edu.cn">feng-yx20@mails.tsinghua.edu.cn</a></div>
        <div><strong>ORCID</strong><a href="https://orcid.org/0000-0001-5614-7480">0000-0001-5614-7480</a></div>
        <div><strong>Google Scholar</strong><a href="https://scholar.google.com/citations?user=gbgdjLwAAAAJ">View publications</a></div>
      </div>
    </div>
  </section>
</div>
