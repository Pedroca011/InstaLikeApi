# Insta-Like API

Bem-vindo à **Insta-Like API**, uma API desenvolvida para permitir que usuários subam fotos e adicionem descrições. Este projeto foi criado para atender às necessidades de aplicações que desejam fornecer recursos semelhantes ao Instagram.

## 📋 Recursos

A Insta-Like API oferece as seguintes funcionalidades:

- **Upload de fotos**: Usuários podem enviar imagens para o servidor.
- **Adição de descrições**: Cada foto enviada pode ter uma descrição associada.
- **Gerenciamento de fotos**: Possibilidade de listar, editar ou excluir fotos existentes.
- **Integração com o Gemini**: Todas as funcionalidades foram otimizadas para integração com a biblioteca Gemini.

## 🛠️ Tecnologias Utilizadas

- **Node.js**: Plataforma de execução JavaScript no backend.
- **Express.js**: Framework para construção de APIs rápidas e robustas.
- **Multer**: Middleware para upload de arquivos.
- **MongoDB**: Banco de dados NoSQL para armazenamento das fotos e descrições.
- **Gemini**: Para otimização e manipulação de imagens.

## 🚀 Como começar

### Pré-requisitos

Antes de começar, você precisará ter instalado na sua máquina:

- [Node.js](https://nodejs.org/) (versão 16 ou superior)
- [MongoDB](https://www.mongodb.com/)
- Um gerenciador de pacotes como [npm](https://www.npmjs.com/) ou [yarn](https://yarnpkg.com/)

### Instalação

1. Clone este repositório:

   ```bash
   git clone https://github.com/seu-usuario/insta-like-api.git

2. Acesse o diretório do projeto:

    ```bash
    cd insta-like-api
3. Instale as dependências:

   ```bash
   npm install
   
4. Configure as variáveis de ambiente criando um arquivo .env com os seguintes campos:

   ```bash
   STRING_CONEXAO = string de coneão com o banco
   GEMINI_API_KEY = codigo da api do Gemini

5. inicie o projeto:

   ```bash
   npm run dev
