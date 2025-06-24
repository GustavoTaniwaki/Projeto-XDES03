# Projeto-XDES03

## 📚 Projeto: Aplicação Web com Autenticação e CRUD Completo
---

Este repositório contém uma aplicação web desenvolvida como parte de um trabalho acadêmico para a disciplina de Programação web (XDES03) com foco em autenticação, CRUD, uso de API externa e comunicação FullStack. O projeto foi desenvolvido utilizando tecnologias modernas para entregar uma aplicação funcional, segura e responsiva.

## 🧩 Problema
---

Hoje em dia, muitas aplicações web necessitam de controle de acesso, cadastro de usuários, e persistência de dados com segurança. Desenvolver uma aplicação do zero com autenticação e manipulação de dados é um desafio comum para qualquer desenvolvedor web em formação. Este projeto visa justamente suprir esse desafio, servindo como base de aprendizado prático.

## 🎬 Nossa Solução para o Projeto: CineRate - Avalie, comente e descubra novos filmes!
---

**CineRate** é uma aplicação web desenvolvida com o objetivo de permitir que usuários avaliem e comentem filmes, além de consultar informações diretamente da [OMDb API](https://www.omdbapi.com/).

## 🎯 Objetivo
---

Criar uma aplicação web completa que permita:

- Autenticação de usuários via login e cadastro
- Controle de acesso via rotas privadas
- Operações de CRUD ( Create Read Update Delete): criar, ler, atualizar, deletar
- Consumo de uma API externa pública
- Comunicação entre frontend e backend via HTTP (GET, POST, PUT, DELETE)

## 🚀 Tecnologias Utilizadas
---

### Frontend

- **Framework:** React
- **Validações:** Yup + React Hook Form
- **Roteamento:** React Router
- **Autenticação:** JSON Web Tokens (JWT)
- **Requisições HTTP:** Axios

### Backend

- **Linguagem:** Node.js
- **Framework:** Express
- **Persistência:** Arquivo JSON ou sistema de arquivos
- **Autenticação:** JWT

### Outros

- **Versionamento:** Git + GitHub
- **API Externa:** [OMDb API][(https://www.omdbapi.com/)]
- **Hospedagem do repositório:** GitHub

## 🖥️ Funcionalidades da Aplicação
---

### 👤 Autenticação
---

- Cadastro com: Nome de usuário, Email, Senha, Confirmação de Senha
- Login com: Email e Senha
- Validações:
  - Campos obrigatórios
  - Email válido
  - Senha com no mínimo 4 caracteres
  - Senha e confirmação iguais
  - Email único

### 🔐 Rotas Privadas
---

- Acesso restrito ao painel principal
- Redirecionamento automático caso o token JWT esteja ausente ou inválido

### 📝 Avaliações de Filmes
---

- Buscar filme por título (com dados da OMDb)
- Criar avaliação com nota e comentário
- Editar avaliação existente
- Remover avaliação
- Listar todas as avaliações do usuário

### 🌐 API Externa
---

- A aplicação consome dados da API pública OMDb API (The Open Movie Database) que fornece informações detalhadas sobre filmes, séries e episódios de TV. Ela é amplamente utilizada para projetos relacionados a cinema, catálogos de filmes, sistemas de avaliação e recomendação, entre outros.

## 🔧 Como Executar o Projeto
---

### Backend

```bash
# Acesse a pasta backend
cd backend

# Instale as dependências
npm install

# Execute o servidor
npm start
```

### Frontend
```bash

# Acesse a pasta frontend
cd frontend

# Instale as dependências
npm install

# Execute o servidor
npm start
```

## 📁 Estrutura de Pastas
---

```bash
cinerate/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── server.js
├── frontend/
│   ├── src/
│   │   ├── pages/
│   │   ├── components/
│   │   ├── services/
│   │   └── App.tsx
└── README.md
```

## 🧪 Requisitos Técnicos Atendidos
---

| Requisito | Descrição | Status |
|----------|-----------|--------|
| Aplicação Web | Roda no navegador | ✅ |
| Login/Cadastro | Com validações | ✅ |
| Rotas Privadas | Protegidas por token | ✅ |
| Frontend | Utiliza React | ✅ |
| Backend | Utiliza Express/Node.js | ✅ |
| Comunicação HTTP | GET, POST, PUT, DELETE | ✅ |
| CRUD completo | Implementado | ✅ |
| E-mail único | Validação implementada | ✅ |
| Uso de API externa | SWAPI (Star Wars) | ✅ |
| Versionamento Git | Repositório público | ✅ |
| Documentação | README com detalhes | ✅ |

📸 Layout 
---
Adicionar imagens do front

📌 Conclusão
---
O CineRate foi criado como parte de uma jornada prática no universo do desenvolvimento full stack. Mais do que um simples projeto acadêmico, ele representa a integração de tecnologias modernas com conceitos fundamentais, como autenticação via JWT, rotas protegidas, validação de formulários e consumo de APIs externas.

Durante o desenvolvimento, buscamos simular desafios reais do mercado, aplicando boas práticas e explorando ferramentas que são amplamente utilizadas em aplicações profissionais. O resultado é uma plataforma funcional, intuitiva e segura — ideal tanto para aprendizado quanto para servir como base em projetos futuros.


👥 Contribuidores
---
<table>
  <td align="center"><a href="https://github.com/thais-souza311"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/84544053?v=4" width="100px;" alt=""/><br /><sub><b>Thais Souza</b></sub></a><br /><a href="https://github.com/thais-souza311" title="RepiMe">:technologist:</a></td>
</table>

[Maria Eduarda]

[Ryan Mazzeu]

[Gustavo Taniwaki]
