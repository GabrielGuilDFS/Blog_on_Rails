README
Blog Simples em Ruby on Rails
Projeto básico de blog desenvolvido com Ruby on Rails, utilizando PostgreSQL como banco de dados.

Funcionalidades
Criar, editar e deletar postagens

Cada postagem contém:

Título

Data de publicação

Conteúdo

Listagem de todas as postagens na página inicial

Tecnologias utilizadas
Ruby on Rails 8.0.2

Ruby 3.4.5

PostgreSQL

Pré-requisitos
Ruby 3.4.5 instalado

Rails 8.0.2 instalado

PostgreSQL instalado e configurado

RVM (Ruby Version Manager) recomendado para gerenciar a versão do Ruby

Como rodar o projeto localmente
1. Clone este repositório:
bash
Copy
Edit
git clone https://github.com/GabrielDFS/blog_on_rails.git
cd blog_on_rails
2. Instale o Ruby usando RVM (caso não tenha):
bash
Copy
Edit
rvm install 3.4.5
rvm use 3.4.5 --default
3. Instale as dependências do projeto:
bash
Copy
Edit
bundle install
4. Configure o banco de dados
Edite o arquivo config/database.yml para ajustar o usuário, senha e outras configurações do PostgreSQL conforme seu ambiente.

5. Crie e migre o banco de dados:
bash
Copy
Edit
rails db:create
rails db:migrate
6. Inicie o servidor Rails:
bash
Copy
Edit
rails server
7. Acesse o projeto no navegador:
Abra http://localhost:3000 no seu navegador.

System dependencies
Ruby 3.4.5

Rails 8.0.2

PostgreSQL 13+

RVM (opcional, mas recomendado)

Configuration
Configurações principais estão em config/database.yml para banco de dados

Demais configurações padrão do Rails

Database initialization
O banco é inicializado via:

bash
Copy
Edit
rails db:create
rails db:migrate
