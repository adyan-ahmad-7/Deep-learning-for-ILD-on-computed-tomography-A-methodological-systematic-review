# Supplementary Materials: Data Leakage and Reported Accuracy of Deep Learning for Interstitial Lung Disease on CT

Electronic supplementary materials for a methodological systematic review of data leakage and reported accuracy in deep learning studies of interstitial lung disease (ILD) on computed tomography (CT).

## Contents

| File | Online Resource | Description |
|------|-----------------|-------------|
| `ESM_1.pdf` | 1 | PRISMA 2020 checklist. Shows where each reporting item appears in the manuscript. |
| `ESM_2.pdf` | 2 | Complete search strategies for all six sources, with search dates, record counts and PRISMA-S items. |
| `ESM_3.xlsx` | 3 | Review dataset: extracted data, risk-of-bias judgements, supporting passages and retrieval log. |
| `ESM_4.pdf` | 4 | Appraisal manual: rules for classifying partitioning and judging the appraisal domains. |

## File details

### ESM_1: PRISMA 2020 checklist
Maps each PRISMA 2020 item (1 to 27) to the section, table or figure of the manuscript where it is reported.

### ESM_2: Search strategies
- Six sources searched without date or language limits: PubMed/MEDLINE, Europe PMC, IEEE Xplore, ScienceDirect, OpenAlex and Semantic Scholar.
- Final database searches were run on 28 October 2026. Citation searching used OpenAlex.
- 2,647 database records were retrieved (1,086 after deduplication across sources), plus 1,913 citation-linked records.
- Search strings are given exactly as entered in each interface.

### ESM_3: Dataset (Excel workbook)
| Sheet | Content |
|-------|---------|
| Read me | Overview of the workbook |
| Included studies | One row per included study (35 studies, 37 reports): extracted items, partitioning and test categories, risk-of-bias judgements, rigour and reproducibility scores |
| Supporting passages | Verbatim passages supporting each partitioning, tuning and test judgement |
| Within-study comparisons | Same metric for the same model on internal data versus a stricter test |
| Group summaries | Counts and medians by task, journal type, indexing and partitioning category |
| Abstract-level appraisal | Abstract-level appraisal of reports not retrieved in full text |
| Retrieval log | Full-text retrieval attempts, routes tried and outcomes |
| Data dictionary | Definition of every column and category |

Overall risk of bias, the independent-patient test flag, both scores and the group summaries are calculated by formula, so they update if the inputs are edited.

### ESM_4: Appraisal manual
Decision rules used to:
- classify partitioning (patient-level, documented sub-patient, suspected sub-patient, not reported)
- judge split independence (D1), tuning independence (D2), strongest test (D3) and label-source confounding (D4)
- assign overall risk of bias
- score evaluation rigour (0 to 4) and reproducibility (0 to 6)

## Notes
- Judgements are based only on what each article reports. When an article is silent, the item is judged "unclear".
- The rigour and reproducibility scores are unweighted counts that describe the literature. They are not quality grades of individual studies.
- Counts will differ if the searches are re-run, because the sources are updated continuously.

## How to use
- Open the PDFs in any PDF reader.
- Open `ESM_3.xlsx` in Excel, LibreOffice or any compatible spreadsheet software. Start with the **Read me** and **Data dictionary** sheets.

## Contact
[Add corresponding author name, affiliation and email]

## License
[Add license, e.g. CC BY 4.0]

## Citation
[Add citation once the article is published]
