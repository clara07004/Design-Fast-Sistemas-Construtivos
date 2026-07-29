# Perguntas técnicas pendentes — Biblioteca do Drive (2026-07-07)

> 28 perguntas diretas, geradas depois de ler ~90 arquivos técnicos do Drive (mapeados em [biblioteca-tecnica-drive/README.md](../biblioteca-tecnica-drive/README.md)) e incorporar os dados em `produtos/`. Cada uma tem uma resposta objetiva (sim/não ou um nome/número) — não precisa de texto longo, só confirmar ou corrigir. Nenhuma bloqueia o uso da base hoje: os arquivos já têm ⚠️ nos pontos em aberto.
>
> **Legenda:** 🔴 crítico — pode virar informação errada em conteúdo publicado · 🟡 organização/escopo · 🟢 detalhe menor.

---

## 1. Certificações e normas vencidas ou de terceiros

**P1** 🔴 O DATec nº 14 (avaliação técnica do sistema Light Steel Frame Saint-Gobain, feita pelo IPT) está com validade vencida desde março/2015 e nem é certificação própria da Fast. **Continuo citando como "referência técnica do setor" (com a ressalva já escrita), ou prefere que eu tire essa referência de `steel-frame.md` e `certificacoes.md`?**

**P2** 🔴 O certificado ABNT do Kit Resistente ao Fogo (Sincol) venceu em 20/06/2025. **A Sincol renovou? Se não renovou, paro de chamar essa linha de "certificada" em `portas.md`?**

**P3** 🔴 O certificado PBQP-H da CCN (fabricante do perfil de aço/drywall) está vencido desde 16/02/2014. **A Fast ainda compra perfil da CCN hoje, ou trocou de fornecedor?**

**P4** 🔴 Os ensaios IPT de fogo e acústica da placa cimentícia Brasilit (Rw 57dB, TRRF 30/120min) foram feitos em 2005/2006 sob o nome comercial antigo "Brasiplac", não "Aquaroc® FC" (nome atual). **A Aquaroc FC de hoje é o mesmo produto/composição da Brasiplac de 2005, ou a fórmula mudou depois do rebranding?**

**P5** 🟡 Esses ensaios de fogo usam a norma NBR 10636, de 1989. **Essa ainda é a norma vigente pra esse tipo de ensaio de parede, ou existe uma versão mais nova?**

---

## 2. Fornecedores que apareceram no Drive mas não estão na lista de parceiros confirmados

**P6** 🔴 Achei um manual completo de placa cimentícia de fachada da marca **PlacLux/ProFort** (instalação, garantia, 8/10/12mm). **A Fast revende essa marca?**

**P7** 🔴 Achei catálogos completos de portas de madeira da **Sincol** (Sinkit, Kit RF, Impressione, Touch, Sincolors) — hoje só a G-DOOR está documentada. **A Fast revende Sincol? Em qual loja ou nicho (ex.: porta corta-fogo)?**

**P8** 🔴 O material da **TC Shingle** é literalmente um pitch de parceria ("Vamos começar?"). **Essa parceria já foi fechada, ou ainda está em avaliação?**

**P9** 🔴 Achei 6 catálogos técnicos de vidro da **Cebrace**, mas já tenho registrado em `acessorios-fixacoes-ferramentas.md` que "a Fast não trabalha com vidro". **Isso mudou com a linha EcoFrame (esquadria de PVC)? Se sim, qual vidro Cebrace ela usa?**

**P10** 🔴 O Catálogo Fast 2025 cita linhas Ecophon específicas (Mineralis, Gedina, Ocean, Sinfonia, Reflecta, Gyprex Clean, Humancare, Raw Grey, New Decor, Brillianto A), mas nenhuma delas aparece nos 5 catálogos técnicos que li (Focus/Master/Solo/Super G/Hygiene Performance). **Quais linhas Ecophon a Fast vende de fato hoje?**

**P11** 🟡 O material Isover que encontrei (Climaver/Facefelt/Flexliner/Isoflex) é isolamento de duto de ar-condicionado e cobertura, não forro de teto. **Mantenho documentado em `forros.md` mesmo assim, ou está fora do escopo do que a Fast vende ao cliente final?**

**P12** 🟡 Achei ficha técnica da **Owens Corning** (lã de vidro, isolante XPS Foamular). **A Fast compra dessa marca também, ou o fornecedor de lã de vidro confirmado é só a Isover?**

**P13** 🟡 Além da **Ciser** (já documentada), achei catálogos de parafuso/chumbador de Walsywa, Bullfor, Hilti, Ancora e fischer. **Algum desses é revendido pela Fast, ou é só a Ciser mesmo?**

**P14** 🟡 Achei catálogos de aço de Gerdau, CSN e ArcelorMittal, mas nenhum bate exatamente com o perfil leve do Steel Frame. **Qual dessas siderúrgicas é de fato a fonte do aço dos perfis "Normatizado" da Fast — ou é nenhuma delas, e são só referência de mercado?**

**P15** 🟡 Achei 3 pastas do fabricante **FrameCad** com o Sistema de Fachada Isolada (IFS 1/2/3) e placas próprias Pro-panel (cimentícia) e Pro-mag (MgO). **A Fast usa esse sistema de fachada e essas placas, ou o vínculo com a FrameCad é só a máquina de corte/furação de perfil — e o fechamento continua sendo Brasilit/Decorlit/Glasroc X?**

> Sem pergunta — apenas aviso: Sto Corp, Panel Rey, Parex, Steeldeck, Norton, Tek Bond, Placo White Book, Placo Espanha, LP (OSB) e ABDI foram triados e não indicam venda ativa pela Fast (referência de mercado ou material institucional). Não documentei o conteúdo completo dessas pastas — avise se algum desses for parceiro real e eu leio tudo.

---

## 3. Dados de fontes antigas — confirmar se ainda valem hoje

**P16** 🟡 O catálogo de telhas de fibrocimento Brasilit (linha completa: Fibrotex, Ondina, Colonial, Kalheta, Kalhetão 90) é de 2010/2011. **Essa linha ainda é a mesma vendida hoje?**

**P17** 🟢 Segundo esse mesmo catálogo, a **Ondina Plus** só é vendida em MS/PR/RS/SC. **Essa restrição regional ainda vale?**

**P18** 🟡 O guia Placo "Soluções Construtivas" com as tabelas de isolamento acústico e resistência ao fogo por parede é de 2014. **Essas tabelas ainda valem, ou existe revisão mais recente que eu deveria usar no lugar?**

**P19** 🟢 O manual CBCA de perfis é de 2012 e citava galvanização de 180g/m² — já troquei esse número pelo Z275 atual em `steel-frame.md`. **Precisa de mais alguma correção nessa tabela de perfis (Ue/U/L/Cr), ou está OK?**

**P20** 🟡 O ensaio de desempenho térmico da placa cimentícia que encontrei é de 2005 e nem é da Brasilit — é da "EterBras Tec Industrial", mostrando desempenho ruim no verão. **Mantenho esse dado como referência de mercado em `placas.md`, ou removo por ser de fabricante diferente do que a Fast vende?**

---

## 4. Dúvidas de escopo — existe no portfólio ou não?

**P21** 🟡 O folheto Placo cita duas variantes de forro monolítico: F530 e "STUD" — só o F530 está no material Fast que já tenho. **A variante STUD existe no portfólio da Fast?**

**P22** 🟡 A **Flexwall®** (parede pré-acabada Placo, sem tratamento de junta nem pintura) não aparece em nenhum catálogo Fast que já absorvi. **É vendida?**

**P23** 🟡 A regra "OSB interno vira Placa Performa, externo vira Glasroc X" foi pensada pra fechamento de parede. O material da TC Shingle descreve a base do telhado como "chapa OSB ou Plywood" — isso é deck de telhado, não parede. **Essa regra também vale pra deck de telhado, ou é um caso à parte ainda sem substituto definido?**

**P24** 🟢 Além das telas Adfors já documentadas (Vertex, FibaLath, FibaTape, FibaFuse), o catálogo tem mais produtos: Vertex Grid, Novelio, GlasGrid, Pet Resistant Mesh. **Algum desses é vendido pela Fast?**

**P25** 🟡 Todas as especificações técnicas Ecophon que li usam norma europeia (EN, NCS, Eurofins) — nenhuma referência ABNT, diferente dos boletins Isover que já vêm adaptados ao Brasil. **As medidas internacionais (ex.: placa 600×600mm) batem com o que a Fast vende, ou existe homologação nacional que muda algum dado?**

---

## 5. Garantias formais sem prazo definido

**P26** 🟢 Qual o prazo de garantia (em anos) das **telhas de fibrocimento Brasilit**? O material que li só diz "garantia total de fábrica", sem número.

**P27** 🟢 Qual o prazo de garantia das **placas de gesso Placo**? O material fala em "controles de qualidade + ensaios IPT", sem prazo.

**P28** 🟢 Qual o prazo de garantia da **estrutura de aço do Steel Frame**?

---

## 6. Documentos que não consegui ler (sem pergunta — é ação, não dúvida)

Estes vieram vazios, truncados ou com OCR corrompido. Não vou adivinhar o conteúdo — se algum for prioridade, me avise que eu peço a versão legível ou tento de novo:

- `CENARIO FABRICAÇÃO 2024.pdf`, `VIABILIDADE NO SISTEMA DE CONSTRUÇÕES RESIDENCIAIS.pdf` (CBCA) — só veio fragmento de imagem
- `90548_manual_prevencao_contra_incendio.pdf`, `Manual_Estruturas Compostas por Perfis Formados a Frio_FINAL.pdf` — arquivos grandes, leitura truncada em ~40%
- `10.3.1 ESPECIFICAÇÕES TÉCNICAS DA PLACA CIMENTICIA.pdf`, `10.3.3 TERMO DE GARANTIA DA PLACA CIMENTICIA.pdf` (Brasilit) — provável PDF escaneado sem OCR
- `BT_placa_aquaroc_FC`, `BT Placa Aquaroc FC Pisos`, `Boletim Técnico - Kit Fixação`, `BT - Membrana Hidrófuga Typar` — só veio cabeçalho, tabelas não foram lidas
- `Guia Técnico Brasilit 2026.pdf`, `AF-ManualPlacostil_A4 MAR2014_WEB.pdf` — catálogos grandes demais, extração parcial
- 5 PDFs do Forro F530/Gyprex (catálogo/instalação/manutenção/certificado) — vieram vazios, provável imagem sem texto
- `LinhaGourmet2022.pdf` (Sincol) — arquivo vetorial, sem texto extraível
- `3.5.2 CATÁLOGO TÉCNICO PARAFUSOS.pdf` (CCN), `certificado cantoneira.pdf` (ArcelorMittal), `bullfor_catalogo[1].pdf` — vazios ou OCR corrompido
- `Decorlit-2023...pdf` — erro "Entity not found", fileId pode estar desatualizado
- Certificado Kit Resistente ao Fogo (Sincol) — número de norma saiu corrompido do OCR ("15530-2:2018"/"15830-3:2023"; a família correta provavelmente é NBR 15930) — vale conferir os dígitos no PDF original

---

## Como responder

Mais rápido: me diga só o número da pergunta (P1, P7, P15...) e a resposta — não precisa reescrever o contexto, eu já sei qual é. Pode responder aos poucos, não precisa ser tudo de uma vez.
