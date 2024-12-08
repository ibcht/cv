# Un simple CV 

Basé sur :
- [JSON Resume](https://jsonresume.org/schema)
- [Jinja](https://jinja.palletsprojects.com/)
- Un site HTML5 fait maison

## Développement local

Prérequis : VS Code, Docker / Podman.

1. Ouvrir le repo dans VS Code et se connecter à un dev container
1. Générer le CV : `jinja index.html.j2 resume.yml -o www/index.html`
1. Naviguer sur le site www

## CICD GitHub Actions

Cf. `.github/workflows/build-and-deploy.yml`

## A faire ...

Génération d'un CV imprimable + efficace qu'une impression du site web.