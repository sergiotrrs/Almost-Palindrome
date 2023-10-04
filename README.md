# Especificación del Programa Java: Verificador de Casi Palíndromos

## Objetivo

El objetivo de este programa en Java es desarrollar una función que determine si una palabra es casi un palíndromo. Una palabra es casi un palíndromo si se puede convertir en un palíndromo al cambiar **solo una** letra. La función debe devolver `true` si la palabra es casi un palíndromo y `false` en caso contrario.

## Requisitos

1. Crear una función llamada `isAlmostPalindrome` que tome una cadena de texto como parámetro y verifique si es casi un palíndromo.

2. La función debe considerar las siguientes condiciones para que una palabra sea casi un palíndromo:
   - Debe ser posible convertir la palabra en un palíndromo cambiando **solo una** letra.
   - Los espacios y la capitalización de las letras no deben considerarse al verificar la condición anterior.

3. Implementar la lógica necesaria para determinar si la palabra cumple con los requisitos mencionados.

4. Crear un programa principal en Java que solicite al usuario una palabra y llame a la función `isAlmostPalindrome` para verificar si es casi un palíndromo.

5. Mostrar el resultado en la pantalla indicando si la palabra es casi un palíndromo o no.

## Ejemplos

- Si el usuario ingresa la palabra "Oso", el programa debe mostrar "false" ya que "Oso" es un palíndromo y no necesita modificaciones.

- Si el usuario ingresa la palabra "Ver", el programa debe mostrar "true" ya que se puede convertir en un palíndromo cambiando la "y" por una "v" para obtener "vev".

- Si el usuario ingresa la palabra "Hola", el programa debe mostrar "false" ya que no es posible convertirla en un palíndromo cambiando solo una letra.

- Si el usuario ingresa la palabra "Ocho", el programa debe mostrar "true" ya que se puede convertir en un palíndromo cambiando la "h" por una "c" para obtener "occo".

- Si el usuario ingresa la palabra "Veronica", el programa debe mostrar "false" ya que no es posible convertirla en un palíndromo cambiando solo una letra.

- Si el usuario ingresa la frase "Anita lavó la tina", el programa debe mostrar "true" ya que se puede convertir en un palíndromo al cambiar la "ó" por la "a" para obtener "Anita lava la tina".

## Observaciones

- Las letras con acentos o diacríticos (como "á", "é", "í", "ó", "ú") deben considerarse equivalentes a sus versiones sin acentos al realizar las comparaciones.

- Se recomienda utilizar las funciones y métodos de Java para manipular cadenas de texto y caracteres.

- El programa debe ser interactivo y permitir al usuario ingresar palabras o frases para su verificación.

- Puedes agregar funciones auxiliares según sea necesario para implementar la lógica de verificación.

Este programa ayudará a determinar si una palabra o frase es casi un palíndromo, lo que puede ser útil en aplicaciones relacionadas con el procesamiento de texto y la detección de patrones.
