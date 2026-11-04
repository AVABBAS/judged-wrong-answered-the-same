# Judged Wrong, Answered the Same: Data and Materials

Data and materials for the article:

> Hamidavi, A. *Judged Wrong, Answered the Same: Judgment–Revision Decoupling in Iterative LLM Self-Review.* Submitted to *AI and Society*, November 2026. Preprint: Research Square, rs-10463884. The same materials are also deposited on the Open Science Framework: [osf.io/bef52](https://osf.io/bef52/).

## About the study

Three frontier models (GPT-5.4, Claude 4.6 Sonnet, and Gemini 3.1 Pro) solved one arithmetic word problem and then reviewed their own preceding output seven times in succession (63 review rounds in total), each time stating an explicit judgment of the work and a final answer. In 9 of the 63 rounds a model judged its own solution "partially wrong" and then restated the identical answer in the same response: the evaluative act was performed in full, and the number it condemned was repeated without change. A companion elicitation study is reported alongside: 36 further solutions to ten classic trap problems under two generation protocols, in which no model produced a wrong initial answer.

## Contents

| Folder | Contents |
| --- | --- |
| `transcripts/` | The complete conversational transcripts for the three models (plain-text renderings of the archived PDFs in the OSF deposit). |
| `codebooks/` | The three per-model codebooks (plain-text renderings of the archived PDFs). |
| `coding-data/` | The archived inter-rater reliability report, and the recount and correction note described below. |
| `elicitation/` | The complete elicitation-study materials: both pilot prompt sets, the per-model pilot solution logs, the reserve solutions, the compiled materials file, and the deposit's own readme. |

## A note on the archived reliability report

The archived inter-rater reliability report in `coding-data/` predates a full recount of the transcripts. Its headline agreement figures (100 percent agreement, kappa of 1.0) do not survive that recount and are explicitly disavowed in the article. The report is preserved here as part of the study record; the recount and correction note in the same folder gives the verified judgment and answer counts re-extracted mechanically from the transcripts, and those are the counts the article reports.

## Citation

Please cite the article. Citation metadata is provided in [CITATION.cff](CITATION.cff).

## Licence

The contents of this repository are released under the Creative Commons Attribution 4.0 International licence (CC BY 4.0, see [LICENSE](LICENSE)).

The transcripts are outputs of publicly available AI systems, generated for this study. They contain no personal data.

## Contact

Abbas Hamidavi
Department of Computer Engineering, Mashhad Branch, Islamic Azad University, Mashhad, Iran
ORCID: [0009-0001-7342-7844](https://orcid.org/0009-0001-7342-7844)
