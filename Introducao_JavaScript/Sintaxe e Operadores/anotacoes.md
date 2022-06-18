# Sintaxe e Operadores

### Operadores

**Tipos de Operadores** 

![image-20220617110804718](C:\Users\Mateus Magalhães\AppData\Roaming\Typora\typora-user-images\image-20220617110804718.png)

* Aritmética
* Atribuição
* Comparação
* Lógica
* Condicional

### Operadores de Atribuição

* = é o mais comum e serve para atribuir um valor. (x = y)
* += atribui valor e faz uma operação de soma. adiciona o valor de uma variável a outra variável (ex: x += y/// equivalente a: x = x+y)
* **= atribui valor e faz uma operação de multiplicação (ex: x * =y///equivalente a: x = x * y)
* /= atribui valor e faz uma operação de divisão (ex: x/=y///equivalente a: x = x / y)
* %= atribui valor e faz uma operação de módulo, retornando o resto da divisão entre os dois números que participam da operação (ex: x%=y///equivalente a: x = x %y )

### Operadores de Aritmética

+ "+" adição
+ "-" subtração
+ "*" multiplicação
+ "**" exponencial (elevando número ao número que vem depois do operador)
+ "/" divisão
+ "%" módulo (retorna o resto da divisão entre 2 números)
+ "++" incrementar (adicionar 1 da variável)
+ "--" decrementar (subtrair 1 da variável)

### Operadores de Comparação

== igual a (pergunta se os valores são iguais, sem fazer checagem de tipo)

=== mesmo valor e mesmo tipo (perguntas se os valores são iguais e faz checagem de tipo. é mais usado)

!= diferente (valor, sem checar tipo)

!== valor e tipos diferentes (chega valor e tipo)

">" = maior que

< = menor que

"">= maior ou igual

<= menor ou igual

### Operadores de Lógica

&& "e" lógico (serve para que duas afirmações sejam verdadeiras ex: "se condição a e condição b forem verdadeiras, quero executar determinada execução")

|| "ou" lógico (parecido com o de cima, mas só precisa que uma das afirmações sejam verdadeiras para executar a instrução)

! "não" lógico (serve para acessar o dado que é o oposto do que estamos usando após o náo lógico. ex: se usar um não lógico depois de um true, espera receber um false)

### Operador Condicional - if ternário

![image-20220617112701958](C:\Users\Mateus Magalhães\AppData\Roaming\Typora\typora-user-images\image-20220617112701958.png)

Equivale a um:

if (condition)

​	statement;

else

​	statement;

### Atividade prática

criar a função:

function comparaNumeros(num1, num2) {

adicionar constante que checa se os numeros sao iguais em valor e tipo:

const saoIguais = num1 === num2;

adicionar constante da soma:

const soma = num1 + num2;

Criando a condicional:

if(saoIguais) {

​	return "São iguais"

}

​	

​	return "Não são iguais"

}

> > > repare que, se adicionarmos uma ! ao if (if(!saoIguais)), teremos o valor oposto. Teremos a segunda resposta primeiro, e a primeira depois.

Agora vamos criar com um **IF TERNÁRIO**:

Ao invés de:

if(saoIguais) {

​	return "São iguais"

}

​	

​	return "Não são iguais"

}

**Usamos:**

**return saoIguais ? "São iguais" : "Não são iguais";**
