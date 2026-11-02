<p align="center">
  <img src="./logo.png" alt="Unpoet" width="880">
</p>

<p align="center">
  <a href="SKILL.md"><img alt="version 1.0.0" src="https://img.shields.io/badge/version-1.0.0-1a1613"></a>
</p>

# Unpoet

**Intimate prose with a reason to exist.**

Unpoet is a skill for agents that write or rewrite sentimental, confessional, and elegiac prose. The text keeps the writer's voice, the facts they supplied, and the effect they asked for. Intensity comes from the situation, the detail, and the rhythm.

Use it for letters, farewells, apologies, recollections, unsent messages, and requests for literary elevation, restraint, subtext, or epistolary gravity.

## What it delivers

| Result | What stays on the page |
| --- | --- |
| **One finished piece** | A complete text, in the requested language and length, ready to use when the brief asks for that. |
| **A fitted register** | Everyday confession, solemn epistle, tragic scale, or moral lucidity. The volume changes inside the same piece. |
| **A clear editing contract** | A light correction, a full rewrite, more restraint, more ceremony, or a shorter cut, with the writer's peculiarities intact. |
| **Translation under the same pressure** | A dignified, precise sentence stays dignified and precise in French or Spanish. |
| **Checkable material** | On a real commission, every memory, promise, quotation, and gesture comes from the person who asked. |

## Commissions

- Love letters and unsent messages
- Farewells and reconciliations
- Apologies in which affection and responsibility remain side by side
- Recollections and sentimental fragments
- Requests for a literary, classical, indirect, or physically close tone

## Installation

```bash
npx skills add t5victor/unpoet
```

Without `--global`, the skill stays in the current project. `--agent` selects the target agent.

For a manual install, place this folder on the agent's skill path.

| Agent | Path |
| --- | --- |
| Cursor | `~/.cursor/skills/unpoet` |
| Codex | `~/.codex/skills/unpoet` |
| Agent Skills | `~/.agents/skills/unpoet` |

## Usage

A confession built on one habit:

```text
Write two paragraphs for someone I love. They always left the hall lamp on when they came over. Since they left, I still do it out of habit. No reproach, no grand declaration, and no tidy ending.
```

A solemn letter that can still be read:

```text
Write a solemn letter in formal English about wanting to stop arguing over the past and to acknowledge the harm we did. It should feel as if it could have been written a hundred years ago, and it should be readable without a dictionary. Three paragraphs.
```

A minimal correction:

```text
Correct as little as possible. Keep what is odd in this sentence: "I still find it funny that, of all the things a person can make a fool of himself over, a crooked cup you always picked for coffee was enough for me."
```