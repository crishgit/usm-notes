# Primer Parcial
#### Ejercicio 1

#### Ejercicio 2

#### Ejercicio 3
Resolver el siguiente sistema de ecuaciones lineales por el método de matriz inversa:
$$
\begin{cases}
3x + 2y + z = 6 \\
1x + 1y - z = 3 \\
-4x + 3y + 4z = 7
\end{cases}
$$

#### Ejercicio 4
De acuerdo a la definición de un determinante, establezca para un determinante de orden $N$, el número de términos y la cantidad de factores por términos.

**Respuesta:**
El determinante se conseguirá con $N!$ términos de $N$ factores. Si $N$ es $5$, el determinante tendrá $5! = 120$ términos de $5$ factores cada uno.

# Práctica 1
Determine la distancia $d$ desde el punto $P$ hasta la recta $L_1$
![Primer Ejercicio](./imagenes/primer_parcial_primer_ejercicio.jpeg)
**Datos:**
$P(p_1, p_2, p_3)$
Un punto $S$ en la recta $L_1$: $S(s_1, s_2, s_3)$
$S$ es el punto de la recta $L_1$ más cercano a $P$.

**Respuesta:**
Nos queda que $d = \sqrt{(s_1 - p_1)^2 + (s_2 - p_2)^2 + (s_3 - p_3)^2}$
Y nos falta por conocer las coordenadas del punto $S$.
Para conocer las coordenadas del punto $S$, sabemos que al ser el punto más cercano a $P$ contenida en $L_1$, debería estar en un plano perpendicular a $L_1$ que contiene a $P$ también.

$$ L_1 = \lambda\vec{R} + \vec{A} $$
$$
\begin{cases}
x = \lambda r_1 + a_1 \\
y = \lambda r_2 + a_2 \\
z = \lambda r_3 + a_3
\end{cases}
$$
Como $S$ está en la recta, buscamos el valor de $\lambda$ que nos de el punto más cercano a $P$.
Diremos entonces, que $S(s_1, s_2, s_3)$, será tal que:
$$
\begin{cases}
s_1 = T(r_1) + a_1 \\
s_2 = T(r_2) + a_2 \\
s_3 = T(r_3) + a_3
\end{cases}
$$
Donde $T$ es el valor: 
$$ T = \frac{(p_1 - a_1)r_1 + (p_2 - a_2)r_2 + (p_3 - a_3)r_3}{r_1^2 + r_2^2 + r_3^2} $$
<center> Y se obtiene de la siguiente manera: </center>
Conocemos un punto y el vector director de la línea a la que el plano es perpendicular. 

Se puede aplicar la fórmula de planos: $\vec{R}\cdot\vec{P} = \vec{R}\cdot\vec{S}$

$$
[r_1, r_2, r_3] \cdot [p_1, p_2, p_3] = 
[r_1, r_2, r_3] \cdot [Tr_1 + a_1, Tr_2 + a_2, Tr_3 + a_3]
$$
$$
r_1p_1 + r_2p_2 + r_3p_3 = Tr_1^2 + a_1r_1 + Tr_2^2 + a_2r_2 + Tr_3^2 + a_3r_3
$$
Despejamos la T 

$$
Tr_1^2 + Tr_2^2 + Tr_3^2 = r_1p_1 + r_2p_2 + r_3p_3 - a_1r_1 - a_2r_2 - a_3r_3
$$
$$
T(r_1^2 + r_2^2 + r_3^2) = r_1p_1 + r_2p_2 + r_3p_3 - a_1r_1 - a_2r_2 - a_3r_3
$$
$$
T = \frac{r_1p_1 + r_2p_2 + r_3p_3 - a_1r_1 - a_2r_2 - a_3r_3}{r_1^2 + r_2^2 + r_3^2}
$$
Y conociendo $T$, podemos conocer las coordenadas de $S$.

**<center> Terminado </center>**

&nbsp;
&nbsp;
&nbsp;
# Práctica 2
