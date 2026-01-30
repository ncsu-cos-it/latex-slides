# latex-slides
LaTeX Slide Example (2026)\
(Dr. Marie Davidian - NC State Statistis Professor)

How to use the new ltx-talk LaTEX package to create accessible pdfs of slides; see attachment template_ltx-talk.tex

ltx-talk was just released at the beginning of December 2025 and is meant to be a replacement for beamer that creates accessible pdf slides.  If you have an investment in course content or other slides made with beamer, have a look.  ltx-talk uses the same syntax as beamer for creating frames and supports overlays.  See below on how to get ltx-talk!

Even if you don't intend to use ltx-talk, do look at template_ltx-talk.tex, as there are notes at the beginning that you will find useful (much of them are repeated here).

CRITICAL: You MUST USE lualatex to compile your LaTEX source!! lualatex is included in the latest version of the Texlive 2025 distribution and in Overleaf.  ltx-talk is ALSO INCLUDED in the latest version of Texlive 2025 (see below) and Overleaf. DO NOT use pdflatex or some other engine.  

BE PATIENT:  When you process a ltx-talk document (or any other LaTEX document for that matter) using lualatex, it will take some time to process and build the tagging structure.  See the notes in the attached template_ltx-talk.tex file.

Other Resources: 
 * https://verapdf.org/home/ 
 * https://dev.verapdf-rest.duallab.com/
 * https://ctan.org/pkg/ltx-talk?lang=en 
 * https://esail.tamu.edu/faculty-tutorials/accessible-latex-pdf-ua-2-overleaf-2025/

Obtain Files
 * ````git clone https://github.com/ncsu-cos-it/latex-slides````
