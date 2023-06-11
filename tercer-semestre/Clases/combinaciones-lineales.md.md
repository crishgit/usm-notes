## Combinación lineal:
Son sumas de vectores de la forma $s\vec{v_1} + t{v_2}$ para un vector $v_1$ y un vector $v_2$.

Esto significa que $s\vec{v_1} + t{v_2}$ es el conjunto de todos los vectores del plano
formados por los vectores $\vec{v_1}$ y $\vec{v_2}$ dado todos los valores posibles de $s$ y $t$.

Dicho de otra manera:
El vector $\vec{U}$ forma un plano con el vector $\vec{V}$ a través de la combinación lineal de $\vec{U}$ y $\vec{V}$.
El resultado de esa combinación lineal son todos los vectores del plano formado por $\vec{U}$ y $\vec{V}$.
Por tanto, hacer la combinación lineal: $s\vec{U} + t\vec{V}$ nos da como un resultado un vector del plano (dados todos los valores posibles de $s$ y $t$).

#### Vector que pertenece a un plano 
Si queremos saber si un vector $\vec{W}$ pertenece a un plano formado por los vectores $\vec{U}$ y $\vec{V}$, debemos hacer la combinación lineal de $\vec{U}$ y $\vec{V}$ y ver si el resultado es igual a $\vec{W}$.
Es decir, si $\vec{W} = s\vec{U} + t\vec{V}$, entonces $\vec{W}$ pertenece al plano formado por $\vec{U}$ y $\vec{V}$.

## Vectores Paralelos:
Vectores paralelos son vectores que tienen la misma dirección, es decir, que tienen la misma pendiente. Se encuentran sobre la misma recta.
Para que un vector $\vec{V_1}$ sea paralelo a un vector $\vec{V_2}$, se debe tener que $\vec{V_2} = K\vec{V_1}$, por tanto, quedamos con el siguiente sistema de ecuaciones:

$$
\begin{cases}
    x_2 = Kx_1 \\
    y_2 = Ky_1
\end{cases}
$$
$$
\begin{cases}
    K = \frac{x_2}{x_1} \\
    K = \frac{y_2}{y_1}
\end{cases}
$$
$$ K = \frac{x_2}{x_1} = \frac{y_2}{y_1}$$
Y donde $K$ es un número real.

#### Obtener un vector paralelo a otro
Por tanto, para buscar un vector paralelo a otro, se debe buscar un número $K$ que cumpla con el sistema de ecuaciones.
