# Modulo 2 - Linguagens de Programação

## Tópico 1 - Linguagens de Programação

<br>

### O que é Linguagem de Programação?

<br>

`Linguagem dede Programação` é um conjunto de comandos, instruções e regras utilizadas para criar um programa de computador.

A linguagem de programação possui regras `léxicas`, regras de `sintaxe` e de `semântica`.

`Léxico` refere-se ao conjuto de palavras pertencentes a determinada linguagem.

~~~
Se (<expressão>) instrução
~~~


`Sintático` refere-se ao conjunto de regras que determina as diferentes possibilidades de associação das palavras.

~~~
Se (<expressão>) instrução
~~~

`Semântica` refere-se ao significado das expressões.

~~~
Se (<expressão>) instrução
~~~


#### Exemplo em Pseudocódigo:
<br>

![](./assets/Capturar.PNG)

<br>

##### `Análise Léxica`
<br>

![](./assets/Capturar1.PNG)

<br>

##### `Análise Sintática`

![](./assets/Capturar2.PNG)

<br>

##### `Análise Semântica`

![](./assets/Capturar3.PNG)

<br>

### `Léxico`:

- Responsável por reconhecer as `palavras reservadas`, constantes, identificadores e outras palavras que pertencem a linguagem de programação.

<br>

### `Sintático`:
- Responsável por `analisar a estrutura` do código fonte sem considerar seu significado na linguagem de programação.


<br>

### `Semântico`:
- Responsável por enfatizar a `interpretação` do código fonte, de modo a prever o resultado da execução do programa.

<br>

## Tópico 2 - Linguagens de Alto e Baixo Nível

<br>

### Esxitem linguagens de `Alto Nível` e `Baixo Nível`, mas qual a diferença?

<br>

#### `Alto Nível` :

- Sintaxe é voltada para o entendimento humano.

![](./assets/Capturar4.PNG)


<br>

#### `Baixo Nível` :

- Abstraem conceitos voltados para a máquina e sintetizam comandos.
- Exemplo : ASSEMBLY

<br>

### Comparando a exibição de "Hello World" de uma linguagem de alto nível e baixo nível

![](./assets/Capturar5.PNG)

![](./assets/Capturar6.PNG)


<br>

![](./assets/Capturar7.PNG)

<br>

### Como a linguagem de programação se torna um programa de computador?

- Linguagem de baixo nível é "traduzida" pelo assembler, que converte o código Assembly em um conjunto de instruções na linguagem de máquina.

![](./assets/Capturar8.PNG)


<br>

### `Linguagem Interpretada`:

- Se o `código` é executado à medida que vai sendo traduzido, como em `JavaScript`, por exemplo, num processo de tradução de trechos seguidos de sua execução imediata, então diz-se que o programa foi interpretado e que o mecanismo utilizado para a tradução é um `interpretador`.

<br>

### `Linguagem Compilada`:
- Se o método utilizado traduz todo o `código`, para só depois executar o software, então diz-se que o software foi `compilado` e que o mecanismo utilizado para a tradução é um compilador.

<br>

> Qual a MELHOR linguagem de programação?
> Qualquer linguagem de alto nível que você aprender será suficiente para sua jornada inicial.

<br>

## Tópico 3 - Compiladores

<br>

Compilador é um software essencial para programadores.

![](./assets/Capturar9.PNG)

<br>

### Mas o que ocorre nesse processo de compilação do código fonte?

<br>

![](./assets/Capturar10.PNG)

> Criar sistema de alto nível utilizando linguagens de baixo nível é inviável

Logo temos a ascensão das linguagens de alto nível para nos ajudar na criação de sistemas. Linguagens próximas da comunicação humana. Consequentemente precisávamos de um caminho para gerar a linguagem de máquina : `COMPILADORES`

- O compilador analisa linguagens de programação de alto nível e transforma em código de máquina


![](./assets/Capturar11.PNG)

<br>

### `Fase de Análise`: 
- Divide o código fonte e cria uma representação intermediária do mesmo.
- Análise `léxica`, `sintática` e `semântica`.

### `Fase de Síntese`:
- Composta por módulos de geração e otimização de código de máquina a partir da geração intermediária.

![](./assets/Capturar12.PNG)


<br>

## Tópico 4 - Pra que serve HTML

<br>

### O que é uma linguagem de marcação? 
- Uma `linguagem dee marcação` (em inglês: markup language), é um conjuton de sinais e códigos aplicados a um texto ou a dados para definir a sua configuração.
- A marcação não aparece no trabalho final.
- O termo "marcação" vem da sinalética ou "marcas de revisão" (em inglês revision marks) utilizada por redatores em provas de impressão de jornais e manuscritos.

`HTML` é o elemento básico da web, define a estrutura ou esqueleto de uma webpage.

<br>

### Linguagem de Marcação de `HiperTexto`
- `HiperTexto` refere-se aos links que conectam páginas da Web entre si, seja dentro de um único site ou entre sites.
- Links são um aspecto fundamental da web.

![](./assets/Capturar13.PNG)

<br>

![](./assets/Capturar14.PNG)

<br>

![](./assets/Capturar15.PNG)





<br>

## Tópico 5 - Para que serve CSS

<br>

### O que é e para que serve `CSS`?

- `CSS` (Cascading Style Sheets ou Folhas de Estilo em Cascata) é uma linguagem de estilo usada para `descrever a apresentação`, em outras palavras, dar estilo a um documento escrito em HTML ou em XML (incluindo várias línguagens em XML como SVG, MathML ou XHTML).
- O CSS descreve como elementos são mostrados na tela, no papel, na fala ou em outras mídias.

![](./assets/Capturar16.PNG)

<br>

![](./assets/Capturar17.PNG)



<br>

## Tópico 6 - Como pesquisar erros/duvidas de código no google

<br>

### O que fazer quando não encontrar a solução para um problema no Google?

- Na maioria das vezes não estamos fazendo a pergunta certa.
- Primeiro entenda a causa real do problema.
- Encontrada a origem do problema, é importante entender do que o problema se trata.

![](./assets/Capturar18.PNG)

<br>

1) Pesquise em inglês
2) Remova da busca qualquer palavras específicas do seu sistema.
3) Adicionar o nome da biblioteca ou linguagem de programação no ínicio da busca pode ajudar.
4) Utilize aspas duplas para buscar o termo específico, removendo conteúdo similares.
~~~
"Programação Web"
~~~
5) Caso queira buscar em um site específico (que não tenha um sistema de busca) utilize:
~~~
site:https://developer.mozilla.org introdução
~~~
6) Caso queira remover um termo específico da busca, utilize o hífen.
~~~
how manipulate html dom -jquery
~~~
7) Podemos utilizar o `before` e especificar o ano para buscar conteúdos mais antigos.
~~~
javascript before:2021
~~~
8) Podemos utilizar o `after` e especificar o ano para buscar conteúdos mais novos.
~~~
javascript after:2021
~~~
9) Podemos utlizar o .. e para intervalos de datas.
~~~
es5 announcement 2008..2011
~~~
10) Podemos utilizar o pipi "|" para comparação de tecnologias
~~~
reactjs | vuejs | angular
~~~
11) Podemos especificar o tipo de arquivo que estamos buscando
~~~
martin fowler microservices filetype:pdf
~~~
12) Podemos utilizar o `related` para encontrar termos relacionados ao que estamos buscando.
~~~
related:microservices
~~~


## Tópico 7 - Como pesquisar erros/duvidas de código no stack overflow















































