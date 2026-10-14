# crest-science.github.io

Source of **<https://crest-science.github.io>** — *AI in Research @ CREST*, the website of the **GenAI practices @CREST 2026-2027** cycle: short, filmed trainings (1h30, Thursdays 2pm, hybrid) for CREST members on using generative AI tools in research.

Organizers: Nicolas Brosse, Émilien Schultz.
Questions and ideas: [Discussions](https://github.com/orgs/crest-science/discussions).

## Where things go

| What | Where |
|---|---|
| Upcoming training (date + speaker confirmed) | a row in `_schedule.md` |
| Past training (pitch, recording, slides) | `formations/YYYY-MM-DD-name/index.qmd` — copy `formations/_template/` |
| Blog post | `blog/posts/YYYY-MM-DD-name/index.qmd` — copy `blog/posts/_template/` |
| Key reference | `references.qmd` |

Internal planning and brainstorming stay in the organizers' pad; only confirmed trainings go into `_schedule.md`.

## Workflow

- `main` is protected: changes go through a pull request (1 approval, site build must pass).
- `dev` is the working branch; open a PR `dev → main` to publish.
- Pushing to `main` builds and deploys the site with GitHub Actions (Settings → Pages → Source: *GitHub Actions*).
- Preview locally: `quarto preview`.

## Media

- **Videos are never stored in this repository**: host them externally and embed with `{{< video URL >}}`.
- **Slides**: Quarto revealjs decks or PDFs (< 10 MB) inside the training folder.
