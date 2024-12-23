# Función  ucfirst()

## ¿Qué hace?

Convierte el primer carácter de una cadena en mayúscula. Los demás caracteres permanecen intactos.

## SINTAXIS

``` bash
ucfirst(string $string): string
```

## Donde:

$string: La cadena a modificar.

## EJEMPLO

``` bash
<?php
$texto = "hola mundo";
echo ucfirst($texto); // Salida: "Hola mundo"

$texto2 = "php es genial";
echo ucfirst($texto2); // Salida: "Php es genial"
?>
```
