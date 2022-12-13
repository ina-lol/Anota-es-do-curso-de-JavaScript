# Aula 2:

## História e evolução do JavaScript:

- Criada pela NetScape cujo nome era LiveScript até o Java se tornar famoso e fazer a NetScape adotar esse nome
- ECMAscript é a versão padronizada do JavaScript
- JScript é a versão da **Microsoft** do JavaScript que tinha comandos propios e consertava alguns bugs
- Existia um grupo dentro da NetScape cujo nome homenageava o Godzilla, o **Modzilla** que mais tarde com a queda da NetScape virou a **Mozilla**
- As versões do JavaScript eram nomeadas por 1, 2, 3 & etc, mas como as expectaticas da versão 4 eram tão grandes a numeração 4 foi pulada logo para a 5, esse sistema de numeração parou na versão 6 que dai por diante as versões do JavaScript são nomeadas pelo ano, a maioria dos Navegadores demoram um tempo pra adotar as versões novas do JavaScript então o curso e baseado na **versão 6** ou **ES6**
> ### Exemplo:
>
> > **Por numero 1, 2, 3 e adiante:** JavaScript ES6<br>
> 
> > **Por ano:** JavaScript ES2017
- JavaScript também tem varias bibliotecas que também pode tirar o aspecto client side e dar o aspecto server side, que significa que o JavaScript pode funcionar em servidores, graças a o **Motor V8** da **Google**, que foi modificado para funcionar **fora dos navegadores** (client side), para funcionar em servidores, o nome dessa ferramenta é [Node.js](https://nodejs.org/en/)

## 🚨 Assistir a video aula 2 "Como chegamos até aqui"

No intuito de conhecer bibliotecas e ferramentas novas, como o [Node.js](https://nodejs.org/en/), [Angular](https://angular.io/), [Vue](https://vuejs.org/), [React](https://pt-br.reactjs.org/) e etc

# Aula 3:

## Proposta:

> **Praticar em vez de só assistir**, afinal você consegue aprender vioção só olhando um video? Não né então coloque isso na programação e pratique também, ajudar as pessoas e juntar a "galera" e aprender, ler manuais e referencias, anotar tudo e pensar em projetos pessoais e tentar resolver eles com programação no caso o JavaScript


## Primeiros passos do JavaScript:

### 📚 Bibliografia recomendada pelo Gustavo Guanabara (Professor desse maravilhoso curso!):

#### Opções pagas:

- [JavaScript: O guia definitivo por David Flanagan](https://www.amazon.com.br/JavaScript-Guia-Definitivo-David-Flanagan/dp/856583719X)
- [JavaScript: O guia do programador por Maurício Samy Silva](https://www.amazon.com.br/Javascript-Guia-Programador-Maur%C3%ADcio-Silva/dp/8575222481)

#### Opções gratuitas:

- [Guia de referência da Mozilla (Empresa que criou o JavaScript, a antiga Netscape)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [Guia de referência da ECMA (Versão 6, a usada no curso)](https://262.ecma-international.org/6.0/)

### Logica de programação é sim importante!

- Uma boa forma de ja iniciar na programação (e também obrigatória convenhamos) e aprender toda a logica da programação, seja utilizando o portugol ou etc.

### Cada linguagem é unica, tem suas áreas e é especifica pra algo

> #### Dicionario:
>
> > **Low level ou baixo nível:**
> A linguagem de baixo nível trabalha mais diretamente com o hardware, é uma linguagem mais próxima da linguagem de máquina. Assembly é um exemplo de linguagem de baixo nível.
> 
> > **Kernel:** E como se fosse a coluna vertebral do sistema operacional, todos tem, não tem quem não tem, um exemplo de kernel famoso é o Linux (Sim o Linux é um kernel e não um sistema.).

- Não seja esse tipo de pessoa, cada linguagem é unica para alguma coisa, como o C, que é low level e é usada para fazer kernels & etc, o JavaScript que ja é high level e é usado para fazer sites, aplicativos & etc

### Não aprenda JavaScript por frameworks ou etc.

- O JavaScript ou ECMAscript puro é o ponto de partida para **TODO MUNDO** aprender essa linguagem.

### ⏱️ Não deixe tudo pra cima da hora, aprenda, reflita e pratique o que você vai ver nesse curso

- Como citado la encima, você consegue aprender só assistindo e pronto? Não né
- Assista e pratique diaramente o que você vai ver nesse curso

### Requisitos para continuar o curso:

> **🚨 TODOS ESSES REQUISITOS SÃO OBRIGATÓRIOS PARA CONTINUAR NO CURSO**

#### Navegador:

> Você pode usar o navegador que você quiser mas umas boas opções são o Google Chrome e o Chromium

- Uma opção bem popular, e que talvez você está usando é o [Google Chrome](https://www.google.com/intl/pt-BR/chrome/browser-tools/), criado pela mesma empresa que patrocina o curso de JavaScript do curso em vídeo, recomendado pelo Gustavo Guanabara
- [Chromium](https://download-chromium.appspot.com/) que é a versão codigo aberto do Google Chrome
> 🚨 **Use sempre uma versão oficial do Chromium**, como ele é codigo aberto **pessoas mal intencionadas modificam o código do chromium e fazem versões maliciosas deles**, normalmente são distribuidas em instaladores & etc, então verifique se você tem uma versão limpa e oficial do Chromium
- [Firefox](https://www.mozilla.org/pt-BR/firefox/new/), navegador da propia mozilla, e que inclusive o navegador que eu uso

#### Editor de codigo (não use o notepad kk):

- [Visual Studio Code](https://code.visualstudio.com/download), feito pela propia microsoft é uma das melhores opções que você pode ter para programar, usado no curso pelo Gustavo Guanabara
- [Sublime text](https://www.sublimetext.com/), simples, funcional e leve uma excelente opção
> O atom não está nessa lista pois não é mais mantido, Fonte: [Tecnoblog](https://tecnoblog.net/noticias/2022/06/10/github-vai-cancelar-editor-de-codigo-atom-e-focar-em-opcao-da-microsoft/)

#### Node.js:

- [Node.js](https://nodejs.org/en/download/), para executar o JavaScript fora do navegador

# Aula 4

## Criando o seu primeiro script em JavaScript

> Essa é uma parte um pouco mais prática então vá para um computador e pratique junto com o vídeo

### Comandos usados no vídeo:

```js
window.alert('Minha primeira mensagem!'); /* Cria um alerta*/
window.confirm('Está gostando de JavaScript?'); /* Cria um alerta de confirmação com ok ou cancela*/
window.prompt('Qual é seu nome?'); /* Cria um alerta com um prompt*/
```
### Resultado final do exemplo 1:

ex1.html
```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exemplo 1 | Curso de JavaScript</title>
    <style>
        body {
            background-color: #6d6dac;
            color: white;
            font: normal 20pt arial;
        }
        h1 {
            color: #fde404;
        }
    </style>
</head>
<body>
    <h1>Olá, mundo!</h1>
    <p>Já me livrei da maldição!</p>
    <script>
        window.alert('Minha primeira mensagem!');
        window.confirm('Está gostando de JavaScript?');
        window.prompt('Qual é seu nome?');
    </script>
</body>
</html>
```

# Módulo B | Comandos basicos:

## Conteúdos desse módulo:

- Armazenar dados
- Tratamento de dados
- Operações com dados

# Aula 5:

## Comentários em JavaScript

- Tem o proposito de documentar o código para ser mais facil de manipular ele

- Existem 2 tipos de "comentários" em JavaScript:

> Linha única
> 
> ```js
> //Isso é um comentário de linha única

> Mútiplas linhas
>
> ```js
> /* Este é um comentário de mútiplas linhas, aproveita e se inscreve
> no Curso em vídeo para mais cursos como esse */

- Já ficou bem evidente a função dos 2 né? Não? Ok, o comentãrio de linha única serve só para 1 linha, já o de mútiplas linhas como o nome já diz serve para mútiplas linhas, mais de uma linha de código


## Tipos de dados e variavéis:

> Leia sempre um sinal de **igual** (=) no JavaScript de **"Recebe"**

> Null é igual a **"nulo"**

> ⚠️ No JavaScript moderno, além de utilizar a palavra **var** para declarar uma variável, também podemos usar a palavra **let**, porém **let** não pode ser redeclarado ele pode ser atualizado
>
> **Exemplo**:
>
> ```js
> let greeting = "Diga oi";
> greeting = "Na verdade fale olá"; // Caso tiver um let no inicio dessa linha, o código retornará um erro
> ```

- Variavéis no JavaScript são compostas por um "declarador" usado pelo Guanabara o **var** mas também tem outros jeitos de declarar variavéis, porém cada um tem suas limitações e escopos (ver avisos acima), e também são compostas por um "identificador" que é o nome que essa variável recebe, e o que essa variável recebe

```js
let vaga1 = 'carro1';
```

- Nesse exemplo acima eu estou declarando uma variável, chamada vaga1 que **recebe** a string "carro1", eu usei o let então eu posso mudar o valor dela, porém não posso redeclarar ela

#### Identificadores:

- Podem começar com **letra**, **$** ou _
- Não podem começar com números, exemplo se a variável que eu declarei acima for 1vaga daría erro
- É possível usar **letras** ou **números**
- É possível utilizar **acentos** e **símbolos**
- Não podem conter um **espaço**, deve ser substituído por um _
- Não podem ser **palavras reservadas** como a palavra **function** ou **alert**

### Continuando:

- O que foi feito no terminal do **node**, no video do curso em video

```js
> 'Oi' // Diz uma string
'Oi' // Bem é a string que você falou
> 3 + 2 // 3 mais 2
5 // Resultado da soma
> let nome = "Gustavo" // Declara a variável nome que recebe Gustavo
undefined // Ele retorna undefined porque você só declarou a variável nome, não mandou mostrar nada
> nome // Chama a variável nome
'Gustavo' // Agora sim! Ele mostrou o que a variável nome recebeu
> nome = 'Paulo' // Lembra? Let não pode ser redeclarado, então nesse caso vamos só mudar o seu valor
'Paulo' // Agora ele já retorna o nome Paulo pois ouve uma mudança nessa variável
> nome // Chama novamente a variável nome
'Paulo' // Pronto! Agora ela tem o valor de Paulo
> .exit // Sai do node
```

- Agora no terminal Visual Studio Code apenas abra o terminal e digite **node**

### Data Types (Tipos primitivos):

- number
  - infinity
  - NaN (Not a number, não é um número)
- string
- boolean
- null
- undefined
- object
  - Array
- function

-----

- O comando **typeof** te fala qual é o tipo primitivo da variável

O que foi feito no **node** na aula:
```js
> let n = 200;
undefined
> n
200
> typeof n
'number'
> n = "Google"
'Google'
> typeof n
'string'
> typeof 6
'number'
> typeof "6" // Ele está entre "" então é uma string
'string'
> typeof []
'object'
> typeof {}
'object'
> typeof function(){}
'function'
> typeof undefined
'undefined'
> typeof NaN
'number'
> typeof Infinity
'number'
> typeof null // Null pelo JavaScript é um objeto
'object'
```


### Dicas para os identificadores:

- **Maiúsculas** e **minúscula** fazem diferença
- Tente escolher **nomes coerentes** para as variáveis
- Evite ser um **"programador alfabeto"** ou um **"programador contador"**

# Aula 6

## Manipulação de dados

Tipos primitivos principais:
  - Number
  - String
  - Boolean (True, False)

**O que foi feito no terminal**
```js

> let s = 'JavaScript'
undefined
> s
'JavaScript'
> 'Eu estou estudando s'
'Eu estou estudando s'
> 'Eu estou estudando ' + s
'Eu estou estudando JavaScript'
> 
> let nome = 'Gustavo'
undefined
> let idade = 41
undefined
> let nota = 5.5
undefined
> nome
'Gustavo'
> idade
41
> nota
5.5
> 'O aluno ' + nome + ' com ' + idade + ' anos ' + 'tirou a nota ' + nota
'O aluno Gustavo com 41 anos tirou a nota 5.5'
> // versões recentes o template strings
undefined
> // o ${} é o que chamamos de placeholder
undefined
> `O aluno ${nome} com ${idade} anos tirou a nota ${nota}`
'O aluno Gustavo com 41 anos tirou a nota 5.5'
> .exit
```
-------

```js
> let n1 = 1545.5
undefined
> n1
1545.5
> n1.toFixed(2)
'1545.50'
> n1.toFixed(2).replace('.', ',')
'1545,50'
> n1.toLocaleString('pt-BR', {style: 'currency', currency: 'BRL'})
'R$ 1.545,50'
> n1.toLocaleString('eng-US', {style: 'currency', currency: 'BTC'})
'BTC 1,545.50'
> n1.toLocaleString('eng-US', {style: 'currency', currency: 'ETH'})
'ETH 1,545.50'
> n1.toLocaleString('eng-US', {style: 'currency', currency: 'XMR'})
'XMR 1,545.50'
> n1.toLocaleString('eng-US', {style: 'currency', currency: 'USD'})
'$1,545.50'
> n1.toLocaleString('eng-US', {style: 'currency', currency: 'EUR'})
'€1,545.50'
> n1.toLocaleString('pt-BR', {style: 'currency', currency: 'EUR'})
'€ 1.545,50'
> n1.toLocaleString('pt-BR', {style: 'currency', currency: 'USD'}
... 
... 
> n1.toLocaleString('pt-BR', {style: 'currency', currency: 'USD'})
'US$ 1.545,50'
>.exit
``` 

**Exercicio 4:**

```html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body {
            font: normal 20pt Arial;
        }
    </style>
</head>
<body>

    <script>
        // Formatar strings
        let nome = window.prompt('Qual é seu nome?');
        document.write(`Olá, <strong>${nome}</strong>! Seu nome tem ${nome.length} letras.<br>`);
        document.write(`Seu nome em maiúsculas é ${nome.toUpperCase()}<br>`);
        document.write(`Seu nome em minúsculas é ${nome.toLowerCase()}`);
        // Formatar números
    </script>
</body>
</html>

```

**Exercicio 3:**

```html

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exemplo 1 | Curso de JavaScript</title>
    <style>
        body {
            background-color: #6d6dac;
            color: white;
            font: normal 20pt arial;
        }
        h1 {
            color: #fde404;
        }
    </style>
</head>
<body>
    <h1>Olá, mundo!</h1>
    <p>Já me livrei da maldição!</p>
    <script>
        let n1 = Number(window.prompt('Digite um número')); // String
        let n2 = Number(window.prompt('Digite outro número')) // String
        // Converter o valor de string para number
        /* Number.parseint(n) para converter para inteiro
        Number.parseFloat(n) para converter para float, com uma virgula
        Number(n) deixe o JavaScript decidir se vai ser inteiro ou float*/
        // Converter de number para string
        /* String(n) ou n.toString()*/
        let s = n1 + n2
        window.alert(`A soma entre ${n1} e ${n2} é igual a ${s}`) // Concatenação
        /* number + number para adição
        string + string para concatenação */
        /* Formatando Strings 
        let s = 'JavaScript'
        s.length quantos caracteres a string tem
        s.toUpperCase() tudo pra MAIÚSCULAS
        s.toLowerCase() Tudo pra minúsculas*/
    </script>
</body>
</html>

```

**Exercicio 2:**
```html

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exemplo 1 | Curso de JavaScript</title>
    <style>
        body {
            background-color: #6d6dac;
            color: white;
            font: normal 20pt arial;
        }
        h1 {
            color: #fde404;
        }
    </style>
</head>
<body>
    <h1>Olá, mundo!</h1>
    <p>Já me livrei da maldição!</p>
    <script>
        let nome = window.prompt('Qual é seu nome?'); // Vai perguntar o nome
        window.alert('É um grande prazer te conhecer, ' + nome + '!'); // Concatenação
    </script>
</body>
</html>

```
# Aula 7

## Operadores

- 5 + 2 = 7
- 5 - 2 = 3
- 5 * 2 = 10
- 5 / 2 = 2.5
- 5 % 2 = 1 (resto da divisão inteira)
- 5 ** 2 = 25 (potencia de 5, no caso 5 ao quadrado)

> ⚠️ No JavaScript existe algo chamado **"precedência de valores"**, veja o exemplo abaixo:
>
> **Exemplo**:
>
> ```js
> 5 + 3 / 2 
> > 6.5
> ```
>
> Mas por que 6.5? Não era 4?
>
> No JavaScript ele faz primeiro a divisão e depois a adição, sendo assim 3 / 2 é igual a 1.5, mais 5 fica 6.5, agora para fazer 5 + 3 primeiro, apenas coloque as **()** como na matématica e pronto!
>
> **Exemplo**:
>
> ```js
> > 5 + 3 / 2
> 6.5
> > (5 + 3) / 2
> 4
> ```

### Precedência dos valores:

1. ()
2. **
3. *, /, %
4. +, -

> ⚠️ Se houver uma **mutiplicação(*)**, **divisão(/)** ou **resto da divisão por inteiro(%)** na mesma linha, quem aparecer primeiro vai ser feito primeiro.

**O que foi feito no node**:
```js
> let a = 5 + 3
undefined
> a
8
> let b = a % 5
undefined
> b
3
> let c = 5 * b ** 2
undefined
> c
45
> let d = 10 - a / 2
undefined
> d
6
> let e = 6 * 2 / d
undefined
> e
2
> let f = b % e + 4 / e
undefined
> f
3
```

**Auto atribuições**:
```js
> let n = 3
undefined
> n = n + 4
7
> n = n -  5
2
> n = n * 4
8
> n = n / 2
4
> n = n ** 2
16
> n = n % 5
1
```

> ⚠️ Para simplificar o **```n = n + 4```**, você pode colocar **```n += 4```**, isso só funciona se a mesma variavél receber ela mais outro número

**O que foi feito no node**:

```js
> let num = 8
undefined
> num
8
> num += 2
10
> num
10
> num %= 2
0
> num = 3
3
> num **= 2
9
```

### Incremento:

- Colocando ++ antes ou depois da variavel soma ela por 1
