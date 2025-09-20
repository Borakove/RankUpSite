# RankUp - Ferramenta de Análise de SEO

O **RankUp** é uma ferramenta web completa para análise de SEO, desenvolvida como um projeto acadêmico para a disciplina de **Desenvolvimento Web**. O sistema está sendo construído de forma incremental, começando com uma landing page e evoluindo para uma aplicação backend robusta que demonstra a transição de uma arquitetura monolítica para uma distribuída.

### Funcionalidades Principais (Proposta Final)

O objetivo final é entregar uma ferramenta de SEO completa, capaz de:

* **Análise On-Page:** Verificar os fundamentos de SEO (títulos, meta descriptions, cabeçalhos, etc.) de uma única página.
* **Rastreamento de Site:** Identificar erros técnicos em um site inteiro, como links quebrados e conteúdo duplicado.
* **Processamento Assíncrono:** Operar de forma a processar análises complexas sem travar a interface do usuário.

### Stack Tecnológica

#### Fase Atual (Landing Page)

* **HTML5:** Para a estrutura semântica do conteúdo.
* **Tailwind CSS:** Para um desenvolvimento de layout rápido, moderno e responsivo.
* **CSS Puro:** Para estilos e animações complexas, com inspiração da comunidade [uiverse.io](https://uiverse.io/).
* **JavaScript:** Para interatividade e validação de formulários.

#### Próximas Fases (Aplicação Completa)

* **Backend:** PHP 8+ com o framework **Laravel**.
* **Banco de Dados:** **MySQL** para armazenamento de dados.
* **Filas e Cache:** **Redis** para gerenciar tarefas assíncronas.
* **Ambiente de Desenvolvimento:** **Docker** com Laravel Sail.

### Como Visualizar o Projeto

Para visualizar a landing page em seu estado atual:

1.  Clone este repositório:
    ```bash
    git clone https://github.com/Borakove/RankUpSite
    ```
2.  Navegue até a pasta do projeto:
    ```bash
    cd RankUpSite
    ```
3.  Abra o arquivo `index.html` diretamente em seu navegador.