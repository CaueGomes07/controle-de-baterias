# 📡 Controle Operacional de Bancos de Baterias - API

API RESTful desenvolvida com Node.js, Express, Sequelize e MySQL para controle de bancos de baterias em torres de telecomunicações.

---

## 📌 Objetivo

Monitorar, manter e gerenciar o ciclo de vida das baterias instaladas em torres, garantindo:
- Cadastro de torres, marcas, bancos e baterias
- Histórico de manutenções e baterias desativadas
- Geração de alertas automáticos
- Acompanhamento de pedidos de baterias
- Visualizações via views SQL
- Automação com procedures e eventos

---

## 🧱 Stack Utilizada

- **Node.js** + **Express** (API REST)
- **Sequelize** (ORM)
- **MySQL** (banco de dados relacional)
- **Docker** (ambiente isolado)
- **Jest** (testes automatizados)
- **Swagger** (documentação da API)

---

## 📂 Estrutura do Projeto


/ctr-batery-api
├── /src
│   ├── /config
│   ├── /controllers
│   ├── /routes
│   ├── /models
│   ├── /services
│   ├── /middlewares
│   ├── app.js
│   └── server.js
├── /migrations
├── /seeders
├── /docs
├── /tests
├── .env
├── Dockerfile
├── docker-compose.yml
├── package.json
└── README.md

