# Mon CV

La typos de'icônes doit être généré avec [icon-font-generator](https://github.com/Workshape/icon-font-generator)

``` bash
# Installation de la dépendance
npm install -g icon-font-generator
icon-font-generator my-icons/*.svg -o dist
```

Le CV est généré avec [RelaxedJS](https://github.com/RelaxedJS/ReLaXed)

``` bash
# Installation de la dépendance
npm i -g relaxedjs
# Génération du pdf
relaxed resume.pug --build-once
```
