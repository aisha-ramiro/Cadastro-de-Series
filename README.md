# Cadastro de Séries

Projeto simples de CRUD (Create, Read, Update, Delete) de séries utilizando **PHP + MySQL**, com HTML, CSS e JavaScript para a interface.

---

## 👥 Desenvolvido por

- Aisha Ramiro
- Bruna Scaramuzza
- Lucas Freitas
- Vitor Gibertoni

---

## 📁 Estrutura do Projeto

```
Cadastro-de-Series/
├── php/
 └──  conexao.php
 └── index.php
 └──  inserir.php
 └──  editar.php
 └── excluir.php
├── css/
 └── style.css
├── server.js
└── banco-dados.txt   ← contém as instruções SQL para criar a tabela no phpMyAdmin
```

---

## ⚙️ Requisitos

- XAMPP instalado
- PHP 7.4 ou superior
- MySQL rodando localmente (via phpMyAdmin)

---

## 🚀 Como rodar o projeto

1. Coloque a pasta do projeto dentro de `C:/xampp/htdocs/`
2. Inicie o **Apache** e **MySQL** no XAMPP
3. Acesse o `phpMyAdmin` em:  
   [http://localhost/phpmyadmin](http://localhost/phpmyadmin)
4. Crie um banco de dados chamado `api_series`
5. Abra o arquivo `banco-dados.txt` do projeto e **cole o conteúdo no SQL do phpMyAdmin** para criar a tabela
6. Acesse o sistema pelo navegador:  
   [http://localhost/Cadastro-de-Series/index.php](http://localhost/Cadastro-de-Series/index.php)

---

## 🧠 Funcionalidades

- Cadastrar uma nova série
- Listar todas as séries cadastradas
- Editar dados de uma série
- Excluir uma série
- Pesquisar séries por título

---

## 🛠 Configuração do Banco de Dados

Se necessário, edite o arquivo `conexao.php` com as credenciais do seu banco:

```php
$host = "localhost";
$user = "root";
$senha = "";
$banco = "api_series";
```

---

## 🗃️ Observação

O arquivo `banco-dados.txt` na raiz do projeto contém o script SQL necessário para criar a tabela `series` no phpMyAdmin.

---

## 📸 Interface

A interface do sistema é simples e responsiva, com formulário centralizado, botões estilizados e tabela de visualização completa com todas as informações da série.

---

## ✔️ Conclusão

Este projeto foi desenvolvido com fins didáticos, aplicando os conceitos de CRUD em PHP com banco MySQL e interface personalizada com HTML, CSS e JavaScript.