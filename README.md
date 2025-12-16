# 📦 Gerenciamento de Pedidos - AcademiaJava UFN

> Sistema Full Stack para controle de cadeia de suprimentos, integrando gestão de fornecedores, estoque e vendas.

![Status](https://img.shields.io/badge/Status-Finalizado-green)
![Java](https://img.shields.io/badge/Java-17-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.2-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

## 📄 Descrição

Projeto final desenvolvido para a **AcademiaJava UFN**. O objetivo é prover uma solução robusta para o gerenciamento de pedidos comerciais. Através de uma interface web intuitiva (SPA), os usuários podem gerenciar todo o ciclo de vida de uma venda, desde o cadastro do fornecedor e produto até o registro final do pedido e pagamento, tudo assegurado por autenticação via Token JWT.

## ✨ Funcionalidades

O sistema implementa o padrão CRUD (Create, Read, Update, Delete) completo para as seguintes entidades:

* 🏭 **Fornecedores:** Gestão de parceiros comerciais e CNPJ.
* 📦 **Produtos:** Controle de catálogo, preços e categorias.
* 👥 **Clientes:** Base de dados de compradores com endereços e contatos.
* 🛒 **Pedidos:** Processamento de vendas associando clientes a produtos.
* 💳 **Pagamentos:** Controle de status financeiro e métodos de pagamento.
* 🏷️ **Categorias:** Organização lógica dos produtos.

## 🚀 Arquitetura e Tecnologias

O projeto foi estruturado em uma arquitetura de microsserviços/monolito modular, separando claramente o Frontend do Backend.

### ☕ Back-end (API REST)
Construído com **Spring Boot**, focado em segurança e escalabilidade.
* **Spring Data JPA:** Para persistência de dados e mapeamento Objeto-Relacional.
* **Spring Security + JWT:** Implementação de segurança stateless para proteção das rotas da API.
* **MySQL:** Banco de dados relacional para armazenamento seguro.

### 🎨 Front-end (SPA)
Interface moderna desenvolvida em **Angular** com **TypeScript**.
* **Componentização:** Estrutura modular para reutilização de código.
* **Responsividade:** Design adaptável utilizando HTML5 e CSS3.
* **Integração:** Consumo da API REST via HTTP Client.

## 🔧 Como Executar o Projeto

### Pré-requisitos
* Java JDK 17+
* Node.js e NPM
* MySQL (Via XAMPP ou instalado nativamente)

### 1. Configurando o Backend
1.  Clone o repositório.
2.  Configure o arquivo `application.properties` com as credenciais do seu MySQL.
3.  Execute o projeto via Maven ou sua IDE de preferência.

### 2. Configurando o Frontend
1.  Navegue até a pasta do frontend:
    ```bash
    cd frontend
    ```
2.  Instale as dependências:
    ```bash
    npm install
    ```
3.  Inicie o servidor de desenvolvimento:
    ```bash
    ng serve
    ```
4.  Acesse a aplicação em: `http://localhost:4200`

## 🤝 Contribuição

Contribuições são bem-vindas!
1.  Faça um fork do projeto.
2.  Crie uma branch para suas alterações (`git checkout -b feature/MinhaNovaFeature`).
3.  Faça commit (`git commit -am 'Adicionando uma nova feature'`).
4.  Faça push para a branch (`git push origin feature/MinhaNovaFeature`).
5.  Abra um Pull Request.

---
