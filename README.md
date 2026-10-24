# CH² PYQ Vault — GATE Chemical Engineering

**Live site:** https://sathwik6174.github.io/gate-ch-pyq-vault/

A topic-led question bank for GATE Chemical Engineering previous-year papers (2007–2025).

## What’s in the site

- **Topic Explorer:** select a syllabus area and open question records across years.
- **Question bank:** search extracted question text, filter by topic/year, and limit results to items needing review.
- **Question metadata:** year, question number/section, source PDF page, topic/subtopic, and a topic-suggestion confidence indicator.
- **Original paper links:** use the source PDF/host link to verify exact wording, symbols, options, figures, and numbering.
- **Answer-key desk:** answer-key references and a visible conflict log for 2013.
- **Static hosting:** GitHub Pages; no Python, local server, build step, or account needed to use the site.

## Data quality and important limitations

The current bank contains 1,270 question records across the supplied papers. Question boundaries and subject/topic labels were generated with a text/OCR-assisted pipeline and syllabus-aligned keyword rules; they have **not** all been manually checked. Each result has a review flag and confidence indicator, and missing/uncertain OCR is called out rather than fabricated. The text shown in the bank is an excerpt/transcription aid, not a replacement for the original PDF, especially for equations, diagrams, linked questions, and answer options.

Official answer keys take precedence where available. Older third-party answers and the 2013 discrepancies are marked for independent verification. Detailed, independently validated worked solutions have not yet been added for every question; no solution is implied merely because a key link is present.

## Sources

- Official GATE downloads: https://gate2026.iitg.ac.in/download.html
- NDLI / IIT Kharagpur GATE CH archive: https://ndl.iitkgp.ac.in/cd_document/gate/ch
- Third-party paper archive: https://www.gateexam.info/previous-papers/CH/

## Deployment

GitHub Actions deploys the static site to GitHub Pages when changes reach `main`. Workflow status: https://github.com/Sathwik6174/gate-ch-pyq-vault/actions
