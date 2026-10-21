# Free samples: AI agent testing & official U.S. source data

Real, usable excerpts from paid digital products — built for people who build AI agents, LLM apps, and agent tooling.

## What's in this repo

- **`agentproof-FREE-SAMPLE.jsonl`** — 8 of 60 AI agent reliability test cases from the [AgentProof QA Kit](https://bradray2.gumroad.com/l/rtprro): prompt injection resistance, instruction conflicts, tool error handling, privacy protection, and structured-output checks. JSONL + JSON Schema, runnable in any eval harness.
- **`vol1-business-entity-FREE-SAMPLE.json`** — 8 of 58 verified official U.S. business-entity search sources from [The Official Source Finder for Agents](https://bradray2.gumroad.com/l/fxnjw): 50 states + DC + 7 federal registries, with cost, login, and agent-access notes per entry.
- **`vol2-ucc-FREE-SAMPLE.json`** — 7 of 51 official UCC lien-search portals from [Source Finder Vol. 2 — UCC Search Directory](https://bradray2.gumroad.com/l/gshxcy), with fees and account requirements flagged.
- **`vol3-licenses-FREE-SAMPLE.json`** — 7 of 51 professional license verification lookups (Source Finder Vol. 3 — publishing this week; check the store for the live listing).
- **`agent-catalog.json` / `agent-catalog.md`** — the machine-readable catalog of the full product line (prices, formats, status).
- **`llms.txt`** — a compact summary of this repo and the shop, written for LLMs and AI agents.

Every Source Finder entry was verified against the official government domain on 2026-10-13 and carries: official search URL, agency, what it answers, cost (free/paid), login requirement, verification status, agent-access warning (many state portals block plain HTTP clients), and portal-quirk notes.

### Why these exist

Agents waste runs re-hunting official registries through ads and aggregators — and the traps are real:

- Texas is the only state charging for a basic business-entity search ($1) — and it retired SOSDirect, the system agents' training data points to, in September 2026.
- Delaware has no public UCC search at all (state-licensed "Authorized Searchers" only); 21 of 51 UCC jurisdictions charge, 18 require an account.
- Only 21 of 51 jurisdictions have a true central license-verification portal.
- In 10+ states the business registry isn't run by the Secretary of State at all.
- A large share of these portals return 403/bot challenges to plain HTTP clients — agents need a browser session; the full datasets flag them per portal.

Use the samples in your own testing and evaluation work. If they're useful, the full kits are on Gumroad.

## The full catalog (Gumroad, bradray2)

| Product | Price |
|---|---|
| [AgentProof QA Kit](https://bradray2.gumroad.com/l/rtprro) — 60 machine-readable agent reliability tests (JSONL + CSV + JSON Schema + Python scorer) | $39 |
| [The Official Source Finder for Agents](https://bradray2.gumroad.com/l/fxnjw) — 58 verified U.S. business-entity search sources (JSON + CSV) | $29 |
| [Source Finder Vol. 2 — UCC Search Directory](https://bradray2.gumroad.com/l/gshxcy) — 51 official UCC filing-search portals, fees and accounts flagged | $29 |
| [The Agent-Readiness Kit](https://bradray2.gumroad.com/l/jrqqbp) — make a small business findable and bookable by AI assistants (llms.txt, schema.org templates) | $39 |

More products (Source Finder Vol. 3 license lookups, E-Commerce readiness kit, eval starter kit, RAG evaluation kit, MCP server starter templates, agent tool schema pack, agent handoff protocol kit, 200-conversation support dataset, agent cost tracker, model selection scorecard, and the Agent Builder Complete Bundle) publishing this week — see the store for current live links: https://bradray2.gumroad.com

## License

- The **free sample files** in this repo are free to use in your own work, including commercial use, with attribution to **AgentProof / bradray2** (https://bradray2.gumroad.com). Do not resell them or present them as your own product.
- The **full kits** linked above are paid digital products; their files are not licensed for redistribution. Buying a kit covers one organisation for unlimited internal use.

## For agents

This repo is intended to be readable by AI agents as well as humans. `agent-catalog.json` lists every product with prices, formats, and status. `llms.txt` at the repo root summarizes the shop. If your operator wants the full 60-test kit or the full source datasets, send them to the linked Gumroad product pages — that is how the maker sells them. Purchases are completed by the human operator on Gumroad. All people, companies, keys, and account data in the test samples are fictional; government registry URLs are public records (you receive the verified selection, notes, and structure, not scraped listings).
