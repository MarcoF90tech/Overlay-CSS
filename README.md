# 🎨 Layout CSS Modular & Design System (Projeto Universitário)

Este repositório contém o código-fonte de um projeto de layout web desenvolvido em conformidade com as especificações técnicas obrigatórias de [Nome da Disciplina ou Faculdade]. O projeto foca na implementação de um Design System robusto, modularização de CSS e na criação de layouts responsivos utilizando **CSS Grid** e **Flexbox**.

## ✨ Especificações Técnicas Atendidas

O projeto foi estruturado para cumprir rigorosamente os seguintes requisitos:

### 1. Sistema de Design (CSS Custom Properties)

* **Design System Consistente:** Desenvolvido em `css/base/_variables.css`.
* **Paleta de Cores:** Definida com variáveis Primárias, Secundárias e Neutras (mais de 8 cores).
* **Tipografia Hierárquica:** 5 tamanhos de fonte baseados em uma escala modular (`--font-size-h1` a `--font-size-h5`).
* **Sistema de Espaçamento Modular:** Variáveis de espaçamento de 8px a 64px (`--spacing-xs` a `--spacing-xxl`).

### 2. Leiautes Responsivos com Grid e Flexbox

* **Leiaute Principal com CSS Grid:** A estrutura geral (`.container` e `.row`) utiliza `display: grid` (`css/layout/_grid.css`).
* **Utilização de Flexbox:** Componentes internos (Navbar, Cards, Botões) usam `display: flex`.
* **5 Breakpoints Responsivos:** Múltiplas media queries definidas para adaptação em XS, SM, MD, LG e XL (`css/layout/_grid.css`).
* **Sistema de Grid Customizado:** Implementado um sistema de 12 colunas (`.col-1` a `.col-12` e responsivos como `.col-lg-4`).

### 3. Componentes e Navegação

* **Navegação Sofisticada:** Menu principal responsivo com submenu **Dropdown** e navegação mobile com **Menu Hambúrguer** (`css/components/_navbar.css`).
* **Sistema de Cards:** Componentes de cards responsivos com Flexbox interno (`css/components/_cards.css`).
* **Botões com Estados:** Implementação completa dos estados visuais de `hover`, `focus`, `active` e `disabled` (`css/components/_buttons.css`).
* **Formulários Estilizados:** Componentes de formulário com feedback visual (classes `.is-invalid` e `.is-valid`) (`css/components/_forms.css`).
* **Componentes de Feedback:** Alertas de status e estruturas para Toasts e Modals (`css/components/_alerts.css`).
* **Badges e Tags:** Sistema de categorização usando Badges com cores do Design System (`css/components/_badges.css`).

---

## 📂 Estrutura do Projeto

O projeto segue uma arquitetura modular clara para facilitar a manutenção e escalabilidade:
