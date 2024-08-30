# Sistema de Pizzaria

**Disciplina:** API Backend  
**Aluno:** João Victor Guimarães Santos  
**Tecnologias:** Laravel 11, PHP 8.2  

## Descrição do Projeto

Este projeto é um sistema de pizzaria desenvolvido como parte da disciplina de API Backend. O sistema foi construído utilizando o framework Laravel na versão 11, com PHP 8.2. O objetivo do sistema é gerenciar pedidos de pizza, cardápios, usuários e entrega de forma eficiente e organizada.

## Funcionalidades

- **Cadastro  de Usuários:** O sistema permite que novos usuários se cadastrem e façam login para acessar funcionalidades exclusivas.

## Tecnologias Utilizadas

- **Laravel 11:** Framework PHP para desenvolvimento de aplicações web robustas.
- **PHP 8.2:** Linguagem de programação utilizada para o desenvolvimento do backend.
- **MySQL:** Banco de dados relacional para armazenar informações de usuários, pedidos e cardápio.
- **Composer:** Gerenciador de dependências para PHP, utilizado para instalar pacotes e bibliotecas necessárias para o projeto.

## Instalação

Para rodar este projeto localmente, siga os passos abaixo:

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/joaosantosg/6semestre-backend
   ```

2. **Acesse o diretório do projeto:**
   ```bash
   cd 6semestre-backend/sistema_pizzaria
   ```

3. **Instale as dependências:**
   ```bash
   composer install
   ```

4. **Configure o arquivo `.env`:**  
   Copie o arquivo `.env.example` para `.env` e configure as variáveis de ambiente, incluindo a conexão com o banco de dados.

5. **Gere a chave da aplicação:**
   ```bash
   php artisan key:generate
   ```

6. **Execute as migrações do banco de dados:**
   ```bash
   php artisan migrate
   ```

7. **Inicie o servidor local:**
   ```bash
   php artisan serve
   ```

O sistema estará disponível em [http://localhost:8000](http://localhost:8000).

## Uso

- Acesse a aplicação pelo navegador.
- Crie uma conta ou faça login com uma conta existente.
- Navegue pelas funcionalidades de gerenciamento de cardápio, pedidos e entregas.

## Estrutura do Projeto

O projeto segue a estrutura padrão do Laravel:

- **app/**: Contém o código-fonte da aplicação, incluindo Models, Controllers e Services.
- **config/**: Configurações gerais da aplicação.
- **database/**: Migrações, seeds e factories do banco de dados.
- **public/**: Arquivos públicos acessíveis, como CSS, JS e imagens.
- **resources/**: Views e assets utilizados na aplicação.
- **routes/**: Definição das rotas da aplicação.
- **tests/**: Testes automatizados.
