# 🛍️ Beauty Store - Landing Page (Projeto Educacional)

## ✨ Visão Geral

Este projeto é uma **Landing Page** para uma loja de cosméticos e beleza, desenvolvida com o objetivo de aprimorar e demonstrar proficiência nas técnicas fundamentais de desenvolvimento *front-end* puro.

O foco educacional deste repositório é a aplicação prática de:
* **Semântica HTML5**
* **Layout Moderno com CSS3** (Flexbox e Grid)
* **Design Responsivo** (Media Queries)
* **Manipulação Básica do DOM** (Menu Hamburger)

## 🎯 Tecnologias Utilizadas

| Categoria | Tecnologia | Conceitos Aplicados |
| :--- | :--- | :--- |
| **Estrutura** | HTML5 | Semântica, Acessibilidade (ARIA) |
| **Estilização** | CSS3 | Variáveis, Transições, Box Shadow |
| **Layout** | Flexbox & Grid | Header Sticky, Grid de Produtos, Alinhamento |
| **Interatividade** | JavaScript (Vanilla) | Menu Hamburger responsivo (Toggle Class) |

## 🖼️ Resultado Visual

Abaixo, você pode ver a estrutura da página inicial com o Header, a seção Hero e o início da seção de Produtos em uma tela com grande resolução.

<img width="1200" height="800" alt="image" src="https://github.com/user-attachments/assets/7a3dfac8-0902-4588-910d-77758db1bac1" />

Página inicial em dispositivos móveis:

<img width="481" height="876" alt="image" src="https://github.com/user-attachments/assets/0518d51c-f0a1-4e40-be93-10dc25994c84" />


## 💡 Lições Aprendidas e Conceitos Aplicados

### 1. HTML e Acessibilidade

* Uso da tag `<nav>` para o menu de navegação e `role` na tag `<button>` para melhorar a acessibilidade do menu (atributo `aria-label="Abrir menu"`).
* Estrutura de *sections* (`<section class="hero">`, `<section class="products">`) para organizar o conteúdo de forma semântica.

### 2. CSS e Layout Avançado

* **Header Fixo (Sticky):** Utilização de `position: sticky` e `z-index` no `header` para mantê-lo visível no topo da página.
* **Menu Responsivo (JavaScript e CSS):** O CSS (`@media (max-width: 768px)`) é usado para ocultar o menu padrão e mostrar o botão Hamburger. O JavaScript gerencia a classe `.active` para exibir/ocultar o menu.
* **CSS Grid para Produtos:** A seção `.product-grid` utiliza `display: grid` com `repeat(auto-fit, minmax(250px, 1fr))` para criar um *layout* de produtos fluido, que se adapta automaticamente à largura da tela.
* **Animação do Menu Hamburger:** Aplicação de `transform: rotate()` no `span` do botão `.menu-toggle` para criar o efeito visual de um "X".

### 3. JavaScript (Menu Toggle)

Foi implementado um JS simples e limpo para gerenciar a classe `.active` no menu e no botão, demonstrando manipulação básica do DOM:

```javascript
  const menuToggle = document.querySelector('.menu-toggle');
  const menu = document.querySelector('.menu');

  menuToggle.addEventListener('click', () => {
    menu.classList.toggle('active');
    menuToggle.classList.toggle('active');
  });
```

## 💻 Como Rodar o Projeto Localmente

Siga estes passos simples para visualizar e testar o projeto em sua máquina local:

1.  **Clone o Repositório:**
    ```bash
    git clone https://github.com/ViniciusModenese/projeto_ecommerce_make.git
    ```
2.  **Navegue até o Diretório:**
    ```bash
    cd projeto_ecommerce_make
    ```
3.  **Abra o Arquivo:**
    * Simplesmente abra o arquivo `index.html` em seu navegador favorito.

## 🤝 Contribuições

Este projeto foi criado com fins de estudo. Sugestões e *feedbacks* são bem-vindos!

## 🔗 Entre em Contato

| | |
| :--- | :--- |
| **GitHub** | [@ViniciusModenese](https://github.com/ViniciusModenese) |
| **LinkedIn** | [Vinicius Modenese Santos](www.linkedin.com/in/viniciusmodenese) |

---
*Desenvolvido com carinho para o aprendizado de Front-end.*
