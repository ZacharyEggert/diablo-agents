# diablo-agents

Claude Code skills for Diablo Guitars.

## Install

```sh
npx skills install ZacharyEggert/diablo-agents
```

Or symlink for local development:

```sh
ln -s "$PWD/skills/amp-listing" ~/.claude/skills/amp-listing
```

## Skills

| Skill | Invoke | What it does |
| --- | --- | --- |
| `amp-listing` | `/amp-listing [amp details]` | Researches a guitar amp, confirms specifics with you, emits a sales listing in the shop's standard format. |

Examples of finished output live in `skills/amp-listing/examples/listings.md`.
