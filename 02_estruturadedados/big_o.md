# Big O
- O Big O vai falar como esse algoritmo escala com o tamanho do input.
- Precisamos fazer uma análise assintótica para saber qual O de n vai perfomar melhor.
- Big O vai falar o quão bem esse algoritmo escala, dado o tamanho desse input.
- Big O é sobre escala. Escalabilidade.
- Complexidade Temporal vs Complexidade Espacial.
  - Mais comum perguntarem sobre complexidade temporal.

### Quais são as principais classificações de Big O notation?

- O(1) constante.
  - Independente do tamanho do input, ele vai ter uma execução de X. É o mesmo tempo.
  - O uso de memória é o mesmo.

- O(log n)
  - Binary Search escala em log n.
  - Conforme o nosso input aumenta muito rápido, o nosso tempo de execução não aumenta tão rápido quanto o input.
  - Alguns exemplos mostrados são o log2 de 10, tem um tempo de 3.3, log2 de 20 tem 4.3, log2 de 40 tem 5.3. Os aumentos são baixos com o crescimento do input.
  - Conforme o input aumenta exponencialmente, o tempo de execução aumenta linearmente. "Escalou de maneira logaritmica".

- O(n)
  - Ele escala exatamente na mesma medida que o input aumenta.

- O(n log n)
  - Sorting: Quicksort e Mergesort.
    - Todos menos bubblesort(O n²).
    - Faz uma ordenação e divide, faz uma ordenação e divide.
    - É muito complexo entender o cálculo, não vão perguntar.
  - Divide and Conquer.

- O(n²)
  - É um loop dentro de um loop.
  - Se tiver dois for alinhado dentro do mesmo array, num loop. Pode cravar que é O(n²).
  - Ele escala numa complexidade que para cada item do array, ele checa todos os outros itens.
  - Bubblesort.

- Casos mais raros, não cai em entrevista.
  - O(2^n)
  - O(raiz de N)
  - O(N!)


