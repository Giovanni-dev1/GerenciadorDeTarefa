Lista de Tarefas com Flask

Esse é um projeto simples que fiz para praticar desenvolvimento web usando Python e Flask.
A ideia foi criar uma aplicação básica de lista de tarefas que roda no navegador.

O usuário consegue adicionar tarefas, marcar como concluídas e também apagar tarefas da lista.

Tecnologias usadas

Python

Flask

HTML

CSS

Funcionalidades

Adicionar novas tarefas

Marcar tarefas como concluídas

Remover tarefas da lista

Interface simples no navegador

Estrutura do projeto

todo-flask
│
├── app.py
├── README.md
│
├── templates
│ └── index.html
│
└── static
└── style.css

Como executar o projeto

Instale as dependências:

pip install flask

Execute o arquivo principal:

python app.py

Abra o navegador e acesse:

http://127.0.0.1:5000

Observação

Esse projeto usa uma lista em memória para armazenar as tarefas.
Isso significa que se o servidor for reiniciado, as tarefas serão apagadas.
