# Definición
Un espacio vectorial es un conjunto de objetos llamados vectores contemplan dos operaciones básicas, suma entre ellos y multiplicación por escalar. Los vectores y los escalares deben cumplir ciertas propiedades que hacen que las operaciones sean consistentes y útiles

Los espacios vectoriales son muy importantes en álgebra lineal porque permiten estudiar propiedades generales de los vectores sin importar su naturaleza específica o su representación. Por ejemplo, se puede definir el concepto de dimensión, base, independencia lineal y combinación lineal para cualquier espacio vectorial.

Un ejemplo de espacio vectorial es el conjunto de todos los puntos en el plano cartesiano $\mathbb{R}^2$.

**Los axiomas de los espacios vectoriales son:**
**1. Cerradura bajo la suma**:
si $u$ y $v$ son vectores en $V$, entonces $u + v$ está en $V$.
**2. Asociatividad de la suma:**
para todo $u$, $v$ y $w$ en $V$, $(u + v) + w = u + (v + w)$.
**3. Existencia del vector cero:**
hay un vector $0$ en $V$ tal que $u + 0 = u$ para todo $u$ en $V$.
**4. Existencia del opuesto:**
para cada $u$ en $V$, hay un vector $-u$ en $V$ tal que $u + (-u) = 0$.
**5. Conmutatividad de la suma:**
para todo $u$ y $v$ en $V$, $u + v = v + u$.
**6. Cerradura bajo la multiplicación por escalar:** 
si $c$ es un escalar y $u$ es un vector en $V$, entonces $cu$ está en $V$.
**7. Asociatividad de la multiplicación por escalar:** 
para todo $c$ y $d$ escalares y todo $u$ en $V$, $(cd)u = c(du)$.
**8. Identidad multiplicativa:** 
para todo vector $u$ en V, 1u = u.
**9. Distributividad de la suma con respecto a la multiplicación por escalar:**
para todo c y todo u y v en V, c(u + v) = cu + cv.
**10. Distributividad de la suma con respecto a la multiplicación por escalar:**
para todo c y d escalares y todo u en V, (c + d)u = cu + du.

Espero que esto te ayude.

# Base de un Espacio Vectorial 
Se define como base de un espacio vectorial a un conjunto de vectores linealmente independientes tales que a partir de una combinación lineal de ellos se puede generar cualquier vector de ese espacio vectorial.

Un subconjunto finito de vectores se llama base si los vectores que lo forman son linealmente independientes y forman un sistema generador del espacio. Con sistema generador nos referimos a que puede generar cualquier vector de ese espacio.

La base es importante porque nos permite pensar en cualquier espacio vectorial "como si fuera F n" y nos permite pasar de un espacio vectorial a otro mediante transformaciones lineales.

