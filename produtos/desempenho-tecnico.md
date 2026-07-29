# Desempenho Técnico — Dados com Status de Citabilidade

> **Este é o arquivo-fonte de números para conteúdo.** Antes de citar qualquer valor de desempenho (térmico, acústico, fogo, corrosão) em post/carrossel/legenda/roteiro, consultar aqui. Cada dado tem um **status de citabilidade** — respeitar sempre.
>
> Fonte: notas técnicas oficiais Fast em `material técnico/` (desempenho térmico LSF, galvanização de perfis, isolamento acústico drywall, resistência ao fogo chapa RF).

## Legenda de status (regra de ouro)

| Status | Significado | Como usar no conteúdo |
|---|---|---|
| ✅ **CITÁVEL** | Norma publicada e vigente | Pode afirmar com a norma como fonte |
| ⚠️ **REFERÊNCIA** | Estimativa de engenharia OU norma em revisão/consulta ("não tem valor normativo") | Usar como ordem de grandeza / conforto; **nunca** apresentar como "a norma exige" nem como valor oficial cravado |

> **Nunca** transformar um dado ⚠️ REFERÊNCIA em promessa normativa. Ex.: não escrever "a norma garante 60 dB" — escrever "dependendo da montagem, chega a ~60 dB (referência de projeto)".

---

## 1. Desempenho térmico — Steel Frame vs. alvenaria ⚠️ REFERÊNCIA

**Número-chave:** a parede de Light Steel Framing **isola cerca de 3 a 5× melhor que alvenaria**.

- Parede LSF (fechamento por face + **lã de vidro 90 mm** na câmara): resistência térmica **R ≈ 2,4 m²·K/W**, transmitância **U ≈ 0,4 W/m²·K** (campo livre).
- Descontando as pontes térmicas dos montantes de aço: **U efetivo ≈ 0,6–0,9 W/m²·K** — ainda excelente.
- Alvenaria rebocada de referência: **U ≈ 2,3–2,5 W/m²·K**.
- Atende com folga o nível mínimo da NBR 15575-4 (a confirmar por zona bioclimática).

**Status:** estimativa de engenharia (cálculo R = e/λ em série; método NBR 15220-2, aceitação NBR 15575-4). **Não** é valor ensaiado. Para declaração oficial, confirmar contra NBR 15220-2 / 15575-4 ou usar o desempenho declarado do fabricante do sistema.

**Frases prontas (ok para post):**
- "Parede de steel frame isola de 3 a 5× melhor que alvenaria." *(comparação de conforto, tom educativo)*
- "A lã de vidro na câmara é o que faz o steel frame ser mais fresco no verão e mais quente no inverno."

**Não escrever:** "U = 0,41 W/m²·K certificado", "atende a NBR 15575 comprovadamente" (sem laudo). Apresentar sempre como estimativa/comparação, não como número oficial cravado.

> Decomposição por camada (R por camada): OSB 11 mm = 0,092 · gesso 12,5 mm = 0,036 · **lã de vidro 90 mm = 2,00** · Rse 0,04 + Rsi 0,13. O isolante responde por ~82% da resistência total — é o herói térmico do sistema.

---

## 2. Galvanização dos perfis de aço (anticorrosão) ✅ CITÁVEL

**Número-chave:** o padrão de proteção do aço Fast é **Z275** (zincagem por imersão a quente).

| Ambiente | Zinco mín. (g/m², 2 faces) | Designação | Fonte |
|---|---|---|---|
| Urbano e rural (maioria das obras) | 275 | **Z275** | NBR 16970-1:2022, Tab. 2 |
| Agressivo marinho (até 2.000 m da orla, ou com cloretos) | 350 | **Z350** | NBR 16970-1:2022, Tab. 2 |
| Industrial agressivo | estudo específico | — | NBR 16970-1 |

- **Z275 = 275 g/m² de zinco** (soma das 2 faces) ≈ **19–20 µm por face** — barreira que protege o aço da corrosão.
- Aço estrutural mínimo **230 MPa**; espessura dos perfis **0,80–3,0 mm** (cartola-ripa mín. 0,65 mm). Perfis regidos pela **NBR 15253**.
- **Cuidado de obra:** evitar contato do perfil galvanizado com tubulação de **cobre** (corrosão galvânica) — isolar nesses pontos.

**Status:** ✅ normas **publicadas e vigentes** (NBR 16970-1:2022, NBR 7008-1:2021, NBR 15253). Pode citar.

**Frases prontas (ok para post):**
- "O aço do steel frame Fast é galvanizado Z275 — o padrão da NBR 16970-1 para obra urbana. Zinco protegendo o aço contra corrosão."
- "Perto do mar? Aí o padrão sobe para Z350. A norma pensa no ambiente da sua obra."
- "Steel frame não enferruja como você imagina: a galvanização é uma barreira de zinco de ~20 µm por face."

**Ótimo para:** quebra de objeção "aço enferruja". É o dado **mais seguro** de citar (norma vigente).

---

## 3. Isolamento acústico — parede de drywall ⚠️ REFERÊNCIA

**Número-chave:** conforme a montagem, uma parede de drywall isola de **~34 dB a ~60 dB** (índice Rw, sons aéreos).

| Tipologia (exemplos) | Rw sem lã (dB) | Rw com lã (dB) |
|---|---|---|
| Simples — 2 chapas 12,5 mm, montante 48 (a mais simples) | 34–36 | 42–44 |
| Simples — 2 chapas 15 mm, montante 48 | 35–37 | 43–45 |
| Simples — 4 chapas 12,5 mm, montante 70 | 44–46 | 50–52 |
| Simples — 4 chapas 15 mm, montante 90 | 46–48 | 54–56 |
| Dupla (DEC) — 5 chapas 12,5 mm | 48 | 55 |
| Dupla (DEC) — 6 chapas 15 mm | 48 | 60 |

**Regras que mudam o número:**
- **A lã faz diferença enorme:** +6 a +12 dB só de adicionar isolante na cavidade (lã de vidro NBR 16726 ou lã de PET NBR 16832).
- **Banda acústica é obrigatória** nos perfis que tocam piso/teto/parede — sem ela, o desempenho declarado não se sustenta.
- Mais chapas + montante mais largo + estrutura dupla = mais isolamento.

**Status:** ⚠️ valores da **NBR 15758 em Projeto de Revisão / Consulta Nacional (mar/2025)**, marcada "NÃO TEM VALOR NORMATIVO". Referência de projeto — **não** citar como exigência da norma vigente.

**Frases prontas (ok para post):**
- "Quer silêncio? A lã de vidro na parede de drywall pode somar mais de 10 dB de isolamento."
- "Uma parede dupla de drywall com lã chega perto de 60 dB — nível de conforto de quarto/estúdio (referência de projeto)."
- "Sem banda acústica, o isolamento não acontece. O detalhe faz o desempenho."

**Não escrever:** "a NBR garante 60 dB", "parede de drywall isola 60 dB" (cravado, sem tipologia). Sempre condicionar à montagem e marcar como referência.

---

## 4. Resistência ao fogo — chapa RF ⚠️ REFERÊNCIA (conceito ✅)

**Ponto técnico essencial (✅ citável como conceito):** a chapa RF **sozinha não tem "X minutos"**. A resistência ao fogo (TRRF) é uma propriedade do **sistema/parede completo**, ensaiado pela NBR 10636, atendendo simultaneamente **isolação + estanqueidade + integridade** (Corta-Fogo). A chapa RF é o componente que **eleva** esse desempenho.

- Chapa RF = chapa de gesso com compostos que dão resistência ao fogo (NBR 14715, código **RF**), para paredes/forros/revestimentos em áreas secas.

**Valores de TRRF do sistema com chapa RF (⚠️ referência):**

| Tipologia da parede | TRRF (min) |
|---|---|
| Simples — 2 chapas 12,5 mm (a mais simples) | 30 |
| Simples — 2 chapas 15 mm | 60 |
| Simples — 4 chapas 12,5 mm | 90 |
| Simples — 4 chapas 15 mm | 120 |

**Status:** o **conceito** (chapa RF eleva o TRRF do sistema; TRRF é do sistema, não da chapa) é ✅ citável (NBR 14715, NBR 10636). Os **minutos** vêm da NBR 15758 em Consulta Nacional (mar/2025), "não tem valor normativo" → ⚠️ referência. O TRRF só vale com a **tipologia completa exatamente como ensaiada** (trocar chapa/montante/fixação invalida). Paredes de compartimentação > 6,5 m exigem pórticos + atestado do fabricante.

**Frases prontas (ok para post):**
- "Chapa RF não tem 'tempo de fogo' sozinha — quem resiste ao fogo é o sistema inteiro (chapa + estrutura + montagem)."
- "Com chapa RF, a parede pode resistir de 30 a 120 minutos ao fogo, conforme o número e a espessura das chapas (referência de projeto)."
- "Quer mais tempo de resistência? Mais chapas e chapas mais espessas. 4 chapas de 15 mm chegam a 120 min."

**Não escrever:** "a chapa RF resiste 120 minutos ao fogo" (erro técnico — é o sistema). Sempre falar em sistema/parede completo.

---

## Resumo para o agente (o que priorizar no conteúdo)

1. **Dado mais seguro de citar:** galvanização Z275/Z350 (✅ norma vigente) — usar sem medo na quebra de objeção "aço enferruja".
2. **Comparação de maior impacto:** térmico "3 a 5× melhor que alvenaria" — poderosa, mas enquadrar como estimativa/conforto.
3. **Sempre condicionar** acústico e fogo à **montagem/tipologia** — nunca cravar número absoluto.
4. **Enquadramento correto que já é conteúdo:** "quem estrutura é o aço; a chapa é vedação"; "chapa RF não tem minutos sozinha — quem resiste é o sistema"; "sem banda acústica, sem isolamento". Esses reframes técnicos são ângulos de post prontos.
5. Ver também [normas-desempenho.md](normas-desempenho.md), [base-normativa-abnt.md](base-normativa-abnt.md) e os docs de departamento.
