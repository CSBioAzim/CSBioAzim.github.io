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
@media (min-width:900px){.ab-wrap .ab-hero p{max-width:57%;}}
.ab-hero .ab-net{position:absolute;inset:0;width:100%;height:100%;z-index:0;pointer-events:none;}
.ab-hero > *{position:relative;z-index:1;}
.ab-hello{font-family:var(--display);font-size:1.05em;font-weight:500;color:var(--muted);margin:0 0 0.9em 0;}
.ab-hero p{font-family:var(--text);font-size:1.08em;line-height:1.72;color:#2a3050;margin:0 0 0.95em 0;max-width:40em;}
.ab-hero p strong{font-weight:700;color:var(--ink);}
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
<p>I am a <strong>Principal AI Scientist</strong> working at the intersection of AI, machine learning, and computational biology. I build <strong>foundation models</strong> and <strong>AI systems</strong> that integrate multimodal biological data, from genomics and proteomics to imaging and scientific literature, to accelerate scientific discovery and therapeutic innovation.</p>
<p>Over the past decade, I have led AI-driven research across drug discovery, translational science, and biopharmaceutical R&amp;D. My current focus includes <span class="ab-key gfp">virtual cells</span>, <span class="ab-key dapi">biological world models</span>, and <span class="ab-key mch">agentic AI</span> that predict cellular responses and guide experiments, accelerating the path from data to therapies.</p>
<div class="ab-actions">
<a class="ab-btn primary" href="mailto:azim.dehghani@gmail.com">✉️ Get in touch</a>
<a class="ab-btn" href="https://scholar.google.com/citations?user=Zg2wZtQAAAAJ&amp;hl=en">🎓 Google Scholar</a>
<a class="ab-btn" href="https://www.linkedin.com/in/azimdehghani/">💼 LinkedIn</a>
</div>
</div>

<script>
/* Background: a cell-state manifold.
   A gently breathing surface stands for the landscape of cell states. A cell travels along it from its
   original state to a perturbed state (forward transition), rests, then returns (backward transition). */
(function(){
  var c=document.getElementById('ab-net'); if(!c||!c.getContext) return;
  var ctx=c.getContext('2d'), hero=c.parentElement, W=0, H=0;
  var still=window.matchMedia&&window.matchMedia('(prefers-reduced-motion: reduce)').matches;
  var NU=44, NV=24;
  function size(){var dpr=window.devicePixelRatio||1; W=hero.clientWidth; H=hero.clientHeight;
    c.width=W*dpr; c.height=H*dpr; c.style.width=W+'px'; c.style.height=H+'px'; ctx.setTransform(dpr,0,0,dpr,0,0);}
  function zf(u,v,t){return 0.55*Math.sin(Math.PI*(1.6*u+0.15)+t*0.5)*Math.cos(Math.PI*(v-0.5)*1.1)
                          +0.28*Math.sin(Math.PI*(2.6*v+u*1.2)-t*0.35)-0.35*u;}
  function proj(u,v,t){var mobile=window.innerWidth<900, Lw=W*(mobile?0.80:0.30), Lh=H*(mobile?0.30:0.34), x0=W*(mobile?0.08:0.60), y0=H*(mobile?0.92:0.78);
    return [x0+u*Lw+v*Lw*0.28, y0-v*Lh-zf(u,v,t)*H*(mobile?0.12:0.16)];}
  function mask(u,v){var du=(u-0.5)/0.5, dv=(v-0.5)/0.5, d=du*du+dv*dv*1.1+0.08*Math.sin(u*7+v*4);
    return Math.max(0,Math.min(1,(1-d)*4.5));}
  function mix(a,b,k){return [a[0]+(b[0]-a[0])*k,a[1]+(b[1]-a[1])*k,a[2]+(b[2]-a[2])*k];}
  var TEAL=[86,186,170], INDIGO=[86,104,196], VIOLET=[150,110,220], AMBER=[214,150,60];
  function pathPt(k,back){var u=0.24+0.54*k, v=back?0.30+0.1*Math.sin(Math.PI*k):0.56+0.12*Math.sin(Math.PI*k); return [u,v];}
  var start=performance.now();
  function frame(now){
    var t=still?0:(now-start)/1000; ctx.clearRect(0,0,W,H);
    // surface, drawn back to front
    for(var j=NV-1;j>=0;j--)for(var i=0;i<NU;i++){
      var u0=i/NU,u1=(i+1)/NU,v0=j/NV,v1=(j+1)/NV, m=mask((u0+u1)/2,(v0+v1)/2); if(m<=0) continue;
      var p00=proj(u0,v0,t),p10=proj(u1,v0,t),p11=proj(u1,v1,t),p01=proj(u0,v1,t);
      var col=mix(TEAL,INDIGO,Math.min(1,Math.max(0,(u0+u1)/2*1.1-0.05)));
      var shade=0.82+0.18*Math.sin(Math.PI*(1.6*u0+0.15)+t*0.5);
      ctx.fillStyle='rgba('+(col[0]*shade|0)+','+(col[1]*shade|0)+','+(col[2]*shade|0)+','+(0.88*m)+')';
      ctx.beginPath();ctx.moveTo(p00[0],p00[1]);ctx.lineTo(p10[0],p10[1]);ctx.lineTo(p11[0],p11[1]);ctx.lineTo(p01[0],p01[1]);ctx.closePath();ctx.fill();
      ctx.strokeStyle='rgba(255,255,255,'+(0.65*m)+')';ctx.lineWidth=0.6;ctx.stroke();
    }
    // journey timing: forward 4.5s, rest 1.2s, backward 4.5s, rest 1.2s
    var T=11.4, ph=(t%T), back=false, k;
    if(ph<4.5){k=ph/4.5;} else if(ph<5.7){k=1;} else if(ph<10.2){back=true;k=1-(ph-5.7)/4.5;} else {back=true;k=0;}
    var e=k<0.5?2*k*k:1-Math.pow(-2*k+2,2)/2;
    // trails
    function trail(isBack,upto,rgb,alpha){ctx.beginPath();for(var s=0;s<=40;s++){var kk=s/40; if(isBack? kk<upto: kk>upto) continue;
        var q=pathPt(kk,isBack), P=proj(q[0],q[1],t); if(s===0||(isBack&&kk>=upto&&false)) ctx.moveTo(P[0],P[1]); else ctx.lineTo(P[0],P[1]);}
      ctx.strokeStyle='rgba('+rgb.join(',')+','+alpha+')';ctx.lineWidth=2.4;ctx.lineCap='round';ctx.stroke();}
    trail(false,1,AMBER,0.3); trail(true,0,VIOLET,0.3);
    if(!back) trail(false,e,AMBER,1); else { // backward trail drawn from the perturbed end toward the cell
      ctx.beginPath(); var started=false; for(var s2=40;s2>=0;s2--){var kk2=s2/40; if(kk2<e) break; var q2=pathPt(kk2,true),P2=proj(q2[0],q2[1],t);
        if(!started){ctx.moveTo(P2[0],P2[1]);started=true;} else ctx.lineTo(P2[0],P2[1]);}
      ctx.strokeStyle='rgba('+VIOLET.join(',')+',1)';ctx.lineWidth=2.6;ctx.stroke(); }
    // state anchors
    var A=proj.apply(null,pathPt(0,false).concat([t])), B=proj.apply(null,pathPt(1,false).concat([t]));
    [[A,TEAL],[B,VIOLET]].forEach(function(s){ctx.strokeStyle='rgba(255,255,255,0.85)';ctx.lineWidth=4.5;ctx.beginPath();ctx.arc(s[0][0],s[0][1],13,0,6.283);ctx.stroke();ctx.strokeStyle='rgba('+s[1].join(',')+',1)';ctx.lineWidth=2;
      ctx.beginPath();ctx.arc(s[0][0],s[0][1],13,0,6.283);ctx.stroke();});
    // the cell
    var q=pathPt(e,back), P=proj(q[0],q[1],t), cc=mix(TEAL,VIOLET,e), cs=(cc[0]|0)+','+(cc[1]|0)+','+(cc[2]|0);
    var g=ctx.createRadialGradient(P[0],P[1],0,P[0],P[1],26); g.addColorStop(0,'rgba('+cs+',0.45)'); g.addColorStop(1,'rgba('+cs+',0)');
    ctx.fillStyle=g;ctx.beginPath();ctx.arc(P[0],P[1],26,0,6.283);ctx.fill();
    ctx.fillStyle='#fff';ctx.beginPath();ctx.arc(P[0],P[1],9,0,6.283);ctx.fill();
    ctx.strokeStyle='rgba('+cs+',0.95)';ctx.lineWidth=2.2;ctx.stroke();
    ctx.fillStyle='rgba('+cs+',0.95)';ctx.beginPath();ctx.arc(P[0],P[1],4,0,6.283);ctx.fill();
    // soften the left side so the text stays easy to read
    if(window.innerWidth<900){ctx.save();ctx.globalCompositeOperation='destination-out';ctx.fillStyle='rgba(0,0,0,0.35)';ctx.fillRect(0,0,W,H);ctx.restore();}
    if(!still) requestAnimationFrame(frame);
  }
  size(); if(still) frame(0); else requestAnimationFrame(frame);
  var tm; window.addEventListener('resize',function(){clearTimeout(tm);tm=setTimeout(function(){size(); if(still) frame(0);},150);});
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
