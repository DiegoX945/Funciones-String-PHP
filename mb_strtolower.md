# Función  mb_strtolower()

## ¿Qué hace? 

La función mb_strtolower() en PHP convierte una cadena a minúsculas.

## SINTAXIS

``` bash
mb_strtolower(string $str, string $encoding = mb_internal_encoding()): string
```
## Donde:

$str: La cadena que se desea convertir a minúsculas.

$encoding: Como se mencionó en varias veces es algo opcional, si no llegara a especificarse se utiliza el UTF-8 por defecto.

## EJEMPLO

``` bash
<?php
// Cadena original
$texto = "ESTAMOS UTILIZANDO PHP";

// Convertir a minúsculas con soporte para caracteres especiales
$resultado = mb_strtolower($texto);
echo $resultado;

?>
```
