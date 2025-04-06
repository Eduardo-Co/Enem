# MMC:

O mmc pode ser calculado como o habital, colocando os números e simplificando de modo que cheguemos em 1, ou utilizamos o método do coração

## Método do Coração para MMC
O **método do coração** é uma técnica visual para encontrar o Mínimo Múltiplo Comum (MMC) de dois ou mais números. Veja como funciona:

1. **Organize os números:**  
   Escreva os números um abaixo do outro.

2. **Divisão pelos fatores primos:**  
   Escolha um número primo (começando pelo 2) e divida os números que forem divisíveis por ele.  
   Anote o primo escolhido fora da “casinha” dos números.

3. **Repita o processo:**  
   Com os quocientes obtidos, escolha o próximo número primo que divida pelo menos um deles e continue dividindo até que os quocientes não tenham mais fatores comuns (exceto o 1).

4. **Calcule o MMC:**  
   Multiplique todos os números primos anotados e os quocientes finais. Esse produto é o MMC.

**Exemplo:**  
Para calcular o MMC de 12 e 18:
- Divisão por 2:  
  12 → 6, 18 → 9 (anote o 2)
- Divisão por 3:  
  6 → 2, 9 → 3 (anote o 3)  
- MMC = 2 × 3 × 2 × 3 = **36**

# Métodos para MDC

O **Máximo Divisor Comum (MDC)** pode ser encontrado utilizando diferentes métodos. Aqui estão dois dos mais utilizados:

### 1. Método da Fatoração
- **Passo 1:** Decomponha cada número em seus fatores primos.  
- **Passo 2:** Identifique os fatores comuns entre as decomposições.  
- **Passo 3:** Multiplique os fatores comuns, utilizando a menor potência encontrada em cada número.  
  O resultado é o MDC.

**Exemplo:**  
Para calcular o MDC de 12 e 18:
- 12 = 2² × 3  
- 18 = 2 × 3²  
- Fatores comuns: 2¹ e 3¹  
- MDC = 2 × 3 = **6**

### 2. Algoritmo de Euclides
- **Passo 1:** Divida o maior número pelo menor e anote o resto.  
- **Passo 2:** Substitua o maior número pelo menor e o menor pelo resto obtido.  
- **Passo 3:** Repita o processo até que o resto seja zero.  
  O último divisor não nulo é o MDC.

**Exemplo:**  
Para calcular o MDC de 12 e 18:
- 18 ÷ 12 = 1, resto 6  
- 12 ÷ 6 = 2, resto 0  
- MDC = **6**
