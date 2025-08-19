# Trabalho e variação térmica — **Gases Ideais** (Obsidian + MathJax, didático)

> **Ideia central:** em gás ideal, **trabalho** só aparece se o **volume mudar**.  
> $$ W=\int_{V_1}^{V_2} P\,dV \;\;\Rightarrow\;\; \boxed{\Delta V\neq 0 \Rightarrow W\neq 0} $$
> **1ª Lei (convenção de Física):**  
> $$ \Delta U = Q - W $$
> **Energia interna (depende só de $T$):**  
> $$ \Delta U = n\,C_V\,\Delta T $$

---

## 1) Isotérmico ($T$ constante)
- **Fixo:** $T$
- **Variação:** quando $V$ aumenta, $P$ diminui ($PV=\text{const}$)
- **Por que há trabalho?** $V$ muda.
- **Formulário:**
  $$ PV=\text{const},\qquad \Delta U=0,\qquad W=nRT\ln\!\left(\frac{V_2}{V_1}\right),\qquad Q=W $$

---

## 2) Isobárico ($P$ constante)
- **Fixo:** $P$
- **Variação:** $V\propto T$
- **Trabalho?** Sim, se $V$ mudar.
- **Formulário:**
  $$ \frac{V}{T}=\text{const},\qquad W=P\,(V_2-V_1),\qquad \Delta U=nC_V\Delta T,\qquad Q=nC_P\Delta T $$

---

## 3) Isocórico / Isovolumétrico ($V$ constante)
- **Fixo:** $V$
- **Variação:** $P\propto T$
- **Trabalho?** **Não.** ($W=0$)
- **Formulário:**
  $$ \frac{P}{T}=\text{const},\qquad W=0,\qquad Q=\Delta U=nC_V\Delta T $$

---

## 4) Adiabático ($Q=0$)
- **Fixo:** troca de calor nula ($Q=0$)
- **Trabalho?** Sim, se $V$ mudar; vem da própria energia interna.
- **Formulário (reversível):**
  $$ PV^{\gamma}=\text{const},\quad T\,V^{\gamma-1}=\text{const},\quad \frac{T^{\gamma}}{P^{\gamma-1}}=\text{const} $$
  $$ W=-\Delta U=-\,nC_V\Delta T $$

---

## Como decidir **rápido**
1. **Quem ficou constante?** ($T$, $P$, $V$ ou $Q=0$)  
2. **Houve $\Delta V$?**  
   - Se **sim** → **há trabalho** ($W\neq 0$).  
   - Se **não** → **sem trabalho** ($W=0$).  
3. Aplique a **1ª Lei**:  
   $$ \Delta U = Q - W $$

> **Regra de ouro:** $$ \boxed{\text{Trabalho em gás ideal nasce da variação de volume.}} $$
