# GoFinances Backend 💸
Este repositório é referente ao backend da iniciativa GoFinances, desenvolvido dentro Bootcamp GoStack 11.0, da Rocketseat 🚀. <br />
Versão Mobile: https://github.com/andrecampll/GoFinancesMobile <br />
Versão Web: https://github.com/andrecampll/GoFinancesWeb

# Proposta
Este projeto é uma aplicação desenvolvida para controle financeiro que provê ao usuário
todas as informações sobre suas transações financeiras, mostrando seus gastos e
ganhos ao longo do tempo. A aplicação também é um estudo dos conceitos de SOLID, da aplicação dos conceitos de Repository e
Service no backend da aplicação e de Relacionamento em Banco de Dados.

# Tecnologias Utilizadas
NodeJS ⚛️ <br />
Express ⚛️ <br />
Postgres 🐘 <br />
Docker 🐋 <br />
Cors ⌨️ <br />
Typescript ⌨️ <br />

# Utilização
⚠️ Certifique-se de ter o Postgres em sua máquina  ⚠️

Para obter esse projeto, siga os passos:
1. Inicialize o Postgres. Caso esteja usando Docker, rode <code>docker run "NOME DA IMAGEM DO POSTGRES"</code>.
2. Configure as credenciais de acesso ao seu Postgres no arquivo "ormconfig.json".
3. Crie a database "gostack_desafio06".
4. Rode o comando <code> yarn </code> na raíz da pasta do projeto clonado para baixar as dependências.
5. Rode o comando <code> yarn typeorm migration:run </code> na raíz da pasta do projeto para executar todas as migrations do banco.
6. Rode <code> yarn dev:server </code> na raíz da pasta do projeto para inicializar o servidor local.
7. Se tudo deu certo, aparecerá uma mensagem no terminal: "Server started at port 3333 🚀".

🚀
