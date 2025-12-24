# To-Do List API (TCC Pós-Graduação Full Stack)

Backend da aplicação de gerenciamento de tarefas.

## 🚀 Tecnologias Utilizadas

* **Node.js**
* **Express**
* **MySQL 8.0**
* **Prisma ORM**
* **Docker & Docker Compose**
* **TypeScript**

## 🗂 Arquitetura e Estrutura de Dados

O banco de dados foi modelado utilizando Prisma, contendo as seguintes entidades:
* **User:** Gerenciamento de acesso e autenticação.
* **Task:** Tarefas com título, descrição e status.
* **Category:** Organização de tarefas (Relacionamento N:1).

## 🔧 Como rodar o projeto localmente

### Pré-requisitos
* Docker e Docker Compose V2 instalados.
* Node.js (v18 ou superior).
* NPM.

### 1. Clonar e Instalar Dependências
```bash
git clone https://github.com/Cezaniltom/tcc-project.git
cd todo-list-api
npm install