# Natura Shop - Fragrâncias Premium

Projeto acadêmico de uma loja de fragrâncias fictícia desenvolvida por Felipe Santos, Victor Rios e Vitor Freitas. O objetivo é demonstrar conhecimentos em HTML5 semântico, CSS3 (Flexbox / Grid) e JavaScript para interação com DOM e persistência local (localStorage).

---

## 🔖 Visão geral

Natura Shop é uma página estática que apresenta uma grade de produtos, filtros por categoria, modal de carrinho com persistência via `localStorage`, modal de login (simulado), formulário de newsletter e alternador de tema claro/escuro.

Funcionalidades principais:
- Exibição responsiva de produtos em grid.
- Filtros por categoria (Todos / Masculino / Feminino / Unissex).
- Adicionar, remover e atualizar quantidade de itens no carrinho.
- Persistência do carrinho no `localStorage`.
- Modal de carrinho lateral com overlay.
- Modal de login (simulação) com toggle para mostrar/ocultar senha.
- Newsletter com validação básica de formulário.
- Alternador de tema claro/escuro (persistência opcional pode ser adicionada).
- Layout responsivo e componentes estilizados com CSS puro.

---

## 🗂 Estrutura do projeto

- index.html — página principal com markup, estilos internos e scripts.
- (Imagens) — imagens externas utilizadas via URLs públicas (Natura).
---

## 🚀 Como executar localmente

Opções simples:

1. Abrir diretamente
   - Abra o arquivo `index.html` no seu navegador (duplo clique ou arrastar para o navegador).

2. Usar um servidor local (recomendado para evitar restrições de CORS ao trabalhar com recursos adicionais)
   - Com Node.js instalado:
     - Instale um servidor estático, por exemplo `live-server`:
       ```
       npm install -g live-server
       ```
     - Execute:
       ```
       live-server
       ```
     - Acesse a URL exibida (normalmente `http://127.0.0.1:8080`).

---

## 🧩 Como usar

- Navegação:
  - Use os links no cabeçalho para navegar entre seções (scroll suave).
- Filtros:
  - Clique nos botões de filtro para ver somente produtos daquela categoria.
- Carrinho:
  - Clique em "Adicionar ao Carrinho" em um produto.
  - Abra o carrinho clicando no botão "🛒 Carrinho" no cabeçalho.
  - No modal do carrinho é possível aumentar/diminuir quantidade ou remover itens.
  - O carrinho é salvo no `localStorage` (chave: `naturaCart`).
- Login:
  - Clique em "Login" para abrir o modal. O login é simulado — envia apenas um alerta.
  - O botão do olho alterna entre mostrar/ocultar a senha.
- Newsletter:
  - Preencha nome e e-mail e submeta para ver a mensagem de sucesso.
- Tema:
  - Clique no botão flutuante no canto inferior direito para alternar tema claro/escuro.

---

## ♿ Acessibilidade & Responsividade

- Layout responsivo com media queries para se adaptar a telas menores (tablet e mobile).
- Botões e controles usam foco nativo do navegador; melhorar com estilos de `:focus` personalizados é sugerido.
- Recomenda-se adicionar atributos ARIA adicionais e labels explícitos para aumentar acessibilidade em futuros refinamentos.

---

## ♻️ Persitência

- O carrinho de compras é persistido no `localStorage` sob a chave `naturaCart`.
- Em futuros aprimoramentos, você pode persistir preferências do tema ou o estado do usuário autenticado (quando backend existir).


## 🛠 Tecnologias

- HTML5
- CSS3 (Flexbox, Grid, Media Queries)
- JavaScript (DOM, eventos, localStorage)
- Imagens hospedadas externamente

---

## 📋 Licença

Projeto de exemplo / acadêmico. Sinta-se à vontade para reutilizar o código para estudos e demonstrações. Recomenda-se aplicar uma licença (por exemplo MIT) caso deseje publicar.

---

## ✍️ Autores

- Felipe Santos
- Victor Rios
- Vitor Freitas

---
