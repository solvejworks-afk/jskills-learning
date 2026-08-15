# JSkills Complete Multi-Page Platform

This build combines the uploaded Grade 3–12 packages and the Teacher Portal into one deployable folder.

## Page structure
- `index.html` — school login + grade selection + Teacher Portal link
- `grade3/index.html` through `grade12/index.html` — separate grade pages
- `teacher.html` — separate Teacher Portal
- Each grade retains its uploaded `styles.css`, `script.js`, and where supplied, `data.js`.

## Navigation
Every major selection opens a separate HTML page:
School Home → Grade → Topic/Learning screens within the selected grade package.
The top navigation on every grade page returns to JSkills Home or opens Teacher Portal.

## Teacher Portal
- Lesson plan creation for Grades 3–12
- Question paper generator
- Unit / Midterm / Quarterly / Half-Yearly / Annual
- Grade-wise assessment analysis
- Student level categorisation
- Report card generation and print
- Whole-class progress
- Remedial / Developing / Board-ready / Advanced pathways

## GitHub Pages
Upload the complete contents of this folder to the repository root, then enable GitHub Pages from the repository's Settings → Pages → Deploy from branch.
