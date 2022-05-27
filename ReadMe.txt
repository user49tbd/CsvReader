Exercício de Sistemas de Arquivos
Diversas estruturas de dados são utilizadas nas funcionalidades dos sistemas operacionais, como 
Pilhas, Listas, Árvores, Filas, etc. Maiores informações serão dadas abaixo.
Pensando nisso, a atividade consiste em pegar o arquivo csv em anexo e criar um projeto Java para 
manipulá-lo. O csv em questão apresenta todas as características de todos os jogadores disponíveis 
no jogo FIFA ‘19 da Eletronic Arts. O arquivo está com jogadores ordenados por seu Overall, do 
maior para o menor, portanto, o primeiro jogador da lista é o Leonel Messi, Overall 94 e o último é 
G. Nugent, com Overall 46.
O arquivo data.csv deve ser colocado na pasta C:\TEMP

O método empilhaBrasileiros recebe o caminho e o nome do arquivo, deverá inicializar uma pilha, 
abrir o arquivo, ler o arquivo, verificar se na coluna referente à nacionalidade existe o valor “Brazil”
e empilhar (push) a linha inteira, apenas de jogadores brasileiros. O método deve retornar essa 
pilha.
O método desempilhaBonsBrasileiros deve receber uma pilha de Strings como parâmetro, percorrer
a pilha, desempilhar (pop) e imprimir (somente nome e Overall) apenas de jogadores com Overall 
acima de 80. Perceba que, como estão ordenados, no arquivo, do melhor para o pior, os jogadores 
serão empilhados do melhor para o pior, portanto, o primeiro impresso deverá ser o pior dentre os 
escolhidos e o último deverá ser Neymar Jr, com Overall 92.
O método listaRevelacoes recebe o caminho e o nome do arquivo, deverá inicializar uma lista 
encadeada, abrir o arquivo, ler o arquivo, verificar se na coluna referente à idade o valor é menor ou
igual a 20, e adicionar (add) à lista, a linha inteira, apenas de jogadores jovens. O método deve 
retornar essa lista.
O método buscaListaBonsJovens deve receber uma lista de Strings como parâmetro, percorrer a 
lista do último para o primeiro, imprimir (somente nome, idade e Overall) apenas de jogadores com 
Overall acima de 80 e 20 anos ou menos. 