## Capacitor: conceitos-chave

Um **capacitor** é um dispositivo que **armazena carga elétrica** e, portanto, **energia potencial elétrica**. Ao fechar o circuito, ele libera essa energia na forma de corrente rápida (uso típico: flash de câmera, desfibrilador).

### Capacitância
- Definição: $C = \dfrac{Q}{U}$
- Unidade: **farad (F)**
- Prefixos:  
  - $1\text{ mF} = 10^{-3}\text{ F}$  
  - $1\text{ µF} = 10^{-6}\text{ F}$  
  - $1\text{ nF} = 10^{-9}\text{ F}$  

### Relações fundamentais
- **Carga:** $Q = C \cdot U$  
- **Energia armazenada:** $E = \dfrac12 C U^{2}$  

### Capacitor de placas paralelas
$$
C = \dfrac{\varepsilon A}{d}
$$
onde $\varepsilon = \varepsilon_0 \varepsilon_r$ é a permissividade do dielétrico, $A$ é a área de cada placa e $d$ a distância entre elas.

### Associação de capacitores

| Configuração | Regra | Observação |
|--------------|-------|------------|
| **Série** | $\displaystyle \frac{1}{C_\text{eq}} = \sum_i \frac{1}{C_i}$ | Mesma **carga** em todos os capacitores; a tensão se divide |
| **Paralelo** | $\displaystyle C_\text{eq} = \sum_i C_i$ | Mesma **tensão** em todos; as cargas se somam |

> **Resumo** – O capacitor armazena carga criando uma diferença de potencial; sua análise é análoga à dos resistores, mas com regras de série/paralelo invertidas.
