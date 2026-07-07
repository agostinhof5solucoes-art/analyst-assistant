# 📊 Analyst Assistant - Terminal de Incidentes & Dashboard

Um sistema integrado de gerenciamento de incidentes técnicos voltado para analistas de suporte, operações de TI e gerenciamento de faturamento. O projeto simula um ambiente corporativo completo com controle de acesso, métricas volumétricas interativas e chat interno de operações.

🔗 **https://agostinhof5solucoes-art.github.io/analyst-assistant/**

---

## 🚀 Funcionalidades Principais

* **Autenticação Segura Simulada:** Controle de visualização adaptativo e proteção de rotas com perfis diferenciados para Analista e Administrador Master (`admin / 123`).
* **Gerenciamento Completo de Incidentes (CRUD Local):** Cadastro detalhado de logs estruturados por TAGs, prioridade (Alta, Média, Baixa), aplicação afetada, descrição do erro e solução aplicada.
* **Dashboard Estatístico em Tempo Real:** Gráficos dinâmicos (Barras e Rosca) integrados via **Chart.js** mapeando automaticamente o volume de problemas por módulo (PDV, Retaguarda, Dispositivos Móveis).
* **Ficha Cadastral Estruturada:** Painel de inserção com sub-abas interativas para registro de novos analistas e listagem geral em tempo de execução.
* **Mídias em Base64:** Upload múltiplo de imagens no cadastro do incidente com conversão assíncrona automática para exibição em galeria e zoom dinâmico.
* **Repositório de Executáveis e Materiais:** Indexação temporária e simulação de download de manuais técnicos em formato `.pdf` e pacotes `.exe`.
* **Chat de Operações:** Janela de conversa simulada persistente, com suporte a atalhos de teclado, inserção de emojis e emissão de alertas sonoros de atenção (*audio feedback*).

---

## 🛠️ Tecnologias e Conceitos Aplicados

* **HTML5 Semântico & CSS3 Avançado:** Arquitetura visual baseada em CSS Grid e Flexbox, uso extensivo de variáveis nativas (`:root`), efeitos de desfoque de fundo (*backdrop-filter*) e transições suaves de interface.
* **JavaScript Moderno (ES6+):** Manipulação pesada e dinâmica do DOM, tratamento assíncrono de mídias usando Promises e a API `FileReader`.
* **Persistência de Dados (Mock Database):** Abstração de persistência simulada em coleções utilizando o **LocalStorage** do navegador, garantindo que os dados não sumam ao atualizar a página.
* **Chart.js:** Utilização de biblioteca externa via CDN para renderização e destruição dinâmica de gráficos analíticos de desempenho.

---

## 💻 Como testar localmente

Se preferir rodar o projeto na sua máquina em vez de usar o link online:
1. Baixe o arquivo `index.html` deste repositório.
2. Dê um duplo clique no arquivo para abri-lo diretamente em qualquer navegador moderno.
3. Para testar o login, utilize o usuário **Agostinho** e senha **123** para o perfil de Analista, ou **Admin** e senha **123** para o perfil de Administrador.
