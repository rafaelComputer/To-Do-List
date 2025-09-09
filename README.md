# To-Do List com React, TypeScript e Vite

## Descrição

Este projeto é uma aplicação simples de lista de tarefas (To-Do List) desenvolvida do zero para praticar conceitos modernos de desenvolvimento frontend com React e TypeScript. A aplicação permite adicionar, listar e marcar tarefas como concluídas, com uma interface clara e funcional.

O foco principal foi exercitar:

- Configuração de projeto moderno com Vite.
- Uso de TypeScript para tipagem estática e maior segurança no código.
- Gerenciamento dinâmico de dados usando os hooks `useState`.
- Organização do código em componentes reutilizáveis.
- Desenvolvimento rápido e eficiente com React.

## Funcionalidades

- **Adicionar Tarefas:** O usuário pode digitar uma nova tarefa e adicioná-la à lista.
- **Listar Tarefas:** As tarefas adicionadas aparecem em uma lista exibida na tela.
- **Marcar como Concluída:** Clicar em uma tarefa alterna seu estado entre concluída ou não concluída, refletido visualmente com riscado e cor diferente.
- **Sem Persistência:** Os dados não são salvos permanentemente; ao atualizar a página, a lista reseta.

## Tecnologias Utilizadas

- [React](https://reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Vite](https://vitejs.dev/) como bundler e dev server
- CSS básico para estilização

## Como Rodar o Projeto

1. Clone este repositório:  
   `git clone https://github.com/seu-usuario/nome-do-repositorio.git`  

2. Entre na pasta do projeto:  
   `cd nome-do-repositorio`  

3. Instale as dependências:  
   `npm install`  

4. Inicie o servidor de desenvolvimento:  
   `npm run dev`  

5. Abra o navegador no endereço que aparecer no terminal, normalmente:  
   `http://localhost:5173`

## Processo de Desenvolvimento

1. Inicialmente criei o projeto usando o Vite com o template React + TypeScript para facilitar a configuração inicial.
2. Defini a tipagem da tarefa usando uma interface `Task` para garantir estrutura e segurança.
3. Usei o hook `useState` para armazenar a lista de tarefas e o texto da nova tarefa.
4. Implementei a função para adicionar tarefas, validando para evitar tarefas vazias.
5. Implementei a função para alternar o estado "concluído" da tarefa, refletindo visualmente sua mudança.
6. Organizei a interface com HTML simples e estilos inline básicos para foco na funcionalidade.
7. Testei os principais fluxos de adicionar, listar e completar tarefas para garantir funcionamento correto.
8. Opcionalmente, criei um arquivo CSS para estilização leve da aplicação.

## Próximos Passos (Evoluções Futuras)

- Persistência dos dados usando localStorage ou backend.
- Organização dos componentes em arquivos separados.
- Adição de funcionalidades como edição e exclusão de tarefas.
- Melhorias visuais e responsividade.

---

Este projeto foi realizado para cumprir um exercício prático de desenvolvimento frontend com foco em React, TypeScript e uso eficiente de Vite.
