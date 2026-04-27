Work in `code-along/02-operational-memory/`.

Preflight:
- verify `code-along/02-operational-memory/inbox/` exists before processing
- write output to `code-along/02-operational-memory/outputs/`
- if the expected `inbox/` directory is missing, stop and report the path issue clearly instead of guessing

Review the notes in `code-along/02-operational-memory/inbox/` and generate a weekly hype doc in markdown in `code-along/02-operational-memory/outputs/`.

Time window:
- use only notes from the current calendar week
- use filenames first to determine which notes belong to the current week
- use file contents as a secondary signal if needed
- ignore older notes unless a note from the current week explicitly references them

Include:
- wins
- momentum
- notable changes
- risks
- blockers
- next bets

Constraints:
- keep the tone crisp and upbeat
- stay evidence-based
- do not exaggerate impact
- if notes exist for only part of the week, summarize only the available evidence and briefly note that coverage is partial
- do not invent missing daily activity or unsupported progress

Output requirements:
- create `code-along/02-operational-memory/outputs/` if it does not exist
- write the file as `code-along/02-operational-memory/outputs/YYYY-MM-DD-weekly-hype-doc.md`
- overwrite that week's file if it already exists
- do not modify source files in `code-along/02-operational-memory/inbox/`
