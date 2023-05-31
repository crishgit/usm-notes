## Segundo Parcial
#### Primer Ejercicio
###### Enunciado
Determine la ecuación del plano que contiene a la recta $x = Ht$, $y = 1 + t$, $ z = 2t $

**<center> Terminado </center>**

&nbsp;
&nbsp;
&nbsp;

#### Segundo Ejercicio
Comentario: ¿puedo decir que $\vec{v_0} \neq \vec{v_i}$? ¿o es lo mismo? 
Respuesta: No es lo mismo, $\vec{v_0}$ es la velocidad inicial y $\vec{v_i}$ es la velocidad inicial en el contexto de la integral.
###### Enunciado
Si el vector velocidad para cuando $t = 0$, $\vec{v} : [0, 0, H]$ y la ecuación de la aceleración $\vec{a} : [sen(t), cos(t), -1]$. 
I) Determine la ecuación de la trayectoria 
II) Plantee la ecuación de la distancia entre los puntos $t = 0 ∧ t=t$.

###### Método de Resolución
Para resolver este ejercicio se debe integrar la ecuación de la aceleración para obtener la ecuación de la velocidad y luego integrar la ecuación de la velocidad para obtener la ecuación de la posición. Luego se debe plantear la ecuación de la distancia entre los puntos $t = 0 ∧ t=t$.

###### Solución
La ecuación de la velocidad se obtiene integrando la ecuación de la aceleración:
$$
\vec{v} = \int \vec{a} dt = \int [sen(t), cos(t), -1] dt = [-cos(t), sen(t), -t] + C
$$
Donde $C$ es la constante de integración y en este contexto significa $\vec{v_i}$. Podemos calcular $\vec{v_i}$ a partir de que sabemos que $\vec{v_0} =[0, 0, H] = [-cos(0), sen(0), -0] + \vec{v_i}$

Despejando $\vec{v_i}$ obtenemos $\vec{v_i} = [0, 0, H] - [-cos(0), sen(0), -0] = [1, 0, H]$
Por lo tanto la ecuación de la velocidad es:
$$
\vec{v} = [-cos(t), sen(t), -t] + [1, 0, H] = [1 - cos(t), sen(t), H - t]
$$

&nbsp;
&nbsp;
La ecuación de la posición se obtiene integrando la ecuación de la velocidad:
$$
\vec{r} = \int \vec{v} dt = \int [1 - cos(t), sen(t), H - t] dt = [t - sen(t), -cos(t), Ht - \frac{t^2}{2}] + C 
$$
Donde $C$ es la constante de integración y en este contexto significa $\vec{r_i}$.  

&nbsp;
&nbsp;
I) La ecuación de la trayectoria queda como:
$$
\vec{r} = [t - sen(t), -cos(t), Ht - \frac{t^2}{2}] + \vec{r_i}
$$

II) La ecuación de la distancia entre los puntos $t = 0 ∧ t=t$ queda como el desplazamiento:
$$
\Delta\vec{r} = [t - sen(t), -cos(t), Ht - \frac{t^2}{2}] + \vec{r_i} $$




**<center> Terminado </center>**

&nbsp;
&nbsp;
&nbsp;
