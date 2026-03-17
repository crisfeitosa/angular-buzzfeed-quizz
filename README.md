# 🎯 BuzzFeed Quizz - Angular

Aplicação de quiz interativo inspirada no estilo BuzzFeed, desenvolvida com **Angular 21**. O usuário responde a uma série de perguntas e descobre se seria um **herói 🦸 ou vilão 🦹**.

## 🛠️ Tecnologias

- 🅰️ Angular 21
- 📘 TypeScript 5.9
- ⚙️ Angular CLI 21.1.3

## ✨ Funcionalidades

- ❓ Quiz com perguntas dinâmicas carregadas de um arquivo JSON
- 🔀 Navegação entre perguntas com seleção de opções
- 🧮 Cálculo automático do resultado com base nas respostas
- 🏆 Exibição do resultado final ao terminar o quiz
- 🚀 Sintaxe moderna do Angular (`@if`, `@for`)

## 📁 Estrutura do Projeto

```
src/
├── app/
│   ├── components/
│   │   └── quizz/          # Componente principal do quiz
│   └── pages/
│       └── home/            # Página inicial
├── assets/
│   ├── data/
│   │   └── quizz_questions.json  # Perguntas e respostas do quiz
│   └── imgs/
│       └── logo.png
└── index.html
```

## 🚀 Como Executar

```bash
# Instalar dependências
npm install

# Iniciar servidor de desenvolvimento
npm start
```

Acesse `http://localhost:4200/` no navegador.

## 📦 Build

```bash
npm run build
```

Os artefatos serão gerados no diretório `dist/`.

## 🧪 Testes

```bash
npm test
```
