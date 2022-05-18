# Modulo 1 - Introdução, Sistemas e Aplicações

## Tópico 1 - Introdução à programação

### O que é programar?

- Um programa de computador é um produto que resulta da `atividade intelectual` de um programador. 
- Essa atividade depende de um treinamento prévio em `abstração` e `modelagem de problemas` (sua formulação e caminhos para a resolução), bem como o uso da lógica na verificação das soluções. 
- Esta atividade intelectual é traduzida em `instruções` para o computador, por meio de alguma linguage, que o faz executar operações que resolvam algum problema proposto.

Portanto, se quisermos dedfinir rapidamente o que é programar podemos dizer que: 
~~~
Programar é dar isntruções para que os computadores façam o que você quer que eles façam.
~~~

### Mas como a gente modela e resolve problemas na vida real?

- A atividade de programar consiste tanto na capacidade de `estruturar e resolver problemas` quanto na tradução dessa solução em `algoritmos` para a `codificação` em si.

### Para Assimilar:

~~~
Um algoritmos representa um conjunto de regras para a solução de um problema
~~~

### Mas como passamos essas instruções para o computador?

- Sabemos que progamar é dar instruções ao computador para ele fazer o que a gente quer que ele faça.
- Sabemos também que um algoritmo é uma forma de organizar em um conjunto de passos as operações para resolver um problema.

#### Resposta rápida: Por meio de uma `linguagem de programação`:

- As linguagens de programação são um método padronizado, formado por um conjunto de regras sintáticas e semânticas, que pode ser compilado ou interpretado e transformado em um programa de computador.

![Niveis de linguagem de programação](./assets/Capturar.PNG)

<br>

### O que é programar?

- Programar é dar `instruções` por meio de uma `linguagem de programação` para que os computadores executem a nossa `resolução de um problema`.

<br>

### Como Funciona a web?

- A internet é uma rede que interconecta computadores e outras redes de computadores e é composta por bilhões de dispositivos como servidores, roteadores, computadores e dispositivos móveis.
- Vários serviços funcionam sobre a infraestrutura da Internet como a telefonia (voz sobre IP) e World Wide Web.
- A World Wide Web é uma aplicação onde documentos e/ou páginas são interligadas através de links. É através dela que, por meio de um navegador e através de URLs, acessamos os sites e aplicações web.
- Os componentes básicos da Web são `clientes e servidores`.

![](./assets/Capturar1.PNG)

<br>

#### Clientes 

- São os aparelhos que se conectam à Internet que `acessam` as páginas Web (por exemplo, seu smartphone conectado ao seu WI-FI).
- Geralmente as páginas Web são acessadas peloas navegadores Web (Chrome, Firefox, Brave, etc.) instalados nesses dispositivos.

<br>

#### Servidores

- São computadores que `armazenam` os arquivos que compõem os sites (por exemplo, documentos HTML, imagens, folhas de estilo, e arquivos JavaScript) e disponibilizam esses arquivos/páginas/sites para serem acessados pelos dispositivos clientes.
- Para isso, o servidor deve estar conectado a Internet, e assim, poderá ser acessado através do seu `endereço IP ou nome de domínio` (por exemplo, [startese](www.startse.com) ).

<br>

#### Mas como se comunicam?

- A comunicação entre dois ou mais dispositivos na Internet é realizada por meio endereços  conhecido como endereço IP) que identificam os dispositivos na rede e portas que fornecem pontos  e conexão para aplicações e serviços específicos.
- De forma resumida, para que um dispositivo A possa se comunicar com um dispositivo B, o  ispositivo A precisa saber o endereço IP de B e saber qual a porta de B está disponível para ele (oferece o serviço que ele espera).

Quando acessamos um determinado site a partir do nosso computador, informamos para o navegador o  ndereço do site, também conhecido como `URL` (Uniform Resource Locator). E o navegador se encarrega  e descobrir qual o endereço do servidor que armazena o site.

> URL é o endereço de um determinado recurso exclusivo na Web. Esse recurso pode ser uma página HTML, um documento CSS, uma imagem, um arquivo PDF, etc.

<br>

![url](./assets/Capturar2.PNG)

<br>

#### `PROTOCOLO` (obrigatório) : 

- Informa ao navegador qual o protocolo de comunicação, pode ser `http` ou `https`. 
- Quando não digitamos na barra de endereço o próprio navegador preenche.

#### `SUBDOMÍNIO` (opcional) : 

- Serve como uma extensão do nome de domínio, geralmente utilizado para disponibilizar diferentes sites/sistemas no mesmo domínio.

#### `DOMÍNIO` (obrigatório) : 

- É basicamente o nome (identificador) do site.
- DEVE ser informado pelo usuário na barra de endereços do navegador.

#### `PORTA` (opcional) : 

- Identifica a porta em que o site está disponivel no servidor, quando não é informada o navegador preenche internamente com a porta padrão de acordo com o protocolo utilizado (80 para http e 443 para https)

#### `RECURSO(path)` (obrigatório) : 

- Identifica qual o rescurso o navegador vai buscar no servidor, quando não é informado pelo usuário o próprio navegador preenche com uma "/", que significa página inicial do site.

#### `QUERY E PARÂMETROS` (opcional) : 

- Utilizado para enviar dados no formato de chave e valor pela URL.
- No exemplo o id é a chave e 12345 é o valor.

#### `ÂNCORA` (opcional) : 

- Utilizado para exibir partes especificas da página.


<br>

## Tópico 2 - Hardware

### O que é hardware?

- O hardware é a parte física do computador.
- O termo hardware é usado para fazer referência a detalhes específicos de cada equipamento incluindo informações detalhadas sobre seus `componentes`, seu `funcionamento`, suas `restrições` e `potencialidades`. 
- Importante lembrar que hardware não é um termo que se aplica exclusivamente a computação, apesar de ser amplamente utilizado neste cenário. Não é errado dizer, por exemplo: “Levarei o  ardware de minha TV para consertar”, isso significa que o equipamento físico está com algum  efeito que precisa de conserto.

Considerando hardware como dispositivos físicos no cenário da computação, ou seja, que auxiliam  a necessidade de calcular, podemos voltar mais ainda no tempo. A Humanidade tem utilizado dispositivos para auxiliar a computação há milênios. Pode se considerar que o ábaco, utilizado  ara fazer cálculos, tenha sido um dos primeiros hardwares usados pela humanidade. A partir do  éculo XVII, surgem as primeiras calculadoras mecânicas. 

![ábaco](./assets/Capturar3.PNG)

<br>

Mas, bom, voltando ao presente, podemos pensar o hardware em duas categorias: `centrais` e `periféricos`.

![tipos de hardware](./assets/Capturar4.PNG)

<br>

### Para Assimilar:

- Os hardwares `centrais` são aqueles vitais para o funcionamento do computador, conectados diretamente à placa-mãe: a própria placa-mãe, o processador, a memória RAM e a finte de alimentação. Tudo o mais são `periféricos`.
- Importante atentar que dispositivos de armazenamento, como o HD, sçao periféricos.

<br>

### Tipos de Periféricos:
<br>

#### `De entrada` : Enviam informação para o computador: teclado, mouse, joystick, touchpad.
#### `De saída` : Transmitem informação do computador para o usuario: monitor, improessora, caixas de som.
#### `De processamento` : Processam a informação que a máquina (unidade central de processamento) enviou. Por exemplo: places de video e de som.
#### `De entrada e saída (ou mistos)` : Enviam e recebem informação do computador: monitor touch, drive gravador de CD e DVD, modem.
#### `De armazenamento` : Armazenam informações do computador e permitem sua recuperação futura: pen drive, disco rígido, cartão de memória, etc.
#### `Externos` : Equipamentos que são adicionados a um periférico: equipamentos a parte que fornecem e/ou encaminham dados.

<br>

## Tópico 3 - Software

<br>

### O que é software?

- O software é a parte intangível do computador, ou seja, a parte lógica. Um programa de  computador ou software é composto por uma sequência de instruções, que é interpretada e executada por um processador. 
- Em um programa correto e funcional, essa sequência segue padrões específicos  que resultam em um comportamento desejado.
- O termo software foi criado na década de 1940, e é um trocadilho com o termo hardware.
- Hardware, em inglês, significa ferramenta física. Software seria tudo o que faz o computador funcionar, através de instruções, excetuando-se a parte física dele.

#### Software é o que `dá vida` ao hardware:
Um hardware sem software é só um conjunto de circuitos elétricos com potencial, não executa nenhuma das coisas que atribuímos a um computador.

<br>

### Há vários tipos de software. Entre eles: `sistemas operacionais, drivers, linguagens de  rogramação, aplicativos e/ou utilitários`.
<br>

#### `Sistemas Operacionais` :
- Um sistema operacional é o software que inicializa o computador e que serve de meio de ligação entre o hardware e os demais programas.
- Fornece a plataforma que os aplicativos especializados precisam para operar e acessar o hardware.
- Toda vez que um aplicativo precisa exibir algo na tela, ele irá pedir ao sistema operacional que encaminhe seu material à saída de video.
- Toda vez que um aplicativo precisar salvar uma informação para recuperá-la posteriormente, ele irá pedir ao sistema operacional que ative o dispositivo de armazenamento (HD, pen drive, etc.).

![Sistemas Operacionais](./assets/Capturar5.PNG)

<br>

#### `Drivers` :
- Para que dispositivos sejam reconhecidos pelo Sistema Operacional, eles dependem de uma interface que gerencie os dispositivos de entrada e saída, essa interface é o `driver`.
- Auxiliam o Sistema Operacional no gerenciamento, reconhecimento e melhor uso possivel do hardware.

![Drivers](./assets/Capturar6.PNG)

<br>

#### `Linguagens de Programação` :
- Como fazemos software hoje em dia? Resposta: Com um software feito para isso.
- O processo de produção de um software exige basicamente dois elementos: uma linguagem de programação e um compilador (ou interpretador).
- A linguagem de programação é uma espécie de linguagem que se assemelha à linguagem humana, que o profissional da computação utiliza para expressar suas ideeias para que, em um segundo momento, um compilador ou interpretador às traduzem para uma linguagem que o computador consigar entender.

![Linguagem de programação](./assets/Capturar7.PNG)

<br>

#### `Aplicativos e/ou utilitários` :
- Os aplicativos são certamente aqueles com os quais você teve maior contato.
- São todos aqueles que rodam em cima do sistema operacional, como: editores de texto, planilhas, jogos, navegadores, reprodutores de música e vídeo, etc.
- Podem ser livres para utilizar, como os `softwares livres` ou podem requerer a compra de sua licença, como os `software proprietários`.

![Aplicativos e/ou utilitários](./assets/Capturar8.PNG)

<br>

### Para Assimilar:

~~~
Software é o que dá sentido ao hardware. É o que faz o hardware operar em função do usuário. Há vários tipos de software, cada um com uma função específica.
~~~

> Importante notar que todo software foi construído por pessoas através de uma linguagem de programação.

<br>

## Tópico 4 - Estrutura de um computador

<br>

- `Computação` significa o ato ou efeito de `computar`.
- Os computadores eletrônicos surgem da `necessidade de calcular` números e grandezas cada vez maiores.

O maior marco da computação que ditou a evolução do hardware até os dias de hoje foi a arquitetura proposta pelo matemático húngaro John von Neumann.

Ele propôs o conceito de `programa armazenado`, ou seja, a memória do computador armazenaria tanto as instruções a serem executadas quanto os dados a serem processados. Desta forma, as instruções poderiam ser facilmente modificdas sem a necessidade de alterar a ligação dos cabos com outros dispositivos.

Essa arquitetura dividia o computador em `Unidade central de processamento` (CPU - Central Process Unit), `Memória Principal` e `dispositivos de entrada e saída`.

Ficou conhecida como `arquitetura de Von Neumann`.

Os computadores eletrônicos são divididos em quatro gerações:

- 1ª Geração - Computadores a válvula e relé
- 2ª Geração - Computadores transistorizados
- 3ª Geração - Computadores com circuitos integrados
- 4ª Geração - Computadores com chips VLSI(Very Large Scale Integration)

![Arquitetura Von Neumann](./assets/Capture9.PNG)

<br>

Aqui temos uma esquematização da arquitetura de Von Neumann. Até os dias de hoje os computadores seguem essa arquitetura, a aperfeiçoando e aumentando a capacidade de processamento e memória.

<br>

### Processador ou CPU:

- A CPU é um microchip capaz de realizar boa parte da computação das informações.
- Sua velocidade é atribuída em função da velocidade do seu clock (relógio), que é medido em hertz (GHz).
- A frequência corresponde ao número de ciclos por segundo que o clock consegue executar.
- Quanto maior a frequência, maior a velocidade.

<br>

### Barramentos (bus):

- Os barramentos são os caminhos de dados impressas na placa mãe.
- São uma fiação que transmitem os dados de entrada ou de saída e entre os dispositivos da placa-mãe: entre a CPU e a memória, por exemplo.

<br>

### Memória:

- A memória é responsável por armazenar informações que o processador esta utilizando no momento, ou então, que irá utilizar futuramente.
- Temos dois tipos de memória:
  - Memória Principal.
  - Memória Secundária.

<br>

#### Memória Principal:

- A principal é a memória RAM (Random Access Memory).
- A cada vez que o computador é ligado, todos os "espaços" da memória são zerados e ela começa a ser novamente preenchida.
- A memória RAM é medida em bytes (especialmente gigabytes).
- Quanto maior a quantiadde de memória RAM disponível, maior é o número de programas ou atividades que poderão ser utilizados ao mesmo tempo, e quanto maior a frequência em `hertz` da troca desses dados, mais fluída a transição entre programas e execução das atividades.

<br>

#### Memória Secundária:

- A memória secundária é a responsável pelo armazenamento, são os HDs e SSDs.
- As informações armazenadas nestes dispositivos persistem.
- O HD (hard disk ou disco rígido) é um dispositivo eletromecânico que contém alguns discos magnetizados sobre os quais uma caeça de leitura e gravação consegue acessar os dados.
- O SSD (Solid State Drive ou Unidade de Estado Sólido) é uma alternativa eletrônica ao HD, ela armazena dados muito mais rápido que um HD convencional, funciona por meio de memória flash, que é como a RAM, mas não volátil, ela consegue manter as informações mesmo sem energia.

<br>

#### Periféricos de entrada:

- Os periféricos de entrada são em geral os dispositivos que nos permitem fornecer dados ao computador.
- É através deles que informamos o que precisamos que seja feito e com quais informações.
- Os periféricos de entrada mais conhecidos são o teclado e o mouse.

<br>

#### Periféricos de saída:

- Os periféricos de saída nos oferecem o resultado do processamento.
- É através deles que podemos visualizar nossa interação com o computador.
- Os mais comuns são os monitores e as impressoras.

<br>

## Tópico 5 - Internet

<br>


### Como surgiu a internet?

<br>

- A ideia de algo como internet surge em contextos militares na década de 60, havia um grande temor em relação a possíveis ataques nucleares. 
- Pesquisas buscavam desenvolver uma cadeia de comunicações onde não existisse um ponto central que, ao ser destruído, colocaria em colapso todo o sistema de comunicações.
- Em meados de 1962, os Estados Unidos criaram a Cadeia de Comunicação Distribuída (CCD), que era composta por vários computadores interligados por várias linhas telefônicas diferentes, que objetivava-se dividir o volume de dados a ser trafegado entre os computadores em pequenos “pacotes”, despachando-os por meio das diferentes linhas telefônicas até um computador de destino. 

<br>

Neste modelo, na eventual falha de um dos `pacotes` por meio de um dos `caminhos`, o sistema poderia utilizar um caminho equivalente, ou seja, não há um ponto único de falha. Uma eventual interrupção em alguma linha de transmissão `não interrompe completamente o sistema`.

A ancestral da internet foi a `ARPANET`. Foi a primeira `rede de computadores` por comutação de pacotes. Em 1966 a ARPANET estava instalada em 17 locais diferentes nos quais computadores conectados às linhas telefônicas conseguiam trocar informações. Em um primeiro momento, sua utilização foi exclusivamente militar.

<br>

### Mas como isso virou a `internet` que conhecemos hoje?

- Com constantes otimizações e incorporações de novas tecnologias à ARPANET, como o desenvolvimento do `protocolo de rede, Transmission Control Protocol/Internet Protocol (TCP/IP)` em 1982 e que, depois, foi liberado para utilização civil, até hoje, tem se mostrado uma das melhores alternativas para comunicação entre computadores.
- Com a adoção de um protocolo único e padronizado, tornou-se viável conectar computadores de diferentes fabricantes em redes com diferentes meios de distribuição.

<br>

### Protocolo de rede:

- Um protocolo de rede é um conjunto de regras que definem a forma como dois sistemas se comunicam.
- É uma espécie de língua falada entre os dispositivos.
- Se ambos 'falam' o mesmo protocolo então a comunicação pode ser estabelecida.

<br>

#### Como se dá o acesso à Internet:

- Por meio de uma Internet Service Provider (ISP) ou Provedor de Serviço de Internet e utiliza-se de, pelo menos, três componentes (CPE, rede de acesso e POP)
- Customer Premise Equipment (CPE) é o equipamento que conectar o dispositivo à rede de acesso (exemplo: modem).
- Rede de acesso é o tipo de infraestrutura que liga o dispositivo ao provedor de internet (exemplos: cabos de cobre, fibra ótica, WI-FI).
- Point of Presence (POP) é o ponto de presença do provedor onde estão os equipamentos que atribuem ao dispositivo um endereço IP, dando-lhe acesso à internet.

<br>

### Endereço IP e MAC Address:

- Para que um computador possa se conectar a internet e se comunicar com outros computadores, faz-se necessário que este recea um número de identificação - esse número é conhecido como endereço Internet Protocol (IP).
- Para entender a importância de um endereço IP, podemos fazer uma analogia com o sistema de telefonia: para que duas pessoas conversem entre si, ambas precisam se um número telefônico (origem e destino).
- O mesmo se aplica aos computadores conectados à internet: cada um, no momento em que se conecta a um provedor de acesso, recebe um número (número IP), a partir do qual pode realizar 'chamada" (conexões) com outros computadores que também estejam conectados à internet.
- Mas como o provedor de acesso sabe se são aparelhos diferentes conectando à internet?
  - Pelo MAC Address! O endereço MAC é um número único de cada máquina, que eprmite distinguir e identificar um aparelho específico.
  - Permitindo bloquear ou garantir aceso de um aparelho específico à redes privadas por exemplo.
- Um endereço de internet, IP na versão 4, é um número escrito em quatro partes (octetos), cada uma variando de 0 a 255 – por exemplo: 200.132.39.115.
- É importante ressaltar que um endereço IP não identifica necessariamente, um equipamento individual, mas sim uma conexão.
- Podemos encontrar equipamentos (gateways) conectados a várias redes que possuem mais de um endereço IP (um para cada conexão).
- O endereço MAC é formado por um conjunto de 6 bytes separados por dois pontos (“:”) ou hífen (“-”), sendo cada byte representado por 
dois algarismos na forma hexadecimal, como por exemplo: "00:19:B9:FB:E2:58".


### Outros Conceitos Importantes: `DNS` E `HTTP`:

<br>

#### `DNS`:

- Para facilitar a memorização dos endereços, foi implementado um sistema de nomes de domínio - DOmain Name System (DNS) - através do qual é possivel traduzir um endereço, como www.mec.gov.br, em um endereço que nos remete até a rede desejada - nesse caso, a do Ministério da Educação (MEC).
- O DNS é um sistema hierárquico que passou a ser utilizado em 1984, fundamentado em uma base de dados distribuída hierarquicamente na qual os equipamentos realizam consultas para descobrir o endereço IP dos computadores que precisam ser conectar.

<br>

#### `HTTP`:

- É o protocolo que nos permite navegar entre páginas na internet.
- HTTP significa `Hypertext Transfer Protocal` ou Protocolo de Transferência de Hipertexto.
- O formato do texto criado para ser transportado pelo protocolo foi chamado de HTML (HyperText Markup Language) e conssite de uma linguagem de marcação pela qual é possível, por meio de comandos (tags), incluir ligações entre textos - inclusive entre materiais publicados em diferentes locais.
- Foi criado no meio dos anos 90 por Tim Berners-Lee, um cientista de CERN, para ajudar a organizar os textos e pesquisas de seus companheiros de CERN.
- Além de um protocolo (conjuto de regras para que dois dispositivos 'conversem') e de uma linguagem de marcação (para permitir que os usuários se expressem), era necessário um software que, utilizando-se do protoclo desenvolvido, conseguisse obter os documentos escritos em HTML, interpretá-los e exibi-los.
- Por meio deste software,esperava-se que o usuário 'navegasse' pelo hipertexto, ou seja, ao encontrar no texto uma ligação com outro material, com um simples clique, o usuário seria direcionado para uma nova página/conteúdo.
- Diante de tal necessidade, Tim Berners-Lee criou um protótipo daquele que viria a ser um dos software mais indispensáveis para quem deseja utilizar a internet: o navegador (ou browser).

<br>


## Tópico 6 - Sistemas Operacionais

<br>

### O que é um Sistema Operacional?
<br>




















































