# Portfolio Designer Gráfico

Um portfólio profissional e moderno para designers gráficos, construído com HTML, Tailwind CSS e JavaScript.

## 🚀 Características

- **Design Responsivo**: Otimizado para desktop, tablet e mobile
- **Performance Otimizada**: Tailwind CSS local com build otimizado
- **Animações Suaves**: Transições e efeitos visuais elegantes
- **SEO Friendly**: Estrutura semântica e meta tags otimizadas
- **Acessibilidade**: Navegação por teclado e leitores de tela

## 🛠️ Tecnologias

- HTML5
- Tailwind CSS 3.4
- JavaScript (Vanilla)
- Express.js (servidor local)
- Remix Icons

## 📦 Instalação

1. **Clone o repositório:**
   ```bash
   git clone <url-do-repositorio>
   cd portfoliodesigner
   ```

2. **Instale as dependências:**
   ```bash
   npm install
   ```

3. **Gere o CSS otimizado:**
   ```bash
   npm run build
   ```

4. **Inicie o servidor de desenvolvimento:**
   ```bash
   npm start
   ```

5. **Acesse o projeto:**
   Abra http://localhost:3000 no seu navegador

## 🔧 Scripts Disponíveis

- `npm start` - Inicia o servidor de desenvolvimento
- `npm run dev` - Alias para npm start
- `npm run build` - Gera o CSS otimizado para produção
- `npm run watch` - Monitora mudanças no CSS e recompila automaticamente

## 📁 Estrutura do Projeto

```
portfoliodesigner/
├── src/
│   └── input.css          # Arquivo CSS de entrada do Tailwind
├── public/
│   └── output.css         # CSS otimizado gerado
├── assets/
│   └── sobre-mim.jpg      # Imagens do projeto
├── index.html             # Página principal
├── server.js              # Servidor Express
├── package.json           # Dependências e scripts
├── tailwind.config.js     # Configuração do Tailwind
├── postcss.config.js      # Configuração do PostCSS
└── README.md              # Este arquivo
```

## 🎨 Personalização

### Cores
As cores principais estão definidas no `tailwind.config.js`:
- **Primary**: #C47E3C (dourado)
- **Secondary**: #1C1C1C (cinza escuro)

### Fontes
- **Inter**: Para textos gerais
- **Playfair Display**: Para títulos
- **Pacifico**: Para o logo

## 📱 Responsividade

O site é totalmente responsivo com breakpoints:
- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🚀 Deploy

Para fazer deploy em produção:

1. Execute o build:
   ```bash
   npm run build
   ```

2. Faça upload dos arquivos:
   - `index.html`
   - `public/output.css`
   - `assets/` (pasta com imagens)

## 📄 Licença

Este projeto está sob a licença ISC.

## 👨‍💻 Autor

Desenvolvido com ❤️ para designers gráficos profissionais. 