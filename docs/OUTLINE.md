# Roteiro das Aulas

[\# 01 - Apresentação da Disciplina (13/03/2019, QUA)](#-01---apresentação-da-disciplina-13032019-qua)<br>
[\# 02 - Fundamentos de PHP (14/03/2019, QUI)](#-02---fundamentos-de-php-14032019-qui)<br>
[\# 03 - Algoritmos básicos no PHP (20/03/2019, QUA)](#-03---algoritmos-básicos-no-php-20032019-qua)<br>
[\# 04 - Funções no PHP (21/03/2019, QUI)](#-04---funções-no-php-21032019-qui)<br>

## \# 01 - Apresentação da Disciplina (13/03/2019, QUA)

---

**Conteúdo:**

- Apresentação da disciplina:
  - Objetivo, conteúdo, avaliação, comunicação, bibliografia e ferramentas
  - [O que você vai aprender em PW1?](http://slides.com/luizcarlos/o-que-vou-aprender-em-pw1#/)
  - Conteúdo
    - Servidor LAMP
    - Executando PHP de modo interativo com Docker.

**Reflexão:**

- O que você vai aprender em PW1?
- Qual o nome e utilidade das tecnologias você irá aprendar nesta disciplina?
- Como funciona uma aplicação Web com LAMP?
- Como executamos o PHP de como interativo usando o Docker?

**Exercício:**

- Analise o [site da discplina](https://ifpb.github.io/pw1/) e se inscreva no channel `#pw1-20191` do [slack do ifpb](https://ifpb.slack.com).
- Configure seu computador com essas [ferramentas](TOOLS.md).

## \# 02 - Fundamentos de PHP (14/03/2019, QUI)

---

**Conteúdo:**

- [PHP Guide](https://ifpb.github.io/php-guide/)
  - [PHP Core](https://ifpb.github.io/php-guide/core/)
    - [Values and Types](https://ifpb.github.io/php-guide/core/values-and-types/)
    - [Variable](https://ifpb.github.io/php-guide/core/variable/)
    - [Expression and Operator](https://ifpb.github.io/php-guide/core/expression-and-operator/)

**Reflexão:**

- Como executamos código PHP?
- Quais são os tipos da linguagem PHP?
- Como declaramos variáveis no PHP?
- Quais são os operadores do PHP, e como elaboramos expressões?
- Quais são as estruturas de decisão e repetição do PHP?

**Exercício:**

- Crie o script [Hello World](https://ifpb.github.io/php-exercises/core/basic/hello/)
- Através de `x = 10` crie um script para as seguintes expressões:

| Expressão   | Resultado |
| ----------- | --------- |
| `x+2`       | 12        |
| `x²`        | 100       |
| `3x²+12x-4` | 416       |
| `x+3 > √x`  | true      |

## \# 03 - Algoritmos básicos no PHP (20/03/2019, QUA)

---

**Conteúdo:**

- [PHP Guide](https://ifpb.github.io/php-guide/)
  - [PHP Core](https://ifpb.github.io/php-guide/core/)
    - [Statements](https://ifpb.github.io/php-guide/core/statements/): if, switch, for, while, do-while

**Reflexão:**

- Quais são as estruturas de decisão do PHP?
- Quais são as estruturas de repetição do PHP?

**Exercício:**

- Crie o algoritmo de [Body Mass Index (BMI)](https://ifpb.github.io/php-exercises/core/basic/bmi/) usando `if` e `switch`;
- Crie o algoritmo para exibir a séria de [00 até 99](https://ifpb.github.io/php-exercises/core/basic/numbers/) de dez em dez usando `for`, `while` e `do-while`;
- Crie um script para:
  - Gerar algumas [séries numéricas](https://ifpb.github.io/php-exercises/core/basic/numbers/)
  - Gerar o calculo do [IRRF](https://ifpb.github.io/php-exercises/core/basic/irrf-2017/)
  - Gerar esta [série harmônica](https://ifpb.github.io/php-exercises/core/basic/harmonic-series/)

## \# 04 - Funções no PHP (21/03/2019, QUI)

---

**Conteúdo:**

- [PHP Guide](https://ifpb.github.io/php-guide/)
  - [PHP Core](https://ifpb.github.io/php-guide/core/)
    - [Function](https://ifpb.github.io/php-guide/core/function/)
      - [Definição e chamada](https://ifpb.github.io/php-guide/core/function/#definition)
      - [Case sensitive](https://ifpb.github.io/php-guide/core/function/#case-insensitive)
      - [Escopo](https://ifpb.github.io/php-guide/core/function/#scope)
      - [Parâmetro Default](https://ifpb.github.io/php-guide/core/function/#default-argument-values)
      - [Chamada de funções externas](https://ifpb.github.io/php-guide/core/statements/#includes)
    - [Teste unitários](https://phptherightway.com/#testing)
      - Gerenciando projetos com [packagist](https://ifpb.github.io/php-guide/packages/packagist/)
      - Executando teste com o [kahlan](https://ifpb.github.io/php-guide/packages/test/kahlan/)

**Reflexão:**

- Como declaramos e chamamos uma função em PHP?
- O que acontece quando passamos uma quantidade de argumentos diferente do total de parâmetros?
- Para chamar uma função é necessário declará-la antes de sua chamada?
- É possível declarar uma variável dentro da função com o mesmo nome de uma variável fora da função?
- O que são parâmetros default?
- Qual é a configuração necessária para chamar uma função declarada em outro arquivo?
- Qual é o benefício de utilizar testes unitários?
- Como se configura e executa testes unitários usando o [kahlan](https://kahlan.github.io/docs/index.html)?
- Qual é a importância do [composer](http://getcomposer.org/) para o PHP?

**Exercício:**

- Crie um script para:
  - Calcular a [soma de números](https://ifpb.github.io/php-exercises/core/function/sum/)
  - Calcular a [área do círculo](https://ifpb.github.io/php-exercises/core/function/area-of-circle/)
  - Calcular as [operações aritméticas básicas](https://ifpb.github.io/php-exercises/core/function/calc/)
  - Calcular o [fatorial](https://ifpb.github.io/php-exercises/core/function/factorial/)
  - Verificar se os lados de um [triângulo](https://ifpb.github.io/php-exercises/core/function/triangle-checker/) são válidos
- Crie estes outros [scritps](https://ifpb.github.io/php-exercises/core/#function).

<!--
## \# 05 - (27/03/2019, QUA)
---

## \# 06 - (28/03/2019, QUI)
---

## \# 07 - (03/04/2019, QUA)
---

## \# 08 - (04/04/2019, QUI)
---

## \# 09 - (10/04/2019, QUA)
---

## \# 10 - (11/04/2019, QUI)
---

## \# 11 - (17/04/2019, QUA)
---

## \# 12 - (24/04/2019, QUA)
---

## \# 13 - (25/04/2019, QUI)
---

## \# 14 - (02/05/2019, QUI)
---

## \# 15 - (08/05/2019, QUA)
---

## \# 16 - (09/05/2019, QUI)
---

## \# 17 - (15/05/2019, QUA)
---

## \# 18 - (16/05/2019, QUI)
---

## \# 19 - (22/05/2019, QUA)
---

## \# 20 - (23/05/2019, QUI)
---

## \# 21 - (29/05/2019, QUA)
---

## \# 22 - (30/05/2019, QUI)
---

## \# 23 - (05/06/2019, QUA)
---

## \# 24 - (06/06/2019, QUI)
---

## \# 25 - (12/06/2019, QUA)
---

## \# 26 - (13/06/2019, QUI)
---

## \# 27 - (19/06/2019, QUA)
---

## \# 28 - (26/06/2019, QUA)
---

## \# 29 - (27/06/2019, QUI)
---

## \# 30 - (07/08/2019, QUA)
---

## \# 31 - (08/08/2019, QUI)
---

## \# 32 - (10/08/2019, SÁB)
---

## \# 33 - (14/08/2019, QUA)
---

## \# 34 - (15/08/2019, QUI)
---

## \# 35 - (21/08/2019, QUA)
---

## \# 36 - (22/08/2019, QUI)
---

## \# 37 - (27/08/2019, TER)
---

## \# 38 - (28/08/2019, QUA)
---

## \# 39 - (29/08/2019, QUI)
---

## \# 40 - (04/09/2019, QUA)
--- -->
