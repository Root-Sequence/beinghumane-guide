# Being Human(e)

> **To be human is unfinished; to be humane is to keep choosing care.**

**Being Human(e)** is a practical, evolving field guide built from observation, experience, uncertainty, and the repeated work of relating to other people without pretending anyone has completed being human.

Its working orientation is:

> **Field guide first, memoir second, theory underneath.**

The project does not offer one final doctrine for living. It gathers patterns, examples, letters, field notes, questions, and provisional lessons about harm, care, fear, shame, grief, love, power, repair, avoidance, tenderness, and the systems that shape ordinary behavior.

## What this project is

- **observational** — it begins with what people do, feel, avoid, repeat, and repair;
- **relational** — it treats being human as something formed among other people, creatures, systems, histories, and environments;
- **practical** — it tries to help readers notice and choose, not merely agree with an abstraction;
- **uncertainty-aware** — it distinguishes patterns and interpretations from universal laws;
- **anti-dominating** — it takes power, coercion, exclusion, and normalized harm seriously;
- **unfinished** — the guide is expected to change as experience, evidence, and perspective change.

## What it is not

- a list of commandments;
- a claim that kindness alone repairs structural harm;
- generic inspirational writing;
- a memoir in which personal experience becomes universal authority;
- a theory book that makes readers pass through jargon before reaching ordinary life;
- a demand for premature forgiveness, reconciliation, optimism, or emotional neatness;
- a substitute for accountability, boundaries, material support, or collective change.

## Writing principles

The writing should be plain, grounded, specific, and recognizably human.

It should:

- lead with lived situations and usable observations;
- preserve contradiction and edge cases;
- distinguish compassion from permission;
- make theory discoverable rather than compulsory;
- use examples without pretending they prove everything;
- name structural conditions without flattening people into symbols;
- leave room for readers to disagree, adapt, and notice what the guide missed.

Avoid stock contrasts, generic motivational gloss, fake profundity, inflated abstraction, repetitive em-dash rhythms, and language that sounds wise without saying anything testable or useful.

## Themes in development

Current and planned material includes:

- communication, misunderstanding, silence, tone, timing, and context;
- harm, care, accountability, boundaries, and repair;
- fear, shame, grief, avoidance, tenderness, and love;
- power, domination, hierarchy, punishment, and normalized cruelty;
- attention economies and environments that reward reactivity;
- capitalism, technofeudalism, compulsory work, and manufactured scarcity;
- disability, dependence, interdependence, and access;
- mutual aid, abolition, anti-domination, and community care;
- public and local technology, including humane relationships with AI;
- finitude, continuity, loss, memory, and what survives us;
- the limits of compassion and the difficulty of seeing several truths at once.

## Current repository structure

The project is an [Astro](https://astro.build/) site. Existing material currently includes:

```text
/
├── notes/
│   ├── raw-observations.md
│   └── responsibility-accountability-and-consequences.md
├── public/
├── src/
│   ├── content/
│   │   ├── field-guide/
│   │   │   └── communication.md
│   │   └── letters/
│   │       └── to-my-nieces.md
│   └── pages/
│       ├── core/
│       │   └── finitude-love-continuance.md
│       └── index.astro
├── astro.config.mjs
├── package.json
└── README.md
```

The repository should grow around real writing rather than accumulating empty categories.

## Working content model

As material develops, it can be organized by function:

- **Field guide** — concise, practical entries organized around situations and recurring human problems;
- **Field notes** — observations that remain contextual, incomplete, or unresolved;
- **Letters** — writing addressed to particular people or future readers;
- **Roots** — deeper theory, history, systems analysis, and intellectual lineage;
- **Notes and fragments** — raw material not yet ready to become a guide entry;
- **Edge cases** — places where a principle breaks, conflicts with another principle, or becomes dangerous when overextended;
- **Sources and further reading** — books, essays, research, traditions, and people that shaped a piece;
- **About** — project scope, authorship, uncertainty, accessibility, and revision practices.

These are content roles, not necessarily permanent URL folders. The public navigation should stay simpler than the underlying research architecture.

## Relationship to Root Sequence

Being Human(e) is part of the wider [Root Sequence ecosystem](https://github.com/Root-Sequence/root-sequence/blob/main/ECOSYSTEM.md).

- **Being Human(e)** is the approachable, ordinary-life front door: what people notice, experience, practice, and choose.
- **Root Sequence** holds deeper systems inquiry, cross-domain patterns, political analysis, and conceptual scaffolding.

A guide entry may link to deeper Root Sequence material, but readers should not need to understand the entire framework before finding something useful.

## Development

Run these commands from the repository root:

| Command | Action |
|---|---|
| `npm install` | Install dependencies |
| `npm run dev` | Start the local development server at `localhost:4321` |
| `npm run build` | Build the production site to `dist/` |
| `npm run preview` | Preview the production build locally |
| `npm run astro -- --help` | Show Astro CLI help |

## Near-term priorities

1. Replace the remaining starter homepage with the project's actual identity.
2. Add a small content index generated from existing field-guide entries and letters.
3. Decide the minimum public navigation before expanding directories.
4. Add clear status, revision, and source metadata to written pieces.
5. Create accessibility, contribution, and content-licensing guidance before accepting outside submissions.
6. Keep raw observations separate from polished guidance without treating either as disposable.

## Status

This project is active and early. Some material is publishable; some is a fragment, example, or structural experiment.

The goal is not to finish being human. It is to keep becoming more capable of noticing harm, choosing care, repairing what can be repaired, and living with what remains unresolved.

## License

The repository currently includes an [MIT License](LICENSE). Before accepting personal stories or outside contributions, the project should define more specific permissions for attribution, publication, editing, withdrawal, archival preservation, and reuse of contributed writing.
