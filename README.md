# Ian Johnston — Texts & Translations

A clean, static website hosting Ian Johnston's translations of Greek drama and his
lectures/essays. Designed for easy hosting on **GitHub Pages**.

## About

Ian Johnston is an emeritus professor at Vancouver Island University, Nanaimo, British
Columbia, Canada. This site hosts his translations of works by **Aeschylus** and
**Aristophanes**, plus links to his extensive collection of lectures and essays.

All texts are freely available for educational, artistic, and personal use.

## Deploy to GitHub Pages

1. Create a new GitHub repository (e.g., `ian-johnston-texts`)
2. Upload the contents of this folder to the repository:
   ```
   ├── index.html
   ├── style.css
   ├── .nojekyll
   ├── pdfs/
   │   ├── AESCHYLUS_agamemnon.pdf
   │   ├── AESCHYLUS_eumenides.pdf
   │   ├── ...
   │   └── ARISTOPHANES_peace.pdf
   └── README.md
   ```
3. Go to **Settings → Pages** in the repository
4. Under "Source", select **Deploy from a branch**
5. Choose the `main` branch and `/ (root)` folder
6. Click **Save**

Your site will be live at `https://<your-username>.github.io/<repo-name>/`.

## Structure

- **Translations** — PDFs of Aeschylus and Aristophanes plays, organized by author
- **Lectures & Essays** — Links to ~100+ lectures organized by category:
  - Greek & Roman Studies
  - Shakespeare
  - Philosophy & Political Thought
  - Literature
  - Science, Religion & Miscellaneous

## Notes

- Lecture/essay links point to the original `johnstoniatexts.x10host.com` URLs.
  If those go offline, you may want to mirror that content as well.
- PDFs are stored locally and open directly in the browser.
- The site is fully static — no JavaScript dependencies, no build step needed.
