## Método de Gauss-Jordan
Aplicaremos operaciones elementales a las filas del sistema de ecuaciones lineales para obtener una matriz que sea $0$ en todos los elementos debajo de la diagonal principal, en el caso de un triángulo inferior. En el caso de un triángulo superior, $0$ en los elementos por encima de la diagonal principal.

##### Ejemplo
Dado el sistema de ecuaciones:
$$\begin{cases}
a + b + c + d = 6 \\
3a + 2b + c + 0d = 5 \\
2a + b + 0c + 0d = 1 \\
a + 2b + 3c + 4d = 7
\end{cases}$$

1) Volvemos $0$ la primera columna por debajo de la diagonal principal con las siguientes operaciones:
$$\begin{cases}
(a_2 - 3a_1) \rightarrow a_2 \\
(a_3 - 2a_1) \rightarrow a_3 \\
(a_4 - a_1) \rightarrow a_4 \\
\end{cases}$$

$$\begin{cases}
a + b + c + d = 6 \\
0a - b - 2c - 3d = -13 \\
0a - b - 2c - 2d = -11 \\
0a + b + 2c + 3d = 1
\end{cases}$$

2) Volvemos $0$ la segunda columna por debajo de la diagonal principal con las siguientes operaciones:
$$\begin{cases}
(a_3 - a_2) \rightarrow a_3 \\
(a_4 + a_2) \rightarrow a_4 \\
\end{cases}$$

$$\begin{cases}
a + b + c + d = 6 \\
0a - b - 2c - 3d = -13 \\
0a + 0b + 0c + d = -24 \\
0a + 0b + 0c + d = -12
\end{cases}$$

3) La última fila es un absurdo, por lo que el sistema no tiene solución.


## Por Matriz Inversa 
Para un sistema de ecuaciones $n \times n$, podemos escribirlo como $AX = B$ donde:
- $A$ es la matriz de coeficientes
- $X$ es el vector de incógnitas 
- $B$ es el vector de términos independientes. 

Si $A$ es invertible, entonces:
$$A^{-1} \times AX = A^{-1} \times B$$
<center> Simplificando: </center>

$$X = A^{-1} \times B$$


