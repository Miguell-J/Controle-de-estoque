# Verificação de Estoque de Produtos

Este é um programa em Python que permite ao usuário inserir o nome, a categoria e a quantidade de um produto e, em seguida, verifica se a quantidade do produto está acima, no limite mínimo ou abaixo de um valor pré-definido para três categorias diferentes: alimentos, bebidas e produtos de limpeza.

## Instruções

1. Execute o código em um ambiente Python compatível.

2. O código solicita ao usuário que insira o nome do produto, a categoria e a quantidade do produto.

3. O programa verifica se todos os campos (nome, categoria e quantidade) foram preenchidos. Se algum campo estiver vazio, ele exibirá uma mensagem solicitando que o usuário preencha todos os campos.

4. Se todos os campos forem preenchidos, o programa determina a categoria do produto com base na presença de palavras-chave ('limento', 'ebida', 'impeza' nas categorias).

5. Com base na categoria identificada, o programa verifica a quantidade do produto em relação ao estoque mínimo pré-definido (alimentos: 50, bebidas: 70, limpeza: 30) e emite uma resposta informando se o estoque está acima, no limite mínimo ou abaixo do mínimo.

## Exemplo de Uso

Após a execução do código, você pode inserir o nome, a categoria e a quantidade do produto e receberá uma resposta com base na categoria e na quantidade inserida.

## Notas

- Este código é um exemplo de verificação de estoque para produtos em diferentes categorias.
- As palavras-chave para determinar a categoria ('limento', 'ebida', 'impeza') são identificadas no texto da categoria inserida, permitindo que o código seja flexível em relação a diferentes formas de escrita.
- Você pode personalizar os valores de estoque mínimo para cada categoria conforme necessário.
