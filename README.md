# Projeto: Site "Batman: The Dark Knight (2008)"

## 📘 Descrição
Site desenvolvido como primeiro projeto prático da disciplina de Frontend 1.  
O objetivo foi criar um site simples, dividido em três páginas, apresentando informações sobre o filme escolhido (*Batman: The Dark Knight (2008)*), incluindo sinopse, elenco e curiosidades.

---

## 🧱 Estrutura de diretórios
```text
/ (raiz)
├── index.html → Página principal (sobre o filme)
├── elenco.html → Página com elenco e equipe
├── extras.html → Página com trailer e curiosidades
├── css/
│   └── style.css → Folha de estilo principal
└── img/
    ├── poster.jpg → Pôster do filme
    ├── bale.jpg → Christian Bale
    ├── ledger.jpg → Heath Ledger
    ├── caine.jpg → Michael Caine
    └── ... → Demais imagens do elenco
```

## ⚙️ Recursos de HTML utilizados

| Recurso | Descrição | Local de uso |
|----------|------------|--------------|
| `<!DOCTYPE html>` | Declaração do documento HTML5 | Todas as páginas |
| `<header>` | Cabeçalho com título e pôster do filme | Todas as páginas |
| `<nav>` | Menu de navegação entre as páginas | Todas as páginas |
| `<main>` | Conteúdo principal de cada página | index.html / elenco.html / extras.html |
| `<section>` | Separação semântica de blocos de conteúdo | Todas as páginas |
| `<ul>` / `<li>` | Listas de informações e menus | index.html / elenco.html |
| `<img>` | Exibição de imagens (pôster e elenco) | Todas as páginas |
| `<footer>` | Rodapé com informações adicionais e links | Todas as páginas |
| `<a>` | Links internos e externos | Menu e rodapé |

---

## 🎨 Recursos de CSS utilizados

| Recurso | Descrição | Local no `style.css` |
|----------|------------|----------------------|
| Reset básico (`* { margin: 0; ... }`) | Padroniza espaçamentos e box-sizing | Início do arquivo |
| Tipografia e cores do corpo (`body`) | Define fonte, cor e fundo padrão | Linhas 8–15 |
| Layout do cabeçalho e menu (`header`, `.menu`) | Centraliza conteúdo e cria barra de navegação | Linhas 18–60 |
| Estrutura principal (`main`, `section`) | Limita largura, aplica espaçamento e sombra | Linhas 70–95 |
| Cards de elenco (`.cards-container`, `.card`) | Layout em grid flexível e responsivo | Linhas 120–160 |
| Rodapé (`footer`) | Fundo escuro e links de referência | Linhas 100–115 |
| Media queries | Ajuste para telas menores (tablets e celulares) | Linhas 110–125 |

---

## 📱 Responsividade
O site adapta-se a diferentes dispositivos (desktop, tablet e celular) utilizando **flexbox** e **media queries**:
- até 768px → menu em coluna;
- até 480px → imagens e títulos ajustados.

---

## 🔗 Navegação
O menu principal, presente em todas as páginas, permite ir diretamente para:
- **Sobre o Filme** (`index.html`)
- **Elenco & Equipe** (`elenco.html`)
- **Extras** (`extras.html`)

---

## 🧩 Observações
- Código validado conforme padrões do **W3C Validator**.  
- Nenhum framework, biblioteca ou script externo foi utilizado.

---

## 👨‍💻 Autor
**Adam Ismail**  
Curso: Análise e Desenvolvimento de Sistemas — IFSC São José  
Data de entrega: 06/10/2025
