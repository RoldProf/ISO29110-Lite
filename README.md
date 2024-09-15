<p align="center">
   <img src="./assets/logo/logo.png" width="30%">
</p>

[![Markdown](https://img.shields.io/badge/markdown-md-blue.svg)](https://developer.mozilla.org/pt-BR/docs/Web/Markdown)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](./LICENSE)
[![Version](https://img.shields.io/badge/version-0.1.0-brightgreen)](./README.md)

---

## O que é o ISO29110-Lite?

O **ISO29110-Lite** é um projeto que visa **simplificar e facilitar a gestão de documentos** (POPs e DOCs) conforme a norma **ISO/IEC 29110** e outros modelos de qualidade reconhecidos (veja mais em [referências](./docs/pt-br/Project_references.md)). Ele é voltado para **ambientes educacionais**, **incubadoras** e **pequenos times**, oferecendo uma abordagem modular e acessível para garantir **conformidade**, **rastreabilidade** e **controle de qualidade** nos processos documentados.

> **Importante**:  
O **ISO29110-Lite** **não é um sistema de gestão de projetos**, mas sim uma ferramenta para **gerir documentos** que registram e normatizam os processos de um projeto. Ele permite o **versionamento**, o **controle de não conformidades** e a **interdependência de POPs**, além de assegurar a **rastreabilidade** dos processos documentados.

Neste repositório, o **ISO29110-Lite** complementa o [**FlowED**](https://github.com/SysDevTools/FlowED), uma metodologia de gestão de projetos projetada para o ambiente acadêmico e pequenos times, com foco em ciclos automatizados e uma abordagem educacional. Entretanto, o **ISO29110-Lite** pode ser facilmente adaptado a outras metodologias de gestão de projetos, como **Scrum**, **Kanban**, ou modelos preditivos como **Waterfall**.

**Saiba mais detalhes** sobre a **Filosofia do Projeto** e como o **ISO29110-Lite** pode ser adaptado a diferentes cenários de gestão de projetos em [Filosofia e escopo do Projeto](./docs/pt-br/Document_of_Project_Philosophy.md).

---

## Sistema de POPs e DOCs

O **ISO29110-Lite** utiliza uma abordagem modular para a **documentação** e o **controle de qualidade**, com base em dois tipos de documentos:

- **POPs (Procedimentos Operacionais Padrão)**: Descrevem as **tarefas e subtarefas** necessárias para a execução de um processo. Cada POP contém instruções detalhadas que garantem que todos os envolvidos no projeto sigam as mesmas etapas para garantir a consistência.
  
- **DOCs (Documentos de Controle)**: Complementam os POPs ao definir **limites, critérios e padrões de controle** para garantir que o processo descrito nos POPs seja executado com **qualidade** e **conformidade**. Os DOCs também asseguram que cada processo seja monitorado e auditado corretamente.

> **Para mais detalhes**, consulte [O Sistema de POPs e DOCs](./docs/pt-br/Pops_and_Docs.md), que explica como esses documentos são organizados e aplicados no contexto de gestão de qualidade.

---

## Uso Combinado com FlowED

O **ISO29110-Lite** complementa o [**FlowED**](https://github.com/SysDevTools/FlowED), fornecendo **POPs** e **DOCs** que documentam os processos nos diferentes ciclos do projeto, como **desenvolvimento**, **homologação** e **publicação**. A combinação dos dois sistemas garante que os processos sigam os padrões de qualidade e conformidade conforme as boas práticas da **ISO/IEC 29110**.

> **Nota**: O **ISO29110-Lite** pode ser facilmente adaptado a outras metodologias, como **Scrum**, **Kanban**, ou modelos preditivos como **Waterfall**.

Para uma explicação mais detalhada sobre como o **ISO29110-Lite** suporta os ciclos do **FlowED**, consulte o [documento completo sobre a integração](./docs/pt-br/ISO29110_FlowED_Integration.md).

---

## Navegação pelo Repositório

A documentação do **ISO29110-Lite** é organizada de forma modular, facilitando o acesso a cada parte conforme as necessidades do projeto. Abaixo está uma visão geral da estrutura de pastas:

1. **docs/**:  
   A pasta **docs/** armazena toda a documentação original do projeto, organizada em subpastas por idioma. Aqui você encontrará guias detalhados sobre o uso do **ISO29110-Lite**, seus POPs e DOCs, e orientações para adaptar a metodologia a diferentes contextos.  

2. **templates/self/**:  
   Pasta dedicada aos **POPs e DOCs** internos do próprio projeto **ISO29110-Lite**, como templates de produção de novos POPs e DOCs. Esses documentos servem para **gerir o próprio processo de documentação** do projeto e podem ser usados como modelo para criar novos procedimentos.  
   Consulte o [Guia da Pasta Self](./docs/pt-br/templates/self/README.md).

3. **templates/cycles/**:  
   Esta pasta contém a documentação organizada por **ciclos** de projeto, refletindo as fases de gestão documentadas pelo **ISO29110-Lite**. Aqui você encontra os documentos prontos para download e uso simples. No estudo de caso com o **FlowED**, essa estrutura cobre os ciclos específicos dessa metodologia.
   
   Aqui estão os ciclos principais:
   - [Ciclo Init](./docs/pt-br/templates/cycles/init/README.md) – Índice de documentos relacionados às **fases iniciais** do projeto.
   - [Ciclo de Desenvolvimento](./docs/pt-br/templates/cycles/develop/README.md) – Índice de documentos relacionados ao ciclo de **desenvolvimento**.
   - [Ciclo de Homologação](./docs/pt-br/templates/cycles/homolog/README.md) – Índice de documentos relacionados ao ciclo de **homologação**.

Para mais informações sobre a estrutura completa do repositório, veja o [Mapa Completo do Repositório](./SiteMap.md).

---

## Referências e Contribuição

Para consultar todas as normas e referências utilizadas no projeto, veja o arquivo de [Referências](./docs/pt-br/Project_references.md).

Se deseja contribuir com o projeto, consulte o [guia de contribuição](./docs/pt-br/CONTRIBUTING.md).  
> **Sugestões e pull requests são sempre bem-vindos!** Junte-se a nós e ajude a melhorar a qualidade e rastreabilidade dos processos documentados no **ISO29110-Lite**.
