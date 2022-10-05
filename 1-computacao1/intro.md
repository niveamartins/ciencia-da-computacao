# Introdução a Computação

## O que é Ciência da Computação?

É a área do conhecimento que atua no desenvolvimento de programas para diferentes dispositivos como, por exemplo, os computadores. O profissional dessa área atua na análise de um problema, estudo de uma solução computacional e desenvolvimento da solução de forma algorítmica.

## O que é um algoritmo?

É a sequência de passos (processos da aplicação). Quando escrevemos um código em alguma linguagem, estamos informando ao nosso computador o que ele deve fazer com aqueles dados, como se fosse uma receita ou um manual de instruções. Pode haver repetição (com enumerações ou condição) dos passos ou não, como também pode existir uma tomada de decisão durante o código. Uma coisa que você deve sempre lembrar é que a ordem dos passos é importante e deve ser levado em conta sempre.

### Componentes de um algoritmo

O algoritmo é composto por 3 componentes - Entradas, processamento (passos) e saída -. O único componente obrigatório é o processamento. Ou seja, o nosso manual não necessariamente tem que conter itens para começar, podemos apenas dar o passo a passo para o computador, como também pode não haver um retorno daquilo. 

Existem algoritmos que não tem entradas, mas tem saída; tem entrada e não tem saída; e algoritmos que não tem nenhuma das duas.

## O que é uma linguagem de programação?

É uma linguagem formal que permite que um programador escreva um algoritmo para criar programas que controlam o comportamento físico e lógico de uma máquina.

### Tipos de linguagens de programação

#### Linguagens de baixo nível
São linguagens totalmente orientadas à máquina. 

* Linguagem de máquina: é uma coleção de dígitos (0 e 1), chamados de bits, que o computador lê e interpreta, sendo o único idioma que os computadores entendem;
* Assembly: consiste em uma série de instruções que correspondem ao fluxo de pedidos executáveis por um microprocessador e, como o computador não entende texto, precisa passar pelo Assembler que troca os textos por comandos em bytes (grupo de 8 bits);

#### Linguagens de alto nível
permite que você escreva códigos usando os idiomas que conhece (português, espanhol, inglês etc.) traduzindo-os em seguida para o idioma da máquina.

* Linguagem Interpretadas: o código fonte é lido e interpretado linha por linha; as ações são realizadas a cada leitura;
* Linguagem Compiladas: o código fonte passa pelo compilador que gera um arquivo executável.

OBS.: Existem linguagens, como o Python, que são linguagens interpretadas e compiladas. Antes da execução do programa, o código fonte é transformado em um bytecode pelo compilador e, após isso, ao executar, o interpretador lê linha por linha do bytecode e envia a instrução para a máquina.


# Introdução ao Python

## Instalação

Para instalar o Python, podemos ir para a [página oficial de download](https://www.python.org/downloads/). Após a instalação, é possível certificar que está tudo certo indo na linha de comando e inserindo:

```
$ python3 --version
```

## Usando o Python na Linha de Comando
Para iniciarmos os estudos e aprender conceitos como operadores aritméticos e lógicos, iremos iniciar o Python na linha de comando da seguinte forma:

```
$ python3
```

Deve aparecer algo como:

```
Python 3.10.6 (main, Aug 30 2022, 05:12:36) [Clang 13.1.6 (clang-1316.0.21.2.5)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> 
```

Podemos testar algumas operações como digitando '1+1' e apertando a tecla Enter.

## Operadores Aritméticos

- Soma (+)
- Subtração (-)
- Multiplicação (*)
- Divisão (/)
- Potência (**)
- Módulo (%)

A ordem da expressão funciona como na matemática normal.

## Operadores Lógicos
São operadores utilizados para comparação entre dois ou mais elementos.

- Igual à (==)
- Diferente de (!= ou <>)
- Maior que (>)
- Menor que (<)
- Maior ou igual à (>=)
- Menor ou igual à (<=)

## Variáveis
São espaços de memória, formalmente chamados de endereços de memória, em que o programa pode guardar um determinado valor. Para elas, são atribuídos nomes. 
Em Python, declaramos uma nova variável no nosso código da seguinte forma:

```
a = 2
```

Essa variável, então, recebeu o valor 2 para ser armazenado em nosso espaço de memória e, sempre que quisermos retornar esse valor, iremos chamar pelo nome 'a' que foi atribuído para a variável (endereço de memória)

### Boas práticas e regras de nomeação de variáveis
1. Os nomes não podem começar com um número.
2. Não pode haver espaços no nome. Use _ em vez disso.
3. Não é possível usar nenhum desses símbolos: '", <> /? | \ ()! @ # $% ^ & * ~ - +
4. É considerada a melhor prática (PEP8) que os nomes são minúsculos.
5. É interessante dar nomes significativos para as suas variáveis como numero_magico, idade e etc.

