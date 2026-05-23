# Giulia Brandes — Landing Page Introdução Alimentar

## 📁 Estrutura
```
projeto-giulia/
├── public/
│   ├── index.html
│   ├── logo.png        ← ⚠️ COLOQUE A LOGO AQUI (PNG com fundo transparente)
│   └── giulia.jpg      ← ⚠️ COLOQUE A FOTO DA GIULIA AQUI
├── src/
│   ├── index.js
│   ├── App.js
│   └── LandingPage.jsx
├── package.json
├── vercel.json
└── .gitignore
```

## 🚀 Como rodar localmente
```bash
npm install
npm start
```

## 🌐 Como publicar no Vercel

1. Coloque a imagem da logo em `public/logo.png`
2. Suba para o GitHub: `git init && git add . && git commit -m "first commit" && git push`
3. Acesse vercel.com → New Project → importe o repositório
4. Framework: **Create React App** (detectado automaticamente)
5. Clique em **Deploy**

## ✏️ O que personalizar antes de publicar

- [ ] **`public/logo.png`** → substitua pelo arquivo da logo real
- [ ] **Link de compra** → procure `SEU_LINK_HOTMART_AQUI` em `LandingPage.jsx` e substitua
- [ ] **Depoimentos** → substitua pelos reais (busque por `ini:"AM"`, `ini:"CF"` etc.)
- [ ] **Foto da nutricionista** → substituia o emoji 👩‍⚕️ por uma `<img>` real

## 🎨 Cores da marca
- Azul marinho: `#253C7C`
- Azul claro: `#85ACDC`  
- Amarelo: `#F9C035`
