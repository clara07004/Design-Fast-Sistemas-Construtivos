# Laje Seca (Steel Deck) e Placa MgO

> Resumo técnico dos documentos oficiais **Metform** (Steel Deck, pasta Drive `1UF-Nm9vIVbzdCUpmOkbDsNXCuWVfLb5V`) e **FRAMECAD Pro-mag** (Placa de Magnésio / MgO, pasta Drive `1RWH8YfAlBblcHBWQwE9Ql8pzTaeaUudd`). Fonte para citar dado técnico em conteúdo. **Não inventar spec:** o que não estiver aqui, abrir o documento-fonte pelo fileId (lista no final).
>
> **Legenda de status:**
> - ✅ **CITÁVEL** — dado literal de manual/catálogo do fabricante. Pode ir para post.
> - ⚠️ **REFERÊNCIA** — dado de apoio, aproximado, com ressalva de edição/data/norma, ou que exige conferência antes de virar número de post (principalmente ensaios de produto importado a validar contra norma brasileira).
>
> **Regra de ouro (construção a seco):**
> - **Steel deck é FÔRMA COLABORANTE** (fôrma incorporada / telha-fôrma). Ele forma uma **laje mista aço-concreto**: a chapa de aço trabalha junto com o concreto. Não é "laje pronta" — depende do concreto e da armadura de retração para funcionar. Quem dimensiona é engenheiro habilitado.
> - **Placa MgO é VEDAÇÃO / fechamento** — interno, externo, forro ou piso sobre estrutura. **Nunca é elemento estrutural.** Quem estrutura é o aço (light steel frame dimensionado por profissional habilitado). A placa fecha, veda e recebe acabamento.

---

## ⚠️ Correção de premissa — reação ao fogo da placa MgO

A placa MgO Pro-mag **não é Euroclasse A1**. O próprio guia técnico do fabricante classifica-a como **A2-s1, d0** pela norma **BS EN 13501-1 +A1:2010** ("não queima, emite fumaça com fogo aberto"), e como **classe A** pelos ensaios americanos **UL 055 / ASTM E84** (Flame Spread ≤ 5, Smoke Developed 0). É **não combustível na prática**, mas contém aglomerante mineral, por isso Euroclasse A2 e não A1. Em conteúdo, escrever "não combustível, classe A / Euroclasse **A2-s1,d0**" — não "A1". ✅ CITÁVEL

---

## Laje steel deck (vãos, sobrecarga, capa)

Fonte: catálogo **Metform — "Steel Deck: a solução definitiva em lajes"** (arquivo Drive; documento sem data de revisão explícita, referência normativa **NBR 14323**). Fabricante Metform (unidades Betim-MG e Taubaté-SP), Sistema de Gestão da Qualidade **ISO 9001**. ⚠️ REFERÊNCIA quanto à vintage do catálogo (base normativa antiga — ver nota no fim da seção); ✅ CITÁVEL quanto às specs físicas do produto.

### O que é
O Steel Deck Metform tem **dupla função**: serve de **fôrma para o concreto durante a construção** e de **armadura positiva da laje para as cargas de serviço**. Constitui, com a estrutura metálica, uma **laje mista aço-concreto**. As nervuras largas permitem usar **conectores de cisalhamento (stud bolts)**, o que possibilita o cálculo de **vigas mistas** e reduz o peso da estrutura. ✅ CITÁVEL

### Dois modelos ✅ CITÁVEL
| Modelo | Largura útil | Altura da nervura (fôrma) | Aplicação típica |
|---|---|---|---|
| **MF-50** | 915 mm | 50 mm | Edificações urbanas: hotéis, hospitais, escritórios, edifícios, garagens |
| **MF-75** | 820 mm | 75 mm | Empreendimentos industriais e lajes com necessidade de resistência a cargas elevadas |

> O número do modelo = altura da nervura da telha-fôrma (50 mm ou 75 mm). A "capa de concreto" (cobrimento) é a altura total da laje **menos** a altura da nervura. Ex.: MF-75 com laje de 140 mm = **75 mm de deck + 65 mm de cobrimento**. ✅ CITÁVEL

### Materiais ✅ CITÁVEL
- **Aço** galvanizado **ASTM A653 Grau 40 (ZAR-280)**, tensão de escoamento **fy = 280 MPa**. Pode ser pintado eletrostaticamente na face inferior.
- **Espessuras da chapa (telha-fôrma):** **0,80 / 0,95 / 1,25 mm**. Comprimento **até 12 m**, conforme projeto.
- **Concreto** convencional, resistência mínima à compressão **fck ≥ 20 MPa**; densidade adotada 2.400 kg/m³.
- **Armadura de retração** em tela soldada, nas duas direções, área mínima **0,1% da área de concreto acima do topo do deck** (evita fissuras por retração/temperatura). Prever ainda armaduras localizadas sobre vigas e pilares.

### Altura da laje, capa e peso próprio ✅ CITÁVEL
- **Altura total da laje:** MF-50 de **100 a 170 mm**; MF-75 de **130 a 200 mm** (faixas das tabelas de carga).
- **Lajes de piso:** recomenda-se altura total de concreto **≥ 140 mm**.
- **Peso próprio da laje:** MF-50 de **1,85 a 3,54 kN/m²**; MF-75 de **2,27 a 3,97 kN/m²** (cresce com a altura).
- **Consumo de concreto:** MF-50 **0,075 a 0,145 m³/m²**; MF-75 **0,0925 a 0,1625 m³/m²**.
- **Largura de apoio recomendada:** MF-50 → 50 mm (apoios externos) / 100 mm (internos); MF-75 → 75 mm (externos) / 150 mm (internos).

### Sobrecarga (carga sobreposta) ✅ CITÁVEL
- Tabela de cargas elaborada para **cargas uniformemente distribuídas**; cargas lineares/pontuais exigem consulta ao Departamento Técnico da Metform.
- A **carga sobreposta máxima** tabelada chega ao teto de **20,00 kN/m²**. Cresce com a espessura da chapa e a altura da laje, e cai com o aumento do vão. Exemplos (MF-50, laje 100 mm, vão 1.800 mm): **9,31 kN/m²** (0,80) · **11,68 kN/m²** (0,95) · **16,43 kN/m²** (1,25).
- Peso próprio da laje **não** precisa ser somado à carga sobreposta ao usar a tabela.

### Vãos máximos SEM escoramento (exemplos-âncora) ✅ CITÁVEL
Dentro desses vãos, **dispensa escoramento** durante a concretagem; acima deles, escorar.

| Config. | MF-50, laje 100 mm (0,80 / 0,95 / 1,25 mm) | MF-75, laje 130 mm (0,80 / 0,95 / 1,25 mm) |
|---|---|---|
| Vão simples | 2,05 / 2,55 / 3,20 m | 2,35 / 3,00 / 3,65 m |
| Vãos duplos | 2,80 / 3,15 / 3,80 m | 3,20 / 3,65 / 4,30 m |
| Vãos triplos | 2,90 / 3,25 / 3,80 m | 3,30 / 3,75 / 4,40 m |
| Balanço | 0,90 / 1,10 / 1,45 m | 1,15 / 1,35 / 1,65 m |

> Para lajes mais altas os vãos caem (ex.: MF-50 laje 170 mm, vão simples 1,05/1,50/2,45 m; MF-75 laje 200 mm, vão simples 1,40/1,95/2,90 m). Os números completos por altura estão nas tabelas do catálogo — usar como referência e confirmar com o projeto.

### Vantagens construtivas ✅ CITÁVEL
- Dispensa escoramento (dentro dos vãos de tabela) e reduz desperdício de material.
- Rapidez e facilidade de instalação; alta qualidade de acabamento inferior da laje.
- Funciona como **plataforma de serviço e proteção** para operários no pavimento inferior.
- Facilita passagem de dutos das instalações e fixação de forros.

### Incêndio ⚠️ REFERÊNCIA
- Os valores de carga da tabela valem em temperatura ambiente **ou em incêndio com atuação de até 30 minutos**. Acima de 30 min, consultar a **NBR 14323** para considerar as armaduras adicionais na resistência nominal.

> **Nota normativa (importante antes de citar em post):** o catálogo referencia a **NBR 14323** (dimensionamento em situação de incêndio de estruturas de aço/mistas). O dimensionamento de lajes mistas com fôrma de aço incorporada hoje se apoia também na **NBR 8800** (projeto de estruturas de aço e mistas de aço-concreto). Tratar as tabelas como **referência de fabricante** — o dimensionamento real (vão, capa, sobrecarga, escoramento) é sempre do **engenheiro habilitado**.

---

### Anexo — Tecno Deck WPC (produto diferente: NÃO é laje)

Fonte: **Manual Tecnodeck 01/2012** (arquivo Drive). ✅ CITÁVEL para specs; ⚠️ produto europeu/2012, conferir linha vigente.

> ⚠️ **Atenção para não confundir:** "Tecno Deck WPC" é um **piso/deck de madeira plástica (WPC — compósito madeira-termoplástico)** para uso **peatonal** (terraços, piscinas, passarelas). **Não tem relação com laje steel deck.** A palavra "deck" é a única coisa em comum. Nunca cruzar specs de um com o outro.

- Compósito **WPC** (madeira + termoplástico). Uso peatonal privado e comercial de média intensidade.
- Modelos: **Tecnodeck ONE** e **Tecnodeck HS** (comercial, maior desgaste).
- Tábua (tablón): **espessura 25 mm**, **largura 140 mm**; comprimentos 2 / 2,5 / 3 / 4 m (5 e 6 m sob consulta).
- Peso: ONE **2,38 kg/m**; HS **3,20 kg/m**. Cores: Tropical Brown, Sand Brown, Vulcano Black (Colorado Red sob consulta).
- Características técnicas: densidade **1,30 g/cm³**; absorção de umidade **0,30%** (peso) / 0,17% (volume); resistência à tração **22,5 MPa**; módulo de ruptura **22,0 MPa**; resistência à flexão **22,5 MPa**; módulo de elasticidade **2.400 MPa**; resistência à compressão **26,4 MPa**; coef. de dilatação térmica 4,9×10⁻⁵ (mm/mm)/°C.
- Ensaios: **TÜV Rheinland** (Berlim), relatório nº 21136167001; **LNEC** (Portugal), boletim B42BPR06 (09/06/2006).

---

## Placa MgO (specs, fogo, aplicação)

Fonte: **Guia Técnico Placa de Magnésio FRAMECAD Pro-mag™ 2014** + **Relatório de Rating de Sub-conjuntos MGO Board (18/05/2014)** + label do **Sistema de Acabamento MGO**. Fabricação em conformidade **ISO 9001**, processo de autoclave de alta pressão; ensaios de origem **SGS SP120100028 (Shanghai, jan/2012)**. **Produto importado (FRAMECAD, sede Nova Zelândia; fabricação China).** ✅ CITÁVEL para as specs de fabricante; ⚠️ REFERÊNCIA para desempenho — ver nota de norma brasileira ao fim.

### O que é
Placa de **óxido de magnésio (MgO)**, material de fechamento **não combustível** e com isolamento térmico. Composição: pó de perlita, cloreto (magnésio) e óxido de magnésio, entre **duas camadas de malha de fibra de vidro**. **Sem amianto, sem sílica, sem formaldeído, sem COV.** Usada como **alternativa ao drywall de gesso**: pode ser riscada e destacada, serrada, furada e parafusada a **estrutura de aço leve (LGS/steel frame)**. ✅ CITÁVEL

### Espessuras, dimensões e aplicação ✅ CITÁVEL
| Espessura | Aplicação | Comprimentos | Largura |
|---|---|---|---|
| **4,5 mm** | Sofito / forro | 2.400–3.600 mm | 1.200 / 1.220 mm |
| **6 mm** | Forro / revestimento | 2.400–3.600 mm | 1.200 / 1.220 mm |
| **9 mm** | Revestimento interno e externo (também borda afilada TE ou quadrada SE) | 2.400–3.600 mm | 1.200 / 1.220 mm |
| **12 mm** | Revestimento | 2.400–3.600 mm | 1.200 / 1.220 mm |
| **18 mm** | **Pisos** | 2.400–3.600 mm | 1.200 / 1.220 mm |

- Pode ser usada em aplicações **internas ou externas**; revestimento de parede e teto, revestimento exterior, fáscias, sofitos, apoio para ladrilhos e isolamento de piso.
- Junta de **3 mm entre placas**, preenchida depois. Fixadores a no mínimo **12 mm da borda** e **50 mm dos cantos**.

### Propriedades físicas ✅ CITÁVEL
| Propriedade | Valor |
|---|---|
| Densidade | **1.120 kg/m³** (70 lb/ft³) |
| Resistência à flexão | **15,4 MPa** (2.234 psi) |
| Tensão de compressão | **3,98 MPa** (577 psi) |
| Condutividade térmica | **0,15 W/m·K** |
| Absorção de umidade (índice reportado) | **11** |
| Dilatação (swelling) | **0,34%** |
| Resistência sonora (placa isolada) | **40 dB** |
| Resistência à combustão | **Classe 1** (acima de 3 mm) |
| Freeze/thaw (ASTM C1185) | Pass ≥ 80% (testada 36 meses) |
| Mofo/fungo/inseto | Não nutriente (**ASTM G-21**) |

### Reação e resistência ao fogo ⚠️ REFERÊNCIA (validar contra norma BR)
- **Não combustível**, **classe A** por **UL 055 / ASTM E84** (Flame Spread ≤ 5; Smoke Developed 0); **Euroclasse A2-s1, d0** por **BS EN 13501-1 +A1:2010**. **(Não é A1 — ver correção no topo.)**
- O fabricante afirma que o sistema pode alcançar **até 4 horas de resistência ao fogo com instalação correta** — isto vale para **montagens específicas ensaiadas/comparadas por normas internacionais (ASTM E119, UL, AS/NZS)**, não é propriedade da placa isolada.
- Para uso em sistema com classificação de fogo: espaçamento dos montantes **≤ 400 mm c/c** e das fixações **≤ 800 mm c/c**.
- **Resistência sonora:** classificação **STC 53–54** (aprovação NYC MEA #359-02-M) — este número é de **sistema/montagem**, não da placa nua (a placa nua é ~40 dB).

**Ratings de montagem (partições interiores não estruturais, LGS + MgO nos dois lados)** — do relatório FRAMECAD, estabelecidos por **ensaio quando disponível e por comparação/cálculo com montagens publicadas nos EUA/Austrália/NZ/África do Sul** (ASTM E119, UL): ⚠️ REFERÊNCIA
| Montagem | Placa (ambos lados) | Isolamento na cavidade | Resistência ao fogo | Acústica (STC) | Térmico (m²·K/W) |
|---|---|---|---|---|---|
| 3 | 9 mm | Não | ~30 min | 33 | 0,18 |
| 4 | 9 mm | Sim (40 kg/m³) | ~30 min | 40 | 1,40 |
| 5 | 12 mm | Não | ~60 min | 34 | 0,20 |
| 6 | 12 mm | Sim (40 kg/m³) | ~60 min | 42 | 1,54 |

> Estes ratings são referências internacionais de **montagens não estruturais** com estrutura de aço leve FRAMECAD. Servem de base técnica, **não** substituem ensaio/laudo brasileiro para citar TRRF em post (ver nota de norma BR).

### Sistema de acabamento MGO (label FRAMECAD) ✅ CITÁVEL (como descrição de sistema)
Sistema de revestimento sobre a placa: primer para MgO (FC MGO primer / FC Limelock primer) → composto de assentamento e camada de nivelamento (FC Bedding compound) → reforço com tela de fibra de vidro (FC Fibreglass Reinforcing) → membrana impermeável (FC waterproof membrane) → acabamento texturizado mineral (FC FAST mineral texture finish). Atributos declarados: resistente a impacto (reforçado com fibra de vidro), acabamento texturizado aplicado à mão, superfície impermeável, sistema de cor total, **BRANZ Appraised** (aprovação neozelandesa).

### Instalação / fixação ✅ CITÁVEL
- Fixada em perfis de aço conformado a frio (steel frame), tipicamente perfil C **89 × 39 mm**, aço 0,75 / 0,95 / 1,5 / 1,55 mm.
- Parafusos FRAMECAD X-Drive (10 g / 4,8 mm, ponta perfurante, 25 mm) e cabeça chata Phillips (6 g, 32 mm), a **300 mm c/c**; a 50 mm dos cantos e 12 mm da borda.
- Corte: faca de ponta de carboneto (risca-e-quebra) ou ferramenta elétrica com coleta de pó.
- Armazenar plano, coberto e seco; se molhar, secar antes de instalar; transportar na vertical.

> **Nota de norma brasileira (conferência obrigatória):** a placa MgO é **produto importado**, ensaiado por **normas ASTM / UL / EN / SGS** — **não** há laudo brasileiro (ABNT / IT do Corpo de Bombeiros) transcrito aqui. Para citar **reação ao fogo** ou **TRRF (tempo de resistência ao fogo)** em conteúdo destinado ao mercado brasileiro, é preciso **ensaio/laudo local ou equivalência formal**. Além disso, atenção ao **teor de cloreto** (composição com cloreto de magnésio) e à **absorção de umidade (índice 11)**: em uso externo/úmido no clima brasileiro, exige projeto e proteção adequados — não vender como "à prova d'água" sem essa ressalva. Marcar todo dado de fogo/umidade como ⚠️ REFERÊNCIA até validação.

---

## Frases prontas (ok para post)

**Steel deck / laje seca**
- "A laje steel deck é uma **laje mista aço-concreto**: a telha-fôrma de aço galvanizado funciona como fôrma durante a concretagem e como armadura positiva depois do concreto curado." ✅
- "O Steel Deck Metform vem em dois modelos — **MF-50** (nervura 50 mm, largura útil 915 mm) e **MF-75** (nervura 75 mm, largura útil 820 mm) — em aço galvanizado **ASTM A653**, espessuras **0,80 / 0,95 / 1,25 mm** e até **12 m** de comprimento." ✅
- "Dentro dos vãos de tabela, o steel deck **dispensa escoramento** e ainda serve de **plataforma de trabalho e proteção** para quem está no pavimento de baixo." ✅
- "A laje steel deck usa concreto de **fck ≥ 20 MPa** e **tela soldada de retração** (mínimo 0,1% da área de concreto acima do deck). O dimensionamento é sempre do engenheiro (NBR 14323 / NBR 8800)." ✅
- "Nervura larga do steel deck permite **conectores stud bolt** e cálculo de **viga mista** — mais leve e mais rápido que a laje maciça convencional." ✅

**Placa MgO**
- "A placa de magnésio (MgO) é **fechamento não combustível**: veda e reveste, mas **não estrutura** — quem estrutura é o aço do steel frame." ✅
- "A placa MgO Pro-mag tem densidade de **1.120 kg/m³**, resistência à flexão de **15,4 MPa** e é **não combustível — classe A (ASTM) / Euroclasse A2-s1,d0 (EN 13501-1)**." ✅
- "MgO existe de **4,5 a 18 mm**: 4,5–6 mm para forro/sofito, 9–12 mm para revestimento interno e externo e **18 mm para piso**." ✅
- "Placa MgO é **sem amianto, sem sílica e sem formaldeído**, fixada por parafuso à estrutura de aço leve — corta com faca (risca e quebra), como o drywall." ✅

---

## Não escrever

- ❌ Chamar **steel deck** de "laje pronta" ou dizer que "dispensa concreto/armadura". É **fôrma colaborante** — precisa de concreto (fck ≥ 20 MPa) e tela de retração para virar laje.
- ❌ Confundir **Tecno Deck WPC** (piso de madeira plástica, uso peatonal) com **laje steel deck**. São produtos totalmente diferentes.
- ❌ Publicar vão/sobrecarga como "vale para qualquer obra". As tabelas são **referência de fabricante**; o dimensionamento é do engenheiro habilitado.
- ❌ Chamar a **placa MgO** (ou qualquer gesso/cimentícia/OSB) de "elemento estrutural" ou dizer que "sustenta a casa". É vedação; a estrutura é o aço.
- ❌ Dizer que a placa MgO é **reação ao fogo A1**. É **A2-s1,d0 (EN 13501-1) / classe A (ASTM/UL)**.
- ❌ Citar "**até 4 horas de resistência ao fogo**" ou os ratings de 30/60 min como se fossem propriedade da placa ou laudo brasileiro. São **montagens específicas** ensaiadas/comparadas por normas internacionais — para o Brasil, exige laudo/equivalência (ABNT / IT do Corpo de Bombeiros).
- ❌ Vender a placa MgO como "**à prova d'água**" sem ressalva. É importada, com **cloreto de magnésio** na composição e **absorção de umidade índice 11** — uso externo/úmido exige projeto e proteção; conferir aplicação.
- ❌ Inventar espessura, vão, carga, densidade ou classe de fogo fora do que está tabelado aqui. Fora da tabela → abrir o arquivo-fonte.

---

## Arquivos-fonte (Google Drive)

**Steel Deck / Metform** — pasta `1UF-Nm9vIVbzdCUpmOkbDsNXCuWVfLb5V`
- **METFORM.pdf** (catálogo Steel Deck MF-50 / MF-75; tabelas de carga e vão; base NBR 14323) — `1ZJeOrKl9PF-69ARJJjg15Zj4YqkI3tJy` — ✅ lido (texto e tabelas extraídos via read_file_content; arquivo grande ~32 MB, não precisou render)
- **TECNO DECK WPC.pdf** (piso de madeira plástica WPC — produto distinto) — `1sEFQnH-ZWimih5GRP_AhXeml2VPmU986` — ✅ lido

**Placa MgO / FRAMECAD Pro-mag** — pasta `1RWH8YfAlBblcHBWQwE9Ql8pzTaeaUudd`
- **Pro-mag Magnesium Board Technical Guide 2014** (PT-BR; propriedades físicas, espessuras, fogo, instalação) — `11bKfbUWCcPeyS_kvYCgS4VvShYkDajY8` — ✅ lido
- **Rating Analysis Report — MGO Board** (18/05/2014; ratings de fogo/acústica/térmico por montagem, normas ASTM/UL) — `1b6jrNh1NH7JMOKdByjm9JvFzIKYuDd93` — ✅ lido
- **FRAMECAD_system_MGO_finishing system label** (componentes do sistema de acabamento) — `1DfMuNp_lgzj2OY2b28aRiq3Pr4qtpFVw` — ✅ lido
- Subpastas da pasta MgO **não abertas aqui** (conferir sob demanda): `antigo` (`14kE0FDhoMIfyjQXWK9L4s1AWRbyUkQtO`), `2014_janeiro` (`1Tv5OwJjpnUjYQk9UIT5jkKtdu8DO4LiU`), `Brochures in Portuguese` (`1flouW3eFZLLEK55embjsvZjpnT4fvFNQ`).

> Todos os PDFs retornaram texto completo via `read_file_content` (inclusive as tabelas do Metform) — não foi necessário download/render por PyMuPDF nem criação de diretório temporário.
