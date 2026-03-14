# MyShop - Aplicação E-commerce

Uma aplicação e-commerce moderna e responsiva construída com React e TypeScript. Navegue por produtos, visualize detalhes e gerencie seu carrinho de compras com uma interface limpa e amigável.

## Funcionalidades

- **Catálogo de Produtos**: Navegue por uma coleção curada de produtos com imagens, descrições e preços
- **Carrinho de Compras**: Adicione/remova produtos, gerencie quantidades com Redux para gerenciamento de estado
- **Detalhes do Produto**: Veja informações detalhadas incluindo avaliações e preços
- **Design Responsivo**: Interface amigável para dispositivos móveis construída com React Bootstrap
- **UI Moderna**: Estilização com styled-components para estilos com escopo de componente
- **Gerenciamento de Estado**: Redux Toolkit para gerenciamento previsível de estado
- **Type Safety**: Suporte completo a TypeScript para desenvolvimento type-safe

## Stack de Tecnologia

- **React 18** - Biblioteca de UI
- **TypeScript** - JavaScript type-safe
- **Vite 5** - Ferramenta de build ultra-rápida
- **Redux Toolkit** - Gerenciamento de estado
- **React-Redux** - Bindings React para Redux
- **Styled Components** - Estilização CSS-in-JS
- **React Bootstrap** - Componentes Bootstrap para React
- **React Icons** - Biblioteca de ícones

## Começando

### Pré-requisitos

- Node.js 20+
- pnpm (ou npm/yarn)

### Instalação

1. Clone o repositório:
```bash
git clone <url-do-repositorio>
cd e-commerce
```

2. Instale as dependências:
```bash
pnpm install
```

### Desenvolvimento

Inicie o servidor de desenvolvimento:
```bash
pnpm run dev
```

A aplicação estará disponível em `http://localhost:5000`

### Build

Crie um build para produção:
```bash
pnpm run build
```

Visualize o build de produção:
```bash
pnpm run preview
```

### Lint

Verifique a qualidade do código:
```bash
pnpm run lint
```

## Estrutura do Projeto

```
src/
├── components/
│   ├── card/          - Componente de cartão de produto
│   ├── cart/          - Exibição e gerenciamento do carrinho
│   ├── header/        - Cabeçalho de navegação com menu do usuário
│   └── productsList/  - Layout de grade de produtos
├── redux/
│   ├── cart/          - Slice de carrinho e ações
│   ├── user/          - Estado de autenticação do usuário
│   ├── root-reducer.ts
│   └── store.ts
├── styles/
│   └── GlobalStyles.ts
├── utils/
│   └── dollar-formatter.ts
├── App.tsx
└── main.tsx
```

## Uso

### Adicionando Produtos ao Carrinho

Clique no botão "Adicionar ao Carrinho" em qualquer cartão de produto para adicioná-lo ao seu carrinho de compras.

### Visualizando o Carrinho

Clique no botão "Carrinho" no cabeçalho para visualizar seu carrinho de compras e gerenciar itens.

### Autenticação de Usuário

Clique no botão "Login" para acessar recursos de autenticação do usuário (pronto para integração).

## Scripts Disponíveis

| Comando | Descrição |
|---------|-----------|
| `pnpm run dev` | Inicia o servidor de desenvolvimento |
| `pnpm run build` | Build para produção |
| `pnpm run preview` | Visualiza o build de produção localmente |
| `pnpm run lint` | Executa ESLint para verificar qualidade do código |

## Deploy

Esta é uma implantação de site estático. A aplicação é construída como uma aplicação de página única (SPA) e pode ser implantada em qualquer serviço de hospedagem estática.

**Saída do build**: Diretório `dist/`

**Plataformas recomendadas**: Vercel, Netlify, GitHub Pages, Replit

### Deploy no Replit

O projeto está pré-configurado para implantação no Replit:
1. Faça push do código para o repositório
2. Clique em "Publicar" no dashboard do Replit
3. A aplicação estará disponível em `https://<nome-do-projeto>.replit.dev`

## Suporte de Navegadores

- Chrome (versão mais recente)
- Firefox (versão mais recente)
- Safari (versão mais recente)
- Edge (versão mais recente)

## Licença

Este projeto é de código aberto e está disponível sob a Licença MIT.

## Contribuindo

Contribuições são bem-vindas! Sinta-se livre para enviar issues e pull requests para melhorar a aplicação.

---

**Feito com ❤️ usando React e TypeScript**
