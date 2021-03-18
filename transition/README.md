# Sass-tricks: Transiciones
Autor: [Angelo Osorio](https://twitter.com/Engel_PAIN) <br>
Fecha de Elaboración: 18-03-2021 (dd,mm,aaaa)

### Como usar transition con css3
1. [Establecer una propiedad](#1-establecer-la-propiedad-que-requiere-transición)
2. [Agregar la duración](#2-tiempo-de-duración-de-la-transición)
3. [Establecer la curva de velocidad](#3-establecer-la-curva-de-velocidad-de-la-transición)
4. [Uniendo todo](#4-uniendo-todo)
5. [Versión corta](#versión-corta)

#### 1. Establecer la propiedad que requiere transición:
   - `transition-property: property-que-cambiará`
   - Ejemplo: ```.target {transition-property: width; } ```

#### 2. Tiempo de duración de la transición:
   - ``` .target { transition-duration: 2s; } ```

#### 3. Establecer la curva de velocidad de la transición:
   - _ease_ - specifies a transition effect with a slow start, then fast, then end slowly (this is default)
   - _linear_ - specifies a transition effect with the same speed from start to end
   - _ease-in_ - specifies a transition effect with a slow start
   - _ease-out_ - specifies a transition effect with a slow end
   - _ease-in-out_ - specifies a transition effect with a slow start and end
   - _cubic-bezier(n,n,n,n)_ - lets you define your own values in a cubic-bezier function
   - ``` .target { transition-timing-function: linear; } ```

#### 4. Uniendo todo:
   ```
   .target {
     transition-property: width;
     transition-duration: 2s;
     transition-timing-function: linear;
   }
   ```

#### Versión corta
   - ``` .target { transition: width 2s linear; } ```

### Prefijos
   - `transition: width .5s linear;`
   - `-o-transition: width .5s linear; /* opera */`
   - `-ms-transition: width .5s linear; /* IE 10 */`
   - `-moz-transition: width .5s linear; /* Firefox */`
   - `-webkit-transition: width .5s linear; /* Chrome y Safari */`