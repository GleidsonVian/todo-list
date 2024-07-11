# Meu App de Tarefas

Este é um aplicativo simples de lista de tarefas criado em Python utilizando a biblioteca Tkinter. O aplicativo permite adicionar, editar, deletar e marcar tarefas como concluídas.

## Funcionalidades

- Adicionar nova tarefa
- Editar tarefa existente
- Deletar tarefa
- Marcar tarefa como concluída (sublinhado)

## Pré-requisitos

- Python 3.x
- Biblioteca Tkinter (geralmente incluída com Python)

## Instalação

1. Clone este repositório:
    ```sh
    git clone https://github.com/seu-usuario/seu-repositorio.git
    ```

2. Navegue até o diretório do projeto:
    ```sh
    cd meu-app-de-tarefas
    ```

3. Certifique-se de que as imagens dos ícones estão no caminho correto. Altere os caminhos das imagens se necessário:
    ```python
    icon_editar = PhotoImage(file=r'C:\caminho\para\seu\projeto\editar-azul.png').subsample(2, 2)
    icon_deletar = PhotoImage(file=r'C:\caminho\para\seu\projeto\lixeira.png').subsample(2, 2)
    ```

## Como usar

1. Execute o aplicativo:
    ```sh
    python seu_app_de_tarefas.py
    ```

2. A interface do usuário aparecerá. Você pode adicionar uma nova tarefa digitando no campo de entrada e clicando no botão "Adicionar tarefa".

3. Para editar uma tarefa, clique no ícone de edição (lápis) ao lado da tarefa, edite o texto no campo de entrada e clique em "Adicionar tarefa".

4. Para deletar uma tarefa, clique no ícone da lixeira ao lado da tarefa.

5. Para marcar uma tarefa como concluída, clique na caixa de seleção ao lado da tarefa. A tarefa será sublinhada para indicar que está concluída.

## Contribuição

Sinta-se à vontade para abrir issues ou enviar pull requests com melhorias ou correções.

