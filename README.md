# 🔓 Escape Room IATEC — "Código Vermelho"

Planejamento completo de um escape room corporativo com clímax em **Keep Talking and Nobody Explodes (KTANE)** rodando no notebook.

## Visão geral

| Item | Definição |
|---|---|
| **Formato** | 2 salas separadas, uma equipe de cada vez |
| **Equipe** | 5 pessoas |
| **Duração alvo** | 30–45 min (25 min salas/puzzles + 10–15 min bomba) |
| **Público** | Diverso, maioria nunca jogou escape room / KTANE |
| **Operação** | Roda o dia todo; a sala é **resetada entre tentativas** |
| **Clímax** | Desarmar a bomba (KTANE) no notebook antes do tempo acabar |

## O enredo (tema)

> Um ex-colaborador insatisfeito escondeu um **notebook armado** na empresa. O sistema
> está bloqueado por senha e, ao destravar, inicia a contagem de uma bomba lógica.
> A equipe (o "esquadrão anti-bombas") tem que vasculhar duas salas, achar as pistas,
> abrir o cofre, montar a senha e **desarmar a bomba** antes do tempo zerar.

## O grande truque de design

A **senha do notebook** exige **DUAS metades**:
- **Metade A** → obtida na **Sala 1** (onde o notebook fica).
- **Metade B** → trancada no **cofre da Sala 2**.

Quando a equipe se divide entre as duas salas, **ninguém termina sozinho** — são forçados
a usar os **rádios comunicadores**. Isso "ensaia" a dinâmica de comunicação do KTANE
antes do clímax. Essa é a espinha dorsal de toda a experiência.

## Fluxo em uma imagem

```
SALA 1 (todos começam aqui)                 SALA 2 (destravada pela chave)
┌───────────────────────────┐               ┌───────────────────────────┐
│ • Notebook (bomba) travado │               │ • COFRE                   │
│ • Puzzle A → CHAVE Sala 2  │──── chave ───►│ • Puzzles C/D → combinação│
│ • Puzzle B → METADE A senha│               │ • Cofre guarda METADE B   │
└───────────────────────────┘               └───────────────────────────┘
             ▲                                            │
             └──────── METADE A + METADE B (rádio) ───────┘
                                  │
                                  ▼
                   Notebook desbloqueado → BOMBA (KTANE)
                   1 desarma • 3–4 no manual • rádio entre salas
```

## Documentos deste repositório

| Arquivo | Conteúdo |
|---|---|
| [`docs/01-fluxo-e-mapa.md`](docs/01-fluxo-e-mapa.md) | Mapa das salas, progressão e papéis dos 5 jogadores |
| [`docs/02-puzzles.md`](docs/02-puzzles.md) | Cada puzzle com material, montagem e **solução** |
| [`docs/03-bomba-ktane.md`](docs/03-bomba-ktane.md) | Configuração e calibragem da bomba para novatos |
| [`docs/04-roteiro-game-master.md`](docs/04-roteiro-game-master.md) | Timeline, sistema de dicas e checklist de **reset** |
| [`docs/05-materiais-e-impressao.md`](docs/05-materiais-e-impressao.md) | Lista de compras/materiais e o que imprimir |

## Materiais que você já tem

Lanterna UV · impressora · transparências · impressora 3D · malas com combinação numérica · cofre · notebook · rádios comunicadores.
```
```
```

---
*Ajuste os nomes de senha/combinações antes de operar — os valores nos docs são exemplos prontos para uso, mas convém trocá-los se alguém puder ter lido este repositório.*
