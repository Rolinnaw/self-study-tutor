# Self-Study Tutor

**A source-grounded 1v1 tutor that turns course materials into connected understanding and independent ability.**

Self-Study Tutor is a personal Codex plugin for learning academic subjects from your own lectures, workshops, textbooks, tutoring materials, past papers, and progress records. It teaches in concise Chinese where helpful, preserves essential English terminology, and moves from explanation to real application without overwhelming the learner.

## Why it exists

Most AI tutoring either explains too much at once or gives answers before the learner can think. Self-Study Tutor is designed around a different goal:

> Understand the foundations, connect the knowledge, practise deliberately, and become able to solve similar problems independently.

It does not treat recognition as mastery. A topic is considered learned only when the learner can transfer it, diagnose mistakes, and connect it to the wider knowledge tree.

## How it works

```mermaid
flowchart LR
    A[Course materials] --> B[Coverage map]
    B --> C[Knowledge tree]
    C --> D[Guided practice]
    D --> E[Real task or project]
    E --> F[Mastery check]
    F --> G[Progress record]
```

For every new subject, the tutor first inventories the available sources, checks existing progress, and asks the learner to choose a teaching mode.

| Mode | Best for | Learning rhythm |
| --- | --- | --- |
| **Application-first** | Programming, data analysis, practical coursework | Minimum foundation → real task → explain concepts when needed |
| **Principles-first** | Computer systems, theory, mathematics | Bottom-up causal model → observable examples → application |
| **Hybrid** | Linux, databases, networking, developer tools | Complete a real task → explain the underlying system → repeat with variation |

## Core principles

- **Grounded in all declared sources** — lectures define scope, workshops show expected application, textbooks add depth, and past papers reveal task patterns rather than replacing the syllabus.
- **Connected knowledge** — each new topic is placed in a compact tree of prerequisites, current concepts, later abilities, and intentionally deferred depth.
- **Learn by doing** — explanations stay short and alternate with prediction, writing, running, debugging, comparison, and application.
- **Graduated help** — problem location → conceptual hint → pseudocode → partial solution → full solution only when necessary.
- **Course first, practice second** — required course methods come first; workplace conventions are labelled `Professional practice / 实务做法`.
- **Evidence-based progress** — mastery requires independent transfer, error diagnosis, and connection to earlier and later concepts.
- **Continuity** — each session records coverage, mastery evidence, unresolved gaps, and the next concrete task.

## Quick start

1. Open a new Chat, Work, or Codex task.
2. Attach or provide the paths to your course materials and progress record.
3. Invoke the tutor:
   - Chat / Work: `@Self Study Tutor`
   - Codex: `$self-study-tutor`
4. Use the [full starter prompt](START_PROMPT.md), or begin with:

```text
Use Self Study Tutor to help me learn this subject.
First inspect my materials and existing progress, then ask me to choose
Application-first, Principles-first, or Hybrid mode. Show the current
knowledge tree and guide me through the first concrete task.
```

## What to provide

Only include the source types that exist for the subject:

- Lectures
- Workshops or labs
- Textbook chapters
- Tutoring-class materials
- Past papers and marking schemes
- Assessment rubrics or exam guidance
- Existing notes, code, projects, and learning-progress records

Missing, conflicting, or potentially incorrect material is reported explicitly rather than guessed.

## Repository structure

```text
self-study-tutor/
├── .codex-plugin/plugin.json
├── START_PROMPT.md
└── skills/self-study-tutor/
    ├── SKILL.md
    ├── agents/openai.yaml
    └── references/
        ├── course-setup.md
        ├── teaching-modes.md
        └── session-methods.md
```

- `SKILL.md` contains the shared tutoring contract and routing rules.
- `course-setup.md` defines source inventory, precedence, and continuity.
- `teaching-modes.md` defines the three learning architectures.
- `session-methods.md` adapts practice to programming, quantitative, and conceptual subjects.
- `START_PROMPT.md` is the reusable course setup template.

## Maintenance

The canonical editable source is this repository. Installed Codex cache files are generated copies and should not be edited manually.

```text
Edit here → validate → commit and push → reinstall the personal plugin
```

Course materials and learning-progress files stay outside the plugin so the same tutoring system can be reused across different subjects.

---

Built for deep understanding, practical competence, and long-term independent learning.
