## Problem

Artificial Intelligence (AI) is growing in capability quickly. Graphs show exponential growth, following Moore's Law.

Human Intelligence on the other hand is limited by biology, at only 100000000000 neurons clocked at 30 Hz.

AI can do more and more jobs at a faster, more consistent pace and at a lower price than humans, so there will be many jobs lost, causing large unemployment. See [economics](../economics)

Creating an AI that is much more intelligent than humans causes existential [risks](https://en.wikipedia.org/wiki/Existential_risk_from_artificial_intelligence) for humanity.

Cheap generated text, images and video also make it hard to tell what is real. See [information](../information/).

The same design tools that speed up medicine lower the barrier to engineering pathogens. See [health](../health/).

Faster, more automated military decisions shorten the time available to humans. See [war](../war/).

Safety training is a property of the weights as shipped, not of the model. Open-weight releases can be "abliterated": the internal direction that produces refusals is found and suppressed, which strips the refusal behaviour cheaply and without retraining. Whatever a model can do, someone will make it do. Weights, once published, cannot be recalled. See [information](../information/) and [health](../health/).

## Research

The inputs are growing far faster than the economy around them. From [Epoch AI](https://epoch.ai/trends) (figures as of 2026):

* Training compute for frontier language models has grown about 5x per year since 2020; across all notable models since 2010 the trend is about 4.5x per year.
* The cost of a frontier training run has risen about 3.5x per year since 2020, a doubling roughly every seven months.
* Pushing the other way: AI chip performance per dollar has improved about 49% per year since 2023, and pre-training compute efficiency about 3.0x per year. A given capability gets cheaper every year even as the frontier gets more expensive.
* Data centres used about 415 TWh in 2024, roughly 1.5% of world electricity, growing about 12% per year; the [IEA](https://www.iea.org/reports/energy-and-ai/energy-demand-from-ai) base case is about 945 TWh by 2030, just under 3%. See [energy](../energy/).

Capability is measured badly, and the measures keep breaking. On SWE-bench Verified, scores went from about 60% to near the human baseline in a single year, and models gained about 30 points on Humanity's Last Exam in a year ([AI Index 2026](https://hai.stanford.edu/ai-index/2026-ai-index-report)). Benchmarks built to last years saturate in months, so a benchmark score carries less information each year.

The closest thing to a clean rate is task length. [METR](https://metr.org/time-horizons/) measures the length of software task a model finishes with 50% success: doubling every ~197 days over the whole record, ~131 days since 2023, ~89 days since 2024, reaching about 320 minutes (CI 170-729) for the best model measured in January 2026. METR itself warns that estimates above 16 hours are unreliable because the task suite saturates, that only 5 of its 31 long tasks have real human baselines, and that the trend shifts when the task mix changes. Reliability matters: at a stricter success bar the horizons are far shorter. The [International AI Safety Report 2026](https://yoshuabengio.org/en/publication/international-ai-safety-report-2026) puts reliable autonomous work at about 30 minutes of a human programmer's time, up from under 10 minutes a year earlier.

What safety institutes actually measure is capability and safeguards, not probability of harm. The [UK AI Security Institute](https://www.aisi.gov.uk/frontier-ai-trends-report) reports success on apprentice-level cyber tasks rising from under 9% in late 2023 to about 50% in 2025, self-replication benchmark success from under 5% in early 2023 to over 60% by summer 2025, and it says it has found universal jailbreaks for every system it has tested. See [health](../health/) and [war](../war/).

Labour effects are visible but contested. The [ILO](https://www.ilo.org/publications/generative-ai-and-jobs-refined-global-index-occupational-exposure) (2025) puts about a quarter of world employment in occupations with some generative-AI exposure and 3.3% in the highest gradient, skewed female (4.7% vs 2.4%). [Stanford's payroll study](https://digitaleconomy.stanford.edu/publication/canaries-in-the-coal-mine-six-facts-about-the-recent-employment-effects-of-artificial-intelligence/) finds employment of 22-25 year olds in the most exposed occupations 19% below the counterfactual as of June 2026, up from 15% in July 2025, with no such gap for experienced workers; the authors call this descriptive, not causal. Against that, [METR's 2025 trial](https://metr.org/blog/2025-07-10-early-2025-ai-experienced-os-dev-study/) found 16 experienced developers 19% slower with AI tools while believing they were 20% faster. See [economics](../economics/).

Where it might stop: [Epoch's bottleneck analysis](https://epoch.ai/blog/can-ai-scaling-continue-through-2030) (2024) finds power binds first, with runs around 2e29 FLOP feasible by 2030 given multi-gigawatt campuses, and public human text the other near-term limit. Forecasters disagree on whether 4-5x per year holds or decelerates to 3-4x from 2026.

Open weights set a floor under all of this. Refusal behaviour in open-weight chat models is mediated largely by a single direction in activation space, and removing that direction disables refusals across prompts while leaving other capabilities close to intact ([Arditi et al. 2024](https://arxiv.org/abs/2406.11717)). The technique needs no retraining and runs on ordinary hardware, so abliterated variants of major releases appear on model-sharing sites within days. The practical floor for misuse is therefore set by the most capable open-weight model, not by the most capable model.

Timelines move a lot. The 2023 survey of [2778 AI researchers](https://arxiv.org/abs/2401.02843) gave a median of 2047 for machines outperforming humans at every task, 13 years earlier than the same question a year before. Between 38% and 51% assigned at least a 10% chance to outcomes as bad as human extinction.

## Solutions
