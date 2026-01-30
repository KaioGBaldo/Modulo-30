# 🛒 EBAC Sports E-Shop - Redux & Hooks Integration

Um projeto de e-commerce esportivo desenvolvido com **React** e **TypeScript**, focado na implementação de funcionalidades de carrinho de compras e sistema de favoritos. A aplicação utiliza uma arquitetura moderna que combina **Redux** para o estado global do carrinho e **Hooks** para o estado local de favoritos.

---

# 📝 Resumo (Resume)
Neste projeto, explorei a convivência de diferentes fluxos de dados. O carrinho de compras foi gerenciado através do **Redux Toolkit**, permitindo que produtos sejam adicionados de qualquer parte da aplicação. Já a funcionalidade de "favoritar" foi implementada com `useState` e lógica de filtragem dinâmica, demonstrando o domínio sobre manipulação de arrays e imutabilidade no React. A aplicação também consome uma API externa para renderizar a lista de produtos dinamicamente.



## 🚀 Tecnologias e Ferramentas (Tech Stack)

[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Redux](https://img.shields.io/badge/Redux_Toolkit-764ABC?style=for-the-badge&logo=redux&logoColor=white)](https://redux-toolkit.js.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Styled Components](https://img.shields.io/badge/Styled_Components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white)](https://styled-components.com/)

## 📋 Funcionalidades em Destaque
* **Estado Global com Redux:** Centralização da lógica do carrinho de compras, permitindo acesso e modificação do estado de forma previsível e segura.
* **Sistema de Favoritos Dinâmico:** Implementação de lógica de "toggle" (adicionar/remover) usando `find` e `filter`, garantindo que não existam duplicatas na lista de desejos.
* **Tipagem com TypeScript:** Definição rigorosa do tipo `Produto`, garantindo que as propriedades `id`, `nome`, `preco` e `imagem` sejam consistentes em toda a aplicação.
* **Componentização Avançada:** Divisão estratégica entre containers de lógica (`Produtos`) e componentes de exibição (`Header`), utilizando o padrão de *Lifting State Up*.
* **Estilização com GlobalStyle:** Uso de Styled Components para manter um tema visual unificado e responsivo para toda a loja.
* **Fetch de API:** Integração com serviços externos para obtenção da lista de produtos em tempo real.



---

# 👨‍💻 Sobre mim (About Me)
Olá, meu nome é **Kaio**, tenho 22 anos. Como meu foco é o **Back-End com Python**, trabalhar com Redux foi um exercício valioso de arquitetura. No Back-End, lidamos constantemente com o gerenciamento de estados em bancos de dados e sessões; entender como o Front-End espelha esses dados no Redux me permite criar APIs mais eficientes e preparadas para aplicações de grande porte.

### Entre em contato (Contact me)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-000?style=for-the-badge&logo=linkedin&logoColor=764ABC)](https://linkedin.com/in/kaio-grativol-baldo-071a74150/)
[![Instagram](https://img.shields.io/badge/Instagram-000?style=for-the-badge&logo=instagram&logoColor=764ABC)](https://www.instagram.com/kaiull__/)
[![GitHub](https://img.shields.io/badge/Github-000?style=for-the-badge&logo=github&logoColor=764ABC)](https://github.com/SeuUsuarioAqui)

---
*Projeto desenvolvido para consolidar a integração entre Hooks e Redux em aplicações de comércio eletrônico.*
