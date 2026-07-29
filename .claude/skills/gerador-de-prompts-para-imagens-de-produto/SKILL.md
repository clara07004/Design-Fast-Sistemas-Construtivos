---
name: gerador-de-prompts-para-imagens-de-produto
description: Gera prompts especializados para imagens do produto principal da empresa — produto instalado em contexto de uso, mockups, ambientação, close-up de detalhes técnicos. Complemento direto do /gpt-image2-unity focado em fotografia de produto. Dispara quando: "quero imagem do produto", "prompt para foto de produto", "imagem de produto com IA", "foto do produto instalado".
---

# Gerador de Prompts para Imagens de Produto

## Contexto

Antes de gerar, ler:
- `_contexto/empresa.md` — o que é o produto, linhas/variantes, contextos de uso, ICP
- `.claude/memory/feedback_linha_visual_fast.md` — **estilos de foto reais da Fast** (obra_em_acao, ambiente_pronto, detalhe_material) — sempre **luz natural clara, nunca dark/moody**
- `marca/DESIGN.md` → `image_style` — paleta e adaptação de marca
- `_contexto/referencias.md` → pasta "Fotos do Produto" no Drive para referência de estilo real

**Produto:** conforme `_contexto/empresa.md`. Nunca inventar características — usar só o que está documentado.

---

## Coleta de Informações

**Obrigatório:**
- `[LINHA/VARIANTE]` — qual linha ou versão do produto aparece na cena
- `[TIPO DE CENA]` — produto instalado / detalhe técnico / ambiente de uso / obra/processo
- `[USO DA IMAGEM]` — capa carrossel / post estático / story / material técnico
- `[ESTILO]` — conforme `image_style.photography` no DESIGN.md (estilo_foto_1 / estilo_foto_2 / estilo_foto_3)

**Opcional:**
- `[AMBIENTE]` — tipo de espaço, contexto de uso, perfil de projeto
- `[PESSOAS]` — sem pessoas (padrão) / usuário do produto / profissional em operação

---

## Os 3 Estilos de Foto (linha real da Fast — todos CLAROS)

Ver `.claude/memory/feedback_linha_visual_fast.md`. Todos com **luz natural de dia, limpa**.

### obra_em_acao
Profissional aplicando o sistema (instalador em drywall, montagem de steel frame, assentamento de piso). Luz de canteiro natural, dinâmico, real, claro; leve tom frio no aço.

### ambiente_pronto
Ambiente finalizado (sala/comercial com forro, parede lisa, piso vinílico instalado). Clean, aspiracional, luz natural ampla, sombras suaves quentes.

### detalhe_material
Macro do material/estrutura (perfil galvanizado, corte de parede em camadas, textura de placa/piso). Técnico e elegante, cor fiel ao material, claro e nítido.

---

## Templates de Prompt por Estilo

### ambiente_pronto — produto instalado (mais usado)
```
[DESCRIÇÃO DO PRODUTO, ex: drywall wall / vinyl floor / acoustic ceiling] installed in
[AMBIENTE, ex: modern high-end residence],
clean natural daylight, bright airy interior, light tones, clean lines, no clutter,
professional architectural photography, wide to mid shot showing full product in context,
no text overlay, no watermarks, no people, photorealistic, portrait format
```

### obra_em_acao — profissional em obra
```
[SUJEITO, ex: professional installer] working on
[PRODUTO/SISTEMA] at [steel frame / drywall site],
clean natural daylight, bright, dynamic real construction context,
candid pose, environmental context visible, slight cool tone on steel,
professional documentary photography, no text overlay, photorealistic, portrait format
```

### [estilo_foto_3] — close-up técnico
```
extreme close-up of [DETALHE, ex: product cross-section showing internal structure],
[DETALHE TÉCNICO — ex.: material layers, sealing detail, joint],
neutral color grade true to product, technical and elegant simultaneously,
macro photography, sharp focus, studio lighting, white or neutral background,
no text overlay, photorealistic
```

---

## Output

```
PRODUTO: [linha/variante e tipo]
ESTILO: [nome do estilo conforme DESIGN.md]
USO: [onde vai ser usada]

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

PROMPT PRINCIPAL:
[prompt completo otimizado para gpt-image-1]

VARIAÇÃO (ângulo diferente): [prompt alternativo]

ASPECT RATIO: [square / portrait / landscape]

COMANDO POWERSHELL (destino = pasta de produção do conteúdo):
# Carrossel:      conteudo/carrosseis/[periodo]/[dia-tema]/instagram/img-slideXX.png
# Post estático:  conteudo/post-estatico/[periodo]/[dia-tema]/img-post.png
python ".claude/skills/gpt-image2-unity/gerar-imagem.py" "[PROMPT]" "conteudo/post-estatico/[periodo]/[dia-tema]/img-post.png" "[RATIO]"

DICAS ESPECÍFICAS:
[O que ajustar se o resultado não estiver no nível esperado]
```
