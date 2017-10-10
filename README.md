## **CIFRADO CÉSAR**

### *OBJETIVOS:*

- Crear una web que pida, por medio de un prompt(), una frase al usuario y devuelva el mismo mensaje encriptado según el algoritmo de Cifrado César con el parámetro de desplazamiento de 33 espacios hacia la derecha.

#### *EJEMPLO:*

-Texto original: ABCDEFGHIJKLMNOPQRSTUVWXYZ

-Texto codificado: HIJKLMNOPQRSTUVWXYZABCDEFG

#### *INDICACIONES:*

1. Primero, debemos pedir una fras al usuario, por medio de un *prompt()*.

2. Crear dos variables: *sentence* para guardar la frase que el usuario ha ingresado; y *newSentence* para guardar la frase ya convertida con el *Cifrado César*.

3. Crear una función llamada **cipher**, cuyos parámetros serán las variables que hemos creado (*sentece, newArray*).

4. Tenemos que recorrer la frase, usando un **for()**.

5. Tenemos que hallar qué numero nrepresenta (i) en **ASCII**; y paraello usaremos **charCodeAt()**.

6. Una vez hallado el número de la letra **ASCII**, aplicaremos la siguiente fórmula.

##### *( x - 65 - n) % 26 + 65*.

    -Donde n será igual al valor fijo.

7. Almacenamos el resultado en newSentence y mostramos el resultado con **String.fromCode()**.


