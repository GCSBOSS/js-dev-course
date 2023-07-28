## Entrada e Saída (I/O)

Em programação, "entrada" e "saída" referem-se à interação entre um programa de computador e o mundo exterior. Essa interação é essencial para que os programas possam receber dados, processá-los e, em seguida, fornecer resultados úteis ao usuário ou ao ambiente em que estão sendo executados.

- **Entrada (Input):** A entrada é a informação que um programa de computador recebe do usuário ou de uma fonte externa. Essa informação pode ser fornecida de diversas formas, dependendo do tipo de programa e do contexto em que está sendo utilizado. Alguns exemplos comuns de entrada são:
  - **Digitação do teclado:** Quando o usuário insere texto ou comandos através do teclado.
  - **Cliques do mouse:** Ao interagir com botões ou elementos gráficos em uma interface gráfica.
  - **Dados de um arquivo:** Um programa pode ler informações de um arquivo armazenado no disco rígido ou em outro dispositivo de armazenamento.
  - **Sinais de sensores:** Em programas que interagem com dispositivos físicos, como sensores de temperatura, pressão, etc.

- **Saída (Output):** A saída é o resultado produzido pelo programa após processar a entrada e realizar as operações necessárias. Assim como a entrada, a saída pode assumir várias formas, como:
  - **Exibição na tela:** Os resultados podem ser exibidos na tela do computador, como texto, gráficos, tabelas, imagens, etc.
  - **Escrita em arquivo:** O programa pode salvar os resultados em um arquivo para uso futuro ou para compartilhamento com outros sistemas ou usuários.
  - **Envio de dados:** A saída pode ser enviada para outro sistema ou servidor através de uma conexão de rede, como em aplicativos web ou serviços de API.
  - **Controle de dispositivos:** Em programas que interagem com dispositivos físicos, a saída pode ser o comando para controlar um motor, ligar um LED, etc.

A capacidade de entrada e saída é fundamental para tornar os programas interativos e úteis. Sem essas funcionalidades, os programas seriam isolados e incapazes de interagir com os usuários ou o ambiente ao seu redor. Portanto, a manipulação adequada de entrada e saída é uma habilidade essencial para os desenvolvedores de software.

Nesse curso vamos usar com principal entrada e saída do Terminal.

## Console

O JavaScript possui uma forma padrão de enviar dados de **saída** ao terminal, através de chamar a função `console.log` e passar como argumentos os valores que se desejam mostrar no terminal.

```js
console.log('Olá Mundo!')

console.log('Algum valor:', 128)
```

Para receber dados de entrada o JavaScript não possui uma forma padronizada ainda. A forma que vamos usar é através de uma função `prompt` nativa do Deno, que ao ser chamada vai requisitar ao terminal que deixe o usuário 'entrar' com algum valor. O valor digitado pelo usuário será retornado e pode ser guardado em uma variável.

```js
let valor = prompt()
```

---
[< Anterior](./variables.md) --- [Índice](./index.md) --- [Próximo >](./operations.md)