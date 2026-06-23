-----

permalink: /
title: “About me”
excerpt: “About me”
author_profile: true
redirect_from:

- /about/
- /about.html

-----

I am a Principal AI Scientist working at the intersection of artificial intelligence, machine learning, and computational biology. My research focuses on building foundation models and AI systems that integrate multimodal biological data—including genomics, transcriptomics, proteomics, imaging, and scientific literature—to accelerate scientific discovery and therapeutic innovation.

My work spans large language models, generative biology, perturbation modeling, and agentic AI systems capable of reasoning over complex biological processes. I am particularly interested in developing **Virtual Cells** and **biological world models** that can simulate cellular behavior, predict responses to genetic and chemical perturbations, and guide experimental design at scale.

Over the past decade, I have led the development of AI-driven solutions across drug discovery, translational research, and biopharmaceutical R&D. My goal is to transform how science is conducted by combining foundation models, autonomous agents, and mechanistic biological knowledge to create intelligent systems that augment scientific decision-making and accelerate the path from data to therapies.

I am also passionate about scaling AI across organizations—bridging cutting-edge research with real-world impact through platform development, cross-functional leadership, and the deployment of production-grade AI systems.

## Research Interests

- Foundation Models for Biology
- Virtual Cells and Biological World Models
- Agentic AI for Scientific Discovery
- Generative Biology and Sequence Design
- Multimodal Learning and Data Integration
- Single-Cell and Spatial Omics
- Causal Inference and Perturbation Modeling
- AI for Drug Discovery and Biopharma R&D

<br/>

<!-- Research Summary Figure -->

<link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@300;400;500;600;700&family=Inter:wght@300;400;500&display=swap" rel="stylesheet">

<style>
.rs-wrap *, .rs-wrap *::before, .rs-wrap *::after { box-sizing: border-box; margin: 0; padding: 0; }

.rs-wrap {
  background: #0B1628;
  border-radius: 16px;
  font-family: 'Inter', sans-serif;
  color: #E8EFF8;
  padding: 40px 32px 32px;
  margin: 24px 0;
  overflow: hidden;
  position: relative;
}

.rs-header {
  text-align: center;
  margin-bottom: 40px;
}
.rs-eyebrow {
  font-family: 'Space Grotesk', sans-serif;
  font-size: 11px;
  font-weight: 500;
  letter-spacing: 0.18em;
  text-transform: uppercase;
  color: #00C2B2;
  margin-bottom: 10px;
}
.rs-header h2 {
  font-family: 'Space Grotesk', sans-serif;
  font-size: 26px;
  font-weight: 700;
  line-height: 1.2;
  background: linear-gradient(135deg, #E8EFF8 30%, #00C2B2 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  margin-bottom: 10px;
  border-bottom: none !important;
}
.rs-header p {
  font-size: 13px;
  color: #8BA4C0;
  max-width: 560px;
  margin: 0 auto;
  line-height: 1.6;
}

/* Orbital */
.rs-orbital-wrap {
  position: relative;
  width: 100%;
  aspect-ratio: 1 / 0.82;
  margin-bottom: 40px;
}
.rs-orbital-svg {
  position: absolute;
  inset: 0;
  width: 100%;
  height: 100%;
}

/* Center node */
.rs-center-node {
  position: absolute;
  top: 50%; left: 50%;
  transform: translate(-50%, -50%);
  width: 148px; height: 148px;
  display: flex; flex-direction: column;
  align-items: center; justify-content: center;
  z-index: 10;
}
.rs-pulse-ring {
  position: absolute;
  inset: 0;
  border-radius: 50%;
  border: 1.5px solid #00C2B2;
  opacity: 0;
  animation: rs-pulse-out 3s ease-out infinite;
}
.rs-pulse-ring:nth-child(2) { animation-delay: 1s; }
.rs-pulse-ring:nth-child(3) { animation-delay: 2s; }
@keyframes rs-pulse-out {
  0%   { transform: scale(1);   opacity: 0.7; }
  100% { transform: scale(2.4); opacity: 0;   }
}
.rs-center-circle {
  width: 148px; height: 148px;
  border-radius: 50%;
  background: radial-gradient(circle at 38% 38%, #1A2E50, #0B1628);
  border: 2px solid #00C2B2;
  box-shadow: 0 0 32px rgba(0,194,178,0.25), inset 0 0 20px rgba(0,194,178,0.07);
  display: flex; flex-direction: column;
  align-items: center; justify-content: center;
  position: relative; z-index: 2;
}
.rs-center-icon  { font-size: 30px; margin-bottom: 6px; filter: drop-shadow(0 0 8px #00C2B2); }
.rs-center-label {
  font-family: 'Space Grotesk', sans-serif;
  font-size: 12px; font-weight: 600;
  color: #00C2B2; text-align: center;
  line-height: 1.3; letter-spacing: 0.03em;
  padding: 0 8px;
}

/* Satellites */
.rs-sat {
  position: absolute;
  transform: translate(-50%, -50%);
  z-index: 5;
}
.rs-chip {
  background: rgba(255,255,255,0.04);
  border: 1px solid rgba(255,255,255,0.12);
  border-radius: 12px;
  padding: 11px 14px;
  display: flex; flex-direction: column;
  align-items: center; gap: 5px;
  width: 112px; text-align: center;
  backdrop-filter: blur(6px);
  transition: border-color 0.25s, box-shadow 0.25s;
  cursor: default;
}
.rs-chip:hover {
  border-color: rgba(255,255,255,0.3);
  box-shadow: 0 0 16px rgba(124,92,252,0.2);
}
.rs-chip.rs-teal   { border-color: rgba(0,194,178,0.35); }
.rs-chip.rs-violet { border-color: rgba(124,92,252,0.35); }
.rs-chip.rs-amber  { border-color: rgba(245,158,11,0.35); }
.rs-sat-icon  { font-size: 20px; }
.rs-sat-label {
  font-family: 'Space Grotesk', sans-serif;
  font-size: 10.5px; font-weight: 600;
  line-height: 1.3; color: #D0DEEE;
  letter-spacing: 0.02em;
}

/* Positions */
.rs-s1 { top: 5%;  left: 50%; }
.rs-s2 { top: 18%; left: 79%; }
.rs-s3 { top: 50%; left: 92%; }
.rs-s4 { top: 80%; left: 79%; }
.rs-s5 { top: 93%; left: 50%; }
.rs-s6 { top: 80%; left: 21%; }
.rs-s7 { top: 50%; left: 8%;  }
.rs-s8 { top: 18%; left: 21%; }

/* Pillars */
.rs-pillars {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 16px;
  margin-bottom: 28px;
}
.rs-pillar {
  background: rgba(255,255,255,0.03);
  border: 1px solid rgba(255,255,255,0.08);
  border-radius: 14px;
  padding: 18px 16px;
  position: relative;
  overflow: hidden;
}
.rs-pillar::before {
  content: '';
  position: absolute;
  top: 0; left: 0; right: 0;
  height: 2px;
  border-radius: 14px 14px 0 0;
}
.rs-p-teal::before   { background: #00C2B2; }
.rs-p-violet::before { background: #7C5CFC; }
.rs-p-amber::before  { background: #F59E0B; }
.rs-pillar-icon  { font-size: 20px; margin-bottom: 7px; }
.rs-pillar-title {
  font-family: 'Space Grotesk', sans-serif;
  font-size: 12px; font-weight: 600;
  margin-bottom: 8px; color: #E8EFF8;
}
.rs-tags { display: flex; flex-wrap: wrap; gap: 5px; }
.rs-tag {
  font-size: 10px; font-weight: 500;
  color: #8BA4C0;
  background: rgba(255,255,255,0.06);
  border-radius: 4px;
  padding: 2px 7px;
  letter-spacing: 0.02em;
}

/* Footer */
.rs-footer {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-wrap: wrap;
  gap: 10px;
  padding: 13px 20px;
  background: rgba(0,194,178,0.06);
  border: 1px solid rgba(0,194,178,0.18);
  border-radius: 10px;
}
.rs-footer span { font-size: 11px; color: #8BA4C0; letter-spacing: 0.04em; }
.rs-footer strong { color: #00C2B2; font-weight: 500; }
.rs-dot { width: 4px; height: 4px; border-radius: 50%; background: #00C2B2; opacity: 0.5; }

@media (max-width: 600px) {
  .rs-pillars { grid-template-columns: 1fr; }
  .rs-chip { width: 90px; }
  .rs-sat-label { font-size: 9px; }
  .rs-center-circle, .rs-center-node { width: 110px; height: 110px; }
}
</style>

<div class="rs-wrap">

  <div class="rs-header">
    <div class="rs-eyebrow">Research Overview</div>
    <h2>AI-Driven Biology &amp; Drug Discovery</h2>
    <p>Building foundation models and intelligent agents that simulate cellular behavior, predict perturbation responses, and accelerate the path from data to therapies.</p>
  </div>

  <div class="rs-orbital-wrap">
    <svg class="rs-orbital-svg" viewBox="0 0 900 738" preserveAspectRatio="xMidYMid meet" xmlns="http://www.w3.org/2000/svg">
      <defs>
        <radialGradient id="rs-og" cx="50%" cy="50%" r="50%">
          <stop offset="0%"   stop-color="#1A3050" stop-opacity="0.4"/>
          <stop offset="100%" stop-color="#0B1628" stop-opacity="0"/>
        </radialGradient>
        <linearGradient id="rs-lgt" x1="0%" y1="0%" x2="100%" y2="0%">
          <stop offset="0%"   stop-color="#00C2B2" stop-opacity="0.6"/>
          <stop offset="100%" stop-color="#00C2B2" stop-opacity="0.1"/>
        </linearGradient>
        <linearGradient id="rs-lgv" x1="0%" y1="0%" x2="100%" y2="0%">
          <stop offset="0%"   stop-color="#7C5CFC" stop-opacity="0.6"/>
          <stop offset="100%" stop-color="#7C5CFC" stop-opacity="0.1"/>
        </linearGradient>
        <linearGradient id="rs-lga" x1="0%" y1="0%" x2="100%" y2="0%">
          <stop offset="0%"   stop-color="#F59E0B" stop-opacity="0.6"/>
          <stop offset="100%" stop-color="#F59E0B" stop-opacity="0.1"/>
        </linearGradient>
      </defs>
      <circle cx="450" cy="369" r="280" fill="url(#rs-og)"/>
      <circle cx="450" cy="369" r="200" fill="none" stroke="rgba(255,255,255,0.05)" stroke-width="1" stroke-dasharray="4 8"/>
      <circle cx="450" cy="369" r="290" fill="none" stroke="rgba(255,255,255,0.03)" stroke-width="1" stroke-dasharray="2 12"/>
      <line x1="450" y1="295" x2="450" y2="93"  stroke="url(#rs-lgt)" stroke-width="1.2"/>
      <line x1="501" y1="319" x2="663" y2="151" stroke="url(#rs-lgv)" stroke-width="1.2"/>
      <line x1="524" y1="369" x2="756" y2="369" stroke="url(#rs-lgt)" stroke-width="1.2"/>
      <line x1="501" y1="419" x2="663" y2="575" stroke="url(#rs-lga)" stroke-width="1.2"/>
      <line x1="450" y1="443" x2="450" y2="643" stroke="url(#rs-lgv)" stroke-width="1.2"/>
      <line x1="399" y1="419" x2="237" y2="575" stroke="url(#rs-lgt)" stroke-width="1.2"/>
      <line x1="376" y1="369" x2="144" y2="369" stroke="url(#rs-lga)" stroke-width="1.2"/>
      <line x1="399" y1="319" x2="237" y2="151" stroke="url(#rs-lgv)" stroke-width="1.2"/>
      <circle cx="450" cy="93"  r="3" fill="#00C2B2" opacity="0.7"/>
      <circle cx="663" cy="151" r="3" fill="#7C5CFC" opacity="0.7"/>
      <circle cx="756" cy="369" r="3" fill="#00C2B2" opacity="0.7"/>
      <circle cx="663" cy="575" r="3" fill="#F59E0B" opacity="0.7"/>
      <circle cx="450" cy="643" r="3" fill="#7C5CFC" opacity="0.7"/>
      <circle cx="237" cy="575" r="3" fill="#00C2B2" opacity="0.7"/>
      <circle cx="144" cy="369" r="3" fill="#F59E0B" opacity="0.7"/>
      <circle cx="237" cy="151" r="3" fill="#7C5CFC" opacity="0.7"/>
    </svg>

```
<div class="rs-center-node">
  <div class="rs-pulse-ring"></div>
  <div class="rs-pulse-ring"></div>
  <div class="rs-pulse-ring"></div>
  <div class="rs-center-circle">
    <div class="rs-center-icon">🧬</div>
    <div class="rs-center-label">Virtual Cell<br>World Model</div>
  </div>
</div>

<div class="rs-sat rs-s1"><div class="rs-chip rs-teal"><div class="rs-sat-icon">🏗️</div><div class="rs-sat-label">Foundation Models for Biology</div></div></div>
<div class="rs-sat rs-s2"><div class="rs-chip rs-violet"><div class="rs-sat-icon">🔬</div><div class="rs-sat-label">Single-Cell &amp; Spatial Omics</div></div></div>
<div class="rs-sat rs-s3"><div class="rs-chip rs-teal"><div class="rs-sat-icon">⚡</div><div class="rs-sat-label">Perturbation Modeling</div></div></div>
<div class="rs-sat rs-s4"><div class="rs-chip rs-amber"><div class="rs-sat-icon">💊</div><div class="rs-sat-label">AI for Drug Discovery</div></div></div>
<div class="rs-sat rs-s5"><div class="rs-chip rs-violet"><div class="rs-sat-icon">🤖</div><div class="rs-sat-label">Agentic AI for Science</div></div></div>
<div class="rs-sat rs-s6"><div class="rs-chip rs-teal"><div class="rs-sat-icon">🧪</div><div class="rs-sat-label">Generative Biology</div></div></div>
<div class="rs-sat rs-s7"><div class="rs-chip rs-amber"><div class="rs-sat-icon">🔗</div><div class="rs-sat-label">Multimodal Data Integration</div></div></div>
<div class="rs-sat rs-s8"><div class="rs-chip rs-violet"><div class="rs-sat-icon">📊</div><div class="rs-sat-label">Causal Inference</div></div></div>
```

  </div>

  <div class="rs-pillars">
    <div class="rs-pillar rs-p-teal">
      <div class="rs-pillar-icon">🧠</div>
      <div class="rs-pillar-title">Foundation Models</div>
      <div class="rs-tags">
        <span class="rs-tag">scRNA-seq</span><span class="rs-tag">Proteomics</span>
        <span class="rs-tag">Imaging</span><span class="rs-tag">Multimodal</span>
        <span class="rs-tag">Pretraining</span>
      </div>
    </div>
    <div class="rs-pillar rs-p-violet">
      <div class="rs-pillar-icon">🌐</div>
      <div class="rs-pillar-title">Biological World Models</div>
      <div class="rs-tags">
        <span class="rs-tag">Object-Centric</span><span class="rs-tag">Perturbation</span>
        <span class="rs-tag">Simulation</span><span class="rs-tag">GRN Inference</span>
      </div>
    </div>
    <div class="rs-pillar rs-p-amber">
      <div class="rs-pillar-icon">⚙️</div>
      <div class="rs-pillar-title">Agentic AI Systems</div>
      <div class="rs-tags">
        <span class="rs-tag">ADME/Tox</span><span class="rs-tag">Closed-Loop</span>
        <span class="rs-tag">Drug Discovery</span><span class="rs-tag">Reasoning</span>
      </div>
    </div>
  </div>

  <div class="rs-footer">
    <span>Principal AI Scientist</span>
    <div class="rs-dot"></div>
    <span><strong>Johnson &amp; Johnson Innovative Medicine</strong></span>
    <div class="rs-dot"></div>
    <span>Computational Biology · Machine Learning · Drug Discovery</span>
  </div>

</div>