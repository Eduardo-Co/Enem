

## 1. Conceito Geral  

- A **lei de velocidade** relaciona a velocidade instantânea de uma reação à concentração dos reagentes.  
- Forma genérica para a reação $aA + bB \rightarrow \text{produtos}$  
  $$v = k\,[A]^m\,[B]^n$$  
  onde  
  - $v$ = velocidade ($\text{mol·L}^{-1}\,\text{s}^{-1}$)  
  - $k$ = constante de velocidade (depende de $T$)  
  - $m, n$ = ordens parciais (determinadas **experimentalmente**)  
  - ordem global $= m + n$

---

## 2. Lei de Velocidade **Diferencial**  

| Ordem | Expressão diferencial | Unidades de $k$ |
|-------|-----------------------|-----------------|
| 0ª    | $v = k$              | $\text{mol·L}^{-1}\,\text{s}^{-1}$ |
| 1ª    | $v = k[A]$           | $\text{s}^{-1}$ |
| 2ª    | $v = k[A]^2$ ou $k[A][B]$ | $\text{L·mol}^{-1}\,\text{s}^{-1}$ |

> **Dica**: ordens fracionárias ou negativas também existem em mecanismos complexos.

---

## 3. Leis **Integradas**

### 0ª ordem  
$$[A] = [A]_0 - k\,t$$  

### 1ª ordem  
$$\ln\!\bigl([A]\bigr) = \ln\!\bigl([A]_0\bigr) - k\,t$$  

### 2ª ordem (a mesma espécie)  
$$\frac{1}{[A]} = \frac{1}{[A]_0} + k\,t$$  

> Gráficos de $[A]$ vs. $t$, $\ln[A]$ vs. $t$ ou $1/[A]$ vs. $t$ ajudam a identificar a ordem.

---

## 4. Tempo de Meia-Vida ($t_{1/2}$)

| Ordem | $t_{1/2}$ | Comentário |
|-------|-----------|------------|
| 0ª    | $\dfrac{[A]_0}{2k}$ | Depende de $[A]_0$ |
| 1ª    | $\dfrac{\ln 2}{k}$  | **Independe** de $[A]_0$ |
| 2ª    | $\dfrac{1}{k[A]_0}$ | Diminui com $[A]_0$ |

---

## 5. Determinação Experimental  

1. **Método das velocidades iniciais** – Medir $v_0$ com diferentes $[A]_0$, plotar $\log v_0$ vs. $\log[A]_0$ (inclinação = ordem).  
2. **Método integral** – Ajustar dados de $[A]$ vs. $t$ às expressões integradas.  
3. **Método de isolamento / pseudo-1ª ordem** – Manter um reagente em grande excesso para que sua concentração permaneça praticamente constante, simplificando a cinética.

---

## 6. Fatores que Afetam $k$

### 6.1 Temperatura – Equação de Arrhenius  
$$k = A\,e^{-E_a/RT}$$  
- $A$ = fator de frequência (ou pré-exponencial)  
- $E_a$ = energia de ativação  
- Representação linear: $\ln k$ vs. $1/T$ (reta de inclinação $-E_a/R$).

### 6.2 Catalisadores  
- Reduzem $E_a$, **não** alteram $\Delta G_{\text{reação}}$ nem a posição de equilíbrio.  
- Podem atuar via adsorção (cat. heterogênea) ou complexação (cat. homogênea).

### 6.3 Meio reacional  
- Polaridade, força iônica e pH modificam estados de transição e, portanto, $k$.

---

## 7. Mecanismos e Etapa Determinante

- Para reações elementares, a lei de velocidade é derivada diretamente da estequiometria.  
- Em sequências de passos, a **etapa lenta** governa a cinética global.  
- **Intermediários** não aparecem na lei final; use hipóteses de estado estacionário ou pré-equilíbrio para eliminá-los.

---

## 8. Reações Reversíveis & Competitivas  

Para $A \rightleftharpoons B$ com $k_1$ (ida) e $k_{-1}$ (volta):  
$$\frac{d[A]}{dt} = -k_1[A] + k_{-1}[B]$$  
A aproximação de **equilíbrio rápido** pode simplificar mecanismos catalíticos.

---

