# The Statistical Horizon: A Scaling Benchmark and Procedural Caution for Institutional Use of AI Text Watermarking

Henri F. Van Ryn
Independent Researcher
henri.vanryn@gmail.com

Version 5.8 | February 10, 2026; revised June 23, 2026

> Watermark detection tells you a signal is present; it does not tell you whether the signal is strong enough to act on. This paper shows why that gap is largest exactly where institutions are most tempted to act: short texts. It also identifies what disclosure is needed before a detector output can bear institutional weight.

This repository contains the public deposit of the working paper formalizing the Statistical Horizon as a structural scaling benchmark for finite-sample AI text watermark detectability.

## Abstract

AI text watermarking has moved from academic speculation into industrial and institutional consideration, but watermark detections remain probabilistic indicators rather than proof of authorship. This paper formalizes the Statistical Horizon as a structural scaling benchmark: in a stylized mean-shift model, the sample length required for detection scales inversely with the square of the combined signal term, creating a steep inverse-quadratic penalty for low-visibility watermarking.

The paper distinguishes two thresholds: a lower detectability floor, n_h, representing the 50%-power point, and a higher-power reliability benchmark, n_E. It argues that crossing the detectability floor does not, by itself, justify institutional reliance.

The framework's contribution is to discipline how watermark signals are interpreted, not to weaken watermarking technology. It does not propose a new detector, a universal token threshold, or an admissibility rule. Instead, it shows why short-text detections under undisclosed parameters are especially vulnerable to overinterpretation, and it sets out what should accompany a detector output before an institution relies on it: disclosed system parameters, empirically characterized error rates at the relevant text length, robustness information, base-rate and multiple-testing context, and corroboration.

The paper situates this caution within current governance. Where a watermark detector output is offered as expert evidence in a U.S. federal proceeding, the disclosures proposed here are technical inputs to the court's Rule 702 / Rule 104(a) reliability gatekeeping, not a substitute for it. In the EU, the framework bears on Article 50 transparency obligations and related transparency expectations for AI-generated content.

## Core Claim

The Statistical Horizon is not an anti-watermarking argument. It is an anti-overclaiming argument.

A watermark detector may be technically valid and still produce outputs that are too weak, too length-sensitive, or too poorly disclosed to support institutional action in a particular case. The shorter the text and the less visible the watermark signal, the more this distinction matters.

## Files

- [`statistical_horizon_v5_8.pdf`](statistical_horizon_v5_8.pdf) — current manuscript (v5.8)
- [`statistical_horizon_v5_8.tex`](statistical_horizon_v5_8.tex) — editable LaTeX source (canonical master)
- [`statistical_horizon_v5_final.pdf`](statistical_horizon_v5_final.pdf) — earlier manuscript (v5.0, archival)
- [`statistical_horizon_v5_final.pdf.ots`](statistical_horizon_v5_final.pdf.ots) — OpenTimestamps blockchain proof of existence for v5.0 (April 16, 2026)
- [`statistical_horizon_v5_fixed.docx`](statistical_horizon_v5_fixed.docx) — Word source (v5.0, archival)

## Version History

- **v5.8** (June 23, 2026): Terminology aligned with evidence-law usage (detectability / reliability / institutional reliance rather than "sufficiency"); Rule 702 / 104(a) gatekeeping framing added; autocorrelation magnitude estimate and correlated-signals caution added; reference corrections.
- **v5.0** (February 10, 2026, revised April 16, 2026): Original public deposit with OpenTimestamps proof. Retained unaltered for provenance.

## Keywords

AI watermarking; statistical inference; forensic science; institutional reliance; machine learning governance; digital provenance; AI policy

## Provenance

SHA256 (statistical_horizon_v5_final.pdf): a5a05d6e458282bce5749eeb7fd254c60046a9b359ec1bbc3ccf2a73380e810f

Timestamp: OpenTimestamps blockchain proof of existence, April 16, 2026 (see statistical_horizon_v5_final.pdf.ots)

Preprint: A formal preprint submission was attempted; the current manuscript and timestamped proof of existence are available in this repository.

## License

CC-BY Attribution 4.0 International
