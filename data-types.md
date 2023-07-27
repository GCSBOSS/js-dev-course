## Tipos de Dados

Em programas de computador, vários dados são utilizados e processados no decorrer da execução.
Cada linguagem de programação oferece a possibilidade de trabalhar com dados de diferentes tipos.Alguns dos tipos de dados comuns incluem:

- Inteiro (int): Armazena números inteiros, como 1, -5, 1000, etc.
- Ponto flutuante (float ou double): Armazena números com casas decimais, como 3.14, -0.5, 2.71828, etc.
- Booleano (bool): Armazena valores verdadeiro (true) ou falso (false).
- Caractere (char): Armazena um único caractere, como 'A', 'b', '1', etc.
- Texto ou cadeia de caracteres (string): Armazena sequências de caracteres, como "Olá, mundo!", "Nome do usuário", etc.

Em Javascript os seguintes tipos de dados primitivos podem ser utilizados:

```js
let idade = 30; // number
let preco = 9.99; // número
let nome = "João"; // string
let mensagem = 'Olá, mundo!'; // string
let possuiCarro = true; // boolean
let temCasa = false; // boolean
let endereco = null; // null - Que indica nenhum valor em especial
let sobrenome; // undefined - A variável foi declarada, mas não possui valor atribuído.
```

Além desses, algumas estruturas de dados também são muito comuns, como:

- **Array**: É uma estrutura de dados que armazena uma lista ordenada de elementos. Os elementos podem ser de qualquer tipo de dado, e são acessados através de índices numéricos.

    ```js
    let numeros = [1, 2, 3, 4, 5]; // Array
    let frutas = ["maçã", "banana", "laranja"]; // Array
    ```

- **Objeto (Object)**: É uma estrutura de dados que armazena pares de chave-valor. Cada valor é associado a uma chave (nome) que permite acessá-lo.

    ```js
    // Object
    let pessoa = {
        nome: "João",
        idade: 30,
        possuiCarro: true
    };
    ```

---
[< Anterior](./intro.md) --- [Índice](./index.md) --- [Próximo >](./variables.md)