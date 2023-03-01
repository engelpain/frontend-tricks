# Trucos de HTML5
Autor: [Angelo Osorio](https://twitter.com/Engel_PAIN)

## Lazy Loading
Lazy Loading ya forma parte del estándar HTML. Se usa agregando el atriburo
*loading="lazy"* a la etiqueta de imagen objetivo. Aquí un ejemplo:
```html
<img loading="lazy" src="image.png" alt="Alter text" />
```

## Sugerencias en el input
HTML5 también agregó la posibilidad de mostrar nativamente sugerencias
a un input.
```html
<label for="country">Choose your country from the list:</label>
<input id="country" list="countries" />
<datalist id="countries">
  <option value="UK">
  <option value="Germany">
  <option value="USA">
  <option value="Japan">
  <option value="India">
</datalist>
```

## Base URL
Establece la url base de una aplicación, así todos los enlaces direccionarán
con esa url como prefijo.
```html
<head>
  <base href="https://www.twitter.com/" target="_blank">
</head>
<body>
  <a href="Engel_PAIN">Autor de la guía</a>
</body>
```

## Picture
También se agregó la posibilidad de cargar e intercambiar imágenes dependiendo
de la media query del dispositivo.
```html
<picture>
  <source media="(min-width: 495px)" srcset="small.jpg">
  <source media="(min-width: 768px)" srcset="medium.jpg">
  <img src="original_image.jpg" alt="Flags">
</picture>
```
