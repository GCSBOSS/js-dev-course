## Ferramentas

Para continuar o curso você vai precisar conhecer e instalar algumas ferramentas de desenvolvimento.

### Editor de Código

Como vamos **escrever** o "código fonte" de nossos programas usando linguagens de programação precisamos de um editor de código. Um editor de código é uma ferramenta de software utilizada por programadores para criar e editar código fonte de programas. É uma parte essencial do processo de desenvolvimento de software, pois permite que os programadores escrevam, visualizem, editem e organizem o código de maneira eficiente.

Aqui estão algumas características e funções comuns encontradas em um editor de código:

- **Edição de texto:** O editor de código oferece uma interface para digitar e editar texto de forma mais prática do que um editor de texto comum.

- **Realce de sintaxe:** O realce de sintaxe é uma funcionalidade importante que torna o código mais legível, pois identifica diferentes elementos de linguagem de programação com cores distintas.

- **Indentação automática:** O editor de código pode ajustar automaticamente a indentação do código para facilitar a visualização da estrutura e hierarquia do programa.

- **Auto-completar:** À medida que o programador digita, o editor pode sugerir palavras-chave, funções e variáveis com base no contexto, agilizando o processo de escrita do código.

- **Navegação rápida:** O editor de código normalmente oferece recursos que permitem navegar rapidamente entre diferentes partes do código, como funções, classes ou arquivos.

- **Localização de erros:** Muitos editores de código possuem recursos integrados para identificar erros de sintaxe ou problemas no código em tempo real, por meio de sublinhados ou mensagens de erro.

- **Integração com ferramentas externas:** Alguns editores de código oferecem integração com ferramentas de desenvolvimento e controle de versão, permitindo que os programadores trabalhem de forma mais eficiente em seus projetos.

- **Personalização:** Os editores de código geralmente são altamente personalizáveis, permitindo que os usuários escolham temas, atalhos de teclado e extensões para se adequarem às suas preferências e necessidades específicas.

Existem muitos editores de código disponíveis, desde opções simples e leves até ambientes de desenvolvimento integrados (IDEs) mais complexos, que oferecem recursos adicionais. A escolha de um editor de código é uma decisão pessoal e muitas vezes depende das preferências do programador e dos requisitos do projeto em questão.

Nesse cursos vamos utilizar o **VSCode**. Para baixá-lo, acesse o link: https://code.visualstudio.com/download e ao final do download, é só instalar.

### Terminal

Um "terminal" é uma ferramenta essencial no desenvolvimento de software. É uma interface de linha de comando que permite que você interaja com o sistema operacional do computador, executando comandos através de texto.

Aqui estão algumas características e funcionalidades importantes de um terminal para um programador iniciante:

- **Interface de linha de comando:** Enquanto a maioria das interações com o computador são feitas através de interfaces gráficas (como janelas e ícones), um terminal oferece uma abordagem de linha de comando, onde você digita comandos em texto e pressiona Enter para executá-los.

- **Execução de programas e scripts:** Com o terminal, você pode executar programas e scripts através de comandos específicos. Por exemplo, você pode executar um programa Python digitando "python nome_do_programa.py" ou executar um script de compilação digitando "make".

- **Gerenciamento de arquivos e diretórios:** Você pode criar, mover, copiar, renomear e excluir arquivos e diretórios usando comandos no terminal. Isso é especialmente útil quando você precisa realizar tarefas de organização de projetos e manipulação de arquivos.

- **Visualização de informações do sistema:** Com alguns comandos específicos, você pode obter informações sobre o sistema, como especificações do hardware, uso de recursos, processos em execução e muito mais.

- **Interação com ambientes de desenvolvimento**: Alguns ambientes de desenvolvimento integrados (IDEs) também têm a opção de abrir um terminal integrado, permitindo que você execute comandos diretamente a partir do IDE.

Nesse curso vamos utilizar o terminal que vem integrado ao VSCode. Para acessar esse terminal, abra o VSCode e pressione `Ctrl - Shift - '`.

### Runtime

Como a linguagem que vamos usar nesse curso é interpretada vamos precisar de um programa que interprete e execute nossos programas aí entra o Runtime.

No contexto da programação, o termo "Runtime" refere-se ao ambiente de execução de um programa de computador. É o conjunto de recursos e bibliotecas necessárias para que o código fonte seja executado e o programa funcione corretamente. O Runtime é responsável por interpretar, compilar e executar o código escrito pelos programadores.

Nesse curso usaremos o **Deno** para executar nossos programas. Deno é um Runtime para JavaScript e TypeScript construído com base no mecanismo V8 do Google Chrome e no Rust. Lançado em maio de 2020.

Para instalar o Deno, acesse o seu Terminal e rode o seguinte commando:

```
winget install --id DenoLand.Deno -e
```

### Conclusão

Com tudo instalado, falta só alguns detalhes antes de entrarmos na programação em si.

Para acompanhar os exemplos das aulas e brincar com seus programas siga as seguintes instruções:

1. Para cada novo programa, crie um arquivo com a extensão `.js` utilizando o editor de código.
2. Abra o terminal do seu editor (`Ctrl - Shift - '`)
3. Selecione a pasta onde seu arquivo está
4. Execute o arquivo com `deno run ./meu-arquivo.js`
5. O resultado será mostrado no terminal.

Para compreender melhor os exemplo de código você precisa entender o que são **comentários**.

Em JavaScript linhas iniciadas por `//` são comentários e não fazem parte do programa em si. Comentários são usados para deixar alguma informação útil sobre o programa em forma textual para quem vai precisar ler e entender o código no futuro. Até o 'você' do futuro!

```js

// Aqui eu posso escrever o que eu quiser
// E o computador não vai se importar ;)

```

Nesse curso vamos usar muitos comentários para explicar partes dos códigos mostrados.

---
[< Anterior](./programming.md) --- [Índice](./index.md) --- [Próximo >](./data-types.md)