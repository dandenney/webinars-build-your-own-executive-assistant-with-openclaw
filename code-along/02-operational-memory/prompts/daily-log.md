Work in `code-along/02-operational-memory/`.

Preflight:
- verify `code-along/02-operational-memory/inbox/` exists before processing
- write output to `code-along/02-operational-memory/outputs/`
- if the expected `inbox/` directory is missing, stop and report the path issue clearly instead of guessing

Review all notes currently in `code-along/02-operational-memory/inbox/` and generate today's operational memory log in markdown in `code-along/02-operational-memory/outputs/`.

Processing rules:
- process all notes currently in `code-along/02-operational-memory/inbox/`, even if the note itself was written on an earlier date
- use filenames as date/context signals when helpful, but do not exclude a note only because its filename is older than today
- use file contents to determine what work, decisions, blockers, or next steps are supported by the notes
- if a note explicitly references earlier work, include that context only when supported by the note
- be explicit when coverage is partial or timing is ambiguous

Focus on:
- progress
- blockers
- notable decisions
- likely next steps

Constraints:
- keep it concise and grounded
- make it useful to a manager or teammate
- cite filenames when helpful
- do not invent work that is not supported by the files
- do not claim that work happened today unless the files support that timing
- if inbox is empty, state briefly that no entries were available to process
- if the notes are sparse or undated, summarize only the available evidence and note that timing/coverage is partial

Output requirements:
- create `code-along/02-operational-memory/outputs/` if it does not exist
- write the file as `code-along/02-operational-memory/outputs/YYYY-MM-DD-operational-memory-log.md`
- overwrite that day's file if it already exists
- do not modify source files in `code-along/02-operational-memory/inbox/`
