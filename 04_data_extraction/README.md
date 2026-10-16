# Data extraction and synthesis

`paper_data_extract_sum.xlsx` is the combined extraction workbook. Its source index contains all 61 included sources. Final inclusion and evidence-maturity decisions match the manuscript. The independent quality scores remain in `../02_primary_study_search/quality_assessment/`.

| Research question | Unit and final material |
|---|---|
| RQ1 | 113 application tasks and the reported evaluation designs. The normalized CSVs link to task IDs and source excerpts. |
| RQ2 | Five functional positions across 113 task reports. The task-step matrix distinguishes explicitly described actions from inference identified through a verifiable relation output. Source evidence, process codes, and material-specific steps are retained in the process workbook. |
| RQ3 | 139 distinct target-LLM operations. Of these, 137 are assigned to five functional roles and two remain unclear. Configuration variants with the same transformation count once. |
| RQ4 | 281 target-LLM uses, of which 255 are classifiable. Configuration facets, parameter reporting, configuration completeness, and resource access have separate units. Source-level summaries use all 61 sources. |
| RQ5 | Source-level memberships in seven external-component families and five process positions. Forty-six sources report eligible external components. Detailed component descriptions and final family-position memberships are linked by source ID. |
| RQ6 | 285 limitation statements with a primary theme, evidence nature, barrier-severity score, and mitigation-maturity score. The workbook contains the record-level coding and the seven-theme synthesis. |
| RQ7 | 258 technical research directions assigned to five themes. Two out-of-scope statements are retained separately in the record table and excluded from the theme totals. |

Source-level memberships may overlap across tasks, roles, families, positions, and themes. Only mutually exclusive categories should be added. NR means not reported, NA means not applicable, and Unclear means that the source does not provide enough detail to decide.

`RQ4/rq4_resource_access.csv` classifies all 61 sources. It separates public materials, materials requiring a request, unverified public links, materials mentioned without a URL, private materials, information-only pages, private demonstration instances, and unreported resources.

Video timestamps and document pages locate source quotations. The corresponding files are in `../02_primary_study_search/grey_literature_evidence/`. Verbatim evidence is kept separate from interpretation and coding.
