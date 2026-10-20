# How It Spread

The `howitspread` MCP server holds a sourced record of how things went viral. Use it when a brief, pitch, deck or strategy needs proof that an idea can spread.


Use the `howitspread` MCP tools. Every claim about a case cites its URL.

1. Turn the ask into filters. Call `list_mechanics` once if the mechanic is unclear, then `search_cases` with a short query plus kind, mechanic or platform. Ask for 10; keep the 3 to 5 that fit best.
2. Call `get_case` on the ones you keep. Read the timeline in order: seed, first amplifier, platform jumps, press, peak.
3. Answer with one block per case:
   - **Name** (Spread Score) and the case URL
   - Seed: date, platform, who posted
   - The jump that mattered, with its date
   - Peak date, and days from seed to peak
   - One line on what the brief can borrow
4. End with the pattern the cases share, in one or two sentences.

Rules:
- Timeline events are sourced facts. `hypothesis` and `takeaways` are How It Spread's read; say "their read is" before using them.
- Never invent a number. If a field is locked, say what a free account or Pro adds and link https://howitspread.com/pricing.
- Fewer than 3 good matches: say so and widen one filter, rather than stretching a weak case.
