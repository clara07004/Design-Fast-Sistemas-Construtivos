---
name: agente
description: >
  Chama o agente de design da Fast (Diretor de Arte Sênior — designer-fast) para
  direção criativa, parecer visual, revisão de carrossel/post, escolha de ângulo
  visual de um briefing ou coordenação da produção (briefing → prompts → imagens →
  carrossel → legenda). Use quando o usuário disser "/agente", "chama o designer",
  "preciso do agente de design", "quero direção de arte", "design review".
---

# /agente — Chamar o agente de design

Aciona o **designer-fast** (Diretor de Arte Sênior da Fast) via a ferramenta Agent.
É atalho direto pro agente de design — não tente resolver a demanda visual sozinho aqui.

## O que fazer

1. Pegue o pedido do usuário em `$ARGUMENTS`.
   - **Se veio texto** (ex.: `/agente revisa o carrossel de fachada`), passe esse texto
     como tarefa pro agente.
   - **Se veio vazio** (`/agente` sozinho), pergunte antes de invocar:
     > "Chamando o Diretor de Arte da Fast. O que você precisa? (ex.: revisar um carrossel,
     > direção de arte de um briefing, decidir layout/foto, escolher o produto a destacar)"
     > Aguarde a resposta e use-a como tarefa.

2. Invoque o agente com a ferramenta **Agent**, `subagent_type: "designer-fast"`, passando
   no `prompt` a demanda do usuário mais o contexto necessário (data de publicação, formato,
   briefing ou peça em questão, caminho dos arquivos relevantes).

3. Quando o agente responder, **repasse o parecer/entrega ao usuário** de forma direta —
   o resultado do agente não aparece automaticamente pra ele. Destaque as decisões e os
   próximos passos.

## Continuidade

- Se já houver um `designer-fast` rodando ou recém-concluído nesta sessão, **continue-o
  com SendMessage** (mantém o contexto) em vez de abrir um novo com Agent.

## Regras

- Não duplicar o trabalho: este comando é só o disparo do agente. A inteligência de design
  mora no `designer-fast` (identidade em `marca/DESIGN.md`, linha visual em
  `.claude/memory/feedback_linha_visual_fast.md`, produtos em `produtos/`).
- Tom direto, em pt-BR.
