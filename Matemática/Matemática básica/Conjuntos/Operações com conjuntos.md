
## União
- **Definição:** A união de dois conjuntos $A$ e $B$, denotada por $A \cup B$, é o conjunto formado por todos os elementos que pertencem a $A$, a $B$ ou a ambos.
- **Exemplo:**  
  - Se $A = \{1, 2, 3\}$ e $B = \{3, 4, 5\}$, então:  
    $A \cup B = \{1, 2, 3, 4, 5\}$

## Interseção
- **Definição:** A interseção de dois conjuntos $A$ e $B$, denotada por $A \cap B$, é o conjunto composto pelos elementos que estão presentes em ambos.
- **Exemplo:**  
  - Se $A = \{1, 2, 3\}$ e $B = \{3, 4, 5\}$, então:  
    $A \cap B = \{3\}$

## Adição dos Conjuntos (União Disjunta e Soma de Cardinalidades)
- **Conceito:** Embora a notação $A + B$ não seja padrão na teoria dos conjuntos, há uma ideia relacionada à união disjunta de conjuntos.
- **União Disjunta:**  
  - Quando $A$ e $B$ são disjuntos (isto é, $A \cap B = \varnothing$), a união disjunta possui cardinalidade dada por:  
    $$|A \cup B| = |A| + |B|$$
- **Caso Geral:**  
  - Se $A$ e $B$ não são disjuntos, a soma das cardinalidades é ajustada pela interseção:  
    $$|A \cup B| = |A| + |B| - |A \cap B|$$

## Subtração dos Conjuntos (Diferença)
- **Definição:** A subtração (ou diferença) de conjuntos, denotada por $A - B$, é o conjunto dos elementos que pertencem a $A$ mas não a $B$. Formalmente:  
  $$A - B = \{x \in A \mid x \notin B\}$$
- **Exemplo:**  
  - Se $A = \{1, 2, 3, 4\}$ e $B = \{2, 4\}$, então:  
    $$A - B = \{1, 3\}$$
==***Lembre-se A-B não é igual a B-A***==


## Complemento
- **Definição:** O complemento de um conjunto $A$, denotado por $A^c$, é o conjunto de todos os elementos do conjunto universo $U$ que não pertencem a $A$.
- **Notação:**  
  $A^c = \{x \in U \mid x \notin A\}$
- **Exemplo:**  
  - Se o conjunto universo é $U = \{1, 2, 3, 4, 5\}$ e $A = \{2, 4\}$, então:  
    $A^c = \{1, 3, 5\}$