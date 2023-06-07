## Segundo Parcial
#### Primer Ejercicio
###### Enunciado
Determine la ecuación del plano que contiene a la recta $x = Ht$, $y = 1 + t$, $z = 2t$

**<center> Terminado </center>**

&nbsp;
&nbsp;
&nbsp;

#### Segundo Ejercicio
###### Enunciado
Si el vector velocidad para cuando $t = 0$, $\vec{v} : [0, 0, H]$ y la ecuación de la aceleración $\vec{a} : [sen(t), cos(t), -1]$. 
I) Determine la ecuación de la trayectoria 
II) Plantee la ecuación de la distancia entre los puntos $t = 0 ∧ t=t$.

###### Método de Resolución
Para resolver este ejercicio se debe integrar la ecuación de la aceleración para obtener la ecuación de la velocidad, luego se ajusta por la velocidad inicial del enunciado. Se continúa integrando la velocidad para obtener la ecuación de la trayectoria. Se termina el ejercicio planteando la ecuación de la trayectoria y de la trayectoria en los tiempos $t = 0 ∧ t=t$.

###### Solución
1) Obtenemos la ecuación de la velocidad integrando la ecuación de la aceleración
$$\vec{v} = \ \int \vec{a} dt \ = \int [sen(t), \ cos(t), \ -1] dt = [-cos(t), \ sen(t), \ -t] + \vec{C}$$

2) Ajustamos la velocidad inicial del enunciado 
$$\vec{v} : [0, \ 0, \ H] \ = [-cos(0), \ sen(0), \ -0] + \vec{C}$$
$$\vec{v} : [0, \ 0, \ H] \ = [-1, \ 0, \ 0] + \vec{C}$$
$$\vec{C} = [0, \ 0, \ H] - [-1, \ 0, \ 0]$$
$$\vec{C} = [1, \ 0, \ H]$$

&nbsp;
$$\vec{v} = [-cos(t), \ sen(t), \ -t] + [1, \ 0, \ H]$$
$$\vec{v} = [1-cos(t), \ sen(t), \ H-t]$$

3) Obtenemos la ecuación de la trayectoria integrando la ecuación de la velocidad
$$\vec{r} = \ \int \vec{v} dt \ = \int [1-cos(t), \ sen(t), \ H-t] dt = [t-sen(t), \ -cos(t), \ Ht-\frac{t^2}{2}] + \vec{C}$$

4) Planteamos la ecuación de la trayectoria
$$\vec{r} = [t-sen(t), \ -cos(t), \ Ht-\frac{t^2}{2}] + \vec{C}$$

5) Planteamos la ecuación de la trayectoria en los tiempos $t = 0 ∧ t=t$. 
** TODO: Terminar **





**<center> Terminado </center>**

&nbsp;
&nbsp;
&nbsp;
