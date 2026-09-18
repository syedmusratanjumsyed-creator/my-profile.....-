Syed Musrat Anjum - Portfolio Website
=====================================

Files
-----
index.html        the whole page
css/style.css     orange & white theme
js/script.js      mobile menu, active link, footer year

How to view
-----------
Unzip the folder and double-click index.html. It opens in any browser,
no install or server needed.

How to put it online (free)
---------------------------
1. Go to https://app.netlify.com/drop
2. Drag the unzipped "portfolio" folder onto the page.
3. You get a live link straight away, e.g. yourname.netlify.app

What to edit
------------
- Text: open index.html in Notepad / VS Code and change the wording.
- Colours: top of css/style.css, the :root block.
    --orange       main orange
    --orange-deep  darker orange for hover
    --orange-soft  pale orange background
- Skill percentages: in index.html search for style="--w:90%".
- Add your resume PDF: put the file in this folder and add a link:
    <a class="btn btn-ghost" href="resume.pdf" download>Download resume</a>
- Add GitHub / LinkedIn: add links inside the contact section.
