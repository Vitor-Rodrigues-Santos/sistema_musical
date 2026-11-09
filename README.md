# 🎵 Exercício Prático - Interface de Sistema Musical 🎤

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)]()
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)]()
[![Status](https://img.shields.io/badge/Status-Concluído-brightgreen?style=for-the-badge)]()

Este repositório contém o código front-end do **Sistema Musical**, desenvolvido como parte da atividade prática focada na criação de múltiplas telas e na estilização consistente de um tema padronizado, garantindo total responsividade para dispositivos móveis e desktops.

---

## 🚀 Tecnologias Utilizadas

- **HTML5** (Estruturação semântica, formulários complexos e tabelas de dados)
- **CSS3** (Estilização centralizada, Variáveis nativas, CSS Grid, Flexbox e Media Queries)

---

## 📋 Atividade Desenvolvida

### 🖥️ 1. Estruturação das Telas do Sistema (`HTML`)
- **Descrição:** Construção de 5 telas interativas que compõem o fluxo completo de gerenciamento do sistema da equipe.
- **Telas desenvolvidas:**
  - **Login (`login.html`):** Tela de autenticação com formulário centralizado.
  - **Menu Principal (`index.html`):** Painel de navegação utilizando layout em cards interativos.
  - **Cadastro de Criador (`cadastro_artista.html`):** Formulário de registro de artistas, upload de imagens e tabela de listagem com ações integradas.
  - **Cadastro de Obra (`cadastro_musica.html`):** Inserção de novas músicas associadas aos artistas, incluindo capa e link do YouTube.
  - **Listagem (`listagem_musicas.html`):** Biblioteca musical completa com área dedicada a filtros de busca e organização em formato tabular.

### 🎨 2. Estilização e Design System (`style.css`)
- **Descrição:** Criação da identidade visual do sistema utilizando um único arquivo de estilos, focado em reaproveitamento de código e adaptação de telas.
- **Recursos e técnicas aplicadas:**
  - **Paleta de Cores no `:root`:** Definição de variáveis globais (`--primary`, `--blue`, `--surface`, `--bg`, etc.) no início do arquivo para facilitar a manutenção e garantir consistência em todas as telas.
  - **Responsividade (Mobile & Desktop):** Uso de media queries (`@media (max-width: 768px)`) adaptando tabelas com *overflow*, empilhando colunas do grid de formulários e ajustando tamanhos de botões e textos para perfeita navegação no celular.
  - **CSS Grid & Flexbox:** Organização dos formulários em formato de grade (`grid-template-columns`), e uso de Flexbox para alinhamento de barras superiores, botões de ação e centralização de elementos (como na tela de login).
  - **Componentização UI:** Criação de classes reaproveitáveis para botões (`btn-primary`, `btn-delete`), cartões, mensagens de alerta e estruturação unificada de tabelas.

---

## 👤 Repositório desenvolvido por:

**Nome:** Vitor Rodrigues Santos  
**Turma:** 1ID-DS
