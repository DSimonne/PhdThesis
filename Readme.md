# Compile the thesis from source

```bash
pdflatex main.tex; biber main; pdflatex main.tex; okular main.pdf
```
Nomenclature: https://www.overleaf.com/learn/latex/Nomenclatures

# TODO
## SXRD single crystals
* in plane lattice displacement ROD fitting
* reflectivity, discuss again, especially the problem in thickness between reflectivity and l scans Pt(111)
* better discuss oxides ?
* don't use 8x8 reconstruction, but just 8x8

## SXRD nanoparticles
* Compare shape with wulff construction and other measurements
* Get particle average size from epitaxy
* Quantify amount of powder -> well epitaxied particles
* Double -110 facet, twin boundaries maybe ?

## BCDI
* Limits of TEM: electron as a probe so not great
* Which are the most favourable facets !!!
* Add facets on top and bottom of the particle in the image
* Change FWHM evolution to percentages
* Radial distributions analysis, onion rings !
* Cross correlation for defect

## XPS
The peak at 531 ev for Pt111 is not oxide bc the PtO2 peak is not visible in the Pt4f level,
oxide reported at 531 ev on pt111 at 1 bar by Boden et al (2022)
also no 8x8 oxide detected so far in sxrd

## Intro
* Field / amplitude / intensity consistent ?
* $r_0$ use consistent ? $2\pi$ ?
* hypothesis to explain: DWBA, dipole approximation, perfect crystals
* When detecting the scattered field at a point $\vec{R}$, we assume that $\|vec{R}|$ is far greater than the electronic density, this is called the dipole approximation. NOT GOOD Each atom can be considered as a ball of certain radius (see \ref{fcc_lattice}).

# Open questions
* Check if line profiles are really biased from ER
* adsorbed molecules impact on strain or strain means adsorbed molecules
* BCDI -> real world
* beam stability: 1h30
* Fit L scans with distorted PtO2
* material loss on B7 nanoparticle ?
