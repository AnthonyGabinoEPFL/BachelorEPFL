Dépôt Git BA1 par Anthony Gabino



\# Notes de cours — BA1 Mathématique



Notes prises en LaTeX lors de la première année de Bachelor de mathématiques



\## Matières



Chaque branche possède son propre dossier avec tout ce qu'il faut pourvoir le piler de votre côté.



\## Structure



```

BA1/

├── shared/

│   ├── preamble.tex       # Importation des packages

│   ├── commands.tex    # Commandes communes (ℝ, ℕ, …)

│   └── titlepage.tex    # Template de page de titre

├── algebre I/

│   ├── algèbre I.tex

│   └── chapitres/

├── ...

└── README.md

```



\## Compilation



Chaque cours se compile indépendamment depuis son dossier :



```bash

cd algèbre I

latexmk -pdf "algèbre I.tex"

```



\## Prérequis



\- Une distribution LaTeX complète — \[MiKeX] (https://miktex.org/) (Linux/Windows/MacOS)

