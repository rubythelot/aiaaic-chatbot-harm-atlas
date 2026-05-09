I am working on an interactive visualization for a talk about chatbot harms using the AIAAIC incident repository.

Current state:
- `index.html` is a standalone generated HTML file.
- `data/AIAAIC Repository - Incidents.csv` is the source dataset.
- The visualization currently shows harm types, harm scopes, time-series patterns, and incident examples.

Please redesign and refactor this into a cleaner, more editorial interactive visualization.

Goals:
1. Make the design feel more like a polished cultural/research artifact than a generic dashboard.
2. Keep the focus on chatbot / conversational AI incidents, but allow comparison against the full repository.
3. Preserve the core analytical views:
   - harm domains
   - ranked harm types
   - time series by harm scope/domain
   - incident examples
   - filters/search
4. Improve typography, spacing, hierarchy, and narrative flow.
5. Make the visualization work well for a projected talk and for a web page.
6. Keep a clear methods note explaining how the chatbot subset is detected.

Suggested visual direction:
- Serious, editorial, research-lab feeling.
- Avoid startup-dashboard clichés.
- Prioritize legibility, strong hierarchy, and elegant interaction.
- Use restrained color, with harm domains clearly distinguishable.

Technical preference:
- Refactor into a maintainable front-end project if useful.
- Use vanilla JS, React, Svelte, or another lightweight approach as you judge appropriate.
- Do not remove the source CSV.
- Make it easy to update the CSV later.

Definition of done:
- The project runs locally.
- The visualization loads the included CSV.
- The design is materially improved.
- The code is easier to edit than the current single generated HTML file.
- Include clear instructions in the README.
