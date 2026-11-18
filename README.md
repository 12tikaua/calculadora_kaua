Calculadora Web (Python, Flask, HTML e JavaScript)

Este projeto é uma calculadora web desenvolvida utilizando Python, Flask, HTML e JavaScript.

O objetivo é demonstrar o funcionamento de uma aplicação web com operações matemáticas básicas.

Operações disponíveis

- Soma: realiza a adição de dois números.
- Subtração: realiza a diferença entre dois números.
- Multiplicação: calcula o produto de dois números.
- Divisão: realiza a divisão entre dois números, com tratamento para divisão por zero.

Requisitos

- Python 3 instalado
- VS Code
- Git
- Ambiente virtual (venv)
- Flask instalado

Estrutura do projeto

calculadora_Kaua/
│
├── app.py
├── operacoes.py
├── requirements.txt
├── README.md
├── templates/
│   ├── index.html
│   ├── soma.html
│   ├── subtracao.html
│   ├── multiplicacao.html
│   └── divisao.html
│
└── static/
    └── script.js

Criando o ambiente virtual

No terminal, dentro da pasta do projeto, execute:

py -m venv venv

Ative o ambiente virtual:

.\venv\Scripts\Activate.ps1

Instalando as dependências

Com o ambiente virtual ativado, execute:

python -m pip install -r requirements.txt

Executando a aplicação

Execute:

python app.py

Depois, abra o navegador e acesse:

http://127.0.0.1:5000

Desenvolvedor

Kaua Andrade

Projeto desenvolvido como atividade acadêmica para praticar Python, Flask, HTML, JavaScript e Git/GitHub.