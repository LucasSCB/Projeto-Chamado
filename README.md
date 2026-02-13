# 🚀 Sistema de Chamados - Backend

API RESTful para gerenciamento de chamados (Helpdesk), com autenticação JWT, controle de permissões (ADMIN/USER), paginação, filtros e testes automatizados.

---

## 📚 Tecnologias Utilizadas

- Node.js
- Express
- Prisma ORM
- SQLite (dev)
- JWT (Autenticação)
- Jest + Supertest (Testes automatizados)
- Thunder Client (para testes manuais)

---

## 🔐 Funcionalidades

### Autenticação
- Login com email e senha
- Geração de token JWT
- Middleware de proteção de rotas
- Controle de permissões por perfil (ADMIN / USER)

### Chamados (CRUD Completo)
- Criar chamado
- Listar chamados (com paginação)
- Buscar por ID
- Atualizar status (ABERTO, EM_ANDAMENTO, FECHADO)
- Deletar chamado (apenas ADMIN)

### Filtros Avançados
- Paginação (`page` e `limit`)
- Filtro por status
- Busca por texto (`q` em título e descrição)

### Testes Automatizados
- Testes de autenticação
- Testes de criação e atualização de chamados
- Validação de status inválido
- Testes de permissões

---

