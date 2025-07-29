
# ⚛️ Projeto React com Vite + Tailwind CSS

Este projeto foi desenvolvido durante um curso introdutório de **React**, utilizando as ferramentas modernas da stack front-end como **Vite** e **Tailwind CSS**. O repositório tem fins exclusivamente didáticos e visa consolidar os conceitos fundamentais do React na prática.

---

## 🚀 Tecnologias Utilizadas

- React 18
- Vite
- Tailwind CSS
- PostCSS
- ESLint

---


# React + Vite

Este modelo fornece uma configuração mínima para que o React funcione no Vite com HMR e algumas regras ESLint.

Atualmente, dois plugins oficiais estão disponíveis:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) usa [Babel](https://babeljs.io/) para atualização rápida

- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) usa [SWC](https://swc.rs/) para atualização rápida

---

## 📦 Instalação e Execução

> Pré-requisitos: Node.js e npm instalados

```
# Clone o repositório
git clone https://github.com/usuario/curso-de-react-yt.git

# Acesse a pasta do projeto
cd curso-de-react-yt

# Instale as dependências
npm install

# Rode o servidor de desenvolvimento
npm run dev
```
---

## 📁 Estrutura do Projeto React

```
curso-de-react-yt-main
├── .gitignore
├── eslint.config.js
├── index.html
├── package-lock.json
├── package.json
├── postcss.config.js
├── public
│   └── vite.svg
├── README.md
├── src
│   ├── App.css
│   ├── App.jsx
│   ├── assets
│   │   └── react.svg
│   ├── components
│   │   ├── AddTask.jsx
│   │   ├── Button.jsx
│   │   ├── Input.jsx
│   │   ├── Tasks.jsx
│   │   └── Title.jsx
│   ├── index.css
│   ├── main.jsx
│   └── pages
│       └── TaskPage.jsx
├── tailwind.config.js
└── vite.config.js

```

---

## 🧠 Tecnologias Detectadas
* React (JSX)

* Vite (como bundler)

* Tailwind CSS

* ESLint

* PostCSS

---

## 📦 Dependências do Projeto

```
"dependencies": {
  "react": "^18.2.0",
  "react-dom": "^18.2.0"
},
"devDependencies": {
  "@vitejs/plugin-react": "^4.0.0",
  "autoprefixer": "^10.4.17",
  "eslint": "^8.45.0",
  "eslint-plugin-react": "^7.32.2",
  "postcss": "^8.4.31",
  "tailwindcss": "^3.3.3",
  "vite": "^4.4.0"
}

```

---

## ✍️ Comentários no Código

```
// Componente principal da aplicação
function App() {
  return (
    <div className="text-center mt-10">
      <h1 className="text-4xl font-bold text-blue-500">
        Olá, React com Vite e Tailwind!
      </h1>
    </div>
  );
}

export default App;

```
---

```
// main.jsx - ponto de entrada
import React from 'react'
import ReactDOM from 'react-dom/client'
import App from './App.jsx'
import './index.css'

ReactDOM.createRoot(document.getElementById('root')).render(
  <React.StrictMode>
    <App />
  </React.StrictMode>,
)

```
---

## 📘 O Que Foi Aprendido
* Criar projetos com Vite

* Configurar Tailwind CSS em um ambiente React

* Criar e renderizar componentes

* Utilizar JSX e estilização condicional

* Organizar estrutura de pastas

* Rodar o projeto em ambiente de desenvolvimento local
---
## 📌 Notas Finais
Este repositório não representa um projeto completo para produção. Foi feito com fins didáticos como parte de um curso introdutório ao React e pode servir como base para projetos mais avançados no futuro.
---
## 🧠 Créditos
Curso baseado nas aulas do canal [Dicas Para Devs](https://www.youtube.com/@dicasparadevs).

 