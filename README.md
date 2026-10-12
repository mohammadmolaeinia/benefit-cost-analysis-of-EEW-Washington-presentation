markdown
# Benefit–Cost Analysis for Earthquake Early Warning in Washington State, a study presentation

A Persian, right-to-left interactive web presentation reviewing a benefit–cost analysis of an earthquake early warning system (EEWS) for Washington State.

**Live presentation:** [mohammadmolaeinia.github.io/hypothesis-presentation-2](https://mohammadmolaeinia.github.io/hypothesis-presentation-2/)

## Overview

This presentation reviews a study evaluating the potential costs and benefits of implementing and operating an earthquake early warning system in Washington State. It introduces the study’s analytical approach, modeled earthquake scenarios, estimated damage-reduction benefits, system costs, and treatment of uncertainty.

## Academic context and purpose

Prepared by Mohammad Molaeinia, an MSc student in earthquake engineering at the International Institute of Earthquake Engineering and Seismology (IIEES), this presentation examines a published study as an early literature-review activity in preparation for the author's thesis.

This repository contains a presentation about the study; it is **not the thesis itself** and does not claim original research results. The analysis and numerical estimates discussed in the presentation should be attributed to the cited study.

## Scientific scope

The presentation covers:

- The purpose and approaches used to estimate the value of an EEW system;
- Factors affecting warning effectiveness, including message receipt, interpretation, belief, decision-making, and response;
- System costs, including capital and operating costs, and the effects of missed and false alerts;
- A 50-year analysis horizon and earthquake scenarios considered in the study;
- Potential benefits for water and electricity services, hospitals, fire stations, and individuals;
- Key analytical inputs, including seismic hazard, system performance, behavioral response, and economic parameters;
- Net present value (NPV), benefit–cost results, and uncertainty analysis using Monte Carlo simulation.

## Features

- Interactive, slide-based navigation and presentation agenda;
- Persian right-to-left (RTL) layout and typography;
- Illustrative charts rendered with Chart.js;
- Mathematical notation rendered with MathJax;
- Responsive web layout.

## Technology stack

The presentation is built with HTML, CSS, and vanilla JavaScript. Chart.js and MathJax are loaded from external CDNs; an internet connection is therefore needed for charts and mathematical notation. No project build step is required.

## Project structure
```text
hypothesis-presentation-2/
├── index.html                          # Presentation structure and content
├── style.css                           # Styling, layout, and responsive behavior
├── script.js                           # Navigation and interactions
├── LICENSE                             # Project license
├── IIEES logo black transparent.png    # IIEES logo asset
├── IIEES logo white transparent.png    # IIEES logo asset
└── Natural Hazards Review cover.png    # Journal cover image
```

## Local usage

Clone the repository:

bash
git clone https://github.com/mohammadmolaeinia/hypothesis-presentation-2.git
cd hypothesis-presentation-2

Open `index.html` in a browser, or serve the project locally:

bash
python -m http.server 8000

Then visit <http://localhost:8000>. An internet connection is required to load the external Chart.js and MathJax libraries.

## Reference

Bouta, A., Ahn, A. Y. E., Bostrom, A., & Vidale, J. E. “Benefit-Cost Analysis for Earthquake Early Warning in Washington State.” *Natural Hazards Review*, 21(2), Article 04019015. Published online in 2019; journal issue published in 2020.  
[https://doi.org/10.1061/(ASCE)NH.1527-6996.0000346](https://doi.org/10.1061/(ASCE)NH.1527-6996.0000346)

## Academic note

The presentation summarizes and interprets a published study. Citations, assumptions, and numerical values should be checked against the original article before academic reuse or quotation.

## License

See [`LICENSE`](LICENSE) for the project's license and terms of use.
