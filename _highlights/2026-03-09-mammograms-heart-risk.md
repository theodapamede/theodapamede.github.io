---
title: "Mammograms can reveal heart risk in women"
date: 2026-03-09
permalink: /highlights/mammograms-heart-risk/
excerpt: "Using AI to measure calcium in breast arteries on routine screening mammograms, we found it predicts heart attacks, strokes, heart failure and death, beyond standard heart-risk scores. *European Heart Journal*, 2026."
og_image: highlights/bac-ehj-2026-og-image.png
---

{% include base_path %}

**In one sentence:** calcium deposits in the arteries of the breast, measured automatically by AI on the mammograms women already have for breast cancer screening, predict future heart attacks, strokes, heart failure and death, and add information that standard heart-risk scores miss.

## Why this matters

Heart disease is the leading cause of death in women, yet women are more often underdiagnosed and undertreated for it than men. At the same time, millions of women have a screening mammogram every year. Those images often show calcium in the small arteries of the breast, known as breast arterial calcification (BAC). Because it is unrelated to breast cancer, it is rarely measured or reported, even though it reflects the health of the blood vessels.

## What we did

We built an AI model that finds and measures BAC on screening mammograms, trained on 1,000 mammograms annotated by an expert breast radiologist. We then applied it to **123,762 women** at two health systems, Emory Healthcare (74,124 women) and Mayo Clinic (49,638 women), with a median follow-up of **7 years**. We grouped women by the amount of calcium (none, mild, moderate or severe) and compared their cardiovascular outcomes, adjusting for the American Heart Association's PREVENT risk score.

<figure>
  <img src="{{ base_path }}/images/highlights/bac-ehj-2026-figure1.jpg" alt="Three pairs of mammograms showing mild, moderate and severe breast arterial calcification, each next to the AI model's calcification map" style="max-width: 420px;">
  <figcaption>Examples of mild, moderate and severe breast arterial calcification (left) and the AI model's calcification map (right).</figcaption>
</figure>

## What we found

- **More calcium, more risk.** Compared with women without BAC, risk of a major cardiovascular event rose step by step with mild, moderate and severe calcification. Women with severe BAC had roughly **three times** the risk.
- **Beyond standard risk scores.** The association held after accounting for the PREVENT score, so BAC adds information that today's risk calculators do not capture.
- **Including younger women.** Moderate to severe BAC was also linked to worse outcomes in women **under 50**, a group usually considered low risk.
- **Confirmed at a second health system.** The results held in the independent Mayo Clinic cohort.

<figure>
  <img src="{{ base_path }}/images/highlights/bac-ehj-2026-graphical-abstract.jpg" alt="Structured graphical abstract summarizing the study design, the AI calcification pipeline and survival curves by calcification severity">
  <figcaption>The study at a glance: cohort, AI pipeline and cardiovascular outcomes by calcification severity.</figcaption>
</figure>

## What it could mean

Because the mammogram has already been taken, an automated BAC reading adds a cardiovascular check to breast cancer screening **without extra imaging or radiation**. It could help flag women who would benefit from earlier preventive care, such as a cardiology referral or closer control of blood pressure and cholesterol. Before routine use, the approach still needs prospective evaluation in clinical practice.

## Read more

- **Paper (open access):** Dapamede T, Urooj A, Joshi V, et al. Artificial intelligence-based quantification of breast arterial calcifications to predict cardiovascular morbidity and mortality. *European Heart Journal*. 2026;47(18):2206–2220. [doi:10.1093/eurheartj/ehag128](https://doi.org/10.1093/eurheartj/ehag128)
- **In the news:** [The Washington Post](https://www.washingtonpost.com/health/2026/03/09/ai-mammograms-heart-disease-risk-women/), and more than [110 news outlets worldwide](https://oxfordjournals.altmetric.com/details/192152517/news).
- **Earlier results:** presented at ACC.25 ([American College of Cardiology press release](https://www.acc.org/About-ACC/Press-Releases/2025/03/20/09/58/AI-Powered-Mammograms)).

<small>Figures reproduced from Dapamede et al., *European Heart Journal* 2026, under a [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) license.</small>
