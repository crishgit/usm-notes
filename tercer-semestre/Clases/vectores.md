# Definición
- Par ordenados de puntos
- Poseen direción y sentido
- Poseen magnitud
- Están definidos en una dimensión

# Notación
Se representan de la forma **$\vec{A}$** en el caso del vector **A**, con el vector en mayúscula y las componentes en minúsculas de la forma **a<sub>n**
- Si el vector es de posición (respecto al origen), se representan de la forma **$\vec{A} = (a_1, a_2)$**
- Si el vector no es respecto al origen, se representan de la forma **$\vec{A}:[a_1, a_2]$**

# Operaciones
#### Definir vectores en base a dos vectores
- Dados **$\vec{A} = (a_1, a_2)$** y **$\vec{B} = (b_1, b_2)$** se busca el vector **$\vec{AB}$**
- **$\vec{AB}: \vec{B} - \vec{A} : [(b_1 - a_1), (b_2 - a_2)]$**

#### Módulo de un vector 
Dado **$\vec{A} = (a_1, a_2)$** se busca el módulo de **$\vec{A}$**
- **$|\vec{A}| = d_{0A} = \sqrt{a_1^2 + a_2^2}$**
La notación **$d_{0A}$** significa la distancia entre el origen y el punto **$A$** (el cual vendría a ser su distancia si el vector parte del origen).

En el caso de n dimensiones:
- **$|\vec{A}| = \sqrt{a_1^2 + a_2^2 + a_3^2 + ... + a_n^2}$**

#### Ángulo entre vectores
Dado **$\vec{A} = (a_1, a_2)$** y **$\vec{B} = (b_1, b_2)$** se busca el ángulo **$\theta$** entre **$\vec{A}$** y **$\vec{B}$**
- **$
cos(\theta) = 
\frac{\vec{A} \cdot \vec{B}}{|\vec{A}| |\vec{B}|} 
$**
- **$
\theta =
arccos(\frac{\vec{A} \cdot \vec{B}}{|\vec{A}| |\vec{B}|})
$**
**$\theta$** es el arcoseno del producto escalar de ambos vectores dividido por el producto de sus módulos.


#### Suma de vectores
Dado **$\vec{A} = (a_1, a_2)$** y **$\vec{B} = (b_1, b_2)$** se busca **$\vec{A} + \vec{B}$**
- **$\vec{A} + \vec{B} = (a_1 + b_1, a_2 + b_2)$**
(Se suman las componentes de cada vector, requiere que ambos vectores sean de la misma dimensión)

#### Producto de un vector por un escalar
Se efectúa multiplicando cada componente del vector por el escalar. Esto provoca que solo se altere su magnitud. El caso especial son los números negativos, que colocan sentido y dirección opuesto.
- **$k\vec{A} = (ka_1, ka_2)$**
- **$-k\vec{A} = (-ka_1, -ka_2)$**
- Nótese que en este caso, **$k$** es un escalar, no un vector. Además, el módulo de **$k\vec{A}$** es igual al módulo de **$-k\vec{A}$**

#### Producto Escalar (de dos vectores)
El producto escalar de dos vectores es una operación algebraica que toma dos vectores y retorna un escalar.
Se puede calcular de dos maneras (ejemplos en el caso de dos dimensiones):
1) Multiplicando el módulo de ambos vectores por el coseno del ángulo que forman
**$\vec{A} \cdot \vec{B} = |\vec{A}| |\vec{B}| cos(\theta)$**

2) Sumando el producto de las componentes correspondientes de ambos vectores
**$\vec{A} \cdot \vec{B} = a_1b_1 + a_2b_2$**

#### Producto Vectorial o Producto Cruz (de dos vectores)
El producto vectorial de dos vectores es una operación algebraica que toma dos vectores y retorna un vector que tiene dirección perpendicular a ambos vectores.

Se calcula a partir de la determinante de una matriz de 3x3, donde la primera fila son los vectores unitarios **$\hat{i}$**, **$\hat{j}$** y **$\hat{k}$**, la segunda fila son las componentes del primer vector y la tercera fila son las componentes del segundo vector.

**$
\vec{A} \times \vec{B} = 
\begin{vmatrix} 
    \hat{i} & \hat{j} & \hat{k} \\ 
    a_1 & a_2 & a_3 \\
    b_1 & b_2 & b_3 
\end{vmatrix} = 
\hat{i} \begin{vmatrix} a_2 & a_3 \\ b_2 & b_3 \end{vmatrix} -
\hat{j} \begin{vmatrix} a_1 & a_3 \\ b_1 & b_3 \end{vmatrix} +
\hat{k} \begin{vmatrix} a_1 & a_2 \\ b_1 & b_2 \end{vmatrix} =
(a_2b_3 - a_3b_2) \hat{i}  -
(a_1b_3 - a_3b_1) \hat{j} +
(a_1b_2 - a_2b_1) \hat{k} 
$**

# Vectores Especiales
#### Vector Nulo
Inicia y termina en el origen. Por ejemplo **$\vec{0} = (0, 0)$**

#### Vector Unitario
Tiene magnitud 1. Por ejemplo:
- **$\hat{A} = \frac{\vec{A}}{|\vec{A}|}$**
- **$\hat{j} = (0,1)$**, donde **$|\hat{j}| = 1$**, vector unitario en el eje **$y$**
- **$\hat{i} = (1,0)$**, donde **$|\hat{i}| = 1$**, vector unitario en el eje **$x$**
- **$\hat{S} = (cos(\theta), sen(\theta) )$**, donde **$|\hat{S}| = 1$**, vector unitario en el eje **$S$**

#### Vector Opuesto
Es el vector que tiene la misma magnitud pero sentido contrario. Por ejemplo:
- **$\vec{A} = (a_1, a_2)$**
- **$\vec{A'} = -\vec{A} = (-a_1, -a_2)$**

Y se cumplen las propiedades:
- **$|\vec{A}| = |\vec{A'}|$**
- **$\vec{A} + \vec{A'} = \vec{0}$**

#### Vector de Posición 
Es el vector que va desde el origen hasta un punto. Por ejemplo:
- **$\vec{A} = (a_1, a_2)$**


# Fuentes:
[matiii-espacios-vectoriales.pptx](../../laminas-profesor/matiii-espacios-vectoriales.pptx)
