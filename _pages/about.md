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
.ab-hero{position:relative;overflow:hidden;background:linear-gradient(135deg,#071426 0%,#0b2240 40%,#0e3050 75%,#0f3d55 100%);border:1px solid #17375c;border-radius:20px;padding:2.2em 2.2em 1.9em 2.2em;margin:0 0 2.4em 0;box-shadow:0 14px 36px rgba(7,20,38,0.35);}
.ab-hero .ab-net{position:absolute;inset:0;width:100%;height:100%;z-index:0;pointer-events:none;}
.ab-pulse{animation:ab-pulse 3.2s ease-in-out infinite;}
@keyframes ab-pulse{0%,100%{fill-opacity:0.35;}50%{fill-opacity:0.9;}}
@media (max-width:700px){.ab-hero .ab-net{opacity:0.55;}}
.ab-hero::before{content:"";position:absolute;top:-100px;right:-80px;width:300px;height:300px;border-radius:50%;background:radial-gradient(circle,rgba(79,227,193,0.22) 0%,rgba(79,227,193,0) 70%);pointer-events:none;}
.ab-hero::after{content:"";position:absolute;bottom:-120px;left:-70px;width:320px;height:320px;border-radius:50%;background:radial-gradient(circle,rgba(95,150,255,0.22) 0%,rgba(95,150,255,0) 70%);pointer-events:none;}
.ab-hero > *{position:relative;z-index:1;}
.ab-hero a{color:#9fd0ff;}
.ab-hello{display:inline-block;font-size:0.8em;font-weight:700;letter-spacing:0.08em;text-transform:uppercase;color:#d9ccff;background:rgba(255,255,255,0.08);border:1px solid rgba(255,255,255,0.18);border-radius:999px;padding:0.3em 0.9em;margin:0 0 0.9em 0;}
.ab-wave{display:inline-block;animation:ab-wave 2.4s ease-in-out infinite;transform-origin:70% 70%;}
@keyframes ab-wave{0%,60%,100%{transform:rotate(0deg);}10%,30%{transform:rotate(14deg);}20%{transform:rotate(-8deg);}40%{transform:rotate(-4deg);}50%{transform:rotate(10deg);}}
.ab-name{font-size:2.1em;font-weight:800;line-height:1.15;margin:0 0 0.2em 0;background:linear-gradient(90deg,#ffffff 0%,#cfe4ff 45%,#d8c8ff 75%,#ffd6b0 100%);-webkit-background-clip:text;background-clip:text;color:transparent;}
.ab-role{font-size:1em;font-weight:600;color:#a9bdd6;margin:0 0 1.2em 0;}
.ab-role span{color:#5c7398;margin:0 0.4em;}
.ab-hero p{font-size:1em;line-height:1.8;color:#dbe5f2;margin:0 0 1em 0;}
.ab-hero p strong{color:#fff;background:linear-gradient(transparent 62%,rgba(160,130,255,0.35) 62%);}
.ab-actions{display:flex;flex-wrap:wrap;gap:0.6em;margin-top:1.4em;}
.ab-btn{display:inline-flex;align-items:center;gap:0.4em;font-size:0.86em;font-weight:600;padding:0.55em 1.2em;border-radius:999px;text-decoration:none !important;transition:all 0.18s ease;}
.ab-btn.primary{background:#fff;color:#132f57 !important;border:1px solid #fff;box-shadow:0 4px 14px rgba(0,0,0,0.25);}
.ab-btn.primary:hover{transform:translateY(-1px);background:#eaf2ff;}
.ab-btn.ghost{background:rgba(255,255,255,0.06);color:#fff !important;border:1px solid rgba(255,255,255,0.35);}
.ab-btn.ghost:hover{background:rgba(255,255,255,0.18);border-color:rgba(255,255,255,0.6);transform:translateY(-1px);}

/* ---------- Section headers ---------- */
.ab-section{display:flex;align-items:center;gap:0.6em;font-size:1.3em;font-weight:800;color:#132f57;margin:2.6em 0 1.1em 0;letter-spacing:-0.01em;}
.ab-section::after{content:"";flex:1;height:3px;border-radius:3px;background:linear-gradient(90deg,#132f57 0%,#5a6fc0 25%,rgba(212,145,90,0.5) 50%,transparent 100%);}
.ab-figure{background:#fff;border:1px solid #e3e9f1;border-radius:16px;padding:0.8em;box-shadow:0 6px 20px rgba(19,47,87,0.06);}
.ab-img{display:block;width:100%;border-radius:10px;margin:0;}
.ab-caption{font-size:0.82em;color:#6b7785;text-align:center;margin:0.6em 0 0.1em 0;font-style:italic;}

/* ---------- Journey (Short Bio) ---------- */
.ab-bio{position:relative;overflow:hidden;background:linear-gradient(135deg,#ffffff 0%,#f7f9fd 100%);border:1px solid #e3e9f1;border-radius:16px;padding:1.5em 1.7em 1.4em 2em;box-shadow:0 6px 20px rgba(19,47,87,0.06);}
.ab-bio::before{content:"";position:absolute;left:0;top:0;bottom:0;width:5px;background:linear-gradient(180deg,#132f57,#5a6fc0,#d4915a);}
.ab-bio::after{content:"🧭";position:absolute;right:0.6em;top:0.2em;font-size:4.5em;opacity:0.07;pointer-events:none;}
.ab-bio p{position:relative;font-size:0.96em;line-height:1.85;color:#3e4a56;margin:0 0 1em 0;}
.ab-bio p:last-child{margin:0;}
.ab-bio p:first-child::first-letter{float:left;font-size:2.9em;line-height:0.9;font-weight:800;color:#132f57;margin:0.08em 0.12em 0 0;}
.ab-bio a{color:#1f4f86;font-weight:600;text-decoration:none !important;background:linear-gradient(transparent 70%,rgba(90,111,192,0.18) 70%);transition:background 0.15s ease;}
.ab-bio a:hover{background:linear-gradient(transparent 0%,rgba(90,111,192,0.18) 0%);}
.ab-bio .now{display:inline-block;font-size:0.72em;font-weight:700;letter-spacing:0.05em;text-transform:uppercase;color:#fff;background:#132f57;border-radius:999px;padding:0.15em 0.65em;margin-right:0.3em;vertical-align:middle;}
.ab-fun{display:flex;align-items:center;gap:0.8em;background:#fffaf4;border:1px dashed #f0cfae;border-radius:12px;padding:0.85em 1.2em;margin:1em 0 0 0;font-size:0.92em;color:#5a4a3a;line-height:1.6;}
.ab-fun .icon{font-size:1.5em;}

/* ---------- News ---------- */
.ab-timeline{position:relative;margin:0;padding:0;}
.ab-news{position:relative;margin:0 0 0.9em 0;padding:0.95em 1.3em;background:#fff;border:1px solid #e3e9f1;border-left:4px solid #4a90c2;border-radius:12px;font-size:0.92em;line-height:1.6;color:#444;box-shadow:0 2px 8px rgba(19,47,87,0.04);transition:transform 0.15s ease,box-shadow 0.15s ease;}
.ab-news:hover{transform:translateX(4px);box-shadow:0 8px 18px rgba(19,47,87,0.09);}
.ab-news a{color:#1f4f86;font-weight:600;}
.ab-news.paper{border-left-color:#7b5ea7;}
.ab-news.talk{border-left-color:#d4915a;}
.ab-badge{display:inline-block;font-size:0.7em;font-weight:700;letter-spacing:0.04em;text-transform:uppercase;padding:0.15em 0.6em;border-radius:999px;margin-right:0.5em;vertical-align:middle;}
.paper .ab-badge{background:#f1ecf8;color:#5e4385;}
.talk .ab-badge{background:#fbf1e8;color:#a3672f;}
.ab-date{display:inline-block;font-size:0.75em;font-weight:600;color:#888;margin-right:0.6em;vertical-align:middle;}

/* ---------- Students ---------- */
.ab-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:1.2em;}
@media (max-width:600px){.ab-grid{grid-template-columns:1fr;}.ab-hero{padding:1.6em 1.3em;}.ab-name{font-size:1.7em;}}
.ab-person{display:flex;gap:1em;align-items:flex-start;background:#fff;border:1px solid #e3e9f1;border-radius:14px;padding:1.1em 1.3em;box-shadow:0 2px 8px rgba(19,47,87,0.04);transition:transform 0.15s ease,box-shadow 0.15s ease;}
.ab-person:hover{transform:translateY(-3px);box-shadow:0 10px 22px rgba(19,47,87,0.1);}
.ab-avatar{flex:0 0 auto;width:2.8em;height:2.8em;border-radius:50%;display:flex;align-items:center;justify-content:center;font-weight:800;font-size:0.95em;color:#fff;background:linear-gradient(135deg,#132f57,#5a6fc0);box-shadow:0 3px 8px rgba(19,47,87,0.25);}
.ab-person .name{font-weight:700;color:#1d2b36;font-size:0.98em;}
.ab-person .school{font-size:0.8em;color:#7b5ea7;font-weight:600;margin:0.15em 0 0.45em 0;}
.ab-person .topic{font-size:0.86em;color:#555;line-height:1.5;}

/* ---------- Awards ---------- */
.ab-awards{list-style:none;margin:0;padding:0;display:grid;grid-template-columns:repeat(2,1fr);gap:0.9em;}
@media (max-width:600px){.ab-awards{grid-template-columns:1fr;}}
.ab-awards li{display:flex;gap:0.8em;align-items:center;background:#fff;border:1px solid #e3e9f1;border-radius:12px;padding:0.85em 1.1em;margin:0;font-size:0.92em;line-height:1.55;color:#444;box-shadow:0 2px 8px rgba(19,47,87,0.04);transition:transform 0.15s ease,box-shadow 0.15s ease;}
.ab-awards li:hover{transform:translateY(-2px);box-shadow:0 8px 18px rgba(19,47,87,0.09);}
.ab-awards .icon{flex:0 0 auto;width:2.2em;height:2.2em;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:1.05em;background:#f1f4fa;}</style>

<div class="ab-hero">
<svg class="ab-net" viewBox="0 0 840 470" preserveAspectRatio="xMaxYMid slice" aria-hidden="true"><g stroke="#7fb8ff" stroke-opacity="0.13" stroke-width="1"><line x1="520" y1="60" x2="610" y2="40"/><line x1="520" y1="60" x2="610" y2="120"/><line x1="520" y1="60" x2="610" y2="200"/><line x1="520" y1="60" x2="610" y2="280"/><line x1="520" y1="60" x2="610" y2="360"/><line x1="520" y1="60" x2="610" y2="430"/><line x1="520" y1="140" x2="610" y2="40"/><line x1="520" y1="140" x2="610" y2="120"/><line x1="520" y1="140" x2="610" y2="200"/><line x1="520" y1="140" x2="610" y2="280"/><line x1="520" y1="140" x2="610" y2="360"/><line x1="520" y1="140" x2="610" y2="430"/><line x1="520" y1="220" x2="610" y2="40"/><line x1="520" y1="220" x2="610" y2="120"/><line x1="520" y1="220" x2="610" y2="200"/><line x1="520" y1="220" x2="610" y2="280"/><line x1="520" y1="220" x2="610" y2="360"/><line x1="520" y1="220" x2="610" y2="430"/><line x1="520" y1="300" x2="610" y2="40"/><line x1="520" y1="300" x2="610" y2="120"/><line x1="520" y1="300" x2="610" y2="200"/><line x1="520" y1="300" x2="610" y2="280"/><line x1="520" y1="300" x2="610" y2="360"/><line x1="520" y1="300" x2="610" y2="430"/><line x1="520" y1="380" x2="610" y2="40"/><line x1="520" y1="380" x2="610" y2="120"/><line x1="520" y1="380" x2="610" y2="200"/><line x1="520" y1="380" x2="610" y2="280"/><line x1="520" y1="380" x2="610" y2="360"/><line x1="520" y1="380" x2="610" y2="430"/><line x1="610" y1="40" x2="700" y2="80"/><line x1="610" y1="40" x2="700" y2="170"/><line x1="610" y1="40" x2="700" y2="260"/><line x1="610" y1="40" x2="700" y2="350"/><line x1="610" y1="120" x2="700" y2="80"/><line x1="610" y1="120" x2="700" y2="170"/><line x1="610" y1="120" x2="700" y2="260"/><line x1="610" y1="120" x2="700" y2="350"/><line x1="610" y1="200" x2="700" y2="80"/><line x1="610" y1="200" x2="700" y2="170"/><line x1="610" y1="200" x2="700" y2="260"/><line x1="610" y1="200" x2="700" y2="350"/><line x1="610" y1="280" x2="700" y2="80"/><line x1="610" y1="280" x2="700" y2="170"/><line x1="610" y1="280" x2="700" y2="260"/><line x1="610" y1="280" x2="700" y2="350"/><line x1="610" y1="360" x2="700" y2="80"/><line x1="610" y1="360" x2="700" y2="170"/><line x1="610" y1="360" x2="700" y2="260"/><line x1="610" y1="360" x2="700" y2="350"/><line x1="610" y1="430" x2="700" y2="80"/><line x1="610" y1="430" x2="700" y2="170"/><line x1="610" y1="430" x2="700" y2="260"/><line x1="610" y1="430" x2="700" y2="350"/><line x1="700" y1="80" x2="790" y2="130"/><line x1="700" y1="80" x2="790" y2="230"/><line x1="700" y1="80" x2="790" y2="330"/><line x1="700" y1="170" x2="790" y2="130"/><line x1="700" y1="170" x2="790" y2="230"/><line x1="700" y1="170" x2="790" y2="330"/><line x1="700" y1="260" x2="790" y2="130"/><line x1="700" y1="260" x2="790" y2="230"/><line x1="700" y1="260" x2="790" y2="330"/><line x1="700" y1="350" x2="790" y2="130"/><line x1="700" y1="350" x2="790" y2="230"/><line x1="700" y1="350" x2="790" y2="330"/></g><g stroke="#9fe8ff" stroke-opacity="0.10" stroke-width="1"><line x1="104" y1="421" x2="56" y2="285"/><line x1="248" y1="241" x2="272" y2="253"/><line x1="334" y1="31" x2="329" y2="17"/><line x1="58" y1="238" x2="56" y2="285"/><line x1="58" y1="238" x2="42" y2="40"/><line x1="483" y1="409" x2="388" y2="325"/><line x1="424" y1="365" x2="388" y2="325"/><line x1="424" y1="365" x2="435" y2="280"/><line x1="272" y1="253" x2="241" y2="344"/><line x1="342" y1="90" x2="329" y2="17"/><line x1="310" y1="107" x2="416" y2="105"/><line x1="334" y1="31" x2="342" y2="90"/><line x1="248" y1="241" x2="314" y2="212"/><line x1="310" y1="107" x2="342" y2="90"/><line x1="241" y1="453" x2="296" y2="448"/><line x1="241" y1="453" x2="270" y2="447"/><line x1="388" y1="325" x2="435" y2="280"/><line x1="332" y1="324" x2="388" y2="325"/><line x1="483" y1="409" x2="424" y2="365"/><line x1="104" y1="421" x2="58" y2="238"/><line x1="272" y1="253" x2="314" y2="212"/><line x1="310" y1="107" x2="165" y2="82"/><line x1="310" y1="107" x2="334" y2="31"/><line x1="332" y1="324" x2="241" y2="344"/><line x1="296" y1="448" x2="270" y2="447"/><line x1="241" y1="453" x2="104" y2="421"/><line x1="416" y1="105" x2="342" y2="90"/><line x1="165" y1="82" x2="42" y2="40"/><line x1="272" y1="253" x2="332" y2="324"/></g><g fill="#bfe6ff" fill-opacity="0.30"><circle cx="241" cy="453" r="2"/><circle cx="296" cy="448" r="2"/><circle cx="483" cy="409" r="2"/><circle cx="248" cy="241" r="3.5"/><circle cx="270" cy="447" r="2"/><circle cx="310" cy="107" r="2.5"/><circle cx="104" cy="421" r="2.5"/><circle cx="272" cy="253" r="2.5"/><circle cx="332" cy="324" r="3.5"/><circle cx="416" cy="105" r="2"/><circle cx="58" cy="238" r="3.5"/><circle cx="165" cy="82" r="2"/><circle cx="56" cy="285" r="3.5"/><circle cx="424" cy="365" r="2.5"/><circle cx="334" cy="31" r="2.5"/><circle cx="314" cy="212" r="2"/><circle cx="241" cy="344" r="3.5"/><circle cx="388" cy="325" r="2"/><circle cx="342" cy="90" r="2.5"/><circle cx="329" cy="17" r="3.5"/><circle cx="435" cy="280" r="2.5"/><circle cx="42" cy="40" r="2.5"/></g><g><circle cx="520" cy="60" r="7" fill="#5fd4ff" fill-opacity="0.55" class="ab-pulse"/><circle cx="520" cy="60" r="3" fill="#ffffff" fill-opacity="0.8"/><circle cx="520" cy="140" r="7" fill="#a99bff" fill-opacity="0.55"/><circle cx="520" cy="140" r="3" fill="#ffffff" fill-opacity="0.8"/><circle cx="520" cy="220" r="7" fill="#4fe3c1" fill-opacity="0.55"/><circle cx="520" cy="220" r="3" fill="#ffffff" fill-opacity="0.8"/><circle cx="520" cy="300" r="7" fill="#5fd4ff" fill-opacity="0.55" class="ab-pulse"/><circle cx="520" cy="300" r="3" fill="#ffffff" fill-opacity="0.8"/><circle cx="520" cy="380" r="7" fill="#a99bff" fill-opacity="0.55"/><circle cx="520" cy="380" r="3" fill="#ffffff" fill-opacity="0.8"/><circle cx="610" cy="40" r="7" fill="#4fe3c1" fill-opacity="0.55"/><circle cx="610" cy="40" r="3" fill="#ffffff" fill-opacity="0.8"/><circle cx="610" cy="120" r="7" fill="#5fd4ff" fill-opacity="0.55" class="ab-pulse"/><circle cx="610" cy="120" r="3" fill="#ffffff" fill-opacity="0.8"/><circle cx="610" cy="200" r="7" fill="#a99bff" fill-opacity="0.55"/><circle cx="610" cy="200" r="3" fill="#ffffff" fill-opacity="0.8"/><circle cx="610" cy="280" r="7" fill="#4fe3c1" fill-opacity="0.55"/><circle cx="610" cy="280" r="3" fill="#ffffff" fill-opacity="0.8"/><circle cx="610" cy="360" r="7" fill="#5fd4ff" fill-opacity="0.55" class="ab-pulse"/><circle cx="610" cy="360" r="3" fill="#ffffff" fill-opacity="0.8"/><circle cx="610" cy="430" r="7" fill="#a99bff" fill-opacity="0.55"/><circle cx="610" cy="430" r="3" fill="#ffffff" fill-opacity="0.8"/><circle cx="700" cy="80" r="7" fill="#4fe3c1" fill-opacity="0.55"/><circle cx="700" cy="80" r="3" fill="#ffffff" fill-opacity="0.8"/><circle cx="700" cy="170" r="7" fill="#5fd4ff" fill-opacity="0.55" class="ab-pulse"/><circle cx="700" cy="170" r="3" fill="#ffffff" fill-opacity="0.8"/><circle cx="700" cy="260" r="7" fill="#a99bff" fill-opacity="0.55"/><circle cx="700" cy="260" r="3" fill="#ffffff" fill-opacity="0.8"/><circle cx="700" cy="350" r="7" fill="#4fe3c1" fill-opacity="0.55"/><circle cx="700" cy="350" r="3" fill="#ffffff" fill-opacity="0.8"/><circle cx="790" cy="130" r="7" fill="#5fd4ff" fill-opacity="0.55" class="ab-pulse"/><circle cx="790" cy="130" r="3" fill="#ffffff" fill-opacity="0.8"/><circle cx="790" cy="230" r="7" fill="#a99bff" fill-opacity="0.55"/><circle cx="790" cy="230" r="3" fill="#ffffff" fill-opacity="0.8"/><circle cx="790" cy="330" r="7" fill="#4fe3c1" fill-opacity="0.55"/><circle cx="790" cy="330" r="3" fill="#ffffff" fill-opacity="0.8"/></g></svg>
<div class="ab-hello"><span class="ab-wave">👋</span> Hello, welcome!</div>
<p>I am a Principal AI Scientist working at the intersection of AI, machine learning, and computational biology. I build foundation models and AI systems that integrate multimodal biological data, from genomics and proteomics to imaging and scientific literature, to accelerate scientific discovery and therapeutic innovation.</p>
<p>Over the past decade, I have led AI-driven research across drug discovery, translational science, and biopharmaceutical R&amp;D. My current focus includes <strong>virtual cells</strong>, <strong>biological world models</strong>, and <strong>agentic AI</strong> that predict cellular responses and guide experiments, accelerating the path from data to therapies.</p>
<div class="ab-actions">
<a class="ab-btn primary" href="mailto:azim.dehghani@gmail.com">✉️ Get in touch</a>
<a class="ab-btn ghost" href="https://scholar.google.com/citations?user=Zg2wZtQAAAAJ&amp;hl=en">🎓 Google Scholar</a>
<a class="ab-btn ghost" href="https://www.linkedin.com/in/azimdehghani/">💼 LinkedIn</a>
</div>
</div>

<div class="ab-figure">
<img class="ab-img" src='/images/Azim_ResearchSummaryFinal.png' alt="Overview of my research, from multimodal representation learning toward virtual cells">
<div class="ab-caption">From multimodal representation learning toward virtual cells</div>
</div>

<div class="ab-section">🧭 My Journey</div>

<div class="ab-bio">
<p>I received a master's in Bioinformatics from the <a href="https://www.mpi-inf.mpg.de/home/">Max Planck Institute for Informatics</a> and <a href="https://zbi-www.bioinf.uni-sb.de/en">Saarland University</a> in Germany, and did my PhD in Computer Science with the <a href="https://www.imprs-cs.de/">International Max Planck Research School for Computer Science</a> at the Max Planck Institute for Informatics, where I was fortunate to be advised by <a href="https://schulzlab.github.io/MS.html">Prof. Marcel Schulz</a>. I was also a visiting student in <a href="http://fraenkel.mit.edu/">Prof. Ernest Fraenkel's lab</a> at <a href="https://www.mit.edu/">MIT</a>.</p>
<p>From April 2019 to February 2021, I was a postdoctoral research associate at the <a href="https://www.broadinstitute.org/">Broad Institute of MIT and Harvard</a> and <a href="https://www.csail.mit.edu/">MIT CSAIL</a> under the supervision of <a href="http://compbio.mit.edu/compbio.html">Prof. Manolis Kellis</a>.</p>
<p><span class="now">Today</span> I am a Principal AI Scientist at <a href="https://www.jnj.com/">Johnson &amp; Johnson Innovative Medicine</a>, building foundation models, virtual cells, and agentic AI for drug discovery.</p>
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
<div class="ab-person"><div class="ab-avatar">AK</div><div><div class="name">Ali Khodabandeh</div><div class="school">University of Central Florida</div><div class="topic">Multimodal foundation models for spatial omics and scRNA-seq</div></div></div>
<div class="ab-person"><div class="ab-avatar">YM</div><div><div class="name">Yuwei Miao</div><div class="school">University of Texas</div><div class="topic">Foundation models for virtual cells</div></div></div>
<div class="ab-person"><div class="ab-avatar">JZ</div><div><div class="name">Junchao Zhu</div><div class="school">Vanderbilt University</div><div class="topic">Multimodal foundation model for spatial omics</div></div></div>
<div class="ab-person"><div class="ab-avatar">SG</div><div><div class="name">Sophie Guo</div><div class="school">MIT</div><div class="topic">Generative modeling of perturbational single-cell data</div></div></div>
</div>

<div class="ab-section">🏆 Awards</div>

<ul class="ab-awards">
<li><span class="icon">🌟</span><span><strong>INSPIRE Award at J&amp;J</strong>, in recognition of exceptional leadership and scientific contribution (2023–2025)</span></li>
<li><span class="icon">🎓</span><span><a href="https://www.imprs-cs.de/">International Max Planck Research School for Computer Science (IMPRS-CS)</a> PhD Fellowship</span></li>
<li><span class="icon">✈️</span><span><a href="https://www.daad.de/en/">DAAD</a> fellowship for a doctoral research visit at MIT</span></li>
<li><span class="icon">🎫</span><span>Travel fellowship for the German Conference on Bioinformatics 2016</span></li>
<li><span class="icon">🎫</span><span>Travel fellowship for <a href="https://irbgroup.org/">ISMB-SIG 2016</a></span></li>
</ul>
