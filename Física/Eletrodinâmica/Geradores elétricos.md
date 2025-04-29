# Geradores e Receptores Elétricos

> **Observação terminológica**  
> Embora o dispositivo **transforme** energia de outra forma em energia elétrica, o nome técnico consagrado é **gerador**  
> (*transformador* apenas altera níveis de tensão em corrente alternada).

---

## 1 ▪ Forças internas  
| Símbolo | Nome | Onde aparece | Sentido interno |
|---------|------|--------------|-----------------|
| $\mathcal{E}$ | **força eletromotriz** (f.e.m.) | geradores | do polo – para o polo + |
| $\mathcal{E}'$ ou $\mathcal{E}_{c}$ | **força contra-eletromotriz** (f.c.e.m.) | receptores (motores, lâmpadas, eletrólises…) | do polo + para o polo – |

A f.c.e.m. **se opõe** à tensão aplicada, de acordo com a lei de Lenz.

---

## 2 ▪ Gerador ideal  
- Resistência interna: $r = 0$  
- Não há dissipação por efeito Joule  
- Tensão nos terminais: $U = \mathcal{E}$ (constante)

---

## 3 ▪ Gerador real  
- Resistência interna não nula: $r \neq 0$  
- Parte da f.e.m. é **dissipada** como calor na resistência interna  
- Relação tensão-corrente  

  $$
  U = \mathcal{E} - I\,r
  $$

  (ou $\;\mathcal{E} = U + I\,r$)

---

## 4 ▪ Receptor real (f.c.e.m.)  
- Também possui resistência interna $r$  
- Relação tensão-corrente  

  $$
  U = \mathcal{E}' + I\,r
  $$

  (ou $\;\mathcal{E}' = U - I\,r$)

  onde $\mathcal{E}' < U$ em operação normal.

---

## 5 ▪ Balanços de potência  

### 5.1 Gerador real  

$$
\begin{aligned}
P_{\text{gerada}}   &= \mathcal{E}\,I \\[4pt]
P_{\text{útil}}     &= U\,I = (\mathcal{E} - I r)\,I \\[4pt]
P_{\text{dissipada}}&= I^{2} r \\[6pt]
P_{\text{gerada}} &= P_{\text{útil}} + P_{\text{dissipada}}
\end{aligned}
$$

### 5.2 Receptor real  

$$
\begin{aligned}
P_{\text{elétrica}} &= U\,I \\[4pt]
P_{\text{útil}}     &= \mathcal{E}'\,I \\[4pt]
P_{\text{dissipada}}&= I^{2} r \\[6pt]
U\,I &= \mathcal{E}'\,I + I^{2} r
\end{aligned}
$$

---

### Resumo rápido
* **Gerador ideal** : $r = 0$, $U = \mathcal{E}$.  
* **Gerador real** : $U = \mathcal{E} - I r$, perde parte da energia em calor.  
* **Receptor real** : $U = \mathcal{E}' + I r$, converte energia elétrica em outra forma, gerando f.c.e.m. que se opõe à tensão aplicada.
