# Implementação de Árvore B em C
Este é um programa em C que implementa uma estrutura de árvore B. Árvores B são estruturas de árvore autoequilibradas comumente utilizadas em sistemas de banco de dados e sistemas de arquivos devido à sua eficiência em inserções, exclusões e buscas.

Este programa permite realizar as seguintes operações em uma árvore B:

Inserir uma chave na árvore B.
Excluir uma chave da árvore B.
Pesquisar por uma chave na árvore B.
Exibir a árvore B.
Exibir a árvore B em ordem ascendente.
Exibir a árvore B em ordem descendente.

Depois de iniciar o programa, você pode escolher entre as seguintes opções do menu:

1. Inserir: Insira uma chave na árvore B.
2. Excluir: Exclua uma chave da árvore B.
3. Pesquisar: Pesquise uma chave na árvore B.
4. Exibir: Exiba a estrutura da árvore B.
5. Exibir em Ordem Crescente: Exiba as chaves da árvore B em ordem crescente.
6. Exibir em Ordem Descendente: Exiba as chaves da árvore B em ordem descendente.
7. Sair: Saia do programa.

Estrutura do Código:

* struct node: Representa um nó na árvore B.
* enum KeyStatus: Representa o status de uma operação de inserção ou exclusão de chave.
* insert(): Insira uma chave na árvore B.
* ins(): Função recursiva para inserção de chave.
* DelNode(): Exclua uma chave da árvore B.
* del(): Função recursiva para exclusão de chave.
* search(): Pesquise por uma chave na árvore B.
* display(): Exiba a estrutura da árvore B.
* displayAscending(): Exiba as chaves da árvore B em ordem ascendente.
* displayDescending(): Exiba as chaves da árvore B em ordem descendente.
* searchPos(): Encontre a posição para inserir ou pesquisar por uma chave em um nó.
