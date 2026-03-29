# 🎯 Sistema de Eventos com Flexbox

Este projeto é uma página web simples desenvolvida com HTML e CSS, com foco no uso do **Flexbox** para organização de layout.

---

## 🚀 Objetivo

O objetivo principal foi aplicar o **Flexbox** para estruturar toda a página, organizando os elementos de forma alinhada, responsiva e visualmente agradável.

---

## 🧠 O que é Flexbox?

O **Flexbox (Flexible Box Layout)** é um modelo de layout do CSS que facilita o alinhamento e a distribuição de elementos dentro de um container, mesmo quando o tamanho dos itens é dinâmico.

---

## 🧩 Onde o Flexbox foi aplicado

### 🔹 Header
- `display: flex`
- `justify-content: space-between`
- `align-items: center`

Utilizado para posicionar o título à esquerda e o menu à direita, com alinhamento vertical.

---

### 🔹 Menu
- `display: flex`
- `gap`

Os links são organizados horizontalmente com espaçamento entre eles.

---

### 🔹 Banner
- `display: flex`
- `flex-direction: column`
- `justify-content: center`
- `align-items: center`

Centraliza o conteúdo tanto horizontal quanto verticalmente.

---

### 🔹 Main (conteúdo principal)
- `display: flex`

Divide a tela em duas partes:
- Filtros (lado esquerdo)
- Lista de eventos (lado direito)

---

### 🔹 Filtros
- `display: flex`
- `flex-direction: column`
- `gap`

Organiza os botões verticalmente com espaçamento.

---

### 🔹 Lista de Eventos
- `display: flex`
- `flex-wrap: wrap`
- `gap`
- `flex: 1`

Permite que os cards:
- fiquem lado a lado
- quebrem linha automaticamente
- ocupem o espaço disponível

---

### 🔹 Cards
- `display: flex`
- `flex-direction: column`

Organiza o conteúdo interno do card.

- `margin-top: auto` no botão:
  - Mantém o botão sempre alinhado na parte inferior

---

### 🔹 Footer
- `display: flex`
- `justify-content: center`
- `align-items: center`

Centraliza o conteúdo no rodapé.

---

## 🎨 Resultado

O uso do Flexbox permitiu criar um layout:
- organizado
- alinhado
- adaptável
- fácil de manter

---

## 🛠 Tecnologias utilizadas

- HTML5
- CSS3 (Flexbox)

---

## 🌐 Acesse o projeto

👉 https://brandim04.github.io/Flexbox/

---

## 👩‍💻 Autora

Projeto desenvolvido por **Larissa Brandim** 💻
