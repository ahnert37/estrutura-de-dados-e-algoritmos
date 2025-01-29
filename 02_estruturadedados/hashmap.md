# Hashmap (Dicionário)

- A maioria dos casos de uso do dicionário é O(1).
- Hash Function, é aqui que acontece a mágica perfomática.
  - Ele vai transformar a chave, o input, num valor e esse valor vai ser a posição do array em que esse item está armazenado que a gente quer pegar.
- Load Factor
  - Diferença de tamanho entre a quantidade de dados que a gente tem e a nossa estrutura de dados.
- Collissions
  - Salvar chave e valor para evitar colisões.
  - Em um momento de colisão, o hashmap pode virar O(n).
  - Onde houver uma colisão, vamos apontar para um outro array ou outro linked lists.

- Na maioria dos casos o Hashmap é O(1).

___

## Recaptulando

- Na vida real, um hashmap é assim:
  - Ele vai ter um array, bastante grande.
  - Uma hash function, que uma funçao geralmente com criptografia que utiliza um MD5 ou um SHA-256.
  - E quando houver colisões, ele geralmente vai lidar com elas armazenando os itens que colidiram numa subestrutura de dados.
  - Quando o nosso Hashmap chegar em 70% do tamanho (Load Factor), geralmente, isso vai gerar uma ação que vai alocar outro array com o dobro do tamanho e vamos jogar todos os nosso elementos nele. Reduzindo assim o nosso Load Factor.