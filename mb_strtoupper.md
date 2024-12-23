# Función  mb_strtoupper()

## ¿Qué hace?

La función mb_strtoupper() en PHP se utiliza para convertir un string a mayúsculas.

## SINTAXIS

``` bash
mb_strtoupper(string $str, string $encoding = mb_internal_encoding()): string
```

## Donde:

$str: La cadena que se desea convertir a mayúscula.
$encoding: Es la codificación de caracteres. Si no se especifica, usara la predeterminada(generalmente UTF-8).

## EJEMPLO

``` bash
<?php
// Cadena original
$texto = "Tyranitar vs Salamance";

// Convertir a mayúsculas con soporte para caracteres especiales
$resultado = mb_strtoupper($texto);
echo $resultado;
?>
```
