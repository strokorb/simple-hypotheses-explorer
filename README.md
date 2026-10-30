# Testing a simple null against a simple alternative

*How α, β and power depend on the critical value*

An interactive explorer for type I and type II errors when testing a simple null hypothesis H₀: θ = θ₀ against a simple alternative H₁: θ = θ₁, with a normally distributed test statistic. Users can change the means, the variance of the test statistic (or σ² and n for a sample mean), the critical value c or the significance level α, and switch between a 2D and a 3D view.

> **Beta version.** The explorer has not yet been fully tested. Please check important results independently, and report problems on the [issues page](https://github.com/strokorb/simple-hypotheses-explorer/issues).
>
> **Educational use only.** The explorer is a teaching tool for building statistical literacy. It is not intended for determining test results in situations where real decisions depend on them.

**Live page:** https://strokorb.github.io/simple-hypotheses-explorer/

## Contents

| Path | What it is |
| --- | --- |
| `index.html` | The interactive explorer (a single self-contained page) |
| `fonts/` | Self-hosted typefaces Source Serif 4 and Source Sans 3, with their license (`OFL.txt`) |
| `figures/` | Static figures in SVG, PDF and PNG: the 3D and 2D versions, each labelled and unlabelled |
| `LICENSE` | Full legal text of CC BY-SA 4.0 |

## Attribution

The 3D view of the explorer and the 3D figures are adapted from “[PPV, NPV, Sensitivity and Specificity](https://commons.wikimedia.org/wiki/File:PPV,_NPV,_Sensitivity_and_Specificity.svg)” by Luigi Albert Maria, Wikimedia Commons, licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).

Changes: relabelled for hypothesis testing (null and alternative densities, critical value, acceptance and critical regions, type I and type II errors); PPV, NPV, sensitivity and specificity formulas removed; alternative density rescaled to the same dispersion as the null density; regions shaded; redrawn as an interactive, live 3D view; 2D companion figures added.

## How this was made

Developed with the assistance of Claude Opus 5.5, an AI model by Anthropic. Kirstin Strokorb designed and reviewed the content and is responsible for it.

## License

Everything in this repository by Kirstin Strokorb is licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/), except the fonts in `fonts/`, which are licensed under the SIL Open Font License 1.1 (see `fonts/OFL.txt`).

When you reuse or adapt this material, please credit both the original figure (as above) and this adaptation, and share your version under the same license.
