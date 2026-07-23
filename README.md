# Paul Thibodeau Solutions Portfolio

Static, GitHub Pages-ready portfolio showcasing Mission PMIS, Hanover InspectorPro, and the Owner's Construction QA Manual.

## Preview
Open `index.html` in a browser.

## Publish
Upload the full folder contents to a GitHub repository, then enable GitHub Pages from the `main` branch and `/root`.

## Before publishing
Replace the placeholder email and LinkedIn link in `index.html`. Add screenshots and live-project links when ready.

## Live project links

- Mission PMIS: https://whateverfps.github.io/mission-pmis/
- Hanover InspectorPro: https://whateverfps.github.io/InspectorPro-Hanover/


## Mission PMIS demo workbook

The portfolio includes `assets/data/Bedford_VA_EHRM_PMIS_MASTER_v9.0.xlsx`. The Mission PMIS live-system link now opens a launcher that downloads this workbook and opens the live PMIS site. Due to browser security, the visitor must still click **Load Excel Workbook** inside PMIS and select the downloaded file. Fully automatic population requires a small update to the Mission PMIS repository itself so it can fetch a packaged workbook by URL.


## Version 4 addition

City InspectorPro has been added as a fourth featured system. The portfolio includes a dedicated case study and downloadable source stack.

Because City InspectorPro is a Flask application, it cannot execute directly on GitHub Pages. A live hosted version requires a Python-capable application host.


## Version 5 addition

Mission Companion v3.36 has been added as the fifth featured system. The downloadable source is sanitized: `.env`, credentials, and bundled project/document libraries are excluded.


## Version 6

Mission Companion was rebuilt as a visual SaaS-style case study using real application screenshots. Public source-download links were removed.
