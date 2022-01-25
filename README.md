# Empreenday GH actions

Repositório criado com o prósito de servir de base para o workshop de configuração de CI/CD com GithubActions
para o Empreenday 2022

Recursos:

- NodeJS
- Typescript
- ExpressJS
- JEST
- Heroku cloud

---

### Requisitos:

1 - Instale o nodejs em sua máquina

2 - Instale o yarn ou npm

---

### Instruções de uso:

1 - Instale as dependências CMD: `yarn` ou ` npm i` dentro da pasta raiz do projeto

2 - Rode o software em modo de desenvolvimento utilizando yarn dev

3 - Rode os testes unitários e funcionais com o comando `yarn test`

---

### Atividade do workshop:

1 - Fazer publicação manual com o Heroku CLI

2 - Integrar o repositório com a branch beta através do heroku para que os deploys ocorram a cada merge na branch beta

3 - Fazer CI que rode os testes com github action em cada pullrequest aberto e/ou atualizado

4 - Fazer CI que gere uma nova tag e faça um release no repositório

5 - Fazer CI/CD, criando integração com um tregger em novas release para o heroku via GH action
