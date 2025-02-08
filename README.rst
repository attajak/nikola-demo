Nikola (demo)
=============

This folder contains the source used to generate a static site using Nikola.

nikola-demo::

    .
    ├── README.txt
    ├── conf.py
    ├── files
    │   ├── favicon.ico
    │   └── images
    │       └── nikola.png
    ├── galleries
    │   └── demo
    │       ├── exclude.meta
    │       ├── index.txt
    │       ├── metadata.sample.yml
    │       ├── tesla2_lg.jpg
    │       ├── tesla4_lg.jpg
    │       ├── tesla_conducts_lg.webp
    │       ├── tesla_lightning1_lg.jpg
    │       ├── tesla_lightning2_lg.jpg
    │       └── tesla_tower1_lg.jpg
    ├── images
    │   ├── frontispiece.jpg
    │   └── illus_001.jpg
    ├── listings
    │   └── hello.py
    ├── pages
    │   ├── 1.rst
    │   ├── bootstrap-demo.rst
    │   ├── charts.rst
    │   ├── creating-a-theme.rst
    │   ├── dr-nikolas-vendetta.rst
    │   ├── extending.rst
    │   ├── internals.rst
    │   ├── listings-demo.rst
    │   ├── manual.rst
    │   ├── path_handlers.rst
    │   ├── quickref.rst
    │   ├── quickstart.rst
    │   ├── social_buttons.rst
    │   └── theming.rst
    ├── posts
    │   └── 1.rst
    └── templates
        └── book.tmpl

Installation and documentation at https://getnikola.com/

Configuration file for the site is ``conf.py``.

To build the site::

    nikola build

To see it::

    nikola serve -b

To check all available commands::

    nikola help
