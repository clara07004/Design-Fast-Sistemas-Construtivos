# Biblioteca Técnica — Google Drive (ARQUIVOS TECNICOS)

Mapa de navegação da biblioteca de documentos técnicos da Fast, hospedada em um
**Drive compartilhado** do Google (`Fast Drywall e Steel Frame...` → `CONTEÚDO` →
`ARQUIVOS TECNICOS`). É fonte primária de fichas técnicas, catálogos, normas e
manuais de engenharia por fabricante/fornecedor — consultar antes de afirmar
qualquer dado técnico que não esteja em `produtos/`.

**Este arquivo é só um mapa de caminhos.** A biblioteca é grande demais para
baixar ou catalogar arquivo a arquivo (são centenas de PDFs, alguns ZIPs de
gigabytes). Quando precisar de um dado específico:

1. Ache a pasta certa neste mapa (pelo fabricante/tema).
2. Use `mcp__f9539f5b-7cac-4ae9-9a61-d488056e2326__search_files` com
   `query: "parentId = '<ID_DA_PASTA>'"` para listar os arquivos daquela pasta.
3. Priorize arquivos pequenos e leia com `read_file_content` (PDF/DOCX/PPTX) —
   evite baixar ZIPs grandes ou arquivos `.rar`/`.rvt`/`.pl` (não são texto).
4. Ignore `Thumbs.db` (lixo de pasta do Windows, sem valor).

- **Pasta raiz:** `ARQUIVOS TECNICOS` — ID `1_tgdWuyddebKpRfUDowzhObFdn555jGx`
- **Acesso:** compartilhado com `barbosa.claraia@gmail.com` (conta conectada ao
  Google Drive do Claude) em 2026-07-07. Se o acesso for revogado, a pasta some
  das buscas — reconfirmar compartilhamento antes de reportar "não encontrado".
- **Mapeado em:** 2026-07-07.

---

## Estrutura (8 pastas de primeiro nível)

### 1. NORMAS ABNT — `1N4PAE1d8lDtXhiUbwHMWjRlN3eQyejBn`
Pasta **plana** (sem subpastas), 19 arquivos. PDFs oficiais das normas + 1 resumo:
- `NBR 15758.pdf` e `NBR-15758-Drywall-Projeto-Desempenho-Etc-Consulta-Nacional.pdf` (versão de consulta pública)
- `NBR 16970-1.pdf`, `NBR-16970-2_LSF.pdf`, `NBR 16970-3.pdf`
- `NBR 15253.pdf`, `NBR 15217.pdf`, `NBR 6355-2012.pdf` / `NBR-6355.pdf`
- `NBR 14762.pdf` / `NBR-14762.pdf`, `NBR 7008-1.pdf` / `-2.pdf` / `-3.pdf`
- `-nbr-14715 - chapas drywall.pdf`
- `RESUMO DA NBR 16970.docx`
- `OneDrive_2026-03-26.zip` (backup bruto, não abrir por padrão)

> Já absorvido em [produtos/base-normativa-abnt.md](../produtos/base-normativa-abnt.md) e [produtos/desempenho-detalhado.md](../produtos/desempenho-detalhado.md) — consultar aqui só se precisar do PDF original (ex.: citar artigo/página exata).

### 2. DOCUMENTOS DE QUALIDADE — `13xb4b0d5S5uShu-PbTTqbOTowjPwzq3L`
Plana, 3 arquivos — avaliações técnicas (DATEC) de Steel Frame e LP:
`Datec-14-LSF.pdf`, `Datec-15-LP.pdf`, `Datec-16-LP.pdf`.

### 3. MANUAL ESTRUTURA COMPOSTA POR PERFIL FORMADA A FRIO — `156JyQPrUZS1n3RUjw_cbxlu9yUW2J-GQ`
Plana, 1 arquivo: `Manual_Estruturas Compostas por Perfis Formados a Frio_FINAL.pdf`.

### 4. PISO VINÍLICO — `13Ymg8_8AINBwKyKJ7HjIxmWn4W1Lu2V_`
Plana, 1 arquivo: `Pisos Vinílicos - Treinamento básico 1_FAST (1).pptx`.

### 5. TC SHINGLE — `1ZHEkh6GF2Mc7KBn3JhzJ-fLwmhs25qSA`
Plana, 2 arquivos: vídeo institucional (`.mp4`) e apresentação comercial (`.pptx`).

### 6. SINCOL PORTAS — `13ucKby_YipF1fgRSv9w2JKliyXXGsuGC`
Plana, 10 arquivos — portas Sincol: catálogo oficial 2026, coleções (Gourmet,
Touch, Sincolors, Impressione), kit resistente ao fogo, manual Sinkit, arquivos
de showroom Archicad/Revit (`.zip`/`.pl`, não são texto).

### 7. WPC — `1Cc_3b_T0yNoWbg9Lo9oHGBDN9ZGKcHWu`
**Vazia** (0 arquivos) no momento do mapeamento.

### 8. SAINT GOBAINT — `12oOyZXUTzapqyVusGa7vRxz9B5fSHDKW`
A maior e mais profunda — 18 subpastas por fabricante/tema. Ver detalhamento abaixo.

---

## SAINT GOBAINT — detalhamento por fabricante/tema

| Subpasta | ID | Conteúdo | Nível |
|---|---|---|---|
| **ABDI** | `1-jtQFfKnNTI1ak_IZFZnRAvhfyAnBQtN` | 1 arquivo: manual da construção industrializada | Plana |
| **CATALOGOS E FICHAS TECNICAS** | `1twLlmybXaUf418uk9Rbf5h7b4wz9Z1FW` | 18 sub-subpastas por marca — ver tabela seguinte | Tem subpastas |
| **CBCA** | `1U0Atz_NWaZzorxj97_tD4bz0nfepgPm5` | Manuais de engenharia Steel Frame CBCA, painéis de vedação, viabilidade econômica + subpasta `MANUAL STEEL FRAME` (`10EHiZWdN1cJAvyQNfVVgRaJX-4VWQ2wo`) | Tem 1 subpasta |
| **LIVROS E MANUAIS** | `1eaDn5GZYEBDecKAlJsOiWwAuXMmZfHU0` | 6 arquivos: manual projetos drywall, segurança contra incêndio, pintura, resíduos de gesso, resistência mecânica/fixação, **desempenho acústico em drywall** | Plana |
| **DECORLIT** | `1_tIF-czOGbKcFFc7PPZltnpvuXhY3bWP` | 1 arquivo: catálogo Decorlit 2023 (placas cimentícias) | Plana |
| **FRAMECAD** | `1U-ILHGk6BR0rfFEYR5uFUuhmEcuMsuEF` | 10 arquivos: treliças de aço, estrutura formada a frio, catálogos FC Fasteners/Connectors | Plana |
| **PREVENCAO CONTRA INCENDIO** | `1dAU_LlcFDnpEJsTPuCKMlfKgNOHdKw3R` | 1 arquivo: manual de prevenção contra incêndio | Plana |
| **DRYWALL MASTER** | `1hDh5GxWw_5-sHrC7GM0ijCyegPuLA5nt` | 7 arquivos: normas internas numeradas (RRM, ACA, CHA, MES, PIN, INS, MGU) | Plana |
| **BRASILIT** | `11FlutBcRqwCenm27JTvEuJkdVM0nQ-pM` | ~20 arquivos: telha shingle, veda-calha, placas Aquaroc FC (piso/parede), manta de telhado, **Guia Técnico Brasilit 2026**, placas cimentícias | Plana |
| **ECOFRAME ESQ PVC** | `18PEoOpdYIeL9T1v5C1lr3HgJm6unXaYb` | 1 arquivo: Cebrace PVC Steel Frame Glass | Plana |
| **ECOPHON** | `1oll7vKh-cHU7uaoEc9HX3PbQZJXPSnmK` | ~30 arquivos: catálogos por linha (Akusto, Master, Solo, Focus, Super G, Hygiene), guias de design acústico por segmento (saúde, educação, escritório, telessaúde) + subpasta `POR PRODUTOS` (`1jYbtcJnZUUYoFqyQliKx6XlBzpHNArfJ` → tem subpasta `ECOPHON FOCUS A`, `1m5MzC5VooCLQ5d1Wyrjoqbq3g8Ol04KR`) | Tem subpastas |
| **NORTON** | `1BuXhctJwQzMZEIPnkW7s73Zh50D5se6f` | 11 arquivos: catálogos de abrasivos por segmento (automotivo, construção, indústria) | Plana |
| **TEK BOND** | `1aLqI2QXSJpj475KAEeU5FDBbutwrg8DW` | 11 arquivos: catálogos de adesivos por segmento (construção, automotivo, moveleiro, calçadista) | Plana |
| **CEBRACE** | `1OqfYd3bDDlFb94GLwOVMIF94SJTJAi8c` | ~24 arquivos: catálogos de vidro (Habitat, **resistente ao fogo**, ThermoVision, texturizados, interiores), guias de limpeza/fixação | Plana |
| **PLACO** | `1FvHb44sdSfmM6hcHHqWRDpM9t9fRolYx` | 2 apresentações soltas (VAB Sistemas GRX/Performa/Adfors, PREVOT Fast 2026) + subpasta `PLACO` aninhada (`1ZPPo3xte9qWfoTBzRt0wTbIlY1pT7lsK`) com: `TESTE E CERTIFICADOS`, `PLACO BRASIL`, `PLACO ESPANHA`, `WHITE BOOK`, `DRYWALL` | Tem subpastas |
| **ADFORS** | `1QEyJMSpcsNOebJELKJRrB-FZKjuTWQaR` | 1 arquivo: catálogo técnico (tela/fibra de reforço) | Plana |
| **ISOVER** | `1WnuPJKfnNAD_F-Lu4GimhykkqNB_fdt0` | ~35 arquivos: catálogos de lã de vidro (Climaver, Facefelt, Flexliner, Wallfelt, HVAC, coberturas) | Plana |
| **QUARTZOLIT** | `1j75uIHeV2b_09LMYPS2z6ubt97fINWty` | ~28 arquivos, maioria ZIPs grandes "WEBER_ProductDocumentation_*" (documentação de produtos Weber/Quartzolit — alguns >100 MB, não baixar sem necessidade específica) | Plana |

### CATALOGOS E FICHAS TECNICAS — sub-subpastas (`1twLlmybXaUf418uk9Rbf5h7b4wz9Z1FW`)

| Sub-subpasta | ID | Conteúdo | Nível |
|---|---|---|---|
| **PARAFUSOS E CHUMBADORES** | `1nqrt2j3d_9PiKIfZsjuG4R_ylAvNSUhm` | Sem arquivo direto — 7 subpastas por marca: `Walsywa`, `BULLFOR`, `HILTI`, `FRAMECAD`, `ANCORA`, `CISER`, `FISCHER` — todas detalhadas abaixo | Tem subpastas (detalhado) |
| **STO CORP** | `16EOgXidL4o_4v29WsuTAuBwFG1C9IhRq` | Fichas EIFS/XPS (Sto) soltas + subpastas `FOTOS treinamento 23 07 2014`, `DETALHES TÉCNICOS` — detalhadas abaixo | Tem subpastas (detalhado) |
| **OWENS CORNING** | `1GhBc7p9vvs5qsBUhqO8dVkQ0VhLXakbp` | Fichas técnicas Foamular XPS e lã de vidro soltas + subpastas `Owens Corning Bill Tolliver`, `TESTES E LAUDOS Foamular` — detalhadas abaixo | Tem subpastas (detalhado) |
| **AÇO** | `17LLyZ3qupd3HqwN_E0higfFEPbmJrVXA` | Sem arquivo direto — subpastas `GYPSTEEL`, `AKZONOVEL-PINTUTA STEEL`, `CBCA`, `GERDAU`, `CSN`, `ARCELORMITTAL`, `FRAMECAD` — detalhadas abaixo | Tem subpastas (detalhado) |
| **FRAMECAD** | `1RWH8YfAlBblcHBWQwE9Ql8pzTaeaUudd` | Fichas MGO board soltas + subpastas `Brochures in Portuguese`, `2014_janeiro`, `antigo` — detalhadas abaixo | Tem subpastas (detalhado) |
| **BRASILIT** | `1xppkSef3coVFz-Pl7oAFozAgOj1WsyhA` | ~18 arquivos: placas cimentícias, telhas fibrocimento, garantias, **resistência ao fogo (30/120 min)**, **acústica 57 dB**, desempenho térmico | Plana |
| **OWA** | `1aJHJtz6X0Ywcul_qHZe4LSuduz26bhmV` | 6 arquivos: forros OWA (higiene, acústico, proteção contra fogo) | Plana |
| **TELHA** | `1EehWZEwY1bUJEjJImYNplonbguaCzLko` | 2 arquivos: Eternit, Prada | Plana |
| **PORTA DE ROLAR** | `1kxTWvz3yDbUb5JYoN9SgN5VG5bVsYELC` | 2 arquivos: Rolltor | Plana |
| **PAREX** | `155Dao-wlMe7PBKPvh-Xdy6y_7E0HLOTy` | 6 arquivos: fichas técnicas de revestimento Parex | Plana |
| **PANEL REY** | `1T1NX6KgrZJcsjB5fCX8hSIaRHRakNY7C` | ~7 arquivos: painel de gesso GlassRey (fachada EIFS/DEFS) | Plana |
| **PLACLUX** | `16imZdJhdXD_fJvJH3W5Zmvkrcx5nSWPM` | 4 arquivos: ProFort DS (placa cimentícia), ensaio de fogo | Plana |
| **AMANCO** | `1qASNeLBBXUFy1dM6J1JwKNaEOTRgYUz9` | 1 arquivo: catálogo predial | Plana |
| **STEELDECK** | `1UF-Nm9vIVbzdCUpmOkbDsNXCuWVfLb5V` | 2 arquivos: Tecno Deck WPC, Metform | Plana |
| **STEEL COLORS** | `1YnmNRM6PhdxC-QK_Da3ca6N6YM77oEA7` | 3 arquivos: treinamento Steelcolors/Gypsteel¹, guia CSN | Plana |
| **ISOVER** | `1r5X4kuwNmh_WBSckp7hzA2WreLE1Y8Ja` | 4 arquivos: painéis PSI, catálogo/certificado/FISPQ de lã de vidro | Plana |
| **FACHADAS** | `1NOSOYNQgC6yvGggx44-HgCTnqB2zuk7S` | Estudos/planilhas de fachada soltos + subpastas `RECEBIDOS - KHSS`, `MIDIA - VIA`, `HYATT - METODO`, `BELMETAL` — detalhadas abaixo | Tem subpastas (detalhado) |
| **LP** | `1nB3FFQrE3DBVglv33CxtDEYtSL7XTIei` | Relatórios técnicos de ensaio soltos (choque térmico, impacto, estanqueidade, RTA) + subpastas `FOGO`, `RES. MECÂNICA`, `CATALOGO`, `ACÚSTICA`, `GARANTIAS` — detalhadas abaixo, **⚠️ conteúdo é sobre OSB (descontinuado)** | Tem subpastas (detalhado) |

¹ "Gypsteel"/variações — por regra interna, tratar como **CCN** ao citar em conteúdo (ver skill `gypstell-alias`).

---

## Detalhamento nível 5-6 — dentro das subpastas por marca

Todas as pastas que na seção anterior estavam marcadas "não exploradas" foram abertas. O que segue é o fundo da árvore — a partir daqui, poucas pastas ainda têm subpastas (listadas no fim desta seção como "ainda não abertas").

### Dentro de PARAFUSOS E CHUMBADORES (7 marcas)
| Marca | ID | Conteúdo |
|---|---|---|
| **Walsywa** | `1nOBY_Wnx1OQTl6cQ4m-3fEDFgCIlK3F6` | 2 arquivos: catálogo de fixação mecânica |
| **BULLFOR** | `1Uu_w-DFgfUr24ZQCdQPKClVhpt-SE07_` | 6 arquivos: catálogo de autoperfurantes p/ construção seca, certificados de corrosão e resistência mecânica |
| **HILTI** | `1fM0OzrxmCRuKCy9QRyK03CMjLudOyvuq` | 1 arquivo: catálogo geral Hilti |
| **FRAMECAD** | `1W9Qn71ymmdn2wZnpqlFSOfO4AItM9j_t` | 4 arquivos: certificado de parafuso, fasteners, instrução aço/parafuso |
| **ANCORA** | `1LiMdxHnBMw-04y_PvPGU6VISaoWiWgz9` | 4 arquivos: fichas técnicas CBA (14/38/56), catálogo Âncora |
| **CISER** | `1fVnddi1cOKKxT_Wv1aoVMXi0UTa_rcdG` | 7 arquivos: catálogo geral e Ciser, certificados, tabelas de barra roscada |
| **FISCHER** | `1oFPo-_hkUUiMU7886oMhAAtV86YQDu5E` | 1 arquivo: catálogo de chumbadores químicos (chemical anchors) |

### Dentro de STO CORP (EIFS/fachada)
| Subpasta | ID | Conteúdo |
|---|---|---|
| **FOTOS treinamento 23 07 2014** | `1aHz9I2Nh4K8IQJk_y1vNZLm495jGsbs8` | ~45 fotos JPG de treinamento de obra + Thumbs.db — baixo valor técnico, só ilustrativo |
| **DETALHES TÉCNICOS** | `1OPK4rlN8ShdNB5aXhVCtXyEejN1DJQe2` | ~60 PDFs de detalhes construtivos EIFS numerados (ex. "10.25a page layout") + arquivos `.dwg` (CAD) correspondentes + subpasta `Nova pasta` (`1eLoNTCzK1-qQnvp5_gCJH80S49Vb4hs5`, não aberta — nome genérico sugere pasta de rascunho) |

### Dentro de OWENS CORNING
| Subpasta | ID | Conteúdo |
|---|---|---|
| **Owens Corning Bill Tolliver** | `1hEI3dzU38rvOALiuSl_k2dQxsQEFd3Dn` | 9 arquivos: treinamento de acústica ("Fundamentos da Acústica"), manual EIFS, guia de controle de som, tabela STC/ICC |
| **TESTES E LAUDOS Foamular** | `1IoDiOMFwCiZsxYHqJvh9gbnxpRVi9yfl` | 8 arquivos: ensaios do isolante XPS Foamular — **NBR 11948 (retardante a chama)**, condutividade térmica, absorção de água, permeabilidade ao vapor, massa específica |

### Dentro de AÇO (7 marcas)
| Marca | ID | Conteúdo |
|---|---|---|
| **GYPSTEEL¹** | `1HmShhNHlQvoOSxTxsJdeV9AKJ-bJg176` | 5 arquivos: certificados de parafusos e de aço (0,80/0,95/1,25mm), catálogo técnico de parafusos |
| **AKZONOVEL-PINTUTA STEEL** | `1S9-eg9LX4kesFr3s5ZvfRVCBY8kC7qwL` | 2 arquivos: 1 foto + Thumbs.db — sem valor técnico |
| **CBCA** | `1vP9qSWmV3ETSiFOJOEvcFCMrS13G7xeC` | 5 arquivos: Manual SF Arquitetura (doc/pdf, duplicado) e Manual SF Engenharia (pdf, 18 MB) |
| **GERDAU** | `1Eg2dF6DNOfm4suA3abbzWnoKRwXPLwKQ` | 1 arquivo: catálogo de perfil |
| **CSN** | `1f0iOB5PU3gdrnbx3yYtKeoblc8wOnzdF` | 3 arquivos: catálogos CSN zincados, laminados a frio, laminados a quente |
| **ARCELORMITTAL** | `12yt0h1OcQeLSOdmIC5FY0-LB_FEu1rzx` | 4 arquivos: barra chata, certificado de cantoneira, manual de cabo de aço, ficha Dramix (fibra de aço p/ concreto) |
| **FRAMECAD** | `1bWMQVP1pq0GemWZw2tfTZRc7LK5zAW95` | ~35 arquivos: linha completa Pro-mag/Pro-panel (placa de óxido de magnésio), fachada isolada (IFS), fibrocimento, guia de gesso — maioria em inglês/PT técnico de fachada FrameCAD |

### Dentro de FRAMECAD (nível CATALOGOS — não confundir com AÇO/FRAMECAD acima)
| Subpasta | ID | Conteúdo |
|---|---|---|
| **Brochures in Portuguese** | `1flouW3eFZLLEK55embjsvZjpnT4fvFNQ` | ~30 arquivos: linha completa de brochuras técnicas FrameCAD em português — fachada isolada, gesso, fibrocimento, conectores, catálogo geral da empresa |
| **2014_janeiro** | `1Tv5OwJjpnUjYQk9UIT5jkKtdu8DO4LiU` | 5 arquivos: manuais do software FRAMECAD ProDesign |
| **antigo** | `14kE0FDhoMIfyjQXWK9L4s1AWRbyUkQtO` | ~24 arquivos: material histórico (2009-2014) — manuais FRAMECAD Detailer/Pro, catálogo de fixadores, guia Marino Ware, doc "Sistema Construtivo Steel Frame" em português |

### Dentro de FACHADAS
| Subpasta | ID | Conteúdo |
|---|---|---|
| **RECEBIDOS - KHSS** | `1YYCQkSWU-TkYGfhZvtRbP1td2qCYB1tx` | Fotos/vídeos de obra (Thunder Valley Hotel & Casino), apresentação "Tower Solutions" + 4 sub-subpastas não abertas: `recebido 07 07 2014` (`1gCxZjVXHWTIoNv03LS1D-nkpcoTHQpdN`), `recebido 11 06 2014` (`1Ku6ZxQrVEg-7IoE8xeEUurRyl4H5ld-3`), `recebido 25 06 2014` (`1gcfs-2KTIsU_7whncHE78pAu1v0ge4ST`), `GypGroup-KHSS Panelization Process` (`1q_Vss7cphqQGPY55zHt0dcI9siZWIi8V`) |
| **MIDIA - VIA** | `1hZhiymidlFk9aAxpdIC_dI6N49L0-DeC` | 1 subpasta não aberta: `Via- Estimate` (`1_GMXXmNMx3BXXK9bZZiKaoETAtPfYwnz`) |
| **HYATT - METODO** | `1hw7DbG2UOiIYVbPZgECwzLSoXDDk3ULP` | 3 arquivos: plantas/marcações de painel do projeto Hyatt Rio |
| **BELMETAL** | `1Fk_OMED_V8by0aM00pquYbTCMPhxZZef` | 4 arquivos: catálogos de fachada (Atlanta, Alcoa, Monopoli, folheto offset) |

### Dentro de LP — ⚠️ conteúdo é sobre OSB (placa descontinuada pela Fast)
| Subpasta | ID | Conteúdo |
|---|---|---|
| **FOGO** | `1qBT_oWJNOnAHvjYa2UmSsm9iSbzMZYib` | 7 arquivos: ensaios de reação ao fogo de placas OSB/mezanino |
| **RES. MECÂNICA** | `1DLCk_F-kSaTjW9-9WIPBNbT75z87Eae4` | 5 arquivos: resistência à flexão de painéis OSB mezanino |
| **CATALOGO** | `1-fGWFYdcasmwSc_mZf-fR-TCxowJp1C0` | 2 subpastas não abertas: `TÉCNICO` (`1mSKVG4nv_URsx_5Jq1Se05VjGDrerAGZ`), `COMERCIAL` (`1UMMW4Ybgy6WZVrxjCW1nzkjCpOXap63B`) |
| **ACÚSTICA** | `1tPtjhGQ8XhIhxApuj4Rj1hxYfkF2eX9W` | 7 arquivos: isolamento acústico de sistemas com OSB |
| **GARANTIAS** | `1fkQedq2fBefdMGh7IxhDQcgO3QCJOgwO` | 10 arquivos: garantias OSB/Shingle, certificados de resistência a cupim e água, inclui `Garantia LP OSB Home APA.pdf` |

> **Toda a pasta LP gira em torno de OSB** — a Fast não usa mais esse produto (regra de nomenclatura em [_contexto/preferencias.md](../_contexto/preferencias.md): interno → "Placa Performa", externo/fachada → "Glasroc X"). Útil só como referência histórica de engenharia — nunca citar OSB em conteúdo publicado.

### Dentro de ECOPHON → POR PRODUTOS → ECOPHON FOCUS A
3 subpastas não abertas (provável material de instalação de um produto específico da linha Focus): `INFORMAÇÕES TÉCNICAS` (`18qX1zmXk_gFFipLtLW4rac3I0qL-WpIL`), `ESQUEMA DE INSTALAÇÕES` (`13fUp9KGtNHoNgYfemtfvC0TGehNdZQ3n`), `ESQUEMAS DE FIXAÇÃO` (`1PMdWryX4L55CkfY4FUbDDxooPwQyQFNx`).

### Dentro de PLACO (pasta aninhada `1ZPPo3xte9qWfoTBzRt0wTbIlY1pT7lsK`)
| Subpasta | ID | Conteúdo |
|---|---|---|
| **TESTE E CERTIFICADOS** | `1aYtVuWCJBE_-WyfsbFsoYvw4olQI2Uh6` | 2 subpastas não abertas: `CERTIFICADO` (`1tGnclBXGnYjDA6C3PuIltPrxbteT-Kdx`), `IPT` (`1BrFIL_qnk9CjBqnum-zB6gaxyGCoJT_F`) |
| **PLACO BRASIL** | `1BYFu5_xY-uqHTWa6uQViSBGZkKHCVU7Q` | ~14 arquivos: manuais de drywall (Placostil), **manual de acústica drywall**, pintura, resíduos de gesso, fixações, certificados de aço + 2 subpastas não abertas: `FORRO F530` (`1eN07JKf-JICFC60N3kvq5jea4fhPVelV`), `FORRO GYPREX` (`1xoVCqIIYei0JE6C_ECtbc-YCQiQ3-nv1`) |
| **WHITE BOOK** | `10j1_uNdjfIT7AoGdjyG3VPKClejMZcIq` | 10 arquivos em inglês — referência internacional Gyproc/Placo: fire protection, building acoustics, thermal insulation, standards, robustness, sustainability |
| **PLACO ESPANHA** | `1zt20-yPHUqe4kL8M4qCgctHfsvZzPswS` | 7 arquivos em espanhol: manuais Placotherm, Placo Yesos, tabiquería (paredes) |
| **DRYWALL** | `1WlDgTXPrpeTdx6mWZTPVwHb-Caa8JKwd` | 4 subpastas por sistema, não abertas: `1 - Sistemas Placostil` (`1SoVkw-NvHBUONeIdLo3STrkgTJEuqDBp`), `2 - Sistema Placopainel` (`1ao2OC5nhZtpuYq4reQJh8joi32vSrnIz`), `3 - Sistema Placoreal` (`1cVXLlRV9bwcXcwLl7V_cLkdl-KDC3kgS`), `4 - Forros Removíveis` (`15zR5DpDAkmlKIMlzqrjKGzByzbV6bSM8`) + 1 apresentação solta |

### Dentro de CBCA → MANUAL STEEL FRAME
Plana, 4 arquivos — 2 ZIPs duplicados `arquitetura.zip` e 2 ZIPs duplicados `engenharia.zip` (conteúdo bruto; preferir os PDFs já listados na pasta CBCA de nível superior).

### Nível 6-7 — o resto da árvore, agora fechado

Todas as pastas listadas como pendentes na primeira revisão foram abertas. Resultado:

**STO CORP/DETALHES TÉCNICOS/Nova pasta** (`1eLoNTCzK1-qQnvp5_gCJH80S49Vb4hs5`) — plana, 9 arquivos: detalhes construtivos EIFS numerados (componentes do sistema, drenagem, aberturas de fachada, peitoril, pingadeira, linha de piso sem junta, encontro com pilar de concreto, textura customizada).

**FACHADAS/RECEBIDOS - KHSS** — 4 subpastas, todas abertas:
- `recebido 07 07 2014` → 1 subpasta `plantas - Thunder Valley Hotel & Casino` (`1OCjwIOiDJrShgt92RW-xigLGzuflIxZM`), plana, 11 PDFs — plantas estruturais/painel do projeto Thunder Valley (S1-S5, TV-x.xx)
- `recebido 11 06 2014` — plana, 4 arquivos: detalhes de conexão de painel, fluxograma de produção com Densglass, mockup de painel metálico
- `recebido 25 06 2014` — plana, 2 arquivos: detalhes EIFS
- `GypGroup-KHSS Panelization Process` — plana, 6 arquivos: templates de precificação de painel (Brasil)

**FACHADAS/MIDIA - VIA/Via- Estimate** — plana, 9 arquivos: elevações e plantas de painel + planilhas de precificação (projeto de estimativa de fachada painelizada)

**LP/CATALOGO** — 2 subpastas, ambas planas:
- `TÉCNICO` — 6 arquivos: LP.rar, catálogo técnico telha shingle, Manual CES LP 2010/2014, garantia e catálogo técnico OSB
- `COMERCIAL` — 9 arquivos: linha completa de produtos OSB da LP (Home Plus Estrutural, Tapume, Decowall, Top-Form/Eco-Form, SmartSide, Eco-Tábua, Indu-Plac, TechShield) — **⚠️ tudo OSB, descontinuado pela Fast**

**ECOPHON FOCUS A** — 3 subpastas:
- `INFORMAÇÕES TÉCNICAS` — plana, ~28 arquivos: EPDs, certificados, SDS, vídeos de instalação/limpeza, fichas técnicas do produto Focus A
- `ESQUEMA DE INSTALAÇÕES` — 4 sub-subpastas por acessório: `ALTO FALANTES` e `TUBO` ainda têm mais um nível (pastas com nome descritivo tipo "1. Connect T15... 2. Parafuso..." — bibliotecas CAD de acessório específico, não abri por serem claramente terminais); `LUMINÁRIA` e `DIFUSOR` confirmados planos (arquivos CAD dwg/dxf/eps/pdf de um único item)
- `ESQUEMAS DE FIXAÇÃO` — 5 subpastas, todas abertas e planas: `DETETOR DE FUMAÇA`, `CORTINEIRO`, `SINAL`, `LUMINÁRIA SUSPENSA`, `LUMINÁRIA EMBUTIDA` — cada uma é um desenho técnico de fixação em múltiplos formatos (dwg/dxf/eps/wmf/pdf)

**PLACO/TESTE E CERTIFICADOS** — 2 subpastas:
- `CERTIFICADO` → 1 subpasta `QUALIDADE PLACO` (`1bPAMtJJc1E_UthfLydCGX_GmVpueKCZJ`) → tem 1 sub-subpasta `2006` (não aberta, terminal) + Thumbs.db
- `IPT` — 3 subpastas, **todas com laudos reais de ensaio do IPT** (Instituto de Pesquisas Tecnológicas):
  - `FOGO` (`14Qmjf_j9nThwmp5DiFqdYq9QAUx5T1Ad`) — 3 laudos: **Parede 30 min, 45 min e 60 min** (TRRF testado e certificado, não estimativa)
  - `ACÚSTICA` (`1ek9psKh5xSn15DGHz-ogEgBXy3Zcdc8Q`) — 4 laudos de sistemas com códigos (ex. `837.482 - 73-48-600_1ST-1ST_comPG.pdf`) — dados de isolamento acústico testados
  - `CARGAS` (`12R5HGAh0j7dWFl-YhwDhCOZcw_xYLlvl`) — 4 laudos: choque de abalo, impacto de corpo duro/mole, cargas suspensas
  - + `IPT 013 - PLACO GERAL.pdf` solto

  > **✅ Lidos e incorporados em 2026-07-07** a [produtos/desempenho-detalhado.md](../produtos/desempenho-detalhado.md) (seção 5). O arquivo solto `IPT 013 - PLACO GERAL.pdf` é a Referência Técnica oficial do IPT sobre o Sistema Placostil (maio/2001) — documento síntese que consolida todos os laudos individuais em tabelas de Rw, TRRF e critérios de impacto/carga. Validade declarada até abril/2003 — o próprio documento pede para confirmar se não há versão mais recente antes de uso comercial.

**PLACO BRASIL** — 2 subpastas, ambas planas:
- `FORRO F530` — 3 arquivos: manual de manutenção, catálogo técnico e manual de instalação do forro de gesso acartonado F530
- `FORRO GYPREX` — 2 arquivos: certificado e catálogo técnico

**PLACO/DRYWALL** — 4 subpastas por sistema:
- `1 - Sistemas Placostil` → 4 sub-subpastas, todas abertas e planas: `1-Componentes dos Sistemas` (~20 arquivos, série cs1-cs6), `2-Paredes` (~140 arquivos, série P01-P71), `3-Forros` (~80 arquivos, série F01-F76), `4-Revestimentos` (~45 arquivos, série R01-R20) — todas bibliotecas de desenho técnico (dwg+pdf pareados) por item numerado, mais índices .xls
- `2-Sistema Placopainel`, `3-Sistema Placoreal`, `4-Forros Removíveis` — já confirmados planos na rodada anterior (séries PP/PR/FR)

**CBCA/MANUAL STEEL FRAME** — plana, 4 arquivos (2 ZIPs duplicados de arquitetura + 2 de engenharia).

### O que ficou deliberadamente não aberto
Só 4 pastas, todas claramente bibliotecas CAD terminais (mesmo padrão de tudo que já foi confirmado plano nesta seção) — abrir apenas se um briefing precisar exatamente daquele acessório:
- `ECOPHON FOCUS A/ESQUEMA DE INSTALAÇÕES/ALTO FALANTES/` — 3 subpastas por método de fixação (reconfirmado em 2026-07-07: continuam sendo pastas-CAD por combinação de acessório, sem ficha técnica)
- `ECOPHON FOCUS A/ESQUEMA DE INSTALAÇÕES/TUBO/` — 6 subpastas por combinação de acessório
- `PLACO/.../CERTIFICADO/QUALIDADE PLACO/2006/` — 1 subpasta

### Limitação técnica conhecida
- **QUARTZOLIT/WEBER:** ~25 dos ~28 arquivos são ZIPs grandes ("WEBER_ProductDocumentation_*", alguns >100MB) — a ferramenta de leitura (`read_file_content`) não abre ZIP, só PDF/DOCX/PPTX/XLSX/imagem. Essa pasta está mapeada por caminho mas **não é possível extrair conteúdo** sem baixar e descompactar manualmente (fora do escopo "não baixar" definido para esta biblioteca).

### Status de cobertura (atualizado 2026-07-07)
- **Caminhos/estrutura de pastas:** mapeamento completo, só as 4 pastas-folha acima ficaram de propósito sem abrir.
- **Conteúdo lido e absorvido em `produtos/`:** Steel Frame (+ DATec nº14, perfis Framecad, aço ZAR), Brasilit (placas + telhas), Placo Brasil (drywall + forros), Ecophon + Isover, Cebrace + Adfors, Decorlit, Sincol (portas, arquivo novo `produtos/portas.md`), TC Shingle, Fixação (6 marcas) + Aço (Gerdau/CSN/ArcelorMittal). Dúvidas consolidadas em [`_contexto/duvidas-tecnicas-biblioteca-drive.md`](../_contexto/duvidas-tecnicas-biblioteca-drive.md).
- **Triagem leve (não documentação completa):** Sto Corp, Owens Corning, Panel Rey, Placlux, Parex, Steeldeck, Steel Colors, Norton, Tek Bond, Placo White Book, Placo Espanha, LP, ABDI — confirmados como referência técnica de mercado/legada, sem indicação de venda ativa pela Fast (ver dúvidas técnicas para reverter esse julgamento se algum for parceiro real).

---

## Onde procurar por tema (atalho rápido)

- **Resistência ao fogo (TRRF/RF):** ⭐ `PLACO/TESTE E CERTIFICADOS/IPT/FOGO` — **laudos reais testados** (parede 30/45/60 min), melhor fonte que NBR 15758; `LP/FOGO` (⚠️ OSB), `PARAFUSOS.../PLACLUX` (REAL FIRE TESTING), `BRASILIT` (PPC ResFogo 30/120 min), `CEBRACE` (vidro resistente ao fogo), `SINCOL PORTAS` (kit resistente ao fogo), `OWENS CORNING/TESTES E LAUDOS Foamular` (NBR 11948), `PLACO/WHITE BOOK` (fire protection, em inglês)
- **Acústico (Rw/isolamento):** ⭐ `PLACO/TESTE E CERTIFICADOS/IPT/ACÚSTICA` — **laudos reais testados** por código de sistema, melhor fonte que NBR 15758; `LIVROS E MANUAIS` (desempenho acústico drywall), `ECOPHON` (catálogos e guias por segmento), `LP/ACÚSTICA` (⚠️ OSB), `BRASILIT` (57 dB placa cimentícia), `PLACO/PLACO BRASIL` (manual de acústica drywall), `OWENS CORNING/Bill Tolliver` (fundamentos de acústica), `PLACO/WHITE BOOK` (building acoustics, em inglês)
- **Cargas/impacto/resistência mecânica:** `PLACO/TESTE E CERTIFICADOS/IPT/CARGAS` — laudos de choque de abalo, impacto de corpo duro/mole, cargas suspensas
- **Térmico (R/U):** `NORMAS ABNT`, `BRASILIT` (desempenho térmico), `ISOVER`/`QUARTZOLIT` (lã de vidro, catálogos Weber), `OWENS CORNING/TESTES E LAUDOS Foamular` (condutividade térmica), `PLACO/WHITE BOOK` (thermal insulation, em inglês)
- **Galvanização/aço estrutural:** `CATALOGOS.../AÇO` (Gypsteel¹, Gerdau, CSN, ArcelorMittal, CBCA), `NORMAS ABNT`
- **Steel Frame (engenharia/montagem):** `CBCA` (+ subpasta `MANUAL STEEL FRAME`), `MANUAL ESTRUTURA COMPOSTA...`, `FRAMECAD` (as 3 pastas: nível SAINT GOBAINT, nível CATALOGOS, e dentro de AÇO), `DOCUMENTOS DE QUALIDADE` (DATEC LSF)
- **Fachada/EIFS:** `STO CORP`, `PANEL REY`, `PLACLUX`, `FACHADAS`, `DECORLIT`, `AÇO/FRAMECAD` (fachada isolada FrameCAD)
- **Fixação/parafusos/chumbadores:** `PARAFUSOS E CHUMBADORES` — 7 marcas: Hilti, Fischer, Ancora, Ciser, Bullfor, Framecad, Walsywa (todas confirmadas planas, sem mais fundo)
- **Piso vinílico:** `PISO VINÍLICO`
- **Portas:** `SINCOL PORTAS`
- **Telhas:** `TC SHINGLE`, `CATALOGOS.../TELHA`, `BRASILIT`
- **Referência internacional (inglês/espanhol):** `PLACO/WHITE BOOK` (padrões Gyproc/Placo em inglês), `PLACO/PLACO ESPANHA` (manuais em espanhol)

## Notas
- Pastas marcadas **"Tem subpastas"** foram identificadas mas não exploradas até o fim (a árvore continua). Antes de dizer "não achei", rodar `search_files` com `parentId` daquela pasta.
- Vários arquivos são ZIPs/RARs grandes (alguns >100 MB) — não baixar por padrão; preferir os PDFs/DOCX soltos, que já cobrem a maioria das fichas técnicas.
- Vários fabricantes citados aqui (Sto, Owens Corning, Panel Rey, LP, Amanco) **não são necessariamente parceiros atuais da Fast** — confirmar com `_contexto/empresa.md` antes de usar como prova social; a pasta parece agregar referência técnica de mercado, não só fornecedores ativos.
