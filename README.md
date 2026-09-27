# annaafrench.com

Personal academic website of Anna French. Plain HTML/CSS, hosted on GitHub Pages.

## Files

| File | What it is |
|---|---|
| `index.html` | Home page (photo, bio, fields, education, JMP) |
| `research.html` | Papers and abstracts |
| `teaching.html` | Teaching |
| `assets/style.css` | All colors, fonts, spacing (colors are at the top) |
| `assets/anna-french.jpg` | Photo (square, 800×800) |
| `files/` | PDFs: CV, papers |
| `CNAME` | Custom domain — don't delete |

## Common updates (all doable in the GitHub website)

**Update the CV:** open the `files` folder → *Add file → Upload files* → upload the new PDF with the
**same name** `CV_Anna_French.pdf` → *Commit changes*. Links everywhere keep working.

**Post a paper:** upload the PDF to `files/` (e.g. `French_JMP.pdf`). Then open `index.html` and
`research.html`, click the pencil icon, find the line `<!-- <a class="btn" href="files/French_JMP.pdf">Paper (PDF)</a> -->`,
delete `<!--` and `-->` at its ends, and *Commit changes*.

**Edit text:** open the page → pencil icon → change the words between the tags → *Commit changes*.
The site updates in about a minute.

**Change the photo:** upload a new square photo named `anna-french.jpg` into `assets/` (it replaces the old one).
