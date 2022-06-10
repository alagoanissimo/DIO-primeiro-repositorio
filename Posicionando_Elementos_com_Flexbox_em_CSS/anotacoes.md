# Posicionando elementos com Flexbox em CSS

### CSS Flexbox

Serve para criar layouts responsivos, sem necessidade de definir valores fixos. Assim, criamos páginas que se adaptam às mais diversas resoluções, sem a necessidade de setar e calcular esses valores para que se adaptem.

Ele visa oferecer distribuição de espaço entre os itens de uma interface e recursos de alinhamento. 

### Flex container = é a tag que envolve os itens. Ela possui itens-filhos. Nela, aplicamos a propriedade "display:flex", que transforma seus filhos-diretos em flex itens. A incialização do container pode ser feita em qualquer tipo de tag, do < div> aos links. A partir do momento em que a tag possui itens filhos, pode ser aplicada a propriedade display:flex.

![GitHub - marcelopoars/flexbox](data:image/png;base64,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)

O Flex Container contém propriedades relacionadas. São elas:

* display = inicializador do container
* flex-direction = direciona itens em linhas ou colunas
* flex-wrap = aplica-se para quebra de linha ou não
* flex-flow = abreviação pro direction e wrap
* justify-content = alinha os itens de acordo com sua direção
* align-itens = alinhas itens de acordo com o eixo do container
* align-content = alinha linhas do container

### Flex Item = são os elementos-filhos diretos do Flex Container. Também podem se tornar Flex Container, recebendo a propriedade display:flex 

Nada impede que um elemento seja um flex container e um flex item ao mesmo tempo. Assim, reaproveitamos e reinventamos o layout

![CSS Flexbox: O que é e como funciona? O guia CSS Flexbox! | Insights para  te ajudar na carreira em tecnologia | Blog da Trybe](https://lh3.googleusercontent.com/5sklzRAu1ozoN9c6L-ZpHxHMaTfaAH4-SmpsCNPPeAi0fMicOyTK6dFWGRDrPQQwTvxv5dkFkM6vm4R_aCalfNoi8HFQHbd1wJ5kygXolj7fDvW9vHhH7jnVt0J-lSeCVKsC_Del=s0)

Propriedades relacionadas do Flex Item:

* flex-grow = define fator de crescimento
* flex-basis: define tamanho inicial do item antes da distribuição do espaço restante dentro do container
* flex-shrink = define capacidade de redução
* flex = abreviação para grow, basis e shrink
* order = relacionado a ordem de distribuição e listagem dos itens
* align-self = define o alinhamento de um item específico do container

# Estrutura básica display:flex

Pertence ao Flex Container.  Ele é a propriedade de inicialização, transformando qualquer tag em um elemento do tipo flex container. Assim, todos os filhos diretos da tag tornam-se flex itens.

Dica: usando div.item, ao adicionar uma * e o número de itens desejado, ele cria automaticamente. Ex: div.item*3 cria 3 itens

**Como criar um flex: abra a tag < style> logo abaixo da tag < title> e adicione as seguintes infos:**

Ex:

< style>

​		.flex{

​				max-width: 300px;

​				padding: 10px;

​				border: 2px solid black;

​				display: flex;

}

​		.item{

​				background-color: aqua;

margin: 5px;

}

< /style>

E, na tag < body>, crie os itens filhos. Você adiciona a classe "flex" a tag < div>-mãe e a classe "item" aos < div>-filhod, assim, ex:

< body>

​	< div class="flex">

​		< div class="item">item 2< /div>

​		< div class="item">item 2< /div>

​		< div class="item">item 3< /div>

### Estrutura básica do Flex direction

Pertence ao flex container. É a propriedade que estabelece eixos dentro do container, definindo assim o comportamento dos itens. A direção que os itens são colocados no flex container. 

Os eixos são:

* row (padrão): acontece quando inicializamos o container. Faz com que os itens sigam a direção da escrita de um texto (da esquerda pra direita). No caso, item1-item2-item3-item4
* row-reverse: sentido oposto à direção de um texto. Se temos 4 valores, ele traz a ordenação inversa: item4-item3-item2-item1
* column: altera para a ordenação normal em eixo vertical, de cima pra baixo, na ordem normal, item1-item2-item3-item4
* column-reverse: ordenação reversa em eixo vertical, de baixo para cima. Ou seja, item4-item3-item2-item1

Isso é muito útil pq é muito comum usar a orientação dos elementos em tela quando trabalhamos com diferentes dimensões de tela.

# Estrutura básica do flex wrap

Pertence ao flex container. É a propriedade que define se os itens devem ou não quebrar a linha. Por padrão eles não quebram linha, compactando eles dentro do limite do seu próprio conteúdo e do container. 

* nowrap: é o padrão, não permite a quebra de linha.
* wrap: permite a quebra de linha assim que um dos flex itens não puder mais ser compactado, para evitar que itens vazem e deixem tudo horroroso. Começa na linha de cima e quando fica cheio desde para a linha de baixo.
* wrap-reverse: mesma lógica do wrap, mas no sentido contrário. Começando na linha de baixo e, quando não couber mais, o resto vai para a linha de cima.

# Estrutura básica com flex flow

Pertence ao flex container. É um atalho para flex-direction e flex-wrap. Ao invés de utilizarmos duas linhas para essas propriedades, podemos dizer esses valores em apenas 1 linha. 

Ex: 

**adicione essa classe na tag < style>:**

.rr-wrap{

​    flex-flow: row-reverse wrap-reverse;

  }

**adicione essa tag+família na tag < body>:**

< h1>row-reverse wrap-reverse</h1>
    < div class="flex-container rr-wrap">
        <div class="item">1</div>
        <div class="item">2</div>
        <div class="item">3</div>
        <div class="item">4</div>
        <div class="item">5</div>   
        <div class="item">6</div> 
    </ div>

# Estrutura básica do justify content

Pertence ao flex container. Essa propriedade se encarrega do alinhamento dos itens no container e da distribuição de espaço entre eles. Se há itens-filhos ocupados 100% do espaço do container, sem margem ou algo do tipo, esse comando não se aplica.

Variações:

* flex-start: alinha no início do container.
* flex-end: leva os itens, de acordo com a sobra de espaço e respeitando o limite do conteúdo, pro fim do container.
* center: leva todos os elementos para o início do container.
* space-between: cria um espaço igual entre os elementos. ele pega o primeiro elemento e coloca muito próximo a borda esquerda do elemento, início, e leva o último para a borda direita, final do elemento.
* space-around: trata do espaçamento do meio, tornando-o duas vezes maior que o inicial e o final. O primeiro espaçamento do elemento 1 p/ esquerda e do elemento 5 p/ direita são iguais. 

# Estrutura básica e prática com align items

Trata do alinhamento dos flex items de acordo com o eixo do container. Ele é diferente para eixo em colunas e eixo em linhas. Permite o alinhamento central no eixo vertical. Alinhamento total ao centro. Não precisa necessariamente saber a altura dos itens-filhos, ao contrário do justify content, que aplica altura no container. O align items pega a proporcionalidade e expande os elementos. 

### Tipos de alinhamento

* center: alinhamento dos itens ao centro
* stretch: padrão, faz com que flex itens cresçam igualmente, de acordo com o maior item do container
* flex-start: alinha os itens do início do container (parte de cima)
* flex-end: alinha os itens no fim do container (parte de baixo). muito útil para gráficos
* baseline: alinha de acordo com a linha base da tipografia dos itens

### Para atingir o alinhamento total ao centro com align-items, faça:

**Crie uma < section> com a classe container central center dentro da tag < body>. Dentro da section, crie uma tag de texto < div> com a classe item, assim:**

< section class="container central center">

        < div class = "item">Lorem Ipsum is therefore always free from repetition.< /div>

  < /section>

**Depois, crie a classe central, assim:**

.central{

​    height: 500px;

​    justify-content: center;

​    align-items: center;

  }

**Por fim, crie a classe central novamente, mas dessa vez atingindo os itens que estão dentro da < section> que você criou no primeiro passo, assim:**

.central .item{

​    flex: 0;

​    padding: 20px;

  }

# Estrutura básica align content

Última propriedade relacionada ao flex container. É responsável por tratar o alinhamento no eixo vertical. 

Ele precisa respeitar algumas orientações:

* Container precisa utilizar quebra de linhas
* A altura do container precisa ser maior que a soma das linhas dos itens. Ex: supondo que a altura das suas linhas é de 20px, 40px na soma, é preciso que o container seja maior que a soma dessas linhas

**Tipos de alinhamento**

* center = alinhamento ao centro
* stretch = padrão, faz com que os itens cresçam igualmente tendo como base o maior deles
* flex-start = alinha itens no início
* flex-end = alinha itens no final
* space-between = cria espaçamento igual entre os elementos
* space-around = espaçamentos do meio são duas vezes maiores que os do início e do final

# Propriedades relacionadas aos flex items

### Estrutura básica flex-grow

Define a proporcionalidade de crescimento dos items, sempre respeitando o tamanho de seus conteúdos internos. Não permite que o conteúdo vaze, etc.

Não funciona caso tenhamos adicionado justify-content ao flex container. Só se pode trabalhar usando NÚMEROS, ou 0 ou algum número relacionado à proporção de crescimento. Quando se aumenta o valor do fg-, aumenta o tamanho do item.

### Estrutura básica flex-basis

Propriedade que estabelece o tamanho inicial dos items antes da distribuição do espaço restante dentro dele, usando como base o conteúdo interno disposto. É como se ela pegasse o tamanho mínimo que ele vai precisar ter. Depois, distribui o tamanho da sobra de espaço antes e após o conteúdo.

**Valores possíveis**:

* auto: quando o item nao tiver tamanho pré-definido, ele será proporcional ao conteúdo. se tiver flex grow definido tentará adaptar os itens tomando o tamanho mínimo sempre igual ao total do container.
* px, %, em, ...: esse valor é o tamanho mínimo que o item vai ter. a partir do momento em que o conteúdo interno do item for muito maior que o valor mínimo definido, ele crescerá até não ter mais espaço e poderá até vazar do item. assim, passa a não valer
* 0 (zero): temos uma relação direta com a definição do flex-grow. se tivermos um flex-grow definido em 1 e um flex-basis em outro valor, precisaremos nos preocupar com o crescimento do item e a distribuição do espaço que sobrará ao redor do flex item.

basis + widht = é a ligação do basis com o tamanho mínimo referente ao conteúdo. ele é utilizado relacionado ao grow pq este tem relação com o máximo de crescimento do espaço que restará no item. ou seja, como ele vai crescer

### Estrutura básica flex-shrink

Estabelece a capacidade de redução ou compressão do tamanho de um item. Temos o tamanho de um item, ele vai ter alguns comportamenmtos esperados. Se o shrink for em 1 permite que os itens tenham seus tamanhos reduzidos proporcionalmente, se shrink estiver em 0 ele não permite a redução dos itens, uma vez que você tenha o seu basis setado em 100px por ex. se a propriedade estiver em 2, 3 ou mais, significa que o item poderá ser reduzido 2, 3 vezes ou quantas forem necessária.
