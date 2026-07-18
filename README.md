# SlopSift agent skill

[![skills.sh](https://skills.sh/b/NikhilVerma/slopsift)](https://skills.sh/NikhilVerma/slopsift)

An installable agent skill for reviewing prose with the [SlopSift](https://slopsift.dev) CLI.

## Install

```bash
npx skills add NikhilVerma/slopsift --skill slopsift
```

The skills CLI detects supported coding agents and installs the `slopsift` skill for the selected environment.

## What it does

The skill instructs an agent to:

- use the repository's existing Bun or Node environment;
- run the real SlopSift parser and deterministic rules;
- inspect exact findings before editing;
- prioritize errors and warnings over low-confidence signals;
- preserve the writer's meaning and voice; and
- treat findings as writing signals, not proof of authorship.

The [WritingLint repository](https://github.com/NikhilVerma/writinglint) contains SlopSift's CLI and parser. This repository contains only the portable agent skill.

## License

MIT
