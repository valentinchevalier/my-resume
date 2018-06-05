# My resume

My resume, written in `.pug` and `.scss`

## Icons font
The icons in the resume are inserted via an icons font. I use [icon-font-generator](https://github.com/Workshape/icon-font-generator) to generate it.

``` bash
# Installation of dependency
npm install -g icon-font-generator
# Font icon generation
icon-font-generator my-icons/*.svg -o dist
```

## PDF generation
The resume is generated from `.pug` and `.scss` to `.pdf` with [RelaxedJS](https://github.com/RelaxedJS/ReLaXed)

``` bash
# Installation of dependency
npm i -g relaxedjs
# PDF generation
relaxed resume.pug --build-once
```
