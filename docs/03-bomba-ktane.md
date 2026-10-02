# 03 — A Bomba (KTANE, modo Zen) + TVs + placar

A bomba roda no **notebook certo** (`SN-4270`) no térreo. Ao digitar a senha `RX7-42QK`, o
sistema destrava e a partida inicia.

> Referências: [manual/regras oficiais](https://keeptalkinggame.com/) e
> [criação de bombas/missões (modkit)](https://github.com/keeptalkinggame/ktanemodkit/wiki/4.-Custom-Missions).
> *Conteúdo parafraseado para conformidade de licença.*

## Modo Zen — o que muda (importante)

No **modo Zen** a bomba **não explode** e o tempo é **progressivo** (conta para cima). É o
modo relax/treino. Consequência de design que você escolheu de propósito:

- **Não existe "perder".** Ninguém sai frustrado — ótimo para novatos.
- **Cada strike aumenta o tempo total** (penalidade), em vez de matar.
- **O objetivo vira o CRONÔMETRO:** menor tempo total = melhor → **premiação** no fim do dia.

> Efeito prático: a tensão não vem do "vai explodir", e sim da **competição por tempo** e da
> **dificuldade de comunicação** entre andares. O clima do dia é de **ranking**, não de sustos.

## Configuração recomendada da bomba

| Parâmetro                 | Valor                                     | Por quê                                               |
| ------------------------- | ----------------------------------------- | ----------------------------------------------------- |
| **Modo**                  | **Zen** (tempo progressivo, sem explosão) | Definição do evento                                   |
| **Penalidade por strike** | tempo somado (padrão Zen)                 | Strike vira custo de tempo, não morte                 |
| **Nº de módulos**         | **4**                                     | 1 por especialista do manual; 5+ vira caos p/ novatos |
| **Módulos needy**         | **0**                                     | Atenção contínua é punitiva demais para 1ª vez        |

### Módulos sugeridos (didáticos, manual claro)
1. **Wires (Fios)** — o mais intuitivo.
2. **The Button (Botão)** — cor + segurar/soltar; ensina comunicação.
3. **Keypad (Símbolos)** — combina com "achar a ordem".
4. **Simon Says** — sequência de cores; puro trabalho de rádio.

> Evite p/ novatos: Morse, Wire Sequences, Mazes, Memory, Passwords sob pressão.

## Consistência: os módulos ↔ as páginas do manual (P2)

Imprima e esconda no salão (P2) **apenas** as páginas dos 4 módulos acima. Se trocar um
módulo, **troque a página** correspondente. Destaque com marca-texto para novato não se perder.

## TVs — o vídeo de 30 min (timer + CCTV) por sala

Cada sala tem **uma TV**. Em vez de espelhar o jogo do KTANE, a TV roda um **vídeo de 30 min**
que já traz **o timer embutido na própria tela** junto com um **loop de CCTV** (ver o puzzle
P5 "Onde está o host" no `02-puzzles.md`). Um único arquivo de vídeo resolve duas coisas:
o cronômetro visível e o puzzle de descoberta da sala.

- **Timer NÃO sincronizado entre salas/alas.** Cada GM dá **play no seu vídeo** quando libera a
  equipe (fim do briefing). Não há relógio central nem espelhamento entre telas — é só dar play.
  Isso simplifica muito a operação com duas alas rodando em paralelo.
- **O timer corre dentro do vídeo** (0 → 30 min). Como o modo da bomba é **Zen** (sem explosão),
  o número que vale é a **duração** até o desarme, não o horário de parede.
- **Uma TV por sala, duas por ala** (salão + sala de desarme). Cada ala tem **seu próprio vídeo**,
  apontando para a **sua** sala de desarme (ver P5). Os dois vídeos são iguais na mecânica, mas
  mostram salas/corredores diferentes.

> **Justiça do placar sem sincronia:** o que mantém o ranking justo **não** é um relógio único,
> e sim **todas as equipes começarem a contar no mesmo marco relativo** — o GM dá play no vídeo
> **no fim do briefing**, ao liberar a equipe. Assim toda equipe tem os mesmos 30 min "do zero".
> Registre o **tempo de desarme** (quando a bomba foi desarmada) como a marca da equipe.

> ⚠️ **Produção do vídeo:** o timer precisa estar **embutido no vídeo** (queimado na imagem), não
> numa sobreposição separada — assim o GM só precisa dar play. Detalhes de montagem no `docs/05`.

## Como iniciar o jogo (timer = o vídeo)

- O GM termina o **briefing** (feito **separadamente em cada salão**) e **dá play no vídeo de
  30 min**. O timer sobe desde o começo, cobrindo puzzles + descoberta da sala + desarme.
- O **notebook certo** fica na tela de senha até ser digitada `RX7-42QK`; a bomba KTANE Zen é
  o clímax, mas **o tempo oficial é o do vídeo** (não o timer interno do KTANE).
- Deixe o gatilho **fixo para todas as equipes** (play no fim do briefing) para o placar ser justo.

> Se preferir, o KTANE pode rodar em Zen em paralelo como "sensação de bomba", mas a marca que
> vai pro placar é a do **vídeo** (momento do desarme). Mantenha um critério só, igual para todos.

## Reset da bomba entre equipes

- Salve um **perfil/preset** com os 4 módulos e a config Zen para não reconfigurar.
- Reset = voltar ao menu, recarregar o preset, deixar o `SN-4270` na tela de senha.
- **Rebobine o vídeo de 30 min** (timer + CCTV) para o início nas duas TVs da ala, pronto para
  dar play no próximo briefing.
- Registre o **tempo de desarme** da equipe na planilha do placar (ver doc 04).

## Regras que o desarmador deve saber
- Ele **não** tem o manual; o salão lê por rádio.
- Cada erro = **strike** = **+tempo** (não explode). Vale mais ir com calma e confirmar cores.
- **Só o desarmador** opera a tela da bomba. O **ajudante** está na mesma sala (cuida de T1,
  serial e rádio), mas **não** mexe na bomba. O salão **não** vê a bomba.
