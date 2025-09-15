### Passo a Passo — Regra de Cramer  

---

#### 1. Matriz dos coeficientes  

Para o sistema  

$$
\begin{cases}
a_{11}x + a_{12}y + a_{13}z = b_1\\
a_{21}x + a_{22}y + a_{23}z = b_2\\
a_{31}x + a_{32}y + a_{33}z = b_3
\end{cases}
$$  

definimos  

$$
A=
\begin{bmatrix}
a_{11}&a_{12}&a_{13}\\
a_{21}&a_{22}&a_{23}\\
a_{31}&a_{32}&a_{33}
\end{bmatrix},
\qquad
\mathbf{b}=
\begin{bmatrix}
b_1\\ b_2\\ b_3
\end{bmatrix}.
$$  

---

#### 2. Determinante principal  

$$
\Delta=\det(A).
$$  

Se $\Delta=0$, o sistema não possui solução única.

---

#### 3. Matrizes auxiliares  

Substitua **apenas a coluna correspondente** por $\mathbf b$ (em sistemas $2\times2$ formam-se só $A_x$ e $A_y$):

$$
A_x=
\begin{bmatrix}
\color{orange}{b_1} & a_{12} & a_{13}\\
\color{orange}{b_2} & a_{22} & a_{23}\\
\color{orange}{b_3} & a_{32} & a_{33}
\end{bmatrix},\qquad
A_y=
\begin{bmatrix}
a_{11} & \color{orange}{b_1} & a_{13}\\
a_{21} & \color{orange}{b_2} & a_{23}\\
a_{31} & \color{orange}{b_3} & a_{33}
\end{bmatrix},\qquad
A_z=
\begin{bmatrix}
a_{11} & a_{12} & \color{orange}{b_1}\\
a_{21} & a_{22} & \color{orange}{b_2}\\
a_{31} & a_{32} & \color{orange}{b_3}
\end{bmatrix}.
$$
  

---

#### 4. Determinantes auxiliares  

$$
\Delta_x=\det(A_x),\qquad
\Delta_y=\det(A_y),\qquad
\Delta_z=\det(A_z).
$$  

---

#### 5. Cálculo das incógnitas  

$$
x=\frac{\Delta_x}{\Delta},\qquad
y=\frac{\Delta_y}{\Delta},\qquad
z=\frac{\Delta_z}{\Delta}.
$$  

---

### Exemplo — Sistema 2 × 2  

$$
\begin{cases}
2x + 3y = 5\\
x - 4y = -2
\end{cases}
$$  

1. $$A=\begin{bmatrix} 2&3\\ 1&-4 \end{bmatrix}\;\;\Rightarrow\;\;\Delta = 2(-4) - 3(1) = -11.$$

2. $$A_x=\begin{bmatrix} 5&3\\ -2&-4 \end{bmatrix}\;\;\Rightarrow\;\;\Delta_x = 5(-4) - 3(-2) = -14.$$

   $$A_y=\begin{bmatrix} 2&5\\ 1&-2 \end{bmatrix}\;\;\Rightarrow\;\;\Delta_y = 2(-2) - 5(1) = -9.$$

3. $$
x = \frac{\Delta_x}{\Delta} = \frac{-14}{-11} = \frac{14}{11},\qquad
y = \frac{\Delta_y}{\Delta} = \frac{-9}{-11} = \frac{9}{11}.
$$  

---

#### Observações  

- A Regra de Cramer vale somente se $\Delta\neq0$.  
- Para matrizes maiores, o custo de $\det(A)$ cresce rapidamente; métodos como eliminação de Gauss ou decomposição LU são mais eficientes na prática.
