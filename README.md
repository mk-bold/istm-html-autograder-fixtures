# ISTM HTML autograder fixtures

Synthetic websites for validating the ISTM 209 and ISTM 210 HTML grading rubrics.

Open the [GitHub Pages fixture index](https://mk-bold.github.io/istm-html-autograder-fixtures/) to reach every live site and matching ZIP download.

- Mickey is the complete case.
- Minnie is an intentionally incomplete case.
- Donald is a limited case.
- All names, content, accounts, and artifacts are fictional test data.
- These records must be excluded from course statistics, research exports, and student comparisons.

The live pages test the published-site path. Matching ZIP downloads test the authenticated MyEducator-attachment fallback. No real student data or credentials are stored here.

For ISTM 209, the grader reads the public site first. It opens the ZIP only when the submitted public `index.html` is missing or unreadable. A ZIP fallback cannot earn the five points reserved for a reachable published site. When a live index loads but that site has broken pages or assets, the grader reports those publishing defects and does not replace the live evidence with a cleaner ZIP.

For the current ISTM 210 Take-Home 3, the submitted ZIP is the required artifact. The deterministic 40-point website rubric produces these pinned reference results:

| Fixture | Reference result |
| --- | ---: |
| Mickey Mouse | 40.00 / 40 |
| Minnie Mouse | 24.24 / 40 |
| Donald Duck | 12.39 / 40 |
