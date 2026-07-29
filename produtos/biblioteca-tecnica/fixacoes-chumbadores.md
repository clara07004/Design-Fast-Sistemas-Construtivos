# Fixações e Chumbadores (construção a seco)

> Fontes: catálogos e fichas técnicas dos fabricantes na biblioteca Drive, pasta **Parafusos e Chumbadores** `1nqrt2j3d_9PiKIfZsjuG4R_ylAvNSUhm` (subpastas Hilti, Fischer, Ciser, Ancora, Bullfor, Walsywa, Framecad). Documento voltado à objeção **"drywall não segura peso"** — cargas de arrancamento/cisalhamento por fabricante, substrato compatível e a regra correta de fixação de peso.
>
> **Status:** ✅ CITÁVEL = valor está na ficha/catálogo do fabricante · ⚠️ REFERÊNCIA = documentado mas condicionado a tabela/projeto, não cravar número.
>
> **Regra de ouro (NBR 16970 / cultura Fast):** no Steel Frame e no drywall a **integridade é da estrutura de aço** — a placa (gesso, cimentícia, Performa) é **vedação, nunca elemento de carga**. Toda carga vai na estrutura ou em bucha específica de placa oca. Nunca na placa sozinha.
>
> **Convenção de conteúdo:** onde o catálogo diz "placa OSB", em conteúdo Fast lê-se **Placa Performa**. Os nomes de SKU dos fabricantes são preservados abaixo por fidelidade técnica.
>
> **Conversão útil:** 1 kN ≈ 102 kgf. Fabricantes misturam unidades (Ciser/Framecad em kN; Walsywa/Ancora/Bullfor/Fischer em kgf).

---

## Por fabricante

### 1. CISER — parafusos autoperfurantes Steel Frame / Drywall ✅ CITÁVEL
Fonte: *Catálogo Steel Frame Ciser* (out/2011, lido). Material: aço baixo carbono cementado temperado. **Ponto-chave:** as cargas abaixo são do parafuso preso à **chapa de aço** (metal-metal) — é a prova de que quem segura é a estrutura, não a placa.

**Resistência ao arrancamento mínimo (PULL-OUT) — kN, conforme espessura da chapa (0,80 a 1,25 mm):**

| Parafuso | Arrancamento | Cisalhamento |
|---|---|---|
| 4,2 mm (Nº 8) cabeça flangeada | 1,15 – 1,95 kN | 2,25 – 4,52 kN |
| 4,8 mm (Nº 10) cabeça sextavada flangeada | 1,20 – 2,25 kN | 2,30 – 4,98 kN |

Ensaios em chapa de aço baixo carbono — escoamento 318–340 MPa, ruptura 392–401 MPa. Valores de laboratório, a título de orientação; aplicar coeficiente de segurança no projeto.

**Linhas (aplicação por ponta/cabeça):**
- **Painéis / estruturas** — cabeça flangeada ou sextavada flangeada, ponta broca (auto-atarraxante), bitolas 4,2 e 4,8 mm.
- **Placa cimentícia** (tipo Superboard) — cabeça chata dentada ponta broca com asas, 4,2×32 mm.
- **Placa OSB / Placa Performa e concreto delgado (cimentícia)** — cabeça chata dentada ponta broca, 4,2×32 mm.
- **Siding PVC** — cabeça flangeada ponta agulha, rosca dupla entrada.
- **Drywall** — cabeça trombeta ponta agulha / rosca grossa (linha em `catalogo-geral-de-produtos`).

---

### 2. FRAMECAD — parafusos de steel framing (importado) ✅ CITÁVEL
Fonte: ficha *002589 10g Dual Thread* + *FRAMECAD Fasteners catalogue* + e-mail Gyp/Brasgips (lidos).

| Parafuso | Tração (última) | Cisalhamento (última) | Torque ruptura |
|---|---|---|---|
| 10g (#10 / 4,8 mm) Dual Thread x16mm, Wafer, Pin Point | **11,2 kN** | **8,6 kN** (single shear) | 65 kg/cm |

- Revestimento AS3566.2 classe 3; salt spray 1000 h.
- **Aviso do fabricante (citar sempre):** *"FRAMECAD Fasteners are not categorized as structural bolts. All values are average ultimate values. An appropriate safety factor must be determined by a qualified professional."*
- Instalação: o parafuso deve penetrar além do metal em **no mínimo 3 passos de rosca**.
- Especificação de obra (Gyp/Brasgips): projeto define **#10 (galv. 10, ø 4,8 mm)** ou **#12 (galv. 12, ø 5,4 mm)**; mínimo **2 parafusos por conexão**. Ponta PP (pin point, metal pré-furado) ou DP (drill point). Une aço 0,55–2 mm.

---

### 3. BULLFOR — parafusos autoperfurantes construção seca ✅ CITÁVEL
Fonte: *Certificado de Resistência Mecânica Linha SAE 1022* + catálogos NIBRA (lidos). Material: aço baixo carbono cementado, temperado e revenido.

**Cargas de ruptura (sem considerar o material a fixar), kg:**

| Parafuso Nº | Tração | Cisalhamento | Torque |
|---|---|---|---|
| 6-20 | 476 kg | 380 kg | 0,28 kg/m |
| 8-18 | 659 kg | 527 kg | 0,45 kg/m |
| 10-16 | 980 kg | 712 kg | 0,65 kg/m |
| 12-14 | 1.205 kg | 964 kg | 1,00 kg/m |
| 14-14 | 1.673 kg | 1.338 kg | 1,40 kg/m |

Tração e cisalhamento também tabelados **em função da espessura da chapa de aço** (0,90 a 5,55 mm). Ex.: #14-14 cisalhamento de 240 kg @ 0,90 mm a 1.000 kg @ 2,70 mm; tração #10-16 de 655 kg @ 2,70 mm a 982 kg @ 4,00 mm (\\* = ruptura do parafuso sem arrancar da chapa).

**Linhas:** Drywall/Steel Framing (cabeça flangeada, trombeta); placa cimentícia (cabeça escareadora com aletas, Duraseal); **placa OSB/Placa Performa e compensado** (broca Duraseal); autoperfurante telha (linha TEK). Corrosão: zincado salt spray >276 h; Duraseal >1.500 h.

---

### 4. WALSYWA — chumbadores mecânicos (concreto / alvenaria) ✅ CITÁVEL
Fonte: *Catálogo Fixação Mecânica 2013* (lido). Cargas médias de **ruptura** em ensaio IPT (laudo nº 28.202), concreto 20 MPa (CBOLT a 28 MPa). São valores de ruptura → aplicar coeficiente de segurança.

**Orientação Walsywa por material base (relevante à objeção):**
- **Gesso acartonado (drywall):** "material de parede fina de baixa resistência para ancoragem" → usar fixadores que transmitem carga **por travamento**: **Waltog** e **buchas para oco**.
- Madeira aglomerada → **Walgips**; madeira compensada → **Snaptoggle**; concreto → metálicos/químicos.

**Chumbador CB/CBE (torque, jaqueta+cone) — concreto 20 MPa, kgf:**

| Bitola | Tração (arrancamento) | Cisalhamento |
|---|---|---|
| 1/4" | 1.253 | 800 |
| 5/16" | 1.600 | 1.190 |
| 3/8" | 2.107 | 1.617 |
| 1/2" | 2.523 | 2.897 |
| 5/8" | 3.333 | 4.967 |
| 3/4" | 4.320 | 6.573 |
| 1" | 7.790 | 12.080 |

**Chumbador WB (presilha, alta resistência a cisalhamento — granito em fachada, porta-pallet):** 1/4" 825/744 · 3/8" 1.919/1.695 · 1/2" 3.193/3.346 · 5/8" 4.026/5.494 · 3/4" 7.708/9.691 · 1" 11.230/10.214 (tração/cisalh. kgf).

**Chumbador URW/WRS (rosca interna, percussão — suspensão de tubulação), tração kgf:** 1/4" 1.725 · 5/16" 2.395 · 3/8" 3.336 · 1/2" 4.740 · 5/8" 5.785 · 3/4" 8.160.

**Chumbador ALFA / AFW (pino cônico, cargas médias estáticas — concreto, tijolo maciço, bloco):** 3/16" 850/510 · 1/4" 1.220/900 · 5/16" 1.630/1.340 · 3/8" 2.650/1.950 · 1/2" 3.030/3.380 · 5/8" 3.520/5.520 (tração/cisalh. kgf).

**CBOLT (intertravamento de rosca, removível — concreto 28 MPa):** 6×30 428/670 · 8×60 806/1.505 · 10×75 1.705/1.762 · 12×125 4.053/2.918 kgf.

**Golpe de Metal (percussão, aplicações leves — concreto/alvenaria):** 3/16"×7/8" 150/200 · 1/4"×1.1/4" 350/710 kgf. **WLT (percussão):** 1/4" 570 · 3/8" 1.207 · 1/2" 2.197 · 3/4" 4.290 kgf (tração).

**Coeficientes de segurança Walsywa** (reduzir a carga de ruptura): estática 3 (baixo risco) / 5 (alto); variável 4/5; dinâmica 7/15; choque 5/10.

**Fitas perfuradas de suspensão (carga recomendada):** extraleve 20 kgf · leve 30 kgf · pesada 225 kgf · gravada Eraflex 120 kgf — fixadas ao teto por pino rosca 1/4" UNC.

---

### 5. ANCORA — chumbadores mecânicos (concreto 30 MPa) ✅ CITÁVEL
Fonte: *Fichas Técnicas CBA 14/38/56* + *Catálogo Ancora 2013* (lidos). Base: concreto 30 MPa (CBA) / concreto e bases maciças densas. **Não é fixação para drywall.**

**CBA (chumbador de torque c/ jaqueta) — kgf:**

| Modelo | Bitola | Arrancamento | Cisalhamento |
|---|---|---|---|
| CBA 14 | 1/4" | 1.650 | 507 |
| CBA 56 | 5/16" | 1.680 | 837 |
| CBA 38 | 3/8" | 2.740 | 1.237 |

**PBA (passante rosca externa) — carga de arrancamento média (C.A.M.) no concreto, kgf:** 1/4" 870–1.180 · 5/16" 1.650 · 3/8" 2.610 · 1/2" 3.020 · 5/8" 3.540.

**ARS / URA (rosca interna, percussão) — arrancamento, kgf:** S14 (1/4") 1.730 · S56 (5/16") 2.410 · S38 (3/8") 3.360 · S12 (1/2") 4.740 · S58 (5/8") 5.800 · S34 (3/4") 8.170. Linha ARS também em inox.

> Nota Ancora: a carga de arrancamento média é o **limite máximo de laboratório**; aplicar coeficiente de segurança e consultar o cisalhamento na seção "Dados Técnicos" do catálogo.

---

### 6. FISCHER — chumbadores químicos e buchas ✅ CITÁVEL
Fonte: *Catálogo Chumbadores Químicos 2009* (lido). **Cita diretamente a lógica da objeção:** *"Se o uso envolver peso demais para os fixadores de nylon e os de aço não oferecerem ancoragem suficiente, são necessários os fixadores químicos."* Escalonamento: **nylon (leve) → aço → químico (pesado).** Cargas recomendadas já trazem coeficiente de segurança; carga última marcada \\* = falha do aço.

**Chumbador Químico RM (ampola + barra roscada FTR) — concreto, carga recomendada de tração (gvz, C20/25), kgf:** M8 830 · M10 1.170 · M12 1.720 · M16 2.610 · M20 4.440 · M24 6.580 · M30 8.520. Cisalhamento M8 540 → M30 8.330.

**FIS EM 390/1100 (epóxi) — concreto/tijolo maciço, ferros de construção CA-50 —** recomendada tração M8 840 → M30 11.000 kgf; ferro ø8 1.070 → ø28 11.130 kgf.

**FIS V 360 / FIS VS 300 T (viniléster híbrido) — concreto, bloco, tijolo maciço e oco —** recomendada tração M6 400 → M30 5.650 kgf.

**FIS P 300 (bucha química) — tijolo maciço/perfurado, bloco oco, concreto (explícito: "cargas leves sem função estrutural"):** alvenaria M6 tração 112 / cisalh. 150 kgf; M10 235/352. Concreto barra roscada M6 270 → M30 3.790 kgf.

**Buchas de nylon fischer:** linha completa citada ("Fixações em Geral — Buchas") mas **sem tabela de carga neste catálogo** → ⚠️ para valor de bucha em drywall/alvenaria, abrir catálogo de buchas específico.

---

### 7. HILTI — ancoragens e fixação à pólvora ⚠️ REFERÊNCIA
Fonte: *Catálogo Técnico Hilti* (índice lido; corpo é catálogo extenso de concreto/aço/pólvora). Documenta sistemas DX (fixação à pólvora), ancoragens mecânicas e químicas, corrosão e materiais base, com software próprio de dimensionamento.

**Valores de carga por âncora não foram extraídos como texto limpo** (tabelas por página, catálogo grande). Foco Hilti = concreto e aço estrutural, **não drywall**. ⚠️ Não cravar carga Hilti sem abrir a tabela do produto específico.

---

## Tabela consolidada

| Fixação | Tipo | Substrato | Carga / spec | Fabricante | Status |
|---|---|---|---|---|---|
| Parafuso 4,2 mm flangeado ponta broca | Autoperfurante | Chapa de aço (steel frame) | Arranc. 1,15–1,95 kN · cisalh. 2,25–4,52 kN | Ciser | ✅ |
| Parafuso 4,8 mm sextavado flangeado | Autoperfurante | Chapa de aço | Arranc. 1,20–2,25 kN · cisalh. 2,30–4,98 kN | Ciser | ✅ |
| Parafuso p/ placa cimentícia (asas) | Autoperfurante | Cimentícia + aço | 4,2×32 mm, chata dentada | Ciser | ✅ |
| Parafuso p/ placa OSB/Performa | Autoperfurante | OSB/Performa + aço | 4,2×32 mm, chata dentada | Ciser | ✅ |
| 10g Dual Thread (#10 / 4,8 mm) | Autoperfurante steel framing | Aço 0,55–2 mm | Tração 11,2 kN · cisalh. 8,6 kN (última) | Framecad | ✅ |
| Parafuso #10-16 SAE 1022 | Autoperfurante | Chapa de aço | Tração 980 kg · cisalh. 712 kg (ruptura) | Bullfor | ✅ |
| Parafuso #14-14 SAE 1022 | Autoperfurante | Chapa de aço | Tração 1.673 kg · cisalh. 1.338 kg (ruptura) | Bullfor | ✅ |
| Chumbador CB 3/8" | Mecânico (torque) | Concreto 20 MPa | Arranc. 2.107 kgf · cisalh. 1.617 kgf | Walsywa | ✅ |
| Chumbador WB 3/4" | Mecânico (presilha) | Concreto 20 MPa | Arranc. 7.708 kgf · cisalh. 9.691 kgf | Walsywa | ✅ |
| Waltog / buchas para oco | Travamento | **Drywall (gesso)** | Fixador indicado p/ placa fina — carga na tabela | Walsywa | ⚠️ |
| Snaptoggle / Walgips | Travamento | Placa fina / aglomerado | Indicado p/ placa oca | Walsywa | ⚠️ |
| Chumbador CBA 3/8" | Mecânico (torque) | Concreto 30 MPa | Arranc. 2.740 kgf · cisalh. 1.237 kgf | Ancora | ✅ |
| Chumbador ARS/URA 1/2" | Rosca interna (percussão) | Concreto | Arranc. 4.740 kgf | Ancora | ✅ |
| Químico RM M12 (barra FTR) | Ancoragem química | Concreto ≥C20/25 | Tração recom. 1.720 kgf · cisalh. 1.250 kgf | Fischer | ✅ |
| FIS P 300 M10 | Bucha química | Alvenaria/bloco oco (carga leve) | Tração recom. 235 kgf · cisalh. 352 kgf | Fischer | ✅ |
| Buchas de nylon | Expansão | Alvenaria/placa (carga leve) | Sem tabela neste catálogo | Fischer | ⚠️ |
| Ancoragens / DX pólvora | Mecânico/químico | Concreto e aço | Consultar tabela do produto | Hilti | ⚠️ |

---

## Fixação de peso em drywall (regra + bucha certa)

**A placa de gesso é vedação, não estrutura.** Peso nunca "pendura na placa" — vai na estrutura de aço ou em bucha que trava atrás da placa. Três caminhos corretos:

1. **Fixar no montante de aço (o certo para a maioria).** O parafuso autoperfurante encontra o perfil galvanizado — é aí que estão as cargas reais de arrancamento: Ciser 4,8 mm até **2,25 kN** no aço; Framecad #10 até **11,2 kN** de tração. Quem segura é a estrutura.
2. **Reforço embutido previsto em projeto.** TV, armário, bancada, aquecedor, caixa de descarga acoplada, quadro elétrico → **chapa de aço ou madeira tratada entre os montantes**, definida no projeto (NBR 16970). Não improvisar depois de fechada a parede.
3. **Bucha específica de placa oca (item leve fora de montante).** Fixadores de **travamento**: Walsywa **Waltog** / buchas para oco, **Snaptoggle**, bucha basculante/mola, bucha tipo S. Fischer confirma o escalonamento nylon → aço → químico; a **FIS P 300** é explícita para "cargas leves sem função estrutural". A capacidade depende da bucha + placa → **consultar a tabela do fabricante antes de cravar kg**.

**Chumbador químico/mecânico (Fischer RM, Walsywa CB/WB, Ancora CBA)** é para **concreto e alvenaria** — laje, viga, contrapiso — não para a placa de gesso. Entra quando a fixação chega à estrutura de concreto por trás/abaixo do sistema seco.

---

## Frases prontas (ok para post)

- "Drywall segura peso, sim. TV, armário e bancada vão em reforço metálico entre os montantes, previsto no projeto — não na placa. Item leve vai em bucha própria de placa oca."
- "Quem segura o peso é a estrutura de aço, não o gesso. O parafuso de steel frame crava no montante: a Ciser ensaia até 2,25 kN de arrancamento e a Framecad até 11,2 kN de tração — na chapa de aço."
- "Existe bucha certa para cada carga: leve vai em bucha de travamento (tipo Waltog/basculante); peso de verdade vai em reforço ou, no concreto, em chumbador químico. O que a norma proíbe é pendurar tudo na placa."
- "Chumbador químico da Fischer (linha RM) ancora tonelada no concreto — M16 suporta mais de 2.600 kgf de tração recomendada. Mas ele é para a laje/viga, não para o gesso."
- "Regra da Fischer, escrita no catálogo: nylon para carga leve, aço para média, químico para pesada. Fixação tem escala — e cada uma tem seu número ensaiado."

---

## Não escrever

- "Pendura qualquer peso direto na placa de gesso" — falso; peso exige montante, reforço ou bucha de travamento.
- Cravar capacidade de carga em drywall **sem a bucha e a tabela do fabricante** (Walsywa/Fischer não tabelam bucha de gesso neste material — é ⚠️).
- Atribuir **função estrutural** à placa (gesso, cimentícia, Performa/OSB) — a integridade é da estrutura de aço.
- Confundir **carga de ruptura** (Walsywa, Ancora, Bullfor, Framecad "ultimate") com carga de trabalho — sempre aplicar coeficiente de segurança; a de trabalho é uma fração da ruptura.
- Usar carga de **chumbador de concreto** (CB, CBA, RM) como se fosse fixação em drywall — são substratos diferentes.
- Citar número da **Hilti** sem abrir a tabela do produto (aqui só o índice é legível).
- Escrever "placa OSB" em conteúdo Fast → usar **Placa Performa**.

---

## Arquivos-fonte

Pasta raiz **Parafusos e Chumbadores** — `1nqrt2j3d_9PiKIfZsjuG4R_ylAvNSUhm`

| Arquivo | Fabricante | ID | Status |
|---|---|---|---|
| Catalogo Fixação Mecânica 2013 | Walsywa | `1OlvcMvVqw1GzzU4-mXrrjP33-e3jytW_` | ✅ lido |
| fixacao_mecanica (versão anterior) | Walsywa | `1aKdCkM0_P857YeOXBkMw9wgSNqDqmlhj` | 🗂️ dup |
| Ficha Técnica CBA 14 | Ancora | `17NASoVzEZuA0MkEuqxSya3Xw5caekGJi` | ✅ lido |
| Ficha Técnica CBA 38 | Ancora | `1USFgdLhzyWKvMVfv704lo6OEen_KJPaq` | ✅ lido |
| Ficha Técnica CBA 56 | Ancora | `1OKB2NeIW57YJZEtrZzcrLDLbYEipg5-P` | ✅ lido |
| Catalogo ANCORA | Ancora | `11XgaWzBQalIW1aqKNKuCHBPO5w9ZXOJV` | ✅ lido |
| CATALOGO HILTI | Hilti | `1ZUpZzuNNeNniq1aiscbes3U-2HLJJ3nY` | ⚠️ índice lido |
| Catalogo Steel Frame CISER | Ciser | `1DOCPbX9y_Ab2lPtf8lKVMYUzaDfG-UhQ` | ✅ lido |
| Catálogo Geral de Produtos | Ciser | `1MwAJktsBifUUIlxXAtmKxnAC4ysKvB0Z` | 🗂️ linhas SF/drywall |
| Certificado parafuso Framecad 4,8 (ficha 002589) | Framecad | `1f70w2b6kdkKLgiuywM4MeOmnAWOGSsy7` | ✅ lido |
| FRAMECAD Fasteners catalogue | Framecad | `1nZXLDm6ZuUxfiW5GH1oanisw0wOxPc8L` | ✅ lido |
| Instrução Aço e Parafuso (Gyp/Brasgips) | Framecad | `1CpIeQyaVx-VLfn9j60ghakTCii1FjcrF` | ✅ lido |
| Certificado Resistência Mecânica SAE 1022 | Bullfor | `1ipyNMdtEmRUmgeF2wLgGGqXGEdb3FPTN` | ✅ lido |
| Catalogo Autoperfurantes Construção Seca | Bullfor | `1jmrtxqtUZ12w0vl_lQUZiCJFo3hWPpoe` | ✅ lido |
| Tabela NIBRA Bullfor (drywall/cimentícia/OSB) | Bullfor | `1wIMt9TTmuh0_7VikqP8aXRM7Wrp-kLGG` | ✅ lido |
| Certificado Corrosão Zincado (>276 h) | Bullfor | `1xKKx9eSMBwDAbmNLY-3tOGD0HAcjs5WU` | ✅ lido |
| Catologue Chemical Anchors 2009 | Fischer | `1JF-tqYUyZSDIpptPfOrqhTUxbpvK--yX` | ✅ lido |

> Não citáveis como dado técnico (comercial/administrativo, mantidos só como registro): notas fiscais e certificados de lote Ciser (`1RgsFBD6yshvwi_z_9kA8iXc2ZZbaSJj6`, `16lTcIeRg0E5op2TKSHZTG4PcrfkK7zZg`, `1Mcr37JdObSlaj6qUIoe9Npe3F6j5hds6`), tabelas de barra roscada/preços Ciser, Sales Quotation Framecad (`1pLJA7bu3aRC1cPLr_rEpBMNMjMZY7tFj`), catálogo Bullfor em imagem (`1lX10jntHdVoV4QoaHXExd271rGrTK6aN`).
