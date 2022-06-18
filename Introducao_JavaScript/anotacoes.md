# Intro ao JavaScript

Características básicas:

* Linguagem interpretada = significa que está sendo rodada em tempor real e o código é disponibilizado instantâneamente. As linguagens compiladas, como C++, precisam passar pelo computador antes do output. O JavaScript compila em tempo real. Enquanto vc coda, já recebe os resultados.
* Linguagem baseada em protótipos = é uma base para a grande maioria das estruturas de dados do javascript. É um conjunto de funções e possibilidade em comum nessas estruturas
* Linguagem multiparadigma = escolhe se quer trabalhar com orientação a objetos, programação funcional ou programação estruturada. Dependendo da sua necessidade. Vc n se prende a apenas um paradigma, isso é top.
* Comumente utilizado em aplicações web client-side = é a parte da aplicação que interage com o usuário. O JS é a linguagem da web e que browsers entendem, por isso é utilizada para criar websites que têm qualquer tipo de interação.
* Segue o padrão ECMAScript = ECMAScript é mais ou menos o padrão para várias linguagens, um conjunto de normas que diz quais funcionalidades estão sendo lançadas na linguagem. 

### Evolução do JS

* Criado em 95, mas só passou a seguir o ECMAScript em 97. 
* Com ECMAScript3, em 99, vieram as expressões regulares. Algo muito utilizável para validar e-mails. O try catch tbm, para tratar erros.
* ECMAScript 5, em 2009, traz o JSON que dá suporte para consumir API, mocar algo. 
* Em 2015 o ECMAScript 6 chega.

### ECMAScript 6

Foi o mais pica. Permitiu usar o paradigma da orientação a objetos, permite declarar classes. Jeitos novos de concatenar variáveis, scripts e muito mais. 

### Aplicações do JS

Não é só fazer site, apesar de ser a linguagem da web. Possível desenvolver Mobile, Smartwatches, Games, Internet of Things (IoT. Utilizando NODE é possível criar rotinas para sua Alexa) e APIs.

# Recursos básicos do JS

### Manipulando um arquivo

Para fazer um comentário de 1 linha, basta digitar // antes dela.

Para fazer um comentário de várias linhas, digite /* no início e */ no final.

CTRL + 1 (no meu pc...) tornar comentário tudo que estiver selecionado

### Variável e constante

Digamos que há a seguinte função de primeiro grau: ax + b = 0. Nela, a e b são CONSTANTES, coeficientes. Ou seja, não mudam. Já x, é a nossa VARIÁVEL, pois ele pode mudar.

Ex: Qual o f de 1?

f(1) = a.1 + b

<--- a e b nunca vão mudar. mas o x, que é o 1, pode sempre mudar. Podemos ver o f de 2, o f de 3+5, ad infinitum... o valor de x sempre vai mudar.

2x+3 <-- 2 e 3 são constantes. x é variável.

Quando criamos uma variável no JS, é bom dar um nome a ela, com letras minusculas.

Constanters são em letras MAIUSCULAS.

Ex: compra com desconto

var desconto = 0.2;

const PRECO = 2;

var total = PRECO - desconto 

### Funções

Na programação não é muito diferente da matemática. 

Para declarar no JS, usamos a palavra function e damos nome a ela. Como "chamar"/iniciar uma função? Ex:

function soma (a, b) {

  console.log(a + b);

  return a + b;

}

soma(3, 5);

# Executando um arquivo .js

### Console

Pode ser utilizado numa página web ou no terminal

### Página web

Ao clicar em inspecionar numa página, há a aba "console". Lá, é possível fazer vários tipos de operações. Quando vc está trabalhando com elementos web, utiliza o console na página mesmo.

### Node.js

Chamando console.log em qualquer parte do código, é possível ver o output rodando no terminal.

# JS em uma página web

### Estrutura de projeto

É uma boa prática separar arquivos por pasta. 

Assets são os artifícios/ferramentas que vc tem, imagens, arquivos CSS, JS. Eles são encontrados na pasta assets. Todos os componentes da páginas html.

### Inserindo JavaScript no HTML

Para importar CSS, faça assim:

< link rel="stylesheet" href="./assets/css/style.css" /> 

Quando o JS for muito grande, insira ele antes da tag de fechamento < /body>. Faça isso porque se colocá-lo antes ele pode tentar interagir com elementos que ainda não foram renderizados.

E, para importar JavaScrip, faça assim:

<s cript src=" ./assets /js/ script.js ">< /script>

### Interagindo com elementos do DOM

DOM = Document Object Model. Ele mostra tudo o que há disponível no documento/janela web. É a estrutura dos elementos dentro da janela. Ele é uma árvore de referências. 

![O Que é DOM (Document Object Model) e Quais Suas Vantagens](https://lh5.googleusercontent.com/SQ3qz32VvBhTPFTeGtWOzPVhcv-mfB7C8mj6k4C1IVOttNGWf71T9s8Pq9QY4F_AlMbEKMwgnMGh5XEQf2v8-UU-G6xZc984pnSwfJvKF-CxSEOsBafgKCkkg6tCWgH6Ni9bb_N8)

**Como manipular o CSS usando o script? Ex: mudar a cor de um elemento pelo console.**

Primeiro é preciso selecionar os elementos pelo tagname. Depois, definir a variável do elemento, executá-lo e, então, mudar a cor do elemento.

Vamos ver:

*document.getElementsByTagName('h1')* <-- seleciona elemento pelo tagname "h1", que, no caso, é o hello world
*HTMLCollection [h1]0: h1length: 1[[Prototype]]: HTMLCollection*
*var heading1 = document.getElementsByTagName('h1')[0]* <-- define o elemento h1 como variável
*undefined*
*heading1*

*< h1>Olá, mundo!< /h1>* <-- elemento h1

*heading1.style.color = 'red'* <-- comando para mudar a cor
*'red'*

# Atividade prática

### Criando um contador

* No JS, primeiro é preciso definir a variável "current number" no span, assim:

var currentNumberWrapper = document.getElementById('currentNumber')

* Depois, definir a função de incrementar (somar):

### Desafio to-do list

# Mercado de trabalho

### Frameworks e bibliotecas

* VueJS
* Angular
* React
* jQuery

Antes de mexer neles, é necessário aprender o vanilla JS. Os frameworks e bibliotecas são ferramentas que foram desenvolvidas para facilitar e acelerar o desenvolvimento em JS. Com elas, há várias funcionalidade que podem ser plugadas no código em JavaScript.

### Mercado de trabalho

