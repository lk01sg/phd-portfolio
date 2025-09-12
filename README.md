# PhD Portfolio Repository

This repository contains my research workflow, drafts, and resources for my PhD journey.

The structure is designed to separate raw data, notebooks, source code, manuscripts, and documentation.

---

## Repository structure

```
/ (root)
├─ /data/           # raw, processed, and sample datasets
│   ├─ /raw/        # original datasets (never modified)
│   ├─ /processed/  # cleaned or transformed datasets
│   └─ /sample/     # lightweight / dummy data for demo, docs, or testing
├─ /notebooks/      # exploratory and analysis notebooks (Quarto / Jupyter)
├─ /src/            # analysis scripts, utility modules, and reproducible pipelines
├─ /manuscripts/    # manuscript drafts, figures, and supplementary materials
├─ /docs/           # documentation, website source for phd-portfolio (GitHub Pages)
├─ /results/        # generated outputs: figures, tables, model checkpoints
├─ /env/            # environment specification (environment.yml / requirements.txt)
└─ README.md        # this file
```

> Notes
>
> * Keep raw data **only** in `/data/raw/` and never commit sensitive/private data to the repository.
> * Use `/data/processed/` for cleaned or transformed datasets used by notebooks and scripts.
> * `/data/sample/` is optional, but useful for sharing small datasets for documentation or testing.

---

## How I use this repo

* Develop experiments in `/notebooks/` and extract production-ready code into `/src/`.
* Save reproducible outputs to `/results/` and link figures to manuscript drafts under `/manuscripts/`.
* Use `docs/` to build the public-facing PhD portfolio site (GitHub Pages). The site is authored in Quarto/Markdown and published to `lk01sg.github.io/phd-portfolio`.

---

## Contributing / Personal workflow

This repository is primarily a personal workspace, but the following conventions help keep it organized:

* Notebooks should include a brief README header describing purpose, inputs, and outputs.
* Code in `/src/` must be importable as a module and documented with docstrings.
* Provide a `requirements.txt` or `environment.yml` in `/env/` so experiments are reproducible.
* Use `git` feature branches for major changes and keep `main`/`master` stable.

---

## License & Contact

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

For reuse of code or figures, please contact me at [lksingagerda@outlook.co.id](mailto:lksingagerda@outlook.co.id).

---

## Quick links

* Project site: `https://lk01sg.github.io/phd-portfolio`
* Example workflow: see `/notebooks/example_workflow.ipynb`

*Last updated: September 12, 2025*
