# Tasks

Checklist to build the Bible Notes app (React web app: Douay-Rheims Bible on the
left, per-verse notes on the right, plus an Articles section). Published on GitHub
Pages, free to use.

Legend: not started · in progress · done

## Setup
- [ ] Initialize a React app (webpack) in this repo.
- [ ] Add dependencies: React Router (routes), and any styling framework (CSS modules / Tailwind)

## Bible (left side)
- [ ] Build the book selector (list all 74 books with correct filenames)
- [ ] Build the chapter selector (per book)
- [ ] Build the verse selector (per chapter)
- [ ] Load and parse the selected verse(s) from the Douay-Rheims JSON
- [ ] Render the verse text on the left pane

## Notes (right side)
- [ ] Create the notes (html) template with these sections:
  - Prophesy
  - Symbols/cultural (may contain images)
  - People/places
  - Archeology (may contain images and data tables)
  - References
- [ ] Wire the right pane to show a chapter's notes file for the selected verse
- [ ] Make each verse clickable so selecting a verse shows its notes

## Articles section
- [ ] Build an Articles page/route listing articles for: prophesy, symbols/cultural, people/places, archeology
- [ ] Each article: full scholarly info + list of all verses mentioning the topic + References section at the bottom
- [ ] Article pages link to supporting evidence (Wikipedia, scholarly sources)

## Content (the real work)
- [ ] Write the first chapter's notes (Prophesy / Symbols / People & places / Archeology / References)
- [ ] Start the article set (one per topic type), each with sources and a verse-list
- [ ] Keep all content Catholic and aligned with the Catechism of the Catholic Church; prefer official church documents/teachings
- [ ] Keep notes/articles short, easy to read, no filler; every item relevant to the topic

## Publish
- [ ] Configure the GitHub Pages deployment (repo/pages main branch → `docs` or `root`)
- [ ] Deploy and verify the live site

---
Notes:
- The Douay-Rheims uses Spanish Catholic book titles (Isaias, Ezechiel, Sophonias, etc.).
  Decide whether to keep source names or rename to English canonical names.
- Priority content: Prophesy is the most important notes section.
