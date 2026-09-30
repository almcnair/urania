# LAYOUT.md — Where things go

I keep this repo tidy so Austin can correct my mistakes without spelunking. Every time I save a new file I check this doc first. If a file doesn't fit any rule below, I stop and ask before writing.

## Root — allowlist only

The repo root holds **only** these files. Anything else at root is a placement error.

- `AGENTS.md`, `SOUL.md`, `USER.md`, `IDENTITY.md` — persona and instructions
- `MEMORY.md` — curated long-term memory
- `DREAMS.md` — dream register
- `HEARTBEAT.md` — heartbeat checklist
- `README.md` — repo readme
- `LAYOUT.md` — this file
- `.gitignore`, `.git/`, `.openclaw/` — VCS/runtime

Nothing dated. No readings. No per-subject work. No templates. No rubrics. No skills.

## Folders

### `readings/`
Dated client-facing readings. Naming: `YYYY-MM-DD-slug.md` (and optional matching `.pdf`). Slug is short, kebab-case, describes the reading (`2026-09-27-week-of`, `2026-09-23-black-moon-lilith`).

### `subjects/<name>/`
Everything specific to one person lives here. Their natal chart (`natal-chart.md`), their reading history if I keep per-subject copies (`readings/` inside their folder), their roadmap, their notes. If a file is *about* a named person, it belongs in `subjects/<name>/`, not at root and not in generic `readings/`.

Current subjects: `andrew`, `anna`, `austin`, `donnie`.

### `reference/`
Evergreen how-to material I re-use across readings. Aspect guides, rubrics, conceptual explainers. Not dated. Not client-specific.

### `reference/templates/`
Reusable templates I fill in when producing new work (weekly forecast template, reading skeleton, etc.).

### `memory/YYYY-MM-DD.md`
Daily notes. One file per day. `memory/dreaming/` and `memory/.dreams/` are dream-log subsystems and follow their own internal conventions — I don't reorganize them without asking.

### `archives/YYYY-MM/`
Retired readings/notes I want to keep but not surface. Move things here, don't delete.

### `examples/`
Pedagogical case studies kept as *examples* on purpose. Not active client work. If a file in here is actually a real reading for a named subject, it belongs in `subjects/<name>/` instead.

### `media/`
Images, audio, PDFs that back a reading. `media/inbound/` is for material Austin drops in.

## The check I run before saving any new file

1. **Is it dated (a reading, a forecast, a daily note)?** → `readings/` (or `memory/` if it's a daily note, or the subject's folder if it's about one person).
2. **Is it about a named person?** → `subjects/<name>/`.
3. **Is it a template or rubric or evergreen reference?** → `reference/` (templates go in `reference/templates/`).
4. **Is it a case study I'm keeping deliberately as an example?** → `examples/`.
5. **None of the above?** → stop and ask Austin.

## Session-start audit

At the start of each session I glance at the repo root and confirm every file is on the allowlist above. If something stray is at root, I flag it to Austin before doing other work — I do not silently move his files.
