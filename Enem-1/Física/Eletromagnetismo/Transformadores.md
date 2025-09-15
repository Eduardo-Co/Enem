##  Transformadores

Transformadores **alteram a tensão** de uma corrente alternada (CA), usando o princípio da **indução eletromagnética** (Lei de Faraday).

---
###  Estrutura:

- Núcleo de ferro (canaliza o campo magnético)
- Bobina primária (entrada)
- Bobina secundária (saída)

---

###  Funcionamento:

A corrente alternada no primário gera fluxo magnético variável:

$$
\mathcal{E} = -\frac{d\Phi_B}{dt}
$$

Esse fluxo se propaga pelo núcleo e **induz uma tensão no secundário**.

---

### Relação de Transformação:

$$
\frac{V_s}{V_p} = \frac{N_s}{N_p}
$$

- $V_s$, $V_p$ → tensões secundária e primária
- $N_s$, $N_p$ → número de espiras em cada bobina

---

###  Tipos:

| Tipo                    | Condição        | Função                 |
|-------------------------|------------------|------------------------|
| Elevador                | $N_s > N_p$       | Aumenta tensão         |
| Abaixador               | $N_s < N_p$       | Reduz tensão           |

---
### Corrente Contínua (CC) não funciona:

$$
\text{Se } \frac{d\Phi_B}{dt} = 0 \Rightarrow \mathcal{E} = 0
$$

Transformadores exigem **corrente alternada (CA)** para funcionar.

---

###  Resumo:

| Conceito            | Fórmula                               | Observação                         |
|---------------------|----------------------------------------|------------------------------------|
| Lei de Faraday      | $\mathcal{E} = -\dfrac{d\Phi_B}{dt}$   | Base do funcionamento              |
| Relação espiras     | $\dfrac{V_s}{V_p} = \dfrac{N_s}{N_p}$  | Define transformação de tensão     |
| Corrente alternada  | Necessária para variação de $\Phi_B$  | Sem isso, não há indução           |