# Drishti Kejriwal: portfolio

A beach-themed product design portfolio. One static file, no build step.

## Run locally
Open `index.html` in a browser, or run `npx serve .`

## Deploy to Vercel
1. Push this folder to a GitHub repo.
2. On vercel.com choose **Add New, Project**, import the repo.
3. Framework preset: **Other**. Leave build command and output directory empty. Click **Deploy**.

## Things still to fill in
Search `index.html` for these placeholders:
- `LINKS={li:...,cv:''}` in the contact script: add the resume URL (put `resume.pdf` in this folder and use `'/resume.pdf'`).
- Boats 01 and 02 open their case studies inside the page. Each one has the original PDF plus page images in `case-studies/<name>/1.jpg, 2.jpg...` (made from the PDF, 90 dpi, sliced). To add another, export the PDF the same way and add `pages`, `count` and `pdf` to its entry in the `BOATS` array. Boats 03 to 05 still say a case study is on its way.
- Nav links for Work and About (sections not built yet).
