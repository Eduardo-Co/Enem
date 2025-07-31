## 📦 Arranjo - Agrupamentos **com** ordem

**Definição:**

O **arranjo** é usado quando queremos **escolher e organizar elementos**, ou seja, **a ordem importa**.

A fórmula do arranjo simples é:

$$
A(n, k) = \frac{n!}{(n - k)!}
$$

---

**Exemplo:**

Um diretor precisa escolher **2 alunos** entre **5 candidatos** para ocupar **cargos diferentes** (ex: presidente e vice).  
De quantas maneiras isso pode ser feito?

### Resolução:

Como **a ordem importa** (presidente ≠ vice), usamos **arranjo**:

$$
A(5, 2) = \frac{5!}{(5 - 2)!} = \frac{5 \cdot 4 \cdot 3!}{3!} = 5 \cdot 4 = \boxed{20}
$$

Portanto, há **20 maneiras diferentes** de ocupar os cargos.

---

**Quando usar arranjo?**

Use arranjo quando:
- A ordem dos elementos **importa**
- Está atribuindo **funções, cargos, posições, senhas, sequências**

Ex: organizar 3 livros na estante entre 10 → arranjo  
Ex: criar senha de 4 dígitos distintos → arranjo
