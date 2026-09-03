# 👥 Cadastro de Clientes

Aplicação web desenvolvida para realizar o **cadastro e gerenciamento de clientes**, permitindo adicionar, visualizar, editar e excluir registros.

O projeto utiliza **Firebase Realtime Database** como banco de dados, possibilitando a sincronização dos dados em tempo real, além de **Semantic UI** para a construção da interface.

## 🎯 Objetivo

O principal objetivo deste projeto é desenvolver uma aplicação prática para gerenciamento de clientes, colocando em prática conceitos de **desenvolvimento web, JavaScript, CRUD e banco de dados em nuvem**.

A aplicação permite centralizar informações dos clientes em uma interface simples e organizada.

## ⚙️ Funcionalidades

O sistema possui as seguintes funcionalidades:

* ➕ Cadastro de clientes;
* 📋 Listagem dos clientes cadastrados;
* ✏️ Edição de clientes;
* 🗑️ Exclusão de clientes;
* 🔄 Atualização dos dados em tempo real;
* ✅ Validação dos campos obrigatórios;
* 💬 Mensagens de confirmação e erro;
* 📱 Interface adaptável para diferentes tamanhos de tela.

## 👤 Dados cadastrados

Para cada cliente, o sistema permite armazenar:

* **Nome**
* **CPF**
* **Telefone**
* **Cidade**
* **Endereço**
* **Data de nascimento**

Os registros são armazenados na coleção `clientes` do Firebase Realtime Database.

## 🗄️ Banco de dados

O projeto utiliza o **Firebase Realtime Database** para armazenamento dos clientes.

A estrutura é organizada utilizando identificadores únicos gerados pelo próprio Firebase:

```text
clientes
 ├── ID_DO_CLIENTE
 │    ├── nome
 │    ├── cpf
 │    ├── telefone
 │    ├── cidade
 │    ├── endereco
 │    └── nascimento
 │
 └── ID_DO_CLIENTE
      ├── nome
      ├── cpf
      ├── telefone
      ├── cidade
      ├── endereco
      └── nascimento
```

A aplicação utiliza listeners do Firebase para acompanhar alterações no banco e atualizar automaticamente a tabela de clientes.

## 🔄 Operações CRUD

O projeto implementa as quatro operações básicas de um CRUD:

| Operação   | Funcionamento                                         |
| ---------- | ----------------------------------------------------- |
| **Create** | Cadastra um novo cliente utilizando `push()`          |
| **Read**   | Recupera e exibe os clientes utilizando `on("value")` |
| **Update** | Atualiza os dados utilizando `update()`               |
| **Delete** | Remove clientes utilizando `remove()`                 |

Essa implementação permite trabalhar de forma prática com o ciclo completo de gerenciamento de registros.

## 🛠️ Tecnologias utilizadas

* **HTML5**
* **CSS3**
* **JavaScript**
* **jQuery**
* **Semantic UI 2.5.0**
* **Firebase Realtime Database**
* **Firebase JavaScript SDK 9.23.0**

## 🎨 Interface

A interface foi desenvolvida utilizando componentes do **Semantic UI**, proporcionando uma estrutura organizada para o formulário de cadastro e para a tabela de clientes.

O sistema possui:

* Formulário de cadastro;
* Campos organizados em duas colunas;
* Botão de salvamento;
* Tabela de clientes;
* Botões para edição e exclusão;
* Rodapé da aplicação.

## 🚀 Como executar

### Pré-requisitos

* Navegador web;
* Editor de código, como Visual Studio Code;
* Conexão com a internet;
* Projeto configurado no Firebase.

### Execução

1. Clone ou baixe este repositório;
2. Abra o projeto no editor de código;
3. Certifique-se de que a configuração do Firebase esteja corretamente definida;
4. Abra o arquivo `index.html` através de um servidor local;
5. Acesse a aplicação pelo navegador.

O projeto utiliza os arquivos externos do Semantic UI, jQuery e Firebase, portanto é necessária conexão com a internet para carregar essas dependências através dos CDNs utilizados.

## 📂 Estrutura do projeto

Uma estrutura básica do projeto é composta por:

```text
cadastro-clientes/
│
├── index.html
├── app.css
└── README.md
```

O arquivo `index.html` contém a estrutura da aplicação, enquanto o `app.css` é responsável pelos estilos personalizados.

## 📚 Conceitos praticados

Durante o desenvolvimento foram aplicados conceitos como:

* Estruturação de páginas com HTML;
* Estilização com CSS;
* Manipulação do DOM;
* Funções JavaScript;
* Eventos e interações com o usuário;
* Template literals;
* Promises;
* Manipulação de objetos;
* Operações CRUD;
* Integração com banco de dados;
* Firebase Realtime Database;
* Sincronização de dados em tempo real;
* Validação de informações;
* Tratamento de erros.

## 📈 Aprendizados

Este projeto proporcionou prática principalmente na integração entre **front-end e banco de dados**, demonstrando como uma aplicação JavaScript pode realizar operações de cadastro, consulta, atualização e exclusão de informações utilizando um banco de dados em nuvem.

Também foi possível compreender na prática o funcionamento de um **CRUD completo** e a utilização de eventos para manter a interface sincronizada com os dados armazenados.

## 📌 Finalidade

Este projeto possui finalidade **educacional**, sendo desenvolvido para praticar conceitos de desenvolvimento web, JavaScript e integração com banco de dados.

## 👨‍💻 Autor

**Matheus Henrique Fernandes**

---

⭐ Projeto desenvolvido como prática de desenvolvimento web, CRUD e Firebase.
