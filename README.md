# IT Service Desk Analytics

Projeto de **Business Intelligence** desenvolvido em **Microsoft Power BI**, com foco na análise de chamados e desempenho de um setor de suporte de Tecnologia da Informação.

O projeto tem como objetivo transformar dados de atendimento em indicadores e informações visuais que auxiliem na identificação de problemas, acompanhamento de SLA e análise da eficiência da equipe de suporte.

## 🎯 Objetivo do Projeto

Desenvolver um dashboard capaz de analisar o funcionamento de um Service Desk, permitindo acompanhar:

- Volume de chamados
- Chamados abertos e fechados
- Tempo médio de atendimento
- Tempo médio de resolução
- Cumprimento de SLA
- Produtividade dos técnicos
- Categorias de problemas
- Prioridade dos chamados
- Departamentos que mais solicitam suporte
- Chamados pendentes e reabertos

## 🛠️ Tecnologias Utilizadas

- Microsoft Power BI
- Power Query
- DAX
- CSV
- GitHub
- GitHub Projects

## 📊 C1 — Visão Geral do Service Desk

A primeira entrega do projeto tem como foco apresentar uma visão geral dos chamados de suporte de TI.

### Principais indicadores

- Total de chamados
- Chamados abertos
- Chamados fechados
- Chamados pendentes
- Percentual de chamados dentro do SLA
- Tempo médio de atendimento
- Tempo médio de resolução
- Percentual de chamados reabertos

### Filtros disponíveis

- Período
- Departamento
- Categoria
- Prioridade
- Técnico
- Status

Os indicadores e gráficos são atualizados dinamicamente conforme os filtros selecionados.

## 📈 C2 — Análise de Atendimento

A segunda entrega terá como objetivo analisar o desempenho do atendimento.

### Análises

- Chamados por mês
- Chamados por categoria
- Chamados por prioridade
- Chamados por departamento
- Desempenho dos técnicos
- Cumprimento de SLA por técnico
- Tempo médio de resolução
- Evolução dos chamados pendentes

## 🚨 C3 — Análise de Problemas

A terceira entrega terá como foco identificar padrões e problemas recorrentes.

### Análises

- Categorias com maior número de chamados
- Problemas recorrentes
- Departamentos com maior demanda
- Horários de maior demanda
- Chamados críticos
- Evolução da demanda
- Tendências de atendimento

## 🗂️ Estrutura do Projeto

```text
IT-ServiceDesk-PowerBI
│
├── Dados
│   ├── chamados.csv
│   ├── tecnicos.csv
│   ├── usuarios.csv
│   ├── categorias.csv
│   ├── departamentos.csv
│   └── historico_chamados.csv
│
├── PowerBI
│   └── IT_ServiceDesk_C1.pbix
│
├── Documentacao
│   └── modelo_dados.png
│
└── README.md
