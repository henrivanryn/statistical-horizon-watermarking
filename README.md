The Statistical Horizon: A Scaling Benchmark and Procedural Caution for Institutional Use of AI Text Watermarking

Henri F. Van Ryn
Independent Researcher
henri.vanryn@gmail.com

Version 5.8 | February 10, 2026; revised June 23, 2026

Watermark detection tells you a signal is present; it does not tell you whether the signal is strong enough to act on. This paper shows why that gap is largest exactly where institutions are most tempted to act: short texts. It also identifies what disclosure is needed before a detector output can bear institutional weight.

This repository contains the public deposit of the working paper formalizing the Statistical Horizon as a structural scaling benchmark for finite-sample AI text watermark detectability.

Abstract

AI text watermarking has moved from academic speculation into industrial and institutional consideration, but watermark detections remain probabilistic indicators rather than proof of authorship. This paper formalizes the Statistical Horizon as a structural scaling benchmark: in a stylized mean-shift model, the sample length required for detection scales inversely with the square of the combined signal term, creating a steep inverse-quadratic penalty for low-visibility watermarking.

The paper distinguishes two thresholds: a lower detectability floor, "$n_h$", representing the 50%-power point, and a higher-power reliability benchmark, "$n_E$". It argues that crossing the detectability floor does not, by itself, justify institutional reliance.

The framework’s contribution is to discipline how watermark signals are interpreted, not to weaken watermarking technology. It does not propose a new detector, a universal token threshold, or an admissibility rule. Instead, it shows why short-text detections under undisclosed parameters are especially vulnerable to overinterpretation, and it sets out what should accompany a detector output before an institution relies on it: disclosed system parameters, empirically characterized error rates at the relevant text length, robustness information, base-rate and multiple-testing context, and corroboration.

The paper situates this caution within current governance. Where a watermark detector output is offered as expert evidence in a U.S. federal proceeding, the disclosures proposed here are technical inputs to the court’s Rule 702 / Rule 104(a) reliability gatekeeping, not a substitute for it. In the EU, the framework bears on Article 50 transparency obligations and related transparency expectations for AI-generated content.

Core Claim

The Statistical Horizon is not an anti-watermarking argument. It is an anti-overclaiming argument.

A watermark detector may be technically valid and still produce outputs that are too weak, too length-sensitive, or too poorly disclosed to support institutional action in a particular case. The shorter the text and the less visible the watermark signal, the more this distinction matters.
