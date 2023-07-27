## Variáveis

Em programação, as variáveis são conceitos fundamentais que permitem armazenar e manipular informações na memória do computador. Uma variável é um espaço na memória do computador que possui um nome (identificador) e um valor associado. Ela é utilizada para armazenar temporariamente dados durante a execução de um programa. O nome da variável é usado para referenciar seu conteúdo, e esse conteúdo pode ser alterado ao longo do programa.

### Declaração

Ao declarar uma variável, você está informando ao compilador ou interpretador da linguagem que deseja reservar um local na memória para armazenar um determinado tipo de dado. O valor associado à variável pode ser atribuído durante a declaração ou posteriormente, por meio de atribuições.

Em diferentes linguagens de programação, a sintaxe para declarar e usar variáveis pode variar, mas o conceito geral é o mesmo.

Em JavaScript variáveis podem ser declaradas usando a palavra-reservada `let`, acompanhada de uma lista identificadores de minha escolha separados por vírgula, que serão os nomes das variáveis.

```js
let minhaVariavel, outraVariavel
```

Nomes de variáveis só podem ser compostos de letras, números, cifrão ($) e underscore (_).

### Atribuição

Atribuir é a operação de apontar uma variável para um determinado dado na memória.
É possível alterar o valor de uma variável inúmeras vezes durante a execução de um programa.

Em JavaScript a operação é feita utilizando o operador `=`, de forma que a variável à esquerda recebe o valor à direita.

```js
let minhaVariavel = 4

// Agora alteramos o valor da variável
minhaVariavel = 100
```

### Tipagem Estática ou Dinâmica
As diversas linguagens de programação tem diferente maneiras de lidar com os tipos de dados que variáveis podem conter e a interação entre variáveis de diferentes tipos. As duas principais formas de tipagem em programação são:

- Tipagem Estática: Quando os tipos de variáveis devem ser declarados na criação da variável e não podem ser mudados durante o programa. Nesse caso o compilador verifica o programa e apresenta  um erro no caso de alguma variável estar sendo usada um dado com o tipo errado.

- Tipagem Dinâmica: Quando uma variável pode guardar valores de vários tipos ao longo do programa. Nesse caso um erro acontecerá apenas durante a execução d programa caso se tente realizar uma operação assumindo o tipo de dado errado.

Em JavaScript a tipagem é dinâmica, de forma que dados tem tipo, mas variáveis não tem um tipo definido. As variáveis podem receber dados de qualquer sempre que desejado.

[< Anterior](./data-types.md) --- [Índice](./index.md) --- [Próximo >](./io.md)
