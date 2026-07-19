# Estratégias de Resposta aos Riscos

## Objetivo

Este documento apresenta possíveis estratégias de resposta para os riscos previamente identificados e analisados no projeto de desenvolvimento do aplicativo móvel para agendamento de consultas médicas. As alternativas são apresentadas de forma exploratória, considerando as abordagens clássicas de gerenciamento de riscos: evitar, mitigar, transferir e aceitar.

---

# 1. Estratégias Possíveis por Risco

## Risco 1 – Instabilidade na integração com o sistema externo de prontuário

**Descrição**

A integração com o sistema externo pode sofrer atrasos ou falhas devido à documentação incompleta da API e às mudanças realizadas pelo fornecedor.

### Estratégias de resposta possíveis

**Evitar**

- Adiar o desenvolvimento das funcionalidades dependentes da integração até que a API esteja estável e suficientemente documentada.
- Reavaliar, quando possível, a dependência da integração para funcionalidades não essenciais.

**Mitigar**

- Desenvolver testes contínuos para validar a integração.
- Documentar internamente o comportamento da API durante o desenvolvimento.
- Manter comunicação frequente com a equipe responsável pelo sistema externo.

**Transferir**

- Formalizar acordos de suporte com o fornecedor da API.
- Compartilhar responsabilidades relacionadas à manutenção da integração com a equipe responsável pelo sistema externo, quando contratualmente possível.

**Aceitar**

- Prosseguir com o desenvolvimento reconhecendo que alterações futuras na API poderão exigir adaptações, acompanhando continuamente a evolução do sistema externo.

---

## Risco 2 – Retrabalho decorrente de mudanças nos requisitos

**Descrição**

Solicitações de alteração no fluxo de agendamento podem exigir modificações em funcionalidades já implementadas.

### Estratégias de resposta possíveis

**Evitar**

- Estabelecer um processo formal de aprovação antes da implementação de novos requisitos.

**Mitigar**

- Priorizar reuniões frequentes de alinhamento com os stakeholders.
- Registrar e controlar todas as solicitações de mudança.
- Planejar entregas incrementais para facilitar ajustes.

**Transferir**

- Compartilhar a responsabilidade pela validação dos requisitos com os stakeholders responsáveis pelas decisões de negócio.

**Aceitar**

- Aceitar pequenas mudanças como parte natural do desenvolvimento, desde que seus impactos sejam controlados e registrados.

---

## Risco 3 – Atraso no cronograma

**Descrição**

A combinação dos riscos técnicos e das mudanças de requisitos pode comprometer os prazos previstos.

### Estratégias de resposta possíveis

**Evitar**

- Replanejar o cronograma antes que os atrasos comprometam as entregas futuras.

**Mitigar**

- Revisar prioridades do backlog.
- Monitorar continuamente o progresso do projeto.
- Antecipar atividades críticas sempre que possível.

**Transferir**

- Avaliar a possibilidade de terceirizar atividades específicas, caso seja viável para o projeto.

**Aceitar**

- Aceitar pequenos desvios no cronograma quando o impacto sobre os objetivos do projeto for considerado baixo.

---

## Risco 4 – Sobrecarga da equipe

**Descrição**

O aumento da carga de trabalho pode reduzir a produtividade e comprometer o cumprimento dos prazos.

### Estratégias de resposta possíveis

**Evitar**

- Limitar a inclusão de novas demandas durante o ciclo de desenvolvimento.

**Mitigar**

- Redistribuir atividades entre os membros da equipe.
- Reavaliar prioridades.
- Ajustar o planejamento conforme a capacidade disponível.

**Transferir**

- Avaliar a contratação temporária de recursos externos ou apoio especializado, quando viável.

**Aceitar**

- Manter a distribuição atual das atividades caso a sobrecarga seja considerada temporária e administrável.

---

## Risco 5 – Redução da qualidade do software

**Descrição**

Mudanças frequentes e pressão por prazos podem aumentar a ocorrência de defeitos.

### Estratégias de resposta possíveis

**Evitar**

- Não aprovar entregas que não atendam aos critérios mínimos de qualidade definidos pelo projeto.

**Mitigar**

- Reforçar revisões de código.
- Ampliar a cobertura de testes.
- Executar testes de regressão após alterações relevantes.

**Transferir**

- Utilizar ferramentas automatizadas ou serviços especializados para apoiar atividades de testes, quando disponível.

**Aceitar**

- Aceitar defeitos de baixa criticidade que possam ser corrigidos em versões futuras, desde que não comprometam funcionalidades essenciais.

---

## Risco 6 – Dificuldades de comunicação e coordenação da equipe distribuída

**Descrição**

A distribuição da equipe pode dificultar o alinhamento das atividades e a comunicação entre seus integrantes.

### Estratégias de resposta possíveis

**Evitar**

- Definir processos de comunicação e responsabilidades antes do início das atividades.

**Mitigar**

- Realizar reuniões periódicas de acompanhamento.
- Centralizar registros de decisões.
- Utilizar ferramentas colaborativas para acompanhamento das tarefas.

**Transferir**

- Não foram identificadas, com base nas informações disponíveis, alternativas claras para transferência desse risco.

**Aceitar**

- Aceitar pequenas dificuldades de comunicação quando elas não comprometerem significativamente o andamento do projeto.

---

# 2. Considerações sobre a aplicação das estratégias

## Evitar

Essa estratégia tende a ser mais adequada quando o risco pode comprometer objetivos essenciais do projeto e existem alternativas viáveis para eliminar sua causa.

**Limitações**

- Pode aumentar custos ou alterar significativamente o planejamento.
- Nem sempre é possível eliminar completamente um risco.

---

## Mitigar

É geralmente a estratégia mais utilizada em projetos de software, buscando reduzir a probabilidade de ocorrência ou minimizar seus impactos.

**Limitações**

- Normalmente exige investimento adicional em planejamento, monitoramento ou recursos.
- Não elimina totalmente o risco.

---

## Transferir

É mais adequada quando outra organização ou fornecedor possui maior capacidade para lidar com determinado risco.

**Limitações**

- Nem todos os riscos podem ser transferidos.
- A responsabilidade final pelo sucesso do projeto normalmente permanece com a equipe de gerenciamento.

---

## Aceitar

É indicada quando o custo de tratar o risco é superior ao seu possível impacto ou quando não existem alternativas viáveis.

**Limitações**

- Exige monitoramento constante.
- O risco permanece presente durante a execução do projeto.

---

# 3. Observações Gerais

As estratégias apresentadas possuem caráter exploratório e não representam recomendações definitivas. A seleção da abordagem mais adequada depende de informações adicionais sobre o projeto, como:

- orçamento disponível para tratamento dos riscos;
- restrições de prazo;
- tolerância ao risco da organização;
- nível de apoio dos stakeholders;
- acordos existentes com fornecedores externos.

Também recomenda-se validar com os stakeholders:

- a prioridade de cada risco para o negócio;
- o impacto aceitável sobre cronograma e escopo;
- a disponibilidade de recursos para implementação das estratégias propostas.

Na ausência dessas informações, as alternativas apresentadas devem ser utilizadas como apoio à tomada de decisão, podendo ser revisadas à medida que novos dados se tornem disponíveis.
