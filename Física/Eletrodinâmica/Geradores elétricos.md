#Tipo-Entender
# Geradores Elétricos

> **Observação terminológica**  
> Embora o dispositivo **transforme** energia de outra forma em energia elétrica, o nome técnico consagrado é **gerador** (não confundir com *transformador*, que apenas altera níveis de tensão em corrente alternada).

---

## 1 ▪ Força eletromotriz (f.e.m.)  
- Denotada por $\mathcal{E}$ (ou simplesmente $E$), é a **tensão total** que a bateria ou fonte disponibiliza antes de quaisquer perdas internas.
- Sua corrente é do menor para o maior, respeitando um sentido anti-horário

---

## 2 ▪ Gerador ideal  
- Resistência interna: $r = 0$  
- Não há dissipação por efeito Joule  
- Tensão nos terminais: $U = \mathcal{E}$ (constante)

---

## 3 ▪ Gerador real  
- Resistência interna não nula: $r \neq 0$  
- Parte da f.e.m. é **dissipada** como calor na resistência interna  
- Relação tensão-corrente:

  $$
  U = \mathcal{E} - I\,r
  $$

  ou, equivalentemente,

  $$
  \mathcal{E} = U + I\,r
  $$

  onde  
  * $U$ — tensão útil nos terminais (entregue ao circuito externo)  
  * $I\,r$ — queda de tensão interna (dissipada)

---

## 4 ▪ Balanço de potência  

$$
\begin{aligned}
P_{\text{gerada}}   &= \mathcal{E}\,I \\[4pt]
P_{\text{útil}}     &= U\,I = (\mathcal{E} - I r)\,I \\[4pt]
P_{\text{dissipada}}&= I^{2} r \\[6pt]
\Rightarrow\quad
P_{\text{gerada}} &= P_{\text{útil}} + P_{\text{dissipada}}
\end{aligned}
$$

---

### Resumo rápido
* $\mathcal{E}$ (f.e.m.) = tensão total fornecida pela bateria.  
* Gerador ideal: $r = 0$, nenhuma perda.  
* Gerador real: $r \neq 0$, $U = \mathcal{E} - I r$, parte da energia vira calor.

---

