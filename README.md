# Template custom de présentation Reveal.js 

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
@import '../IO-theme.scss';
```
