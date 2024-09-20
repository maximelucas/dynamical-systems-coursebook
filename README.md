
# Source pour les codes du cours Théorie Qualitative des Systèmes Dynamiques

Le jupyter-book peut-être trouvé à l'adresse [ https://github.com/maximelucas/dynamical-systems-coursebook/intro.html]( https://github.com/maximelucas/dynamical-systems-coursebook/intro.html).

## Deployer ce jupyter-book

- Ce jupyter-book est redéployé et publié automatiquement à chaque push par une Action Github.

It is also possible to do it manually:

- add additional notebooks/markdown files to directories separated by topic
- add the corresponding files to the `_toc.yml` file to add them to the overall table of content of the book. 
- test building the book for errors using `jupyter-book build .` or `jb build .` (if already inside the coursebook directory). 
- if no errors are present, the updated version of the book can be pushed live using the script `publish_book.sh`, which builds the book and pushes it to the live github pages website. 

## Construire localement

Exécuter `jupyter-book build .`
