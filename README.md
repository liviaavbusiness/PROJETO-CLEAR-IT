# PROJETO CLEAR IT - Copiloto Inteligente de Pré-Vendas

Sistema baseado em Inteligência Artificial para estruturar, padronizar e escalar o conhecimento consultivo utilizado no processo de pré-vendas técnicas da Clear IT.

---

# 1. Visão do Projeto

A Clear IT atua no mercado corporativo oferecendo soluções especializadas em infraestrutura, nuvem, cibersegurança, observabilidade, automação e serviços gerenciados.

Seu modelo comercial depende fortemente de um processo consultivo técnico, no qual especialistas interpretam necessidades complexas dos clientes e constroem soluções altamente personalizadas.

O objetivo deste projeto é desenvolver um sistema inteligente capaz de apoiar esse processo, transformando conhecimento técnico especializado em um ativo organizacional reutilizável, padronizado e escalável.

Mais do que automatizar tarefas, a proposta busca estruturar inteligência consultiva hoje concentrada em pessoas específicas dentro da empresa.

---

# 2. Problema de Negócio

Atualmente, grande parte da qualidade do processo de pré-vendas depende diretamente da experiência individual dos especialistas técnicos responsáveis por interpretar demandas e desenhar soluções adequadas para cada cliente.

Esse cenário gera dependência operacional sobre profissionais específicos e dificulta a escalabilidade do processo consultivo.

Principais consequências identificadas:

* dependência excessiva de especialistas seniores;
* baixa padronização entre diferentes processos de pré-vendas;
* retrabalho causado por levantamentos incompletos;
* inconsistência na coleta de requisitos técnicos e de negócio;
* aumento no tempo necessário para construção de propostas;
* dificuldade de transferência de conhecimento para novos profissionais.

Hoje, parte do conhecimento mais estratégico da empresa encontra-se distribuído entre especialistas e não estruturado como processo organizacional.

---

# 3. Público Estratégico

## Usuários Diretos

Profissionais que conduzem ou participam diretamente do processo de pré-vendas.

* equipe de pré-vendas;
* engenheiros de solução;
* arquitetos de solução;
* especialistas técnicos consultivos.

---

## Usuários Indiretos

Profissionais impactados pela qualidade do processo comercial e técnico.

* equipe comercial;
* lideranças técnicas;
* equipe de operações;
* gestores comerciais.

---

## Cliente Final Atendido pela Clear IT

A empresa atende organizações privadas que operam ambientes tecnológicos críticos e dependem de infraestrutura robusta, segurança digital, disponibilidade contínua e evolução tecnológica.

Perfis recorrentes:

* grandes empresas;
* indústrias;
* hospitais;
* instituições financeiras;
* varejo;
* empresas com operações críticas.

---

# 4. Dor do Cliente Atendido pela Clear IT

Os clientes da Clear IT normalmente não chegam apresentando uma solução desejada.

Na maioria dos casos, apresentam sintomas ou problemas de negócio que precisam ser interpretados tecnicamente.

Principais dores observadas:

* ambientes com baixa escalabilidade;
* infraestrutura crítica suscetível a falhas;
* baixa maturidade em cibersegurança;
* dificuldade em monitorar ambientes complexos;
* vulnerabilidades operacionais;
* baixa capacidade de resposta a incidentes;
* riscos relacionados à indisponibilidade de sistemas;
* dificuldade em modernizar ambientes legados;
* necessidade de automação operacional.

O papel consultivo da Clear IT consiste justamente em interpretar esse cenário e transformar a necessidade empresarial em solução tecnológica adequada.

---

# 5. Objetivo do Projeto

Construir um sistema inteligente capaz de reproduzir parte do raciocínio consultivo utilizado pelos especialistas da Clear IT durante o processo de análise inicial de oportunidades comerciais.

O sistema deverá apoiar profissionais de pré-vendas durante a interpretação da necessidade do cliente, auxiliando na construção de diagnósticos mais completos e reduzindo dependência operacional sobre especialistas específicos.

O objetivo não é substituir especialistas humanos.

O objetivo é estruturar inteligência consultiva e ampliar capacidade operacional da empresa.

---

# 6. MVP Definido

O MVP será um **Agente Inteligente de Pré-Vendas Consultivas**, responsável por apoiar a análise inicial de oportunidades comerciais através da simulação parcial do raciocínio normalmente utilizado pelos especialistas da Clear IT.

O sistema deverá receber informações iniciais sobre a necessidade apresentada pelo cliente e conduzir uma análise consultiva estruturada.

Fluxo esperado de funcionamento:

Receber contexto inicial da oportunidade > Interpretar qual necessidade o cliente está apresentando > Identificar qual problema empresarial existe por trás da demanda inicial > Classificar qual domínio tecnológico está envolvido > Consultar base de conhecimento da Clear IT > Identificar informações ausentes importantes para o diagnóstico > Gerar perguntas contextualizadas para aprofundamento consultivo > Relacionar necessidade ao portfólio da empresa > Estruturar hipótese inicial de solução > Gerar resumo consultivo para apoio à equipe de pré-vendas.

---

# 7. Capacidades Obrigatórias do MVP

O sistema deverá ser capaz de:

* interpretar o contexto inicial apresentado pelo cliente;
* identificar a dor real por trás da demanda inicial;
* compreender o cenário empresarial apresentado;
* detectar lacunas de informação relevantes;
* sugerir perguntas consultivas contextualizadas;
* relacionar necessidades ao portfólio da Clear IT;
* identificar possíveis caminhos de solução;
* estruturar um resumo consultivo inicial;
* apoiar profissionais menos experientes durante o discovery.

---

# 8. Escopo Fora do MVP

Nesta primeira versão, o sistema não terá como objetivo:

* gerar proposta comercial completa;
* substituir especialistas técnicos;
* definir arquitetura técnica final;
* gerar orçamento financeiro;
* automatizar negociação comercial;
* tomar decisões finais sobre recomendação técnica.

O foco inicial será estruturar inteligência consultiva durante a fase inicial da pré-venda.

---

# 9. Portfólio de Soluções da Clear IT

O sistema deverá compreender o portfólio atual da empresa para relacionar corretamente problemas identificados às possíveis soluções existentes.

Áreas estratégicas:

## Infraestrutura e Nuvem

* estratégia de adoção em nuvem;
* resiliência de dados;
* armazenamento corporativo;
* ambientes híbridos;
* comunicação entre campus e datacenter;
* infraestrutura para inteligência artificial.

---

## Cibersegurança

* proteção de perímetro;
* proteção de dispositivos;
* proteção de identidade;
* gestão de vulnerabilidades;
* microsegmentação;
* conscientização e simulações.

---

## Centro de Operações de Segurança

* gestão de logs e eventos;
* monitoramento contínuo;
* análise comportamental;
* inteligência de ameaças em tempo real;
* automação e resposta a incidentes.

---

## Centro de Operações Cognitivas

* observabilidade de infraestrutura;
* automação operacional;
* análise preditiva;
* dashboards gerenciais;
* recomendações de evolução tecnológica.

---

# 10. Métricas de Sucesso

Indicadores esperados após implementação.

* redução do retrabalho técnico;
* redução do tempo de análise inicial;
* aumento da qualidade dos briefings recebidos;
* menor dependência operacional de especialistas específicos;
* maior padronização entre diferentes profissionais;
* aceleração no processo de construção das propostas.

---

# Estado Atual do Projeto

Sprint 1 — Descoberta e Estruturação Estratégica

Status atual:

* entendimento do desafio concluído;
* problema central identificado;
* público estratégico mapeado;
* dores do cliente documentadas;
* MVP definido conceitualmente;
* perguntas de validação preparadas;
* arquitetura técnica ainda não iniciada.

---

Projeto desenvolvido pela equipe STACK 5 durante o desafio proposto pela Clear IT.
