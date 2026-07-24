# Repository Guidelines

## Project Structure & Module Organization
- Root contains topic files: `README.md` (overview), `FLOSS_Tools*.md` (software), `Projects*.md` (build ideas), `RFParts*.md` (components), and geography-specific equipment lists (`en_in.md`, `tr-tr.md`, etc.).
- Language or region variants live alongside their originals; keep translations in separate `*_tr.md` or `xx-yy.md` files to match existing patterns.
- No build artifacts or compiled assets are tracked; all content is Markdown.

## Build, Test, and Development Commands
- Content is plain Markdown; no build step is required.
- Optional lint (if you have it installed): `markdownlint **/*.md` to catch formatting issues; fix warnings locally before sending changes.
- Use `git status` to confirm only intentional files are staged.

## Coding Style & Naming Conventions
- Write in clear, concise English unless creating a localized file; keep tone instructional and fact-based.
- Use Markdown headings for structure, bullet lists for equipment/projects, and reference links where helpful.
- Follow existing naming: lowercase filenames; suffix translations with language/region codes mirroring `en_in.md` or `tr-tr.md`.
- Prefer short paragraphs; avoid ASCII art or embedded binaries.

## Testing Guidelines
- There are no automated tests; manual review is expected.
- Before opening a PR, skim rendered Markdown to verify headings, lists, and links display correctly (e.g., via GitHub preview).
- Keep examples actionable (prices, models, or commands) and cite sources where possible.

## Commit & Pull Request Guidelines
- Commit messages observed here are short and imperative (e.g., “Update README.md”); mirror that style.
- Keep commits scoped to one topic or file set (e.g., only `Projects*.md` for project additions).
- PRs should include: a concise summary of changes, affected files, rationale (why the addition/change matters), and links or screenshots if formatting is non-obvious.

## Localization & Content Additions
- When adding a new geography, copy the closest existing file as a starting point and adjust currency, availability, and sourcing notes.
- Maintain neutrality: note when prices/availability are approximate and date-sensitive.
- If introducing new sections, add them to both the primary language file and any maintained translations, or open a follow-up task to track translation parity.
