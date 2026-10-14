# Peptide company research

An English–Spanish research interface comparing 12 publicly traded pharmaceutical and biotechnology companies. It brings clinical evidence, regulatory status, financial disclosures, patents and licensing arrangements into a consistent, navigable format.

**Research cutoff: 11 October 2026.** Market prices generally refer to the 9 October 2026 close; individual figures retain their own dates. This is a saved research snapshot, not a live data service.

## Objective and process

The initial research and interface were produced in under 24 hours. The project demonstrates rapid, AI-assisted research and software development: framing an open-ended question, directing investigation across several disciplines, and turning the results into an accessible bilingual interface.

Human contribution included setting the objective, directing the AI-assisted workflow, reviewing the output and shaping the presentation. AI models assisted research synthesis and implementation. AI-generated work can contain errors; inclusion of a source link does not mean every claim has been independently verified.

## What the interface includes

- Company summaries with separate evidence views.
- 308 source records linked to public URLs, with evidence identifiers connecting research statements to sources.
- Distinctions between sourced facts, assumptions, illustrative valuation scenarios and unresolved questions.
- Clinical, financial, regulatory and intellectual-property comparisons.
- English and Spanish navigation and content.

Coverage: VKTX, RYTM, ZEAL, PTGX, ALT, CAMX, 4587, 1801, 1276, NVO, LLY and KLRA.

## Open the research

[Open the public website](https://serpentofthesky.github.io/peptide-research/#en/VKTX). GitHub Pages serves the same standalone research snapshot in this repository.

Open `index.html` directly in a modern browser. All application code and data are embedded in that file; no installation, API key or build step is required. Internet access is needed only to visit external sources.

Alternatively, from this directory run:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Paste `http://127.0.0.1:8000/#en/VKTX` into a browser. Keep Terminal open while using this local server; press Control-C to stop it.

## Scope and limitations

This repository publishes the finished interface. Private working files, model conversations, prompts, local research infrastructure and application materials are excluded. Local filesystem metadata and personal attribution have been removed from the public artifact.

The material is for information and education, not investment or medical advice, and is not peer-reviewed research or an AI safety research project. Clinical, regulatory and financial information can change. Some sources are dynamic, restricted or may become unavailable; check the original documents, dates and stated limitations before relying on any claim. Scenarios are illustrations, not forecasts.
