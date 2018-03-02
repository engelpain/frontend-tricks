# Alertas de Bootstrap 4
Centro Nacional de Desarrollo e Investigación de Tecnologías Libres (CENDITEL) <br>
[CENDITEL](https://www.cenditel.gob.ve/), Mérida - Venezuela<br>
Dirección de Desarrollo<br>
Autor: [Ing. Angelo Osorio](https://twitter.com/Engel_PAIN)<br>
Fecha de Elaboración: 02-03-2018 (dd,mm,aaaa)

## Clases para table
* table
* table table-striped
* table table-bordered
* table table-hover
* table table-sm

## Colorear celdas
* table
   * table table-{primary, secondary, success, warning, danger, dark, light}
* thead, tbody, th, tr, td
   * table-{primary, secondary, success, warning, danger, dark, light}
   * bg-{primary, secondary, success, warning, danger, dark, light}

## Tabla responsiva
```html
<div class="table-responsive">
  <table class="table">
    ...
  </table>
</div>
```
## Ejemplo de tabla
```html
<table class="table">
  <thead class="bg-primary text-light">
    <tr>
      <th scope="col">#</th>
      <th scope="col">First</th>
      <th scope="col">Last</th>
      <th scope="col">Handle</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">1</th>
      <td>Mark</td>
      <td>Otto</td>
      <td>@mdo</td>
    </tr>
    <tr>
      <th scope="row">2</th>
      <td>Jacob</td>
      <td>Thornton</td>
      <td>@fat</td>
    </tr>
    <tr>
      <th scope="row">3</th>
      <td>Larry</td>
      <td>the Bird</td>
      <td>@twitter</td>
    </tr>
  </tbody>
</table>
```