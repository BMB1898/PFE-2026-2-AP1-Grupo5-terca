# 📋 Documentação Scrum: PKZ & One to One (Grupo 5)

> Documentação montada a partir do histórico de commits do repositório `PFE-2026-2-AP1-Grupo5-terca`.
>
> **Premissas:**
> - **Sprints semanais.** Os commits se concentram em quatro semanas de setembro/2026, então cada semana virou uma Sprint.
> - **Papéis de Scrum.** Scrum Master: Bernardo Machado Borghetti.
> - **Pontos de estória.** O histórico não tem estimativas, então as métricas contam só commits e arquivos.

---

## Visão geral do Product Backlog

| ID | Item do Product Backlog | Sprint |
|---|---|---|
| PB-01 | Configurar o repositório do projeto | 1 |
| PB-02 | Mapa mental do escopo | 1 (refinado nas Sprints 3 e 4) |
| PB-03 | Planejamento 5W2H | 2 (ajustado na 4) |
| PB-04 | Árvore Hierárquica de Tarefas (AHT) | 2 (ajustada na 4) |
| PB-05 | Documento de Visão | 2 |
| PB-06 | Brainstorm: problema, ideias e proposta final | 2 (v2 na 3, v3 na 4) |
| PB-07 | Protótipo de alta fidelidade no Figma | 4 |
| PB-08 | Telas dos portais (Aluno One to One / Aluno PKZ Lab) | 4 |
| PB-09 | README completo do projeto | 4 |
| PB-10 | Transcrições e resumo das reuniões com o cliente | 4 |

---

## 🏁 Sprint 1: Kickoff e concepção inicial

**Período:** 01/09/2026 a 07/09/2026 (commits em 03/09)

### 🎯 Objetivo da Sprint

Criar a base do projeto e ter uma primeira visão do escopo por meio de um mapa mental.

### 📝 Sprint Backlog

| Item | Descrição | Responsável | Commit | Status |
|---|---|---|---|---|
| PB-01 | Criar o repositório e o README inicial | BMB1898 | `5c05780` Initial commit | ✅ Concluído |
| PB-02 | Mapa mental com a visão geral do projeto | BernardoBorghetti | `b6f509d` Mindmap | ✅ Concluído |

### 📦 Incremento

- Repositório `PFE-2026-2-AP1-Grupo5-terca` criado com README.
- `Mindmap/MindMap-G5.jpg`: primeiro mapa mental dos serviços PKZ e One to One.

### 🔎 Sprint Review

A equipe chegou a um entendimento inicial do cliente (Playmakerz) e dos dois serviços que o site vai divulgar. O mapa mental serve de ponto de partida para o planejamento formal.

### 🔁 Retrospectiva

- **Foi bem:** o repositório e o primeiro artefato ficaram prontos no mesmo dia.
- **Melhorar:** só 2 dos integrantes contribuíram. É preciso dividir melhor as tarefas.
- **Ação:** na próxima Sprint, dar um artefato de planejamento para cada integrante.

**Métricas:** 2 commits · 2 arquivos criados · 2 contribuidores

---

## 🧭 Sprint 2: Planejamento e definição do produto

**Período:** 08/09/2026 a 14/09/2026 (commits em 09, 10 e 12/09)

### 🎯 Objetivo da Sprint

Formalizar o planejamento e a visão do produto: por que o site existe, para quem ele é, o que ele faz e como o usuário navega.

### 📝 Sprint Backlog

| Item | Descrição | Responsável | Commit | Data | Status |
|---|---|---|---|---|---|
| PB-03 | Planejamento 5W2H (o que, por que, quem, onde, quando, como, quanto) | Giovanni | `9ed635a` 5w2h | 09/09 | ✅ Concluído |
| PB-04 | AHT em PlantUML (fluxo Landing, One to One, PKZ, Planos, Agendar, Cadastro, Portal) | João Enes | `9b7dc83` AHT | 09/09 | ✅ Concluído |
| PB-04 | Imagem renderizada da AHT | BernardoBorghetti | `a0334cc` AHT-com_imagem | 09/09 | ✅ Concluído |
| PB-05 | Documento de Visão (objetivo, escopo, stakeholders, requisitos, restrições, riscos) | BernardoParrilha | `709d8a1` Doc_visao | 10/09 | ✅ Concluído |
| PB-06 | Brainstorm: problema, geração de ideias e proposta de arquitetura | Rafael Castro | `8cb6e11` Brainstorm | 12/09 | ✅ Concluído |

### 📦 Incremento

- **5W2H:** plataforma web de divulgação, custo zero, com GitHub, Figma, HTML/CSS e VS Code, e entrega no fim do semestre.
- **Documento de Visão:**
  - Requisitos funcionais: navegação simples e apresentação dos serviços.
  - Requisitos não funcionais: desempenho, compatibilidade, disponibilidade e acessibilidade.
  - Restrição principal: não haverá back-end.
- **AHT:** jornada completa do usuário, com os ramos One to One, PKZ, Planos, Agendamento, Cadastro e Portal (Adulto/Atleta).
- **Brainstorm:**
  - Problemas identificados: falta de autoridade, perda de leads, conflito de personas e jornadas desarticuladas.
  - Proposta de arquitetura com 8 páginas.

### 🔎 Sprint Review

Sprint mais produtiva em diversidade de contribuições: 5 integrantes entregaram artefatos. O produto está bem definido e as páginas e o funil de leads (aula experimental) estão claros.

### 🔁 Retrospectiva

- **Foi bem:** o trabalho foi bem dividido e todos os artefatos de planejamento ficaram prontos.
- **Melhorar:** os artefatos foram feitos em paralelo e podem ter inconsistências entre si (por exemplo, o escopo do Doc de Visão é mais enxuto que a arquitetura do Brainstorm).
- **Ação:** na próxima Sprint, revisar e alinhar os documentos entre si.

**Métricas:** 5 commits · 5 arquivos criados · 5 contribuidores

---

## 🔧 Sprint 3: Refinamento dos artefatos

**Período:** 15/09/2026 a 21/09/2026 (commits em 18/09)

### 🎯 Objetivo da Sprint

Revisar e alinhar o Brainstorm e o Mapa Mental com as definições da Sprint anterior.

### 📝 Sprint Backlog

| Item | Descrição | Responsável | Commit | Status |
|---|---|---|---|---|
| PB-06 | Revisar o Brainstorm (v2) | BernardoBorghetti | `8dd3001` Doc_visao-v2 / `fc1479c` Brainstorm-v2 | ✅ Concluído |
| PB-05 | Revisar o Documento de Visão (v2) | BernardoBorghetti | `8dd3001` | ✅ Concluído |
| PB-02 | Atualizar o Mapa Mental | SkyeMel26 | `4189116` alteração do mindmap | ✅ Concluído |

### 📦 Incremento

- `Brainstorm/brainstorm.md` refinado em duas iterações.
- O mapa mental original foi trocado por uma nova versão (`Screenshot 2026-09-18 170826.png`).

### 🔎 Sprint Review

O Brainstorm ficou mais maduro, com problema, ideias e proposta final mais claros. O mapa mental ganhou uma nova versão, alinhada à arquitetura proposta.

### 🔁 Retrospectiva

- **Foi bem:** a equipe revisou os artefatos em vez de só criar novos.
- **Melhorar:**
  - O commit `Doc_visao-v2` alterou só o `brainstorm.md`. A revisão do Documento de Visão não entrou no repositório, e isso mostra uma falha na nomeação e conferência dos commits.
  - O novo mapa mental foi salvo com um nome genérico ("Screenshot…").
- **Ação:** conferir os arquivos antes de cada commit e adotar nomes de arquivo padronizados.

**Métricas:** 3 commits · 2 arquivos alterados · 2 contribuidores

---

## 🎨 Sprint 4: Consolidação, prototipação e entrega

**Período:** 22/09/2026 a 28/09/2026 (commits em 27 e 28/09)

### 🎯 Objetivo da Sprint

Fechar a documentação, construir o protótipo de alta fidelidade no Figma, documentar o projeto no README e registrar as reuniões com o cliente.

### 📝 Sprint Backlog

**Parte A: ajustes finais da documentação (27/09)**

| Item | Descrição | Responsável | Commit | Status |
|---|---|---|---|---|
| PB-03 / PB-06 / PB-02 | Ajustes no 5W2H e no Brainstorm, e volta do mapa mental com nome padronizado | BernardoBorghetti | `7020625` Ajustes_Pontuais | ✅ Concluído |
| PB-06 | Brainstorm v3 (versão final, com Planos, Agendamento, Cadastro e Portais) | BernardoBorghetti | `634ee91` Brainstorm-v3 | ✅ Concluído |
| PB-04 | AHT atualizada (PlantUML + imagem em PNG) | SkyeMel | `20960c2` alteração uml | ✅ Concluído |

**Parte B: prototipação e entrega (28/09)**

| Item | Descrição | Responsável | Commit | Status |
|---|---|---|---|---|
| PB-02 | Mapa mental final (`MindMap-G5-atualizado.png`) | SkyeMel | `d315384` | ✅ Concluído |
| PB-07 | Link do protótipo no Figma | SkyeMel | `0e25790` link do figma | ✅ Concluído |
| PB-07 | Protótipo v1 (5 telas) | SkyeMel | `807a3e4` prototipo-v1 | ✅ Concluído |
| PB-07 | Protótipo atualizado (8 telas: Landing, PKZ, One to One, Planos, Agendamento, Cadastro, Portal Aluno, Portal Atleta) | SkyeMel | `ce209a1` | ✅ Concluído |
| PB-09 | README v1 e v1.1 (problema, solução, tabela de páginas, galeria do protótipo, estrutura) | BernardoBorghetti | `a459e47`, `ff63308` | ✅ Concluído |
| PB-08 | Telas do Portal Aluno One to One (8 telas) | SkyeMel | `c252a26` | ✅ Concluído |
| PB-08 | Telas do Portal Aluno PKZ Lab (8 telas) | Rafael Castro | `12fc813` | ✅ Concluído |
| — | Organizar as pastas do protótipo (`PortalAluno1to1/`, `PortalAlunopkz/`) | SkyeMel | `342f7df`, `dc7d82b` | ✅ Concluído |
| PB-10 | Transcrições das reuniões com o cliente e resumo em forma de guia do site | Giovanni | `f6d9f7b` | ✅ Concluído |

### 📦 Incremento

- **Documentação final:** 5W2H, Brainstorm v3, AHT (PUML + PNG) e Mapa Mental atualizado.
- **Protótipo no Figma:**
  - 8 páginas principais.
  - 16 telas de portais logados: 8 do One to One e 8 do PKZ Lab.
- **README:** apresentação completa do projeto, com problema, solução, tabela de páginas, galeria de telas e estrutura do repositório.
- **Registro do cliente:** transcrições de 2 reuniões (a de briefing com Henrique, Pedro e Eduardo, e a de construção do site) e um `Resumo.md` que funciona como guia do site.
  - O guia cobre sitemap, textos, FAQ, estratégia de preço, direção visual, requisitos do portal e pontos em aberto.

### 🔎 Sprint Review

Maior Sprint em volume de entregas. O projeto passou da fase de documentação para um protótipo navegável, que cobre toda a jornada prevista na AHT, incluindo as áreas logadas. O README deixa o repositório pronto para apresentação. O resumo das reuniões dá a base de conteúdo para a fase de codificação em HTML/CSS.

### 🔁 Retrospectiva

- **Foi bem:**
  - O protótipo ficou completo e coerente com a AHT e o Brainstorm.
  - O README ficou profissional.
  - As reuniões com o cliente foram registradas.
- **Melhorar:**
  - O trabalho se concentrou no fim da Sprint: 16 commits em 2 dias, com vários deles entre 20h e 22h de 28/09.
  - O mapa mental foi substituído 3 vezes (18/09, 27/09 e 28/09).
  - As pastas foram reorganizadas várias vezes depois dos uploads (`PortalAlunopkz` foi criada dentro de `PortalAluno1to1` e depois movida).
  - As transcrições das reuniões só entraram no repositório no fim, embora devessem guiar o protótipo.
- **Ação para a próxima Sprint:**
  - Combinar a estrutura de pastas antes de subir arquivos.
  - Distribuir os commits ao longo da Sprint.
  - Resolver os "pontos em aberto" do `Resumo.md` com o cliente antes de começar a codificação.
  - Revisar o Documento de Visão, que não foi atualizado desde 10/09, para refletir o escopo final (cadastro, portais, planos).

**Métricas:** 16 commits · ~40 arquivos adicionados, alterados ou movidos · 4 contribuidores

---

## 📊 Resumo geral

| Sprint | Período | Foco | Commits | Contribuidores |
|---|---|---|---|---|
| 1 | 01 a 07/09 | Kickoff e mapa mental | 2 | 2 |
| 2 | 08 a 14/09 | Planejamento (5W2H, AHT, Visão, Brainstorm) | 5 | 5 |
| 3 | 15 a 21/09 | Refinamento | 3 | 2 |
| 4 | 22 a 28/09 | Consolidação, protótipo, README e reuniões | 16 | 4 |
