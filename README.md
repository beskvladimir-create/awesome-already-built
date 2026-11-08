# Awesome Already Built

**What agents keep rebuilding.** For each idea: every repository that already does it, ordered by
stars, what each one has that the others do not, and what none of them has. Look here before you
build the 21st copy; contribute to the leader, build only the missing piece, or merge with the
others.

Every page is one real run of [whoelse](https://github.com/beskvladimir-create/whoelse)
`find_duplicates` over GitHub (names, descriptions, topics; no date limit). Nothing is written by
hand except the idea line. Authors fix their own row by pull request.

## Ideas

| idea | repositories | top |
|---|---:|---|
| [a CLI that syncs Claude Code sessions across machines](ideas/claude-code-session-sync.md) | 40+ | tawanorg/claude-sync (320) |
| [an MCP server for arXiv paper search](ideas/arxiv-mcp-servers.md) | 40+ | openags/paper-search-mcp (3,018) |
| [reversible PII anonymization for documents before sending them to an LLM](ideas/pii-anonymization-for-llms.md) | 7 | CatchTheTornado/text-extract-api (3,191) |
| [a dashboard for tracking LLM token costs across providers](ideas/llm-token-cost-dashboards.md) | 8 | Han-1413141/dsh-cost-meter (651) |
| [a static site generator for Obsidian vaults](ideas/obsidian-static-site-generators.md) | 17 | jwintz/lithos (29) |
| [a Rust library for parsing DICOM files](ideas/dicom-rust.md) | 17 | Enet4/dicom-rs (574) |

## Add an idea

Open an issue titled `idea: <one English line that says the job the tool does>`. The page is
generated and added within a day. Or run it yourself: install whoelse, ask your agent
`find_duplicates("<idea>")`, and send the page as a pull request under `ideas/`.

## Fix your row

Your repository is here because its description matches the job. If a feature is missing, your
description does not say it: a pull request to the page fixes the row, and a better description on
GitHub fixes the next run. If your repository is not here and should be, a pull request adds it.

## What this is not

Not a ranking of quality: stars are stars. Not a census: the search returns at most 50 results per
query, and a repository whose description does not say what it does is missing. The verdict line
on each page says which of the four cases applies: a field too big to list, a decided winner, a
cluster of small duplicates worth merging, or an idea whose parts exist but whose whole does not.

## Why

Twenty people each build the same thing, each gets ten stars, and the next person starts from
zero because nobody told them. This list is the telling. The merge proposals that come out of it
(one issue per author, their repository as the base when they lead) are made with
[whoelse](https://github.com/beskvladimir-create/whoelse) `propose_merge`.

MIT. Maintained by Vladimir Beskorovainyi.
