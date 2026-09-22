# 02 — Puzzles (montagem + soluções)

> ⚠️ **Página de spoilers.** Contém todas as soluções. Só o Game Master deve ter acesso.
> Nível calibrado como **médio/difícil**, mas com "rampas" para novatos (ver dicas no doc 04).
> Os valores (senhas, combinações) são **exemplos prontos** — troque-os antes de operar.

Usa só o que você tem: **lanterna UV, impressora, transparências, impressora 3D, malas com
combinação numérica, cofre, notebook, rádios**.

---

## SALA 1

### 🧩 Puzzle A — "O Mapa Rasgado" → CHAVE da Sala 2
**Objetivo:** abrir a **mala com combinação numérica** que guarda a chave física da Sala 2.

**Montagem:**
- Espalhe pela Sala 1 **4 cartões impressos**, cada um com um dígito grande e um pequeno ícone/coordenada.
- Um **quadro/pôster** na parede indica a **ordem** de leitura dos ícones (ex.: "☀ 🌙 ★ ⚡" ).
- Cada cartão associa um ícone a um dígito.

**Solução (exemplo):**
- ☀=7, 🌙=3, ★=9, ⚡=1 → combinação da mala = **7391**.
- Dentro da mala: a **chave física** da porta da Sala 2 + um bilhete: *"Metade do código nasce na luz que os olhos não veem"* (dica para o Puzzle B/UV).

**Por que médio/difícil:** exige juntar objetos espalhados + inferir a ordem pelo pôster (2 passos).

---

### 🧩 Puzzle B — "Tinta Invisível" → METADE A da senha do notebook
**Objetivo:** revelar a **METADE A** (primeiros caracteres) da senha do notebook.

**Montagem:**
- Escreva com **caneta UV** parte da senha em um local não óbvio (verso de um quadro, dentro de uma gaveta, embaixo da mesa do notebook).
- A **lanterna UV** fica escondida/protegida — a equipe precisa achá-la (pode estar dentro da mala do Puzzle A, reforçando a ordem A→B).
- O texto UV mostra: **`METADE A: RX7-`** e um símbolo `▮▮` indicando que **faltam 4 caracteres** (que virão do cofre).

**Solução:** METADE A = **`RX7-`** (a senha completa será `RX7-42QK`, ver Puzzle no cofre).

**Por que médio/difícil:** a pista fica invisível até acharem a lanterna; força procura ativa.

---

## SALA 2

### 🧩 Puzzle C — "Lógica do Servidor" → 2 primeiros dígitos do cofre
**Objetivo:** deduzir 2 dígitos por um mini enigma de lógica (estilo Einstein).

**Montagem:** um cartão impresso com 4 pistas sobre 4 "servidores" (A, B, C, D) e suas posições/cores. A equipe deduz uma ordem, e a **posição de um servidor específico** dá os dígitos.

**Pistas (exemplo):**
1. O servidor **vermelho** não está nas pontas.
2. **A** está imediatamente à esquerda do **azul**.
3. **D** é o último.
4. O **verde** é o primeiro.

**Solução:** ordem = Verde(A?) … deduz-se **ordem A, C(vermelho), B(azul), D**.
Os 2 dígitos = **posição do servidor vermelho na fila × 10 + nº de servidores** → **24**
(*ajuste o mapeamento como preferir; o importante é dar 2 dígitos fixos, ex. `24`*).

---

### 🧩 Puzzle D — "Sobreposição" → 2 últimos dígitos do cofre
**Objetivo:** obter 2 dígitos sobrepondo **transparências**.

**Montagem:**
- Imprima **2 transparências**: cada uma sozinha parece ruído/linhas aleatórias.
- Sobrepostas **na orientação certa** (marque cantos com ► para alinhar), revelam **2 dígitos grandes**.
- Esconda as transparências em locais diferentes da Sala 2 para forçar busca.

**Solução (exemplo):** dígitos revelados = **68**.

---

### 🔐 O COFRE → METADE B da senha
**Combinação = Puzzle C + Puzzle D = `2468`** (exemplo).

**Dentro do cofre:**
- Cartão impresso: **`METADE B: 42QK`**
- Bilhete: *"Junte as duas metades. Ao digitar, o relógio começa a correr."*

**Senha completa do notebook = METADE A + METADE B = `RX7-42QK`.**

---

## Peças opcionais em impressora 3D (deixa o cenário melhor)
- **Suporte/base temática** para o notebook (visual de "bomba").
- **Engrenagem/token** que encaixa em algo para "destravar" fisicamente a mala.
- **Porta-cartões** com ícones em relevo para o Puzzle A (dá pistas táteis a iniciantes).
- **Alinhador de transparências** (moldura com trilhos) para facilitar o Puzzle D.

## Resumo das soluções (cola do GM)

| Puzzle | Resultado |
|---|---|
| A — Mapa Rasgado | Mala = **7391** → chave da Sala 2 |
| B — Tinta Invisível (UV) | METADE A = **`RX7-`** |
| C — Lógica do Servidor | 2 dígitos = **24** |
| D — Sobreposição | 2 dígitos = **68** |
| Cofre (C+D) | **2468** → METADE B = **`42QK`** |
| **Senha do notebook** | **`RX7-42QK`** → arma a bomba |
