Nomes: Rafael Moura de Almeida. N° USP: 112255505. Turma 04.
	Rafael Francisco de Freitas Timoteo. N° USP: 12924740. Turma 04.
	Guilherme Augusto Arrabal de Souza. N° USP: 5642180. Turma 94.

/*****************************************************************************************************************************/

Este programa possui 5 códigos fontes: ep1.c, que contém a função main; lista.h, que contém as estruturas
utilizadas para carregar o arquivo em uma estrutura de lista e os protótipos da funções principais que 
armazenam as linhas e palavras do arquivo de texto em listas e também permitem a recuperação dessas
informações; lista.c, que contém as funções declaradas em lista.h além de funções adicionais necessárias 
para realizar o armazenamento e recuperação das linhas e palavras do arquivo de texto; arvore_binaria.h, 
que contém as estruturas utilizadas para carregar o arquivo em uma árvore binária de busca e os protótipos
das funções principais que armazenam as linhas e palavras do arquivo de texto em árvores binárias 
de busca e também permitem permitem a recuperação dessas informações; e arvore_binaria.c, que contém
as funções declaradas em arvore_binaria.h além  de funções adicionais necessárias para realizar
o armazenamento e recuperação das linhas e palavras do arquivo de texto.

/*****************************************************************************************************************************/

Para compilar os códigos fontes: copie o caminho do diretório EP - AED1 no seu computador, 
no qual se localizam todos os arquivos fontes além dos arquivos de texto usados para testar
o programa e esse README, abra o prompt de comando ou o terminal do linux
 e digite "cd <ctrl + v(caminho EP - AED1)>" para ir até o diretório de EP - AED1. 
Então, digite: "gcc ep1.c lista.c arvore_binaria.c -o ep" na linha de comando do prompt de comando 
ou no terminal do linux.

Para executar: depois de compilado, digite: ep <arquivo-texto.txt> lista para carregar o arquivo usando
listas como estrutura. Caso deseje utilizar a estrutura árvore binária de busca para carregar o arquivo
e realizar as buscas, digite ep <arquivo-texto.txt> arvore.
Exemplos:
Para utilizar listas:			Para utilizar árvore binária de busca:
ep texto.txt lista				ep texto.txt arvore
ep sample.txt lista			ep sample.txt arvore
ep 5000.txt lista				ep 5000.txt arvore
ep bible.txt lista				ep bible.txt arvore
ep In-Search-Of-Lost-Time.txt lista	ep In-Search-Of-Lost-Time.txt arvore

Para buscar uma palavra:
busca <palavra>

Exemplos:
busca god
busca the
busca in
busca are
busca he
busca is
busca she
busca him
busca thy
busca thou

Na pasta EP - AED1 foram incluídos 9 arquivos de texto para testar o programa e realizar  o armazenamento
em memória de cada linha e cada palavra do arquivo txt na estrutura de dados selecionada pelo usuário:

texto.txt (13 linhas)
sample.txt (66 linhas)
new.txt (440 linhas)
2021.txt (2021 linhas)
3000.txt (3000 linhas)
5000.txt (5000 linhas)
biblia-em-txt.txt (32369 linhas)
bible.txt (100182 linhas)
In-Search-Of-Lost-Time (109888 linhas)