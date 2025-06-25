# 🔄 Entropia (S) & Energia Livre de Gibbs (G)

## 📚 Entropia – Conceitos-chave
> [!note]+ Definição  
> **Entropia (S)** mede a dispersão de energia ou o grau de desordem de um sistema.  
> É uma **função de estado**: depende apenas dos estados inicial e final.

- Unidade: **J · K⁻¹** (geralmente J · mol⁻¹ · K⁻¹ como entropia molar).  
- **2ª Lei da Termodinâmica:**  
  $$\Delta S_{\text{universo}} = \Delta S_{\text{sistema}} + \Delta S_{\text{vizinhança}} > 0$$  
  para processos espontâneos.  
- **Entropia-padrão (S°):** valor tabulado para 1 mol a 25 °C (298 K) e 1 atm.

### 🔧 Fatores que Aumentam S
- Temperatura ↑  
- Mudança de fase: $$S_{\text{gás}} > S_{\text{líquido}} > S_{\text{sólido}}$$  
- Maior nº de moles de gás (ou de partículas)  
- Mistura de substâncias (mistura ideal: $$\Delta S_\text{mistura} > 0$$)  
- Complexidade molecular (mais átomos → mais modos vibracionais)

---

## ⚡ Energia Livre de Gibbs – Conceitos-chave
> [!formula]  
> $$G = H - T\,S$$  

- **Critério de espontaneidade (T, P constantes):**  
  - $$\Delta G < 0$$ → processo espontâneo  
  - $$\Delta G = 0$$ → equilíbrio  
  - $$\Delta G > 0$$ → não espontâneo  
- **Equação fundamental:**  
  $$\Delta G = \Delta H - T\,\Delta S$$  
  onde \(T\) é em Kelvin.  

> [!tip] Interpretação rápida  
> | ΔH | ΔS | ΔG (espont.) | Comentário |
> |---|---|---|---|
> | − | + | Sempre < 0 | Espontâneo em todas as T |
> | − | − | T dependente | Espontâneo se \(T < \frac{\Delta H}{\Delta S}\) |
> | + | + | T dependente | Espontâneo se \(T > \frac{\Delta H}{\Delta S}\) |
> | + | − | Nunca < 0 | Nunca espontâneo |

### 🔄 Relação com Equilíbrio Químico
$$\Delta G^{\,\circ} = -\,R\,T \ln K$$  
- \(K > 1 \Rightarrow \Delta G^{\,\circ} < 0\) (produtos favorecidos)  
- \(K < 1 \Rightarrow \Delta G^{\,\circ} > 0\) (reagentes favorecidos)

### 🔌 Acoplamento de Reações
Reações endergônicas (ΔG > 0) podem ocorrer se **acopladas** a reações altamente exergônicas (ΔG ≪ 0), como a hidrólise de ATP em bioquímica.

---

## 📈 Resumo Visual
```mermaid
graph LR
A[ΔH] -- negativo --> C[ΔG < 0]
B[ΔS] -- positivo --> C
A -- positivo --> D[ΔG > 0]
B -- negativo --> D
