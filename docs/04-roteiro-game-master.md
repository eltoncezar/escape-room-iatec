# 04 — Roteiro do Game Master (GM)

Escape room em **dois andares**, **duas alas em paralelo** (B e C), rodando o dia todo
(**8:30–16:30**) em ciclos de **30 min de jogo + 10 min de reset**. Modo **Zen**: sem explosão,
**menor tempo vence** → premiação. Cada ala tem seus **2 GMs**: um no salão (2º andar), um na
sala de desarme (térreo), comunicando-se por um canal de rádio separado do dos jogadores. São,
portanto, **2 equipes de GM no total** (uma por ala), com **canais de rádio distintos por ala**
para não haver interferência.

> Mapeamento físico das alas (1B/Calabouço e 1C/sala ao lado da sala do pastor), escala e
> restrições operacionais do dia: ver o steering `.kiro/steering/evento.md`.

## Escala do dia (8:30–16:30)

- **Ciclo por slot:** 30 min de jogo + 10 min de reset = **40 min por equipe**, por ala.
- **Duas alas em paralelo:** a cada 40 min, **duas equipes** entram (uma na Ala B, uma na Ala C).
- Reserve **almoço** e um **buffer** entre blocos — não encaixe slots de ponta a ponta sem respiro.
- Participantes chegam no **horário agendado**; tenha a lista de inscrições à mão para chamar
  a próxima equipe e evitar atraso em cadeia (um slot estourado empurra todos os seguintes).

Exemplo de grade (ajuste à sua programação; cada linha = um par de equipes, uma por ala):

| Slot   | Jogo             | Reset       |
| ------ | ---------------- | ----------- |
| 1      | 08:30–09:00      | 09:00–09:10 |
| 2      | 09:10–09:40      | 09:40–09:50 |
| 3      | 09:50–10:20      | 10:20–10:30 |
| …      | …                | …           |
| almoço | —                | —           |
| …      | …                | …           |
| último | até ~16:00–16:30 | —           |

> O número exato de slots depende do almoço/buffer. Com ~40 min por slot e duas alas, você
> atende **2 equipes por slot**. Feche a grade final antes do dia e divulgue nos agendamentos.

## Antes de cada equipe: briefing (no salão, fora da pontuação)

> "Um ex-colaborador deixou um **notebook armado** na sala de manutenção do térreo, escondido
> entre vários notebooks iguais. Vocês são o esquadrão anti-bombas. **Dois de vocês** vão descer
> até o térreo: um fica responsável por **operar e desarmar o notebook** certo, o outro **resolve
> as pistas de lá embaixo e cuida do rádio**. Os **outros quatro** ficam aqui no salão caçando as
> pistas. Vocês estão em **andares diferentes** — só se falam pelo **rádio**. A bomba está em modo
> de treino: **não explode**, mas cada erro e cada minuto **contam no seu tempo**. Vence a equipe
> que desarmar no **menor tempo**. Escolham quem desce (desarmador + ajudante)... agora."

Anuncie as regras:
1. Nada de força bruta em cadeados/malas/notebooks.
2. **Só a dupla do desarme** fica no térreo; o manual **não** desce. Na bomba, **só o desarmador** opera a tela.
3. Podem pedir dicas (custam tempo — ver abaixo).
4. O **cronômetro nas TVs é a sua pontuação.**

**Defina o início do timer igual para todas as equipes** (recomendado: inicia no briefing —
ver doc 03) para o placar ser justo.

## Timeline e gatilhos de dica

| Tempo      | Esperado                             | Dica sutil se travar                                                                  |
| ---------- | ------------------------------------ | ------------------------------------------------------------------------------------- |
| 0–3 min    | Explorando o salão, achando P1/P2/P3 | "Reparem no que parece inútil agora — anotem."                                        |
| ~5 min     | Montando tokens `◆ ▲ ■`              | "Vocês têm 3 símbolos. Onde há um painel que os traduz?"                              |
| ~8 min     | Deveriam ter a **chave** (P4)        | Dê 1 token→dígito do painel do GATE.                                                  |
| ~10 min    | Dupla desceu e começa o T1           | (GM térreo) "As etiquetas dos notebooks não são decorativas."                         |
| ~10–18 min | **Salão esperando a maleta**         | "Enquanto isso: organizem o manual (B1) e vejam o Protocolo (B2) pra ganhar tempo."   |
| ~15 min    | Combinação da maleta ditada          | "Lá embaixo, já passaram os 4 dígitos pra cima?"                                      |
| ~18 min    | Maleta aberta → metade 2 + serial    | "Vocês têm as duas metades agora. Juntem e ditem."                                    |
| ~22 min    | Achar o notebook certo               | (GM térreo) "Compare o serial com a máscara que acharam lá em cima."                  |
| ~25 min+   | **BOMBA (Zen)**                      | Dicas de **comunicação**, não de solução: "digam a **cor** e a **posição** dos fios". |

Como é Zen, não há estouro; a dica evita que uma equipe empaque e atrase a fila do dia.

> **Janela do slot (30 min de jogo):** os tempos acima são o alvo folgado de design. No dia,
> se por volta dos **~22–25 min** a equipe ainda estiver longe do desarme, seja mais generoso
> com as dicas (registrando a penalidade) para o jogo fechar perto dos **~30 min** e não
> atropelar os **10 min de reset** nem o próximo horário agendado.

## Sistema de dicas (Zen = custo em tempo)
- **Dica 1 (leve):** onde olhar → **+30s** no tempo.
- **Dica 2 (média):** o método → **+60s**.
- **Dica 3 (forte):** parte do resultado → **+120s**.

Isso mantém o placar justo: quem pediu mais ajuda tem tempo maior. Registre as dicas na planilha.

### Bônus do B2 "Protocolo de Emergência" (opcional)
Se a equipe resolver o satélite B2 (cifra → **`SIMON`**), ela escolhe **uma** recompensa:
- **−90s** no tempo final, **ou**
- **1 dica grátis** no clímax (sem a penalidade de tempo acima).

Registre o bônus na planilha (coluna própria). B2 é **opcional** e não trava o fluxo; serve
para ocupar o salão durante a janela do T1 e recompensar quem for mais rápido.

## Cola de soluções (rápida)

| Etapa                             | Valor                                               |
| --------------------------------- | --------------------------------------------------- |
| Mala (GATE P4)                    | **4826** → chave da sala de desarme                 |
| Metade 1 (P1, UV)                 | **`RX7-`**                                          |
| Combinação da maleta (T1, térreo) | **7315**                                            |
| Maleta de evidências (salão)      | Metade 2 **`42QK`** + Serial **`SN-4270`**          |
| Senha do notebook                 | **`RX7-42QK`** (só no `SN-4270`)                    |
| B2 — Protocolo (opcional)         | cifra → **`SIMON`** → **−90s** ou **1 dica grátis** |
| Bomba                             | 4 módulos vanilla, **Zen** (ver doc 03)             |

## ✅ Checklist de RESET (dois andares)

> Cada ala faz **o seu próprio reset em paralelo**, dentro da **janela de 10 min** entre slots.
> Tenha **kits pré-montados por sala** (4 kits no total: 2 salões + 2 salas de desarme). Os GMs
> de cada ala resetam a própria ala; faça na ordem. Para caber nos 10 min, prefira repor com
> peças/kits prontos em vez de remontar na hora.

**Salão (2º andar — 1B ou 1C)**
- [ ] Reesconder P1 (metade 1) e a lanterna UV; conferir se a marca UV está legível (retocar)
- [ ] Reespalhar/embaralhar as páginas do manual (P2) nos esconderijos
- [ ] Reesconder as 2 transparências do P3 (máscara `SN-••7•`)
- [ ] Repor o cartaz-guia do B1 e o cartão + transparência/UV do B2 (Protocolo → `SIMON`)
- [ ] Repor o painel do GATE e trancar a mala em **4826** com a chave da sala de desarme dentro
- [ ] Trancar a **maleta de evidências** em **7315** com Metade 2 **`42QK`** + Serial **`SN-4270`** dentro
- [ ] TV do salão espelhando o cronômetro do jogo · Rádio #1 da ala carregado, canal certo

**Sala de desarme (térreo — Calabouço ou sala ao lado da sala do pastor)**
- [ ] Trancar a porta da sala de desarme (chave volta pra mala do salão)
- [ ] Repor puzzles do T1 (etiquetas dos notebooks, cartaz, cifra/transparência)
- [ ] Notebooks na mesa (5–10): todos na **tela de senha**; só o **`SN-4270`** é o certo
- [ ] Conferir seriais adesivados; garantir que só 1 = `SN-4270`
- [ ] KTANE no `SN-4270` com **preset Zen** carregado (4 módulos) · TV espelhando timer
- [ ] Rádio #2 da ala carregado, canal certo

**Geral (por ala)**
- [ ] Baterias sobressalentes (rádios, lanterna UV)
- [ ] Planilha do placar (global) atualizada com a equipe e a **ala**
- [ ] Plaquinhas de foto no ponto de fotos
- [ ] Timer do jogo zerado/pronto para a próxima equipe
- [ ] Confirmar que os **canais de rádio** da ala não conflitam com os da outra ala

## 🏆 Premiação 1 — Placar de velocidade

Placar **único/global**: as duas alas competem no mesmo ranking. Registre a **ala** e o
**horário** de cada equipe para rastrear, mas o que rankeia é o **tempo ajustado**. A coluna
**Deptos.** (nº de departamentos distintos na equipe) **não** entra no ranking de tempo — serve
só para o meta-jogo do cofre (Premiação 2, abaixo).

| Equipe | Ala (B/C) | Horário | Deptos. | Início | Tempo final (Zen) | Strikes | Dicas (+tempo) | Bônus B2 (−90s?) | Tempo ajustado | Posição |
| ------ | --------- | ------- | ------- | ------ | ----------------- | ------- | -------------- | ---------------- | -------------- | ------- |
|        |           |         |         |        |                   |         |                |                  |                |         |

> **Tempo ajustado = tempo final do jogo + penalidades de dica − bônus B2 (se resgatado como tempo).**
> É o número que rankeia. (Strikes já entram no tempo do jogo pelo próprio Zen.)
> Se a equipe escolheu o B2 como "dica grátis" em vez de −90s, não subtraia tempo; só registre que a dica não penalizou.
> **Justiça entre alas:** mantenha config da bomba e início do timer **idênticos** nas duas alas.
> **Deptos. não afeta o tempo** — diversidade só dá vantagem na Premiação 2 (cofre).

## 🔐 Premiação 2 — Cofre (bônus, fora do relógio)

Meta-jogo opcional: o **cofre de dial único** guarda uma **premiação bônus**. Durante o jogo, as
pistas da combinação ficam espalhadas pela sala parecendo **red herring** — não travam nada.
A disputa só acontece **no fim do dia**, depois da Premiação 1. Regras completas e pontos em
aberto em [`07-meta-jogo-cofre.md`](07-meta-jogo-cofre.md).

**Ritual de abertura (na premiação):**
1. Anuncie a Premiação 1 primeiro; depois abra a Premiação 2.
2. **Ordem de tentativa = ranking de velocidade** (equipe mais rápida tenta primeiro).
3. Cada equipe tenta **uma abertura** com a combinação que juntou + etapas ganhas por diversidade.
4. **O primeiro que abrir leva. Abriu, acabou** (cofre único).
5. Ninguém abriu → sem Premiação 2 (ou critério de "chegou mais perto" — a definir).

> ⚠️ **A definir:** número de etapas da combinação e a escala de vantagem por diversidade. Até
> fechar, trate como provisório. A vantagem por diversidade é entregue **no credenciamento**
> (etapas reveladas ajudam a saber o que falta caçar), **nunca** afeta a Premiação 1.

## Variante "só treino" para aquecer
Se uma equipe estiver muito insegura, deixe uma **mini-bomba Zen de 1 módulo** no salão antes
de descer, só para a dupla do desarme e a equipe treinarem a dinâmica de rádio (não conta no
placar). Cuidado com o relógio: com slots de 30 min, use o aquecimento só quando sobrar folga.
