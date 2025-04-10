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

# Método Rápido para Calcular o MDC: Algoritmo de Euclides

1) Inicie como MDC
2) procure um que divida os dois ao mesmo tempo
3) realize divisões e repita o processo 2
4) Encerre quando ao menos um chegue a 1 ou quando não houver mais números pelos quais possamos dividir ambos
5) Multiplique os resultados encontrados