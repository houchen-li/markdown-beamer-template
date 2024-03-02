---
output:
    beamer_presentation:
        pdf_engine: 'xelatex'
        path: './main.pdf'
        includes:
            in_header: 'header.tex'
            before_body: 'doc_prefix.tex'
            after_body: 'doc_suffix.tex'
        pandoc_args:
        - '--filter=pandoc-crossref'
export_on_save:
    pandoc: true
################################################
theme: Madrid
colortheme: orchid
aspectratio: 169
#section-titles: false
lang: en-US
#geometry:
#- 'left=1.6in'
#- 'right=1in'
#- 'top=1.2in'
#- 'bottom=1.2in'
fontenc: 'T1'
fontsize: '10pt'
mainfont: NewComputerModern
mainfontoptions:
- 'Extension=.otf'
- 'UprightFont=NewCM10-Regular'
- 'BoldFont=NewCM10-Bold'
- 'ItalicFont=NewCM10-Italic'
- 'BoldItalicFont=NewCM10-BoldItalic'
CJKmainfont: 'Source Han Serif CN'
CJKoptions:
- 'Extension=.otf'
- 'UprightFont=SourceHanSerifCN-Regular'
- 'BoldFont=SourceHanSerifCN-Bold'
- 'ItalicFont=ukai.ttc'
#- 'BoldItalicFont='
linestretch: '1.25'
indent: true
toc: true
#toc-title: 'Contents'
#toc-depth: 3
numbersections: false
hyperrefoptions:
- 'linktoc=all'
bibliography:
- 'refs/bibliography.bib'
csl: 'refs/american-physics-society.csl'
################################################
title: 'Quantum Mechanics'
author:
- 'Wikipedia'
institute:
- 'Fachbereich Physik, Philipps-Universität Marburg'
date: 'May 16th, 2020'
---

# Introduction

---

Quantum mechanics (QM; also known as quantum physics, quantum theory, the wave mechanical model and matrix mechanics), including quantum field theory, is a fundamental theory in physics. It describes advanced properties of nature on an atomic scale. [@Feynman1964]

---

![The 1927 Solvay Conference in Brussels was the fifth world physics conference.](figures/Solvay_conference_1927.jpg){width=60%}

---

According to Planck, each energy element (E) is proportional to its frequency (\(\nu\)):
\[E=h\nu,\] {#eq:photon-energy}
where h is Planck's constant.


# Methods

---

* quantization of certain physical properties
* quantum entanglement
* principle of uncertainty
* wave–particle duality


# Results

---

![Wavefunctions of the electron in a hydrogen atom at different energy levels. Quantum mechanics cannot predict the exact location of a particle in space, only the probability of finding it at different locations. The brighter areas represent a higher probability of finding the electron.](figures/Hydrogen_Density_Plots.png){width=40%}


# Conclusion

---

In light of the Bell tests, Cramer in 1986 formulated his transactional interpretation which is unique in providing a physical explanation for the Born rule. Relational quantum mechanics appeared in the late 1990s as the modern derivative of the Copenhagen Interpretation.


# Reference {.allowframebreaks}

---
