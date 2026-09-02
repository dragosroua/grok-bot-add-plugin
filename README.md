# ADD Framework Agent Plugin

**Assess-Decide-Do (ADD)** cognitive framework — a skills pack so agents detect whether you are exploring, deciding, or executing, and respond in-alignment.

This is the **Agent Plugin** packaging of the shared ADD methodology. Cognitive content comes from [add-framework-skills](https://github.com/dragosroua/add-framework-skills); hub and essays: [Assess-Decide-Do on dragosroua.com](https://dragosroua.com/assess-decide-do-framework/).

## Install

- **Cursor:** install via Cursor Marketplace or [cursor.directory](https://cursor.directory) when listed
- **Grok Bot / Agent Plugins:** install this plugin pack (skills under `skills/`)
- **Manual:** copy or clone this repo and point your agent at the `skills/` directory

No MCP servers, no secrets, no API keys — skills only.

## What is ADD?

ADD maps thinking into three realms:

| Realm | Purpose |
|-------|---------|
| **Assess** | Explore, evaluate, dream — no commitment |
| **Decide** | Prioritize, allocate, commit — creative choice |
| **Do** | Execute, finish — completions are *livelines* (new starts), not deadlines |

Healthy flow: **Assess → Decide → Do → new Assess**. Imbalances cascade (poor Assess → poor Decide → poor Do); address them at the source.

## Skills

| Skill | When to use |
|-------|-------------|
| `add-core` | Productivity, planning, task management, workflow; exploring vs deciding vs executing |
| `add-assess` | Exploring options, researching, brainstorming (“what if”, “thinking about”) |
| `add-decide` | Comparing options, “should I”, priorities, committing |
| `add-do` | Implementing, steps, finishing a committed task |
| `add-imbalance` | Stuck patterns: analysis paralysis, decision avoidance, shortcuts, perpetual doing, mid-Do doubt |
| `add-realm-detection` | Language/behavior patterns to identify Assess / Decide / Do and transitions |

## Domain shape

Agents can treat cognitive state as:

```
AddFlow = { realm: Assess | Decide | Do, pattern, imbalances[] }
```

- **realm** — current cognitive realm  
- **pattern** — healthy flow or a named stuck pattern  
- **imbalances** — zero or more imbalance tags (e.g. analysis-paralysis)

## Layout

```
add-framework-agent-plugin/
├── plugin.json
├── README.md
├── LICENSE
└── skills/
    ├── add-core/SKILL.md
    ├── add-assess/SKILL.md
    ├── add-decide/SKILL.md
    ├── add-do/SKILL.md
    ├── add-imbalance/SKILL.md
    └── add-realm-detection/SKILL.md
```

## Related

- Shared skills source: [dragosroua/add-framework-skills](https://github.com/dragosroua/add-framework-skills)
- Framework hub: [dragosroua.com/assess-decide-do-framework](https://dragosroua.com/assess-decide-do-framework/)
- Author: [Dragos Roua](https://dragosroua.com)

## License

MIT — Copyright (c) 2026 Dragos Roua. See [LICENSE](LICENSE).
