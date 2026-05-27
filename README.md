# Treinando uma IA de Aprendizagem: Power BI com NotebookLM

## Sobre o Projeto

Este projeto foi desenvolvido como parte do desafio da DIO com o objetivo de explorar o uso da Inteligência Artificial como ferramenta de aprendizagem ativa utilizando o NotebookLM.

O tema escolhido para estudo foi **Power BI**, com foco em conceitos fundamentais, modelagem de dados, Power Query, DAX e construção de dashboards analíticos.

A proposta consiste em utilizar o NotebookLM para organizar conhecimento, realizar perguntas contextualizadas sobre documentos, consolidar aprendizados e estruturar um mini guia de estudos.

---

## Contexto e Objetivos

O estudo foi realizado com o propósito de compreender os principais fundamentos do Power BI e utilizar o NotebookLM como ferramenta de apoio ao aprendizado técnico.

### Objetivos do estudo

- Entender os fundamentos do Power BI;
- Compreender modelagem de dados aplicada ao BI;
- Revisar conceitos de ETL utilizando Power Query;
- Conhecer fundamentos da linguagem DAX;
- Consolidar boas práticas na construção de dashboards;
- Explorar o uso do NotebookLM como ferramenta de estudo técnico.

---

## Curadoria de Fontes

As seguintes fontes abertas foram selecionadas para estudo e poderiam ser utilizadas como material de apoio no NotebookLM:

### 1. Documentação Oficial do Power BI
https://learn.microsoft.com/pt-br/power-bi/

Objetivo:
Compreender fundamentos, modelagem, visualizações e publicação de relatórios.

### 2. Introdução ao DAX no Power BI
https://learn.microsoft.com/pt-br/dax/

Objetivo:
Estudar a linguagem DAX e compreender medidas, colunas calculadas e funções.

### 3. Power Query e Transformação de Dados
https://learn.microsoft.com/pt-br/power-query/

Objetivo:
Entender processos de transformação e limpeza de dados.

### 4. Modelagem de Dados no Power BI
https://learn.microsoft.com/pt-br/power-bi/transform-model/

Objetivo:
Compreender relacionamentos entre tabelas e boas práticas de modelagem.

### 5. Boas práticas de dashboards
https://learn.microsoft.com/pt-br/power-bi/guidance/

Objetivo:
Aprender organização visual, performance e usabilidade.

---

## Engenharia de Prompts e "Cicatrizes"

Durante os testes com IA, diferentes perguntas foram realizadas buscando aprofundar o entendimento sobre Power BI.

### Prompt 1

**Pergunta realizada**

> Explique o que é Power BI e quais são seus principais componentes.

**Resultado obtido**

A resposta apresentou uma visão geral sobre Power BI Desktop, Power BI Service, dashboards, relatórios e fontes de dados.

**Dificuldade encontrada**

A resposta inicial estava muito resumida.

**Refinamento realizado**

> Explique os componentes do Power BI com exemplos práticos de uso empresarial.

---

### Prompt 2

**Pergunta realizada**

> Explique a diferença entre relacionamento 1:N e N:N no Power BI com exemplos simples.

**Resultado obtido**

A IA explicou conceitos de relacionamento entre tabelas.

**Dificuldade encontrada**

A explicação ficou excessivamente teórica.

**Refinamento realizado**

> Explique utilizando um cenário de vendas com clientes, pedidos e produtos.

---

### Prompt 3

**Pergunta realizada**

> O que é DAX no Power BI? Explique para iniciantes.

**Resultado obtido**

Foram apresentados conceitos sobre medidas, agregações e cálculos.

**Dificuldade encontrada**

Exemplos insuficientes.

**Refinamento realizado**

> Mostre exemplos práticos de DAX usando SUM, CALCULATE e filtros.

---

### Prompt 4

**Pergunta realizada**

> Quais erros prejudicam a performance de dashboards Power BI?

**Resultado obtido**

Foram identificados problemas relacionados a excesso de visuais, modelagem inadequada e medidas complexas.

**Aprendizado obtido**

O refinamento do prompt melhora significativamente a qualidade das respostas da IA.

---

## Miniguia de Estudo — Power BI

### O que é Power BI?

Power BI é uma plataforma de Business Intelligence utilizada para análise de dados, construção de dashboards e geração de relatórios interativos.

Seus principais objetivos são:

- Transformar dados em informação visual;
- Apoiar tomada de decisão;
- Consolidar dados de diferentes fontes;
- Facilitar análise gerencial.

---

### Componentes principais do Power BI

#### Power BI Desktop
Ferramenta utilizada para criação de relatórios, transformação de dados e modelagem.

#### Power Query
Responsável por ETL (Extração, Transformação e Carga de Dados).

#### DAX (Data Analysis Expressions)
Linguagem utilizada para cálculos e medidas.

#### Power BI Service
Ambiente web para compartilhamento e publicação de relatórios.

#### Dashboards
Painéis visuais para acompanhamento de indicadores.

---

### Modelagem de Dados

Boas práticas identificadas:

- Evitar relacionamentos ambíguos;
- Utilizar modelo estrela quando possível;
- Reduzir redundância de dados;
- Criar relacionamentos consistentes.

---

### DAX — Conceitos Fundamentais

Exemplos de funções comuns:

**Soma de vendas**

```DAX
Total Vendas = SUM(Vendas[Valor])
```

Total Vendas SP =
CALCULATE(
    SUM(Vendas[Valor]),
    Clientes[Estado] = "SP")

---


## Glossário

| Conceito | Definição |
|---|---|
| Power BI | Plataforma de Business Intelligence |
| Dashboard | Painel visual de indicadores |
| ETL | Extração, transformação e carga de dados |
| DAX | Linguagem de fórmulas do Power BI |
| Power Query | Ferramenta de transformação de dados |
| Modelagem | Organização dos relacionamentos entre tabelas |
| Medida | Cálculo realizado em DAX |



## Prompts Reutilizáveis

Estes prompts podem apoiar futuras revisões de estudo:

- Explique este conceito como se eu estivesse iniciando em Power BI.
- Mostre exemplos práticos utilizando um cenário empresarial.
- Explique vantagens, desvantagens e erros comuns relacionados ao tema.
- Crie um resumo técnico do assunto em tópicos.
- Monte um glossário dos principais conceitos estudados.

---


## Tecnologias Relacionadas
- Power BI
- Business Intelligence (BI)
- Power Query
- DAX
- Modelagem de Dados
- Inteligência Artificial
- NotebookLM
- Análise de Dados

---


## Conclusão

O NotebookLM demonstrou potencial como ferramenta de aprendizagem ativa ao apoiar a organização do conhecimento, refinamento de perguntas e consolidação de estudos técnicos sobre Power BI.

Além da geração de resumos, a experiência evidenciou a importância da engenharia de prompts e do pensamento crítico para obtenção de respostas mais relevantes e contextualizadas.

---


## Próximos Passos
- Criar exemplos práticos no Power BI
- Adicionar capturas de tela
- Expandir estudos sobre DAX
- Estudar modelagem dimensional
- Criar dashboards simples para prática
