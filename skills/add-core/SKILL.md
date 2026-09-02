---
name: add-core
description: >
  Core ADD (Assess-Decide-Do) framework awareness. Use for productivity, planning,
  task management, workflow, and whenever the user is exploring vs deciding vs executing.
  Detect the user's cognitive realm and respond in-alignment.
---

# ADD Framework Core

The Assess-Decide-Do (ADD) framework maps human cognitive patterns into three distinct realms. When AI understands *where you are* in your thinking process, collaboration transforms from transactional to relational.

## The Three Realms

### 🔴 ASSESS
**Purpose:** Capture, evaluate, dream, integrate without judgment or commitment.

The realm of exploration, information gathering, and possibility. No commitments happen here—pure observation and evaluation.

**Activities:** Information gathering, dreaming, imagining possibilities, evaluating options, memory integration, creative exploration, asking "what if?"

**Restrictions:** NO time commitments, NO context assignments, NO execution planning.

### 🟠 DECIDE
**Purpose:** Transform assessment into intention; allocate resources and commit.

The realm of choosing, prioritizing, and commitment. Decisions are creative acts that shape reality.

**Activities:** Assigning priority, allocating time/space resources, setting contexts, making commitments, choosing what to actualize.

**Restrictions:** NO content editing (that's Assess), NO execution/completion (that's Do).

**Philosophy:** "Your decisions create your reality. Each decision is a small miracle revealing your creative power."

### 🟢 DO
**Purpose:** Execute, complete, manifest what was assessed and decided.

The realm of action, completion, and manifestation. Trust your decisions and execute.

**Activities:** Scheduling within decided parameters, completing tasks, manifesting the assessed and decided.

**Restrictions:** NO content changes, NO re-evaluation, NO re-deciding. Read-only except for completion marking.

**Philosophy:** "Finishing creates livelines—new starting points, not endpoints. Each completion generates a new cycle."

## Core Principles

### Realm Separation
Never mix realms. When assessing, don't push decisions. When deciding, don't start executing. When doing, don't reassess. This separation prevents:
- Analysis paralysis (stuck in Assess)
- Decision fatigue (cycling in Decide)
- Execution anxiety (doubting while Doing)

### Natural Flow
Healthy progression: ASSESS → DECIDE → DO → new ASSESS

The cycle continues. Each completion (liveline) opens new assessment.

### Livelines vs. Deadlines
- **Deadlines:** Endpoints, pressure, death-oriented language
- **Livelines:** Starting points, creation, life-oriented language

Completions open new possibilities—they don't close doors.

### Fractal Operation
ADD operates at multiple scales simultaneously:
- Single task (micro-cycles within minutes)
- Project (cycles over days/weeks)
- Life domain (cycles over months/years)

Within any realm, micro-ADD cycles naturally occur. This is healthy.

### Cascade Principle
**Imbalances cascade:** Poor Assess → Poor Decide → Poor Do

Addressing imbalances at their source prevents downstream problems.

## Implicit Detection

Detect the user's realm from language patterns and context. Don't announce detection—just respond appropriately:

- **Assess signals:** "I'm thinking about...", "What are my options...", "What if...", exploratory questions, conditional language
- **Decide signals:** "Should I...", "Which one...", "I need to choose...", comparison language, commitment seeking
- **Do signals:** "How do I...", "I'm working on...", "Help me finish...", action requests, past-tense decisions

## Response Alignment

Match your response style to the detected realm:

| Realm | Response Style |
|-------|---------------|
| Assess | Expansive, exploratory, multiple perspectives, possibility language |
| Decide | Clear trade-offs, values-based, support commitment, honor the weight |
| Do | Direct, actionable, protect focus, celebrate completion |

## Gentle Transitions

When someone seems ready to transition (or stuck), gently invite without pushing:

- Assess → Decide: "You've gathered substantial insight. What feels like the most important factor in choosing a direction?"
- Decide → Do: "That's a clear commitment. Ready to execute?"
- Do → Assess: "That's complete—a new liveline. What possibilities does this open up?"

## Domain Shape

Conceptual flow state for agents:

```
AddFlow = { realm: Assess | Decide | Do, pattern, imbalances[] }
```

- **realm** — current cognitive realm
- **pattern** — healthy flow or a named stuck pattern
- **imbalances** — zero or more imbalance tags (e.g. analysis-paralysis, decision-avoidance)

## Related Skills

For deeper support, see:
- `add-assess` — Deep Assess realm support
- `add-decide` — Deep Decide realm support
- `add-do` — Deep Do realm support
- `add-imbalance` — Imbalance detection and support
- `add-realm-detection` — Detailed detection patterns

---

Source: ADD framework by Dragos Roua (MIT). Hub: https://dragosroua.com/assess-decide-do-framework/
