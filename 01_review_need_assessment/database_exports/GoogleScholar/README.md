# Google Scholar review-need retrieval

This directory stores the Google Scholar top-100 retrieval for the review-need search.

- Query: `query.txt`
- Publication-year filter: none
- Ranking: relevance
- Retrieval size: first 100 records (five pages of 20)
- Patents: excluded
- Citations: included
- Output: `google_scholar_top100.bib`
- Audit: `google_scholar_top100_audit.txt`

Google Scholar acquisition is recorded separately from BibTeX construction because it does not provide an official public Scholar API. The five result pages are saved as a structured `google_scholar_top100_raw.json` file with ranks 1--100.

The resulting `google_scholar_top100.bib` preserves Scholar rank and does not deduplicate the 100 input records. Metadata may be enriched from local bibliographies and Crossref, but the result order is not changed.
