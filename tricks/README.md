# Sass-tricks: Trucos
Autor: [Angelo Osorio](https://twitter.com/Engel_PAIN) <br>
Fecha de Elaboración: 25-03-2021 (dd,mm,aaaa)

### Lista de trucos
1. [Elipsis](#Elipsis)

#### Elipsis
- Para poner 3 puntos a un párrafo si supera el tamaño del contenedor.
- **Nota:** Requiere que el texto se desborde del contenedor.
- `text-overflow: ellipsis`
- Ejemplo:
   ```
   .ellipsis {
     width: 500px;
     text-overflow: ellipsis;
     overflow: hidden;
     white-space: nowrap;
   }
   ```