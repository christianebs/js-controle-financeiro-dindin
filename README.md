![visitors](https://visitor-badge.laobi.icu/badge?page_id=christianebs.js-controle-financeiro-dindin) ![GitHub Repo stars](https://img.shields.io/github/stars/christianebs/js-controle-financeiro-dindin) ![GitHub pull requests](https://img.shields.io/github/issues-pr/christianebs/js-controle-financeiro-dindin) ![GitHub closed issues](https://img.shields.io/github/issues-closed/christianebs/js-controle-financeiro-dindin)

# API de Controle Financeiro - Dindin

Este projeto foi desenvolvido como parte do Módulo 3 da **Cubos Academy**, consiste em uma API denominada "Dindin". Com o objetivo de proporcionar uma solução eficiente para a gestão financeira pessoal, a API permite operações como cadastro de usuário, login, edição de perfil, gerenciamento de categorias e transações, e obtenção de extrato financeiro. 

## :woman_mechanic: Linguagens e Ferramentas

![JavaScript](https://img.shields.io/badge/javascript-0D1117.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![Postgres](https://img.shields.io/badge/postgres-0D1117.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0D1117.svg?style=for-the-badge&logo=visual-studio-code&logoColor=0078d7) ![Insomnia](https://img.shields.io/badge/Insomnia-0D1117?style=for-the-badge&logo=insomnia&logoColor=5849BE) ![Beekeeper](https://img.shields.io/badge/beekeeper-0D1117?style=for-the-badge&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAMAAAAolt3jAAAAIGNIUk0AAHomAACAhAAA+gAAAIDoAAB1MAAA6mAAADqYAAAXcJy6UTwAAAFNUExURQAAAP//a/rXOvPUOejMN/jWOvjWOenQOP/fPP3VOf/nOf/xP+zSOPzYOvvYOo98IfTTOfjWOvjWOfjWOffWOf//R1xQFUc+EO7NN/jWOvjWOfjWOffWOfjWOf/cO5J+IvjWOfjWOfjWOffWOfjWOfjWOvfWOfjWOvjWOvnXO/nXOvjWOvfWOfjWOfjWOfjWOfjWOfjWOvfWOfjWOfjWOfjWOvfWOfjWOfjWOfnXOjoyDe/ON/vYOvzZOv3aO5WBIjkxDd7AM8esLpJ+ItC0MPrYOvjWOZaBIzUuDKONJqSOJj83DiQfCJSAIvXTOTcvDM2xL/HQOObGNXppHBUTBcCmLO/PN/rXOvvZOuTFNSokCZqFJJiDIyslCuXGNeXFNbyiKxQRBH5sHefHNX1sHRUSBb+lLPTSOI57ISMeCJF9IfTTOXtrHM+zMP///548sBYAAAA5dFJOUwAAAAAAAAAAAAAAAAAAABqI7eyGGQpYx/v7xlYKNa729qw0KtTSKWH6aPxiK9U3sPf3C1rJ/ByK7y1GWkAAAAABYktHRG4iD1EXAAAAB3RJTUUH5wkZEwMcxtjpWwAAAJtJREFUCB0FwdtKw0AUQNG9JydOW6wIUgUviOiL4P//iC8iiC0iFQURvFBCMse1BDxQ9dMJw0P1irX6rrOVnqk5bXXrtaeq6s/y2QiZqer8o8soQlXVKBnA7vtcVSGACx3Yaw0IyNAeNaGUNtZah+Gt78dWupPu6KV+HbN63Cz/cHGj88tXctq1fHJ/uFODMTPvq9AtbpXMh9+Jf7viMqPTlzUXAAAAJXRFWHRkYXRlOmNyZWF0ZQAyMDIzLTA5LTI1VDE5OjAzOjI4KzAwOjAwxaUCOQAAACV0RVh0ZGF0ZTptb2RpZnkAMjAyMy0wOS0yNVQxOTowMzoyOCswMDowMLT4uoUAAAAodEVYdGRhdGU6dGltZXN0YW1wADIwMjMtMDktMjVUMTk6MDM6MjgrMDA6MDDj7ZtaAAAAAElFTkSuQmCC&logoColor=5849BE) ![Git](https://img.shields.io/badge/git-0D1117.svg?style=for-the-badge&logo=git&logoColor=%23F05033) ![GitHub](https://img.shields.io/badge/github-0D1117.svg?style=for-the-badge&logo=github&logoColor=white)

## :paintbrush: Layout

- Insomnia

![js-dindin](https://github.com/christianebs/js-controle-financeiro-dindin/assets/108686840/b71d5dda-1053-4a37-be45-5d302a943a8c)

- Beekeeper

![banco-de-dados-dindin](https://github.com/christianebs/js-controle-financeiro-dindin/assets/108686840/cea380e7-0423-474b-bc06-13687f64f428)


## :triangular_flag_on_post: Contribua com o projeto

- Realize o Fork
- Faça as modificações necessárias
- Realize a Pull Request (PR)

## :card_file_box: Fucionalidades do Projeto

- [x] Gerenciamento de Usuários
    - Cadastrar Usuário
    - Fazer Login
    - Detalhar Perfil do Usuário Logado
    - Editar Perfil do Usuário Logado

- [x] Gerenciamento de Categorias
    - Listar categorias

- [x] Gerenciamento de Transações
    - Listar transações
    - Detalhar transação
    - Cadastrar transação
    - Editar transação
    - Remover transação

- [x] Relatórios e Consultas
    - Obter extrato de transações
    - Filtrar transações por categoria

## :computer: Rodando o Projeto

```shell
# 1. Clone o projeto

git clone https://github.com/christianebs/js-api-dindin/

# 2. Instale as dependências

npm install

# 3. Execute o servidor com nodemon para reinicialização automática

npm run dev
```

Observações:

- As dependências estão definidas no arquivo package.json. Ao executar **npm install**, todas elas serão instaladas 
- O arquivo package.json já contém a configuração necessária na seção de scripts para utilizar o nodemon:

```shell 
"scripts": {
    "dev": "nodemon ./src/index.js"
},
```
Essa configuração permite iniciar o servidor em modo de desenvolvimento usando o nodemon.

- Não é necessário inicializar um novo projeto Node.js com **npm init -y**, pois ao clonar o repositório, você já terá um package.json configurado.
- Para encerrar todos os serviços, utilize o atalho padrão do terminal pressionando **CTRL+C**. Esse comando interrompe a execução dos processos, encerrando o servidor e liberando o terminal.

## :arrows_counterclockwise: Endpoints

- POST /usuario - Cadastrar um novo usuário no sistema
- POST /login - Realizar o login de um usuário cadastrado
- GET /usuario - Obter informações do perfil do usuário autenticado
- PUT /usuario - Atualizar informações do perfil do usuário autenticado
- GET /categoria - Listar todas as categorias cadastradas
- GET /transacao - Obter uma lista de todas as transações do usuário logado
- GET /transacao/:id - Consultar detalhes de uma transação específica do usuário logado
- POST /transacao - Adicionar uma nova transação associada ao usuário logado
- PUT /transacao/:id - Atualizar informações de uma transação do usuário logado
- DELETE /transacao/:id - Excluir uma transação do usuário logado
- GET /transacao/extrato - Gerar um extrato com a soma de transações de entrada e saída do usuário logado
- GET /transacao?filtro[]=roupas&filtro[]=salários - Consultar transações do usuário logado com base em categorias específicas

## :woman_technologist: Desenvolvedoras


| [<img src="https://user-images.githubusercontent.com/108686840/271874870-1003d6c2-7574-4104-a392-ab6b2713cff2.png" width=115><br><sub>Christiane Barbosa</sub>](https://github.com/christianebs) | [<img src="https://avatars.githubusercontent.com/u/141354578?v=4" width=115><br><sub>Marcela Linhares</sub>](https://github.com/MarcelaLinhares) |
| :----------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------: |