# Referências Visuais — Google Drive

> **Status (jul/2026):** Google Drive **conectado** (via MCP). Pastas registradas: **Fotos de Obra** (acervo real, ~500+ fotos cruas) e **Biblioteca Técnica** (catálogos/manuais dos fabricantes — já documentada em `produtos/biblioteca-tecnica/`). Identidade visual/logos hoje estão **locais** em `marca/logos/` (kit oficial instalado). Material de marca/produto local em `material pra contexto/` e `material técnico/` já foi extraído e documentado.
>
> ⚠️ **Curadoria obrigatória de fotos:** o acervo de fotos é CRU e não curado — antes de usar QUALQUER foto, aplicar a curadoria crítica de `.claude/memory/feedback_curadoria_fotos.md` (nunca usar a primeira disponível; comparar; reprovar baixa qualidade). Fotos **HEIC** precisam ser convertidas para JPG/PNG antes do uso em HTML.

## Identidade Visual — sem pasta no Drive (local)
Não há pasta raiz nem pasta de identidade visual no Drive para este projeto — os logos e o kit de marca já estão instalados localmente em [`marca/logos/`](../marca/logos/) (ver `LEIA-ME.md` da pasta), e a especificação completa de identidade (cores, tipografia, DNA visual) está em [`marca/DESIGN.md`](../marca/DESIGN.md). Não é necessário buscar nada no Drive para isso.

---

## Fotos de Obra / Acervo Real ✅ CONECTADO
**Descrição:** Fotos reais da empresa — obras, serviços executados, ambientes, equipes, equipamentos, steel frame e drywall em canteiro. Acervo **cru e não curado**: ~500+ imagens, pasta plana (sem subpastas), mistura de JPEG, HEIC (Apple — converter antes de usar) e PNG. Nem toda foto tem qualidade de peça — **curar antes de usar** (ver `.claude/memory/feedback_curadoria_fotos.md`).
**Link:** https://drive.google.com/drive/folders/10mzjRSxlVcF-u63TxDM87f3HdtTLfs3r
**ID da pasta:** `10mzjRSxlVcF-u63TxDM87f3HdtTLfs3r`

**Fluxo de uso (quando a origem escolhida for Drive):** a origem foto real × IA é escolha do usuário — definida no `/briefing-unity` ou perguntada no fluxo rápido; não é automática nem prioritária. Escolhido o Drive: `search_files` com `parentId` = ID acima → **curadoria crítica** (nunca a primeira; comparar; reprovar baixa resolução/desfoque/bagunça/poluição visual) → escolher a que reforça a copy e cabe na composição → `download_file_content` só da(s) aprovada(s) → salvar como `img-slideXX.jpg` na pasta do conteúdo. HEIC → converter para JPG antes.

---

## Catálogo Técnico / Biblioteca dos Fabricantes ✅ CONECTADO
**Descrição:** Biblioteca técnica (250+ arquivos): normas ABNT, manuais steel frame (CBCA/ABDI), Datec, e catálogos/fichas dos fabricantes (Placo, Brasilit, Isover, Ecophon, Quartzolit, Framecad, etc.). **Já catalogada e documentada** em `produtos/biblioteca-tecnica/` (índice + docs por fabricante). Buscar arquivo-fonte pelo ID no `INDICE.md`.
**Link:** https://drive.google.com/drive/folders/1_tgdWuyddebKpRfUDowzhObFdn555jGx
**ID da pasta:** `1_tgdWuyddebKpRfUDowzhObFdn555jGx`

Arquivos disponíveis:
- [Arquivo 1 — ex.: Catálogo Comercial]
- [Arquivo 2 — ex.: Ficha Técnica]
- [Arquivo 3 — ex.: Manual de Instalação / Uso]
- [Arquivo 4 — ex.: Laudos e relatórios técnicos]
- [...]

---

## Referências de estilo — não usamos perfil externo do Instagram

O CCOS genérico prevê aqui uma referência externa (perfil de concorrente/ecossistema) pra calibrar estilo. **Não é o caso da Fast**: a linha visual foi extraída diretamente de **carrosséis e capas reais publicados pela própria Fast** (pasta local `carrosseis reais/` e `capas reais/`), o que é uma base mais forte do que uma referência externa.

Onde está isso hoje:
- **DNA visual completo** (cores, tipografia Anton+Poppins, fotografia, elementos gráficos, templates de layout): [`marca/DESIGN.md`](../marca/DESIGN.md) + [`.claude/memory/feedback_linha_visual_fast.md`](../.claude/memory/feedback_linha_visual_fast.md)
- **Regras de capa** (logo, hook, foto, cue "Arrasta", diagonal vermelha): [`.claude/memory/feedback_capas_fast.md`](../.claude/memory/feedback_capas_fast.md)

Se no futuro Clara quiser adicionar um perfil de referência externo (ex.: concorrente ou marca do mesmo ecossistema para benchmarking pontual), essa seção pode ser reconstruída — mas hoje não é necessária.
