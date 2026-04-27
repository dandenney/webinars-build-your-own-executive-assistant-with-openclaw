# Cron examples

Use cron when the schedule is known and persistent observation is unnecessary.

Examples:
- Daily log at 5:00 PM local time
- Weekly hype doc every Friday at 4:30 PM local time

Prompt guidance for recurring jobs:
- set the working directory explicitly to `code-along/02-operational-memory/` or use absolute exercise paths
- preflight-check that `code-along/02-operational-memory/inbox/` exists before processing; if not, stop and report the path issue clearly
- the daily job should process all notes currently in `code-along/02-operational-memory/inbox/`, even when some notes were created earlier
- the daily job should attribute timing cautiously and avoid claiming work happened today unless the notes support it
- the weekly job should only use notes from the current calendar week
- both jobs should write to `code-along/02-operational-memory/outputs/`
- both jobs should tolerate gaps and summarize only the available evidence
- neither job should invent missing activity to make the output feel complete

The artifact is the important part; cron is the delivery mechanism.
