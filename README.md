# DepthChron

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24424596.svg)](https://doi.org/10.5281/zenodo.24424596)

**Age-depth modelling for sediment cores, in your web browser.**

![DepthChron](https://storeassets.im-cdn.com/media-manager/1302352/4849f6647b39466da2313c011d3d7b88_DepthChron_Free_cover_1024.jpg)

DepthChron is uniquely designed for ease of use: it needs no coding, runs offline in a browser, takes mixed methods in one table and writes the methods paragraph.

## Download
| Edition | What it includes | Where |
|---|---|---|
| **DepthChron (Free)** v1.1.4 | Calibration, corrections, Bayesian and classical age-depth models, event layers, figures, tables, methods paragraph | [Zenodo](https://doi.org/10.5281/zenodo.24424596) · [Store](https://twmglobal.myinstamojo.com/product/depthchron) |
| **DepthChron Pro** v1.1.4 | Everything in Free, plus model interpretation and event recurrence analysis | [![DepthChron Pro, India (₹)](https://img.shields.io/badge/DepthChron%20Pro-India%20%28%E2%82%B9%29-e07b00?style=for-the-badge)](https://twmglobal.myinstamojo.com/product/depthchron-pro) [![DepthChron Pro, International ($)](https://img.shields.io/badge/DepthChron%20Pro-International%20%28%24%29-1f6feb?style=for-the-badge)](https://geomantle.com/depthchron) |

DepthChron is a single HTML file: save it, open it in Chrome, Edge or Firefox, and start. No installation, no account and no internet connection are needed, and your data never leaves your computer.

## What it does
- Radiocarbon (AMS or conventional, as 14C age, F14C or pMC, including post-1950 bomb samples), OSL / IRSL and calendar ages in one table
- Calibration with IntCal20, SHCal20, Marine20 and Bomb21 (Hua et al. 2022), plus IntCal13 / SHCal13 / Marine13, IntCal09 and IntCal04 for older studies
- Corrections: marine reservoir (ΔR with uncertainty), mixed marine–terrestrial carbon (CALIB 8.2 method), hard-water offset, δ13C normalisation, OSL datum shift to AD 1950
- Bayesian age-depth model after Blaauw and Christen (2011), with Student-t outlier handling, hiatuses and Steady / Dynamic depositional-environment presets
- Classical models after Blaauw (2010): linear interpolation, regression, polynomials
- Instantaneous event layers (tsunami, storm, turbidite, tephra) removed before modelling; event ages compared across cores; a horizon at the top, base or inside an event layer is recognised as the same deposit
- Exports: age tables and dates (CSV), PNG and SVG figures (with the citation stored inside them), project files, a methods paragraph written from your settings, and a one-click "Download all" .zip
- Drag-and-drop import of Excel or CSV date tables, with a live preview that flags age reversals as you type
- Interactive age-depth figure (hover for ages, drag to zoom, click a date for details), summary cards and a stratigraphic log column
- Unlimited cores per project. Everything runs on your computer; no data leaves it.

## New in 1.1.4
- Pro: site event list. Events recorded in several cores are matched into site events and their ages combined, so recurrence can be analysed for a whole site without counting an event twice (checked on simulated records with known event ages).
- In the all-features demo, the "Buried soil top" horizon is no longer counted as an event in the recurrence analysis.
- Support: support@geomantle.com.

## New in 1.1.3
- New first demo, Demo: all features: three simulated coastal cores (not real data) with mixed dates, event layers, a hiatus and an event horizon, so every step, including event ages and recurrence, shows results. The Lake Ulu demos are now Lake Ulu: short run and Lake Ulu: long run, and the Events step explains when a project has no event layers.
- Models now run in a background worker, so a run keeps going when you switch to another tab or window. Lake Ulu results are identical to v1.1.2.

## New in 1.1.2
- The demo is now the published Lake Ulu core (EN21103; data: Jia et al., 2024, CC BY 4.0) in two versions: Demo: short run (about 3 minutes) and Demo: long run (the full settings, about 20 minutes).

## New in 1.1.1
- Pro features are no longer contained in the Free file.

## New in 1.1.0
- Duplicate events (a horizon marking the same deposit as an event layer) are flagged and kept out of event comparisons
- Horizons outside the modelled depths are listed so they are not silently left out
- "Download all (.zip)" on the Export step, Next buttons through to Export, and a "How to cite" box
- DepthChron Pro (sold separately) adds model interpretation and event recurrence analysis; see below

## How to use
1. Download DepthChron from Zenodo or the store, save DepthChron_v1.1.4.html anywhere and open it in Chrome, Edge or Firefox. No installation or internet connection is needed.
2. Try the built-in demos. Demo: all features (loaded first; three simulated coastal cores, not real data) runs in under a minute and shows every step, including event ages and recurrence. Lake Ulu: short run (about 3 minutes) and Lake Ulu: long run (full settings, about 20 minutes) load the published Lake Ulu core (EN21103; data: Jia et al., 2024, CC BY 4.0). Then click New project.
3. Follow the seven steps: Project, Dates, Corrections, Calibrate, Model, Events, Export.

The User Guide (PDF) explains each step, how to choose settings, and how to read the results.

## Validation
- Calibration: CALIB 8.2 medians within 0–1 yr (IntCal20, SHCal20, Marine20, mixed curves)
- Bayesian model: MSB2K (rbacon example) medians within 0.4–3.7 yr; 23 published Bacon chronologies from LegacyAge 1.0 (Li et al. 2022) reproduced with a typical median difference of about 16 yr
- Simulated cores with known true ages: true age inside the 95% range at every depth on clean cores
- Pro features: see DepthChron_v1.1.4_validation.zip on [Zenodo](https://doi.org/10.5281/zenodo.24424596) (25 simulated cores; Lake Ulu, Jia et al. 2024, Quaternary Science Reviews 331, 108650; 16 simulated event records)

## DepthChron Pro
Model interpretation (accumulation zones, robust and tentative rate changes, hiatus durations, time resolution, where a new date helps most, a ready results paragraph, and checks of doubtful settings before every interpretation) and event recurrence analysis (intervals, mean recurrence, variability, and the chance of another event from Poisson and Brownian passage time models), for one core or for a site event list that matches events across cores.

**Get DepthChron Pro:**

[![DepthChron Pro, India (₹)](https://img.shields.io/badge/DepthChron%20Pro-India%20%28%E2%82%B9%29-e07b00?style=for-the-badge)](https://twmglobal.myinstamojo.com/product/depthchron-pro) [![DepthChron Pro, International ($)](https://img.shields.io/badge/DepthChron%20Pro-International%20%28%24%29-1f6feb?style=for-the-badge)](https://geomantle.com/depthchron)

Questions or issues: open an [issue](../../issues) or write to support@geomantle.com

## How to cite
GitHub's **Cite this repository** button (right-hand panel) gives the same citation in APA and BibTeX.

In text: Khan, A. (2026)

Reference: Khan, A. (2026). DepthChron: age-depth modelling for mixed radiocarbon, luminescence and calendar ages, version 1.1.4 [Computer software]. Zenodo. https://doi.org/10.5281/zenodo.24424596

Please also cite the calibration curves and methods you used; the methods paragraph on the Export step lists them.

Results support, and do not replace, the judgment of a qualified specialist.

## Licence
DepthChron is distributed under the Creative Commons Attribution-NoDerivatives 4.0 International licence (CC BY-ND 4.0); see [LICENSE.md](LICENSE.md).

Dr. Afzal Khan (ORCID [0000-0001-8844-122X](https://orcid.org/0000-0001-8844-122X)) · Developed by an IIT alumnus and GATE UPSC qualifier
