<div align="center" width="100%">
  <img src="https://i.imgur.com/Z3Dygty.png" alt="purecore.codes" />
</div>

A **purecore** nasceu da necessidade prática de construir as ferramentas que eu mesmo uso, de forma **nativa, controlada e sem dependências externas**.

O primeiro exemplo disso foi a criação de uma biblioteca compatível com o Express, mas com implementação própria: ao migrar de `express` para `@purecore/apify`, a única mudança necessária foi o `import`.
Para validar, utilizei a `helmet` como referência de comportamento — e funcionou de primeira.

Como a biblioteca era simples, optei por reimplementar suas funcionalidades e **eliminar a dependência externa**. A partir daí, estabeleci um princípio:

> **Todos os projetos da purecore devem ser dependency-free.**

Isso resolve três problemas reais:

* Conflitos de versão entre bibliotecas
* Fragilidade causada por supply chain attacks
* Dependência de decisões externas para manter meu próprio sistema funcionando

Além disso, já existia um gerenciador de pacotes próprio para Bun, que:

* Salva dependências localmente
* Cria links simbólicos para `node_modules`
* Evita downloads repetidos
* Garante reprodutibilidade

Com isso, a purecore evoluiu para um ecossistema onde:

* Cada módulo é autocontido
* O comportamento é previsível
* A superfície de falha é mínima
* A evolução é arquitetural, não acidental

---

# Áreas de Pesquisa e Desenvolvimento

## FullAgenticStack

Ao perceber que eu já utilizava agentes no:

* Front-end
* Back-end
* Banco de dados
* Infraestrutura

surgiu um termo semanticamente preciso: **FullAgenticStack**.

Derivações usadas:

* FAS System
* FAS-driven development
* FAS Dev

A proposta é tratar **agentes como unidades arquiteturais**, não apenas como features.

---

## UI / UX

* Agentic UX
* Adaptive UX
* Progressive Disclosure

Interfaces que:

* Reagem ao contexto
* Evoluem com o usuário
* Exibem apenas o necessário

---

## React / Tailwind

* ComponentFactory via config/preset
* ThemeFactory via config/preset
* Behavior Animations

UI declarada por configuração, não por repetição manual.

---

## Natural Language

* **CogGate** — Cognitive Gateway para sistemas legados *(em desenvolvimento)*
* NLToolFactory
* NLAgentConfig
* WhatsApp Chatbots
* E-commerce conversacional
* Agentes Web conversacionais
* Análise prosódica

---

## Modelagem Comportamental

* BehaviorID
* Estados Cognitivos
* Transições Cognitivas
* Next Best Action

Modelar **comportamento como sistema**, não como regra isolada.

---

## Cognitive AI

Pesquisa em sistemas cognitivos aplicados à arquitetura de software.

---

## Memória para IA

Estruturas de memória para agentes:

* Persistentes
* Observáveis
* Evolutivas

---

## Multi-Agents

* Reinforcement Learning
* Deep RL
* Ensemble Learning

### Atomic Behavior Agents

Agentes pequenos, verificáveis e composicionais.

---

## Arquiteturas

* Self-driven systems
* Self-healing systems
* Agentic MCP-driven development
* Aspect Async Multi-Agent Event-driven Development

---

## Comunicação

* Orquestração
* Coreografia
* Sync / Async

---

## Bancos de Dados

* Reactive EntityAgent Data Access Layer

Entidades como agentes ativos, não como registros passivos.

---

## Segurança

* Passwordless
  *(se você ainda usa senha, tenho más notícias)*
* OAuth2.1 com Token Ingestion
* Zero Trust com mTLS

---

```html
<div align="center" width="100%">
  <img src="https://i.imgur.com/rskx8Gw.png" alt="purecore.codes" />
</div>
```
