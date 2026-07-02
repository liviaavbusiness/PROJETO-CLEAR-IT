# Regras de Negócio - MVP Copiloto Inteligente de Pré-Vendas

Este documento define as regras de negócio que delimitam o comportamento esperado do sistema durante o funcionamento do MVP.

As regras estabelecem restrições, limites operacionais e princípios obrigatórios que devem ser respeitados durante o desenvolvimento da solução.

O objetivo é garantir que o sistema atue como apoio consultivo ao processo de pré-vendas sem ultrapassar limites técnicos, comerciais ou estratégicos definidos pela Clear IT.

---

# Princípio Central do Produto

O sistema proposto não tem como objetivo substituir especialistas técnicos da Clear IT.

Seu papel consiste em apoiar o processo de pré-vendas, transformar conhecimento consultivo em inteligência reutilizável e reduzir dependência excessiva de conhecimento individual concentrado em profissionais específicos.

Toda decisão final continua sendo responsabilidade humana.

---

# Regras de Negócio

| Código | Regra |
|----------|----------|
| RN01 | O sistema deve atuar exclusivamente como ferramenta de apoio à equipe de pré-vendas e nunca substituir a validação humana realizada por especialistas técnicos. |
| RN02 | Toda recomendação gerada pelo sistema deve ser tratada como hipótese inicial e não como decisão técnica definitiva. |
| RN03 | O sistema deve sempre interpretar primeiro o problema empresarial do cliente antes de associar qualquer solução tecnológica. |
| RN04 | O sistema não pode recomendar soluções fora do portfólio oficial da Clear IT. |
| RN05 | Antes de sugerir qualquer caminho técnico, o sistema deve consultar a base de conhecimento interna construída a partir do conhecimento dos especialistas. |
| RN06 | O sistema deve identificar informações ausentes antes de construir qualquer hipótese de solução. |
| RN07 | O sistema deve priorizar perguntas consultivas que aprofundem o entendimento do problema antes de avançar para recomendações. |
| RN08 | O sistema não pode gerar propostas comerciais finais ou valores financeiros durante o MVP. |
| RN09 | O sistema não pode definir arquitetura técnica final sem validação posterior de especialistas humanos. |
| RN10 | O sistema deve preservar o modelo consultivo da Clear IT, respeitando o fato de que clientes corporativos não compram produtos isolados, mas soluções completas adaptadas ao seu contexto específico. |

---

# Regras Relacionadas ao Portfólio da Empresa

As recomendações produzidas pelo sistema devem estar limitadas às áreas de atuação oficiais da Clear IT.

Domínios permitidos:

### Infraestrutura e Nuvem

- Estratégia de adoção em nuvem
- Resiliência de dados
- Comunicação entre ambientes corporativos
- Inteligência Artificial
- Observabilidade de aplicações

### Cibersegurança

- Proteção de perímetro
- Proteção de dispositivos
- Proteção de identidade
- Gestão de vulnerabilidades
- Microsegmentação
- Conscientização e simulações de segurança

### Centro de Operações de Segurança

- Gestão de logs e eventos
- Monitoramento contínuo de ameaças
- Análise comportamental
- Orquestração e automação de segurança
- Inteligência Artificial aplicada à segurança

### Centro de Operações Cognitivas

- Observabilidade de infraestrutura
- Dashboards gerenciais
- Automação operacional
- Análise preditiva com Inteligência Artificial
- Resposta automatizada a incidentes
- Recomendações de evolução operacional

### Serviços Gerenciados

- Monitoramento contínuo 24x7x365
- Gestão proativa de infraestrutura
- Detecção de vulnerabilidades
- Resposta a incidentes
- Serviços contínuos especializados

---

# Restrições Técnicas do MVP

Durante a primeira versão do produto, o sistema não deve executar atividades fora do escopo definido.

Não faz parte do MVP:

- gerar propostas comerciais completas;
- definir orçamento financeiro;
- substituir especialistas humanos;
- gerar arquitetura técnica final;
- automatizar negociação comercial;
- realizar integrações com sistemas internos produtivos;
- enviar propostas diretamente ao cliente.

---

# Regras de Segurança e Compliance

O sistema deverá respeitar princípios mínimos de segurança e proteção de dados.

### Regras obrigatórias

- Nenhum dado sensível do cliente poderá ser exposto externamente.
- Informações processadas devem seguir conformidade com LGPD.
- O sistema não poderá armazenar dados sem controle de acesso.
- Dados estratégicos fornecidos pelos clientes devem ser tratados de forma segura.
- O sistema deve manter rastreabilidade mínima das análises realizadas.

---

# Papel Estratégico do Produto

O MVP existe para resolver um problema interno da Clear IT.

Problema central:

O conhecimento consultivo necessário para conduzir pré-vendas complexas encontra-se concentrado em especialistas específicos, dificultando escala operacional, padronização e eficiência do processo comercial.

O sistema deverá transformar esse conhecimento em um processo estruturado, reutilizável e escalável.

---

# Objetivo Final

Criar uma Inteligência Artificial capaz de replicar parte do raciocínio consultivo utilizado por especialistas da Clear IT, permitindo que equipes de pré-vendas conduzam processos mais consistentes, completos e estratégicos, reduzindo retrabalho e dependência operacional.
