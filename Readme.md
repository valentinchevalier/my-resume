# My resume

My resume, written in `.pug` and `.scss`

## Icons font
The icons in the resume are inserted via an icons font. I use [icon-font-generator](https://github.com/Workshape/icon-font-generator) to generate it.

``` bash
# Installation of dependency
npm i

# Font icon generation
npm run icon:generate
```

## PDF generation
The resume is generated from `.pug` and `.scss` to `.pdf` with [RelaxedJS](https://github.com/RelaxedJS/ReLaXed)

``` bash
# Installation of dependency
npm i

# Launch watch command for developpement
npm run start

# Build PDF for production
npm run build
```
