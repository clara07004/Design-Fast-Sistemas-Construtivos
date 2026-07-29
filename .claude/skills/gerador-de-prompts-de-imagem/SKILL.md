---
name: gerador-de-prompts-de-imagem
description: Cria prompts precisos e estruturados para geração de imagem com IA — thumbnails, capas de carrossel, posts, stories. Melhora diretamente a qualidade das imagens geradas pelo /gpt-image2-unity. Use ANTES de executar o script gerar-imagem.py quando quiser um prompt mais elaborado do que o padrão. Dispara quando: "quero criar uma imagem com IA", "me ajuda a escrever um prompt", "preciso melhorar o prompt dessa imagem".
---

# Gerador de Prompts de Imagem

## Contexto da empresa

Antes de gerar, ler:
- `_contexto/empresa.md` — produtos, contexto de uso e posicionamento da empresa
- `.claude/memory/feedback_linha_visual_fast.md` — **DNA visual real** (estilos de foto: obra_em_acao, ambiente_pronto, detalhe_material; estética CLARA)
- `marca/DESIGN.md` → seção `image_style` — paleta e adaptação de marca
- `_contexto/preferencias.md` — restrições visuais (sem EPI incorreto, sem obras improvisadas)

**Regras fixas para qualquer prompt:**
- Sempre em inglês
- Sempre incluir: `no text overlay`, `no watermarks`, `photorealistic`
- **Estética Fast = luz natural de dia, clara, limpa, arejada** (aço levemente frio, interiores quentes). **NUNCA dark/moody/dramatic** — o feed da Fast é CLARO (off-white). Incluir sempre algo como `clean natural daylight, bright airy, light background`.
- Nunca: obras com EPI incorreto, texto embutido, ilustrações genéricas
- Contexto preferencial: ambiente de uso do produto, arquitetura contemporânea, alto padrão

**Ferramenta alvo:** `gpt-image-1` (OpenAI). Os prompts são otimizados para este modelo.

---

## Diagnóstico inicial

Confirmar antes de gerar:
1. Qual o objetivo da imagem? (capa carrossel, fundo post estático, story, imagem avulsa)
2. O que deve aparecer? (esquadria instalada, detalhe de produto, cena de obra, ambiente interno)
3. Qual o estilo de foto? (obra_em_acao / ambiente_pronto / detalhe_material) — **sempre luz natural clara, nunca dark/moody**
4. Qual a proporção? (square 1:1, portrait 9:16, landscape 3:2)

---

## Anatomia de um prompt eficaz

```
[SUJEITO] + [AÇÃO/ESTADO] + [AMBIENTE/CONTEXTO] + [ESTILO] + [ILUMINAÇÃO] + [QUALIDADE] + [RESTRIÇÕES]
```

**Exemplos por camada (adaptar ao produto da empresa):**

**Sujeito:** "[produto] in modern apartment", "[produto] installed in contemporary project", "close-up of [produto] technical detail"

**Ambiente/Contexto:** "contemporary Brazilian residence", "high-end construction site", "modern minimal interior with natural light"

**Estilo:** "professional architectural photography", "cinematic still", "editorial architectural photography"

**Iluminação:** "natural daylight flooding through windows", "soft ambient side light", "dramatic golden hour"

**Qualidade:** "ultra detailed", "8k resolution", "photorealistic", "sharp focus"

**Restrições fixas:** "no text overlay, no watermarks, no people, photorealistic"

---

## Prompts por caso de uso

### Capa de Carrossel (portrait 1024×1536)
```
[Cena de obra real / steel frame / drywall relacionada ao tema do carrossel],
clean natural daylight, bright airy atmosphere, light background, [composição com área para texto],
professional architectural photography, high-end Brazilian construction context,
[produto da empresa se aplicável ao tema],
no text overlay, no watermarks, photorealistic, portrait format
```

### Post Estático — fundo full-bleed (portrait 1024×1536)
```
[Cena concreta do produto ou ambiente de uso],
cinematic professional photography, [iluminação], [enquadramento],
contemporary architecture, premium materials, warm natural tones,
no text overlay, no watermarks, no people (unless specified), photorealistic, portrait format
```

### Imagem de produto instalado
```
[Nome do produto, ex: PVC casement window] installed in [contexto de projeto],
natural daylight from outside, contemporary interior design, minimal decor,
architectural installation photography, wide to mid shot showing full product in context,
warm wood tones and white walls, no text overlay, photorealistic
```

---

## Modificadores por estilo (linha visual real da Fast — sempre CLARO)

| Estilo | Modificadores |
|---|---|
| obra_em_acao | real steel frame/drywall site, professional installing, clean natural daylight, dynamic, bright, slight cool tone on steel |
| ambiente_pronto | finished interior (forro, parede lisa, piso vinílico), clean, aspirational, ample natural light, warm soft shadows |
| detalhe_material | macro of profile/board/floor texture, technical yet elegant, neutral true-to-material color, bright, sharp |
| off_white_textured | soft, clean, paper/plaster texture, warm off-white light background |

> **Nunca** usar `dark_lifestyle` / `full_bleed_dark` / "moody" / "dramatic dark" — eram do template antigo. O feed da Fast é claro, natural e limpo. Para "problema/alvenaria" use tom levemente dessaturado, não escuro/cinematográfico.

---

## Output

```
OBJETIVO DA IMAGEM: [uso]
PROPORÇÃO: [square / portrait / landscape]
ESTILO: [estilo do DESIGN.md]

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

PROMPT PRINCIPAL:
[prompt completo, pronto para usar no script gerar-imagem.py]

VARIAÇÃO A (mais minimalista): [...]
VARIAÇÃO B (mais impactante): [...]

ASPECT RATIO PARA O SCRIPT: [square / portrait / landscape]

COMANDO POWERSHELL (destino = pasta de produção do conteúdo; não existe conteudo/imagens/):
# Carrossel:    conteudo/carrosseis/[periodo]/[dia-tema]/instagram/img-slideXX.png
# Post estático: conteudo/post-estatico/[periodo]/[dia-tema]/img-post.png
python ".claude/skills/gpt-image2-unity/gerar-imagem.py" "[PROMPT]" "conteudo/carrosseis/[periodo]/[dia-tema]/instagram/img-slideXX.png" "[RATIO]"
```
