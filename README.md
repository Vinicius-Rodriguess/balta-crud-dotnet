# 🧩 **Sistema de Gestão de Alunos (ASP.NET 7)**

Este projeto é uma aplicação web desenvolvida com **ASP.NET Core 7** utilizando **Razor Pages**. O sistema simula o gerenciamento de alunos e seus planos premium, com autenticação via **ASP.NET Identity** e persistência de dados em **SQLite**.

---

## 🚀 **Funcionalidades**

### **Back-End**

- Cadastro e autenticação de usuários com ASP.NET Identity.
- CRUD completo para as entidades:
  - **Student** (alunos)
  - **Premium** (planos premium)
- Relacionamento entre Student e Premium.
- Geração automática de páginas com **Scaffolding**.

---

## 🛠️ **Tecnologias Utilizadas**

- **.NET 7**: Plataforma principal do projeto.
- **Razor Pages**: Padrão de desenvolvimento web.
- **SQLite**: Banco de dados leve e local.
- **Entity Framework Core**: ORM para manipulação do banco.
- **ASP.NET Core Identity**: Autenticação e gerenciamento de usuários.
- **Bootstrap**: Estilização padrão das páginas scaffolded.

---

## 🔧 **Como o Sistema Funciona**

1. **Home Page**: Tela de boas-vindas com redirecionamento para login ou área autenticada.
2. **Cadastro/Login**: Implementado automaticamente via Identity.
3. **Área Autenticada**:
   - Acesso aos cadastros de estudantes.
   - Controle dos dados de planos premium associados.
4. **Relacionamento**:
   - Um estudante pode ter um plano premium associado.

---

## 📋 **Requisitos**

- SDK do **.NET 7**
- CLI do **Entity Framework**
- Editor recomendado: **Visual Studio 2022** ou superior

---

## 🔧 **Como Configurar o Projeto**

1. Clone este repositório:

   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio-dotnet.git
   cd seu-repositorio-dotnet
   ```

2. Restaure os pacotes e aplique a migração:

   ```bash
   dotnet restore
   dotnet ef database update
   ```

3. Inicie o projeto:

   ```bash
   dotnet run
   ```

4. Acesse o navegador:

   ```
   https://localhost:5001
   ```

---

## 💾 **Exemplo de Uso**

- Registre-se ou faça login no sistema.
- Cadastre estudantes e associe planos premium.
- Acesse e edite os registros existentes.

---

## ✅ **Melhorias Futuras**

- Validações mais robustas nos formulários.
- Layout personalizado e responsivo.
- Telas de visualização detalhada para registros.
- Funcionalidade de exportação de dados.

---

## 👨‍💻 **Autor**

**Vinicius Rodrigues**

- GitHub: [Vinicius-Rodriguess](https://github.com/Vinicius-Rodriguess)
- Email: rodrigues.vini.2004@gmail.com
