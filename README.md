# 🚀 Layout CSS Modular & Design System

Este projeto é um desenvolvimento universitário que implementa um **Design System** e um **Layout Responsivo** robusto. O foco é na modularidade do código CSS e no cumprimento de todas as especificações técnicas obrigatórias, utilizando **CSS Grid** para a estrutura e **Flexbox** para os componentes.

## ✨ Especificações Técnicas Obrigatórias (Checklist)

| Requisito | Status | Implementação Chave |
| :--- | :--- | :--- |
| **Design System** (Variáveis) | ✅ | Cores, 5 Níveis de Tipografia, Espaçamento Modular (8px a 64px) em `css/base/_variables.css`. |
| **Layout com CSS Grid** | ✅ | Estrutura principal e o sistema de 12 colunas definido em `css/layout/_grid.css`. |
| **Uso de Flexbox** | ✅ | Componentes internos (Navbar, Cards, Botões) usam `display: flex`. |
| **5+ Breakpoints** | ✅ | Múltiplas media queries definidas em `css/layout/_grid.css` (SM, MD, LG, XL, XXL). |
| **Navegação Sofisticada** | ✅ | Menu Hambúrguer (Mobile) e Submenu Dropdown (Desktop) em `css/components/_navbar.css`. |
| **Botões com Estados** | ✅ | Estilos para `:hover`, `:focus`, `:active` e `:disabled` em `css/components/_buttons.css`. |
| **Formulários c/ Validação** | ✅ | Estilização dos campos e feedback visual de erro/sucesso em `css/components/_forms.css`. |
| **Componentes de Feedback** | ✅ | Estruturas para Alerts, Toasts e Modals usando cores de feedback em `css/components/_alerts.css`. |
| **Badges e Tags** | ✅ | Componentes de categorização usando as cores do Design System em `css/components/_badges.css`. |
| **Estrutura Modular** | ✅ | Código organizado em pastas (`base`, `layout`, `components`, `utilities`) e importado via `css/main.css`. |
