# Template custom de présentation Reveal.js 

## Run
```
npm start
```

## Build
```
npm run build
```

## Print to PDF
Dans l'url ajoutez le paramètre print-pdf : localhost:8000/?print-pdf, puis ctrl+p (impression sans marges)

## Settings
Pour l'ajout de css custom et desactiver les propriétés par defaut

```js
- index.html

Reveal.initialize({
  disableLayout: true, //for custom css
});
```

## Theme
Modification du theme : ajout d'un fichier scss et l'importer dans settings.scss
```js
- settings.scss

//custom css
@import './IO-theme.scss';
```
