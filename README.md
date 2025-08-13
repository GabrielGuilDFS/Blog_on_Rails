# Blog Simples em Ruby on Rails

Projeto básico de blog desenvolvido com Ruby on Rails, utilizando PostgreSQL como banco de dados.

---

### 1. Funcionalidades

- Criar, editar e deletar postagens
- Cada postagem contém:
  - Título
  - Data de publicação
  - Conteúdo
- Listagem de todas as postagens na página inicial

---

### 2. Tecnologias utilizadas

- Ruby on Rails 8.0.2
- Ruby 3.4.5
- PostgreSQL

---

### 3. Pré-requisitos

- Ruby 3.4.5 instalado
- Rails 8.0.2 instalado
- PostgreSQL instalado e configurado
- RVM (Ruby Version Manager) recomendado para gerenciar a versão do Ruby

---

### 4. Como rodar o projeto localmente

1. Clone este repositório:

```bash
git clone https://github.com/GabrielDFS/blog_on_rails.git
cd blog_on_rails
```
### 6. Instale o Ruby usando RVM (caso não tenha):
rvm install 3.4.5
rvm use 3.4.5 --default

### 7. Instale as dependências do projeto:
bundle install

### 8. Configure o banco de dados
- Edite o arquivo config/database.yml para ajustar o usuário, senha e outras configurações do PostgreSQL conforme seu ambiente.

### 9. Crie e migre o banco de dados:
rails db:create
rails db:migrate

### 10. Inicie o servidor Rails:
rails server

### 11. Acesse o projeto no navegador:
- Abra http://localhost:3000 no seu navegador.

### System dependencies
- Ruby 3.4.5

- Rails 8.0.2

- PostgreSQL 13+

- RVM (opcional, mas recomendado)

### Configuration
- Configurações principais estão em config/database.yml para banco de dados

- Demais configurações padrão do Rails

- Database initialization
  
- O banco é inicializado via:

rails db:create
rails db:migrate
