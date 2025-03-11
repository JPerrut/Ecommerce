## 🛒 Plataforma de E-commerce de Tecnologia
Aplicação e-commerce responsável por exibir e gerenciar produtos de tecnologia. A plataforma oferece uma experiência completa ao usuário, permitindo a busca e filtragem de produtos por meio de uma barra de pesquisa, adição de itens ao carrinho, ajuste de quantidades (aumentar ou diminuir), remoção de produtos e finalização da compra com integração de pagamento.

## 🚀 Visão Geral
### Sistema completo para e-commerce de produtos de tecnologia, composto por:

📱 Aplicativo Mobile (Clientes)
<br>
🖥️ Aplicação Web (Clientes e Administradores)
<br>
🚀 Backend (API RESTful)

Este repositório contém o backend, frontend web e mobile do sistema, que permitem que os usuários explorem produtos, adicionem itens ao carrinho e finalizem compras.

## ✨ Características do Projeto
✅ Busca e Filtragem de Produtos – Barra de pesquisa e filtros para encontrar produtos de tecnologia.
<br>
✅ Carrinho de Compras – Adição, remoção e ajuste de quantidades de produtos.
<br>
✅ Finalização de Compra – Integração com sistema de pagamento.
<br>
✅ Interface Responsiva – Design adaptado para dispositivos móveis e desktop.
<br>
✅ Autenticação de Usuários – Cadastro e login para clientes.
<br>
✅ Painel Administrativo – Gerenciamento de produtos e pedidos.

## 🛠️ Tecnologias Utilizadas
### Backend
- **NestJS** – Framework Node.js para construção de APIs escaláveis.

- **Prisma** – ORM moderno para interação com o banco de dados.

- **PostgreSQL** – Banco de dados relacional para armazenamento de dados.

- **TypeScript** – Adiciona tipagem estática ao JavaScript.

### Frontend Web
- **Next.js** – Framework React para construção de aplicações web modernas.

- **Tailwind CSS** – Framework CSS utilitário para estilização rápida e responsiva.

- **React** – Biblioteca JavaScript para construção de interfaces de usuário.

### Mobile
- **React Native** – Framework para desenvolvimento de aplicativos móveis multiplataforma.

- **Expo** – Plataforma que facilita o desenvolvimento e a publicação de aplicativos React Native.

- **React Navigation** – Biblioteca para gerenciamento de navegação entre telas.

## Ferramentas de Desenvolvimento
- **Prisma CLI** – Ferramenta para gerenciamento de migrações e schemas do banco de dados.

- **ESLint** – Linting para garantir a qualidade do código.

- **Jest** – Framework para testes unitários e de integração.

## 🚀 Como Rodar o Projeto Localmente
### Pré-requisitos
- Node.js (versão 18 ou superior)
- npm ou yarn (gerenciadores de pacotes)
- PostgreSQL (banco de dados)

### Backend
1. Acesse a pasta do backend:
    ```bash
    cd apps/backend
    ```
2. Instale as dependências:
    ```bash
    yarn install
    ```
4. Configure o banco de dados no arquivo .env:
    ```bash
    DATABASE_URL="postgresql://usuario:senha@localhost:5432/gam3r.store?schema=public"
    ```
5. Execute as migrações do Prisma:
    ```bash
    npx prisma migrate dev
    ```
6. Inicie o servidor de desenvolvimento:
    ```bash
    yarn run dev
    ```
### Frontend Web
1. Acesse a pasta do frontend:
    ```bash
    cd apps/frontend
    ```
2. Instale as dependências:
    ```bash
    yarn install
    ```
3. Configure a URL da API no arquivo .env:
    ```bash
    NEXT_PUBLIC_API_URL=http://localhost:3005
    ```
4. Inicie o servidor de desenvolvimento:
    ```bash
    yarn run dev
    ```
### Mobile
1. Acesse a pasta do mobile:
    ```bash
    cd apps/mobile
    ```
2. Instale as dependências:
    ```bash
    yarn install
    ```
3. Configure a URL da API no arquivo .env:
    ```bash
    API_URL=http://ipv4:3005
    ```
4. Inicie o servidor de desenvolvimento:
    ```bash
    yarn run dev
    ```
## 🖼️ Telas do Projeto

<table>
<th>Desktop</th>
  <tr>
    <td align="center">
      <img src="public/readme/initialPage.png" width="250"/>
      <br><em>Tela inicial</em>
    </td>
    <td align="center">
      <img src="public/readme/searchField.png" width="250"/>
      <br><em>Tela de Pesquisa</em>
    </td>
    <td align="center">
      <img src="public/readme/shoppingCart.png" width="250"/>
      <br><em>Tela de carrinho</em>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="public/readme/payment.png" width="250"/>
      <br><em>Tela de pagamento</em>
    </td>
    <td align="center">
      <img src="public/readme/purchaseCompleted.png" width="250"/>
      <br><em>Tela de compra finalizada</em>
    </td>
  </tr>
    <th>Mobile</th>
  <tr>
    <td align="center">
      <img src="public/readme/initialPage-mobile.png" width="250"/>
      <br><em>Tela inicial</em>
    </td>
    <td align="center">
      <img src="public/readme/shoppingCart-mobile.png" width="250"/>
      <br><em>Tela de carrinho</em>
    </td>
    </tr>
    <tr>
    <td align="center">
      <img src="public/readme/payment-mobile.png" width="250"/>
      <br><em>Tela Pagamento</em>
    </td>
    <td align="center">
      <img src="public/readme/userPage-mobile.png" width="250"/>
      <br><em>Tela de usuário</em>
    </td>
  </tr>
</table>

## 🤝 Contribuição

### Contribuições são bem-vindas! Siga os passos abaixo:

1. Faça um fork do projeto.
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`).
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`).
4. Faça push para a branch (`git push origin feature/nova-feature`).
5. Abra um Pull Request.

## 📄 Licença
Este projeto está licenciado sob a <a href="https://opensource.org/license/mit">MIT License</a>.

## 📞 Contato
### Se tiver dúvidas ou sugestões, entre em contato:

Nome: João Perrut <br>
Email: joaoperrutc@gmail.com <br>
Linkedin: https://www.linkedin.com/in/perrut/