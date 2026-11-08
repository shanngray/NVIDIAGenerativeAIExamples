# SECURITY STATUS: INACTIVE (classified 2026-11-09)

On 2026-11-09, Shannon Gray classified this repository as **inactive** for his own work. This is Shannon Gray's classification of his own use of the project. It is not an independent assessment of whether the code is maintained.

It **has known, unfixed security vulnerabilities** in its dependencies. The dated inventory generated 2026-11-09T07:12:20+11:00 (OSV, GitHub Advisory Database via OSV, and CISA KEV), retained in the parked-findings list generated 2026-11-09T08:41:59+11:00, recorded 983 open advisories against this repository's default branch: 91 critical, 418 high, 347 medium, 59 low, 4 none, 64 unknown. This notice repeats that inventory. It is not a new scan.

Most serious (up to 5):
- langchain_community 0.0.16 (PyPI): PYSEC-2025-70 / CVE-2025-2828, severity critical; fixed in no fix listed
- nltk 3.8.1 (PyPI): GHSA-7p94-766c-hgjp / CVE-2025-14009, severity critical; fixed in 3.9.3
- nltk 3.8.1 (PyPI): PYSEC-2026-96 / CVE-2025-14009, severity critical; fixed in 3.9.3
- nltk 3.8.1 (PyPI): PYSEC-2026-99 / CVE-2026-0848, severity critical; fixed in 3.9.3
- gradio 4.13.0 (PyPI): PYSEC-2024-215 / CVE-2024-47167, severity critical; fixed in 5.0.0

## Retained findings
Known findings for this repository are kept on record (Sentry's parked-findings list: 983 open entries as of 2026-11-09T08:41:59+11:00) and are not deleted while it is inactive. That inventory records no CISA KEV finding for this repository.

## Before work resumes
1. Review the recorded findings and re-scan for newer advisories.
2. Remediate: update affected dependencies to fixed versions.
3. Test the project after the updates.
4. Then update or remove this file.

## Alerts while inactive
While this repository is inactive, Shannon gets a security alert only for **confirmed active exploitation**: a listing in the CISA Known Exploited Vulnerabilities catalog, OR reliable evidence of in-the-wild exploitation from another source (with source, URL and date). A public proof-of-concept or exploit code alone is not enough. Other advisories are kept on record without an alert.

## About this file
This file is a notice only. Placing it here does not guarantee that every person or tool reading the repository will see it. It does not replace or change any existing security policy. [SECURITY.md](SECURITY.md) remains the security policy for this repository and still applies; report vulnerabilities as it describes.
