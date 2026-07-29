# Desempenho Técnico Detalhado — Térmico, Acústico, Fogo e Galvanização

> Fonte: 4 documentos técnicos internos (`documentos técnicos/*.docx`), absorvidos em 2026-07-07 + 12 laudos de ensaio reais do IPT (Instituto de Pesquisas Tecnológicas) sobre o sistema Placostil (Placo do Brasil), localizados na [biblioteca-tecnica-drive](../biblioteca-tecnica-drive/README.md) e lidos em 2026-07-07.
> **Status normativo variável — ler a coluna "Status" antes de citar qualquer valor em conteúdo.**
> Complementa [normas-desempenho.md](normas-desempenho.md) e [base-normativa-abnt.md](base-normativa-abnt.md).

---

## ⚠️ Status normativo dos dados deste arquivo

| Tema | Base | Status |
|---|---|---|
| Galvanização (Z275/Z350) | NBR 16970-1:2022, NBR 7008-1:2021 | **Norma publicada e vigente** — pode citar como exigência normativa |
| Desempenho térmico (R/U) | NBR 15220-2, NBR 15575-4 | **Estimativa de engenharia**, não é valor ensaiado nem extraído de norma publicada. Não citar como "conforme norma" |
| Isolamento acústico (Rw) — genérico | NBR 15758, Tabela 2 | **Projeto de Revisão em Consulta Nacional (mar/2025) — NÃO TEM VALOR NORMATIVO.** Usar só como referência interna de projeto |
| Resistência ao fogo (TRRF) — genérico | NBR 15758, Tabela 2 + NBR 10636 | **Idem acima — NBR 15758 sem valor normativo.** NBR 10636 (método de ensaio) é vigente, mas os valores de TRRF citados vêm da tabela em consulta |
| **Rw, TRRF e cargas — sistema Placostil (Placo)** | **Laudos de ensaio reais do IPT** (Relatórios nº 837.482 a 848.496, 1996-97) + **Referência Técnica IPT nº 013** (maio/2001) | ⭐ **Ensaio real, certificado, citável com fonte** (ver seção 5). Ressalva: a Referência Técnica IPT 013 tem validade declarada até **abril/2003** — o próprio documento pede para confirmar se não foi substituída por versão mais recente antes de uso comercial |

Para qualquer conteúdo público que cite Rw, TRRF ou R/U térmico **genéricos** (seções 1, 3, 4), tratar como **referência técnica de projeto**, não como "certificado" ou "conforme norma ABNT". Para o **sistema Placostil especificamente** (seção 5), os valores vêm de ensaio real do IPT e podem ser citados como tal, com a ressalva de validade documental acima.

---

## 1. Desempenho térmico — parede externa Steel Frame (LSF)

**Composição calculada** (exterior → interior): fechamento 11 mm + gesso 12,5 mm / câmara 90 mm com lã de vidro / gesso 12,5 mm + fechamento 11 mm.

> Nota de nomenclatura: o cálculo-fonte usa "OSB" como camada de fechamento. Em conteúdo, aplicar a regra do projeto — uso interno → "Placa Performa"; uso externo/fachada → "Glasroc X" (nunca atribuir função estrutural à camada de fechamento). Ver [base-normativa-abnt.md](base-normativa-abnt.md).

| Camada | Espessura | λ (W/m·K) | R (m²·K/W) |
|---|---|---|---|
| Resistência superficial externa (Rse) | — | — | 0,040 |
| Fechamento (OSB/Performa/Glasroc X conforme uso) | 11 mm | 0,12 | 0,092 |
| Gesso | 12,5 mm | 0,35 | 0,036 |
| Lã de vidro (câmara) | 90 mm | 0,045 | 2,000 |
| Gesso | 12,5 mm | 0,35 | 0,036 |
| Fechamento (OSB/Performa/Glasroc X conforme uso) | 11 mm | 0,12 | 0,092 |
| Resistência superficial interna (Rsi) | — | — | 0,130 |
| **Total (campo livre, sem ponte térmica)** | | | **R ≈ 2,43** → **U ≈ 0,41 W/m²·K** |

- **Com ponte térmica do montante metálico:** U efetivo real ≈ **0,6 a 0,9 W/m²·K** (faixa aproximada — depende de espaçamento/espessura do montante, não especificados na fonte).
- **Comparação:** alvenaria rebocada ≈ U 2,3–2,5 W/m²·K → LSF isola **cerca de 3 a 5x melhor**.
- Método: resistências em série por camada (R = e/λ; U = 1/R_total) — **cálculo de engenharia, não ensaio laboratorial**.
- Limites de aceitação por zona bioclimática (NBR 15575-4) **não constam nesta base** — variam por zona e absortância da fachada, precisam de confirmação antes de uso comparativo em conteúdo.

---

## 2. Galvanização de perfis LSF (norma vigente)

**NBR 16970-1:2022, Tabela 2 — classes mínimas de revestimento de zinco:**

| Ambiente | Massa mínima de zinco (2 faces) | Designação |
|---|---|---|
| Urbano e rural (padrão da maioria das obras) | 275 g/m² | **Z275** |
| Agressivo marinho¹ | 350 g/m² | **Z350** |

¹ Ambiente marinho = até 2.000 m da orla, **ou** qualquer concentração de cloretos (Cl⁻) detectada conforme NBR 6211. Ambientes industriais agressivos exigem estudo específico à parte.

- Equivalência: 100 g/m² ≈ 7,1 µm por face → **Z275 ≈ 19–20 µm por face**.
- Aço estrutural: escoamento mínimo **fy ≥ 230 MPa** (consistente com NBR 15253, já documentado em [base-normativa-abnt.md](base-normativa-abnt.md)).
- Espessura nominal dos perfis (U simples/enrijecido, cartola, cantoneira): **0,80 mm a 3,0 mm**; cartola usada como ripa: mínimo **0,65 mm**.
- Massa de zinco medida por ensaio triplo (média), conforme NBR 7008-1:2021.
- **Cuidado de obra:** corrosão galvânica no contato do perfil galvanizado com tubulação de cobre — prever isolamento nesses pontos, inclusive na passagem por furos dos perfis.

---

## 3. Isolamento acústico — drywall (Rw)

> **NBR 15758, Tabela 2 — Projeto de Revisão em Consulta Nacional (mar/2025). Sem valor normativo.** Usar como referência técnica interna, não como exigência normativa vigente.

| Tipologia | Rw sem isolante (dB) | Rw com isolante (dB) |
|---|---|---|
| Simples — 2 chapas 12,5 mm, montante 48 | 34–36 | 42–44 |
| Simples — 2 chapas 15 mm, montante 48 | 35–37 | 43–45 |
| Simples — 4 chapas 12,5 mm, montante 70 | 44–46 | 50–52 |
| Simples — 4 chapas 15 mm, montante 90 | 46–48 | 54–56 |
| Dupla (DEC) — 5 chapas 12,5 mm | 48 (isolante x2) | 55 |
| Dupla (DEC) — 6 chapas 15 mm | 48 (isolante x2) | 60 |

- Faixa geral: **≈34 dB** (parede mais simples, sem lã) até **≈60 dB** (estrutura dupla, isolamento duplo).
- Isolante testado: lã de vidro (NBR 16726) ou lã de PET (NBR 16832); espessura varia com a largura do montante.
- **Condição obrigatória:** uso de banda acústica nos perfis, na interface com piso/teto/substrato (item 5.1h da norma) — sem banda, o Rw declarado não é garantido.
- Tipologias marcadas "b" na fonte dependem de confirmação do fabricante (ensaiadas em estrutura simples).

---

## 4. Resistência ao fogo — chapa RF (TRRF)

> **NBR 15758, Tabela 2 — Projeto de Revisão em Consulta Nacional (mar/2025). Sem valor normativo.** NBR 10636 (método de ensaio) é vigente; os valores de TRRF abaixo vêm da tabela em consulta, não de ensaio publicado.

| Tipologia (estrutura simples) | TRRF com chapa RF (min) |
|---|---|
| 2 chapas 12,5 mm | 30 |
| 2 chapas 15 mm | 60 |
| 4 chapas 12,5 mm | 90 |
| 4 chapas 15 mm | 120 |

- Faixa: **30 a 120 minutos**, conforme número e espessura das chapas.
- **Ponto técnico essencial:** a chapa RF **isoladamente não tem "tempo de resistência ao fogo"** — TRRF é propriedade do sistema completo ensaiado (chapas + montante + fixações), conforme NBR 10636. Trocar qualquer componente invalida o valor tabelado.
- Chapa RF definida pela NBR 14715 e NBR 15758 item 3.6: chapa de gesso com compostos químicos que conferem resistência ao fogo, para paredes, forros e revestimentos em áreas secas.
- Paredes de compartimentação acima de 6,5 m de altura exigem estruturação por pórticos e atestado do fabricante — a tabela acima **não se aplica diretamente** nesse caso.

---

## 5. Sistema Placostil (Placo) — ensaios reais do IPT ⭐

> **Fonte:** Instituto de Pesquisas Tecnológicas (IPT-SP), Laboratórios de Ensaios de Fogo, Acústica e Componentes/Sistemas. 12 relatórios de ensaio (1996-1997) + Referência Técnica IPT nº 013 "Sistema Placostil" (maio/2001, validade declarada abril/2003), cliente Placo do Brasil Ltda. **Estes são ensaios reais e certificados — não estimativa, não norma em consulta.** Localização dos PDFs originais: pasta `PLACO/TESTE E CERTIFICADOS/IPT` — ver [biblioteca-tecnica-drive/README.md](../biblioteca-tecnica-drive/README.md).
>
> ⚠️ **Duas ressalvas antes de citar:**
> 1. A Referência Técnica IPT 013 tem validade declarada **até abril/2003** e o próprio documento instrui o leitor a confirmar se não foi substituída por versão mais recente (contato: cct@ipt.br) — os ensaios individuais continuam válidos como registro histórico daquela amostra específica, mas o **parecer consolidado** pode ter sido atualizado.
> 2. O produto testado é a linha **Placostil clássica** (chapas Placo ST/RF/RU, perfis M48/R48 galvanizados, ~0,5mm) — confirmar que os produtos atuais vendidos pela Fast (ex.: linha Performa) correspondem a essa mesma configuração antes de transferir o número automaticamente para outro produto.

### 5.1 Isolamento acústico (Rw) — dados de ensaio real (ISO 140/III, Rw conforme ISO 717/1)

| Configuração | Espessura total | Chapas | Lã de vidro no vão | Rw medido | Relatório IPT |
|---|---|---|---|---|---|
| Placostil 72/48 — parede simples | 72 mm | 1 chapa 12,5mm cada face | Sem lã (SFV) | **36 dB** | nº 842.294 |
| Placostil 72/48 — parede simples | 72 mm | 1 chapa 12,5mm cada face | Com lã 50mm, 16 kg/m³ (CFV) | **43 dB** | nº 837.482 |
| Placostil 98/48 — parede dupla | 98 mm | 2 chapas 12,5mm cada face | Sem lã (SFV) | **42 dB** | nº 837.483 |
| Placostil 98/48 — parede dupla | 98 mm | 2 chapas 12,5mm cada face | Com lã 50mm, 16 kg/m³ (CFV) | **49 dB** | nº 837.484 |

- Densidade superficial da parede: ±26-27 kg/m² (simples) e ±46 kg/m² (dupla).
- Ensaio conforme ISO 140/III, em pórtico de concreto de 4,00 m x 3,00 m, área de amostra 12 m².
- **Recomendação do próprio IPT (RT 013):** para paredes internas entre habitações/unidades contíguas, **Rw mínimo de 50** — nenhuma das 4 configurações testadas atinge isso isoladamente; a 98/48 com lã (49 dB) chega perto.
- **Validação cruzada:** estes valores reais batem com a faixa estimada da NBR 15758 em [normas-desempenho.md](normas-desempenho.md) para a mesma tipologia (parede simples 2 chapas 12,5mm: 34-36 dB sem lã / 42-44 dB com lã) — reforça a confiabilidade de ambas as fontes para esse caso específico.

### 5.2 Resistência ao fogo (TRRF) — ensaio real (NBR 10636/1989)

| Configuração | Chapa | Montante | Resultado | Relatório IPT | Data |
|---|---|---|---|---|---|
| Placostil 72/48-600, 1 chapa cada face | Placo ST (NBA13) | a cada 60 cm | **CF30 / PC30** (30 min) | nº 838.170 | 17/05/1996 |
| Placostil 72/48-400, 1 chapa cada face | Placo RF (PPFBA13) | a cada 40 cm | **CF45 / PC45** (45 min) | nº 842.847 | 11/03/1997 |
| Placostil 98/48-600, 2 chapas cada face | Placo ST (NBA13) | a cada 60 cm | **CF60** (60 min, conforme ensaio + RT 013 Tabela 4) | nº 848.496 | 16/09/1997 |
| Placostil 98/48-600, 2 chapas cada face | Placo RF | a cada 60 cm | **CF120** (120 min, valor de RT 013 Tabela 4 — chapa importada, conferir aplicabilidade) | RT/IPT nº 006 (citada na RT 013) | — |

- Classificação conforme NBR 10636/1989: **CF (corta-fogo)** = atende estabilidade + estanqueidade + isolamento térmico; **PC (pára-chamas)** = atende estabilidade + estanqueidade (sem exigência de isolamento térmico).
- No ensaio CF30 (838.170): amostra manteve integridade, sem passagem de chamas, elevação de temperatura na face não exposta dentro do limite (140°C acima da inicial) durante os 30 min.
- No ensaio CF45 (842.847): houve abaulamento e fissuras verticais entre placas, **mas sem comprometer estabilidade** — parede permaneceu estável, estanque e isolada termicamente pelos 45 min.
- **Trocar qualquer componente (chapa, montante, espaçamento, fixação) invalida a classificação** — mesmo princípio já registrado na seção 4 para a NBR 10636.

### 5.3 Resistência mecânica e cargas — ensaio real (Laboratório de Componentes e Sistemas do IPT)

Ensaios na parede Placostil 72/48 (montante a cada 60 cm ou 40 cm conforme indicado):

| Ensaio | Critério IPT (utilização / segurança) | Resultado real | Relatório |
|---|---|---|---|
| Impacto de corpo duro | 2,5 J / 10 J | **Aprovado em toda a faixa** (0,1 a 10 J) — mossas de 0,1 a 1,7 mm, sem ruptura | nº 839.054 |
| Choque de abalo | — | ⚠️ **Ruptura localizada da placa no 2º choque**, aplicado entre montantes | nº 839.056 |
| Impacto de corpo mole (montante a cada 40 cm) | 60J e 120J (utilização) / 180J e 240J (segurança) | Sobre o montante: fissuras crescentes até 240J, **sem ruptura**. Entre montantes: fissuras a partir de 120J, **ruptura da placa em 240J** | nº 839.059 |
| Cargas suspensas (peças fixadas direto na placa) | Coeficiente de segurança 3x sobre carga de uso | Bucha Toggler 3/16-24: estável até 40 kg (pequeno deslocamento residual). Bucha Hilti HLD2: sintomas de falência a partir de 38 kg. Bucha Grip-Tite: destacamento a partir de 11 kg | nº 839.060 |

- **Leitura honesta do resultado:** a parede Placostil **não é indestrutível** — passa nos critérios de *utilização* com folga, mas alguns ensaios de *segurança* (choque de abalo, impacto de corpo mole entre montantes a 240J) resultaram em ruptura da placa. Isso é esperado e normal para o método de ensaio (que existe justamente para achar o limite) — não usar esses números para prometer "resistência a qualquer impacto".
- **Cargas suspensas variam drasticamente por tipo de bucha/parafuso** — de 11 kg (Grip-Tite) a 40 kg (Toggler) no mesmo tipo de parede. Nunca generalizar "aguenta X kg" sem especificar o sistema de fixação.
- Critérios oficiais do IPT (RT 013) para peças suspensas: **coeficiente de segurança de 3x** — ou seja, a carga de uso recomendada é sempre 1/3 da carga de ruptura ensaiada.

---

## Como usar em conteúdo

- **Pode afirmar como norma vigente:** classes de galvanização Z275/Z350 (seção 2).
- **Pode afirmar como ensaio real/certificado, citando o IPT:** Rw e TRRF do sistema Placostil (seção 5) — com a ressalva de validade documental e de correspondência ao produto atual.
- **Não pode afirmar como "conforme norma ABNT":** valores de Rw, TRRF e R/U térmico genéricos (seções 1, 3, 4) — são referência técnica de projeto, ainda sem lastro normativo publicado. Redação recomendada: "em projetos de referência, sistemas de X chapas alcançam até Y dB/min" — nunca "a norma exige X dB/min".
- **Nunca extrapolar resultado de ensaio de segurança como garantia de utilização ilimitada** — ex.: não dizer "resiste a impactos de até 240J" quando o próprio ensaio mostrou ruptura nesse nível entre montantes (seção 5.3).
- Ao citar a camada de fechamento no cálculo térmico, aplicar sempre a regra de nomenclatura (Placa Performa / Glasroc X conforme uso) — nunca reproduzir "OSB" em conteúdo publicado.
- Antes de publicar qualquer peça que cite estes números, considerar validar com ficha técnica do fabricante (Placo/Knauf/Brasilit) ou aguardar publicação definitiva da NBR 15758.
