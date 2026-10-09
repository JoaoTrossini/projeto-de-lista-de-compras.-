# 🛒 Lista de Compras

## Sobre o projeto

O Lista de Compras é um aplicativo desenvolvido com React Native, Expo e TypeScript. Seu objetivo é facilitar a organização dos produtos que precisam ser comprados.

## Funcionalidades

* Visualização dos produtos da lista.
* Cadastro de produtos com nome e quantidade.
* Remoção de produtos.
* Atualização automática da quantidade de itens.
* Interface simples e organizada.
* Mensagem exibida quando a lista está vazia.

## Tecnologias utilizadas

* React Native
* Expo
* TypeScript
* JavaScript
* CSS-in-JS com StyleSheet

## Como executar o projeto

### Pré-requisitos

* Node.js instalado.
* npm instalado.

### Passos

1. Abra o terminal na pasta do projeto.

2. Instale as dependências:

   ```bash
   npm install
   ```

3. Inicie o aplicativo no navegador:

   ```bash
   npx expo start --web
   ```

4. Aguarde o Expo iniciar e abra o endereço exibido no terminal, caso o navegador não abra automaticamente.

## Estrutura do projeto

```text
lista-de-compras/
├── components/
│   ├── Cabecalho.tsx
│   ├── FormularioItem.tsx
│   ├── ItemCompra.tsx
│   └── ListaCompras.tsx
├── App.tsx
├── index.tsx
├── index.ts
├── types.ts
├── package.json
└── README.md
```

## Observação

Os produtos são armazenados temporariamente na memória do aplicativo. O armazenamento permanente não está implementado nesta versão.

## Autor

João Trossini
