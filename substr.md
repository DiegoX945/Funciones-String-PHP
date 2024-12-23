# Función  substr()

## ¿Qué hace?

Extrae y devuelve una porción de una cadena, comenzando desde una posición específica y opcionalmente con una longitud determinada.

## SINTAXIS

``` bash
substr(string $string, int $start, ?int $length = null): string
```

## Donde:

$string: La cadena de la que quieres extraer la subcadena.

$start: la posición desde donde quieres empezarla extracción.

$lenght (opcional): La cantidad de caracteres que deseas extraer.

## EJEMPLO

### Ejemplo simple

``` bash
<?php
$cadena = "Hola Mundo";
echo substr($cadena, 5); // Salida: "Mundo" (empieza en la posición 5 y extrae hasta el final)
?>
```

### Ejemplo con strpos

``` bash
<?php
$email = "usuario@dominio.com";
$dominio = substr($email, strpos($email, "@") + 1);
echo $dominio; // Salida: "dominio.com"
?>
```
