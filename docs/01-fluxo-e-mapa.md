# 01 — Fluxo, mapa e papéis

## Linha do tempo da experiência (alvo: 30–45 min)

```
0:00 ─ Briefing na Sala 1 (fora do relógio) — GM conta o enredo
0:00 ─ [RELÓGIO INICIA] equipe entra na Sala 1
        │
        ├─ Puzzle A (chave da Sala 2)      ─┐ feitos em paralelo
        ├─ Puzzle B (METADE A da senha)    ─┘
        │
~8-12min ─ Acham a CHAVE → abrem a Sala 2 (equipe se divide)
        │
        ├─ Sala 2: Puzzles C + D → combinação do cofre
        ├─ Sala 1: continua decifrando pistas, passa dados por RÁDIO
        │
~20-25min ─ Cofre aberto → pega METADE B da senha
        │
        ├─ Junta METADE A (Sala 1) + METADE B (Sala 2) por RÁDIO
        │
~25min ─ Digita senha no notebook → BOMBA ARMA (KTANE)
        │
        ├─ 1 desarmador vê a tela / 3-4 no manual (podem estar em salas diferentes)
        │
~40min ─ Bomba desarmada 🎉  ou  BOOM 💥 (fim)
```

> **Regra de ouro do tempo:** os puzzles das salas devem consumir **no máx. ~25 min**.
> A bomba tem seu próprio cronômetro (ver `03-bomba-ktane.md`). Some os dois e mantenha
> o total dentro de 45 min. Use o sistema de dicas do GM para não estourar.

## Mapa das salas

```
        SALA 1 — "A Base"                         SALA 2 — "O Cofre"
 ┌──────────────────────────────┐         ┌──────────────────────────────┐
 │  [Mesa] NOTEBOOK travado 🔒   │         │        COFRE 🔐              │
 │                               │         │                              │
 │  [Quadro/parede] cifra + UV   │  porta  │  [Estante] Puzzle C          │
 │                               │═══🔑═══►│  (lógica → 2 dígitos)        │
 │  Mala trancada 🧳 (Puzzle A)  │         │                              │
 │  → dentro: CHAVE Sala 2       │         │  [Caixa] Puzzle D            │
 │                               │         │  (transparências → 2 díg.)   │
 │  Pistas METADE A da senha     │         │  Cofre guarda: METADE B      │
 │  (só completáveis c/ Sala 2)  │         │                              │
 └──────────────────────────────┘         └──────────────────────────────┘
   Rádio #1 fica aqui                        Rádio #2 fica aqui
```

## Por que o notebook fica na Sala 1

Mantém o clímax onde a equipe começou e cria um "vaivém": quem foi pra Sala 2 abrir o
cofre precisa **voltar ou transmitir por rádio** a METADE B. No fim, todos convergem
para o notebook. Se preferir separação máxima (desarmador isolado), veja a variante no
roteiro do GM.

## Papéis dos 5 jogadores (evitando ociosidade)

Não distribua papéis fixos no início — deixe a equipe se auto-organizar, mas o GM deve
**induzir** a divisão se travar. Estrutura ideal por fase:

| Fase | Distribuição sugerida |
|---|---|
| **Sala 1 (início)** | 2 no Puzzle A · 2 no Puzzle B · 1 "escrivão" anota tudo achado |
| **Abriu Sala 2** | 2–3 vão para a Sala 2 (cofre) · 2 ficam na Sala 1 (pistas + rádio) |
| **Cofre aberto** | Todos convergem info por rádio para montar a senha |
| **Bomba (KTANE)** | **1 desarmador** (só ele vê a tela) · **3–4 no manual**, cada um responsável por 1–2 tipos de módulo |

### Dica de papéis no KTANE
Divida o **manual** por módulo entre as pessoas: "você é o especialista em **fios**",
"você em **botão**", "você em **teclado/símbolos**". Assim ninguém fica parado e a
comunicação fica objetiva ("desarmador, que módulo é? fios? passa as cores").

## Dependências entre puzzles (grafo)

```
Puzzle A ──► CHAVE ──► abre SALA 2
Puzzle B ──► METADE A da senha ─┐
Puzzle C ─┐                     ├─► SENHA COMPLETA ──► arma BOMBA ──► KTANE
Puzzle D ─┴► combinação COFRE ──► METADE B ─────────┘
```

Repare: **A** é o gargalo que libera a Sala 2. **C+D** são paralelos e ambos alimentam o
cofre. **B** pode ser resolvido cedo, mas só vira senha útil quando o cofre entrega a
METADE B — por isso a comunicação por rádio é inevitável.
