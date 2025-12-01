# Atividade: Landing Page de Oportunidades IFRN com Flexbox

## 📋 Objetivo
Criar uma landing page responsiva utilizando HTML5 e CSS3 com Flexbox, apresentando informações sobre oportunidades de trabalho em projetos de pesquisa e extensão do IFRN (Instituto Federal de Educação, Ciência e Tecnologia do Rio Grande do Norte).

## 🎯 Competências Desenvolvidas
- Criação de layouts responsivos com CSS Flexbox
- Abordagem Mobile-First
- Estruturação semântica de HTML5
- Design de interfaces modernas e acessíveis
- Pesquisa e organização de conteúdo

## ✅ Checklist da Atividade

### 1. Estrutura HTML
- [X] Criar arquivo `index.html` com estrutura básica HTML5
- [X] Utilizar tags semânticas (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`)
- [ ] Adicionar meta tags para responsividade (`viewport`)
- [ ] Incluir meta tags para SEO (description, keywords)
- [ ] Vincular arquivo CSS externo

### 2. Cabeçalho (Header)
- [ ] Criar logo ou título do IFRN
- [ ] Adicionar menu de navegação
- [ ] Implementar Flexbox para alinhar elementos do header
- [ ] Tornar o header fixo ou responsivo

### 3. Seção Hero (Principal)
- [ ] Criar seção de destaque com título principal
- [ ] Adicionar subtítulo ou descrição breve
- [ ] Incluir call-to-action (CTA) principal
- [ ] Aplicar Flexbox para centralizar conteúdo

### 4. Seção de Oportunidades (Cards)
- [ ] Pesquisar pelo menos 3-6 oportunidades reais ou fictícias de projetos IFRN
- [ ] Criar cards para cada oportunidade com:
  - [ ] Título do projeto/oportunidade
  - [ ] Área de atuação (Pesquisa/Extensão)
  - [ ] Breve descrição
  - [ ] Requisitos básicos
  - [ ] Link ou botão "Saiba Mais"
- [ ] Usar Flexbox para layout dos cards
- [ ] Implementar `flex-wrap` para responsividade
- [ ] Aplicar criatividade no design dos cards

### 5. CSS com Flexbox
- [ ] Criar arquivo `oportunidades.css`
- [ ] Definir reset CSS básico ou usar normalize.css
- [ ] Implementar variáveis CSS para cores e espaçamentos
- [ ] Criar classes utilitárias com Flexbox

#### 5.1. Mobile-First (Smartphone - até 768px)
- [ ] Definir estilos base para mobile
- [ ] Cards empilhados verticalmente (flex-direction: column)
- [ ] Menu hambúrguer ou menu vertical
- [ ] Espaçamentos otimizados para telas pequenas
- [ ] Textos com tamanhos legíveis

#### 5.2. Tablet (768px - 1024px)
- [ ] Criar media query para tablets
- [ ] Cards em 2 colunas (flex-basis, flex-grow)
- [ ] Ajustar espaçamentos
- [ ] Menu horizontal se aplicável

#### 5.3. Desktop (acima de 1024px)
- [ ] Criar media query para desktop
- [ ] Cards em 3 ou mais colunas
- [ ] Layout ampliado com max-width para container
- [ ] Hover effects nos cards e botões

### 6. Estilização Avançada
- [ ] Definir paleta de cores profissional
- [ ] Escolher tipografia adequada (Google Fonts recomendado)
- [ ] Adicionar sombras e bordas nos cards
- [ ] Implementar transições CSS (transitions/animations)
- [ ] Adicionar ícones (Font Awesome, Material Icons, etc.)

### 7. Footer
- [ ] Criar rodapé com informações de contato
- [ ] Links para redes sociais do IFRN
- [ ] Informações de copyright
- [ ] Usar Flexbox para organizar elementos

### 8. Acessibilidade e Boas Práticas
- [ ] Adicionar atributos `alt` em imagens
- [ ] Usar contraste adequado de cores
- [ ] Testar navegação por teclado
- [ ] Validar HTML no [W3C Validator](https://validator.w3.org/)
- [ ] Validar CSS no [CSS Validator](https://jigsaw.w3.org/css-validator/)

### 9. Testes e Responsividade
- [ ] Testar em Chrome DevTools (diferentes dispositivos)
- [ ] Verificar em smartphone real
- [ ] Testar em tablet (ou simulador)
- [ ] Verificar em desktop (diferentes resoluções)
- [ ] Ajustar breakpoints conforme necessário

### 10. Documentação
- [ ] Criar arquivo README.md explicando o projeto
- [ ] Documentar fontes de pesquisa das oportunidades
- [ ] Listar tecnologias utilizadas
- [ ] Incluir screenshots ou link para visualização

## 📚 Recursos Úteis

### Flexbox
- [CSS Tricks - A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [Flexbox Froggy](https://flexboxfroggy.com/) - Jogo para aprender Flexbox
- [MDN - Flexbox](https://developer.mozilla.org/pt-BR/docs/Learn/CSS/CSS_layout/Flexbox)

### Pesquisa de Oportunidades IFRN
- [Portal IFRN](https://portal.ifrn.edu.br/)
- [IFRN - Pesquisa](https://portal.ifrn.edu.br/pesquisa)
- [IFRN - Extensão](https://portal.ifrn.edu.br/extensao)
- [Editais IFRN](https://portal.ifrn.edu.br/editais)

### Design e Inspiração
- [Dribbble](https://dribbble.com/) - Inspiração de design
- [Behance](https://www.behance.net/) - Portfólio de designers
- [Awwwards](https://www.awwwards.com/) - Melhores sites

### Ferramentas
- [Google Fonts](https://fonts.google.com/)
- [Font Awesome](https://fontawesome.com/)
- [Coolors](https://coolors.co/) - Gerador de paleta de cores
- [Unsplash](https://unsplash.com/) - Imagens gratuitas

## 💡 Dicas Importantes

1. **Mobile-First é FUNDAMENTAL**: Comece sempre desenvolvendo para smartphones, depois adapte para telas maiores.

2. **Criatividade nos Cards**: Explore diferentes layouts, cores, ícones e efeitos hover. Cada card pode ter um estilo único mantendo consistência.

3. **Pesquisa Real**: Busque informações reais sobre projetos do IFRN. Isso torna o projeto mais significativo e você aprende sobre as oportunidades disponíveis.

4. **Flexbox Properties Essenciais**:
   - `display: flex`
   - `flex-direction`
   - `justify-content`
   - `align-items`
   - `flex-wrap`
   - `gap`
   - `flex-basis`, `flex-grow`, `flex-shrink`

5. **Teste Constantemente**: Abra o DevTools e teste em diferentes tamanhos de tela enquanto desenvolve.

## 📦 Entrega

Organize seus arquivos da seguinte forma:
```
projeto/
├── index.html
├── css/
│   └── oportunidades.css
├── images/
│   └── (suas imagens)
├── README.md
└── ATIVIDADE.md (este arquivo)
```

## 🎓 Critérios de Avaliação

- **Responsividade (30%)**: Layout funcional em mobile, tablet e desktop
- **Uso de Flexbox (25%)**: Aplicação correta das propriedades Flexbox
- **Mobile-First (15%)**: Abordagem mobile-first clara no código
- **Criatividade (15%)**: Design atrativo e original dos cards
- **Código Limpo (10%)**: HTML semântico e CSS organizado
- **Documentação (5%)**: README completo e código comentado

## ⏰ Prazo e Forma de Entrega

Apenas commit e push no seu repositório _fork_.
Se desejar, pode vincular a um projeto vercel.

---

**Boa sorte e use sua criatividade! 🚀**
