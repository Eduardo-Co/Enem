---
aliases:
  - Resumo Termodinâmica
  - Gases
  - Processos
tags:
  - física
  - termodinâmica
  - gases
---
# Resumo de Propriedades e Processos de Gases

## 1. Pressão
- **Definição:** razão entre força normal e área sobre a qual ela atua:  
  $p = \dfrac{F}{A}$
- **Unidades:**
  - **Pascal (Pa):** $\mathrm{N/m^2}$  
  - **Atmosfera (atm):** $1\,\mathrm{atm} = 1{,}013\times10^5\,\mathrm{Pa}$  
  - Outras: bar, torr (mmHg), psi

## 2. Volume
- **Definição:** espaço ocupado por um corpo ou substância.  
- **Unidade SI:** metro cúbico ($\mathrm{m^3}$)  
- Em gases costuma-se usar litro (L, onde $1\,\mathrm{L}=10^{-3}\,\mathrm{m^3}$).

## 3. Equação de Clapeyron (Gás Ideal)
$$
p \cdot V = n \cdot R \cdot T
$$
- $p$: pressão (Pa ou atm)  
- $V$: volume (m³ ou L)  
- $n$: quantidade de substância (mol)  
- $R$: constante universal dos gases  
  $$
    R = 8{,}314\;\mathrm{J/(mol\cdot K)}
  $$
- $T$: temperatura absoluta (K)

### 3.1 Equação Geral dos Gases  
A equação de Clapeyron serve como **equação geral** que relaciona $p$, $V$ e $T$ para gases ideais.  

$$
\frac{p_1\,V_1}{T_1} \;=\;\frac{p_2\,V_2}{T_2}
$$

## 4. Processos Termodinâmicos

| Processo                | Grandeza constante    | Gráfico $p\times V$               | Trabalho $W$                                   |
|-------------------------|-----------------------|-----------------------------------|------------------------------------------------|
| **Isotérmico**          | $T = \text{const}$    | Curva hiperbólica $p\propto1/V$   | $W = nRT\ln\!\bigl(\tfrac{V_f}{V_i}\bigr)$     |
| **Isobárico**           | $p = \text{const}$    | Linha horizontal                  | $W = p\,(V_f - V_i)$                           |
| **Isovolumétrico**      | $V = \text{const}$    | Linha vertical                    | $W = 0$                                       |

- **Isotérmico:** $T$ constante → calor recebido = trabalho realizado.  
- **Isobárico:** $p$ constante → variação de volume faz trabalho.  
- **Isovolumétrico:** $V$ constante → sem deslocamento → $W=0$.


---

## 5. Misturas – Lei Combinada dos Gases

A mistura completa obedece:

$$
\frac{p_{\mathrm{mix}}\,V_{\mathrm{mix}}}{T_{\mathrm{mix}}}
\;=\;\sum_i \frac{p_i\,V_i}{T_i}
$$

---

## Trabalho de um Gás

- **Definição geral**  
  O trabalho realizado **pelo** gás (positivo se expande) ou **sobre** o gás (negativo se comprime) é a área sob a curva \(p\)×\(V\):
  $$
    \tau = \int_{V_i}^{V_f} p\,\mathrm{d}V
  $$

- **Processo Isobárico** (pressão constante)  
  $$
    \tau = p\,\Delta V = p\,(V_f - V_i)
  $$

- **Analogia Mecânica**  
  É análogo ao trabalho em mecânica:
  $$
    \tau = F \cdot D
  $$
  onde \(F\) é a força e \(D\) o deslocamento.

---



