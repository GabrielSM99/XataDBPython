-XataDBX

Esse é um projeto que usa scripts de paginação, população e testes com  o XataDB. O objetivo desse projeto é gerar dados por meio de bibliotecas como random e faker, automatizar algumas operações de banco de dados e testes unitarios basicos.

Paginacao: Divisao dos datasets em paginas menores, suporte a parametros customizaveis e visualização dos dados paginados para validação
Tests: Testes unitarios para verificar a integridade dos dados e relatorio automatizados com os resultados dos testes.
Populacao: Auto geração de dados ficticios para popular o XataDB.

Tecnologias Usadas

Python: Usado para a lógica principal do projeto.

XataDB: Banco de dados para armazenar as informações.

Como usar:
-Clone o repositório

git clone https://github.com/GabrielSM99/XataDBPython.git

-Instale os requisitos

1-
sudo apt update
sudo apt install -y pkg-config libcairo2-dev
pip install -r requirements.txt

-Abra o jupyter notebook

pip install notebook
jupyter notebook
