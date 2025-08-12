# Hidroestática — ENEM (Resumo Obsidian)

> [!summary] Essência
> Hidroestática estuda **fluidos em repouso**. No ENEM, caem: **pressão** e sua **variação com a profundidade (Stevin)**, **Pascal (prensa hidráulica)**, **vasos comunicantes/manômetros** e **empuxo (Arquimedes) & flutuação**.

---

## 1) Conceitos básicos
- **Pressão**: $p=\dfrac{F}{A}$ (Pa).  
- **Densidade**: $\rho=\dfrac{m}{V}$ ($\text{kg}\,\text{m}^{-3}$).  
- **Peso específico**: $\gamma=\rho\,g$ ($\text{N}\,\text{m}^{-3}$).  
- **Observações-chave**:  
  - Em um **mesmo fluido** e **mesma profundidade**, a **pressão é a mesma** (independe da forma do recipiente).  
  - **Pressão é escalar e isotrópica** (atua igualmente em todas as direções).

---

## 2) Variação da pressão com a profundidade (Lei de Stevin)
- Em um ponto à profundidade $h$:
  $$p = p_0 + \rho g h$$
  onde $p_0$ é a pressão na superfície (geralmente **atmosférica**).
- **Diferença de pressão** entre dois pontos no mesmo fluido:
  $$\Delta p = \rho g \Delta h$$
- **Derivação express (cancelamento de $A$)**:
  $$p=\frac{F}{A}=\frac{\rho g V}{A}=\frac{\rho g (A h)}{A}=\rho g h$$
  > **A área $A$ cancela**. Só importa a **altura vertical $h$**.

---

## 3) Princípio de Pascal (prensa hidráulica)
- Uma variação de pressão aplicada a um fluido **incompressível** em repouso **se transmite integralmente**:
  $$\frac{F_1}{A_1}=\frac{F_2}{A_2} \quad\Rightarrow\quad F_2=F_1\frac{A_2}{A_1}$$
- **Ganho de força** em $A_2>A_1$; **deslocamento diminui** (conserva trabalho: $F\cdot d$).

---

## 4) Vasos comunicantes & manômetros em “U”
- **Mesmo fluido** e **mesmo $p_0$** $\Rightarrow$ **mesma altura** nas ramas abertas.  
- Com **dois fluidos** (ex.: água/óleo), os níveis são diferentes; igualando as pressões no mesmo nível:
  $$p_0 + \rho_1 g h_1 = p_0 + \rho_2 g h_2 \;\Rightarrow\; \rho_1 h_1 = \rho_2 h_2$$
- **Manômetro em U** (pressão manométrica):
  $$\Delta p = \rho_{\text{man}} g\,\Delta h$$
  onde $\rho_{\text{man}}$ é a densidade do fluido do manômetro.

---

## 5) Empuxo (Arquimedes) & flutuação
- **Empuxo**: força vertical para cima exercida pelo fluido:
  $$E = \rho_{\text{fluido}} g\,V_{\text{deslocado}}$$
- **Condições de flutuação** (corpo homogêneo, repouso):
  - **Afunda**: $\rho_{\text{corpo}} > \rho_{\text{fluido}}$  
  - **Flutua**: $\rho_{\text{corpo}} < \rho_{\text{fluido}}$  
  - **Neutro**: $\rho_{\text{corpo}} = \rho_{\text{fluido}}$
- **Fração submersa** (quando flutua):
  $$\text{fração submersa}=\frac{\rho_{\text{corpo}}}{\rho_{\text{fluido}}}$$

> [!tip] Decisão rápida (flutua × afunda)
> Compare densidades: se $\,\rho_{\text{corpo}}/\rho_{\text{fluido}}<1\,$ → **flutua**; se $=1$ → **neutro**; se $>1$ → **afunda**.

---

## 6) Pressão atmosférica e barômetro
- **Unidades úteis**: $1\,\text{atm}\approx 1{,}01\times10^5\,\text{Pa}$; $1\,\text{bar}=10^5\,\text{Pa}$.  
- **Barômetro de Hg**:
  $$p_{\text{atm}}=\rho_{\text{Hg}} g h \quad(\rho_{\text{Hg}}\approx 13{,}6\times10^3\,\text{kg}\,\text{m}^{-3})$$

---

## 7) Valores e conversões que ajudam
- $g\approx 9{,}8\,\text{m}\,\text{s}^{-2}$ (no ENEM, muitas vezes $10$).  
- $\rho_{\text{água}}\approx 1{,}0\times10^3\,\text{kg}\,\text{m}^{-3}$.  
- **Pa** $=\text{N}\,\text{m}^{-2}$; **$1\,\text{atm}\simeq 76$ cmHg**.

---

## 8) Pegadinhas clássicas no ENEM
- **Forma do recipiente não altera $p(h)$** (mesma $h$ → mesma $p$).  
- **$h$ é altura vertical** (não confundir com comprimento do tubo).  
- **Empuxo depende do fluido**, não da densidade do corpo (exceto via fração submersa).  
- Em prensas, **ganho de força ≠ ganho de energia** (há perda no deslocamento).  
- **Vasos com mistura**: iguale pressões **no mesmo plano horizontal**.  
- **Pressão absoluta**: $p_{\text{abs}}=p_{\text{atm}}+p_{\text{man}}$.

---

## 9) Exemplos rápidos (modelo ENEM)
**(A) Diferença de pressão com profundidade**  
Água, $\rho=10^3$; $g=10$; $\Delta h=2\,\text{m}$.  
$$\Delta p=\rho g \Delta h=10^3\cdot 10\cdot 2=2,0\times10^4\,\text{Pa}$$

**(B) Prensa hidráulica**  
$A_1=2\,\text{cm}^2$, $A_2=50\,\text{cm}^2$, $F_1=80\,\text{N}$.  
$$F_2=F_1\frac{A_2}{A_1}=80\cdot \frac{50}{2}=2000\,\text{N}$$

**(C) Fração submersa**  
Bloco $\rho_{\text{corpo}}=800\,\text{kg}\,\text{m}^{-3}$ em água.  
$$\text{fração}=\frac{800}{1000}=0{,}8 \Rightarrow 80\% \text{ submerso}$$

---

## 10) Mapa mental mínimo para resolver
1. **É fluido em repouso?** → Hidroestática.  
2. **Pergunta é sobre $p$ ou $F$?**  
   - **$p(h)$** → **Stevin**: $p=p_0+\rho g h$ (via $p=F/A=\rho g V/A=\rho g h$).  
   - **Transmissão de $p$** → **Pascal**: $\dfrac{F}{A}=\text{constante}$.  
   - **Níveis/colunas** → **Vasos/manômetro**: $\Delta p=\rho g \Delta h$.  
   - **Flutuação** → **Arquimedes**: $E=\rho g V_{\text{desl}}$ e densidades relativas.



Veja que aqui, $V = A \cdot h$
> [!done] Domine isto: **$p=\rho g h$** *(vem de $p=\frac{F}{A}=\frac{\rho g V}{A}=\rho g h$)*, **$\Delta p=\rho g \Delta h$**, **$\dfrac{F_1}{A_1}=\dfrac{F_2}{A_2}$**, **$E=\rho g V$**, **$\text{fração}=\dfrac{\rho_{\text{corpo}}}{\rho_{\text{fluido}}}$** e **$p_{\text{abs}}=p_{\text{atm}}+p_{\text{man}}$**.
