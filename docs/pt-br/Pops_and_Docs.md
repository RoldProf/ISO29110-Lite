# O Sistema de POPs e DOCs

O sistema de **POPs** (Procedimentos Operacionais Padrão) e **DOCs** (Documentos de Controle) adotado pelo **ISO29110-Lite** é uma forma prática de **estruturar e normatizar os processos** dentro de um projeto de software. Ele foi criado para garantir a **consistência**, **rastreabilidade** e **controle de qualidade** em todas as fases de um projeto, conforme as boas práticas da **ISO/IEC 29110**.

Os **POPs** são usados para documentar as tarefas e subtarefas que precisam ser realizadas, enquanto os **DOCs** normatizam o procedimento descrito, estabelecendo critérios de qualidade e controle. Juntos, eles garantem que todos os processos sigam padrões consistentes e rastreáveis, permitindo revisões e auditorias eficientes.

## POPs (Procedimentos Operacionais Padrão)

Os **POPs** têm como objetivo **descrever detalhadamente as tarefas e subtarefas** necessárias para a execução de um processo. Cada POP contém uma série de **passos detalhados**, que instruem o responsável pelo processo sobre **como realizar cada atividade** de maneira padronizada, minimizando erros e garantindo a consistência entre os membros da equipe.

### Estrutura de um POP
Um **POP** é um **documento prático e instrucional**, organizado de forma a garantir que todos os membros da equipe estejam alinhados e saibam exatamente **o que fazer** e **quando fazer**.

Elementos típicos de um POP incluem:

- **Objetivo**: Descrição do que o procedimento busca alcançar.
- **Tarefas e Subtarefas**: Passos detalhados que devem ser seguidos, divididos em subtarefas para facilitar a execução.
- **Responsáveis**: Quem é responsável por realizar cada etapa.

#### Exemplo de POP
```md
# POP001: Configuração de Ambiente de Desenvolvimento

## Objetivo
Garantir que o ambiente de desenvolvimento esteja configurado corretamente para suportar o desenvolvimento do projeto.

## Tarefas e Subtarefas
1. **Instalar Git**:
   - Verifique a versão mais recente no [site oficial do Git](https://git-scm.com/).
   - Baixe e instale a versão mais recente.

2. **Configurar VS Code**:
   - Baixe e instale o VS Code.
   - Instale os seguintes plugins:
     - GitLens
     - Docker
     - Prettier
```

### Aplicação no Projeto

No **ISO29110-Lite**, os **POPs** são criados para documentar os processos de diferentes ciclos de um projeto. No contexto de uso conjunto com o [**FlowED**](https://github.com/SysDevTools/FlowED) eles podem ser aplicados a ciclos como:

- **Ciclo de Desenvolvimento**: Documentando as tarefas de codificação, configuração de ambiente e teste.
- **Ciclo de Homologação**: Garantindo que todos os critérios de qualidade e conformidade sejam seguidos durante o processo de validação.
- **Ciclo de Publicação**: Documentando o processo de entrega e publicação do projeto.

Cada POP garante que os processos sejam **seguidos de forma consistente e repetível**, minimizando ambiguidades e falhas de comunicação.

## DOCs (Documentos de Controle)

Os **DOCs** são documentos complementares aos **POPs**, cuja função é **normatizar o procedimento descrito no POP**, estabelecendo **limites**, **critérios de aceitação** e **pontos de controle** para garantir que o processo seja realizado de forma correta e dentro dos padrões de qualidade exigidos.

### Estrutura de um DOC
O **DOC** não descreve **como** realizar a tarefa, mas sim **como ela deve ser controlada**. Ele define os padrões de controle e garante que as atividades sigam os critérios de qualidade estabelecidos.

Elementos típicos de um DOC incluem:

- **Critérios de Aceitação**: Definem os padrões de qualidade que o procedimento deve atender.
- **Limites de Execução**: Determinam prazos ou condições sob as quais o procedimento deve ser realizado.
- **Pontos de Controle**: Especificam os momentos em que o processo deve ser monitorado ou revisado.

#### Exemplo de DOC
```md
# DOC001: Controle de Qualidade para Configuração de Ambiente de Desenvolvimento

## Critérios de Aceitação
1. **Git**: Deve ser instalado corretamente e a versão mais recente deve estar ativa (`git --version`).
2. **VS Code**: Deve estar instalado com os plugins necessários (GitLens, Docker, Prettier).
3. **Repositório**: O repositório deve ser clonado corretamente e estar acessível.

## Limites de Execução
- Todo o procedimento deve ser concluído em até **2 horas** após o início da configuração.

## Pontos de Controle
- Verificar se a instalação do Git e do VS Code foi realizada conforme o planejado.
- Realizar uma revisão após a clonagem do repositório.
```

## Como POPs e DOCs Funcionam Juntos

- **POPs (Como Fazer)**: Descrevem detalhadamente **como realizar as tarefas** e garantir que o processo seja padronizado.
- **DOCs (Como Controlar)**: Estabelecem os **critérios de qualidade** e asseguram que as tarefas descritas no POP estejam sendo realizadas conforme o esperado.

Juntos, os **POPs e DOCs** garantem que os processos sejam **rastreáveis**, **auditores** e que sigam as boas práticas estabelecidas pela **ISO/IEC 29110**.

---

## Benefícios do Sistema de POPs e DOCs

O uso de **POPs** e **DOCs** no **ISO29110-Lite** traz diversos benefícios:

1. **Consistência**:  
O uso de POPs garante que os processos sejam seguidos de maneira consistente por todos os membros da equipe.

2. **Controle de Qualidade**:  
Os DOCs asseguram que o que foi definido no POP seja monitorado e auditado, garantindo que o processo esteja em conformidade com as **boas práticas da norma ISO/IEC 29110**.

3. **Rastreabilidade**:  
POPs e DOCs juntos fornecem uma trilha de auditoria completa, permitindo que qualquer processo seja rastreado e analisado, garantindo conformidade e facilitando auditorias internas e externas.

4. **Flexibilidade Modular**:  
Cada POP e DOC pode ser adaptado às necessidades específicas do projeto, permitindo personalização sem perder a essência das **boas práticas normativas**.

