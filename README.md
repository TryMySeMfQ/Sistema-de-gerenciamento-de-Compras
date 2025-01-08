# Sistema-de-gerenciamento-de-Compras

Sistema de gerenciamento de Compras>
Requisitos:
1. Configurar o repositório no Git
O grupo deve:
Criar um repositório no GitHub.
Configurar o repositório localmente com o comando git clone.
Dividir as tarefas entre os integrantes usando branches (ex.: feature/adicionar-tarefa, feature/filtro-tarefas).
Fazer commits claros e descritivos (ex.: git commit -m "Adiciona função para adicionar tarefas").
Realizar merges no branch principal utilizando pull requests.

2. Estrutura do Projeto
HTML:
Uma página simples com:
Um campo de entrada para adicionar tarefas.
Um botão para adicionar tarefas.
Uma lista de tarefas exibida no DOM.
Botões para filtrar tarefas (todas, concluídas, pendentes).
CSS:
Estilo básico para diferenciar tarefas concluídas de pendentes.

3. Orientação a Objetos (OOP)
Criar uma classe Tarefa com os seguintes atributos:
id (gerado automaticamente)
descrição (texto da tarefa)
concluída (booleano, inicializa como false)
dataCriacao (armazenada como Date)
Adicionar métodos à classe:
marcarConcluida(): altera o status de uma tarefa para true.
toString(): retorna uma string formatada com a descrição da tarefa e sua data de criação.

4. Lista de Tarefas
Criar uma classe ListaDeTarefas que:
Armazena todas as tarefas em um array.
Implementa métodos para:
Adicionar tarefas: Adiciona objetos da classe Tarefa.
Remover tarefas: Remove pelo id.
Filtrar tarefas: Retorna tarefas pendentes ou concluídas.
Exibir tarefas: Mostra as tarefas no console ou DOM.

5. Funções Anônimas e Callbacks
Utilize funções anônimas para:
Manipular eventos de clique nos botões (ex.: adicionar tarefas, filtrar, remover).
Utilize callbacks para:
Filtrar tarefas (ex.: listaDeTarefas.filtrar(tarefa => tarefa.concluida)).

6. Manipulação do DOM
Adicionar, exibir, e remover tarefas dinamicamente no DOM.
Destaques:
Crie uma tabela ou lista <ul> para exibir as tarefas.
Use o botão de filtro para mostrar tarefas específicas (pendentes ou concluídas).

7. Formatação de Datas com Intl.DateTimeFormat
Formate a data de criação da tarefa utilizando Intl.DateTimeFormat:
Exemplo: new Intl.DateTimeFormat('pt-BR', { dateStyle: 'short', timeStyle: 'short' }).format(dataCriacao).


