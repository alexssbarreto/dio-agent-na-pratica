# DIO Agent na Prática

Desafio de Projeto da [DIO](https://dio.me): configure o [DIO Agent](https://github.com/digitalinnovationone/dio-agent) e use as skills dele para estudar, praticar e planejar a sua carreira.

## Como fazer

1. Clique em **Use this template** para criar a sua cópia deste repositório.
2. Siga os passos abaixo, copiando cada prompt para o DIO Agent.
3. Preencha a seção [Minha entrega](#minha-entrega) e entregue o link da sua cópia na DIO.

## 1. Configure o DIO Agent

- Instale um harness. Recomendamos o [Google Antigravity](https://antigravity.google/docs), mas qualquer um [da lista do DIO Agent](https://github.com/digitalinnovationone/dio-agent#-comece-em-3-passos) funciona.
- Baixe o [DIO Agent](https://github.com/digitalinnovationone/dio-agent) em **Code**, **Download ZIP**, e extraia.
- No harness, abra a pasta que tem o arquivo `AGENTS.md` e mande:

```
Oi!
Quem é você e como pode me ajudar nos meus estudos na DIO?
```

Se ele se apresentar como DIO Agent, está tudo certo.

## 2. Estudar

Troque o conceito pelo que você quer entender:

```
Me explica o que é uma skill de um agente de IA.
Meu nível: uso IA no dia a dia, mas nunca configurei um agente.
```

## 3. Praticar

Use um desafio em que você travou ou este exemplo:

```
Estou travado em um Desafio de Código da DIO.
O desafio pede a soma de todos os números de 1 até N.
Meu código imprime só o último número, não a soma:
let n = parseInt(gets());
let soma = 0;
for (let i = 1; i <= n; i++) {
  soma = i;
}
print(soma);
Me ajuda a destravar sem dar a resposta pronta.
```

## 4. Planejar

Preencha os colchetes com a sua Trilha:

```
Quero montar um plano de estudos.
Trilha: [link do seu Bootcamp ou Formação]
Objetivo: concluir em [4 semanas].
Meu nível: [iniciante, intermediário ou avançado].
Tempo: [1 hora por dia, de segunda a sexta].
```

## Bônus: seu próximo passo

Se você quer construir com IA:

```
Quero escolher meu próximo passo na Carreira AI Builder.
Quero construir: [um app para os pedidos do meu negócio].
Programação: [nenhuma, o básico ou trabalho com isso].
Objetivo: [tirar uma ideia do papel].
```

---

## Minha entrega

# 🤖 Formação em Engenharia de Agentes de IA

> Trilha prática para aprender a projetar, construir e integrar agentes de IA em produtos e serviços.

## 🎯 Objetivo

Desenvolver capacidade para **analisar problemas reais, projetar arquiteturas de agentes e implementá-los como componentes de software**, utilizando IA para automatizar processos, ampliar produtos existentes e acelerar o desenvolvimento.

O objetivo não é aprender apenas um framework ou construir um chatbot.

A meta é conseguir responder:

> **“Dado este problema de negócio, qual arquitetura de IA resolve isso de forma simples, segura, observável e sustentável?”**

---

## 👨‍💻 Meu contexto

**Nível:** Intermediário / Avançado  
**Perfil:** Desenvolvedor  
**Stack:** PHP, Java, Node.js e Angular  
**Disponibilidade:** 1 hora por dia  
**Frequência:** Segunda a sexta  
**Duração inicial:** 4 semanas  
**Carga:** 20 horas

### Objetivo prático

Aprender a criar agentes que possam ser utilizados como:

- ferramentas de produtos;
- serviços internos;
- APIs;
- automações;
- assistentes especializados;
- componentes de sistemas existentes;
- ferramentas para desenvolvedores;
- soluções de integração entre sistemas.

---

# 🧭 Linhas de atuação

A formação será organizada em **6 linhas principais**.

## 1. 🧠 Fundamentos de IA aplicada a software

### Objetivo

Entender como LLMs podem ser utilizadas dentro de aplicações de software e quais são suas limitações.

### Estudar

- LLMs
- tokens
- contexto
- janela de contexto
- temperatura e parâmetros
- limitações dos modelos
- hallucination
- prompt engineering
- context engineering
- structured outputs
- schemas
- function/tool calling
- embeddings
- modelos de geração e representação

### Pergunta central

> **Como transformar a capacidade de um LLM em uma funcionalidade confiável de software?**

---

# 2. 🔧 Construção de agentes

### Objetivo

Aprender a projetar agentes capazes de **decidir, utilizar ferramentas e executar ações**.

### Estudar

- o que caracteriza um agente
- agent loop
- percepção
- decisão
- planejamento
- execução
- observação
- ferramentas
- tool calling
- estado
- memória
- contexto
- planejamento e execução
- tratamento de erros
- limites de autonomia
- human-in-the-loop
- guardrails

### Modelo mental

```text
Problema
   ↓
Contexto
   ↓
Decisão
   ↓
Ferramenta
   ↓
Execução
   ↓
Observação
   ↓
Nova decisão
```

### Pergunta central

> **O que o agente precisa decidir e quais ações ele realmente pode executar?**

---

# 3. 🏗️ Arquitetura e orquestração

### Objetivo

Aprender a escolher a arquitetura adequada para cada problema.

### Estudar

- LLM simples
- workflow
- agente
- agentes especializados
- multiagentes
- orquestração
- state machines
- workflows determinísticos
- workflows orientados por agentes
- decomposição de tarefas
- comunicação entre agentes
- sincronização
- tratamento de falhas

### Regra

Não usar multiagentes apenas porque é uma tecnologia disponível.

Antes de criar múltiplos agentes, perguntar:

> **Um único agente ou um workflow determinístico resolveria o problema?**

### Comparação

```text
LLM
 ↓
Responde

Workflow
 ↓
Executa etapas conhecidas

Agente
 ↓
Decide quais ações executar

Multiagente
 ↓
Vários agentes especializados colaboram
```

---

# 4. 🔌 Ferramentas, integração e MCP

### Objetivo

Aprender a conectar agentes aos sistemas onde o trabalho realmente acontece.

### Estudar

- APIs
- REST
- funções
- serviços internos
- bancos de dados
- ferramentas de domínio
- autenticação
- autorização
- permissões
- MCP
- servidores MCP
- clientes MCP
- integração com sistemas existentes
- contratos de ferramentas

### Exemplos

Um agente pode:

```text
Consultar cliente
      ↓
Consultar pedidos
      ↓
Analisar situação
      ↓
Executar operação
      ↓
Registrar resultado
```

As ferramentas podem estar implementadas em:

- Java
- Node.js
- PHP
- APIs existentes
- bancos de dados
- serviços externos
- MCP

### Pergunta central

> **Quais capacidades do meu sistema eu quero disponibilizar para o agente?**

---

# 5. 📚 Conhecimento, RAG e contexto

### Objetivo

Aprender a fazer agentes trabalharem com conhecimento externo ao modelo.

### Estudar

- embeddings
- chunking
- vector stores
- similarity search
- retrieval
- RAG
- grounding
- fontes de conhecimento
- contexto dinâmico
- documentos
- bases internas
- atualização do conhecimento

### Arquitetura mental

```text
Usuário
   ↓
Agente
   ↓
Consulta conhecimento
   ↓
Retrieval
   ↓
Contexto relevante
   ↓
LLM
   ↓
Resposta / ação
```

### Pergunta central

> **O agente precisa raciocinar ou precisa primeiro buscar conhecimento?**

---

# 6. 🛡️ Operação, avaliação e produção

### Objetivo

Aprender a transformar um protótipo de agente em um componente confiável de software.

### Estudar

- avaliação de agentes
- testes
- qualidade das respostas
- qualidade das ferramentas
- observabilidade
- logs
- tracing
- métricas
- custos
- latência
- segurança
- controle de acesso
- proteção de dados
- limites de execução
- versionamento
- rollback
- monitoramento
- LLMOps

### Pergunta central

> **Como sei que meu agente funciona e como detecto quando ele começa a falhar?**

---

# 🗺️ Formação em 4 semanas

## Semana 1 — Fundamentos para construção

**Objetivo:** entender os blocos fundamentais.

| Dia | Tema |
|---|---|
| Segunda | LLMs, tokens, contexto e limitações |
| Terça | Prompt Engineering + Context Engineering |
| Quarta | Structured Outputs + Tool Calling |
| Quinta | Embeddings + RAG |
| Sexta | Arquitetura de uma solução de IA |

### Entrega da semana

Desenhar a arquitetura de uma solução de IA aplicada a um problema real.

---

# Semana 2 — Engenharia de agentes

**Objetivo:** construir um agente funcional.

| Dia | Tema |
|---|---|
| Segunda | Arquitetura e Agent Loop |
| Terça | Tools e APIs |
| Quarta | Estado, memória e contexto |
| Quinta | Guardrails + Human-in-the-loop |
| Sexta | Construção de um agente funcional |

### Entrega da semana

Construir um agente que:

- receba um objetivo;
- raciocine sobre o próximo passo;
- utilize pelo menos duas ferramentas;
- observe o resultado;
- continue ou encerre a execução.

---

# Semana 3 — Orquestração e integração

**Objetivo:** aprender a construir arquiteturas de agentes.

| Dia | Tema |
|---|---|
| Segunda | Workflow vs Agent vs Multiagent |
| Terça | Orquestração |
| Quarta | MCP |
| Quinta | Agentes aplicados ao desenvolvimento |
| Sexta | Projeto integrado |

### Entrega da semana

Construir uma solução em que um agente utilize ferramentas reais de um sistema.

Exemplo:

```text
Agente
  ├── API
  ├── Banco de dados
  ├── Serviço externo
  └── Base de conhecimento
```

---

# Semana 4 — Produto e produção

**Objetivo:** transformar conhecimento em uma solução reutilizável.

| Dia | Tema |
|---|---|
| Segunda | Definição do problema e arquitetura |
| Terça | Implementação do agente |
| Quarta | Tools + RAG + MCP |
| Quinta | Avaliação + observabilidade + segurança |
| Sexta | Refatoração + documentação |

### Entrega final

Um **Agente como Serviço**, preparado para evoluir para uma aplicação real.

Arquitetura de referência:

```text
┌──────────────────────┐
│       Angular        │
│          UI          │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│     Java / Node      │
│      API / BFF       │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│ Agent / Orchestrator │
└───────┬───────┬──────┘
        │       │
        ▼       ▼
      LLM     Tools
                │
        ┌───────┼────────┐
        ▼       ▼        ▼
       API      DB      MCP
        │
        ▼
   Sistemas reais
```

---

# 🧪 Estratégia de estudos

Cada sessão de 1 hora seguirá aproximadamente este formato:

### 10 min — Conceito

Entender o fundamento e os trade-offs.

### 40 min — Prática

Implementar ou modificar alguma coisa.

### 10 min — Registro

Responder:

```text
O que aprendi?

O que construí?

O que deu errado?

Quando eu usaria isso em produção?

Qual trade-off encontrei?

O que eu ainda não consigo explicar?
```

---

# 🧩 Stack de laboratório

A stack principal de experimentação será:

### Backend

- Java
- Node.js
- PHP

### Frontend

- Angular

### Integração

- REST APIs
- APIs de terceiros
- bancos de dados
- MCP

### IA

- LLMs
- Tool Calling
- RAG
- Agents
- Orchestration

A escolha do framework será secundária.

O objetivo é aprender **arquitetura e padrões que possam ser transferidos entre tecnologias**.

---

# 🎯 Ordem de prioridade

```text
LLMs
 ↓
Prompt / Context Engineering
 ↓
Structured Output
 ↓
Tool Calling
 ↓
RAG
 ↓
Agents
 ↓
State / Memory
 ↓
Orchestration
 ↓
MCP
 ↓
Multiagents
 ↓
Evaluation
 ↓
Observability
 ↓
Production
```

---

# 🚫 O que não será prioridade inicialmente

Durante as primeiras 20 horas, não aprofundar desnecessariamente em:

- treinamento de modelos;
- matemática de machine learning;
- fine-tuning avançado;
- otimização de modelos;
- infraestrutura especializada de inferência;
- criação de modelos do zero.

Esses assuntos podem entrar posteriormente quando houver uma necessidade concreta do produto.

---

# 🏆 Critério de sucesso

Ao finalizar esta formação, devo conseguir receber um problema como:

> “Precisamos automatizar este processo.”

e conduzir a análise:

```text
1. Qual é o problema?
        ↓
2. Precisa realmente de IA?
        ↓
3. LLM, workflow ou agente?
        ↓
4. O que o agente precisa saber?
        ↓
5. Quais ferramentas precisa utilizar?
        ↓
6. Precisa de RAG?
        ↓
7. Precisa de memória/estado?
        ↓
8. Um ou vários agentes?
        ↓
9. Como controlar suas ações?
        ↓
10. Como avaliar?
        ↓
11. Como observar em produção?
        ↓
12. Como disponibilizar como serviço?
```

---

# 🚀 Projeto final

O projeto final deve ser tratado como **produto**, não apenas como exercício.

Deve possuir:

- problema de negócio definido;
- arquitetura;
- agente;
- ferramentas;
- integração com serviços;
- contexto/conhecimento quando necessário;
- controle de execução;
- tratamento de erros;
- avaliação;
- observabilidade;
- documentação;
- possibilidade de exposição via API.

### Resultado esperado

Construir uma base que possa evoluir para uma **plataforma ou conjunto de serviços de agentes reutilizáveis**.

---

# 📌 Princípio da formação

> **Não quero apenas aprender a usar agentes. Quero aprender a projetá-los.**

Tecnologias e frameworks mudam.

Os princípios que preciso dominar são:

**Problema → Arquitetura → Contexto → Ferramentas → Decisão → Execução → Avaliação → Operação.**

Essa é a base que deverá orientar meus próximos estudos em IA aplicada ao desenvolvimento de software.

_Cole o print do seu plano de estudos._

### Como foi para você

_Conte em poucas linhas como foi usar o DIO Agent pela primeira vez._
