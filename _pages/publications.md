---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

**1) An efficient regularization method to eliminate vanishing gradient effect in deep neural networks** (under submision)

 **2) When genes are not enough: learning of transcript isoform regulatory networks** <br/>**Azim Dehghani Amirabad**, Marcel H. Schulz (submitted)
 
**3) Large-scale inference of competing endogeneous RNA networks with sparse partial correlation** <br/>Markus List, **Azim Dehghani Amirabad** , Dennis Kostka, Marcel H. Schulz
Bioinformatics (Proceedings of ISMB), 2019. ([full text](https://academic.oup.com/bioinformatics/article/35/14/i596/5529172)) 
 
**4) Multitask regression for context-specific prioritization of miRNA targets in transcripts** <br/>**Azim Dehghani Amirabad** , Marcel H. Schulz <br/>Proceedings of German Conference for Bioinformatics 2016 ([full text](https://peerj.com/preprints/2377/)) 

**5) Transgenic expression of the RNA binding protein IMP2 stabilizes miRNA targets in murine microsteatosis**<br/>**Azim Dehghani Amirabad** , Pathmanaban Ramasamy, Marina Wierz, Karl Nordström, Sonja M. Kessler, Marcel H. Schulz, Martin Simon<br/>Molecular Basis of Disease 2018 ([full text](https://www.sciencedirect.com/science/article/pii/S0925443918302023)) 

**6) More than the Killer Trait: Infection with the Bacterial Endosymbiont Caedibacter taeniospiralis Causes Transcriptomic Modulation in Paramecium Host** <br/>Katrin Grosser, Pathmanaban Ramasamy, **Azim Dehghani Amirabad**, Marcel H. Schulz, Gilles Gasparoni, Martin Simon, and Martina Schrallhammer <br/>Genome Biol Evol. 2018 (full text) 

**7) Combining transcription factor binding affinities with open-chromatin data for accurate gene expression prediction** <br/>F Schmidt , N Gasparoni, G Gasparoni, K Gianmoena, C Cadenas, JK Polansky, P Ebert, KJV Nordström, M Barann, A Sinha, S Fröhler, J Xiong, **A Dehghani Amirabad**, F Behjati Ardakani, B Hutter, G Zipprich, B Felder, E Jürgen Eils, B Brors, W Chen, JG Hengstler, A Hamann, T Lengauer, P Rosenstiel, J Walter, MH Schulz <br/>Nucleic Acids Research, 29 November 2016 ([full text](https://academic.oup.com/nar/article/45/1/54/2605711)) 

**8) Epigenetic reprogramming in memory formation of human CD4+ T cells** <br/>Durek P, Nordström KJV, Gasparoni G, Kressler C, Almeida M, Salhab A, Bassler K, Ulas T, Schmidt F, Xiong J, Glažar P, Klironomos F, Sinha A, Kinkley S, Yang X, **Amirabad AD**, Ardakani FB, Feuerbach L, Gorka O, Ebert P, Müller F, Li N, Frischbutter S, Schlickeiser S, Cendon C, Fröhler S, Felder B, Gasparoni N, Imbusch CD, Hutter B, Zipprich G, Tauchmann Y, Reinke S, Wassilew G, Hoffmann U, Arrigoni L, Richter AS, Sieverling L, Chang HD, Syrbe U, Manke T, Kalus U, Eils J, Brors B, Ruland J, Lengauer T, Rajewsky N, Chen W, Schulz MH, Dong J, Sawitzki B, Chung HR, Rosenstiel P, Schultze JP, Radbruch A, Walter J, Hamann A, Polansky JK<br/>Cell Immunity, Volume 45, Issue 5, 15 November 2016, ([full text](https://www.cell.com/immunity/fulltext/S1074-7613%2816%2930433-2)) 

**9) Epigenetic regulation of serotype expression antagonizes transcriptome dynamics in Paramecium tetraurelia** <br/>M Cheaib, **A Dehghani Amirabad**, KJV Nordstroem, MH Schulz, M Simon <br\>DNA Research, Oxford Journals. 2015 Jun ([full text](dnaresearch.oxfordjournals.org/content/22/4/293.long)) 

**10) Attenuation of NF-kB and activation of Nrf2 signaling by 1,2,4-triazine derivatives, protects neuron-like PC12 cells against apoptosis**<br/>Tusi SK1, Ansari N, Amini M, **Amirabad AD**, Shafiee A, Khodagholi F <br/>Apoptosis. 2010 Jun;15(6):738-51 ([full text](https://link.springer.com/article/10.1007%2Fs10495-010-0496-6)) 

**11) Inhibition of LPS-induced apoptosis in differentiated-PC12 cells by new triazine derivatives through NF-kB-mediated suppression of COX-2**<br/>Ansari N1, Khodagholi F, Ramin M, Amini M, Irannejad H, Dargahi L, **Amirabad AD**<br/>
Neurochem Int. 2010 Dec ([full text](https://www.sciencedirect.com/science/article/pii/S0197018610003062)) 
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
