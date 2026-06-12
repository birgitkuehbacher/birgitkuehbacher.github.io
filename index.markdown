---
layout: mine
title: Birgit Kühbacher
---

<div class="profile-layout">
  <aside class="profile-card">
    <img class="profile-photo" src="{{ '/assets/me_fishbowl.jpg' | relative_url }}" alt="Photo">

    <h1>Birgit Kühbacher</h1>
    <p class="profile-role">PhD Student</p>
    <p class="profile-affiliation">
      <a href="https://www.helmholtz-munich.de/" target="_blank" rel="noopener">Helmholtz Munich</a>
      <a href="https://www.tum.de/" target="_blank" rel="noopener">Technical University of Munich (TUM)</a>
    </p>

    <div class="profile-links" aria-label="Academic and contact links">
      {%- for entry in site.minima.social_links -%}
        <a rel="me noopener" href="{{ entry.url }}" target="_blank" aria-label="{{ entry.title }}" title="{{ entry.title }}">
          <span class="{{ entry.icon }}" aria-hidden="true"></span>
        </a>
      {%- endfor -%}
    </div>
  </aside>

  <div class="profile-content">
    <section class="content-section">
      <p>
        I am a PhD student at Helmholtz Munich, supervised by
        <a href="https://sites.google.com/view/nikikilbertus/home">Niki Kilbertus</a>
        and
        <a href="https://www.pa.op.dlr.de/~/VeronikaEyring">Veronika Eyring</a>.
        As part of the
        <a href="https://www.cwi.nl/en/jobs/internships-for-phd-students-mfx/">CWI PhD Internship Program</a>,
        I had the pleasure of spending three months with the
        <a href="https://www.cwi.nl/en/research/scientific-computing/">Scientific Computing Group</a>
        in Amsterdam under the supervision of
        <a href="https://www.cwi.nl/en/people/daan-crommelin/">Daan Crommelin</a>.
      </p>

      <p>
        My research lies at the intersection of machine learning and Earth system science.
        I work on machine learning for weather forecasting and climate modeling, with a particular focus on uncertainty quantification, probabilistic machine learning, and the representation of unresolved processes.
        More broadly, I am interested in stochastic and data-driven model components, hybrid physical–machine learning approaches, and the long-term stability and generalization of machine learning methods in Earth system modeling.
      </p>

      <p>
        My current work focuses on generative and autoregressive models for climate ensembles.
        The goal is to develop machine learning methods that can generate physically plausible ensemble members and thereby help quantify internal variability and uncertainty in climate projections, particularly in settings where large ensembles are unavailable.
      </p>

      <p>
        Previously, I investigated stochastic machine learning parameterizations in chaotic dynamical systems, studying how different sources of uncertainty contribute to ensemble spread and forecast variability.
        Before that, I developed methods for training physically consistent and interpretable deep-learning-based climate model parameterizations by identifying and removing spurious non-physical relationships in the training data.
      </p>
    </section>

    <!--
    <section class="content-section">
      <h2>Research Interests</h2>
      <ul class="interest-list">
        <li>Machine learning for climate science</li>
      </ul>
    </section>
    -->

    <section class="content-section">
      <div class="section-heading">
        <h2>Publications</h2>
        <a class="section-link" href="https://scholar.google.com/citations?user=N4p5kuoAAAAJ">All publications</a>
      </div>

      <article class="publication">
        <p class="publication-year">2026 </p>
        <h3>Decomposing Ensemble Spread in Lorenz'96 With Learned Stochastic Parameterizations</h3>
        <p class="publication-authors"><strong>Birgit Kühbacher</strong>, Daan Crommelin, Niki Kilbertus</p>
        <p> Accepted at UAI 2026</p>
        <div class="publication-links">
          <a href="https://arxiv.org/abs/2605.22242">Paper</a>
          <!-- <a href="#">Code</a> -->
          <!-- <details class="publication-bibtex">
            <summary>Bib</summary>
            <div class="bibtex-panel">
              <button class="bibtex-copy" type="button" aria-label="Copy BibTeX citation" title="Copy BibTeX citation">
                <svg viewBox="0 0 24 24" aria-hidden="true">
                  <rect x="9" y="9" width="11" height="11" rx="2"></rect>
                  <path d="M15 9V6a2 2 0 0 0-2-2H6a2 2 0 0 0-2 2v7a2 2 0 0 0 2 2h3"></path>
                </svg>
              </button>
              <pre><code>{% raw %}@article{kuehbacherYEAR,
                author  = {Kühbacher, Birgit and Coauthor One and Coauthor Two},
                title   = {Publication title goes here},
                journal = {Venue},
                year    = {YEAR}
              }{% endraw %}</code></pre>
              <span class="bibtex-status" aria-live="polite"></span>
            </div>
          </details> -->
        </div>
      </article>

      <article class="publication">
        <p class="publication-year">2024 ICMLA</p>
        <h3>Towards Physically Consistent Deep Learning for Climate Model Parameterizations</h3>
        <p class="publication-authors"><strong>Birgit Kühbacher</strong>, Fernando Iglesias-Suarez, Niki Kilbertus, Veronika Eyring</p>
        <p> in 2024 International Conference on Machine Learning and Applications (ICMLA) </p>
        <div class="publication-links">
          <a href="https://arxiv.org/abs/2406.03920">Paper</a>
          <a href="https://github.com/EyringMLClimateGroup/kuehbacher24ICMLA_PCMasking">Code</a>
          <button class="bibtex-toggle" type="button" aria-expanded="false" aria-controls="bibtex-icmla">Bib</button>
        </div>
        <div class="bibtex-panel" id="bibtex-icmla" hidden>
          <button class="bibtex-copy" type="button" aria-label="Copy BibTeX citation" title="Copy BibTeX citation">
            <svg viewBox="0 0 24 24" aria-hidden="true">
              <rect x="9" y="9" width="11" height="11" rx="2"></rect>
              <path d="M15 9V6a2 2 0 0 0-2-2H6a2 2 0 0 0-2 2v7a2 2 0 0 0 2 2h3"></path>
            </svg>
          </button>
          <pre><code>{% raw %}@inproceedings{kuhbacher2024,
                title = {{Towards Physically Consistent Deep Learning For Climate Model Parameterizations}},
                booktitle = {2024 {{International Conference}} on {{Machine Learning}} and {{Applications}} ({{ICMLA}})},
                author = {K{\"u}hbacher, Birgit and {Iglesias-Suarez}, Fernando and Kilbertus, Niki and Eyring, Veronika},
                year = 2024,
                pages = {280--287},
                doi = {10.1109/ICMLA61862.2024.00044},
              }{% endraw %}</code></pre>
          <span class="bibtex-status" aria-live="polite"></span>
        </div>
      </article>

    </section>
  </div>
</div>
