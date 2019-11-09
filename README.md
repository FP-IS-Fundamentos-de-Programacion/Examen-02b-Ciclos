# Examen 01 Sentencias condicionales

<center>
<img src="img/js.png" width="400" title="CSS3">
</center>

## Instrucciones

Utilizando HTML+JS resuelva los siguientes problemas.

**NOTAS:**

1. Para el ingreso de datos todos los programas deberán utilizar un formulario HTML.
2. Los resultados deberán mostrarse dentro de un elemento HTML ó en una ventana tipo alert.
3. NO es necesario agregar estilos (css)
4. Si así lo prefiere, puede resolver todos los ejercicios en un mismo documento HTML y JS siempre y cuando quede claro en donde termina un ejercicio y en donde inicia el siguiente.
5. Todos los mensajes de salida deberán ser lo suficientemente claros.
6. Puede utilizar el ciclo de su preferencia

### (4 Puntos) Problema 1 Ciclo simple

Programe una página web que contenga un formulario en la que el usuario pueda capturar dos números. El programa generará una lista empezando en el número 1 y terminando en el número que el usuario capturo en la primer caja del formulario. El conteo se realizará en intervalos de acuerdo a lo capturado en la segunda caja del formulario. Por ejemplo:

- Número 1: 10
- Número 2: 3

El resultado debe ser:
1, 4, 7, 10

### (4 Puntos) Problema 2 Múltiplos de 3

Programe que una página que permita evaluar una serie de números para ver si son múltiplos de 3. La página contará con un formulario en el cual el usuario podrá capturar el número en el que iniciará el análisis y otro caja para el número en el que terminará el análisis. Al presionar un botón se generará una tabla como la que se muestra en el siguiente ejemplo:

- Número 1: 7
- Numero 2: 15
- Resultado:

|     |             |      |      |      |
| --- | :---------: | ---: | ---: | ---: |
| 7   | múltiplo de |    3 |    = |   No |
| 8   | múltiplo de |    3 |    = |   No |
| 9   | múltiplo de |    3 |    = |   Sí |

...

|     |             |      |      |      |
| --- | :---------: | ---: | ---: | ---: |
| 14  | múltiplo de |    3 |    = |   No |
| 15  | múltiplo de |    3 |    = |   Sí |

Puede utilizar el elemento que prefiera: `list, select o table` para mostrar el resultado.

### (2 Puntos) Problema 4 El límite

Escribir una página web que mediante un formulario permita capturar dos números. El primero indicará el máximo de números que se pueden capturar, el segundo indicará el máximo de la suma que se puede alcanzar. El programa empezará a solicitar números al usuario utilizando `propmt` y terminará cuando se alcance el máximo de números capturados (primer número), o cuando la suma de los números capturados rebase el máximo de la cantidad indicada en el segundo número. Por ejemplo:

- Numero 1: 5
- Número 2: 10

Números capturados:

- 5
- 3
- 9

El programa terminó por que la suma rebasó la cantidad máxima de 10 (número 2).

Puede utilizar el elemento que prefiera: `list, select o table` para mostrar el resultado.
