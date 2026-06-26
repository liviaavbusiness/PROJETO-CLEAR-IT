# PROJETO CLEAR IT - Contexto Técnico

## Solução Proposta

Desenvolver um sistema baseado em inteligência artificial capaz de apoiar o processo de pré-vendas consultivas da Clear IT, auxiliando profissionais durante a etapa de discovery e recomendação inicial de soluções.

---

## Arquitetura Conceitual

### Camada de Entrada

Responsável por receber informações iniciais sobre a oportunidade comercial.

Entradas possíveis:

* briefing inicial;
* informações do cliente;
* contexto do negócio;
* descrição do problema apresentado.

---

### Camada de Inteligência

Responsável pelo raciocínio consultivo do sistema.

Funções esperadas:

* interpretar oportunidade;
* identificar contexto técnico;
* detectar lacunas de informação;
* sugerir perguntas contextualizadas;
* relacionar necessidade ao portfólio;
* apoiar análise consultiva.

---

### Camada de Conhecimento

Base responsável por armazenar conhecimento necessário para apoiar as decisões do sistema.

Fontes possíveis:

* portfólio da Clear IT;
* documentação técnica;
* casos anteriores;
* padrões consultivos;
* conhecimento especializado dos profissionais.

---

### Camada de Saída

Responsável por gerar os resultados esperados.

Saídas previstas:

* perguntas contextualizadas;
* identificação de informações ausentes;
* recomendações iniciais;
* resumo executivo;
* geração de follow-up;
* próximos passos.

---

## Tecnologias Previstas

Backend:

* Python
* FastAPI

Camada de Inteligência Artificial:

* OpenAI API
* LangGraph

Banco de Dados:

* PostgreSQL
* Banco vetorial

Possíveis integrações futuras:

* CRM
* Base documental interna
* Sistemas de propostas comerciais

---

## Evolução Técnica Esperada

O sistema inicialmente atuará como assistente de discovery e poderá evoluir progressivamente até se tornar um copiloto inteligente de pré-vendas com maior autonomia de apoio consultivo.
