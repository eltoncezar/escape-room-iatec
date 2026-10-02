---
inclusion: always
---

# Contexto operacional do evento

Este steering descreve **como o escape room será operado na prática**. Sempre que algo nos
docs conflitar com o que está aqui, **este arquivo manda** — os docs de design (`docs/*.md`)
descrevem a experiência; este arquivo descreve a operação do dia.

## Identidade (oficial)

- **Nome:** Protocolo de Contenção
- **Slogan:** *A ameaça veio de dentro. O tempo está correndo.*

> Nome definitivo da atração (substitui o antigo "Código Vermelho"). Direção de arte e
> prompts de IA para logo/divulgação em `docs/06-identidade-visual.md`.

## O dia

| Item                 | Definição                                                              |
| -------------------- | ---------------------------------------------------------------------- |
| **Data**             | **19/10** — Dia do Profissional de T.I. (dentro da programação do dia) |
| **Janela**           | **8:30 às 16:30**                                                      |
| **Ciclo por equipe** | **30 min de jogo + 10 min de reset** = 40 min por slot                 |
| **Inscrição**        | Participantes **se inscrevem e agendam um horário** para participar    |
| **Operação**         | **Dobrada** — duas alas rodando em paralelo, **duas equipes de GM**    |

> Objetivo da operação dobrada: atender todo mundo ao longo do dia. Com duas alas em paralelo
> e slots de 40 min, dá para rodar o dia inteiro sem gargalo.

## Grade de horários (concreta)

A janela de **8:30–16:30** (8 h = 480 min) é dividida em **slots de 40 min** (30 de jogo + 10
de reset), com **1 h de almoço** no meio. Isso dá **10 slots no dia**. Como as **duas alas**
rodam em paralelo, **cada slot atende 2 equipes** (uma na Ala B, uma na Ala C).

**Capacidade do dia:** 10 slots × 2 alas = **20 equipes** = **120 participantes** (6 por equipe).

| Slot | Jogo            | Reset       | Observação      |
| ---- | --------------- | ----------- | --------------- |
| 1    | 08:30–09:00     | 09:00–09:10 | abertura        |
| 2    | 09:10–09:40     | 09:40–09:50 |                 |
| 3    | 09:50–10:20     | 10:20–10:30 |                 |
| 4    | 10:30–11:00     | 11:00–11:10 |                 |
| 5    | 11:10–11:40     | 11:40–11:50 |                 |
| 6    | 11:50–12:20     | 12:20–12:30 | último da manhã |
| —    | **12:30–13:30** | —           | **almoço**      |
| 7    | 13:30–14:00     | 14:00–14:10 | retomada        |
| 8    | 14:10–14:40     | 14:40–14:50 |                 |
| 9    | 14:50–15:20     | 15:20–15:30 |                 |
| 10   | 15:30–16:00     | 16:00–16:10 | último do dia   |

> Sobra uma folga de **16:10–16:30** no fim: use para **premiação**, fotos finais e um
> respiro. **Não** encaixe um 11º slot aí — ele estouraria a janela (jogo iria até 16:40).

**Regras da grade:**
- Chame a próxima equipe **durante o reset** da anterior, para o salão começar pontualmente.
- Um slot estourado **empurra todos os seguintes** — por isso o teto rígido de **30 min de
  jogo**: ver os gatilhos de dica no `docs/04` para fechar perto dos ~28–30 min.
- As duas alas devem andar **em sincronia** (mesmo horário de início por slot) para o placar
  comparar tempos de forma justa.
- Se precisar de **menos** equipes (inscrições abaixo de 20), tire slots **das pontas** (o 1 e
  o 10) ou aumente o buffer — não encurte o jogo.

## Equipe

- **6 pessoas por equipe.**
- **4 ficam no salão** (sala da equipe, 2º andar).
- **2 descem para a sala de desarme** (térreo): o **desarmador** (opera o notebook/bomba) e um
  **ajudante** (resolve os puzzles do térreo, cruza o serial, lê etiquetas). Antes era 1 pessoa
  sozinha; agora são 2 — ajuste papéis e roteiro de acordo.

## Alas (duas em paralelo)

Cada ala é um fluxo completo e independente: um salão (equipe de 4) + uma sala de desarme
(dupla do térreo).

| Ala       | Salão (equipe de 4)     | Sala de desarme (dupla)                                                                                          |
| --------- | ----------------------- | ---------------------------------------------------------------------------------------------------------------- |
| **Ala B** | **Sala de reuniões 1B** | **"Calabouço"** — sala pequena, sem janelas, sem número                                                          |
| **Ala C** | **Sala de reuniões 1C** | **Sala sem nome ao lado da sala do pastor** — reunião desocupada usada pelo suporte p/ guardar notebooks antigos |

> O "Calabouço" é um apelido carinhoso, não um nome oficial. A sala da Ala C também não tem
> nome oficial; nos docs refira a ela como "sala de desarme da Ala C".

## Nomenclatura nos docs

Para não duplicar os puzzles e o roteiro por ala, os docs usam **termos genéricos**:

- **"Salão"** = sala da equipe de 4 (2º andar) → fisicamente **1B** (Ala B) ou **1C** (Ala C).
- **"Sala de desarme"** = sala da dupla do térreo → fisicamente **Calabouço** (Ala B) ou
  **sala ao lado da sala do pastor** (Ala C).

Evite escrever "Sala 1" / "Sala 2" sem qualificar: com duas alas isso fica ambíguo. Prefira
"Salão" e "Sala de desarme", e cite a ala quando a distinção importar.

## Implicações para materiais e reset

- **Tudo dobrado:** dois conjuntos completos de puzzles, **duas malas por ala** (uma para o
  GATE/P4, uma para a "maleta de evidências"), dois jogos de rádios (canais separados por ala
  para não haver interferência), KTANE preparado nas duas salas de desarme.
- **Cofre fora do caminho crítico:** só existe **1 cofre** e precisamos de duas alas, então o
  cofre **não entra no fluxo da sala**. No lugar dele, cada salão usa uma **mala com combinação
  numérica** (a "maleta de evidências") que guarda a Metade 2 da senha + o Serial. Mesma
  mecânica: a combinação de 4 dígitos vem do térreo (T1) **por rádio**. Isso preserva a
  dependência salão↔térreo.
- **O cofre, porém, não foi descartado:** ele é reaproveitado como **meta-jogo da Premiação 2**
  (premiação bônus, fora do relógio) — ver seção "Meta-jogo do cofre" e `docs/07`.
- **Kit de reset: 1 por sala** (ou seja, 4 kits — 2 salões + 2 salas de desarme).
- **Troque os valores de senha/combinação** (e, idealmente, use valores diferentes por ala)
  antes de operar — o repositório pode ter sido lido por participantes.
- **Reset em 10 min** é a restrição apertada do dia: priorize peças print-in-place e kits
  pré-montados para caber na janela.

## Placar e premiações

Há **duas premiações independentes**:

- **Premiação 1 — Velocidade (principal):** por **menor tempo** no fim do dia (modo Zen). O
  placar registra a **ala** de cada equipe, mas o ranking é **único/global** (as duas alas
  competem no mesmo placar). Mantenha a config da bomba e o início do timer **idênticos nas
  duas alas** para o ranking ser justo.
- **Premiação 2 — Cofre (bônus):** meta-jogo opcional com o cofre de dial único. Detalhes,
  regras e os pontos em aberto em `docs/07-meta-jogo-cofre.md`.

## Meta-jogo do cofre (premiação bônus)

- Só existe **1 cofre**. Em vez de usá-lo no fluxo da sala, ele vira uma **premiação bônus
  separada**, **fora do caminho crítico**. A **maleta de evidências** (ex-cofre) **continua**
  no fluxo da bomba — o cofre é peça **nova e paralela**, não a substitui.
- A combinação do cofre (de dial) é fatiada em **N etapas** (nº **a definir**) e espalhada pela
  sala como pistas que **parecem red herring**. A sala é 100% resolvível sem tocar nelas.
- **Abertura na premiação:** evento sequencial fora do relógio; ordem de tentativa = **ranking
  de velocidade**; **o primeiro que abrir leva** (abriu, acabou).
- **Incentivo do RH (diversidade de departamentos):** equipes com mais verticais distintas
  ganham vantagem **só no cofre** (nunca na Premiação 1) — dicas grátis ou etapas reveladas,
  definidas **no credenciamento**. A **escala é provisória** (ver `docs/07`).

> **A definir antes de operar:** (1) o número de etapas da combinação; (2) a escala de vantagem
> por diversidade. Trate ambos como abertos até o RH/organização fechar.
