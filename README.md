\# Patent Examiner Virtual Assistant



Browser-based patent examiner support tool hosted with GitHub Pages.



\## Features



\- Patent claims text analysis

\- CPC prediction using local CPC scheme and definition files

\- Claim mapping

\- Unity assessment

\- Claims tree view

\- Virtual examiner analysis

\- PERP builder

\- PDF upload and text extraction support

\- Local image and JavaScript assets for offline-style browser execution



\## Included files



\- `index.html` or `index-v26.2.1-stable.html`  Main application page

\- `ipc\_cpc\_section\_map.js`  CPC or IPC subclass to examination section mapping

\- `perpData.js`  PERP objection builder data

\- `cpcDefinitions-2026.js`  CPC definitions data

\- `cpcScheme-2026.js`  CPC scheme data

\- `pdf.min.js`  PDF.js browser library

\- `pdf.worker.min.js`  PDF.js worker library

\- `IP Aust\_inline\_white\_95pxhigh.png`  Banner logo image



\## Hosting on GitHub Pages



1\. Create a new GitHub repository

2\. Upload all project files to the repository root

3\. In GitHub, open \*\*Settings\*\* > \*\*Pages\*\*

4\. Under \*\*Build and deployment\*\*, choose:

&#x20;  - Source: `Deploy from a branch`

&#x20;  - Branch: `main`

&#x20;  - Folder: `/ (root)`

5\. Save the settings

6\. Open the published site at:



&#x20;  `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/`



If you keep the original HTML filename instead of renaming it to `index.html`, open:



`https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/index.html`



\## Local development



\- Download or clone the repository

\- Open `index.html` in a browser



\## Notes



\- This is a static site intended to run in the browser

\- All outputs should be reviewed and validated by the user before use

\- If you move files into subfolders, update all relative paths in the HTML



\## Updating the site



\- Edit the files locally

\- Commit and push to `main`

\- GitHub Pages republishes the latest version automatically



\## Support



Use GitHub Issues in this repository for bug reports or enhancements.

