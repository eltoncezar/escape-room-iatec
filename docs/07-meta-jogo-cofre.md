# 07 — Meta-jogo do cofre (premiação bônus)

> **Camada opcional, FORA do caminho crítico.** Nada aqui trava a sala, a bomba ou o placar
> principal. A sala pode ser 100% resolvida sem ninguém tocar no cofre. Este doc descreve uma
> **segunda disputa**, resolvida só no fim do dia, usando um cofre físico que a IATEC já tem.

> ⚠️ **Pontos em aberto (ainda não decididos):**
> - **Número de etapas** da combinação do cofre (o doc usa **N etapas** como exemplo; definir).
> - **Escala de vantagem por diversidade** de departamentos (tabela provisória — ver abaixo).
>
> Tudo que depender desses dois pontos está marcado como provisório. Feche-os antes de operar.

## A ideia em uma frase

O **cofre de dial** (único, de segredo giratório) guarda a **premiação bônus**. A combinação
dele está **fatiada em N etapas** espalhadas pela sala, disfarçadas de red herring. Durante o
jogo ninguém sabe que aquilo abre um cofre — só no fim, na premiação, as equipes tentam abrir.

## Por que isto não quebra o jogo principal

- O cofre do meta-jogo **não é a maleta de evidências.** A **maleta** (ex-cofre) continua no
  caminho crítico guardando Metade 2 + Serial e é essencial para a bomba armar (ver `02-puzzles.md`).
  O **cofre** é uma peça **nova e separada**, puramente opcional.
- As pistas da combinação do cofre **não travam nada**: nem a chave (P4), nem a maleta, nem a
  senha, nem o desarme. Se a equipe ignorar tudo, resolve a sala normalmente.
- O timer e o placar principal (Premiação 1, menor tempo) **não mudam**. O meta-jogo só define
  a **Premiação 2**.

## As duas premiações

| | Premiação 1 — Velocidade | Premiação 2 — Cofre (bônus) |
|---|---|---|
| **Critério** | Menor **tempo ajustado** (modo Zen) | Abrir o cofre de dial no fim do dia |
| **Quando** | Fechamento do dia | Fechamento do dia, após a Premiação 1 |
| **Quantos ganham** | 1 (ranking global, as duas alas juntas) | 1 (o primeiro que conseguir abrir) |
| **Depende do quê** | Desempenho na sala | Pistas da combinação coletadas + sorte/dedução |

> As duas premiações são **independentes**: dá para vencer uma e não a outra. O ranking de
> tempo (Premiação 1) ainda é o "principal"; o cofre é o **bônus** que o RH usa para incentivar
> integração (ver seção de diversidade).

## A combinação em N etapas (cofre de dial)

- É um **cofre de dial** (segredo giratório), não de teclado. A combinação é uma **sequência de
  N etapas**, no formato *"X para a esquerda, Y para a direita, ..."*. Exemplo com N=5:
  `30 ESQ · 15 DIR · 40 ESQ · 5 DIR · 20 ESQ`.
- Cada etapa é revelada por **uma pista** escondida no fluxo da sala. As pistas **parecem
  irrelevantes** durante o jogo (red herring): números soltos, marcações, um detalhe num cartaz.
- **Sem confirmação:** a equipe nunca sabe, durante o jogo, se o que achou está certo nem se
  está completo. Podem terminar com **3 de N** etapas e só descobrir girando o dial na premiação.

> **Por que funciona como meta-jogo:** a ausência de feedback é o charme. Quem foi observador e
> anotou "o que parecia inútil" (mesma lição do P1) chega na premiação com vantagem — mas sem
> certeza. Gera torcida e conversa entre as equipes no fim do dia.

> **Nota de design (a definir):** o **N** ainda não está fechado. Quanto maior o N, mais difícil
> abrir e mais raro alguém levar o bônus; menor N, mais provável abrir cedo. Escolha o N olhando
> para quantas equipes você quer que tenham chance real (ver "ritual de abertura").

## Ritual de abertura (no fim do dia)

Como há **um só cofre**, a Premiação 2 é um **evento sequencial**, fora do relógio, feito na
hora da premiação:

1. Depois de anunciar a Premiação 1, abra a Premiação 2.
2. **A ordem de tentativa segue o ranking de velocidade** (a equipe mais rápida tenta primeiro).
3. Cada equipe na sua vez tenta **uma abertura** com a combinação que juntou (e as etapas que
   ganhou por diversidade, se for o caso).
4. **O primeiro a abrir leva a premiação bônus. Abriu, acabou** — as demais não tentam mais.
5. Se ninguém abrir, não há Premiação 2 (ou defina um critério de "chegou mais perto" — a definir).

> **Consequência de design:** recompensa duplamente a equipe mais rápida — ela ganha (ou
> concorre a) a Premiação 1 **e** tenta o cofre primeiro. É proposital: velocidade na sala vale.
> Se achar que concentra demais, dá para inverter a ordem do cofre (mais lento tenta primeiro)
> como variante — mas o padrão é **por velocidade**.

## Incentivo do RH — diversidade de departamentos (PROVISÓRIO)

O RH quer **integração entre verticais**. O incentivo: quanto **mais departamentos distintos**
numa equipe, maior a vantagem no meta-jogo do cofre (nunca na Premiação 1 — tempo é só mérito
de jogo).

**Tabela provisória (a definir os números finais):**

| Departamentos distintos na equipe | Vantagem no meta-jogo do cofre |
|---|---|
| 1 (equipe toda do mesmo setor) | nada |
| 2 | **1 dica grátis** |
| 3 | 1 etapa da combinação revelada |
| 4 | 2 etapas reveladas |
| 5+ | 2 etapas reveladas **+** prioridade em empate de tempo na ordem do cofre |

**Regras do incentivo:**
- A vantagem é **definida no credenciamento/briefing**, quando se conhece a composição da
  equipe — e as **etapas reveladas são entregues antes do jogo**, para ajudarem a saber o que
  ainda falta caçar na sala. Revelar no fim não teria utilidade.
- A diversidade **não afeta a Premiação 1** (menor tempo). Só mexe no cofre, para não penalizar
  quem montou equipe por afinidade de setor.
- "Etapa revelada" = você entrega **uma das N etapas prontas** (ex.: "a 2ª é `15 DIR`"), mas
  **não diz a posição dela na ordem** se quiser manter desafio — detalhe a definir junto com o N.

> ⚠️ Esta tabela é um ponto de partida. Os números (quantos departamentos → quantas etapas) e o
> próprio N ainda serão definidos. Ajuste para que a vantagem incentive a mistura **sem** entregar
> o cofre de graça (com N etapas no total, no máximo 2 reveladas ainda deixa a maioria por caçar).

## Montagem e reset (resumo; detalhar junto com o N)

- **1 cofre só, no evento todo** (não é por ala). Fica num ponto comum/da premiação, não dentro
  das salas de jogo. As **pistas** das etapas é que ficam espalhadas pelas salas.
- Como são **duas alas** rodando o mesmo fluxo, as pistas precisam existir **nos dois salões** —
  mas apontam para a **mesma combinação** do único cofre.
- **Reset das pistas** entra no kit de reset de cada salão (repor os red herrings). O **cofre em
  si** não é resetado durante o dia — ele só é aberto uma vez, na premiação.
- **Troque a combinação** antes do evento (o repositório pode ter sido lido por participantes).

> Como as pistas são "red herring", o reset delas é leve — são números/marcações discretas.
> Detalhar as peças exatas depois de fechar o N (quantas pistas montar por salão).

## O que fica dentro do cofre

- A **premiação bônus** (brinde/prêmio físico — definir com o RH).
- Opcional: um cartão de parabéns temático ("Contenção concluída. Acesso concedido.").
