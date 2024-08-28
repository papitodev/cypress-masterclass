![poster](./.github/poster.png)

# 📚 Criando e Testando APIs com Cypress

Aprenda a desenvolver APIs RESTful de forma eficiente utilizando Node.js e Express, integrando o MongoDB como banco de dados, e automatize todo o processo de testes de ponta a ponta com o Cypress.

## 🛠️ Desenvolvimento de APIs

Aprenda a criar APIs RESTful com Node.js e Express, estruturando rotas e implementando operações CRUD básicas.

## 🗃️ Banco de Dados

Você aprenderá a conectar sua aplicação ao MongoDB utilizando Mongoose, além de modelar e manipular dados através de schemas. 

## 🔍 Testando APIs com Cypress

Aprenda a criar testes para cada endpoint, focando nas operações CRUD. Vamos explorar técnicas para simular e validar respostas da API.

## **Pré-requisitos:**

1. **Node.js (versão 20.x LTS)**  
   Certifique-se de ter o Node.js instalado, preferencialmente na versão 20.x LTS, para garantir compatibilidade e suporte de longo prazo.

2. **Visual Studio Code**  
   Utilize o Visual Studio Code como seu ambiente de desenvolvimento. Esta IDE é altamente recomendada por sua integração com ferramentas de desenvolvimento, extensões e suporte para Node.js.

3. **Windows Terminal**  
   O Windows Terminal é recomendado para gerenciar seus shells de forma eficiente, permitindo a execução de múltiplos terminais em uma única janela com suporte a diferentes shells e configurações personalizáveis.

4. **Git Bash**  
   Instale o Git Bash para usar uma interface de linha de comando Unix no Windows. Isso facilitará o uso de comandos Git e scripts de shell no ambiente de desenvolvimento.

## **Prompt:**

Crie uma API RESTful em Node.js para um sistema de cadastro de livros. A API deve incluir as seguintes funcionalidades:

1. **Cadastro de livros**: Permita que os usuários cadastrem livros informando título, autor, editora, ano de publicação e número de páginas. Todos os campos são obrigatórios.
2. **Listagem de livros**: Implemente um endpoint para listar todos os livros cadastrados, retornando todas as informações dos livros.
3. **Consulta de livro por ID**: Crie um endpoint que permita consultar um livro específico usando seu ID.
4. **Remoção de livro**: Implemente um endpoint para deletar um livro do sistema utilizando seu ID.
5. **Banco de Dados**: Utilize o MongoDB como banco de dados.

#### **Requisitos técnicos:**

- Utilize Express.js para gerenciar as rotas da API.
- Use Mongoose para a modelagem dos dados e integração com o MongoDB.
- Inclua tratamento de erros e validações adequadas para todos os endpoints.
- Adicione comentários no código para explicar as principais partes da implementação.

## **Subindo a API 🚀**

1. Clonar o repositório e instalar as dependências:

```bash
npm install
```

2. Para executar a API execute:

```bash
npm start
```

