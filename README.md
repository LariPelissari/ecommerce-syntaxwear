# 👟 SintaxWear - Tênis & Sneakers Online

> Uma landing page moderna, elegante e totalmente responsiva para uma loja conceitual de calçados e sneakers urbanos.

---

## 📌 Sobre o Projeto

O **SintaxWear** é um projeto de e-commerce front-end desenvolvido com foco na aplicação prática de **HTML5 Semântico** e **CSS3 Avançado** (Flexbox, CSS Grid e Design Responsivo).

A proposta da página é apresentar uma experiência imersiva para o usuário, destacando lançamentos de tênis e sneakers, coleções exclusivas e categorias temáticas, mantendo uma navegação fluida tanto no computador quanto em dispositivos móveis (smartphones e tablets).

Projeto desenvolvido com muito carinho durante a jornada de estudos no **DevQuest**.

---

## 🚀 Tecnologias Utilizadas

Este projeto foi construído utilizando tecnologias puras da web (sem uso de frameworks pesados), consolidando os fundamentos do desenvolvimento front-end:

- ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) **HTML5 Semântico**: Estruturação acessível e organizada com tags como `<header>`, `<main>`, `<nav>`, `<section>` e `<footer>`.
- ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white) **CSS3 Moderno**:
  - **CSS Variables**: Gerenciamento de variáveis globais (fontes e propriedades reutilizáveis).
  - **Flexbox**: Alinhamentos dinâmicos de cabeçalho, botões, categorias e rodapé.
  - **CSS Grid (`grid-template-areas`)**: Construção de um mosaico elegante de exibição de produtos.
  - **Design Responsivo (@media queries)**: Adaptação visual para telas grandes, tablets e smartphones.
  - **Menu Mobile sem JavaScript**: Implementação da técnica do "Checkbox Hack" com `:checked` para abrir/fechar o menu mobile de forma leve.
  - **Modern CSS Reset**: Base de normalização de estilos baseada nas melhores práticas de Andy Bell para acessibilidade e consistência entre navegadores.
- 🔤 **Google Fonts**: Tipografia moderna utilizando as fontes *Ubuntu*, *Roboto Mono* e *Cinzel Decorative*.

---

## 🎨 Seções da Página

1. **Header Fixo (Navegação Superior)**:
   - Logotipo da SintaxWear.
   - Menu com categorias principais (*Masculino*, *Feminino*, *Outlet*).
   - Atalhos rápidos (*Nossas lojas*, *Sobre*, Minha Conta, Ajuda e Carrinho).
   - Menu hambúrguer interativo adaptado para telas menores.

2. **Hero Section (Banner Principal)**:
   - Destaque para o modelo exclusivo **Krypton One** com slogan de impacto.
   - Botões de chamada para ação (*Call To Action* - CTAs): "Ver modelos" e "Comprar".
   - Imagem de fundo inteligente que se adapta entre desktop e mobile.

3. **Categorias de Calçados**:
   - Cards visuais com efeitos de overlay escuro e botões estilizados:
     - *Casual*
     - *Esporte*
     - *Moderno*
     - *Futurista*

4. **Grid de Produtos em Destaque**:
   - Layout estilo mosaico (*Bento Grid*) com diferentes dimensões de fotos de calçados e modelos.
   - Destaque principal com botões de acesso direto às coleções Feminina e Masculina.

5. **Rodapé (Footer)**:
   - Formulário para inscrição em newsletter por e-mail.
   - Links com ícones para redes sociais (Instagram, WhatsApp, TikTok e Facebook).
   - Mapa de navegação completo categorizado.
   - Linha de direitos autorais e copyright.

---

## 📁 Estrutura de Pastas e Arquivos

O projeto segue o padrão de **CSS modular**, onde cada parte do site tem seu próprio arquivo de estilo dedicado, facilitando a leitura, manutenção e evolução do código:

```plaintext
ecommerce-syntaxwear/
│
├── index.html                   # Página principal do site
├── README.md                    # Documentação do projeto
│
├── css/                         # Folhas de estilo (CSS)
│   ├── reset.css                # Normalização de estilos padrão dos navegadores
│   ├── variables.css            # Importação de fontes e variáveis globais (:root)
│   ├── base.css                 # Estilos globais (corpo da página, botões e espaçamentos gerais)
│   └── components/              # Estilos específicos de cada seção do site
│       ├── header.css           # Cabeçalho, navegação e menu mobile
│       ├── hero.css             # Banner principal de destaque
│       ├── product-category.css # Cards das categorias de calçados
│       ├── product-grid.css     # Mosaico com CSS Grid para exibição dos produtos
│       └── footer.css           # Rodapé, newsletter e redes sociais
│
└── images/                      # Imagens e ícones utilizados
    ├── banners/                 # Banners principais (versão desktop e mobile)
    ├── favicons/                # Ícones de favoritos para aba do navegador
    ├── icons/                   # Ícones em formato vetorial SVG (carrinho, usuário, redes sociais)
    ├── logo/                    # Identidade visual da marca (Logo em SVG e PNG)
    └── produtos/                # Imagens dos tênis e modelos para cards e mosaico
```

---

## 💻 Como Visualizar e Rodar o Projeto

Como este projeto foi desenvolvido com tecnologias nativas da web, você não precisa instalar nenhuma ferramenta pesada para executá-lo!

### Pré-requisitos
- Um navegador de internet moderno (ex: Google Chrome, Mozilla Firefox, Microsoft Edge ou Safari).
- (Opcional, mas recomendado) O editor de código **Visual Studio Code (VS Code)**.

### Passo a Passo

1. **Baixar ou clonar o projeto**:
   ```bash
   git clone https://github.com/LariPelissari/ecommerce-syntaxwear.git
   ```

2. **Acessar a pasta do projeto**:
   ```bash
   cd ecommerce-syntaxwear
   ```

3. **Abrir a página no navegador**:
   - **Opção 1**: Dê um duplo clique no arquivo `index.html` e ele abrirá diretamente no seu navegador padrão.
   - **Opção 2 (Recomendada via VS Code)**:
     - Abra a pasta do projeto no VS Code.
     - Se tiver a extensão **Live Server** instalada, clique com o botão direito no arquivo `index.html` e selecione **"Open with Live Server"**.

---

## 💡 Principais Aprendizados e Conceitos Praticados

Durante a criação deste projeto, foram desenvolvidas e praticadas habilidades fundamentais:

- **Organização Modular de CSS**: Divisão do código em arquivos menores por componente, evitando arquivos gigantes e desorganizados.
- **Técnica de Menu Hambúrguer com CSS Puro**: Criação de um menu mobile funcional utilizando apenas `<input type="checkbox">` e o seletor `:checked`, sem necessidade de JavaScript.
- **Layouts Avançados com CSS Grid**: Uso de `grid-template-areas` para posicionar elementos de forma limpa e intuitiva como num tabuleiro.
- **Harmonia de Espaçamentos e Tipografia**: Uso de unidades relativas como `rem` para melhor acessibilidade e escalabilidade visual.
- **Acessibilidade e Boas Práticas**: Inclusão de atributos `aria-label`, textos alternativos (`alt`) em imagens e contrastes adequados.

---

## 👩‍💻 Autora

Desenvolvido por **Larissa Pelissari** 💜  
Estudante de desenvolvimento web apaixonada por tecnologia e design.

- **GitHub**: [@LariPelissari](https://github.com/LariPelissari)

---

✨ *Gostou do projeto? Deixe uma estrelinha (⭐) no repositório!*