# Análise Qualitativa dos Riscos

## Objetivo

Este documento apresenta a análise qualitativa dos riscos identificados para o projeto de desenvolvimento do aplicativo móvel de agendamento de consultas médicas. A avaliação considera os possíveis impactos no projeto, os fatores que influenciam a ocorrência dos riscos e sua classificação qualitativa quanto à probabilidade e ao impacto.

---

# 1. Análise Estruturada dos Riscos

## Risco 1 – Instabilidade na integração com o sistema externo de prontuário

**Descrição**

A integração com o sistema externo pode apresentar falhas devido à documentação incompleta da API e às mudanças recentes realizadas pelo fornecedor.

**Possíveis impactos no projeto**

- Atraso na conclusão das funcionalidades dependentes da integração.
- Retrabalho durante desenvolvimento e testes.
- Possível comprometimento da entrega do projeto, uma vez que a integração foi definida como crítica.

**Fatores que influenciam a ocorrência**

- Documentação incompleta da API.
- Alterações recentes no sistema externo.
- Dependência de um sistema sob responsabilidade de terceiros.

**Probabilidade (qualitativa)**

Alta

**Impacto (qualitativo)**

Alto

**Justificativa da classificação**

O cenário informa explicitamente que a integração já apresenta instabilidade e que ela é crítica para a entrega do projeto, indicando elevada probabilidade de continuidade do risco e alto impacto caso ocorra.

---

## Risco 2 – Retrabalho decorrente de mudanças nos requisitos

**Descrição**

Alterações solicitadas pelos stakeholders podem exigir modificações em funcionalidades já implementadas.

**Possíveis impactos no projeto**

- Aumento do esforço de desenvolvimento.
- Replanejamento das atividades.
- Possíveis atrasos nas entregas.

**Fatores que influenciam a ocorrência**

- Evolução dos requisitos durante o desenvolvimento.
- Inclusão de novas regras de negócio.
- Necessidade de revisão das funcionalidades existentes.

**Probabilidade (qualitativa)**

Alta

**Impacto (qualitativo)**

Alto

**Justificativa da classificação**

O cenário informa que alterações nos requisitos já foram solicitadas, indicando que o risco está presente e pode afetar diretamente prazo e esforço do projeto.

---

## Risco 3 – Atraso no cronograma do projeto

**Descrição**

As dificuldades técnicas e organizacionais podem impedir o cumprimento dos prazos inicialmente estimados.

**Possíveis impactos no projeto**

- Adiamento da entrega.
- Replanejamento do cronograma.
- Aumento do esforço para cumprimento dos prazos.

**Fatores que influenciam a ocorrência**

- Problemas na integração.
- Mudanças frequentes nos requisitos.
- Aumento da carga de trabalho da equipe.

**Probabilidade (qualitativa)**

Alta

**Impacto (qualitativo)**

Alto

**Justificativa da classificação**

Os principais fatores que podem provocar atrasos já estão presentes no cenário, tornando esse risco altamente relevante para o andamento do projeto.

---

## Risco 4 – Sobrecarga da equipe de desenvolvimento

**Descrição**

O aumento da carga de trabalho pode reduzir a capacidade da equipe de executar as atividades dentro do prazo previsto.

**Possíveis impactos no projeto**

- Redução da produtividade.
- Maior dificuldade para cumprir cronogramas.
- Possível aumento da necessidade de retrabalho.

**Fatores que influenciam a ocorrência**

- Equipe composta por quatro desenvolvedores e um tester.
- Alterações frequentes nos requisitos.
- Necessidade de resolver problemas de integração.

**Probabilidade (qualitativa)**

Alta

**Impacto (qualitativo)**

Médio

**Justificativa da classificação**

O aumento da carga de trabalho foi relatado pela própria equipe. Embora represente um risco relevante, seu impacto tende a ocorrer de forma indireta sobre prazo e qualidade.

---

## Risco 5 – Redução da qualidade do software

**Descrição**

As mudanças frequentes e o aumento da carga de trabalho podem aumentar a probabilidade de introdução de defeitos durante o desenvolvimento.

**Possíveis impactos no projeto**

- Maior quantidade de erros identificados nos testes.
- Necessidade de correções adicionais.
- Redução da qualidade percebida pelos usuários.

**Fatores que influenciam a ocorrência**

- Modificações em funcionalidades já implementadas.
- Pressão para cumprimento dos prazos.
- Dependência da integração com sistema externo.

**Probabilidade (qualitativa)**

Média

**Impacto (qualitativo)**

Alto

**Justificativa da classificação**

Embora o cenário não informe ocorrência de defeitos, os fatores apresentados aumentam a possibilidade de redução da qualidade. A probabilidade é considerada média devido à ausência de informações sobre o processo de testes.

---

## Risco 6 – Dificuldades de comunicação e coordenação da equipe distribuída

**Descrição**

A distribuição da equipe pode dificultar o alinhamento das atividades e a comunicação entre seus integrantes.

**Possíveis impactos no projeto**

- Desalinhamento das tarefas.
- Atrasos na tomada de decisão.
- Retrabalho decorrente de falhas de comunicação.

**Fatores que influenciam a ocorrência**

- Equipe distribuída.
- Mudanças frequentes nos requisitos.
- Necessidade de coordenação entre desenvolvimento e testes.

**Probabilidade (qualitativa)**

Média

**Impacto (qualitativo)**

Médio

**Justificativa da classificação**

O contexto informa que a equipe é distribuída, mas não fornece detalhes sobre os processos de comunicação utilizados. Assim, a classificação considera essa incerteza.

---

# 2. Matriz Qualitativa de Riscos

| Probabilidade \ Impacto | Baixo | Médio | Alto |
|--------------------------|:-----:|:------:|:-----:|
| **Alta** | | **R4** | **R1, R2, R3** |
| **Média** | | **R6** | **R5** |
| **Baixa** | | | |

## Legenda

| Código | Risco |
|---------|-------|
| **R1** | Instabilidade na integração com o sistema externo |
| **R2** | Retrabalho decorrente de mudanças nos requisitos |
| **R3** | Atraso no cronograma |
| **R4** | Sobrecarga da equipe |
| **R5** | Redução da qualidade do software |
| **R6** | Dificuldades de comunicação da equipe distribuída |

---

# Considerações sobre incertezas

A classificação qualitativa foi realizada exclusivamente com base nas informações disponíveis no cenário. Alguns aspectos que poderiam influenciar uma avaliação mais precisa não foram informados, como:

- existência de plano de gerenciamento de riscos;
- processo de controle de mudanças;
- nível de maturidade da equipe;
- estratégias de comunicação adotadas para a equipe distribuída;
- métricas históricas de qualidade e produtividade.

Caso essas informações estejam disponíveis em etapas futuras do projeto, recomenda-se revisar esta análise para refinar as classificações de probabilidade e impacto.
