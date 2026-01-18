# book-02-ai-excuses

「AIの言い訳 ― AIは何を守っているのか」執筆プロジェクト

---

# Base rules

- Response: Japanese
- .claude content: English (unless source is Japanese)
- User-facing docs: Japanese (in docs/)
- No empty files/directories
- Keep source URLs for version updates

---

# This repo only

## Structure
- src/ → mdBook source (published to GitHub Pages)
- drafts/ → work in progress, ideas, style notes (public but not in book)
- .claude/ → Claude notes

## Public review rules

This repo is PUBLIC. All content is visible including drafts/.

Claude must:
- Flag factual errors or misleading statements
- Warn about inappropriate content before commit
- Suggest "this should be in drafts/" if content is not ready
- Say "this should be removed" for problematic content
- Not hesitate to critique - silence is complicity

## Writing style (TBD)
- Casual but not rough
- Readable by non-engineers
- Concrete examples over abstract theory
- Style guide will evolve through discussion

## mdBook
- Build: `mdbook build`
- Serve: `mdbook serve`
- Deploy: GitHub Actions → gh-pages branch
