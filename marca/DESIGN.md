---
version: "1.1"
name: "Fast Sistemas Construtivos"
description: "Fast Sistemas Construtivos — construção a seco (drywall, steel frame, acústica) — Manual de Marca 2025 + linha visual real do feed"
status: configured
---

# ⚑ FONTE DE VERDADE DA LINHA VISUAL: `.claude/memory/feedback_linha_visual_fast.md`
# (DNA extraído de 33+ carrosséis reais). Em conflito, o rulebook vence este arquivo.
# Reconciliações jul/2026: fontes reais = Anton (condensada) + Poppins (geométrica/corpo),
# NÃO Big Noodle + Poppins (spec antigo do Manual, mantidos como fallback). Fundo do feed é
# CLARO (off-white texturizado), não dark/moody. Os layout_templates abaixo são REPERTÓRIO a
# recombinar, NUNCA molde fixo a reproduzir. Toda arte tem foto OU grafismo forte protagonista.

colors:
  primary: "#D21217"           # Vermelho Fast — cor principal (energia, movimento, ação)
  primary-active: "#A91918"    # Vermelho escurecido — hover/ativo
  primary-disabled: "#7D1715"  # Bordô — variante profunda / estado desabilitado
  on-primary: "#FFFFFF"        # Texto branco sobre vermelho
  secondary: "#FFCE00"         # Amarelo Fast — acento, destaques, energia
  on-secondary: "#191A1A"      # Texto preto sobre amarelo (contraste)
  canvas: "#F5F4F2"            # Off-white quente — fundo principal
  surface-card: "#FFFFFF"      # Branco puro — cards e superfícies
  ink: "#191A1A"               # Preto Fast — texto principal / títulos
  body: "#3C3C3B"              # Cinza escuro — corpo de texto
  accent: "#FFCE00"            # Amarelo — acento pontual
  muted: "#717578"             # Cinza médio — textos secundários, legendas

  # Paleta de suporte / secundária (Manual de Marca 2025)
  white: "#FFFFFF"
  black: "#191A1A"
  off-white: "#EAEAEA"
  gray: "#717578"
  gray-light: "#BCBCBC"
  gray-lighter: "#EAEAEA"
  gray-dark: "#3C3C3B"
  bordo: "#7D1715"             # Bordô — vermelho profundo
  red-alt: "#A91918"           # Vermelho alternativo
  blue: "#61619E"              # Azul-arroxeado — acento secundário raro
  gold: "#DBA04E"              # Dourado/ocre — paleta secundária (Steel Frame/Drywall)
  tan: "#A98259"               # Marrom/tan — paleta secundária

  # NÃO usar cor fora desta paleta (regra do Manual: "cor fora do padrão" = uso incorreto)

typography:
  display:
    fontFamily: "Anton"   # Títulos e headlines da marca
    fontSize: "100px"
    fontWeight: "700"
    lineHeight: "1.05"
    letterSpacing: "0.01em"
  heading:
    fontFamily: "Anton"
    fontSize: "70px"
    fontWeight: "700"
    lineHeight: "1.1"
  subheading:
    fontFamily: "Poppins"
    fontSize: "48px"
    fontWeight: "600"
    lineHeight: "1.3"
  body:
    fontFamily: "Poppins"
    fontSize: "28px"
    fontWeight: "400"
    lineHeight: "1.5"
  label:
    fontFamily: "Poppins"
    fontSize: "22px"
    fontWeight: "700"
    lineHeight: "1.3"
  caption:
    fontFamily: "Poppins"
    fontSize: "20px"
    fontWeight: "400"
    lineHeight: "1.4"

  # Regras de uso
  # - Anton: títulos condensados CAIXA-ALTA, "gritados" (ex.: VAI MONTAR DRYWALL?, PLACA ST)
  # - Poppins (Bold/SemiBold): títulos geométricos caixa-mista, consultivos; e corpo/labels/legendas
  # - Título SEMPRE bicolor preto + vermelho (palavra-chave em vermelho) + tracinho vermelho curto abaixo
  # - Máximo 2 famílias (Anton + Poppins). Fallback web: Anton→Oswald/Bebas pesada; Poppins→Montserrat
  # - (Manual antigo: Big Noodle + Montserrat — substituídos pela linha REAL do feed: Anton + Poppins)

spacing:
  xs: "16px"
  sm: "24px"
  md: "40px"
  lg: "64px"
  xl: "96px"
  section: "160px"

rounded:
  sm: "4px"
  md: "8px"
  lg: "16px"
  pill: "9999px"

# Logo
# - Símbolo: fusão criativa das letras "F" + "D" — remete a perfis de aço encaixados (Steel Frame),
#   a uma planta baixa (Drywall) e a um triângulo de "play" (ação/movimento/agilidade).
# - Assinatura: símbolo + "Fast" + "Sistemas Construtivos".
# - Cor: vermelho Fast (#D21217). Versão negativo: logo branco sobre fundo vermelho ou preto.
# - Versões aprovadas: HORIZONTAL (rodapés, e-mail, tarjas), VERTICAL (cabeçalhos, topo de site,
#   posts para redes, telas pequenas), REDUZIDA/SÍMBOLO (ícones, avatares, marca d'água).
# - Redução mínima: ~1,9–2,5 cm (impresso). Digital: manter legibilidade do símbolo.
# - Área de respiro: margem mínima de segurança ao redor da marca — respeitar espaço em branco.
# USOS INCORRETOS (proibido): distorcer/esticar, mudar cor fora da paleta, reposicionar elementos,
#   excluir o símbolo, circular ou contornar a marca, aplicar sombra/3D/relevo, rotacionar,
#   recriar com fontes diferentes.

components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.md}"
    padding: "16px 32px"
    height: "52px"
    fontFamily: "Poppins"
    fontWeight: "700"
    fontSize: "16px"

  button-secondary:
    backgroundColor: "transparent"
    textColor: "{colors.primary}"
    border: "2px solid {colors.primary}"
    rounded: "{rounded.md}"
    padding: "16px 32px"

  card:
    backgroundColor: "{colors.surface-card}"
    rounded: "{rounded.lg}"
    padding: "40px"
    border: "1px solid #EAEAEA"

  tag:
    backgroundColor: "{colors.primary}"
    textColor: "#FFFFFF"
    rounded: "{rounded.sm}"
    padding: "6px 12px"
    fontFamily: "Poppins"
    fontWeight: "700"
    fontSize: "12px"

# Regras de uso das cores
# PODE:
# - Vermelho #D21217 com fundo branco/off-white — combinação principal
# - Amarelo #FFCE00 como acento pontual (highlight, ícone, detalhe) — nunca como fundo de texto longo
# - Logo branco sobre fundo vermelho ou preto — versão negativo
# - Texto #191A1A sobre off-white para leitura longa
# - Cinzas (#717578, #BCBCBC, #EAEAEA) para hierarquia e apoio
#
# NÃO PODE:
# - Vermelho + amarelo saturados sobrepostos sem neutro entre eles
# - Cor fora da paleta oficial (uso incorreto no Manual)
# - Alterar os HEX das cores principais
# - Amarelo como cor de corpo de texto (baixo contraste)

# =============================================================================
# ESTILO DE IMAGEM — Referência visual da marca
# Para uso pelos motores de geração de imagem (gpt-image-1, etc.)
# Fonte: Manual de Marca 2025 + catálogos Fast (obra real de drywall/steel frame)
# =============================================================================

image_style:

  visual_philosophy:

    feel: "Técnico, ágil e confiável, com energia. Moderno e industrializado, mas humano (obra real, gente trabalhando). Não é 'loja de material barato' nem grife fria — é autoridade acessível em construção a seco."

    forbidden_aesthetic: "Fundo chapado com cor sólida + texto centralizado (cara de template pronto). Estoque genérico de 'engravatado apertando a mão'. Render 3D plastificado sem contexto de obra real. Excesso de vermelho saturado cobrindo tudo."

    background_rule: |
      OBRIGATÓRIO: TODO slide precisa de fundo com foto de obra real (steel frame, drywall,
      fachada, piso instalado) OU textura de material real (aço galvanizado, gesso, cimentício,
      madeira do piso). Vale inclusive para slides de infográfico, lista e comparação — o
      grafismo (ícones, losangos, cards, blueprint) entra POR CIMA da foto/textura, NUNCA
      sozinho sobre off-white. Off-white texturizado + grid/blueprint NÃO conta como fundo:
      é só a zona de texto sobre a foto. Fundo chapado + texto é inaceitável. O vermelho entra
      como acento/destaque, não como fundo total. ÚNICA exceção: o slide de CTA final, que é
      vermelho Fast sólido. (Regra endurecida no 1º teste, jul/2026.)

    avoid:
      - "Layouts retos, simétricos e centrados demais"
      - "Vermelho cobrindo o slide inteiro em todos os cards"
      - "Foto de banco de imagem sem relação com construção a seco"
      - "Placa/parede apresentada como elemento 'estrutural' (contraria a norma)"

    pursue:
      - "Composições em camadas: foto de obra + elemento gráfico + texto"
      - "Detalhe técnico real (corte de parede, perfil de aço, textura de placa/piso)"
      - "Pessoas reais em ação na obra (instalador, arquiteto, cliente no ambiente pronto)"
      - "Contraste de acabamento: ambiente finalizado e sofisticado vs. estrutura técnica"

  photography:

    obra_em_acao:
      description: "Profissional aplicando o sistema — instalador em parede de drywall, montagem de steel frame, assentamento de piso"
      mood: "Real, dinâmico, luz de canteiro; foco em produtividade e precisão"
      lighting: "Natural de obra, side light; nada artificial demais"
      color_grade: "Neutro com leve calor; vermelho da marca aparece em EPI/detalhe quando possível"
      subjects: "Instalador, gesseiro, engenheiro/arquiteto em campo, ferramenta Fast em uso"
      framing: "Ação cropada, sujeito ligeiramente fora do centro"
      brand_subjects: "Montagem de perfil de aço, parafusadeira na placa, nível na parede, régua de piso vinílico sendo encaixada"

    ambiente_pronto:
      description: "Ambiente finalizado — sala/quarto/comercial com forro, parede lisa, piso vinílico instalado"
      mood: "Clean, aspiracional, acolhedor"
      lighting: "Luz natural ampla, sombras suaves"
      color_grade: "Fiel, levemente quente; valoriza acabamento e textura do piso"
      framing: "Arquitetural, linhas retas, profundidade de ambiente"
      brand_subjects: "Piso Biancogres instalado, forro acústico, parede de drywall acabada, fachada em steel frame"

    detalhe_material:
      description: "Macro do material e da estrutura — perfil galvanizado, corte de parede em camadas, textura de placa/piso"
      mood: "Técnico e elegante ao mesmo tempo"
      framing: "Close-up extremo — textura e encaixe"
      color_grade: "Neutro, fiel à cor real do material (aço, gesso, cimentício, madeira do vinílico)"
      brand_subjects: "Corte transversal da parede (aço + lã + placa), rosca do parafuso, veio do piso vinílico, malha de fibra do Glasroc"

  backgrounds:

    off_white_textured:
      use: "Zona de TEXTO sobre a foto (painel/card recortado). NUNCA ocupa o slide sozinho — sempre há foto/textura de material atrás ou ao lado (ver background_rule). Vale para infográficos e comparativos também: o off-white é o painel do texto, não o fundo. Exceção única do slide sem foto: CTA final (vermelho sólido)."
      color: "#F5F4F2 off-white quente"
      texture: "Textura sutil de papel/linho"
      feel: "Leve, limpo, técnico"

    solid_accent:
      use: "Slide de CTA final, fechamento, destaque de marca"
      color: "Vermelho Fast #D21217 (fundo sólido)"
      texture: "Textura sutil opcional"
      feel: "Impacto, energia, marca"

    full_bleed_photo:
      use: "Capa e slides de solução — foto grande integrada"
      description: "Foto CLARA de obra/ambiente ocupa grande porção; dissolve diagonal para a off-white à esquerda (zona do texto). O feed é CLARO, não escuro/moody."
      overlay: "Transição suave off-white→foto (máscara diagonal); NÃO usar overlay escuro opaco"
      text_color: "Preto/carvão sobre a off-white; branco só dentro de box vermelho/carvão"

    full_bleed_bright:
      use: "Slide de solução — ambiente pronto, piso/forro/fachada instalados"
      description: "Foto clara/natural, produto visível no contexto"
      text: "Vermelho Fast ou preto conforme a foto"

    split_dynamic:
      use: "Slides de contexto/comparação"
      layout: "60% foto de obra CLARA + 40% painel vermelho Fast, borda diagonal/curva na divisão"
      text: "Branco sobre o painel vermelho"

  graphic_elements:

    text_highlight_box:
      description: "Retângulo sólido atrás de palavras-chave"
      color: "Vermelho #D21217 (sobre fundo claro) ou Amarelo #FFCE00 (destaque pontual)"
      text_color: "Branco sobre vermelho; preto sobre amarelo"
      usage: "Destacar nome do produto (Placa Performa, Glasroc X), spec (<5% absorção), prova"
      style: "Padding pequeno (4-8px), sem border-radius exagerado"

    hand_drawn_loop:
      description: "Oval/loop à mão em traço fino circundando sujeito ou produto"
      color: "Vermelho Fast #D21217"
      style: "Brush fino, levemente imperfeito — anotação orgânica, NÃO geométrico"
      usage: "Cover sobre pessoa/obra, slide de produto em destaque"

    # white_bracket_frame: elemento do template antigo (cover escuro) — NÃO faz parte da linha real
    # da Fast (capas são claras). Não usar; mantido só como histórico.

    floating_card:
      description: "Card branco arredondado flutuando sobre a foto, sombra suave"
      radius: "16-24px"
      shadow: "Sombra ambiente suave, não hard drop shadow"
      usage: "Container de spec técnica em slides full-bleed"

    icon_circle:
      description: "Círculo sólido com ícone de linha branco dentro"
      fill: "Vermelho Fast #D21217"
      icon: "Branco, estilo outline/line"
      usage: "Infográficos SEM vs COM, listas de vantagens"
      icon_subjects: "Perfil de aço, parede, gota (umidade), chama (fogo/RF), folha (sustentável), régua/piso, ferramenta"

    accent_blob:
      description: "Forma orgânica grande em vermelho aparecendo por um canto"
      usage: "Canto de slides de solução, transição para CTA"
      style: "Quarto de círculo/forma orgânica — só a borda aparece"

    pill_cta:
      description: "Botão pill/cápsula com texto pequeno"
      style: "Outline (só borda) — branco sobre escuro, vermelho sobre claro"
      radius: "9999px"
      usage: |
        CTA do cover e CTA final. Usar SOMENTE os CTAs oficiais do repositório — NÃO inventar
        (ex.: "Fale com a gente" está descartado). Lista oficial, escolher pelo objetivo do post:
        'Fale com um especialista' (consideração/consultoria) · 'Ver na loja' (venda loja/e-commerce) ·
        'Agende uma conversa estratégica' (franquia). Fonte: _contexto/estrategia.md.

    spec_bar:
      description: "Barra horizontal na base com specs técnicas"
      style: "Fundo #191A1A, texto branco, labels pequenos"
      usage: "Slides de produto específico"
      brand_specs: "Ex.: 'Glasroc X | absorção <5% | incombustível | 11 kg/m²' · 'Massima Pró | capa 0,55mm | classe até 42 | 10 anos'"

  layout_templates:

    T1_capa:
      name: "Capa (repertório — variar sempre; regras completas em .claude/memory/feedback_capas_fast.md)"
      background: "Off-white CLARO; foto/render claro integrado por dissolve diagonal (grande porção à direita)"
      elements:
        - "Logo lockup completo no topo-esquerda"
        - "Hook bicolor preto+vermelho (Anton ou Poppins) + tracinho vermelho curto"
        - "Cue 'Arrasta ▶' na base + acento diagonal vermelho (losango/faixa)"
      palette: "Off-white + foto clara + vermelho + preto"
      prompt_style: "Clean natural daylight, bright airy, real steel frame/drywall, light background — NUNCA moody/dark"

    T2_problema_highlight:
      name: "Problema com Highlight"
      background: "Off-white texturizado #F5F4F2"
      elements:
        - "Headline #191A1A grande, Anton"
        - "Corpo em cinza #3C3C3B, Poppins regular"
        - "Highlight boxes vermelhos atrás de frases-chave"
      palette: "Off-white + preto + highlight vermelho"
      no_photo: true

    T3_regra_simples:
      name: "Regra Simples (SEM vs COM)"
      background: "Off-white texturizado"
      elements:
        - "Título 'Regra simples' — cinza, topo"
        - "2 linhas: círculo vermelho com ícone + label highlight + corpo cinza"
        - "Muito respiro, sem fotos"
      palette: "Off-white + cinza + círculos vermelhos + highlight"
      no_photo: true

    T4_split_dinamico:
      name: "Split Dinâmico"
      background: "Foto de obra CLARA (60%) + painel vermelho Fast (40%), borda diagonal/curva"
      elements:
        - "Texto no painel vermelho, branco"
        - "Headline Anton + corpo Poppins"
      palette: "Foto clara + vermelho + branco"

    T5_photo_floating_card:
      name: "Full Photo com Floating Card"
      background: "Foto de ambiente pronto / obra full-bleed"
      elements:
        - "Card branco arredondado com texto"
        - "Linhas de acento vermelhas flanqueando o card"
        - "Highlight vermelho no texto do card"
      palette: "Foto atmosférica + card branco + acento vermelho"

    T6_solucao_produto:
      name: "Solução Produto"
      background: "Off-white texturizado"
      elements:
        - "Esquerda: headline com box vermelho atrás do nome do produto"
        - "Direita: foto do produto em container arch arredondado"
        - "Base: detalhe/close-up do material"
        - "Loop fino desenhado à mão ao redor da composição"
      palette: "Off-white + highlights vermelhos + foto real do produto"

    T7_cta_acento:
      name: "CTA Acento"
      background: "Vermelho Fast #D21217 (slide inteiro)"
      elements:
        - "Logo Fast branco, centralizado"
        - "Headline curto e forte em branco (Anton)"
        - "Pill CTA outline branco"
        - "Foto do slide anterior aparecendo por uma borda (continuidade)"
        - "Textura sutil opcional no fundo vermelho"
      palette: "Vermelho + branco"

  image_typography:
    cover_label: "Poppins 400, pequeno (14-16px equiv), caixa alta ou sentence case"
    cover_headline: "Anton ou Poppins Bold, muito grande (60-80px equiv), BICOLOR preto+vermelho sobre off-white (branco só dentro de box/painel)"
    slide_headline: "Anton 700, grande (40-56px equiv), #191A1A sobre claro"
    body_text: "Poppins 400, médio (20-24px equiv)"
    highlight_text: "Mesma fonte/peso do entorno — só o fundo muda (box vermelho/amarelo)"
    cta_text: "Poppins 700, pequeno (14-16px equiv)"

  brand_adaptation:
    accent_color: "vermelho Fast #D21217"
    cta_slide: "fundo vermelho #D21217 + logo/branco"
    split_panel: "painel vermelho #D21217"
    highlight_box: "box vermelho #D21217 (texto branco) ou amarelo #FFCE00 (texto preto)"
    icon_circles: "círculos vermelhos #D21217 com ícone branco"
    product_photos: "produtos Fast reais (drywall, steel frame, piso Biancogres, forro, Glasroc X)"
    lifestyle_context: "obra brasileira real, ambiente residencial/comercial acabado a seco"
    spec_bar_values: "specs reais dos produtos (ver produtos/normas-desempenho.md)"
    infographic_contrast: "alvenaria vs. construção a seco; sem sistema de fachada vs. sistema completo"
