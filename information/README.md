## Problem

Producing convincing text, images, audio and video is now nearly free. Checking whether any of it is real is not. See [ai](../ai/).

Attention is allocated by systems optimised for engagement, and outrage engages better than accuracy.

A society that cannot agree on basic facts cannot make collective decisions or hold power to account. See [politics](../politics/).

Once anything can be faked, real evidence also stops convincing anyone. That is the more dangerous half: not that lies are believed, but that nothing is.

Trust is far cheaper to destroy than to rebuild.

## Research

Trust is measured, and falling. The [Reuters Institute Digital News Report](https://reutersinstitute.politics.ox.ac.uk/digital-news-report/2026/dnr-executive-summary) surveys about 97,500 people across 48 markets each year. As of 2026:

* 37% say they can trust most news most of the time, the lowest since the measure began in 2015, after three years flat at 40%.
* 62% worry about telling real from fake online, up 4 points in a year.
* 42% actively avoid the news.
* Social media and video networks (54%) are now the most used news source, ahead of TV and news sites.

In the US, [Pew](https://www.pewresearch.org/short-reads/2025/10/29/how-americans-trust-in-information-from-news-organizations-and-social-media-sites-has-changed-over-time/) found 56% with at least some trust in national news organisations in September 2025, down from 76% in 2016. Local news holds up better at 70%. The fall is uneven: 44% among Republicans, 69% among Democrats.

The measured reach of false content is smaller than the debate assumes. In the 2016 US election, 0.1% of Twitter users produced about 80% of fake-news shares and 1% of users took 80% of the exposures ([Grinberg et al., Science 2019](https://www.science.org/doi/10.1126/science.aau2706)). Fake news was about 0.15% of the American daily media diet ([Allen et al., Science Advances 2020](https://www.science.org/doi/full/10.1126/sciadv.aay3539)). A 2024 review in Nature argues three popular claims are unsupported: that average exposure is high, that algorithms mainly cause it, and that social media is a primary driver of polarisation ([Budak et al.](https://www.nature.com/articles/s41586-024-07417-w)). Concentrated is not harmless, since the small motivated fringe is also the part that acts. Almost all of this evidence is US, English-language and predates cheap generative video.

Corrections mostly work. The backfire effect, the claim that correcting a false belief hardens it, is widely repeated and has replicated poorly. Wood and Porter tested 52 contested issues across more than 10,100 subjects and found no case of backfire ([Political Behavior, 2019](https://link.springer.com/article/10.1007/s11109-018-9443-y)). Simultaneous fact-checking experiments in Argentina, Nigeria, South Africa and the UK reduced false beliefs in every country, with most effects still detectable two weeks later ([PNAS, 2021](https://www.pnas.org/doi/10.1073/pnas.2104235118)). Moving a stated belief is much easier than moving a vote.

On whether algorithmic feeds polarise, the best test is the preregistered 2020 Facebook and Instagram Election Study, run on Meta's own data. Replacing the algorithmic feed with a reverse-chronological one for three months cut time on platform sharply but did not measurably change issue polarisation, affective polarisation or political knowledge ([Guess et al., Science 2023](https://www.science.org/doi/10.1126/science.abp9364)). Three months in one country is not the whole question, but it is the strongest causal evidence available. See [politics](../politics/).

Detection is losing. Against deepfakes actually circulating in 2024, state-of-the-art open-source detectors lost roughly 50% AUC on video, 48% on audio and 45% on images versus their benchmark scores ([Deepfake-Eval-2024](https://arxiv.org/abs/2503.02857)). Detectors learn the fingerprints of the generators they trained on, and generators change faster than detectors are retrained. Generation is a one-off cost paid by the forger; verification is a per-item cost paid by everyone else. See [ai](../ai/).

Provenance is the alternative, and it is not ready. C2PA cryptographically signs where an asset came from and how it was edited. Its own [security document](https://spec.c2pa.org/specifications/specifications/2.4/security/Security_Considerations.html) states that C2PA "does not offer any protection against the complete removal of C2PA manifests" - a screenshot or re-encode strips it - and that it attests provenance, not truth. An independent formal review in 2026 concluded the specifications "fail to achieve their claimed security goals" and advised against relying on them for journalism or legal evidence ([Golaszewski et al.](https://arxiv.org/abs/2604.24890)).

The liar's dividend has been measured. Across five experiments with over 15,000 US adults, politicians who answered a genuine scandal by calling the story fake gained more support than by apologising or staying silent, across partisan groups. The tactic worked against text reports and was largely ineffective against video ([Schiff, Schiff and Bueno, APSR 2025](https://www.cambridge.org/core/journals/american-political-science-review/article/liars-dividend-can-politicians-claim-misinformation-to-evade-accountability/687FEE54DBD7ED0C96D72B26606AA073)). Video is the protection that cheap generation is removing.

## Solutions

