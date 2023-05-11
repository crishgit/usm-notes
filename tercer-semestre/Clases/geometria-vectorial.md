# Recta Vectorial
Es el lugar geométrico de una serie continua de puntos sin desviaciones suaves ni ángulos.
##### Ecuación vectorial
$$
\vec{r} = t(\vec{m}) + \vec{r}_0
$$

##### Ecuación paramétrica
$$
\begin{cases}
r_x = m_x t + r_{0x} \\
r_y = m_y t + r_{0y} \\
r_z = m_z t + r_{0z}
\end{cases}
$$
Proviene de la igualdad de la ecuación vectorial, donde $t$ es un parámetro real:
$$
\vec{r} = t(\vec{m}) + \vec{r}_0 
\quad\quad\Rightarrow
\begin{pmatrix} r_x \\ r_y \\ r_z \end{pmatrix} =
t \begin{pmatrix} m_x \\ m_y \\ m_z \end{pmatrix} +
\begin{pmatrix} r_{0x} \\ r_{0y} \\ r_{0z} \end{pmatrix}
\quad\quad\Rightarrow
\begin{pmatrix} r_x \\ r_y \\ r_z \end{pmatrix} =
\begin{pmatrix} m_x t + r_{0x} \\ m_y t + r_{0y} \\ m_z t + r_{0z} \end{pmatrix}
$$

##### Ecuación continua
$$
\frac{r_x - r_{0x}}{m_x} = \frac{r_y - r_{0y}}{m_y} = \frac{r_z - r_{0z}}{m_z}
$$
Proviene de la igualdad de la ecuación paramétrica, donde $t$ es un parámetro real
$$
\begin{cases}
r_x = m_x t + r_{0x} \\
r_y = m_y t + r_{0y} \\
r_z = m_z t + r_{0z}
\end{cases}
\quad\quad\Rightarrow
\begin{cases}
\frac{r_x - r_{0x}}{m_x} = t \\
\frac{r_y - r_{0y}}{m_y} = t \\
\frac{r_z - r_{0z}}{m_z} = t 
\end{cases}
$$

##### Fórmulas Línea
$$
\vec{r} = t(\vec{m}) + \vec{r}_0 \\
$$
$$
\begin{cases}
r_x = m_x t + r_{0x} \\
r_y = m_y t + r_{0y} \\
r_z = m_z t + r_{0z}
\end{cases}
$$
&nbsp
$$
\frac{r_x - r_{0x}}{m_x} = 
\frac{r_y - r_{0y}}{m_y} =
\frac{r_z - r_{0z}}{m_z}
$$

&nbsp
&nbsp
# Plano vectorial
Es el lugar geométrico de los puntos que forman una superficie. 

**Ecuación Vectorial:** $\vec{AX} \cdot \vec{N} = 0$
**Ecuación General:** $\vec{N} \cdot \vec{X} = \vec{N} \cdot \vec{A}$
    **Esa ecuación se puede escribir como:** 
    $$ n_1x + n_2y + n_3z = n_1a_1 + n_2a_2 + n_3a_3 $$
Donde $\vec{N}$ es el vector normal al plano, $\vec{A}$ es un punto del plano y $\vec{X}$ es un punto cualquiera del plano.
<center> *Un vector normal al plano es perpendicular a todos los vectores del plano. </center>

**Ecuación Paramétrica:**
$$
\vec{AX} = \alpha \vec{AB} + \beta \vec{AC}
$$
$$
\begin{cases}
x = a_1 + \alpha (b_1 - a_1) + \beta (c_1 - a_1) \\
y = a_2 + \alpha (b_2 - a_2) + \beta (c_2 - a_2) \\
z = a_3 + \alpha (b_3 - a_3) + \beta (c_3 - a_3)
\end{cases}
$$
Donde $\vec{A}$, $\vec{B}$ y $\vec{C}$ son puntos del plano y $\vec{X}$ es un punto cualquiera del plano.

** Ecuación Segmentaria: ** Dado $\vec{A}(a_1,0,0)$ y $\vec{B}(0,b_2,0)$ y $\vec{C}(0,0,c_3)$ y $\vec{N}$ un vector perpendicular al plano?
$$
\vec{N} = \vec{AB} \times \vec{AC}
$$
$$
\Rightarrow
$$
$$
\frac{x}{a_1} + \frac{y}{b_2} + \frac{z}{c_3} = 1 
$$

&nbsp
&nbsp
&nbsp
&nbsp
&nbsp
# Resumen de Fórmulas
##### Línea
**<center> Vectorial </center>**
$$
\vec{r} = t(\vec{m}) + \vec{r}_0 \\
$$
&nbsp
**<center> Paramétrica </center>**
$$
\begin{cases}
r_x = m_x t + r_{0x} \\
r_y = m_y t + r_{0y} \\
r_z = m_z t + r_{0z}
\end{cases}
$$
&nbsp
**<center> Continua </center>**
$$
\frac{r_x - r_{0x}}{m_x} =
\frac{r_y - r_{0y}}{m_y} =
\frac{r_z - r_{0z}}{m_z}
$$

&nbsp
&nbsp
##### Plano 
**<center> Vectorial </center>**
$$
\vec{AX} \cdot \vec{N} = 0
$$
&nbsp
**<center> General </center>**
$$
\vec{N} \cdot \vec{X} = \vec{N} \cdot \vec{A}
$$
&nbsp
**<center> Paramétrica </center>**
$$
\vec{AX} = \alpha \vec{AB} + \beta \vec{AC}
$$
$$
\begin{cases}
x = a_1 + \alpha (b_1 - a_1) + \beta (c_1 - a_1) \\
y = a_2 + \alpha (b_2 - a_2) + \beta (c_2 - a_2) \\
z = a_3 + \alpha (b_3 - a_3) + \beta (c_3 - a_3)
\end{cases}
$$
&nbsp
**<center> Segmentaria </center>**
$$
\vec{N} = \vec{AB} \times \vec{AC}
$$
$$
\frac{x}{a_1} + \frac{y}{b_2} + \frac{z}{c_3} = 1 
$$
