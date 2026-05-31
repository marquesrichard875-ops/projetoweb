# Artisanal Sweets - Site de Confeitaria Artesanal

Um site elegante e responsivo para uma confeitaria artesanal, desenvolvido em **HTML e CSS puro** (sem frameworks).

## 📁 Estrutura de Arquivos

```
artisanal-sweets-html-css/
├── index.html          # Página inicial (Home)
├── produtos.html       # Catálogo de produtos com filtros
├── sobre.html          # Sobre a marca e história
├── contato.html        # Formulário de contato
├── styles.css          # Estilos globais
└── README.md           # Este arquivo
```

## 🎨 Características

- **Design Responsivo**: Funciona perfeitamente em celulares, tablets e computadores
- **Paleta de Cores Elegante**: Tons quentes (marrom, bege) que remetem à confeitaria
- **Navegação Intuitiva**: Menu sticky que acompanha o usuário
- **Componentes Interativos**: 
  - Filtros de produtos funcionais
  - Formulário de contato
  - Links diretos para WhatsApp
- **Otimizado para Performance**: Sem dependências externas
- **Acessibilidade**: Semântica HTML correta

## 🚀 Como Usar

### Opção 1: Abrir Localmente
1. Baixe os arquivos
2. Extraia em uma pasta
3. Abra `index.html` no navegador

### Opção 2: Usar um Servidor Local (Recomendado)

**Com Python 3:**
```bash
cd artisanal-sweets-html-css
python -m http.server 8000
```
Depois acesse: `http://localhost:8000`

**Com Node.js (http-server):**
```bash
npm install -g http-server
cd artisanal-sweets-html-css
http-server
```

### Opção 3: Fazer Upload para um Servidor Web
Envie todos os arquivos para seu servidor de hospedagem (ex: Netlify, Vercel, GitHub Pages, etc.)

## 📝 Páginas

### 1. **Home (index.html)**
- Hero section com chamada para ação
- Grid de produtos em destaque
- Seção de features
- Testimonial
- Newsletter signup

### 2. **Produtos (produtos.html)**
- Catálogo completo de produtos
- Filtros por categoria (Brigadeiros, Bolos, Doces Especiais)
- Cards com descrição, preço e botão de pedido
- Links diretos para WhatsApp

### 3. **Sobre (sobre.html)**
- História da marca
- Valores e filosofia
- Estatísticas (17+ anos, 100% natural)
- Citação do fundador

### 4. **Contato (contato.html)**
- Informações de contato (WhatsApp, Instagram)
- Mapa de área de atendimento
- Formulário de mensagem
- Testimonial

## 🎯 Customização

### Alterar Cores
Edite as variáveis CSS no topo do arquivo `styles.css`:

```css
:root {
  --primary-color: #6B4423;      /* Cor principal */
  --primary-dark: #5A3A1F;       /* Cor escura */
  --primary-light: #D4B5A0;      /* Cor clara */
  --accent-light: #F5E6D3;       /* Cor de destaque */
  /* ... outras cores */
}
```

### Alterar Textos
Abra cada arquivo `.html` e procure pelos textos que deseja modificar. Os textos estão claramente marcados em comentários HTML.

### Alterar Links do WhatsApp
Procure por `https://wa.me/5511999998888` nos arquivos HTML e substitua pelo seu número de WhatsApp.

### Adicionar Novos Produtos
No arquivo `produtos.html`, copie um bloco de `<div class="card">` e modifique:
- `data-categoria`: categoria do produto
- Emoji/ícone
- Título, descrição e preço
- Link do WhatsApp

## 📱 Responsividade

O site é totalmente responsivo com breakpoints em:
- **Desktop**: 1280px (max-width)
- **Tablet**: 768px
- **Mobile**: 480px

## 🔗 Links Importantes

- **WhatsApp**: Atualize o número em todos os links
- **Instagram**: @artisanalsweets (atualize conforme necessário)
- **Email**: Adicione um formulário de backend se necessário

## 💡 Dicas de Manutenção

1. **Backup Regular**: Faça backup dos arquivos regularmente
2. **Testes em Navegadores**: Teste em Chrome, Firefox, Safari e Edge
3. **Otimização de Imagens**: Se adicionar imagens, comprima-as antes
4. **SEO**: Atualize as meta tags no `<head>` de cada página
5. **Analytics**: Adicione Google Analytics se desejar rastrear visitantes

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica
- **CSS3**: Estilos modernos com Grid e Flexbox
- **JavaScript Vanilla**: Interatividade (filtros, formulários)
- **Sem dependências externas**: Tudo funciona offline

## 📄 Licença

Este projeto é livre para uso pessoal e comercial.

## 📞 Suporte

Para dúvidas ou sugestões sobre o site, entre em contato via WhatsApp ou Instagram.

---

**Desenvolvido com ❤️ para Artisanal Sweets**
