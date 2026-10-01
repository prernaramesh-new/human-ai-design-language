# Human–AI Design Language

A design language by **Ozonetel** for interfaces where people and AI work together.

Conversational AI quietly dropped things interface design already knew how to do. A person can no longer reliably tell what the AI is doing, what it can touch, or how to get back to their own work. These aren't novel puzzles — they're regressions. This is an attempt to rebuild that legibility, published openly so others can use it, argue with it, and improve it.

**→ [Read the design language](https://prernaramesh-new.github.io/human-ai-design-language/)**

## Four questions

| Question | The problem | Status |
|---|---|---|
| **What is it doing?** | When AI goes quiet, people can't tell whether it's working, waiting, or stuck. | Nine states, two visual families |
| **What can it see?** | People need to know what AI can use, and what stays private. | Six studies, fifteen concepts |
| **Where is my work?** | Returning to a task shouldn't mean explaining everything again. | Five of six parts; the sixth, AI for collaboration, to come |
| **Why do I not want to talk to it?** | When AI makes an interaction feel like effort, people stop using it. | Research done, design not started |

The empty sections are deliberate and marked as such. Where a study shows several concepts, they are presented as options, not a recommendation. This is a first public draft, not a finished system.

## What we'd like comments on

Anything, but especially:

- Where would these patterns break down in a product you use?
- What feels unclear, incomplete, or difficult to apply?
- What would you change, add, or approach differently?
- Do you have examples from products or workflows that could help us test these ideas?

**[Open a discussion](../../discussions)** — one thread per question. No issue needed; these are proposals, not bugs.

## How it's built

Six self-contained HTML files. No build step, no dependencies, no external assets — clone it and open `index.html` in a browser.

| File | Contents |
|---|---|
| `index.html` | Introduction and the four questions |
| `human-ai-activity.html` | What is it doing? — nine states |
| `human-ai-access.html` | What can it see? |
| `human-ai-continuity.html` | Where is my work? |
| `human-ai-motivation.html` | Why do I not want to talk to it? |
| `human-ai-design-language-reference.html` | Design notes and references |

## Credits

Designed and built by **Prerna Ramesh**. A design language by **Ozonetel**.

## Licence

[CC BY 4.0](LICENSE) — use it, adapt it, build on it commercially. Just credit Ozonetel.
