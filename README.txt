BillCapture Demo (static, client-side)
======================================

What this is
------------
A single-file web prototype that mimics a mobile bill-capture app:
1) Capture or upload a photo
2) Fake "scan" step
3) Review editable fields
4) Generate a document preview
5) Submit confirmation

No backend. No storage. Everything runs in the browser.

How to publish on GitHub Pages
------------------------------
1) Create a new public repository on GitHub (e.g., billcapture-demo).
2) Upload `index.html` and `logo.png` to the repository root.
3) Go to Settings → Pages → Build and deployment:
   - Source: Deploy from a branch
   - Branch: main
   - Folder: /(root)
   Save.
4) Wait ~1 minute. Your site will be at:
   https://USERNAME.github.io/REPO-NAME/
   Replace USERNAME and REPO-NAME accordingly.

How to change branding
----------------------
- Replace logo.png with your logo file (same name). PNG or SVG recommended.
- Edit colors: open index.html and change CSS variables near the top:
    --brand, --accent, --bg, --card, --text.
- Change the title text “BillCapture · Demo” in the <title> and <h1> tags.

How to embed in Squarespace
---------------------------
Add an Embed block and paste:
<iframe src="https://USERNAME.github.io/REPO-NAME/" style="width:100%;height:900px;border:0"></iframe>

Notes
-----
- On iPhone, open in Safari for camera access.
- This is a demo only. It does not upload or store data.
