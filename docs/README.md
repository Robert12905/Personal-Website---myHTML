This repository acts as a personal web-domain to use as my personal portfolio going forward. This website will be built and maintained over time, which I plan on hosting locally via my homelab. The intention is to provide future employers and peers a clean and concise way of contacting me and gathering information regarding my professional career as a software engineer.

External Interface & Navigation The user interacts with this software through a standard web UI. The interface consists of: Navigation Bar: Uses anchor links to navigate between the "Home," "About," and "Projects" sections. External Outbound Links: Interactive buttons linking to , , and . Responsive Layout: The interface automatically adjusts for desktop, tablet, and mobile viewports.

Technical Documentation How to Obtain and Install Clone the Repository:

Dependencies: None. This project (currently) uses raw HTML, CSS, and Vanilla JavaScript. No build tools or package managers are required.

How to Run Navigate to the project folder on your local machine.

Open the index.html file in any modern web browser (Chrome, Firefox, Safari, or Edge).

Contributing & Feedback If you find a bug or have a suggestion, please see the file for details on how to report issues or suggest enhancements.

Licenses
This project is licensed under the MIT License. See the  file for the full legal text.
[![OpenSSF Scorecard](https://api.scorecard.dev/projects/github.com/Robert12905/Personal-Website---myHTML/badge)](https://scorecard.dev/viewer/?
uri=github.com/Robert12905/Personal-Website---myHTML)[![OpenSSF Best Practices](https://www.bestpractices.dev/projects/12387/badge)](https://www.bestpractices.dev/projects/12387)

This project is actively maintained. As of April 2026, I am consistently updating the content, monitoring for security vulnerabilities, and ensuring the site remains compatible with modern web browsers.
We welcome improvements to this portfolio! To maintain our OpenSSF Best Practices status, please follow these testing requirements for all change proposals:

Automated Static Analysis: Ensure all HTML/CSS/JS changes pass the existing npm test (HTMLHint/ESLint) before submitting a Pull Request. Adding New Logic: If adding JavaScript functions, you must include an inline console.assert or a corresponding test case in the tests/ directory to validate inputs/outputs. Verification: All Pull Requests will trigger a GitHub Actions run. PRs will not be merged unless all CI checks are green.

Any Issue that have been made aware to me have been listed here: [Issue Tracker] (https://github.com/Robert12905/Personal-Website---myHTML/issues)

To ensure the long-term stability and security of this portfolio, all major new functionality must be accompanied by automated tests. New UI Elements: Must be validated via htmlhint. New Logic: Must include unit tests (e.g., Jest) or assertions. Security: All new code must pass existing Semgrep and Secret-scanning pipelines
