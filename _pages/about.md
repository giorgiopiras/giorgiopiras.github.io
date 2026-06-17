---
layout: hardik
permalink: /
title: "Giorgio Piras"
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

{% include base_path %}

<header class="header">
  <a href="{{ base_path }}/" class="logo">Giorgio Piras</a>

  <button class="menu-toggle" id="menu-toggle" aria-label="Toggle menu">
    <svg class="menu-icon" xmlns="http://www.w3.org/2000/svg" width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
      <line x1="3" y1="12" x2="21" y2="12"></line>
      <line x1="3" y1="6" x2="21" y2="6"></line>
      <line x1="3" y1="18" x2="21" y2="18"></line>
    </svg>
    <svg class="close-icon" xmlns="http://www.w3.org/2000/svg" width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
      <line x1="18" y1="6" x2="6" y2="18"></line>
      <line x1="6" y1="6" x2="18" y2="18"></line>
    </svg>
  </button>

  <nav class="nav" id="nav">
    <a href="{{ base_path }}/" class="nav-link active">About</a>
    <a href="#publications" class="nav-link">Publications</a>
    <a href="#cv" class="nav-link">CV</a>
  </nav>
</header>

<main>
  <section class="about-section">
    <div class="about-content">
      <p>
        I am a Postdoctoral Researcher at the <a href="https://www.saiferlab.ai/" target="_blank" rel="noopener">sAIfer lab</a>, in the Department of Electrical and Electronic Engineering at the University of Cagliari (UNICA), Italy. My research focuses on Adversarial Machine Learning and Large Language Models security.
      </p>
      <p>
        I got my BSc in Electrical, Electronic, and Computer Engineering in July 2019 with mark 110/110, and my MSc with honors in Computer Engineering, Artificial Intelligence and Cybersecurity in July 2021 from the University of Cagliari. In November 2021 I started my PhD at the Sapienza University of Rome in the context of the National PhD-AI program. I obtained my PhD with honors in January 2025 discussing the thesis titled <em>Adversarial Pruning: Improving Evaluations and Methods</em>, supervised by Prof. Battista Biggio.
      </p>
      <p>
        During my PhD, I have been a visiting student at the Karlsruhe Institute for Technology, Germany, supervised by Prof. Christian Wressnegger. I serve as a reviewer for conferences including NeurIPS, ICLR, AAAI, USENIX, and ACM CCS, and journals including Pattern Recognition, Neurocomputing, Machine Learning, and IEEE TIFS.
      </p>
      <div class="about-links">
        <a href="mailto:{{ site.author.email }}" class="about-link">
          <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"></path><polyline points="22,6 12,13 2,6"></polyline></svg>
          Email
        </a>
        <a href="{{ site.author.googlescholar }}" class="about-link" target="_blank" rel="noopener">
          <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M2 3h6a4 4 0 0 1 4 4v14a3 3 0 0 0-3-3H2z"></path><path d="M22 3h-6a4 4 0 0 0-4 4v14a3 3 0 0 1 3-3h7z"></path></svg>
          Scholar
        </a>
        <a href="https://github.com/{{ site.author.github }}" class="about-link" target="_blank" rel="noopener">
          <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true"><path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"></path></svg>
          GitHub
        </a>
        <a href="https://www.linkedin.com/in/{{ site.author.linkedin }}" class="about-link" target="_blank" rel="noopener">
          <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M20.45 20.45h-3.56v-5.57c0-1.33-.02-3.04-1.85-3.04-1.85 0-2.14 1.45-2.14 2.94v5.67H9.34V9h3.42v1.56h.05c.48-.9 1.64-1.85 3.37-1.85 3.61 0 4.27 2.37 4.27 5.46v6.28zM5.32 7.43a2.06 2.06 0 1 1 0-4.12 2.06 2.06 0 0 1 0 4.12zM7.1 20.45H3.54V9H7.1v11.45zM22.23 0H1.77C.79 0 0 .77 0 1.72v20.56C0 23.23.79 24 1.77 24h20.46c.98 0 1.77-.77 1.77-1.72V1.72C24 .77 23.21 0 22.23 0z"/></svg>
          LinkedIn
        </a>
        <a href="https://x.com/{{ site.author.twitter }}" class="about-link" target="_blank" rel="noopener">
          <svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 24 24" fill="currentColor" aria-hidden="true"><path d="M18.244 2.25h3.308l-7.227 8.26 8.502 11.24H16.17l-5.214-6.817L4.99 21.75H1.68l7.73-8.835L1.254 2.25H8.08l4.713 6.231zm-1.161 17.52h1.833L7.084 4.126H5.117z"/></svg>
          X
        </a>
      </div>
    </div>
    <div class="about-image">
      <img src="{{ '/images/profile.jpeg' | relative_url }}" alt="Giorgio Piras" class="profile-image">
    </div>
  </section>

  <section class="mt-4" id="publications">
    <div class="section-header">
      <h2 class="section-title">Publications</h2>
      <a href="{{ site.author.googlescholar }}" class="section-link" target="_blank" rel="noopener">View all &rarr;</a>
    </div>
    <div class="publications-list">
      {% assign selected_publications = site.publications | where: "selected", true | sort: "date" | reverse %}
      {% for pub in selected_publications %}
        <article class="publication-item">
          {% if pub.teaser %}
            <img src="{{ pub.teaser | relative_url }}" alt="Thumbnail for {{ pub.title }}" class="publication-thumbnail" loading="lazy">
          {% else %}
            <div class="publication-thumbnail"></div>
          {% endif %}
          <div class="publication-content">
            <h3><a href="{{ pub.paperurl | default: pub.url }}" target="_blank" rel="noopener">{{ pub.title }}</a></h3>
            {% if pub.authors %}
              <p class="publication-authors">{{ pub.authors }}</p>
            {% endif %}
            {% if pub.excerpt %}
              <p class="publication-summary">{{ pub.excerpt }}</p>
            {% endif %}
            <div class="publication-meta">
              {% if pub.venue %}<span class="publication-venue">{{ pub.venue }}</span>{% endif %}
              {% if pub.paperurl %}<span class="meta-separator">·</span><a href="{{ pub.paperurl }}" class="publication-link" target="_blank" rel="noopener">Paper</a>{% endif %}
              {% if pub.projecturl %}<span class="meta-separator">·</span><a href="{{ pub.projecturl }}" class="publication-link" target="_blank" rel="noopener">Project Page</a>{% endif %}
              {% if pub.codeurl %}<span class="meta-separator">·</span><a href="{{ pub.codeurl }}" class="publication-link" target="_blank" rel="noopener">Code</a>{% endif %}
            </div>
          </div>
        </article>
      {% endfor %}
    </div>
    <p class="scholar-box">For a full list of my publications, checkout my <a href="{{ site.author.googlescholar }}" target="_blank" rel="noopener">Google Scholar profile</a>!</p>
  </section>

  <section class="cv-section" id="cv">
    <h2 class="section-title">CV</h2>

    <h3>Education</h3>
    <ul>
      <li><strong>Postdoctoral Researcher</strong>, University of Cagliari, 1st November 2024 - ongoing.</li>
      <li><strong>Ph.D. in Artificial Intelligence</strong>, University of Rome La Sapienza / University of Cagliari, 24th January 2025, with honors. Thesis: <a href="https://tesidottorato.depositolegale.it/bitstream/20.500.14242/193911/1/Tesi_dottorato_Piras.pdf" target="_blank" rel="noopener"><em>Adversarial Pruning: Improving Evaluations and Methods</em></a>. Supervisor: Prof. Battista Biggio.</li>
      <li><strong>M.S. in Artificial Intelligence and Cybersecurity</strong>, University of Cagliari, 27th July 2021, with honors. Thesis: <em>On Explainability of Machine Learning DGA Detectors from DNS Traffic Data</em>.</li>
      <li><strong>B.S. in Electrical, Electronic and Computer Engineering</strong>, University of Cagliari, 25th July 2019, full marks. Thesis: <a href="https://corsi.unica.it/ingegneriaelettricaeelettronica/files/2020/04/Tesi_Piras_Giorgio.pdf" target="_blank" rel="noopener"><em>Utilizzabilita di Tecniche Affidabilistiche per la Manutenzione Predittiva di Stazioni Radio Base</em></a>.</li>
    </ul>

    <h3>Projects</h3>
    <ul>
      <li>Participation, with the University of Cagliari, in the EU HORIZON project <em>Security for AI and AI for Security</em> (Sec4AI4Sec), Grant Agreement no. 101120393.</li>
      <li>Participation, with the University of Cagliari, in the EU HORIZON project <em>A Comprehensive Trustworthy Framework for Connected Machine Learning and Secure Interconnected AI Solutions</em> (CoEvolution), Grant Agreement no. 101168560.</li>
    </ul>

    <h3>Work Experience</h3>
    <ul>
      <li><strong>12/2024 - 02/2025: AI Security Consultant</strong>, Consulthink, Rome, Italy. Project report on Secure AI strategies.</li>
      <li><strong>06/2024 - 07/2024: Consultant</strong>, Smeralda Computing &amp; Ass. S.r.l., Sassari, Italy. Project report: "Kentos" of the Autonomous Region of Sardinia.</li>
      <li><strong>03/2024 - 06/2024: Newspaper</strong>, L'Unione Sarda, Cagliari, Italy. Magazine articles on AI ethics.</li>
      <li><strong>06/2023 - 07/2023: Consultant</strong>, Smeralda Computing &amp; Ass. S.r.l., Sassari, Italy. Project report on the state of the Italian cybersecurity infrastructure.</li>
      <li><strong>03/2023 - 06/2023: Newspaper</strong>, L'Unione Sarda, Cagliari, Italy. Magazine articles on AI security.</li>
    </ul>

    <h3>Other Activities</h3>
    <ul>
      <li>Reviewer for NeurIPS, ICLR, AAAI, USENIX, ACM CCS, Pattern Recognition, Neurocomputing, Machine Learning, and IEEE TIFS.</li>
    </ul>

  </section>
  <div class="footer-spacer"></div>
</main>

<script>
  const toggle = document.getElementById("menu-toggle");
  const nav = document.getElementById("nav");

  toggle?.addEventListener("click", () => {
    nav?.classList.toggle("open");
    toggle.classList.toggle("open");
  });
</script>
