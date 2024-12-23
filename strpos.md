# Función  strpos()

## ¿Qué hace?

Encuentra la posición de la primera aparición de un texto (subcadena) dentro de otra cadena. Es sensible a mayúsculas y minúsculas.

## SINTAXIS

``` bash

strpos(string $haystack, string $needle, int $offset = 0): int|false
```

## Donde:

&haystack: La cadena en la que se buscara.

$needle: El texto o subcadena que se desea buscar

$offset: La posición inicial desde donde comenzara la búsqueda (por defecto,0)

## EJEMPLO

``` bash

<?php
$cadena = "Hola Mundo, bienvenido al mundo PHP";
$posicion = strpos($cadena, "M");

if ($posicion !== false) {
    echo "El caractér esta en la posicion :$posicion"; 
// Salida: El caractér esta en la posicion : 5
} else {
    echo "El caractér no se encontró.";
}
?>
```
