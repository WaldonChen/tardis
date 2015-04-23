=========
TARDIS
=========

TeAching Risc Derived Instruction Set

Build
========

Build TARDIS
--------------

Clone the repo with: ::

    git clone https://github.com/waldonchen/tardis tardis

Clone and Rebuild github pages
-------------------------------

.. This is a comment. Following specular characters are used to create table and directory tree.
   ┌─┬─┐
   │ │ │
   ├─┼─┤
   │ │ │
   └─┴─┘

1. Create a *tardis-docs* directory. The directory structure look like this: ::

    tardis
    ├── ...
    ├── .git
    │   └── ...
    ├── docs
    │   ├── conf.py
    │   ├── Makefile
    │   └── index.rst
    ├── LICENSE
    └── README.rst

    tardis-docs     <- sibling folder of tardis

2. Clone and checkout the gh-pages branch. ::

    cd tardis-docs
    git clone https://github.com/waldonchen/tardis html
    cd html
    git checkout gh-pages

3. Rebuild GitHub pages with following command: ::

    cd tardis-docs/html
    git add .
    git commit -m "rebuilt docs"
    git push origin gh-pages

Documentation
================

Visit the documention of TARDIS on `github.io`_.

.. _github.io: http://waldonchen.github.io/tardis/
