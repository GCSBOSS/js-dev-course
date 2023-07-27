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

Nesse curso vamos usar com principal entrada e saída o **Terminal**.

## Terminal

Um "terminal" é uma ferramenta essencial no desenvolvimento de software. É uma interface de linha de comando que permite que você interaja com o sistema operacional do computador, executando comandos através de texto.

Aqui estão algumas características e funcionalidades importantes de um terminal para um programador iniciante:

1. Interface de linha de comando: Enquanto a maioria das interações com o computador são feitas através de interfaces gráficas (como janelas e ícones), um terminal oferece uma abordagem de linha de comando, onde você digita comandos em texto e pressiona Enter para executá-los.

2. Acesso direto ao sistema operacional: O terminal permite que você tenha acesso direto ao sistema operacional do computador, como o Windows Command Prompt ou o macOS Terminal, o que permite executar várias tarefas de gerenciamento de arquivos e configurações do sistema.

3. Execução de programas e scripts: Com o terminal, você pode executar programas e scripts através de comandos específicos. Por exemplo, você pode executar um programa Python digitando "python nome_do_programa.py" ou executar um script de compilação digitando "make".

4. Gerenciamento de arquivos e diretórios: Você pode criar, mover, copiar, renomear e excluir arquivos e diretórios usando comandos no terminal. Isso é especialmente útil quando você precisa realizar tarefas de organização de projetos e manipulação de arquivos.

6. Visualização de informações do sistema: Com alguns comandos específicos, você pode obter informações sobre o sistema, como especificações do hardware, uso de recursos, processos em execução e muito mais.

8. Interação com ambientes de desenvolvimento: Alguns ambientes de desenvolvimento integrados (IDEs) também têm a opção de abrir um terminal integrado, permitindo que você execute comandos diretamente a partir do IDE.

## Console

O JavaScript possui uma forma padrão de enviar dados de **saída** ao terminal, através de chamar a função `console.log` e passar como argumentos os valores que se desejam mostrar no terminal.

```js
console.log('Olá Mundo!');

console.log('Algum valor:', 128);
```

Para receber dados de entrada o JavaScript não possui uma forma padronizada. A forma que vamos usar é através de uma função do NodeJS (a plataforma que vamos usar para executar JavaScript) ``