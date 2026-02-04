# 🚀 Portfólio Web - Felipe Andrade

Portfólio pessoal moderno e responsivo criado com HTML5, CSS3 e JavaScript puro.

## ✨ Características

- ✅ Design moderno e profissional
- ✅ Totalmente responsivo (mobile, tablet, desktop)
- ✅ Animações suaves e efeitos interativos
- ✅ Efeito de digitação automática
- ✅ Navegação suave entre seções
- ✅ Barras de progresso de habilidades animadas
- ✅ Cards de projetos com hover effects
- ✅ Formulário de contato funcional
- ✅ Tema dark moderno (inspirado em terminal de código)
- ✅ 100% customizável
- ✅ SEO otimizado
- ✅ Performance otimizada

## 📁 Estrutura de Arquivos

```
portfolio/
│
├── index.html          # Estrutura HTML principal
├── styles.css          # Estilos CSS
├── script.js           # JavaScript para interatividade
└── README.md          # Este arquivo
```

## 🎨 Personalização

### 1. Informações Pessoais

Abra o arquivo `index.html` e substitua:

- **Seu nome** (linha ~45): `Felipe Andrade`
- **GitHub** (linha ~59): `https://github.com/seu-usuario`
- **LinkedIn** (linha ~66): `https://linkedin.com/in/seu-perfil`
- **Email** (linha ~73): `seu.email@gmail.com`

### 2. Seção Hero (Apresentação)

No arquivo `index.html`, seção `<section id="home">`:

- Edite a descrição pessoal (linha ~52)
- Personalize o bloco de código no "code window" (linhas ~86-103)

No arquivo `script.js`:

- Personalize os textos do efeito de digitação (linhas 12-18)

### 3. Seção Sobre

No `index.html`, seção `<section id="about">`:

- Reescreva sua biografia (linhas ~130-150)
- Atualize as estatísticas (linhas ~152-162):
  - Número de projetos
  - Tecnologias que domina
  - Commits no GitHub

### 4. Habilidades (Skills)

No `index.html`, seção `<section id="skills">`:

- Ajuste os níveis das barras de progresso alterando `data-progress` (exemplo: linha ~185)
- Adicione ou remova tecnologias nas categorias
- Personalize as soft skills

**Valores de progresso:**
- 90-100%: Avançado/Expert
- 75-89%: Intermediário Avançado
- 60-74%: Intermediário
- 40-59%: Básico/Iniciante

### 5. Projetos

Para cada projeto no `index.html`, seção `<section id="projects">`:

**Substitua:**
- **Imagem do projeto**: URL na tag `<img src="">` (linha ~222)
- **Links**: GitHub e Demo ao vivo (linhas ~227-233)
- **Título**: Nome do projeto (linha ~239)
- **Descrição**: O que o projeto faz (linha ~240)
- **Tecnologias**: Tags das tecnologias usadas (linhas ~244-248)

**Como adicionar novos projetos:**

1. Copie todo o bloco `<div class="project-card">...</div>`
2. Cole antes do fechamento de `<div class="projects-grid">`
3. Personalize as informações

### 6. Adicionar Sua Foto

No `index.html`, linha ~167:

```html
<!-- Substitua isso: -->
<div class="image-placeholder">
    <span>Sua Foto</span>
</div>

<!-- Por isso: -->
<img src="caminho/para/sua/foto.jpg" alt="Felipe Andrade">
```

**Dica:** Use uma foto profissional, de preferência quadrada (1:1).

### 7. Cores do Tema

No `styles.css`, linhas 1-10, você pode alterar as cores:

```css
:root {
    --primary-color: #64ffda;      /* Verde água - cor principal */
    --secondary-color: #0a192f;    /* Azul escuro - fundo */
    --text-primary: #ccd6f6;       /* Texto claro */
    --text-secondary: #8892b0;     /* Texto secundário */
    --accent: #64ffda;             /* Cor de destaque */
}
```

**Sugestões de paletas:**

**Roxo Tech:**
```css
--primary-color: #9d4edd;
--accent: #9d4edd;
```

**Laranja Vibrante:**
```css
--primary-color: #ff6b35;
--accent: #ff6b35;
```

**Azul Clássico:**
```css
--primary-color: #00d4ff;
--accent: #00d4ff;
```

## 📧 Configurar Formulário de Contato

O formulário está pronto, mas precisa ser integrado com um serviço de email.

### Opção 1: EmailJS (Recomendado - Grátis)

1. Cadastre-se em https://www.emailjs.com/
2. Configure um serviço de email
3. Crie um template
4. No `script.js`, descomente e configure as linhas 128-139

### Opção 2: Formspree (Mais Simples)

1. Cadastre-se em https://formspree.io/
2. Crie um form e copie o endpoint
3. No `index.html`, adicione ao `<form>`:
```html
<form action="https://formspree.io/f/SEU_FORM_ID" method="POST">
```

### Opção 3: Netlify Forms (Se hospedar na Netlify)

Adicione `netlify` ao form:
```html
<form name="contact" netlify>
```

## 🌐 Como Publicar

### Opção 1: GitHub Pages (Grátis)

1. Crie um repositório no GitHub
2. Faça upload dos arquivos
3. Vá em Settings > Pages
4. Escolha a branch main
5. Seu site estará em: `https://seu-usuario.github.io/nome-repo`

### Opção 2: Netlify (Grátis - Recomendado)

1. Cadastre-se em https://www.netlify.com/
2. Arraste a pasta do projeto para o Netlify
3. Pronto! Site no ar em segundos
4. Você ganha um domínio `.netlify.app` grátis

### Opção 3: Vercel (Grátis)

1. Cadastre-se em https://vercel.com/
2. Conecte seu repositório GitHub
3. Deploy automático a cada commit

## 📱 Teste de Responsividade

Teste seu portfólio em:

- **Desktop**: Chrome, Firefox, Safari
- **Tablet**: iPad, Android Tablet
- **Mobile**: iPhone, Android

Use o DevTools do navegador (F12) para testar diferentes resoluções.

## ⚡ Performance

O portfólio já está otimizado com:

- ✅ CSS e JS minificados (quando hospedar)
- ✅ Lazy loading de imagens
- ✅ Animações CSS performáticas
- ✅ Código limpo e semântico

## 🎯 Checklist de Personalização

- [ ] Substituir todas as informações pessoais
- [ ] Atualizar links (GitHub, LinkedIn, Email)
- [ ] Adicionar sua foto
- [ ] Personalizar textos do efeito de digitação
- [ ] Reescrever biografia
- [ ] Atualizar estatísticas (projetos, commits)
- [ ] Ajustar níveis das habilidades
- [ ] Adicionar seus projetos reais
- [ ] Trocar imagens placeholder por screenshots reais
- [ ] Configurar formulário de contato
- [ ] Testar em diferentes dispositivos
- [ ] Fazer deploy

## 🆘 Problemas Comuns

**Animações não funcionam:**
- Verifique se o `script.js` está carregando corretamente
- Abra o Console do navegador (F12) e veja se há erros

**Menu mobile não abre:**
- Certifique-se que o JavaScript está habilitado
- Verifique se não há erros no console

**Imagens não aparecem:**
- Verifique se o caminho está correto
- Use URLs completas ou caminhos relativos corretos

**Formulário não envia:**
- Configure um dos serviços de email mencionados acima
- Por padrão, apenas mostra um alerta

## 📚 Recursos Úteis

- **Ícones**: https://heroicons.com/
- **Fontes**: https://fonts.google.com/
- **Imagens**: https://unsplash.com/
- **Paletas de Cores**: https://coolors.co/
- **Animações CSS**: https://animate.style/

## 💡 Dicas Extras

1. **Adicione Google Analytics** para ver quantas pessoas visitam
2. **Configure um domínio customizado** (.com, .dev, etc)
3. **Adicione um blog** para compartilhar conhecimento
4. **Crie uma página de currículo** em PDF para download
5. **Adicione dark/light mode toggle** para acessibilidade

## 🤝 Suporte

Se tiver dúvidas ou problemas:

1. Verifique a seção de Problemas Comuns
2. Leia a documentação do HTML/CSS/JS
3. Use o ChatGPT ou Claude para ajudar a depurar

## 📄 Licença

Este projeto é de código aberto. Sinta-se livre para usar, modificar e compartilhar!

---

**Feito com ❤️ e muito ☕ por Felipe Andrade**

🚀 **Bora codar e fazer seu portfólio brilhar!**
