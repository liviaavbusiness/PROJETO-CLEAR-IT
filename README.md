# PROJETO CLEAR IT – Intelligent Pre-Sales Copilot

> MVP desenvolvido para o desafio da Clear IT, com foco na estruturação do conhecimento consultivo da pré-venda por meio de Inteligência Artificial.

---

# Sobre o Projeto

Este projeto foi desenvolvido durante o desafio liderado pela Pulse Mais e tem como objetivo construir um MVP capaz de apoiar o processo de pré-vendas para a empresa Clear IT, auxiliando especialistas na condução do discovery, identificação das necessidades do cliente e recomendação consultiva de soluções aderentes ao portfólio da empresa.

Mais do que automatizar tarefas, o projeto busca transformar o conhecimento consultivo da Clear IT em um ativo reutilizável, padronizado e escalável.

---

# Contexto do Desafio

A Clear IT é uma empresa brasileira especializada em soluções de Cloud, Cibersegurança, Observabilidade e Inteligência Artificial.

O desafio proposto consiste em compreender como ocorre atualmente o processo de pré-vendas e desenvolver uma solução capaz de apoiar esse processo utilizando Inteligência Artificial, preservando a qualidade consultiva e reduzindo a dependência do conhecimento individual dos especialistas.

---

# Problema de Negócio

Atualmente, grande parte do conhecimento necessário para conduzir uma boa pré-venda encontra-se distribuído entre especialistas da empresa.

Como consequência:

- diferentes profissionais podem conduzir discoveries de formas inconsistente;
- aumenta o retrabalho na elaboração das propostas;
- novos colaboradores possuem maior curva de aprendizagem;
- o processo torna-se pouco escalável.

---

# Objetivo

Construir um agente inteligente capaz de:

- apoiar reuniões de discovery;
- mapear jornada do cliente e situações recorrentes;
- identificar a dor real do cliente;
- sugerir perguntas contextualizadas;
- identificar lacunas de informação;
- relacionar necessidades ao portfólio da Clear IT;
- gerar documentação automaticamente;
- apoiar a tomada de decisão da equipe de pré-vendas.

---

# Escopo do MVP

O MVP contempla:

- Discovery guiado
- Identificação da dor
- Mapeamento das necessidades
- Classificação da oportunidade
- Identificação de lacunas
- Storytelling consultivo
- Geração automática de resumo executivo
- Ata de reunião
- Próximos passos
- Follow-up

---

# Estrutura do Projeto

```
docs/
│
├── business-context-lite.md
├── technical-context-lite.md
├── onion-cycles.md
│
└── knowledge-base/
```

A documentação foi organizada seguindo os princípios de Spec-as-Code, priorizando o entendimento do negócio antes do desenvolvimento da solução.

# Evolução e Estrutura do Projeto

O projeto está sendo desenvolvido de forma incremental, priorizando inicialmente a compreensão profunda do problema de negócio e evoluindo progressivamente até a construção de uma solução inteligente de apoio ao processo de pré-vendas consultivas da Clear IT.

A evolução prevista da solução seguirá as seguintes etapas:

**MVP 1 → Assistente de Discovery Comercial e Técnico**

Auxilia profissionais durante a etapa inicial de discovery, apoiando identificação de necessidades, levantamento de contexto e detecção de lacunas de informação.

**MVP 2 → Sistema Inteligente de Recomendação de Soluções**

Relaciona necessidades identificadas às soluções aderentes ao portfólio da Clear IT.

**MVP 3 → Gerador Inteligente de Propostas Consultivas**

Apoia a construção inicial de propostas comerciais a partir das informações levantadas durante o discovery.

**MVP 4 → Copiloto de Pré-Vendas Baseado em Inteligência Artificial**

Acompanha o processo consultivo de ponta a ponta, auxiliando decisões técnicas e comerciais.

**MVP 5 → Arquiteto de Soluções Autônomo Baseado em Inteligência Artificial**

Sistema capaz de atuar com maior autonomia no apoio consultivo e no desenho inicial de soluções complexas.

---

A documentação do projeto está organizada utilizando princípios de Spec-as-Code, garantindo que o entendimento do negócio seja definido antes da implementação técnica.

Estrutura atual:

docs/

├── business-context-lite.md

├── technical-context-lite.md

├── onion-cycles.md

└── knowledge-base/

└── clear-it.md

---

# Tecnologias (Previstas)

- Python
- FastAPI
- OpenAI API
- LangChain (a validar)
- Lovable
- GitHub
- Markdown

*A arquitetura técnica será refinada durante as próximas Sprints.*

---

# Metodologia

O projeto está sendo conduzido utilizando uma abordagem incremental baseada em:

- Product Discovery
- Engenharia de Requisitos
- Design Thinking
- Spec-as-Code
- Desenvolvimento Ágil (Sprints)

---

# Status do Projeto

Sprint 1 — Descoberta e Documentação

Status atual:

- ✅ Entendimento do desafio
- ✅ Levantamento das dores
- ✅ Personas
- ✅ Hipóteses
- ✅ KPIs
- ✅ Definição do MVP
- 🚧 Validação com a Clear IT
- ⏳ Desenvolvimento do MVP

---

# Equipe

| Integrante | Responsabilidade |
|------------|------------------|
| Gustavo Lopes | Product Discovery |
| Gustavo Henrique Cavalcanti Rocha | Desenvolvimento |
| Myrella de Almeida Cordeiro | Desenvolvimento |
| Wendy de Lima Pedrosa | UX/UI |
| Juan Pablo | Documentação |
| Lívia Alves Viana | QA / Apresentação |

*A definição das responsabilidades será atualizada conforme a evolução do projeto.*

---

# Próximos Passos

- Validar o entendimento do desafio junto à Clear IT;
- Consolidar a arquitetura técnica;
- Iniciar o desenvolvimento do MVP;
- Integrar a Base de Conhecimento ao agente inteligente;
- Realizar testes com cenários reais de pré-venda.

---
# Evolução e Estrutura do Projeto

O projeto está sendo desenvolvido de forma incremental, priorizando inicialmente a compreensão profunda do problema de negócio e evoluindo progressivamente até a construção de uma solução inteligente de apoio ao processo de pré-vendas consultivas da Clear IT.

A evolução prevista da solução seguirá as seguintes etapas:

**MVP 1 → Assistente de Discovery Comercial e Técnico**

Auxilia profissionais durante a etapa inicial de discovery, apoiando identificação de necessidades, levantamento de contexto e detecção de lacunas de informação.

**MVP 2 → Sistema Inteligente de Recomendação de Soluções**

Relaciona necessidades identificadas às soluções aderentes ao portfólio da Clear IT.

**MVP 3 → Gerador Inteligente de Propostas Consultivas**

Apoia a construção inicial de propostas comerciais a partir das informações levantadas durante o discovery.

**MVP 4 → Copiloto de Pré-Vendas Baseado em Inteligência Artificial**

Acompanha o processo consultivo de ponta a ponta, auxiliando decisões técnicas e comerciais.

**MVP 5 → Arquiteto de Soluções Autônomo Baseado em Inteligência Artificial**

Sistema capaz de atuar com maior autonomia no apoio consultivo e no desenho inicial de soluções complexas.

---

# Licença

Projeto acadêmico desenvolvido exclusivamente pela equipe STACK 5 para fins educacionais durante o Challenge da Clear IT.

## Estrutura do Projeto

O projeto será organizado em documentação, base de conhecimento e código do MVP.
