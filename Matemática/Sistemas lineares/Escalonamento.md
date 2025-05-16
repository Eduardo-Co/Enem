### Passo a Passo — Eliminação de Gauss  

---

#### 1. Matriz aumentada  

Para o sistema linear  

$$
A\mathbf x = \mathbf b
$$  

constrói-se a matriz aumentada  

$$
\bigl[A \;|\; \mathbf b\bigr].
$$  

---

#### 2. Operações elementares de linha  

1. **Troca** $L_i \leftrightarrow L_j$  
2. **Multiplica** $L_i \gets k\,L_i,\;k\neq0$  
3. **Soma** $L_j \gets L_j + k\,L_i$  

Essas operações **não alteram** o conjunto de soluções.

---

#### 3. Escalonamento (eliminação direta)  

Para cada coluna-pivô $k$:

1. Escolha um **pivô** não-nulo (troque linhas se necessário).  
2. Zere todos os elementos **abaixo** do pivô usando  

   $$
   L_j \gets L_j \;-\; \frac{a_{jk}}{a_{kk}}\,L_k.
   $$  

Ao final obtém-se uma matriz **triangular superior** $U$ (ou forma **escalonada**).

---

#### 4. Diagnóstico do sistema  

* Linha do tipo $[0\,0\,\dots\,0 \;|\; c\neq0]$  $\Rightarrow$ **sistema impossível**.  
* Se $\operatorname{rank}(A) < \operatorname{rank}([A\,|\,b])$  $\Rightarrow$ impossível.  
* Se $\operatorname{rank}(A) < n$ e não há inconsistência  $\Rightarrow$ **infinitas soluções** (variáveis livres).

---

#### 5. Retrosubstituição  

Com $U\mathbf x = \mathbf c$ obtido:

$$
\begin{aligned}
x_n &= \frac{c_n}{u_{nn}},\\[2pt]
x_{n-1} &= \frac{c_{\,n-1}-u_{\,n-1,n}\,x_n}{u_{\,n-1,n-1}},\\
&\;\;\vdots
\end{aligned}
$$

---

#### 6. (Opcional) Gauss-Jordan  

Após zerar **abaixo** dos pivôs, zere também **acima** deles.  
Chega-se à forma reduzida  

$$
\bigl[I \;|\; \mathbf x\bigr],
$$  

onde $\mathbf x$ já contém a solução.

---

### Exemplo — Sistema $3 \times 3$  

$$
\begin{cases}
2x + y - z = 8\\
-3x - y + 2z = -11\\
-2x + y + 2z = -3
\end{cases}
$$  

Matriz aumentada inicial  

$$
\left[
\begin{array}{rrr|r}
 2 & 1 & -1 &  8\\
-3 & -1&  2 & -11\\
-2 & 1 &  2 & -3
\end{array}
\right]
$$  

1. $L_2 \gets L_2 + \tfrac32\,L_1,\;\;L_3 \gets L_3 + L_1$

$$
\left[
\begin{array}{rrr|r}
 2 & 1 & -1 &  8\\
 0 & \tfrac12 & \tfrac12 & 1\\
 0 & 2 & 1 & 5
\end{array}
\right]
$$  

2. Pivô da 2ª coluna: $L_3 \gets L_3 - 4\,L_2$

$$
\left[
\begin{array}{rrr|r}
2 & 1 & -1 & 8\\
0 & \tfrac12 & \tfrac12 & 1\\
0 & 0 & -1 & 1
\end{array}
\right]
$$  

Retrosubstituindo:  

$$
\begin{aligned}
z &= \frac{1}{-1} = -1,\\[4pt]
y &= \frac{1 - \tfrac12(-1)}{\tfrac12} = 3,\\[4pt]
x &= \frac{8 \;-\; 1\cdot3 \;+\; (-1)(-1)}{2} = 2.
\end{aligned}
$$  

**Solução única:** $(x,\,y,\,z) = (2,\,3,\,-1)$.

---

#### Observações finais  

* Use **pivotamento parcial** (trocar com o maior valor da coluna) para reduzir erros numéricos.  
* Complexidade computacional: $\mathcal O(n^3)$, bem mais eficiente que expandir determinantes para $n$ grande.
