# Statistical Foundations of Machine Learning: A Review

**Author:** Ilgiz Satkynov

## What this is

This is a review / expository paper, not an original research contribution. It synthesizes existing statistical theory (calibration, the bias-variance tradeoff, sampling theory, fairness impossibility results) and existing published case studies (Buolamwini & Gebru's Gender Shades audit, the Amazon hiring tool reporting by Dastin, the COMPAS analysis by Angwin et al., and the impossibility results of Chouldechova and Kleinberg et al.) to argue that many AI fairness failures are statistical phenomena rather than software bugs.

The one original element is a small bias-variance simulation (Python, using scikit-learn) whose code and actual output are included as a figure. That simulation is illustrative, not a novel empirical contribution.

## Why "review" and not "research paper"

A research paper requires something new: a theorem, a method, a dataset, or an empirical result that didn't exist before. This document doesn't have one of those. It explains and connects other people's work clearly and accurately, which is a legitimate and useful kind of writing, but a different category from original research. Labeling it accurately here so nobody mistakes it for more than it is.

## Contents

- `Satkynov_Statistical_Foundations_in_ML.pdf` — the full paper (18 pages), including 6 figures, an auto-generated table of contents, and a reference list.

## Sources

Full citations are listed in the paper's References section. Key sources include:

- Buolamwini, J., & Gebru, T. (2018). Gender Shades. *PMLR*.
- Angwin, J., Larson, J., Mattu, S., & Kirchner, L. (2016). Machine Bias. *ProPublica*.
- Dastin, J. (2018). Amazon scraps secret AI recruiting tool. *Reuters*.
- Chouldechova, A. (2017). Fair prediction with disparate impact. *Big Data*.
- Kleinberg, J., Mullainathan, S., & Raghavan, M. (2017). Inherent trade-offs in the fair determination of risk scores.
- Belkin, M., Hsu, D., Ma, S., & Mandal, S. (2019). Reconciling modern machine-learning practice and the classical bias-variance trade-off. *PNAS*.

## License

Feel free to read, cite, or build on this. No specific license applied yet — add one if you want to formalize reuse terms.
