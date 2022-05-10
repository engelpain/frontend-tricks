# Typing effect
Efecto de escritura en una terminal para páginas web.

1. Se agregan algunos estilos para el texto.
```css
.typing-effect {
  animation: typing 5s steps(25), blink 1s step-end infinite alternate;
  border-right: 10px solid;
  font-family: monospace;
  font-style: 2em;
  overflow: hidden;
  white-space: nowrap;
  width: 25ch;
}
```


1. Agregando los keyframes para los efectos
```css
@keyframes typing {
  from {
    width: 0;
  }
}

@keyframes blink {
  50% {
    border-color: transparent;
  }
}

```

1. En el html se agrega la clase que convoca los estilos
```html
<div class="typing-effect">Probemos un efecto nuevo</div>
```
