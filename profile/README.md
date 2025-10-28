## ClickEstoque.io
<p align="center">
  <img src= "LOGO2.png" heigth = "300px">
</p>

## Sobre 

Este projeto tem como objetivo desenvolver uma plataforma de venda de produtos, onde os usuários podem visualizar os produtos disponíveis e as lojas que os comercializam.A plataforma pode ser acessada tanto por usuários cadastrados quanto por visitantes não autenticados. Usuários registrados têm a possibilidade de cadastrar suas próprias lojas e anunciar produtos no site.Além disso, o sistema permite publicar comentários sobre os produtos e lojas hospedados na plataforma, promovendo a interação e a avaliação da comunidade.

Para a realização do projeto, foram utilizados as tecnologias: 

<p align="left">
  <img src="https://img.icons8.com/color/48/000000/nestjs.png" alt="NestJS" width="30" style="vertical-align:middle; margin-right:8px;" />
  <strong>NestJS</strong> – Framework Node.js para aplicações server-side escaláveis
</p>

<p align="left">
  <img src="https://i.pinimg.com/736x/4a/2b/e7/4a2be73b1e2efb44355436c40bf496dd.jpg" alt="Next.js" width="30" style="vertical-align:middle; margin-right:8px;" />
  <strong>Next.js</strong> – Framework React para SSR e SSG
</p>

<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" alt="TypeScript" width="30" style="vertical-align:middle; margin-right:8px;" />
  <strong>TypeScript</strong> – Superset do JavaScript com tipagem estática
</p>

<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript" width="30" style="vertical-align:middle; margin-right:8px;" />
  <strong>JavaScript</strong> – Linguagem base do ecossistema web
</p>

<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/prisma/prisma-original.svg" alt="Prisma" width="30" style="vertical-align:middle; margin-right:8px;" />
  <strong>Prisma</strong> – ORM moderno para Node.js e TypeScript
</p>

<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-original.svg" alt="Tailwind CSS" width="30" style="vertical-align:middle; margin-right:8px;" />
  <strong>Tailwind CSS</strong> – Framework CSS utilitário para estilização rápida
</p>

<p align="left">
  <img src="https://raw.githubusercontent.com/react-icons/react-icons/master/react-icons.svg" alt="React Icons" width="30" style="vertical-align:middle; margin-right:8px;" />
  <strong>React Icons</strong> – Biblioteca de ícones para projetos React
</p>

## Objetivo 

O objetivo do projeto é facilitar a visualização de lojas e seus produtos no mercado, oferecendo assim um ambiente simples de usar aos usuarios, tanto para quem deseja preucurar produtos tanto para quem deseja mostrar suas lojas.

## Funcionalidades

- Realizar login na plataforma
- Alterar sua senha de forma segura
- Cadastrar um novo perfil com dados personalizados
- Adicionar uma foto ao seu perfil
- Visualizar seus próprios dados e avaliações no perfil
- Adicionar lojas e produtos
- Visualizar as lojas e produtos
- Comentar nos produtos
- Visualizar e excluir seus próprios comentários
- Excluir suas própias lojas e produtos
- Excluir completamente seu perfil da plataforma

## Como Executar
   
1. Clone o repositório:
  ```bash
  git clone https://github.com/seu-usuario/jacare-auth-app.git
  cd jacare-auth-app
  ```

2. Instale as dependências:
  ```bash
  npm install
  ```

3. Configure o banco de dados:
  ```bash
  #Crie o arquivo .env com o seguinte conteúdo:
  DATABASE_URL="file:./dev.db"   (ou a URL de sua instância PostgreSQL/MySQL)
  ```

4. Execute a migração inicial
  ```bash
    npx prisma migrate dev --name init
  ```

5. Rode o servidor de desenvolvimento
  ```bash
    npm run dev
  ```

6. Acesse no navegador
  ```bash
    http://localhost:3000 
  ```

## Créditos

<table align="center">
  <tr>
    <td align="center">
      <a href="https://github.com/gabiiverissimo-sys">
        <img src="https://avatars.githubusercontent.com/u/239393174?s=64&v=4" width="100px" alt="Gabriella"/>
        <br />
        <sub><b>Gabriella </b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/giovannabrito19">
        <img src="https://avatars.githubusercontent.com/u/175221432?v=4" width="100px" alt="Giovanna Brito"/>
        <br />
        <sub><b>Giovana brito </b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/H3ytt0r62">
        <img src="https://avatars.githubusercontent.com/u/205556312?v=4" width="100px" alt="Heyttor Augusto"/>
        <br />
        <sub><b>Heyttor Augusto</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/pedrolrm">
        <img src="https://avatars.githubusercontent.com/u/141690806?v=4" width="100px" alt="Pedro Luca"/>
        <br />
        <sub><b> Pedro Luca</b></sub>
      </a>
    </td>
   <tr>
</table>
