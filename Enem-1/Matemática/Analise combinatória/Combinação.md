## 🎲 Combinação - Agrupamentos sem importar a ordem

**Definição:**

A combinação é usada quando queremos **escolher elementos** de um conjunto, **sem se importar com a ordem**.

A fórmula da combinação é:

$$
C(n, k) = \binom{n}{k} = \frac{n!}{k! \cdot (n - k)!}
$$
ou
$$
C^p_{n} = \frac{n!}{k! \cdot (n - k)!}
$$

---

**Exemplo:**

Uma escola vai formar uma equipe com **3 alunos** entre **10 disponíveis**.  
De quantas formas diferentes essa equipe pode ser formada?

### Resolução:

Como **a ordem dos alunos não importa**, usamos **combinação**:

$$
\binom{10}{3} = \frac{10!}{3! \cdot (10 - 3)!} = \frac{10 \cdot 9 \cdot 8}{3 \cdot 2 \cdot 1} = \boxed{120}
$$

Portanto, há **120 maneiras** de formar a equipe.

---

**Quando usar combinação?**

Use combinação quando:
- A ordem dos elementos **não importa**
- Está formando **grupos, comissões, equipes, seleções**, etc.

Ex: selecionar 5 livros para ler entre 12 → combinação.  
Ex: sortear 2 pessoas para prêmio sem ordem → combinação.


---
