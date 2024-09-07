# Projeto TSBeginner - README

## Descrição

Este projeto é um aplicativo web simples para gerenciar **Tarefas** e **Lembretes**. O usuário pode alternar entre os modos de Tarefa (Todo) e Lembrete (Reminder), adicionando itens a uma lista que é renderizada na tela. O código utiliza TypeScript para fornecer tipagem estática e organização clara do código.

## Estrutura de Arquivos

- **index.html**: Contém a estrutura HTML e o layout básico da interface do usuário. Inclui um botão para alternar modos e um formulário para adicionar tarefas ou lembretes.
- **index.js**: Implementa a lógica do aplicativo, incluindo a criação de tarefas e lembretes, manipulação de eventos e renderização dinâmica dos itens na lista.

### Arquivo: `index.html`
- Estrutura do formulário com dois modos (Tarefa e Lembrete).
- Controles para inserir descrição, data (no modo Lembrete) e opções de notificação.
- Botão para alternar entre modos de Tarefa e Lembrete.
- Conexão ao arquivo JavaScript (`index.js`) que controla o comportamento da aplicação【11†source】.

### Arquivo: `index.js`
- Utiliza uma **IIFE** (Immediately Invoked Function Expression) para encapsular o escopo.
- Define as classes **Todo** (Tarefa) e **Reminder** (Lembrete), além de métodos de renderização para exibir a descrição e os status de cada item.
- Inclui a lógica para alternar entre os modos de Tarefa e Lembrete.
- Gerenciamento da interface do usuário (UI) com a exibição dinâmica de formulários e lista de tarefas.
- Função utilitária para gerar IDs únicos e manipular datas【12†source】.

## Funcionalidades

- **Modo Tarefa (Todo)**: Adicione tarefas com uma descrição e marque-as como concluídas ou em progresso.
- **Modo Lembrete (Reminder)**: Adicione lembretes com descrição, data e plataforma de notificação (SMS, Email ou Push Notification).
- Alternar facilmente entre os modos **Tarefa** e **Lembrete**.
- Lista de itens renderizada dinamicamente na interface.

## Como Usar

1. **Alternar Modos**: Use o botão "Toggle Mode" para alternar entre o modo Tarefa e Lembrete.
2. **Adicionar Tarefas**: No modo Tarefa, insira a descrição e clique em "Submit" para adicionar uma nova tarefa à lista.
3. **Adicionar Lembretes**: No modo Lembrete, insira a descrição, selecione a data e a plataforma de notificação, e clique em "Submit".
4. **Visualização Dinâmica**: A lista de itens será atualizada dinamicamente na tela.

## Instalação e Execução

1. Navegue até o diretório do projeto:
   ```bash
   cd tsbeginner
   ```
2. Instale as dependências:
   ```bash
   npm install
   ```
3. Compile o TypeScript para JavaScript:
   ```bash
   npm run build
   ```
4. Abra o arquivo `index.html` no navegador para ver o aplicativo em ação.

## Tecnologias Utilizadas

- **HTML5** para estruturação da interface.
- **JavaScript/TypeScript** para a lógica do aplicativo e tipagem estática.
- **CSS** básico embutido no HTML para estilização.

## Melhorias Futuras

- Adicionar funcionalidade de edição e remoção de tarefas e lembretes.
- Implementar armazenamento local para manter as tarefas/lembretes ao recarregar a página.
- Melhorar a estilização da interface.

## Autor

Desenvolvido como um projeto introdutório para explorar o uso de TypeScript em aplicações web.
