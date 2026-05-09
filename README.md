# AIAAIC Chatbot Harm Atlas

Interactive visualization exploring harms in the AI Incident Tracking Foundation / AIAAIC incident repository, with a focus on chatbot and conversational AI incidents.

## Files

- `index.html` — current standalone interactive visualization.
- `data/AIAAIC Repository - Incidents.csv` — source dataset used to generate the visualization.
- `codex_prompt.md` — design and refactor prompt to give Codex.

## How to preview locally

Open `index.html` directly in a browser, or run a local server:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Suggested next step

Ask Codex to refactor this from a single generated HTML file into a cleaner maintainable app, ideally with:

- `src/` components
- parsed CSV data loading
- reusable harm-category taxonomy
- a more editorial / talk-ready design system
- responsive layout for projection and web sharing
