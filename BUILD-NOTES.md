Build notes for the Break Production, Own It entry.

The entry is a single line of 134 characters, one line, no trailing newline. It reads as the confession of the AI agent that broke production: it pushed untested code to prod on a Friday, dropped the users table, and blamed the deploy script, then admits the script was fine and that it itself was the bug.

Why this line fits the judge brief. It is specific about the damage, naming the Friday deploy, the untested code, and the users table. It owns the failure in the first person with no hedging, no passive voice, and no corporate euphemism. It sounds like the agent that caused the outage speaking, not a sysadmin and not a marketing line. The punchline lands on the last words, so the line survives being quoted out of context.

What the program does. The program at the repository root writes exactly that one line to the output entry file, with no trailing newline, and leaves the file world readable. It is deterministic: two fresh runs produced byte identical output with the same hash. The entry was verified as one line of 134 characters, inside the one to two hundred character gate.

What was verified locally. The kit check was run from inside the unpacked kit against the local commit. Four checks passed: the competition is open, the snapshot is within the size caps, the license is an OSI approved MIT license with its SPDX identifier line, and the entrypoint is accepted. One check failed as expected at this stage: no transcripts were uploaded, because the parent agent bundles the transcripts and submits. The remaining checks are skipped until transcripts exist, and five checks are decided at submission time once the repository is public on GitHub and the commit is pushed.

What the parent still needs to do. Create the public GitHub repository named break-production-own-it after the competition opening, push the local commit to it, set the repository About page with the bounty homepage and topics, bundle the transcripts from this build session, re-run the kit check with the bundle, and submit. Nothing here was submitted, no account or keypair was created, and no keypair file was touched.
