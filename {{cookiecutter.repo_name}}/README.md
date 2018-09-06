# {{cookiecutter.project_name}}

{{cookiecutter.description}}

## Project Organization

    ├── Makefile            <- Makefile with commands like `make docs`
    ├── README.md           <- The top-level README for developers using this project.
    │
    ├── docs                <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── notebooks           <- Notes and notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    |
    ├── processed_data
    |   ├── CRYSOL          <- Output of CRYSOL.
    │   ├── DAMMIF          <- Output of DAMMIF.
    |   ├── DAMAVER         <- Output of DAMAVER.
    |   ├── DENSS           <- Output of DENSS.
    |   ├── GNOM            <- Output of GNOM.
    |   ├── others          <- Output from other processing softwares.
    |   ├── SUPALM          <- Output of SUPALM for alignment of high resolution model to DAMMIF.
    |   ├── SUPCOMB_dam     <- Output of SUPCOMB using the DAMMIF models.
    |   └── SUPCOMB_highres <- Output of SUPCOMB using a high resolution model.
    |
    ├── references          <- Data dictionaries, manuals, and all other explanatory materials.
    |   └── models          <- High resolution structural models.
    |
    ├── reports             <- Generated analysis as HTML, PDF, LaTeX, etc.
    |   └── figures         <- Generated graphics and figures to be used in reporting
    │
    ├── scattering_data
    |   ├── averaged        <- Averaged data.
    |   ├── raw             <- Raw data acquired.
    |   ├── subtracted      <- The final, buffer-subtracted averaged scattering data for modeling.
    |   └── uv              <- UV data acquired.
    |
    └── scripts             <- PyMOL scripts to generate figures.

--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
