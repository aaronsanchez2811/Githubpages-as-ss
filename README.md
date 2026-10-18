## Readme

Web de documentació tècnica de Linux, xarxes i serveis, feta per Aaron Sánchez i Sergi Sunyol.

Web publicada: https://aaronsanchez2811.github.io/Githubpages-as-ss/

## Eina utilitzada

MkDocs 1.6.1, un generador de webs estàtiques fet en Python.

| | Hugo | Jekyll | MkDocs |
|---|---|---|---|
| Llenguatge | Go | Ruby | Python |
| Pensat per a | Webs i blogs | Blogs | Documentació |
| Configuració | hugo.toml | _config.yml | mkdocs.yml |

L'hem triat perquè està pensat per a documentació tècnica, que és el que demanava la pràctica, i tota la configuració és en un sol fitxer.

## Instal·lació i ús en local

py -m pip install mkdocs
git clone https://github.com/aaronsanchez2811/Githubpages-as-ss.git
cd Githubpages-as-ss
py -m mkdocs serve

La web es veu a http://127.0.0.1:8000.

## Generar i publicar

build crea la carpeta site/ amb l'HTML final, i gh-deploy la puja a la branca gh-pages, que és la que publica GitHub Pages.

## Desplegament automàtic

El fitxer .github/workflows/deploy.yml és un workflow de GitHub Actions. Cada vegada que fem git push a main, instal·la MkDocs, genera la web i la publica sola.

## Estructura

├── .github/workflows/deploy.yml
├── docs/
│   ├── index.md
│   ├── blog/
│   ├── linux/
│   ├── xarxes/
│   ├── serveis/
│   ├── css/
│   └── img/
├── mkdocs.yml
└── README.md
