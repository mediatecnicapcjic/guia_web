# Tablas

Una tabla se define con la etiqueta `<table>`.

Las filas se definen con la etiqueta `<tr>`.

Las celdas se definen con la etiqueta `<td>`.

Ejemplo:

```markup
<table>
  <tr>
    <td>Pedro</td>
    <td>Perez</td>
  <tr>
  <tr>
    <td>Juan</td>
    <td>Gomez</td>
  <tr>
</table>
```

Nunca utilices `<tr>` por fuera de un `<table>`.

Nunca utilices `<td>` por fuera de un `<tr>`.

## Encabezados

Para crear encabezados utiliza `th` en vez de `td`:

```markup
<table>
  <tr>
    <th>Nombre</th>
    <th>Apellido</th>
  <tr>
  <tr>
    <td>Juan</td>
    <td>Gomez</td>
  <tr>
</table>
```

## Celdas que ocupan más de una columna o fila

Para que una celda \(`td` o `th`\) ocupe más de una columna utiliza el atributo `colspan` con el número de columnas que quieres que ocupe. Por ejemplo:

```markup
<table>
  <tr>
    <td>1</td>
    <td>2</td>
    <td>3</td>
  </tr>
  <tr>
    <td colspan="2">Ocupa 2 columnas</td>
    <td>4</td>
  </tr>
  <tr>
    <td colspan="3">Ocupa 3 columnas</td>
  </tr>
</table>
```

Para que una celda ocupe más de una fila utiliza el atributo `rowspan` con el número de filas que quieres que ocupe:

```markup
<table>
  <tr>
    <td rowspan="2">Ocupa 2 filas</td>
    <td>1</td>
  </tr>
  <tr>
    <td>2</td>
  </tr>
</table>
```

