# 01 — Fluxo, mapa e papéis

## Mapa dos dois andares

```
╔═══════════════════════ 2º ANDAR ═══════════════════════╗
║  SALA 1 — SALÃO (grande) — EQUIPE DE 4                  ║
║                                                         ║
║   P1 ▸ METADE 1 da senha (achada CEDO, sem saber p/quê) ║
║   P2 ▸ páginas do MANUAL do KTANE (escondidas)          ║
║   P3 ▸ máscara parcial do SERIAL (ex.: SN-••7•)         ║
║        └─ P1+P2+P3 = GATE ─► P4                         ║
║   P4 ▸ CHAVE física da Sala 2                           ║
║                                                         ║
║   COFRE ▸ guarda METADE 2 da senha + SERIAL completo    ║
║           (combinação vem do TÉRREO, por rádio)         ║
║   TV ▸ cronômetro do jogo (Zen)   ·   RÁDIO #1          ║
╚═════════════════════════════════════════════════════════╝
                         │  chave desce com o desarmador
                         ▼
╔═══════════════════════ TÉRREO ═════════════════════════╗
║  SALA 2 — REUNIÃO (pequena, p/ 4) — DESARMADOR SOZINHO  ║
║                                                         ║
║   • 5–10 notebooks na mesa (só 1 é o certo; resto na    ║
║     tela de senha p/ despistar)                         ║
║   • Puzzles do térreo ▸ COMBINAÇÃO DO COFRE             ║
║     (desarmador dita por rádio p/ o salão)              ║
║   • Notebook certo é achado cruzando o SERIAL           ║
║   TV ▸ mesmo cronômetro do jogo   ·   RÁDIO #2          ║
╚═════════════════════════════════════════════════════════╝
```

## Grafo de dependências (a ordem é imposta pelo design)

```
P1 (metade 1) ─┐
P2 (manual)    ├─ GATE ─► P4 = CHAVE ─► abre SALA 2 (desarmador desce)
P3 (máscara)  ─┘                              │
                                              ▼
                         Puzzles da Sala 2 ─► COMBINAÇÃO do cofre ──(rádio)──► salão
                                              │
                       salão abre COFRE ─► METADE 2 + SERIAL completo
                                              │
              METADE 1 + METADE 2 = SENHA ──(rádio)──► desarmador
                                              │
       desarmador usa SERIAL p/ achar o notebook certo ─► digita SENHA
                                              │
                                    BOMBA (KTANE Zen) ─► desarma ouvindo o manual (rádio)
                                              │
                                    tempo total ─► PLACAR
```

> **Regras de sanidade do design (para não travar):**
> - **P4 (chave) NÃO depende do cofre nem da Sala 2** — só dos 3 gates do salão. Assim a
>   equipe sempre consegue abrir a Sala 2 sozinha.
> - **A combinação do cofre está SÓ na Sala 2** — obriga o desarmador a ser útil (não fica
>   só recebendo ordens).
> - **A METADE 1 é achada antes da chave** e parece inútil no momento — recompensa quem anota.

## Linha do tempo (alvo: 30–45 min de jogo; tempo Zen = pontuação)

```
[fora do relógio] Briefing no salão — GM explica enredo, entrega rádios, define desarmador
[RELÓGIO/Zen] equipe entra; a bomba (Zen) já pode iniciar junto (ver doc 03)
  │
  ├─ 0–10 min: 4 puzzles paralelos no salão (P1,P2,P3) → convergem no GATE → P4 = chave
  │            desarmador desce ao térreo com a chave e entra na Sala 2
  │
  ├─ 8–18 min: desarmador resolve puzzles do térreo → COMBINAÇÃO do cofre → dita por rádio
  │            (enquanto isso a equipe organiza páginas do manual e a metade 1)
  │
  ├─ 15–22 min: salão abre o COFRE → METADE 2 + SERIAL completo
  │             equipe junta senha; dita SENHA + SERIAL por rádio
  │
  ├─ 20–25 min: desarmador acha o notebook certo → digita senha → BOMBA arma
  │
  └─ 25–40 min: desarme do KTANE (Zen), equipe lendo o manual por rádio
              → tempo total travado no placar 🏆
```

Como é **Zen**, não há "estouro": o cronômetro é a **nota**. O GM usa dicas para evitar que
uma equipe fique travada tempo demais (ruim para o clima e para a fila do dia).

## Papéis (mantendo os 5 ativos)

**Salão (4 pessoas)** — sugerir, não impor:
| Papel | Faz |
|---|---|
| **Rádio-líder** | Fala com o desarmador; centraliza pedidos e respostas |
| **Puzzle A** | Toca P1 + parte do GATE |
| **Puzzle B** | Toca P2 (manual) + P3 (máscara serial) |
| **Escrivão/Manual** | Anota tudo (metade 1!) e, no clímax, vira leitor do manual do KTANE |

**Térreo (1 pessoa)** — o **desarmador**:
- Resolve os puzzles do térreo (combinação do cofre), acha o notebook certo, digita a senha
  e **desarma sozinho** ouvindo o manual pelo rádio. **Não** tem o manual em mãos.

### Divisão do manual no clímax
No salão, distribua o **manual** por módulo entre as 3–4 pessoas: "você é fios", "você é
botão", "você é Simon". O desarmador diz o módulo e as cores; o especialista responde. Isso
evita ociosidade e deixa a comunicação objetiva.

## Variantes rápidas
- **Mais fácil:** máscara do serial (P3) já mostra quase todo o serial; combinação do cofre
  com menos passos.
- **Mais difícil:** exija que a equipe **ordene** as páginas do manual (P2) antes de conseguir
  ler qualquer módulo no clímax.
