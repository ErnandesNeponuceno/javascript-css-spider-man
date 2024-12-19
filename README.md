
# 🕷️ Spider-Man Multiverso

Uma página interativa dedicada às três versões do Homem-Aranha apresentadas nos cinemas: **Tobey Maguire**, **Tom Holland**, e **Andrew Garfield**. A aplicação utiliza **HTML**, **CSS**, e **JavaScript** para criar uma experiência visual e dinâmica, permitindo navegar entre os personagens e acessar suas respectivas páginas.

---

## 🛠️ Funcionalidades

- **Carrossel Interativo**:
  - Apresenta os três personagens do Homem-Aranha em um carrossel 3D.
  - Botões de controle para alternar entre os personagens.

- **Animações ao Hover**:
  - Ao passar o mouse sobre um personagem, efeitos de destaque são aplicados:
    - O plano de fundo do card desaparece.
    - A imagem do personagem aumenta de tamanho.
    - Um efeito de sombra é adicionado.

- **Páginas Exclusivas**:
  - Cada personagem tem sua própria página dedicada com imagens e vídeos relacionados aos filmes.

- **JavaScript Dinâmico**:
  - Manipula eventos como `mouseenter` e `mouseleave` para aplicar os efeitos visuais.
  - Controla o movimento do carrossel 3D.

---

## 🎯 Estrutura do Projeto

### **Estrutura de Diretórios**
```plaintext
javascript-css-spider-man/
├── assets/
│   ├── css/
│   │   ├── components/              # Componentes de estilo
│   │   │   ├── _gallery.css
│   │   │   ├── _link-button.css
│   │   │   ├── _navigator.css
│   │   │   ├── _pills.css
│   │   ├── global.css               # Estilos globais
│   │   ├── home-page-styles.css     # Estilo da página inicial
│   │   ├── internal.css             # Estilo das páginas internas
│   │   ├── reset.css                # Reset de CSS
│   ├── images/                      # Imagens utilizadas no projeto
│   ├── videos/                      # Vídeos relacionados aos filmes
│   ├── js/
│   │   └── script.js                # Lógica e interatividade
├── pages/
│   ├── andrew-garfield/             # Páginas do Andrew Garfield
│   │   ├── spiderman1.html
│   │   ├── spiderman2.html
│   ├── tobey-maguire/               # Páginas do Tobey Maguire
│   │   ├── spiderman1.html
│   │   ├── spiderman2.html
│   │   ├── spiderman3.html
│   ├── tom-holland/                 # Páginas do Tom Holland
│   │   ├── spiderman1.html
│   │   ├── spiderman2.html
│   │   ├── spiderman3.html
├── index.html                       # Página principal
```

---

## 💻 Tecnologias Utilizadas

<div style="display: inline_block">
  <img alt="HTML" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
  <img alt="CSS" src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E">
</div>

---

## 🚀 Como Rodar o Projeto?

### **Pré-requisitos**
- Navegador web atualizado.

### **Passos**
1. Clone o repositório:
   ```bash
   git clone https://github.com/ErnandesNeponuceno/javascript-css-spider-man.git
   ```
2. Acesse a pasta do projeto:
   ```bash
   cd javascript-css-spider-man
   ```
3. Abra o arquivo **`index.html`** no navegador.

---

## 🔍 Interatividade com JavaScript

### **Efeitos de Hover**
O JavaScript utiliza os eventos `mouseenter` e `mouseleave` para aplicar efeitos dinâmicos. Ao passar o mouse sobre um card:
- A classe `s-card--hovered` é adicionada, ativando os estilos de destaque no CSS.
- O plano de fundo do card desaparece, e a imagem do personagem aumenta de tamanho.

### **Controle do Carrossel**
A função `selectCarouselItem` permite alternar entre os personagens no carrossel 3D. O botão ativo é destacado, e a rotação do carrossel é ajustada dinamicamente com o CSS `transform`.

---


## ✨ Créditos

- Projeto desenvolvido como exemplo prático para estudo de **interatividade web** disponível em - [DIO](https://web.dio.me) .
- **Imagens e vídeos** pertencem aos respectivos estúdios dos filmes do Homem-Aranha.

---
