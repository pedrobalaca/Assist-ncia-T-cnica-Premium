# 🛠️ Assistência Técnica Premium - Gerador de Orçamentos Rápido

Este é um projeto **minimalista e moderno** construído em HTML, CSS e JavaScript puro, desenhado para ser uma ferramenta de **Gerador de Orçamentos e Códigos de Atendimento** para assistências técnicas de informática.

O objetivo é fornecer uma interface de usuário limpa, responsiva e com suporte a temas (claro/escuro) para agilizar o processo de triagem e registro de pedidos de serviço.

---

## 🔗 Acesso Rápido (Live Demo)

O aplicativo está hospedado no GitHub Pages e pode ser acessado diretamente:

➡️ **[Visitar Assistência Técnica Premium](https://pedrobalaca.github.io/Assist-ncia-T-cnica-Premium/)**

---

## ✨ Funcionalidades Principais

* **Fluxo de Orçamento Rápido:** O usuário é guiado por etapas intuitivas para selecionar o tipo de serviço (Montagem, Troca de SO, Upgrade de SSD).
* **Geração de Código Exclusivo:** Cada orçamento finalizado gera um código de atendimento único (Ex: `TEC-1A7B9C`).
* **Download do Orçamento:** Permite **baixar o resumo do orçamento como um arquivo de texto (.txt)**, facilitando o arquivamento para o cliente.
* **Consulta de Pedidos (Simulação):** Possibilidade de consultar o resumo de um pedido salvo usando o código gerado.
* **Modo Claro/Escuro (Toggle):** Alternância elegante entre o modo de visualização, com a preferência salva no `localStorage`.
* **Design Minimalista e Sem Logos:** Foco total na usabilidade, utilizando apenas ícones de texto (`🔧`, `🚀`, etc.) para manter a performance e a simplicidade.
* **Totalmente Front-End:** Não depende de back-end ou banco de dados; utiliza o `localStorage` do navegador para armazenar os orçamentos (simulação de persistência).

---

## 🚀 Como Usar

Para testar o projeto, basta visitar o link acima. Se preferir contribuir ou inspecionar o código, siga as instruções abaixo:

### Desenvolvimento Local

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/pedrobalaca/Assist-ncia-T-cnica-Premium.git](https://github.com/pedrobalaca/Assist-ncia-T-cnica-Premium.git)
    ```
2.  **Navegue até o diretório:**
    ```bash
    cd Assist-ncia-T-cnica-Premium
    ```
3.  **Abra o arquivo:**
    Abra o arquivo `index.html` no seu navegador favorito.

### Demonstração de Fluxo

1.  Na tela inicial, escolha um serviço (ex: **"Melhorar Desempenho"**).
2.  Na etapa 3, selecione o tamanho do SSD e a opção de sistema.
3.  Clique em **"Finalizar Orçamento"**.
4.  O sistema gerará um código. Use os botões **"Copiar Código"** e **"Baixar Orçamento"** para salvar os detalhes.
5.  Volte para a tela inicial e selecione **"Consultar Orçamento (Código)"**.
6.  Cole o código para visualizar o resumo do pedido.

---

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído usando a base fundamental do desenvolvimento web para máxima leveza e compatibilidade:

* **HTML5:** Estrutura e Conteúdo.
* **CSS3:** Estilização, Design Responsivo e Variáveis de Tema (Dark Mode).
* **JavaScript (Puro):** Lógica, Interatividade, Manipulação do DOM e Armazenamento (`localStorage`).
