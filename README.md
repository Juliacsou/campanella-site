# Campanella ProfSupport — Landing Page

Landing page institucional da **Campanella ProfSupport** — Gestão administrativa especializada para professores e escolas de idiomas.

Construída em **HTML5**, **Tailwind CSS** e **JavaScript vanilla**, reproduzindo com máxima fidelidade estética e funcional o projeto original do Base44, sem necessidade de Node.js, compilação ou dependências pesadas.

---

## 🚀 Como visualizar / rodar localmente

Como o projeto é estático:
- Basta abrir o arquivo `index.html` em qualquer navegador (Google Chrome, Firefox, Safari, Edge);
- Ou rodar um servidor local simples:
  ```bash
  python3 -m http.server 3000
  # ou
  npx serve
  ```

---

## 🌐 Como publicar (Hospedagem 100% gratuita)

### Opção 1: GitHub Pages
1. Vá até as configurações deste repositório no GitHub: **Settings > Pages**
2. Em **Source**, selecione `Deploy from a branch`
3. Escolha a branch `main` e a pasta `/ (root)`
4. Clique em **Save**. Em menos de 1 minuto seu site estará no ar gratuitamente com HTTPS!

### Opção 2: Vercel / Netlify
Basta conectar este repositório no dashboard da Vercel ou Netlify e clicar em **Deploy**. Como é um site estático, o deploy é instantâneo.

---

## 📁 Estrutura de Arquivos

```
├── index.html              # Landing page completa com todas as seções, modal e scripts
├── assets/
│   └── images/
│       ├── logo.png        # Logo / Favicon da Campanella ProfSupport
│       └── hero.png        # Imagem principal da seção Hero
└── README.md
```

---

## ✨ Recursos Implementados

- **Design 100% idêntico**: Tipografia (Instrument Serif, Plus Jakarta Sans, Inter), espaçamentos e paleta de cores.
- **Navegação com efeito blur**: Cabeçalho translúcido dinâmico ao rolar a página.
- **Menu mobile responsivo**: Acesso rápido às seções e WhatsApp em qualquer celular.
- **Seção de Planos com evolução**: Cards Start, Growth, Pro (destacado) e Premium com listagem de itens e diferenciais.
- **Comissão por Matrícula**: Seção escura detalhando a dinâmica de comissão e serviços por resultado.
- **Modal de Contato / Proposta**: Formulário interativo que gera e envia automaticamente a mensagem formatada para o WhatsApp comercial `(41) 99164-4723`.
