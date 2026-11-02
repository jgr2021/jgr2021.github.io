# Dynamic graph and spectral estimation manuscript

**Authors:** Gurui Jin and Ercan E. Kuruoğlu  
**Affiliation:** Shenzhen International Graduate School, Tsinghua University, Shenzhen, China  
**Status:** Manuscript in preparation. Planned submission to IEEE Signal Processing Letters (SPL).

- [English manuscript](Theta_U_SPL_EN.pdf)
- [Chinese review version](Theta_U_SPL_ZH.pdf)
- [English LaTeX source](Theta_U_SPL_EN.tex)
- [Chinese LaTeX source](Theta_U_SPL_ZH.tex)

## Build

Use TeX Live with IEEEtran, TikZ, and the packages listed in the source:

```sh
pdflatex -interaction=nonstopmode -halt-on-error Theta_U_SPL_EN.tex
pdflatex -interaction=nonstopmode -halt-on-error Theta_U_SPL_EN.tex
xelatex -interaction=nonstopmode -halt-on-error Theta_U_SPL_ZH.tex
xelatex -interaction=nonstopmode -halt-on-error Theta_U_SPL_ZH.tex
```

The Chinese source uses ctex with fontset=windows and requires the corresponding Windows fonts. On another platform, select an available ctex fontset.

The PDFs contain synthetic experiments and distinguish the proposed estimator from adapted literature baselines. This directory contains manuscript artifacts; it is not an experiment-code release.
