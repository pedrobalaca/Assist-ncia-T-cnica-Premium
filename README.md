# 🛠️ Assistência Técnica Premium - Gerador de Orçamentos Rápido

Este é um projeto **minimalista e moderno** construído em HTML, CSS e JavaScript puro, desenhado para ser uma ferramenta de **Gerador de Orçamentos e Códigos de Atendimento** para assistências técnicas de informática.

O objetivo é fornecer uma interface de usuário limpa, responsiva e com suporte a temas (claro/escuro) para agilizar o processo de triagem e registro de pedidos de serviço.

---

## ✨ Funcionalidades Principais

* **Fluxo de Orçamento Rápido:** O usuário é guiado por etapas intuitivas para selecionar o tipo de serviço (Montagem, Troca de SO, Upgrade de SSD).
* **Geração de Código Exclusivo:** Cada orçamento finalizado gera um código de atendimento único (Ex: `TEC-1A7B9C`).
* **Consulta de Pedidos (Simulação):** Possibilidade de consultar o resumo de um pedido salvo usando o código gerado.
* **Modo Claro/Escuro (Toggle):** Alternância elegante entre o modo de visualização, com a preferência salva no `localStorage`.
* **Design Minimalista e Sem Logos:** Foco total na usabilidade, utilizando apenas ícones de texto (`🔧`, `🚀`, etc.) para manter a performance e a simplicidade.
* **Totalmente Front-End:** Não depende de back-end ou banco de dados; utiliza o `localStorage` do navegador para armazenar os orçamentos (simulação de persistência).

---

## 🚀 Como Usar

Este projeto é um aplicativo de página única (SPA) e pode ser rodado localmente sem a necessidade de servidores web.

### Instalação

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git](https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git)
    ```
2.  **Navegue até o diretório:**
    ```bash
    cd SEU_REPOSITORIO
    ```
3.  **Abra o arquivo:**
    Simplesmente clique duas vezes no arquivo `index.html` no seu explorador de arquivos, ou abra-o diretamente no seu navegador.

### Demonstração de Fluxo

1.  Na tela inicial, escolha um serviço (ex: **"Melhorar Desempenho"**).
2.  Na etapa 3, selecione o tamanho do SSD e a opção de sistema.
3.  Clique em **"Finalizar Orçamento"**.
4.  O sistema gerará um código de atendimento. Copie este código.
5.  Volte para a tela inicial e selecione **"Consultar Orçamento (Código)"**.
6.  Cole o código para visualizar os detalhes do pedido.

---

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído usando a base fundamental do desenvolvimento web para máxima leveza e compatibilidade:

* **HTML5:** Estrutura e Conteúdo.
* **CSS3:** Estilização, Design Responsivo e Variáveis de Tema (Dark Mode).
* **JavaScript (Puro):** Lógica, Interatividade, Manipulação do DOM e Armazenamento (`localStorage`).

---

## 📝 Próximos Passos (Sugestões de Melhoria)

* **Cálculo de Preços:** Adicionar uma lógica de precificação baseada nas escolhas do usuário.
* **Otimização do `localStorage`:** Implementar um mecanismo para limpar códigos antigos e evitar excesso de dados.
* **Confirmação Visual:** Melhorar as animações e feedback visual após a geração ou consulta do código.
* **Deploy:** Publicar o projeto em um serviço de hospedagem estático (GitHub Pages, Netlify) para acesso em tempo real.
