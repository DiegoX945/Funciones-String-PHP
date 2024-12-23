# Funcion mb_convert_case()
## ¿Qué hace?
La funcion mb_convert_case() es una función en PHP que se utiliza para convertir el caso (mayúsculas o minúsculas) de una cadena de texto.
## SINTAXIS
``` bash
mb_convert_case(string $str, int $mode, string $encoding = mb_internal_encoding()): string
```
## Donde:

&str: El string que se va a convertir.

$mode: Modo de conversión (MB CASE UPPER, MB CASE LOWER, o MB CASE TITLE).

$enconding: Es la codificación de caracteres, la cual por efecto será UTF-8.

## EJEMPLO
``` bash
<?php
//Cadena original
$texto1 = "¡hola mundo!";
//Convertir a mayúsculas
echo mb_convert_case($texto1, MB_CASE_UPPER); 
echo "<br>";
echo "<br>";
//Convertir a minúsculas
$texto2 = "¡HELLO WORLD!";
echo mb_convert_case($texto2, MB_CASE_LOWER);
echo "<br>";
echo "<br>";
//Convertir al formato de título
echo mb_convert_case($texto2, MB_CASE_TITLE); 
?>
```
