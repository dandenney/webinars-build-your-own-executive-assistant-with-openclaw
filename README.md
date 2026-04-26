# OpenClaw Local-Only Code-Along

This repo is a small workshop for practicing local-first OpenClaw workflows.

The workshop flow is:

1. **Data intake review**
2. **Operational memory**
3. **Offline communications triage**

Everything stays in local folders and produces reviewable markdown artifacts.

## Main walkthrough

The HTML walkthrough for the session is:

- `webinar-runbook.html`

## Repo structure

```text
.
├── webinar-runbook.html
└── code-along/
    ├── INDEX.md
    ├── 01-data-intake-review/
    ├── 02-operational-memory/
    ├── 03-offline-communications-triage/
    └── mission-control/
```

## Exercises

### 1) `code-along/01-data-intake-review/`
Turn unknown files into a trustworthy intake report.

- `incoming/` — starter files to inspect
- `prompts/intake-review.md` — instructions for generating the report
- `outputs/` — generated markdown output
- `expected/report-outline.md` — expected shape of the report

Expected artifact:

- `outputs/intake-review.md`

### 2) `code-along/02-operational-memory/`
Turn work residue into daily and weekly momentum docs.

- `inbox/` — starter notes and work residue
- `prompts/daily-log.md` — daily log prompt
- `prompts/weekly-hype.md` — weekly summary prompt
- `outputs/` — generated markdown output
- `schedule/cron-examples.md` — cron examples for the walkthrough
- `schedule/heartbeat-note.md` — heartbeat guidance for the walkthrough

Expected artifacts:

- `outputs/daily-log.md`
- `outputs/weekly-hype.md`

This exercise also includes a cron example as part of the standard workshop flow.

### 3) `code-along/03-offline-communications-triage/`
Turn exported mail into an action list.

- `eml/` — starter exported email files
- `prompts/email-triage.md` — triage prompt
- `outputs/` — generated markdown output
- `expected/report-outline.md` — expected shape of the report

Expected artifact:

- `outputs/email-triage.md`

### Optional: `code-along/mission-control/`
Reserved for a simple dashboard or extension page that links to the generated artifacts.

## Workshop characteristics

- Local files only
- No live integrations
- Copy/paste prompts
- Markdown outputs

## Practice-run notes

If you are following the workshop manually:

- open `webinar-runbook.html`
- keep the `code-along/` folder visible
- run prompts against the exercise folders one at a time

If a different file named `walkthrough.html` is referenced anywhere else, that is not the current walkthrough file in this repo.
