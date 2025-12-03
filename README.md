# Fundamentos de Álgebra — Actividad #16
**Materia:** Fundamentos de álgebra  
**Alumno:** Dylan Emmanuel Mosquda Lugo
**Fecha:** 11 de noviembre de 2025

---
* ** Actividad #18
* **Materia:** Fundamentos de Álgebra
* **Tema:** [**Documentación de Ejercicios con Git Branches**]
* **Fecha:** [18/11/2025]
* **Estudiante:** [Dylan Emmanuel Mosqueda Lugo]
* **Grupo:** [1ª A]

## Objetivo de la Documentación
Documentación de los ejercicios realizados en la Actividad #16, con operaciones de matrices expresadas en formato **LaTeX**.

[En esta actividad utilize el git Branches  ]

---

### Identificación de matrices
## Ejercicios Realizados

Matriz identidad, porque la diagonal está compuestos por solo unos y los elementos fuera de la diagonal son ceros.
## Ejercicio 1 — Determinantes 2×2

$$ A =
\begin{pmatrix}
1 & 0 \\
0 & 1 \\
\end{pmatrix}
$$
---

MUESTRA
A=\begin{pmatrix}5 & 2[4pt]3 & 1\end{pmatrix},\quad
B=\begin{pmatrix}6 & 9[4pt]2 & 3\end{pmatrix},\quad
C=\begin{pmatrix}-1 & 4[4pt]2 & -5\end{pmatrix},\quad
D=\begin{pmatrix}0 & 5[4pt]-5 & 0\end{pmatrix}
$$

Calcula la suma de A y B
Cálculo de determinantes:

$$ A =
\begin{pmatrix}
1 & 2 & 3 \\
4 & 5 & 6 \\
\end{pmatrix}
$$
\det(A) = (5)(1) - (2)(3) = 5 - 6 = -1
$$

$$ B =
\begin{pmatrix}
9 & 10 & 11 \\
12 & 13 & 14 \\
\end{pmatrix}
$$
\det(B) = (6)(3) - (9)(2) = 18 - 18 = 0
$$

$$ A + B =
\begin{pmatrix}
1 + 9 & 2 + 10 & 3 + 11 \\
4 + 12 & 5 + 13 & 6 + 14 \\
\end{pmatrix}
$$
\det(C) = (-1)(-5) - (4)(2) = 5 - 8 = -3
$$

$$ A + B =
\begin{pmatrix}
10 & 12 & 14 \\
16 & 18 & 20 \\
\end{pmatrix}
$$
\det(D) = (0)(0) - (5)(-5) = 0 - (-25) = 25
$$

---
# OTRO EJERCICIO

Matriz identidad, porque la diagonal está compuestos por solo unos y los elementos fuera de la diagonal son ceros.
## Ejercicio 2 — Regla de Sarrus (3×3)

$$ A =
\begin{pmatrix}
1 & 0 \\
0 & 1 \\
$$
G=\begin{pmatrix}
1 & 0 & 2[4pt]
1 & 3 & 1[4pt]
2 & 0 & 1
\end{pmatrix}
$$
---

MUESTRA
$$
\det(G) = 1\cdot3\cdot1 + 0\cdot1\cdot2 + 2\cdot1\cdot0 ; - ; (2\cdot3\cdot2 + 1\cdot1\cdot1 + 1\cdot0\cdot0)
$$

Calcula la resta de A y B
---

$$ A =
\begin{pmatrix}
1 & 2 & 3 \\
4 & 5 & 6 \\
## Ejercicio 3 — Método de cofactores (3×3)

$$
G=\begin{pmatrix}
g_{11} & g_{12} & g_{13}[4pt]
g_{21} & g_{22} & g_{23}[4pt]
g_{31} & g_{32} & g_{33}
\end{pmatrix}
$$

$$ B =
\begin{pmatrix}
9 & 10 & 11 \\
12 & 13 & 14 \\
\end{pmatrix}
$$
\det(G) = g_{11}C_{11} - g_{12}C_{12} + g_{13}C_{13}
$$

$$ A - B =
\begin{pmatrix}
1 + 9 & 2 + 10 & 3 + 11 \\
4 + 12 & 5 + 13 & 6 + 14 \\
\end{pmatrix}
---

## Ejercicio 4 — Verificar propiedades

$$
A=\begin{pmatrix}2 & 1[4pt]1 & 3\end{pmatrix},\quad
B=\begin{pmatrix}1 & 2[4pt]3 & 1\end{pmatrix}
$$

$$ A - B =
\begin{pmatrix}
10 & 12 & 14 \\
16 & 18 & 20 \\
\end{pmatrix}
Cálculo:

$$
\det(A)=2\cdot3 - 1\cdot1 = 6-1=5
$$

$$
\det(B)=1\cdot1 - 2\cdot3 = 1-6=-5
$$

Producto (AB):

Matriz identidad, porque la diagonal está compuestos por solo unos y los elementos fuera de la diagonal son ceros.
$$
AB=\begin{pmatrix}5 & 5[4pt]10 & 5\end{pmatrix}
$$

$$ A =
\begin{pmatrix}
1 & 0 \\
0 & 1 \\
\end{pmatrix}
$$
\det(AB)=5\cdot5 - 5\cdot10 = 25 - 50 = -25
$$

Producto de determinantes:

$$
\det(A)\det(B)=5\cdot(-5)=-25
$$

---

MUESTRA
## Ejercicio 5 — Aplicación geométrica de determinantes

Calcula la multiplicación de A y B
### a) Cálculo del área con vectores

$$ A =
\begin{pmatrix}
1 & 2 & 3 \\
4 & 5 & 6 \\
\end{pmatrix}
$$
Sean los vectores:

$$ B =
\begin{pmatrix}
9 & 10 & 11 \\
12 & 13 & 14 \\
\end{pmatrix}
$$

$$ A * B =
\begin{pmatrix}
1 + 9 & 2 + 10 & 3 + 11 \\
4 + 12 & 5 + 13 & 6 + 14 \\
\end{pmatrix}
u = (3,2), \ v = (1,4)
$$

$$ A * B =
Construimos la matriz:

$$
\begin{pmatrix}
10 & 12 & 14 \\
16 & 18 & 20 \\
3 & 1 \
2 & 4
\end{pmatrix}
$$

Determinante:

Matriz identidad, porque la diagonal está compuestos por solo unos y los elementos fuera de la diagonal son ceros.
$$
\det(u,v) = 3\cdot4 - 2\cdot1 = 12 - 2 = 10
$$

Área:

$$ A =
\begin{pmatrix}
1 & 0 \\
0 & 1 \\
\end{pmatrix}
$$
---
\text{Área} = |\det(u,v)| = |10| = 10
$$

MUESTRA
### b) Determinante con orientación

Calcula la división de A por B
Sean los vectores:

$$ A =
\begin{pmatrix}
1 & 2 & 3 \\
4 & 5 & 6 \\
\end{pmatrix}
$$

$$ B =
\begin{pmatrix}
9 & 10 & 11 \\
12 & 13 & 14 \\
\end{pmatrix}
u = (4,3), \ v = (3,2)
$$

$$ A / B =
\begin{pmatrix}
1 + 9 & 2 + 10 & 3 + 11 \\
4 + 12 & 5 + 13 & 6 + 14 \\
\end{pmatrix}
$$
Construimos la matriz:

$$ A / B =
$$
\begin{pmatrix}
10 & 12 & 14 \\
16 & 18 & 20 \\
4 & 3 \
3 & 2
\end{pmatrix}
$$

Determinante:

$$
\det(u,v) = 4\cdot2 - 3\cdot3 = 8 - 9 = -1
$$

### Créditos
Área:

Area=∣det⁡(u,v)∣=∣−1∣=1

*Fin del README.*




