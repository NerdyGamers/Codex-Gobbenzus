# AGENTS.md

This repository is the working source for Codex Gobbenzus lore development.
The wiki repository (`Codex-Gobbenzus.wiki`) is the canonical publishing surface.

## Purpose

- Keep Goboid lore consistent, expandable, and easy for future agents/authors to maintain.
- Capture clear writing and workflow standards before adding new lore blocks.
- Ensure visual assets are placed with intent, not randomly scattered.

## Canon Naming Rules

- **Single individual:** `Gob` / `Gob-Gob` / `Gobben`
- **Multiple individuals:** `Gobz` / `Gob-Gobz` / `Gobbenz`
- **Taxonomic terms:** `Goboid` (singular), `Goboidz` (plural)
- **Use `Goboid/Goboidz` for:** headings, taxonomy, lore bible statements, and first factual mention on a page.
- **Use Gob/Gobz variants for:** dialogue, quotes, chants, and culturally biased narration.
- **Never use:** `Goblin`/`Goblins` (fantasy naming is non-canon for this project).
- When editing legacy pages, do not mass-replace flavor text. Prefer incremental normalization.

## Authoring Standards

- Keep tone: grimy, darkly comedic, Orkoid, tactical, and characterful.
- Preserve internal logic: prank warfare is strategic doctrine, not random slapstick.
- Distinguish Goboid identity from Orks/Gretchin with concrete behavior and doctrine differences.
- Add cross-links to at least 2 related pages whenever adding a new lore page.
- Prefer short sections with explicit headers and at least one table for dense facts.

## Workflow (High Level)

1. Define the lore gap (what is missing, why it matters to setting coherence).
2. Draft constraints first (era, clan perspective, reliability of narrator, canon conflicts).
3. Write the page section with one clear thesis.
4. Add links and update index/navigation pages.
5. Add or assign visual assets that reinforce the section's core idea.
6. Perform a consistency pass across terminology and timeline references.

## File/Repo Responsibility

- `Codex-Gobbenzus/`: planning standards, source prompts, asset organization conventions.
- `Codex-Gobbenzus.wiki/`: published lore pages and navigable wiki structure.
- `Codex-Gobbenzus/img/`: canonical hosted image library for wiki embeds.

## Image Hosting Rule

- Wiki pages should not rely on wiki-repo image storage for long-term assets.
- Store images in `img/` in this repository.
- Wiki embeds should use raw URLs:
  `https://raw.githubusercontent.com/NerdyGamers/Codex-Gobbenzus/main/img/<filename>.png`

## Definition of Done for Lore Changes

- Terminology follows naming rules above.
- New/updated lore has no contradiction with existing major pages.
- Navigation updated (usually `Home.md` and at least one related page).
- Visual intention captured (image linked, queued, or explicitly marked as pending).
