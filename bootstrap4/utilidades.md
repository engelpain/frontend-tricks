# Utilidades de Bootstrap 4
Centro Nacional de Desarrollo e Investigación de Tecnologías Libres (CENDITEL) <br>
[CENDITEL](https://www.cenditel.gob.ve/), Mérida - Venezuela<br>
Dirección de Desarrollo<br>
Autor: [Ing. Angelo Osorio](https://twitter.com/Engel_PAIN)<br>
Fecha de Elaboración: 01-03-2018 (dd,mm,aaaa)

1. [Bordes](#bordes)
   1. [Agregar bordes](#agregar-bordes)
   1. [Colorear bordes](#colorear-bordes)
   1. [Redondear bordes](#redondear-bordes)
   1. [Eliminar bordes](#eliminar-bordes)
2. [Texto](#texto)
   1. [Colorear Texto](#colorear-texto)
   1. [Alinear Texto](#alinear-texto)
   1. [Comportamiento del texto](#comportamiento-del-texto)
   1. [Transformación del texto](#transformaci%C3%B3n-del-texto)
3. [Fondo](#fondo)
   1. [Colorear Fondo](#colorear-fondo)
4. [Embed](#embed)
5. [Posición](#posici%C3%B3n)
6. [Visibilidad](#visibilidad)
7. [Flotantes](#flotantes)

## Bordes
### Agregar bordes
* border
* border-top
* border-right
* border-bottom
* border-left

### Colorear bordes
* border border-primary
* border border-secondary
* border border-success
* border border-danger
* border border-warning
* border border-info
* border border-light
* border border-dark
* border border-white

### Redondear bordes
* rounded
* rounded-top
* rounded-right
* rounded-bottom
* rounded-left
* rounded-circle
* rounded-0

### Eliminar bordes
* border-0
* border-top-0
* border-right-0
* border-bottom-0
* border-left-0

## Texto
### Colorear texto
* text-primary
* text-secondary
* text-success
* text-danger
* text-warning
* text-info
* text-light
* text-dark
* text-muted
* text-white

### Alinear texto
* Texto Vertical
   * align-baseline
   * align-top
   * align-middle
   * align-bottom
   * align-text-top
   * align-text-bottom
* Texto Horizontal
   * text-left
   * text-center
   * text-right
   * text-justify
* Por media query
   * text-sm-left
   * text-md-left
   * text-lg-left
   * text-xl-left

### Comportamiento del texto
* Sin salto de línea
   * text-nowrap
* Corta el texto al tamaño del div
   * text-truncate

### Transformación del texto
* text-lowercase
* text-uppercase
* text-capitalize
* font-weight-bold
* font-weight-normal
* font-weight-light
* font-italic

## Fondo
### Colorear fondo
* bg-primary
* bg-secondary
* bg-success
* bg-danger
* bg-warning
* bg-info
* bg-light
* bg-dark
* bg-white

## Embed
* 21:9 aspect ratio
   * div.embed-responsive.embed-responsive-21by9
      * iframe.embed-responsive-item

* 16:9 aspect ratio
   * div.embed-responsive.embed-responsive-16by9
      * iframe.embed-responsive-item

* 4:3 aspect ratio
   * div.embed-responsive.embed-responsive-4by3
      * iframe.embed-responsive-item

* 1:1 aspect ratio
   * div.embed-responsive.embed-responsive-1by1
      * iframe.embed-responsive-item

## Posición 
* position-static
* position-relative
* position-absolute
* position-fixed
* position-sticky
* fixed-top
* fixed-bottom
* sticky-top

## Visibilidad
* Visibilidad de los elementos
   * none
   * inline
   * inline-block
   * block
   * table
   * table-cell
   * table-row
   * flex
   * inline-flex

* Mostrar elementos por media query
   * Mostrado en todas: d-block
   * Mostrado solo en xs: .d-block .d-sm-none
   * Mostrado solo en sm: .d-none .d-sm-block .d-md-none
   * Mostrado solo en md: .d-none .d-md-block .d-lg-none
   * Mostrado solo en lg: .d-none .d-lg-block .d-xl-none
   * Mostrado solo en xl: .d-none .d-xl-block
* Ocultar elementos por media query
   * Ocultar en todas: d-none
   * Oculto solo en xs: d-none d-sm-block
   * Oculto solo en sm: d-sm-none d-md-block
   * Oculto solo en md: d-md-none d-lg-block
   * Oculto solo en lg: d-lg-none d-xl-block
   * Oculto solo en xl: d-xl-none

## Flotantes
* float-left
* float-right
* float-none