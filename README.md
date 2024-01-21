# End-to-end Testing in Scratch App with Cypress

Project to demonstrate end-to-end (e2e) tests in [Scratch App](https://notes-serverless-app.com) written with [Cypress](https://cypress.io) running on GitHub Actions.

## Pre-requirements

To clone and run this project, you will need:

- [git](https://git-scm.com/downloads) (I've used version `2.25.1` while writing this doc)
- [Node.js](https://nodejs.org/en/) (I've used version `v20.10.0` while writing this doc)
- npm (I've used version `10.2.3` while writing this doc)

**Note:** When installing Node.js, npm is automatically installed. 🚀

## Installation

To install the dev dependencies, run `npm install` (or `npm i` for short.)

## Configuring the environment variables

Before running the tests, some environment variables need to be set up.

Make a copy of the [`cypress.env.example.json`](./cypress.env.example.json) file as `cypress.env.json`, and set the appropriate values for all the variables.

**Note:** The `cypress.env.json` file is not tracked by git since it's listed in the `.gitignore` file.

## Running the tests

In this project, you can run tests in interactive and headless modes, both on desktop and tablet viewports.

### Headless mode

Run `npm test` (or `npm t` for short) to run all tests in headless mode using a desktop viewport.

Run `npm run test:tablet` to run the appropriate tests in headless mode using a tablet viewport.

### Interactive mode

Run `npm run cy:open` to open the __Cypress App__ to run tests in interactive mode using a desktop viewport.

Run `npm run cy:open:tablet` to open the __Cypress App__ to run tests in interactive mode using a tablet viewport.

## Project description

Análise estática no código de teste para garantir o uso de convenções definidas pela comunidade ✔️
Testes e2e para diferentes funcionalidades de na aplicação Scratch App, tais como Sign up, Login, CRUD, etc. ✔️
Testar recebimento de e-mails ✔️
Testar upload de arquivos ✔️
Interagir com componentes renderizados dentro de iFrames ✔️
Interceptar requisições para tornar os testes mais robustos ✔️
Proteger dados sensíveis ✔️
Testar a responsividade da aplicação simulando seu uso em um dispositivo móvel ✔️
Armazenar a sessão do usuário no cache para otimizar o processo de autenticação ✔️
Criar e documentar comandos customizados ✔️
Configurar um workflow de integração contínua com múltiplas fases e paralelização ✔️
Integrar os testes com o Cypress Cloud ([visite aqui](https://cloud.cypress.io/projects/7rhrye))✔️
Categorizar os testes e executá-los por suas tags ✔️

___

Made with ❤️ by [Peri Barros](https://github.com/peribarros).