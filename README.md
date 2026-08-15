# JSkills Final v7 — Functional Simulation Build

This is the final standalone GitHub Pages demo architecture.

## Separate pages
- index.html — school login / grade hub
- grade3/index.html ... grade12/index.html — separate grade pages
- teacher.html — separate teacher portal

## Functional simulations
Every grade subject topic has a **local HTML5 Canvas simulation**. It does not depend on an iframe or an external site to function.
Each simulation has interactive controls and a topic-specific visual model.

The grade page then launches a **20-question assessment** related to the selected topic.

## External references
External providers can be added as enrichment links later (PhET, GeoGebra, HHMI BioInteractive, British Council, etc.). The local simulation is the guaranteed demo fallback.

## Pathway
Grades 3–5: foundational simulation + assessment.
Grades 6–9: science pathway adds Physics, Chemistry, Botany, Zoology and early foundation diagnostics.
Grade 10: CBSE Board + NEET foundation.
Grades 11–12: senior-secondary Physics, Chemistry, Botany, Zoology + board support.

## Teacher Portal
- Grade/lesson plan
- Question papers: Midterm, Quarterly, Half-Yearly, Annual
- Grade-wise results
- Student level categorisation
- Report cards + print
- Whole-class progress
- Intervention recommendations

## GitHub Pages
Upload the **contents of this folder** to the root of the repository. Do not upload only the ZIP.
Enable Settings → Pages → Deploy from branch → main → /(root).

This is a demo/prototype. Real student accounts, secure data storage, OMR image processing, school subscriptions and multi-school isolation require a backend/database before production use.
