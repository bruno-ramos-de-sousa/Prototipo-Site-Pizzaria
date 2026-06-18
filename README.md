<div align="center">

# 🍕 Pizzaria Irare — Protótipo de Site

**Protótipo de sistema web para pedidos online de uma pizzaria artesanal.**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)

🔗 **[Ver protótipo ao vivo](https://bruno-ramos-de-sousa.github.io/Prototipo-Site-Pizzaria/)**

</div>

---

## 📖 Sobre o Projeto

A **Pizzaria Irare** é um protótipo de site para pedidos online, desenvolvido como projeto pessoal de aprendizado em desenvolvimento web front-end. O objetivo é simular um sistema real de uma pizzaria artesanal — da vitrine do cardápio ao fluxo de cadastro e login do usuário — aplicando boas práticas de HTML semântico, CSS responsivo e organização de código.

> _"Irare: Onde o sabor encontra o coração."_

O projeto é continuamente aprimorado com novas funcionalidades e melhorias de design ao longo do tempo.

---

## ✨ Funcionalidades Atuais

- 🏠 **Página inicial** com banner de promoções e acesso rápido ao cardápio
- 🍕 **Cardápio interativo** com cards de produtos, preços e botão de adicionar ao carrinho
- 🔐 **Fluxo de autenticação** com páginas de Login e Cadastro de usuário
- 🛡️ **Área administrativa** com login separado do sistema (gestor/funcionário)
- ℹ️ **Página Sobre** com a história e proposta da marca Irare
- 📱 **Design responsivo** — adaptado para 4 tamanhos de tela (desktop → mobile)
- 🔍 **Barra de pesquisa** e ícone de carrinho de compras na navegação

---

## 🗂️ Estrutura do Projeto

```
Prototipo-Site-Pizzaria/
│
├── index.html                  ← Página inicial (Home)
│
├── components/
│   ├── cardapio.html           ← Cardápio com os produtos
│   ├── login.html              ← Login do cliente
│   ├── cadastro.html           ← Cadastro de novo cliente
│   ├── loginSistema.html       ← Login da área administrativa
│   └── sobre.html              ← Página "Sobre a Irare"
│
├── css/
│   └── style.css               ← Folha de estilos global (~940 linhas)
│
├── js/
│   └── script.js               ← JavaScript (em desenvolvimento)
│
└── img/                        ← Assets visuais do projeto
    ├── icon.png                ← Logo da Irare
    ├── pizza1.png / pizza2.png ← Fotos dos produtos
    ├── pizzaFundo.png          ← Imagem decorativa do hero
    ├── loja.png                ← Imagem da fachada da loja
    ├── servidor.png            ← Ícone da área administrativa
    ├── shoppingCart.png        ← Ícone do carrinho
    ├── user.png                ← Avatar do usuário
    └── ...                     ← Demais ícones e imagens de UI
```

---

## 📄 Páginas

### Home (`index.html`)

Página principal do site. Exibe o logotipo, barra de navegação completa com busca, botões de **Entrar** e **Criar Conta**, acesso ao carrinho, seção de **Promoções quentes** (2 pizzas por R$ 69,99) e botão de destaque para o cardápio. Inclui rodapé com telefone e e-mail de contato.

---

### Cardápio (`components/cardapio.html`)

Galeria de 7 produtos em cards estruturados com:

- Foto do produto
- Nome e descrição
- Preço (de R$ 29,90 a R$ 36,90)
- Botão de adição ao carrinho

---

### Login do Cliente (`components/login.html`)

Formulário de acesso com:

- Campo de e-mail
- Campo de senha
- Opção "Lembrar-me"
- Link de redirecionamento para cadastro

---

### Cadastro (`components/cadastro.html`)

Formulário de criação de conta com:

- Nome, e-mail, senha e confirmação de senha
- Checkbox de aceite dos termos de uso
- Link de redirecionamento para login

---

### Login do Sistema (`components/loginSistema.html`)

Tela de acesso exclusiva para funcionários e gestores da pizzaria, com layout diferenciado (imagem de servidor no lugar da fachada da loja).

---

### Sobre (`components/sobre.html`)

Página institucional da marca Irare contendo:

- Proposta e valores da pizzaria
- Diferenciais (ingredientes premium, fermentação lenta, ambiente acolhedor)
- Compromisso com a excelência

---

## 🎨 Design

| Elemento           | Valor                                     |
| ------------------ | ----------------------------------------- |
| **Tipografia**     | Poppins (Google Fonts)                    |
| **Cor primária**   | Vermelho escuro `#7a0000`                 |
| **Cor secundária** | Laranja vibrante `#ff751f`                |
| **Cor de fundo**   | Creme `#faf9f6`                           |
| **Cor de texto**   | Quase branco `#f4f4f4` / Escuro `#252526` |

### Responsividade

O layout foi desenvolvido com abordagem _desktop-first_ e adaptado para os seguintes breakpoints:

| Breakpoint | Dispositivo alvo           |
| ---------- | -------------------------- |
| `1440px`   | Monitores grandes          |
| `1024px`   | Laptops e tablets deitados |
| `768px`    | Tablets em portrait        |
| `425px`    | Smartphones                |

---

## Como Executar Localmente

Nenhuma dependência ou build necessário — é um projeto estático puro.

```bash
# 1. Clone o repositório
git clone https://github.com/bruno-ramos-de-sousa/Prototipo-Site-Pizzaria.git

# 2. Acesse a pasta do projeto
cd Prototipo-Site-Pizzaria

# 3. Abra o arquivo principal no navegador
# Clique duas vezes em index.html
# — ou —
# Use a extensão Live Server no VS Code (recomendado)
```

> **Recomendação:** Abrir com a extensão **Live Server** do VS Code garante hot-reload e evita problemas com caminhos relativos de imagens.

---

## Próximas Funcionalidades

- [ ] Funcionalidade real do carrinho de compras com JavaScript
- [ ] Autenticação de usuário com backend
- [ ] Sistema de pedidos com rastreamento
- [ ] Painel administrativo para gestão do cardápio
- [ ] Integração com API de pagamentos
- [ ] Animações e microinterações com CSS/JS

---

## Autor

**Bruno Ramos de Sousa**
📧 brunoramosdsousa0@gmail.com
🔗 [github.com/bruno-ramos-de-sousa](https://github.com/bruno-ramos-de-sousa)

---

<div align="center">
  <small>© 2026 Pizzaria Irare. Todos os direitos reservados.</small>
</div>
