# johnstoniatexts

A clean, static website hosting Ian Johnston's translations of classical works and his
lectures/essays. Designed for easy hosting on **GitHub Pages**.

## About

Ian Johnston is an emeritus professor at Vancouver Island University, Nanaimo, British
Columbia, Canada. This site hosts his translations of **Homer** and **Lucretius**, plus
his extensive collection of lectures and essays on Greek and Roman studies,
Shakespeare, philosophy and political thought, literature, science, religion, and more.

All texts are freely available for educational, artistic, and personal use. Commercial
publishing is also permitted without permission and without charge.

## Contact

For comments or questions please contact **johnstoi.ian@gmail.com**.

## Deploy to GitHub Pages

1. Push this repository to GitHub (already at `b1narybob/ian-johnston-texts`)
2. Go to **Settings → Pages** in the repository
3. Under "Source", select **Deploy from a branch**
4. Choose the `main` branch and `/ (root)` folder
5. Click **Save**

Your site will be live at `https://b1narybob.github.io/ian-johnston-texts/`.

## Structure

```
├── index.html          — home page: intro, translations, lectures & essays, about
├── style.css           — site stylesheet
├── .nojekyll           — disables Jekyll processing on GitHub Pages
├── geoffrey.bmp        — dedication photo
├── pdfs/               — primary translation PDFs (Homer, Lucretius)
│   ├── HOMER_iliadall.pdf
│   ├── HOMER_iliadabridged.pdf
│   ├── HOMER_odysseyall.pdf
│   ├── HOMER_odysseyabridged.pdf
│   └── LUCRETIUS_natureofthings.pdf
└── johnstoniatexts/    — lecture/essay texts mirrored locally (HTML, PDF, RTF)
    └── on_*.html, on_*.pdf, on_*.rtf
```

- **Translations** — PDFs of Johnston's Homer translations (Iliad and Odyssey, complete
  and abridged) and his Lucretius translation (*On the Nature of Things*), plus an RTF
  of his Homer translations. Aeschylus and Aristophanes translation PDFs will be added
  under `pdfs/` as they become available.
- **Lectures & Essays** — ~90 lectures organized by category (Greek & Roman Studies,
  Shakespeare, Philosophy & Political Thought, Literature, Science/Religion/Miscellaneous).
  Most lectures link to the original `johnstoniatexts.x10host.com` pages; where a local
  copy exists it is linked as "(Local HTML / PDF / RTF)" alongside it.
- The site is fully static — no JavaScript dependencies, no build step needed.

## Notes

- Local lecture files in `johnstoniatexts/` are mirrored verbatim from the author's
  Dropbox archive; their contents are not edited.
- Some `johnstoniatexts.x10host.com` links may go offline over time; the local copies
  preserve the most important lectures regardless.
