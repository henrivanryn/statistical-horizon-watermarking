# The Statistical Horizon: A Scaling Benchmark and Procedural Caution for Institutional Use of AI Text Watermarking

**Henri F. Van Ryn** | Independent Researcher | <henri.vanryn@gmail.com>

Version 6.1 | February 10, 2026 (revised August 3, 2026)

This repository contains the public deposit of the working paper formalizing the Statistical Horizon as a structural scaling benchmark for finite-sample AI text watermark detectability.

## Abstract

AI text watermarking has evolved from academic speculation into industrial
practice. Yet for the statistical detector class analyzed in this paper, watermark
detections remain probabilistic indicators rather than proof of authorship. This
paper formalizes the Statistical Horizon as a structural scaling benchmark for
finite-sample watermark detectability. In the stylized mean-shift model used here,
required sample length scales inversely with the square of the combined signal
term ηδ, creating a steep, inverse-quadratic penalty for low-visibility
watermarking. The paper argues that this scaling result should not be confused
with a rule for strong institutional attribution. Under the model developed here,
the Statistical Horizon n_h is best understood as a lower detectability floor: it
corresponds to the point at which expected detector signal reaches threshold and,
in the Gaussian power analysis, to a 50% detection-power point. Because n_h
describes prospective power rather than the evidentiary weight of a particular
observed statistic, a sample shorter than n_h can still yield a highly probative
result; the paper presents reliance on n_h as a normative, precautionary
institutional posture rather than as a mathematical consequence of the horizon
equation itself. To make the gap between detectability and reliability explicit,
the paper also defines a higher-power reliability benchmark n_E, showing that
practical institutional interpretation depends not only on watermark strength but
also on desired power, calibration, sample length, robustness, and disclosure.
The paper further develops a four-step institutional sequence distinguishing
detection from adjudication. Structural limits are not obstacles to governance.
They are conditions for governing responsibly.

## Files

- `statistical_horizon_v6_1.pdf` — final manuscript (Version 6.1)
- `statistical_horizon_v6_1.tex` — LaTeX source
- `CHANGELOG_v5.9_to_v6.0.md` — full revision history and independent verification record (Vera and Grok reviews), including the v6.1 correction

**Superseded files (retained for provenance, not current):** `statistical_horizon_v5_final.pdf`, `statistical_horizon_v5_final.pdf.ots`, `statistical_horizon_v5_fixed.docx`. The duplicate `statistical_horizon_v5_fixed (1).docx` should be removed as a redundant upload artifact.

## Keywords

AI watermarking; statistical inference; forensic standards; evidentiary weighting; institutional reliance; machine learning governance; digital provenance; AI policy

## Revision Summary (v5.0 → v6.1)

Version 6.1 is a substantial revision over the previously posted v5.0, developed through two rounds of independent verification review. Key changes:

- Reframed the Statistical Horizon (n_h) throughout as a *prospective-power* benchmark rather than an evidentiary threshold, with a worked example showing low power and strong observed evidence can coexist (likelihood ratio ≈602 at z=4.2, L=400 tokens)
- Corrected a mathematically false base-rate claim regarding posterior support and observed statistic magnitude
- Scoped claims about "watermark detection" to the statistical/green-list detector class analyzed, rather than watermarking generally
- Softened autocorrelation/dependence claims to explicitly conditional language
- Added the four-step "detection is not adjudication" institutional sequence
- Updated legal/regulatory discussion to reflect the EU AI Act Article 50 transparency obligations (applicable August 2, 2026) and the California AI Transparency Act as amended by AB-853 (2025)
- Corrected bibliography: added a previously uncited reference, fixed several published titles, updated the Li et al. citation to its final *Annals of Statistics* publication, and corrected the California statute's citation to reflect the AB-853 amendment

See `CHANGELOG_v5.9_to_v6.0.md` for the full itemized history, including independent verification notes from two reviewers.

## Provenance

**SHA256** (`statistical_horizon_v6_1.pdf`): `f40ba70b56e45d4d40416a7d8214195bb8a892f78b0bc0fa743e1179a378682e`

**SHA256** (`statistical_horizon_v6_1.tex`): `6eeabdc3c2f1f043436fdd1dd50188924dfa231ab6d989920e9537c4bd373457`

**Timestamp:** Not yet generated for v6.1 — recommend running OpenTimestamps against the new PDF after upload (`ots stamp statistical_horizon_v6_1.pdf`) and committing the resulting `.ots` file, consistent with the practice used for v5.0.

**Preprint:** Formal preprint submission in progress. Manuscript and source available in this repository.

**License:** CC-BY Attribution 4.0 International
