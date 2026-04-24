# Cron examples

Use cron when the schedule is known and persistent observation is unnecessary.

Examples:
- Daily log at 5:00 PM local time
- Weekly hype doc every Friday at 4:30 PM local time

Prompt guidance for recurring jobs:
- the daily job should only use notes from today
- the weekly job should only use notes from the current calendar week
- both jobs should tolerate gaps and summarize only the available evidence
- neither job should invent missing activity to make the output feel complete

The artifact is the important part; cron is the delivery mechanism.
