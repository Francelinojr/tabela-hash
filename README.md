# tabela-hash

1-Implementar uma estrutura de tabela hash para armazenar n objetos
com encadeamento separado duplo. No encadeamento duplo existem
dois níveis de endereçamento, nos dois o mapeamento da chave ao
endereço se dá por uma função hash. A figura abaixo ilustra o
esquema de encadeamento separado duplo.

a. No primeiro nível crie um vetor com 10 ponteiros para vetores.
Aplique a função hash para direcionar o elemento da chave c
em uma das outras tabelas do segundo nível;

b. No segundo nível cada tabela é composta por um vetor de n/10
listas de objetos a serem armazenados. Uma segunda função
hash diferente da primeira deve ser definida para direcionar a
chave c em uma das listas específicas

2- Implemente as funções hash específica de cada nível de
endereçamento, além dos métodos de inserção de novos objetos a
partir de suas chaves únicas e recuperação de objetos já cadastrados a
partir da chave única.
