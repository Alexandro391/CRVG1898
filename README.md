Aqui está uma proposta de README para o seu projeto, estruturada com base nas funcionalidades e na identidade visual identificadas no código-fonte.

---

# Club de Regatas Vasco da Gama — Portal Institucional 1898

Este é um portal web dinâmico e responsivo dedicado à história e ao acompanhamento do Club de Regatas Vasco da Gama. O projeto utiliza uma estética minimalista e "flat", focada nas cores tradicionais do clube (preto e branco) com detalhes em vermelho e dourado.

## 🚀 Funcionalidades Principais

* **Sistema de Gestão (Admin Mode):** Interface integrada que permite a edição direta de textos (campos editáveis), remoção de registros e atualização de imagens sem sair do navegador.
* **Seções Dinâmicas:**
    * **História:** Linha do tempo interativa e destaques históricos.
    * **Títulos e Troféus:** Listagem detalhada de conquistas com contadores e galeria de média.
    * **Ídolos e Elenco:** Cartões informativos com fotos, estatísticas e biografias dos atletas.
    * **Estatísticas e Jogos:** Filtros para visualização de partidas, resultados e desempenho de jogadores.
    * **Artilharia:** Ranking automatizado de goleadores com barras de progresso visual.
* **Galeria Multimédia:** Suporte para imagens, vídeos e integração de vídeos externos com sistema de *lightbox* para visualização ampliada.
* **Experiência PWA:** Inclui suporte para instalação como aplicação web, permitindo que o portal seja fixado no ecrã inicial do utilizador.

## 🛠️ Tecnologias Utilizadas

* **Frontend:** HTML5, CSS3 (variáveis nativas, Flexbox, Grid) e JavaScript Vanilla.
* **Backend & Persistência:** Integração com **Firebase** (Firestore para dados em tempo real e Hosting para alojamento).
* **Design:**
    * Tipografia: Bebas Neue, Playfair Display e Barlow (via Google Fonts).
    * Animações: CSS Animations (como o efeito de flutuação do escudo) e transições suaves de scroll.

## 📂 Estrutura do Projeto

* `index.html`: Arquivo principal contendo a estrutura da aplicação, estilos CSS incorporados e lógica de manipulação do DOM.
* **Firebase SDK:** Carregamento modular dos scripts para base de dados e autenticação.

## ⚙️ Como Utilizar

1.  **Modo de Edição:** O portal possui um botão flutuante de administração. Ao ser ativado, as áreas de texto tornam-se editáveis e botões de gestão de média (upload/delete) tornam-se visíveis.
2.  **Configuração Firebase:** Para que o sistema de salvamento funcione, é necessário configurar as credenciais do Firebase no final do script presente no `index.html`.
3.  **Instalação PWA:** Ao aceder via navegador compatível, um banner de instalação será exibido para permitir o acesso rápido via ecrã inicial.

---

> **Nota:** Este projeto foi desenvolvido com foco em performance e identidade visual, utilizando técnicas modernas de design para honrar a história do Gigante da Colina.
