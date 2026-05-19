# RAIZA Projetos Paisagísticos

Bem-vindo ao repositório oficial do site da **RAIZA Projetos Paisagísticos**, uma empresa de paisagismo localizada em Capão da Canoa, Rio Grande do Sul.

🔗 **[Acesse o projeto em produção aqui (Live Demo)](https://raizapaisagismov1.vercel.app/)**

---

## 🌿 Sobre o Projeto

Este projeto é uma Landing Page moderna, elegante e focada em SEO (Search Engine Optimization), desenvolvida para apresentar o portfólio, serviços e o processo de trabalho da RAIZA. A interface foi pensada para transmitir luxo, sofisticação e harmonia com a natureza, utilizando tons terrosos, verdes profundos e animações fluidas.

O site foi construído seguindo uma arquitetura 100% estática (frontend-only), garantindo extrema velocidade de carregamento, segurança e facilidade de hospedagem.

## 🛠️ Tecnologias Utilizadas

- **[Astro](https://astro.build/)**: Framework principal configurado para SSG (Static Site Generation), entregando HTML puro com zero JavaScript desnecessário no cliente.
- **[Tailwind CSS v4](https://tailwindcss.com/)**: Estilização utilitária para um design responsivo e customizado através de variáveis CSS.
- **[TypeScript](https://www.typescriptlang.org/)**: Tipagem estática para garantir um código limpo e seguro.

---

## 🚀 Como Executar o Projeto Localmente

Siga os passos abaixo para rodar o projeto no seu ambiente de desenvolvimento:

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/raiza-projeto.git
   ```

2. **Acesse a pasta do projeto:**
   ```bash
   cd raiza-projeto
   ```

3. **Instale as dependências:**
   ```bash
   npm install
   ```

4. **Inicie o servidor de desenvolvimento:**
   ```bash
   npm run dev
   ```
   *O site estará disponível em `http://localhost:4321`.*

---

## 🌐 Como Colocar no Ar (Deploy)

Por ser um site estático, colocar o projeto no ar é muito simples e pode ser feito de forma autônoma em qualquer hospedagem (Hostinger, Vercel, Netlify, GitHub Pages, etc).

### Opção 1: Hospedagem Tradicional (Hostinger, Locaweb, etc)

1. No terminal, execute o comando de build:
   ```bash
   npm run build
   ```
2. O Astro irá gerar uma pasta chamada `dist/` na raiz do projeto. Esta pasta contém todo o HTML, CSS, Imagens e JavaScript minificados.
3. Acesse o Gerenciador de Arquivos do seu painel de hospedagem (como o cPanel da Hostinger).
4. Arraste e solte **todo o conteúdo de dentro da pasta `dist/`** para a sua pasta pública no servidor (geralmente chamada de `public_html`).
5. Pronto! O site já estará no ar.

### Opção 2: Deploy Automático (Vercel ou Netlify)

1. Envie o seu código para um repositório no GitHub.
2. Acesse a [Vercel](https://vercel.com/) ou [Netlify](https://netlify.com/) e crie um novo projeto.
3. Conecte com o seu repositório do GitHub.
4. O serviço irá reconhecer automaticamente que é um projeto Astro e configurará o comando de build (`npm run build`) e o diretório de saída (`dist/`).
5. Clique em Deploy. Toda vez que você fizer um *push* no GitHub, o site atualizará sozinho!

---

## 📐 Estrutura de Componentes

O projeto foi componentizado para facilitar a manutenção, organizados na pasta `src/components`:

- `Header.astro`: Navegação responsiva com logo.
- `Hero.astro`: Seção inicial de impacto.
- `About.astro`: Quem somos e a essência do design.
- `Services.astro`: Grid com as especialidades da empresa.
- `Portfolio.astro`: Carrossel 2D infinito de projetos e Modal de visualização.
- `Process.astro`: Linha do tempo dos processos.
- `CTA.astro`: Chamada para ação focada em captar orçamentos.
- `Footer.astro`: Rodapé com contatos e localização.
