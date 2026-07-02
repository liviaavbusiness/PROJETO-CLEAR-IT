# Critérios de Aceite — MVP Copiloto Inteligente de Pré-Vendas

Este documento estabelece os critérios objetivos que definem quando cada funcionalidade principal do MVP pode ser considerada pronta para testes e validação.

Os critérios foram definidos com base no fluxo consultivo atual da Clear IT e no objetivo central de transformar conhecimento especializado em inteligência operacional escalável.

---

# US01 — Interpretação Inicial da Oportunidade

### Objetivo

Permitir que o sistema compreenda o contexto inicial fornecido pelo cliente e produza uma leitura estruturada do cenário apresentado.

### Critérios de Aceite

- O sistema deve receber descrições textuais inseridas manualmente pelo usuário.
- O sistema deve interpretar o contexto recebido em tempo inferior a 5 segundos.
- O sistema deve identificar elementos centrais do cenário apresentado pelo cliente.
- O sistema deve estruturar a interpretação sem sugerir soluções prematuras.
- O resultado deve apresentar entendimento coerente do contexto informado.

---

# US02 — Identificação da Dor Real do Cliente

### Objetivo

Permitir que a Inteligência Artificial identifique a necessidade empresarial real por trás da demanda inicialmente apresentada.

### Critérios de Aceite

- O sistema deve diferenciar demanda aparente de problema empresarial subjacente.
- O sistema deve identificar pelo menos uma dor central associada ao contexto apresentado.
- O sistema deve apresentar justificativa lógica para a identificação realizada.
- O sistema não pode limitar a análise apenas ao pedido técnico inicial do cliente.
- O resultado deve representar uma interpretação consultiva semelhante ao raciocínio humano.

---

# US03 — Geração Inteligente de Perguntas Consultivas

### Objetivo

Gerar perguntas estratégicas que aprofundem o discovery e revelem informações ausentes.

### Critérios de Aceite

- O sistema deve identificar informações insuficientes ou incompletas.
- O sistema deve gerar entre 3 e 7 perguntas contextualizadas.
- Cada pergunta deve estar relacionada a uma lacuna identificada anteriormente.
- As perguntas devem seguir lógica consultiva semelhante à utilizada por especialistas.
- As perguntas devem ajudar no aprofundamento técnico e de negócio da oportunidade.

---

# US04 — Associação ao Portfólio Tecnológico da Clear IT

### Objetivo

Relacionar o problema identificado às áreas de atuação e soluções disponíveis no portfólio da empresa.

### Critérios de Aceite

- O sistema deve consultar a base de conhecimento interna antes de gerar recomendações.
- O sistema deve identificar qual domínio tecnológico melhor se relaciona com a necessidade apresentada.
- O sistema deve associar corretamente pelo menos uma solução do portfólio Clear IT.
- O sistema deve justificar a relação entre problema identificado e solução sugerida.
- O sistema não deve recomendar soluções fora das áreas de atuação da empresa.

---

# US05 — Construção de Hipótese Inicial e Resumo Consultivo

### Objetivo

Estruturar uma visão consolidada da oportunidade para continuidade interna do processo comercial e técnico.

### Critérios de Aceite

- O sistema deve gerar resumo estruturado contendo contexto e dor identificada.
- O resumo deve apresentar informações faltantes detectadas durante a análise.
- O sistema deve apresentar hipótese inicial de solução vinculada ao portfólio da empresa.
- O resultado deve organizar as informações de forma compreensível para pré-vendas e especialistas.
- O sistema deve sinalizar que a recomendação representa uma hipótese inicial e não decisão final.

---

# Critério Geral de Validação do MVP

O MVP será considerado validado quando for capaz de:

- Interpretar corretamente o contexto inicial de uma oportunidade.
- Identificar a dor empresarial central do cliente.
- Detectar lacunas relevantes durante o discovery.
- Gerar perguntas consultivas contextualizadas.
- Relacionar o problema ao portfólio tecnológico da Clear IT.
- Produzir um resumo estruturado capaz de apoiar a continuidade da pré-venda.

---

# Objetivo Final da Validação

Garantir que o sistema consiga replicar parte do raciocínio consultivo atualmente concentrado nos especialistas da Clear IT, reduzindo dependência individual e aumentando a padronização do processo de pré-vendas.
