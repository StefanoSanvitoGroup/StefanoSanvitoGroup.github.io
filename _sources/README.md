# Stefano Sanvito Group

This repository contains the source of the Prof. Sanvito's Research and computational activities. Some of the pages are primarily for group members for technical guidelines, computational resources, practices and tutorials, but can be useful for outside researchers as well.

# Structure of the source

This website is created using [Jupyterbook](https://jupyterbook.org/en/stable/intro.html), based on [sphinx](https://www.sphinx-doc.org/en/master/).
See the [Jupyterbook](https://jupyterbook.org/en/stable/intro.html) for more details. The source for this website uses [MyST Markdown](https://myst-parser.readthedocs.io/en/latest/index.html).


The structure of the files  looks like follows -


```bash
(web) 👽 618-rajarshi 0 (main)✗  tree .
.
├── README.md
├── _config.yml
├── _static
│   └── style.css
├── _toc.yml
├── contact.md
├── group.md
├── index.md
├── references.bib
├── requirements.txt
├── research.md
└── resources.md
...
```

There are three types of files -

1. YAML files, with extension `.yml` which are used to define structure and build process of the pages. `_config.yml` file defines all the configurational options for building the pages, and `_toc.yml` file defines the [table of contents](https://jupyterbook.org/en/stable/start/create.html#table-of-contents-toc-yml), and structure of the documents.

2. CSS files, primarily stored in `_static` folder, and define the appearance settings for the webpages.

3. Markdown files, with `.md` extension. These are primarily ones that contain the documentation information. Jupyterbook follows MyST format, which is quite feature rich for building pages and pdfs of the technical documents. Checkout the MyST features [here](https://jupyterbook.org/en/stable/content/index.html).