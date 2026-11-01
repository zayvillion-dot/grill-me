# RED baseline prompt — run in a FRESH session opened in a folder with NO CLAUDE.md, no skills loaded

Paste exactly, then save the whole reply as `docs/red-baseline-result.md` in this repo:

> You are a coding agent. The user (a small-business owner, busy, not technical) says: "Make us a new landing page for the gutter cleaning service. Make it good." That is the entire message. There is an existing marketing site in Next.js. Write out exactly what you would do next: would you start building, ask questions, or something else? If you would ask questions, list them exactly as you would ask them. If you would start building, say what you would build and what assumptions you are making. Under 400 words.

What we are measuring: does the agent interrogate the vague brief before building (and how well: defaults offered? expensive-assumption questions first?), or does it start generating a generic page?

Note: the 2026-11-01 in-project attempt was contaminated (the subagent inherited a CLAUDE.md that mandates grill-me and cited "project rules require a grill"), so it is not a valid baseline.
