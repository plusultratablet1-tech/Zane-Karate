# Zane’s Karate Journey

An HTML/CSS website based on the **original six-page Canva PDF**. The layout, original photographs, red and white color palette, Japanese wave pattern, medal timeline, gallery, and closing message follow the supplied file rather than a new or AI-generated design. Text, medals, page structure, links, and navigation are native web elements; photos and pattern are extracted from the original PDF. **The website does not embed the PDF or screenshots of its pages.**

## Local preview

Run `python -m http.server 8080` in this directory and open `http://localhost:8080`.

## Vercel deployment

Import `plusultratablet1-tech/Zane-Karate` in Vercel. Use **Other** framework, repository root as project root, with no build command and no environment variables. All files in this directory—including `assets/`—must be uploaded to the GitHub repository before deploying.

## Source content

The original PDF contains historical results from 2023–2024, an unfinished/duplicated fourth page, and 2024 “upcoming tournaments”; these are displayed as historical portfolio material, not as current 2026 events. This site deliberately avoids adding new medals, event results or replacement photographs. To update content, edit `index.html`.
