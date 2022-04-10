# Estudo-de-estrutura-de-dados-e-algoritmos
Informações pertinentes de ambos 

## Algoritmos: 
---
* Apresentam uma sequência finita e não ambígua de instruções que conseguem ser finalizadas num período finito de tempo.
* E um preocesso discreto ou seja possui uma sequência de ações indivisíveis e é determinístico, portanto para cada passo da sequeência há apenas uma ação para ser feita. 
* É cosntituído por um conjunto de expressões simbólicas que representam ações, teste de condições e estruras de controle.

* Pseudo cógidos são notações algoritmicas proximas de uma linguagem natural: 
[Ler o número; Read(X)]; 
[Fazer isso: if (isso), then isso]
[Impreimir o resultado: Print(y)]
[Termina: exit]

* Algoritmos:

  Maior valor de um vetor;  Soma e média de valores de um vetor; Diagonal principla de uma matriz; Pesquisa linear e Ordenação de vetor 
## Estrutura de dados: 
---

* Representam os objetos do mundo real e definem a parte estática de uma algoritmo.
* A manipulação das estruturas de dados através de instruções definem a parte dinâmica dos algoritmos.
* Tipos:
  * Booleano: Verdadeiro e Falso
  * Dados núméricos: inteiro e real 
  * Alfanumérico: Alfabeto(ex.: A,a,B,b...), Caracteres numéricos(ex.: 1,2,3...), Operadores e caracteres especiais(ex.: ^(exp),+,-,* ,@...) e caracteres de controle(ex.: Del, CR, HT...)
#### Array ou Vetores: 

  Um vetor contém um nome, um indíce do tipo inteiro e uma dimensão do tipo ineiro. por exemplo o vetor AMZ[ ] 1 21 13 45 29 48
o AMZ[2] = 21 e esse vetor tem índice = 6 

#### Matizes: Matrizes são vetores bidimensionais, portanto são representadas por um nome e dois índices por exemplo: BAR[I,J] (Coluna, Linhas)

  x|1|2|3
  ---|---|---|---|
  1|251|235|124
  2|120|123|556
  3|456|679|999

  e assim o BAR[1,2] = 235

* Instrução de atribuição: 
Diferente do operador relacional = 
O operador de atribução <-, pode constar variaveis, cosntantes, operadores e outras funções

  x <- 21; 
  
  y <- x*y 

* Leitura e escrita de dados:

  Read (<nome da variavel> ou 'texto')
  
  Write (<nome da variavel> ou 'texto')
  
* Estrutura condicional:
  
  if (algo)
  
  Then (Isso)
  
  Else (Isso)
  
* Estrutura de repetição:
  
  Do While (alguma situação)
  
  O que fazer
  
  Repat Until (alguma situação)
  
  O que fazer 
  
  Do For (alguma situação)
  
  O que fazer 
  
  
#### Map:
  Muito semelhante a um Object
  
  É uma coleção de chave-valor sendo possível adcionar, acessar, modificar e deletar. 
  
  Porém com algumas diferenças: qualquer objeto pode ser uma chave e um Map consegue guardar a ordem dos pares. 
  
  Diferente de um object não é possivel usar o .key = value nem .ket/[key]. Deve-se usar os métodos .set e .get
  
  Outra diferneça são os métodos has e size para contar a quantidade de propriedades.
  
  Quando usar Map ao invés de Object:
    * As keys são desconhecidas até o tempo de execução, você precisa procurá-las dinamicamente?
    * Todos os valores sempre serão do mesmo tipo, e podem ser usados de forma intercambiável?
    * Você precisa de keys que não são strings?
    * Os pares key-value são adicionados ou removidos frequentemente?
    * Você tem uma quantidade de pares key-value arbitrária (de troca fácil) ? A coleção é iterada?
  
#### Set:

  > Map está para Object assim como Set está para Array
  
  Principal diferença Set não aceita valores repetidos, guarda apenas valores únicos 
  
  Set tem métodos parecidos com map. add(), para adicionar, delete(), has()
para verificar se o item existe, forEach() para percorrelo e size() para retornar o tamanho   
  
  É possível criar um set a partir de um array passando ele dentro de um cosntrutor new.
  
  
  ( É necessário ficar atento a compatibilidade tanto no **Map** quanto no **Set** )
  
