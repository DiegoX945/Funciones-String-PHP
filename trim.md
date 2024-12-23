# Función  trim()

## ¿Qué hace?

Elimina espacios en blanco u otros caracteres específicos al inicio y al final de una cadena.

## SINTAXIS

``` bash
trim(string $string, string $characters = " \n\r\t\v\0"): string
```

## Donde:

$string: La cadena que desea procesar

$characters (opcional): Lista de caracteres que se eliminaran(por defecto, espacios en blanco, saltos de línea, tabulaciones, etc)

## EJEMPLO

``` bash

<?php
$texto = "   Hola Mundo   ";
echo trim($texto); // Salida: "Hola Mundo"

$textoConCaracteres = "xxxHola Mundoxxx";
echo trim($textoConCaracteres, "x"); // Salida: "Hola Mundo"
?>
```
