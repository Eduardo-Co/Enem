## Quando lidamos com **intervalos de datas** (anos, meses, dias) em contextos de **Progressão Aritmética (PA)** ou contagem discreta, é fundamental **contar o termo inicial**.

# Progressão Aritmética (PA)

- **Fórmula do termo geral:**  
    $a_n = a_1 + (n-1)\cdot r$
    
- **Soma dos termos (PA finita):**  
    $S_n = \dfrac{(a_1 + a_n)\cdot n}{2}$
    
- **Cuidado com os extremos:**  
    Sempre confira se os valores extremos devem ser incluídos na soma ($a_1$ até $a_n$).
    
- **Propriedades:**
    
    - Diferença entre dois termos consecutivos é constante ($r$).
        
    - Termos equidistantes dos extremos têm mesma soma:  
        $a_k + a_{n+1-k} = a_1 + a_n$
        
- **Termo médio:**  
    Qualquer termo é a média aritmética dos vizinhos:  
    $a_n = \dfrac{a_{n-1} + a_{n+1}}{2}$
    
- **PA de segunda ordem:**  
    Uma sequência em que as diferenças sucessivas formam uma PA.
    
- **Interpolação aritmética:**  
    Inserir $k$ termos entre $a$ e $b$ formando uma PA:  
    $r = \dfrac{b-a}{k+1}$
    

---

# Progressão Geométrica (PG)

- **Fórmula do termo geral:**  
    $a_n = a_1 \cdot q^{n-1}$
    
- **Representação gráfica:**  
    Crescimento/decrescimento exponencial; se $|q|>1$, cresce rápido; $0<|q|<1$, decresce.
    
- **Soma dos termos (PG finita):**  
    $S_n = a_1 \cdot \dfrac{q^n - 1}{q - 1}$, se $q\ne 1$
    
- **Soma da PG infinita ($|q|<1$):**  
    $S = \dfrac{a_1}{1-q}$
    
- **Termo médio:**  
    Qualquer termo é a média geométrica dos vizinhos:  
    $a_n = \sqrt{a_{n-1}\cdot a_{n+1}}$
    
- **Termos equidistantes:**  
    Produto de termos equidistantes dos extremos é igual:  
    $a_k \cdot a_{n+1-k} = a_1 \cdot a_n$
    
- **Interpolação geométrica:**  
    Inserir $k$ termos entre $a$ e $b$ formando PG:  
    $q = \sqrt[k+1]{\dfrac{b}{a}}$