# R Básico 

### Nesse repositório você encontrará aspactos básicos da linguagem R. Leia e em seguida coloque em prática usando o software.

#### Operadores na linguagem R

- Atribuir nome a um objeto: <-
- Atribuir valor a um argumento: =
- Operações matemáticas de multiplicação: *
- Operações matemáticas de divisão: /
- Operações matemáticas de soma: +
- Operações matemáticas de subtração: -
- Valor de x elevado a "a": x^a
- Maior, menor, igual, maior ou igual, menor ou igual e diferente, respectivamente: > < = >= <= !=
- Adição de uma condição na função: &
- Adição de outra possibilidade a função: |
- Indica y em função de x: y ~ x
- A vírgula separa um argumento de outro dentro da mesma função: ,
- Delimita um caractere: " "
- Delimita os argumentos dentro de uma função: ( )
- Indica o início e o fim de uma função: { }
- Seleciona parte de um objeto: [ ]
- Adiciona comentários ao código que não são lidos pelo R: #
- Remover objetos: rm(objeto)
- Remove todos os objetos criados: rm(list = ls())
- Instalar pacotes: install.packages("nome_do_pacote")
- Carrega o pacote instalado: require(nome_do_pacote
- Ativa o pacote: library(nome_do_pacote)
- Para verificar exemplos de uma função: example(nome_da_funcao)
- Exibir demonstrações de funções de um pacote: demo(nome_do_pacote)
- Pedir ajuda sobre uma função: help(nome_da_funcao)

#### Funções matemáticas

- Retorna o tamanho de um vetor x: lenght(x)
- Retorna o logaritmo na base x: log(x)
- Retorna o exponencial de x: exp(x)
- Retorna a raiz quadrada de x: sqrt(x)
- Retorna o fatorial de x (x!): factorial(x)
- Arredonda o valor de x: round(x)

#### Funções estatísticas

- Retorna o valor máximo de um vetor x: max(x)
- Retorna o valor mínimo de um vetor de x: min(x)
- Soma dos valores do vetor x: sum(x)
- Média dos valores do vetor x: mean(x)
- Mediana dos valores do vetor x: median(x)
- Retorna a amplitude do vetor de x: range(x)
- Retorna o desvio-padrão do vetor de x: sd(x)
- Retorna a variância do vetor de x: var(x)

#### Observação:

##### Você pode criar um vetor com um conjunto de números usando a função concatenar "c". Exemplo:
- x <- c(2, 5, 8, 26, 28, 9) # x é o nome do objeto criado que possui os valores
- x # Após colocar o nome do objeto x, você verá o conjunto de valores selecionados acima

#### Referência

https://operdata.com.br/blog/introducao-ao-software-r/
