# Identificação dos Riscos

## Objetivo

Este documento apresenta os riscos identificados para o projeto de desenvolvimento de um aplicativo móvel para agendamento de consultas médicas. A análise foi realizada considerando exclusivamente as informações fornecidas no cenário e suas implicações diretas, sem assumir informações adicionais.

---

# 1. Lista de riscos identificados

## Risco 1 – Instabilidade na integração com o sistema externo de prontuário

**Descrição**

A integração com o sistema de prontuário eletrônico pode apresentar falhas ou atrasos devido à documentação incompleta da API e às mudanças recentes realizadas no sistema externo.

**Contexto de ocorrência**

Esse risco pode se manifestar durante o desenvolvimento, testes ou homologação das funcionalidades que dependem da comunicação com o sistema externo. Como a integração foi informada como crítica para a entrega do projeto, eventuais problemas podem comprometer funcionalidades essenciais.

---

## Risco 2 – Retrabalho decorrente de mudanças nos requisitos

**Descrição**

Alterações solicitadas pelos stakeholders no fluxo de agendamento podem exigir revisões em funcionalidades já implementadas, resultando em retrabalho.

**Contexto de ocorrência**

Esse risco ocorre sempre que novos requisitos ou regras de negócio são incorporados após o início da implementação das funcionalidades relacionadas ao agendamento.

---

## Risco 3 – Atraso no cronograma do projeto

**Descrição**

A combinação entre dificuldades na integração com o sistema externo, mudanças nos requisitos e aumento da carga de trabalho pode impactar os prazos previstos para o projeto.

**Contexto de ocorrência**

Esse risco pode ocorrer durante a execução das atividades planejadas, especialmente na implementação das funcionalidades ainda em desenvolvimento e na conclusão da integração externa.

---

## Risco 4 – Sobrecarga da equipe de desenvolvimento

**Descrição**

O aumento da carga de trabalho relatado pela equipe pode reduzir a capacidade de execução das atividades dentro dos prazos inicialmente estimados.

**Contexto de ocorrência**

Esse risco pode ocorrer durante períodos de implementação de mudanças nos requisitos e resolução de problemas relacionados à integração com o sistema externo.

---

## Risco 5 – Redução da qualidade do software

**Descrição**

O aumento do volume de trabalho e a necessidade de realizar alterações durante o desenvolvimento podem aumentar a probabilidade de defeitos nas funcionalidades entregues.

**Contexto de ocorrência**

Esse risco pode se manifestar durante a implementação, integração e testes das funcionalidades, principalmente quando houver necessidade de modificações em componentes já desenvolvidos.

---

## Risco 6 – Dificuldades de comunicação e coordenação da equipe distribuída

**Descrição**

O contexto informa que a equipe é distribuída, o que pode dificultar o alinhamento das atividades, a comunicação entre os membros e a coordenação das mudanças solicitadas.

**Contexto de ocorrência**

Esse risco pode ocorrer durante o planejamento das atividades, na implementação das alterações de requisitos e na coordenação das tarefas entre desenvolvedores e responsável pelos testes.

---

# Considerações sobre incertezas

Durante a identificação dos riscos, foram observados alguns pontos que exigem validação para uma análise mais precisa:

- Não foi informado se existem planos de contingência para a integração com o sistema externo.
- Não foi informado o nível de experiência da equipe com a tecnologia utilizada ou com o sistema de prontuário eletrônico.
- Não foi informado como ocorre o processo de gerenciamento de mudanças de requisitos.
- Não foi informado se existem ferramentas ou processos específicos para apoiar a comunicação da equipe distribuída.

Na ausência dessas informações, os riscos identificados foram limitados às evidências apresentadas no cenário e às suas implicações diretas.
