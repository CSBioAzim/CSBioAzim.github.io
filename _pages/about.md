---
permalink: /
title: "About me"
excerpt: "Azim Dehghani Amirabad, Principal AI Scientist building foundation models, virtual cells and agentic AI for drug discovery."
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
@media (min-width:1024px){.page{padding-right:0 !important;}}

/* ---------- Hero ---------- */
.ab-hero{position:relative;overflow:hidden;background:linear-gradient(135deg,#f3f7fc 0%,#f6f1fb 60%,#fdf5ef 100%);border:1px solid #e3e9f1;border-radius:20px;padding:2.2em 2.2em 1.9em 2.2em;margin:0 0 2.4em 0;box-shadow:0 10px 30px rgba(46,109,164,0.08);}
.ab-hero::before{content:"";position:absolute;top:-90px;right:-70px;width:260px;height:260px;border-radius:50%;background:radial-gradient(circle,rgba(123,94,167,0.22) 0%,rgba(123,94,167,0) 70%);pointer-events:none;}
.ab-hero::after{content:"";position:absolute;bottom:-110px;left:-60px;width:280px;height:280px;border-radius:50%;background:radial-gradient(circle,rgba(46,109,164,0.18) 0%,rgba(46,109,164,0) 70%);pointer-events:none;}
.ab-hero > *{position:relative;z-index:1;}
.ab-hello{display:inline-block;font-size:0.8em;font-weight:700;letter-spacing:0.08em;text-transform:uppercase;color:#7b5ea7;background:rgba(255,255,255,0.75);border:1px solid #e4dcf0;border-radius:999px;padding:0.3em 0.9em;margin:0 0 0.9em 0;}
.ab-wave{display:inline-block;animation:ab-wave 2.4s ease-in-out infinite;transform-origin:70% 70%;}
@keyframes ab-wave{0%,60%,100%{transform:rotate(0deg);}10%,30%{transform:rotate(14deg);}20%{transform:rotate(-8deg);}40%{transform:rotate(-4deg);}50%{transform:rotate(10deg);}}
.ab-name{font-size:2.1em;font-weight:800;line-height:1.15;margin:0 0 0.2em 0;background:linear-gradient(90deg,#1f5f99 0%,#7b5ea7 60%,#c07a45 100%);-webkit-background-clip:text;background-clip:text;color:transparent;}
.ab-role{font-size:1em;font-weight:600;color:#4a5866;margin:0 0 1.2em 0;}
.ab-role span{color:#b7c1cc;margin:0 0.4em;}
.ab-hero p{font-size:1em;line-height:1.8;color:#3a4652;margin:0 0 1em 0;}
.ab-hero p strong{color:#1d2b36;background:linear-gradient(transparent 62%,rgba(123,94,167,0.18) 62%);}
.ab-actions{display:flex;flex-wrap:wrap;gap:0.6em;margin-top:1.4em;}
.ab-btn{display:inline-flex;align-items:center;gap:0.4em;font-size:0.86em;font-weight:600;padding:0.55em 1.2em;border-radius:999px;text-decoration:none !important;transition:all 0.18s ease;}
.ab-btn.primary{background:linear-gradient(90deg,#2e6da4,#5a6fc0);color:#fff !important;border:1px solid transparent;box-shadow:0 4px 12px rgba(46,109,164,0.25);}
.ab-btn.primary:hover{transform:translateY(-1px);box-shadow:0 6px 16px rgba(46,109,164,0.35);}
.ab-btn.ghost{background:rgba(255,255,255,0.85);color:#2e6da4 !important;border:1px solid #c9dced;}
.ab-btn.ghost:hover{background:#2e6da4;color:#fff !important;border-color:#2e6da4;transform:translateY(-1px);}

/* ---------- Section headers ---------- */
.ab-section{display:flex;align-items:center;gap:0.6em;font-size:1.3em;font-weight:700;color:#2c3e50;margin:2.2em 0 1em 0;}
.ab-section::after{content:"";flex:1;height:2px;background:linear-gradient(90deg,#d6e4f0,transparent);}
.ab-img{width:100%;border-radius:14px;border:1px solid #eef1f4;margin:0.5em 0 0.5em 0;box-shadow:0 4px 14px rgba(0,0,0,0.05);}

/* ---------- Journey (Short Bio) ---------- */
.ab-journey{position:relative;margin:0;padding:0 0 0 2.4em;}
.ab-journey::before{content:"";position:absolute;left:0.95em;top:0.6em;bottom:0.6em;width:3px;border-radius:3px;background:linear-gradient(180deg,#2e6da4,#7b5ea7,#d4915a);}
.ab-step{position:relative;background:#fff;border:1px solid #e8edf2;border-radius:12px;padding:1em 1.3em;margin:0 0 1em 0;box-shadow:0 1px 3px rgba(0,0,0,0.04);transition:transform 0.15s ease,box-shadow 0.15s ease;}
.ab-step:hover{transform:translateX(3px);box-shadow:0 6px 16px rgba(0,0,0,0.07);}
.ab-step .dot{position:absolute;left:-2.4em;top:0.85em;width:2em;height:2em;border-radius:50%;background:#fff;border:2px solid #d6e4f0;display:flex;align-items:center;justify-content:center;font-size:0.95em;box-shadow:0 2px 6px rgba(0,0,0,0.06);}
.ab-step .when{font-size:0.72em;font-weight:700;letter-spacing:0.05em;text-transform:uppercase;color:#7b5ea7;margin:0 0 0.2em 0;}
.ab-step .what{font-size:1em;font-weight:700;color:#1d2b36;margin:0 0 0.3em 0;}
.ab-step .detail{font-size:0.9em;line-height:1.65;color:#4a5560;}
.ab-step.now{border-color:#cfdcee;background:linear-gradient(135deg,#f5f9fd,#f8f4fc);}
.ab-step.now .dot{border-color:#2e6da4;}
.ab-fun{display:flex;align-items:center;gap:0.8em;background:#fffaf4;border:1px dashed #f0cfae;border-radius:12px;padding:0.85em 1.2em;margin:0.4em 0 0 2.4em;font-size:0.92em;color:#5a4a3a;line-height:1.6;}
.ab-fun .icon{font-size:1.5em;}

/* ---------- News ---------- */
.ab-timeline{position:relative;margin:0;padding:0;}
.ab-news{position:relative;margin:0 0 1em 0;padding:0.9em 1.3em;background:#fff;border:1px solid #e8edf2;border-left:4px solid #4a90c2;border-radius:10px;font-size:0.92em;line-height:1.6;color:#444;transition:transform 0.15s ease,box-shadow 0.15s ease;}
.ab-news:hover{transform:translateX(3px);box-shadow:0 4px 12px rgba(0,0,0,0.06);}
.ab-news.paper{border-left-color:#7b5ea7;}
.ab-news.talk{border-left-color:#d4915a;}
.ab-badge{display:inline-block;font-size:0.7em;font-weight:700;letter-spacing:0.04em;text-transform:uppercase;padding:0.15em 0.6em;border-radius:999px;margin-right:0.5em;vertical-align:middle;}
.paper .ab-badge{background:#f1ecf8;color:#5e4385;}
.talk .ab-badge{background:#fbf1e8;color:#a3672f;}
.ab-date{display:inline-block;font-size:0.75em;font-weight:600;color:#888;margin-right:0.6em;vertical-align:middle;}

/* ---------- Students ---------- */
.ab-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:1.2em;}
@media (max-width:600px){.ab-grid{grid-template-columns:1fr;}.ab-hero{padding:1.6em 1.3em;}.ab-name{font-size:1.7em;}}
.ab-person{background:#fff;border:1px solid #e8edf2;border-radius:12px;padding:1.2em 1.4em;transition:transform 0.15s ease,box-shadow 0.15s ease;}
.ab-person:hover{transform:translateY(-2px);box-shadow:0 6px 16px rgba(0,0,0,0.07);}
.ab-person .name{font-weight:700;color:#1d2b36;font-size:0.98em;}
.ab-person .school{font-size:0.8em;color:#7b5ea7;font-weight:600;margin:0.15em 0 0.45em 0;}
.ab-person .topic{font-size:0.86em;color:#555;line-height:1.5;}

/* ---------- Awards ---------- */
.ab-awards{list-style:none;margin:0;padding:0;}
.ab-awards li{display:flex;gap:0.7em;align-items:flex-start;background:#fff;border:1px solid #e8edf2;border-radius:10px;padding:0.7em 1em;margin:0 0 0.7em 0;font-size:0.92em;line-height:1.55;color:#444;}
.ab-awards .icon{font-size:1.2em;line-height:1.3;}
</style>

<div class="ab-hero">
<div class="ab-hello"><span class="ab-wave">👋</span> Hello, welcome!</div>
<div class="ab-name">I'm Azim Dehghani Amirabad</div>
<div class="ab-role">Principal AI Scientist<span>•</span>Johnson &amp; Johnson Innovative Medicine</div>
<p>I am a Principal AI Scientist working at the intersection of AI, machine learning, and computational biology. I build foundation models and AI systems that integrate multimodal biological data, from genomics and proteomics to imaging and scientific literature, to accelerate scientific discovery and therapeutic innovation.</p>
<p>Over the past decade, I have led AI-driven research across drug discovery, translational science, and biopharmaceutical R&amp;D. My current focus includes <strong>virtual cells</strong>, <strong>biological world models</strong>, and <strong>agentic AI</strong> that predict cellular responses and guide experiments, accelerating the path from data to therapies.</p>
<div class="ab-actions">
<a class="ab-btn primary" href="mailto:azim.dehghani@gmail.com">✉️ Get in touch</a>
<a class="ab-btn ghost" href="https://scholar.google.com/citations?user=Zg2wZtQAAAAJ&amp;hl=en">🎓 Google Scholar</a>
<a class="ab-btn ghost" href="https://www.linkedin.com/in/azimdehghani/">💼 LinkedIn</a>
</div>
</div>

<img class="ab-img" src='/images/Azim_ResearchSummaryFinal.png' alt="Overview of my research, from multimodal representation learning toward virtual cells">

<div class="ab-section">🧭 My Journey</div>

<div class="ab-journey">
<div class="ab-step">
<div class="dot">🎓</div>
<div class="when">Master's</div>
<div class="what">Bioinformatics</div>
<div class="detail"><a href="https://www.mpi-inf.mpg.de/home/">Max Planck Institute for Informatics</a> and <a href="https://zbi-www.bioinf.uni-sb.de/en">Saarland University</a>, Germany</div>
</div>
<div class="ab-step">
<div class="dot">🔬</div>
<div class="when">PhD</div>
<div class="what">Computer Science</div>
<div class="detail"><a href="https://www.imprs-cs.de/">International Max Planck Research School for Computer Science</a> at the Max Planck Institute for Informatics, advised by <a href="https://schulzlab.github.io/MS.html">Prof. Marcel Schulz</a>. Visiting student in <a href="http://fraenkel.mit.edu/">Prof. Ernest Fraenkel's lab</a> at MIT.</div>
</div>
<div class="ab-step">
<div class="dot">🧬</div>
<div class="when">2019 – 2021</div>
<div class="what">Postdoctoral Research Associate</div>
<div class="detail"><a href="https://www.broadinstitute.org/">Broad Institute of MIT and Harvard</a> and <a href="https://www.csail.mit.edu/">MIT CSAIL</a>, with <a href="http://compbio.mit.edu/compbio.html">Prof. Manolis Kellis</a></div>
</div>
<div class="ab-step now">
<div class="dot">🚀</div>
<div class="when">Today</div>
<div class="what">Principal AI Scientist</div>
<div class="detail"><a href="https://www.jnj.com/">Johnson &amp; Johnson Innovative Medicine</a>, building foundation models, virtual cells, and agentic AI for drug discovery</div>
</div>
</div>

<div class="ab-fun"><span class="icon">⚽</span><span>Outside the lab, you'll find me playing soccer or hiking. My favorite player? <a href="https://www.youtube.com/watch?v=OUKGsb8CpF8&amp;t=412s">Cristiano Ronaldo</a>, of course!</span></div>

<div class="ab-section">📰 News</div>

<div class="ab-timeline">
<div class="ab-news paper"><span class="ab-date">Oct 2026</span><span class="ab-badge">Paper</span>Our work <a href="https://arxiv.org/abs/2610.28579">Spatially Informed and Direction Sensitive Representation Learning for Spatial Transcriptomics</a> was accepted at the NeurIPS 2026 AI4DD Workshop! 🎉</div>
<div class="ab-news paper"><span class="ab-date">Oct 2026</span><span class="ab-badge">Paper</span>Our work <a href="https://arxiv.org/abs/2610.14853">Disentangling Marginal Capacity from Geometry in Optimal-Transport Label Transfer</a> was accepted at NeurIPS 2026! 🎉</div>
<div class="ab-news paper"><span class="ab-date">Oct 2026</span><span class="ab-badge">Paper</span>Our work <a href="https://arxiv.org/abs/2610.04475">VCLMU: Mechanism-Centric Virtual Cell World Modeling for Perturbation Response</a> was accepted at NeurIPS 2026! 🎉</div>
<div class="ab-news talk"><span class="ab-date">Oct 2026</span><span class="ab-badge">Talk</span>Invited talk on <strong>Scaling AI across Pharma R&amp;D</strong> at <a href="https://www.aidrivendrugdevelopment.com/speakers-7lf7">AIDDD</a>. 🎤</div>
<div class="ab-news paper"><span class="ab-date">2026</span><span class="ab-badge">Paper</span>Our work <a href="https://arxiv.org/abs/2608.14924">PaSTel</a>, bridging histology and spatial transcriptomics through multimodal, bio-prior-guided contrastive pretraining, was published at ICML 2026! 🎉</div>
<div class="ab-news talk"><span class="ab-date">Jun 2026</span><span class="ab-badge">Talk</span>Invited talk on <strong>AI in Biotech: Accelerating Drug Discovery &amp; Development</strong> at <a href="https://futurebiotechexpo.com/conference/speakers">Future Biotech Expo</a>. 🎤</div>
<div class="ab-news talk"><span class="ab-date">Oct 2025</span><span class="ab-badge">Talk</span>Invited talk on <strong>AI's Impact on the Future of Biotechnology</strong> at <a href="https://neet.mit.edu/threads/lm">MIT Department of Engineering</a>. 🎤</div>
<div class="ab-news talk"><span class="ab-date">2025</span><span class="ab-badge">Talk</span>Invited talk at <a href="https://bostonbiotechnologysummit.com/program/speakers/">Boston Biotech Summit 2025</a> on <strong>how AI is transforming value creation in biotech</strong> (<a href="https://www.cpl.com/blog/2025/07/ai-transforms-digital-health-key-insights-from-recent-biotech-summits">see blog about my talk</a>). 🎤</div>
<div class="ab-news paper"><span class="ab-date">Jul 2025</span><span class="ab-badge">Paper</span>Presented our paper on a <strong>multimodal foundation model for gRNA activity prediction</strong> at ICML 2025, Vancouver (<a href="https://openreview.net/pdf/53cf4d58ae4c7f9bee4b2f82d0d81d4a54fe65bb.pdf">full text</a>). 🎉</div>
<div class="ab-news talk"><span class="ab-date">2024</span><span class="ab-badge">Talk</span>Invited talk at <a href="https://bostonbiotechnologysummit.com/program/speakers/">Boston Biotech Summit 2024</a> on <strong>AI applications in the biotech and pharmaceutical industry</strong> (<a href="https://www.youtube.com/watch?v=enxpQX6PFiQ">watch my pre-summit interview</a>). 🎤</div>
</div>

<div class="ab-section">🎓 Students &amp; Interns</div>

<div class="ab-grid">
<div class="ab-person"><div class="name">Ali Khodabandeh</div><div class="school">University of Central Florida</div><div class="topic">Multimodal foundation models for spatial omics and scRNA-seq</div></div>
<div class="ab-person"><div class="name">Yuwei Miao</div><div class="school">University of Texas</div><div class="topic">Foundation models for virtual cells</div></div>
<div class="ab-person"><div class="name">Junchao Zhu</div><div class="school">Vanderbilt University</div><div class="topic">Multimodal foundation model for spatial omics</div></div>
<div class="ab-person"><div class="name">Sophie Guo</div><div class="school">MIT</div><div class="topic">Generative modeling of perturbational single-cell data</div></div>
</div>

<div class="ab-section">🏆 Awards</div>

<ul class="ab-awards">
<li><span class="icon">🌟</span><span><strong>INSPIRE Award at J&amp;J</strong>, in recognition of exceptional leadership and scientific contribution (2023–2025)</span></li>
<li><span class="icon">🎓</span><span><a href="https://www.imprs-cs.de/">International Max Planck Research School for Computer Science (IMPRS-CS)</a> PhD Fellowship</span></li>
<li><span class="icon">✈️</span><span><a href="https://www.daad.de/en/">DAAD</a> fellowship for a doctoral research visit at MIT</span></li>
<li><span class="icon">🎫</span><span>Travel fellowship for the German Conference on Bioinformatics 2016</span></li>
<li><span class="icon">🎫</span><span>Travel fellowship for <a href="https://irbgroup.org/">ISMB-SIG 2016</a></span></li>
</ul>
