---
permalink: /
title: "About me"
excerpt: "Azim Dehghani Amirabad, Principal AI Scientist building foundation models, virtual cells and agentic AI for drug discovery."
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:opsz,wght@12..96,500;12..96,700;12..96,800&family=Source+Serif+4:ital,opsz,wght@0,8..60,400;0,8..60,600;1,8..60,400&display=swap" rel="stylesheet">

<style>
/* Palette: a fluorescence-microscopy field.
   Field (dark)  #060a1c   Ink #121735   Paper #f6f7fb   Rule #e3e6f0
   Channels: DAPI #6c8cff (nucleus blue), GFP #34d39a (green), mCherry #f0679f (magenta) */
@media (min-width:1024px){.page{padding-right:0 !important;}}
.ab-wrap{--field:#060a1c;--ink:#121735;--muted:#59607a;--paper:#f6f7fb;--rule:#e3e6f0;--dapi:#6c8cff;--gfp:#34d39a;--mch:#f0679f;--dapi-d:#3654d6;--gfp-d:#0f8a5f;--mch-d:#c2306d;
  --display:"Bricolage Grotesque",system-ui,sans-serif;--text:"Source Serif 4","Charter","Iowan Old Style",Georgia,serif;color:var(--ink);}
.ab-wrap a{color:var(--dapi-d);text-decoration:none !important;border-bottom:1px solid rgba(54,84,214,0.3);transition:color .15s ease,border-color .15s ease;}
.ab-wrap a:hover{color:var(--ink);border-bottom-color:var(--ink);}
.ab-wrap a:focus-visible{outline:2px solid var(--dapi);outline-offset:3px;border-radius:3px;}

/* ---------- Hero: light field, same paper as "My journey" ---------- */
.ab-hero{position:relative;overflow:hidden;background:
  radial-gradient(70% 90% at 96% 0%,rgba(108,140,255,0.10) 0%,rgba(108,140,255,0) 60%),
  radial-gradient(60% 80% at 0% 100%,rgba(52,211,154,0.08) 0%,rgba(52,211,154,0) 60%),
  #fff;
  border:1px solid var(--rule);border-radius:26px;padding:2.4em 2.5em 2.2em 2.5em;margin:0 0 2.2em 0;
  box-shadow:0 1px 2px rgba(18,23,53,0.04),0 18px 40px -22px rgba(30,40,110,0.18);}
.ab-hero .ab-net{position:absolute;inset:0;width:100%;height:100%;z-index:0;pointer-events:none;}
.ab-hero > *{position:relative;z-index:1;}
.ab-hello{font-family:var(--display);font-size:1.05em;font-weight:500;color:var(--muted);margin:0 0 0.9em 0;}
.ab-hero p{font-family:var(--text);font-size:1.08em;line-height:1.72;color:#2a3050;margin:0 0 0.95em 0;max-width:40em;}
.ab-key{font-family:var(--display);font-weight:700;font-size:0.98em;letter-spacing:-0.005em;white-space:nowrap;}
.ab-key::before{content:"";display:inline-block;width:0.5em;height:0.5em;border-radius:50%;margin:0 0.3em 0.08em 0.05em;vertical-align:middle;}
.ab-key.gfp{color:var(--gfp-d);} .ab-key.gfp::before{background:var(--gfp);box-shadow:0 0 8px rgba(52,211,154,0.7);}
.ab-key.dapi{color:var(--dapi-d);} .ab-key.dapi::before{background:var(--dapi);box-shadow:0 0 8px rgba(108,140,255,0.7);}
.ab-key.mch{color:var(--mch-d);} .ab-key.mch::before{background:var(--mch);box-shadow:0 0 8px rgba(240,103,159,0.7);}
.ab-actions{display:flex;flex-wrap:wrap;gap:0.6em;margin-top:1.5em;}
.ab-wrap .ab-btn{font-family:var(--display);display:inline-flex;align-items:center;gap:0.45em;font-size:0.9em;font-weight:500;padding:0.6em 1.25em;border-radius:12px;border:1px solid #d5d9e8;color:var(--ink);background:rgba(255,255,255,0.85);transition:background .15s ease,border-color .15s ease;}
.ab-wrap .ab-btn:hover{background:#f1f3fa;border-color:#b9c0d8;color:var(--ink);}
.ab-wrap .ab-btn.primary{background:var(--ink);color:#fff;border-color:var(--ink);font-weight:700;}
.ab-wrap .ab-btn.primary:hover{background:#262d5c;color:#fff;}

/* ---------- Figure ---------- */
.ab-figure{border:1px solid var(--rule);border-radius:18px;padding:0.7em;background:#fff;}
.ab-img{display:block;width:100%;border-radius:12px;margin:0;}

/* ---------- Section titles ---------- */
.ab-h{font-family:var(--display);font-size:1.75em;font-weight:800;letter-spacing:-0.02em;line-height:1.1;color:var(--ink);margin:2.1em 0 0.75em 0;}
.ab-h::after{content:"";display:block;width:2.2em;height:4px;border-radius:4px;margin-top:0.35em;background:linear-gradient(90deg,var(--dapi) 0 33%,var(--gfp) 33% 66%,var(--mch) 66% 100%);}

/* ---------- Journey ---------- */
.ab-bio{font-family:var(--text);font-size:1.06em;line-height:1.82;color:#2a3050;max-width:41em;}
.ab-bio p{margin:0 0 1em 0;}
.ab-bio p:first-child::first-letter{font-family:var(--display);float:left;font-size:3.3em;line-height:0.86;font-weight:800;color:var(--dapi-d);margin:0.06em 0.1em 0 0;}
.ab-degree{font-family:var(--display);font-weight:700;font-size:0.97em;letter-spacing:-0.005em;white-space:nowrap;padding:0.05em 0.5em 0.1em 0.4em;border-radius:8px;}
.ab-degree .ab-cap{width:1.05em;height:1.05em;fill:currentColor;vertical-align:-0.15em;margin-right:0.3em;}
.ab-degree.bio{color:var(--ink);background:rgba(52,211,154,0.12);}
.ab-degree.bio .ab-cap{fill:var(--gfp-d);}
.ab-degree.cs{color:var(--ink);background:rgba(108,140,255,0.12);}
.ab-degree.cs .ab-cap{fill:var(--dapi-d);}
.ab-now{font-family:var(--display);font-weight:700;color:var(--gfp-d);}
.ab-fun{font-family:var(--text);font-style:italic;color:var(--muted);font-size:1em;margin:0.2em 0 0 0;}

/* ---------- News ---------- */
.ab-news{list-style:none;margin:0;padding:0.2em 0 0.4em 0;display:flex;flex-direction:column;gap:0.95em;}
.ab-news li{position:relative;display:grid;grid-template-columns:6.2em 1fr;gap:1.1em;padding:1.05em 1.4em 1.05em 1.5em;margin:0;border-radius:14px;background:#fff;border:1px solid rgba(18,23,53,0.06);
  box-shadow:0 1px 2px rgba(18,23,53,0.04),0 4px 10px -2px rgba(18,23,53,0.06),0 14px 28px -12px rgba(30,40,110,0.14);}
.ab-news li::before{content:"";position:absolute;left:0;top:0.9em;bottom:0.9em;width:3px;border-radius:0 3px 3px 0;}
.ab-news li.paper::before{background:var(--dapi);}
.ab-news li.talk::before{background:var(--mch);}
.ab-news .when{font-family:var(--display);font-weight:700;font-size:0.92em;color:var(--ink);padding-top:0.12em;}
.ab-news .what{font-family:var(--text);font-size:1em;line-height:1.62;color:#2a3050;}
.ab-news .kind{font-family:var(--display);font-size:0.82em;font-weight:700;margin-right:0.5em;}
.ab-news .kind::before{content:"";display:inline-block;width:0.55em;height:0.55em;border-radius:50%;margin-right:0.35em;vertical-align:0.05em;}
.ab-news .paper .kind{color:var(--dapi-d);} .ab-news .paper .kind::before{background:var(--dapi);}
.ab-news .talk .kind{color:var(--mch-d);} .ab-news .talk .kind::before{background:var(--mch);}
@media (max-width:600px){.ab-news li{grid-template-columns:1fr;gap:0.2em;}}

/* ---------- Students ---------- */
.ab-people{display:grid;grid-template-columns:repeat(2,1fr);gap:1.6em 2em;}
@media (max-width:600px){.ab-people{grid-template-columns:1fr;}}
.ab-person{display:flex;gap:1em;align-items:flex-start;}
.ab-avatar{flex:0 0 auto;width:3.1em;height:3.1em;border-radius:50%;display:flex;align-items:center;justify-content:center;font-family:var(--display);font-weight:800;font-size:0.95em;color:var(--field);background:#fff;border:3px solid var(--c);box-shadow:0 0 0 4px color-mix(in srgb,var(--c) 18%,transparent);}
.ab-person .name{font-family:var(--display);font-weight:700;font-size:1.05em;color:var(--ink);}
.ab-person .school{font-family:var(--display);font-size:0.86em;font-weight:500;color:var(--muted);margin:0.05em 0 0.3em 0;}
.ab-person .topic{font-family:var(--text);font-size:0.97em;line-height:1.5;color:#2a3050;}

/* ---------- Awards ---------- */
.ab-awards{list-style:none;margin:0;padding:0;}
.ab-awards li{display:grid;grid-template-columns:2.6em 1fr;gap:0.9em;align-items:center;padding:0.8em 0;border-bottom:1px solid var(--rule);margin:0;font-family:var(--text);font-size:1em;line-height:1.55;color:#2a3050;}
.ab-awards li:first-child{border-top:1px solid var(--rule);}
.ab-awards .icon{width:2.4em;height:2.4em;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:1.05em;background:var(--paper);}
.ab-awards strong{font-family:var(--display);font-weight:700;color:var(--ink);}
</style>

<div class="ab-wrap">

<div class="ab-hero">
<canvas class="ab-net" id="ab-net" aria-hidden="true"></canvas>
<div class="ab-hello">Hello, welcome 👋</div>
<p>I am a Principal AI Scientist working at the intersection of AI, machine learning, and computational biology. I build foundation models and AI systems that integrate multimodal biological data, from genomics and proteomics to imaging and scientific literature, to accelerate scientific discovery and therapeutic innovation.</p>
<p>Over the past decade, I have led AI-driven research across drug discovery, translational science, and biopharmaceutical R&amp;D. My current focus includes <span class="ab-key gfp">virtual cells</span>, <span class="ab-key dapi">biological world models</span>, and <span class="ab-key mch">agentic AI</span> that predict cellular responses and guide experiments, accelerating the path from data to therapies.</p>
<div class="ab-actions">
<a class="ab-btn primary" href="mailto:azim.dehghani@gmail.com">✉️ Get in touch</a>
<a class="ab-btn" href="https://scholar.google.com/citations?user=Zg2wZtQAAAAJ&amp;hl=en">🎓 Google Scholar</a>
<a class="ab-btn" href="https://www.linkedin.com/in/azimdehghani/">💼 LinkedIn</a>
</div>
</div>

<script>
(function(){
  var c=document.getElementById('ab-net'); if(!c||!c.getContext) return;
  var ctx=c.getContext('2d'), hero=c.parentElement, nodes=[], W=0, H=0;
  var chans=['108,140,255','52,211,154','240,103,159'];
  var still=window.matchMedia&&window.matchMedia('(prefers-reduced-motion: reduce)').matches;
  function size(){
    var dpr=window.devicePixelRatio||1; W=hero.clientWidth; H=hero.clientHeight;
    c.width=W*dpr; c.height=H*dpr; c.style.width=W+'px'; c.style.height=H+'px';
    ctx.setTransform(dpr,0,0,dpr,0,0);
    var n=Math.max(20,Math.min(64,Math.round(W*H/9500))); nodes=[];
    for(var i=0;i<n;i++){
      // nodes favour the right side so the text column stays calm
      var x=W*(0.25+0.75*Math.pow(Math.random(),0.6));
      nodes.push({x:x,y:Math.random()*H,vx:(Math.random()-.5)*.3,vy:(Math.random()-.5)*.3,r:1.3+Math.random()*2.2,c:chans[i%3]});
    }
  }
  function frame(){
    ctx.clearRect(0,0,W,H); var D=125;
    for(var i=0;i<nodes.length;i++){var a=nodes[i];
      if(!still){a.x+=a.vx;a.y+=a.vy;if(a.x<0||a.x>W)a.vx*=-1;if(a.y<0||a.y>H)a.vy*=-1;}
      for(var j=i+1;j<nodes.length;j++){var b=nodes[j],dx=a.x-b.x,dy=a.y-b.y,d=Math.sqrt(dx*dx+dy*dy);
        if(d<D){ctx.strokeStyle='rgba(70,85,160,'+(0.16*(1-d/D))+')';ctx.lineWidth=1;ctx.beginPath();ctx.moveTo(a.x,a.y);ctx.lineTo(b.x,b.y);ctx.stroke();}}
    }
    for(var k=0;k<nodes.length;k++){var p=nodes[k];
      ctx.fillStyle='rgba('+p.c+',0.16)';ctx.beginPath();ctx.arc(p.x,p.y,p.r*3.2,0,6.283);ctx.fill();
      ctx.fillStyle='rgba('+p.c+',0.85)';ctx.beginPath();ctx.arc(p.x,p.y,p.r,0,6.283);ctx.fill();}
    if(!still) requestAnimationFrame(frame);
  }
  size(); frame();
  var t; window.addEventListener('resize',function(){clearTimeout(t);t=setTimeout(function(){size(); if(still) frame();},150);});
})();
</script>

<div class="ab-figure">
<img class="ab-img" src='/images/Azim_ResearchSummaryFinal.png' alt="Overview of my research, from multimodal representation learning toward virtual cells">
</div>

<div class="ab-h">My journey</div>

<div class="ab-bio">
<p>I received a master's in <span class="ab-degree bio"><svg class="ab-cap" viewBox="0 0 24 24" aria-hidden="true"><path d="M12 3 1.5 8.5 12 14l8.5-4.45V16h2V8.5L12 3Z"/><path d="M5.5 12.3v3.9c0 1.9 2.9 3.8 6.5 3.8s6.5-1.9 6.5-3.8v-3.9L12 15.7l-6.5-3.4Z"/></svg>Bioinformatics</span> from the <a href="https://www.mpi-inf.mpg.de/home/">Max Planck Institute for Informatics</a> and <a href="https://zbi-www.bioinf.uni-sb.de/en">Saarland University</a> in Germany, and did my PhD in <span class="ab-degree cs"><svg class="ab-cap" viewBox="0 0 24 24" aria-hidden="true"><path d="M12 3 1.5 8.5 12 14l8.5-4.45V16h2V8.5L12 3Z"/><path d="M5.5 12.3v3.9c0 1.9 2.9 3.8 6.5 3.8s6.5-1.9 6.5-3.8v-3.9L12 15.7l-6.5-3.4Z"/></svg>Computer Science</span> with the <a href="https://www.imprs-cs.de/">International Max Planck Research School for Computer Science</a> at the Max Planck Institute for Informatics, where I was fortunate to be advised by <a href="https://schulzlab.github.io/MS.html">Prof. Marcel Schulz</a>. I was also a visiting student in <a href="http://fraenkel.mit.edu/">Prof. Ernest Fraenkel's lab</a> at <a href="https://www.mit.edu/">MIT</a>.</p>
<p>From April 2019 to February 2021, I was a postdoctoral research associate at the <a href="https://www.broadinstitute.org/">Broad Institute of MIT and Harvard</a> and <a href="https://www.csail.mit.edu/">MIT CSAIL</a> under the supervision of <a href="http://compbio.mit.edu/compbio.html">Prof. Manolis Kellis</a>.</p>
<p><span class="ab-now">Today</span>, I am a Principal AI Scientist at <a href="https://www.jnj.com/">Johnson &amp; Johnson Innovative Medicine</a>, building foundation models, virtual cells, and agentic AI for drug discovery.</p>
<p class="ab-fun">⚽ Outside the lab, you'll find me playing soccer or hiking. My favorite player? <a href="https://www.youtube.com/watch?v=OUKGsb8CpF8&amp;t=412s">Cristiano Ronaldo</a>, of course!</p>
</div>

<div class="ab-h">News</div>

<ul class="ab-news">
<li class="paper"><span class="when">Oct 2026</span><span class="what"><span class="kind">Paper</span>Our work <a href="https://arxiv.org/abs/2610.28579">Spatially Informed and Direction Sensitive Representation Learning for Spatial Transcriptomics</a> was accepted at the NeurIPS 2026 AI4DD Workshop! 🎉</span></li>
<li class="paper"><span class="when">Oct 2026</span><span class="what"><span class="kind">Paper</span>Our work <a href="https://arxiv.org/abs/2610.14853">Disentangling Marginal Capacity from Geometry in Optimal-Transport Label Transfer</a> was accepted at NeurIPS 2026! 🎉</span></li>
<li class="paper"><span class="when">Oct 2026</span><span class="what"><span class="kind">Paper</span>Our work <a href="https://arxiv.org/abs/2610.04475">VCLMU: Mechanism-Centric Virtual Cell World Modeling for Perturbation Response</a> was accepted at NeurIPS 2026! 🎉</span></li>
<li class="talk"><span class="when">Oct 2026</span><span class="what"><span class="kind">Talk</span>Invited talk on <strong>Scaling AI across Pharma R&amp;D</strong> at <a href="https://www.aidrivendrugdevelopment.com/speakers-7lf7">AIDDD</a>. 🎤</span></li>
<li class="paper"><span class="when">2026</span><span class="what"><span class="kind">Paper</span>Our work <a href="https://arxiv.org/abs/2608.14924">PaSTel</a>, bridging histology and spatial transcriptomics through multimodal, bio-prior-guided contrastive pretraining, was published at ICML 2026! 🎉</span></li>
<li class="talk"><span class="when">Jun 2026</span><span class="what"><span class="kind">Talk</span>Invited talk on <strong>AI in Biotech: Accelerating Drug Discovery &amp; Development</strong> at <a href="https://futurebiotechexpo.com/conference/speakers">Future Biotech Expo</a>. 🎤</span></li>
<li class="talk"><span class="when">Oct 2025</span><span class="what"><span class="kind">Talk</span>Invited talk on <strong>AI's Impact on the Future of Biotechnology</strong> at <a href="https://neet.mit.edu/threads/lm">MIT Department of Engineering</a>. 🎤</span></li>
<li class="talk"><span class="when">2025</span><span class="what"><span class="kind">Talk</span>Invited talk at <a href="https://bostonbiotechnologysummit.com/program/speakers/">Boston Biotech Summit 2025</a> on <strong>how AI is transforming value creation in biotech</strong> (<a href="https://www.cpl.com/blog/2025/07/ai-transforms-digital-health-key-insights-from-recent-biotech-summits">see blog about my talk</a>). 🎤</span></li>
<li class="paper"><span class="when">Jul 2025</span><span class="what"><span class="kind">Paper</span>Presented our paper on a <strong>multimodal foundation model for gRNA activity prediction</strong> at ICML 2025, Vancouver (<a href="https://openreview.net/pdf/53cf4d58ae4c7f9bee4b2f82d0d81d4a54fe65bb.pdf">full text</a>). 🎉</span></li>
<li class="talk"><span class="when">2024</span><span class="what"><span class="kind">Talk</span>Invited talk at <a href="https://bostonbiotechnologysummit.com/program/speakers/">Boston Biotech Summit 2024</a> on <strong>AI applications in the biotech and pharmaceutical industry</strong> (<a href="https://www.youtube.com/watch?v=enxpQX6PFiQ">watch my pre-summit interview</a>). 🎤</span></li>
</ul>

<div class="ab-h">Students &amp; interns</div>

<div class="ab-people">
<div class="ab-person"><div class="ab-avatar" style="--c:#34d39a">AK</div><div><div class="name">Ali Khodabandeh</div><div class="school">University of Central Florida</div><div class="topic">Multimodal foundation models for spatial omics and scRNA-seq</div></div></div>
<div class="ab-person"><div class="ab-avatar" style="--c:#6c8cff">YM</div><div><div class="name">Yuwei Miao</div><div class="school">University of Texas</div><div class="topic">Foundation models for virtual cells</div></div></div>
<div class="ab-person"><div class="ab-avatar" style="--c:#f0679f">JZ</div><div><div class="name">Junchao Zhu</div><div class="school">Vanderbilt University</div><div class="topic">Multimodal foundation model for spatial omics</div></div></div>
<div class="ab-person"><div class="ab-avatar" style="--c:#34d39a">SG</div><div><div class="name">Sophie Guo</div><div class="school">MIT</div><div class="topic">Generative modeling of perturbational single-cell data</div></div></div>
</div>

<div class="ab-h">Awards</div>

<ul class="ab-awards">
<li><span class="icon">🌟</span><span><strong>INSPIRE Award at J&amp;J</strong>, in recognition of exceptional leadership and scientific contribution (2023–2025)</span></li>
<li><span class="icon">🎓</span><span><a href="https://www.imprs-cs.de/">International Max Planck Research School for Computer Science (IMPRS-CS)</a> PhD Fellowship</span></li>
<li><span class="icon">✈️</span><span><a href="https://www.daad.de/en/">DAAD</a> fellowship for a doctoral research visit at MIT</span></li>
<li><span class="icon">🎫</span><span>Travel fellowship for the German Conference on Bioinformatics 2016</span></li>
<li><span class="icon">🎫</span><span>Travel fellowship for <a href="https://irbgroup.org/">ISMB-SIG 2016</a></span></li>
</ul>

</div>
