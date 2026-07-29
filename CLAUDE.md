# CCOS — Sistema de Automação de Conteúdo

## O que é esse workspace

> **Projeto configurado para a Fast Sistemas Construtivos** (via `/setup`). Este workspace é o projeto de conteúdo/design da Fast — contexto (`_contexto/`), marca (`marca/`), base técnica (`produtos/`) e outputs (`conteudo/`) são reais e devem ser mantidos. Credenciais ficam em `credentials/` / `.env` (nunca committar).

Sistema de automação do processo de criação de conteúdo para redes sociais. Orquestra skills de IA para ir da definição estratégica até a entrega do pacote de conteúdo pronto para publicação.

**Empresa:** Fast Sistemas Construtivos — referência nacional e maior ecossistema de **construção a seco** do Brasil (drywall, steel frame, acústica, pisos vinílicos, esquadrias, argamassas), operando indústria, varejo, atacado, engenharia/obras e franquias (Fast Franchising — 1ª franquia de drywall do Brasil, certificada pela ABF; Fast Homes — casas modulares em steel frame). Contexto completo em [_contexto/empresa.md](_contexto/empresa.md); identidade visual em [marca/DESIGN.md](marca/DESIGN.md); base técnica em [produtos/](produtos/README.md).

**Estrutura de pastas:**
- `_contexto/` — memória do sistema (não apagar)
- `marca/` — DESIGN.md e identidade visual
- `dados/` — arquivos para análise (CSV, PDF, prints, referências)
- `templates/skills/` — templates de skills prontos pra personalizar com /mapear
- `templates/ferramentas/catalogo.md` — APIs e ferramentas disponíveis pra usar em skills
- `credentials/` — credenciais e tokens (não committar)

---

## Contexto do negócio

No início de toda conversa, ler os seguintes arquivos (se existirem e estiverem configurados):

1. `_contexto/empresa.md` — quem é o usuário, o que faz, como funciona o negócio
2. `_contexto/preferencias.md` — tom de voz, estilo de escrita, o que evitar
3. `_contexto/estrategia.md` — foco atual, prioridades, o que pode esperar
4. `_contexto/referencias.md` — pastas do Google Drive com material de referência visual

Usar essas informações como base pra qualquer resposta ou decisão. Ao sugerir prioridades, formatos ou abordagens, considerar o foco atual descrito em `estrategia.md`.

Para qualquer tarefa visual (carrossel, proposta, slide, landing page), consultar `marca/DESIGN.md` como referência de estilo.

**Referências visuais do Drive:** quando `_contexto/referencias.md` tiver pastas configuradas, consultá-las antes de criar qualquer conteúdo visual. Usar o MCP do Google Drive para listar os arquivos da pasta relevante (`search_files` com `parentId = 'ID_DA_PASTA'`) e baixar as imagens com `download_file_content`. Priorizar imagens menores que 300KB para caber no contexto. Usar o material encontrado como referência de estilo, produto e padrão visual — não como template a copiar literalmente.

Não é necessário listar o que foi lido nem confirmar a leitura. Apenas usar o contexto naturalmente.

---

## Conhecimento técnico do produto (consulta obrigatória)

**Antes de gerar calendário, briefing, roteiro, carrossel ou post estático**, ler os arquivos relevantes em `produtos/`. Esse diretório consolida toda a documentação técnica oficial (catálogos, manuais, laudos, fichas técnicas) da empresa.

A empresa tem um posicionamento definido em `_contexto/empresa.md` — o conteúdo precisa:

- **Ser realista e verdadeiro:** nunca inventar dimensões, ensaios, certificações ou valores de desempenho. Tudo precisa estar lastreado em `produtos/`
- **Conter especificações técnicas reais:** citar linhas, variantes, normas e valores reais documentados nos arquivos de produto
- **Permitir que o cliente conheça o produto pelo post:** o conteúdo é parte da qualificação do lead, não decoração visual
- **Manter o posicionamento:** vocabulário alinhado com `_contexto/preferencias.md`, sem comparações genéricas sem lastro

Arquivos de consulta principais:
- `produtos/README.md` — índice de todos os tópicos
- `produtos/visao-geral.md` — características e vantagens do produto/serviço
- `produtos/normas-desempenho.md` — normas técnicas, certificações, laudos, valores ensaiados
- `produtos/fotos-obras/` — acervo visual real (curar antes de usar; a origem foto real × IA é escolhida no briefing, não é automática)
- Demais arquivos em `produtos/` conforme indexado no README

**Frases genéricas para revisar:** "qualidade superior", "máxima durabilidade", "tecnologia avançada" sem citar dado técnico = reescrever com número real do laudo ou da norma.

**SUBSTITUIÇÃO OBRIGATÓRIA — OSB por contexto (setor de construção a seco):** sempre que qualquer conteúdo (briefing, roteiro, carrossel, legenda, post estático) mencionar "placa OSB", "OSB" ou "chapa de OSB", **substituir automaticamente, sem perguntar**, conforme o contexto: **uso interno** (parede/divisória) → **"Placa Performa"**; **uso externo/fachada** → **"Glasroc X"** (nunca usar "Placa Performa" em contexto de fachada). A placa OSB caiu em desuso e não é mais mencionada pelas marcas do grupo. **Nunca atribuir função estrutural ao fechamento** (OSB, gesso, cimentícia): no Steel Frame brasileiro a integridade é da estrutura de aço — o fechamento é vedação; a NBR brasileira não exige OSB estrutural. Contexto em `produtos/base-normativa-abnt.md`, `produtos/placas.md` (seção 4) e em [_contexto/preferencias.md](_contexto/preferencias.md).
> Default do setor de construção a seco. Empresa replicada que **não** trabalhe com Steel Frame/Drywall ou não adote a Placa Performa deve ajustar/remover esta regra no setup.

---

## Skills disponíveis

**Skills do sistema CCOS (genéricas):**
- `/setup` — configura o sistema pro seu negócio (rodar na primeira vez)
- `/syncar` — salva o trabalho no GitHub (commit + push)
- `/mapear` — entrevista processos repetitivos e cria skills personalizadas

**Skills de conteúdo:**
- `/calendario-comercial` — mapa de oportunidades do período (quando e o quê postar)
- `/briefing-unity` — briefing completo de um tema: objetivo, mensagem, formato, referências
- `/carrossel-unity` — produção de carrossel: texto + HTML + PNG via Playwright
- `/estatico-unity` — produção de post card único: foto IA + HTML + PNG via Playwright
- `/roteiro-unity` — roteiro de vídeo para Reels/TikTok (orgânico via Ogilvy, tráfego via Schwartz)
- `/publicar-social-unity` — publica conteúdo aprovado no Instagram, TikTok, LinkedIn

**Skills de pesquisa e ideação:**
- `/gerador-de-angulos-para-um-tema` — 10 lentes criativas para explorar um tema antes do briefing
- `/gerador-de-angulos-de-conteudo` — matrix perspectivas × audiência × formatos narrativos, 10 ângulos únicos
- `/banco-de-objecoes-do-avatar` — mapeia 6 tipos de objeção por ICP com resposta em conteúdo

**Skills de copy e distribuição:**
- `/hooks-para-carrossel` — 5 opções de capa para carrossel com direção visual (usar antes do /carrossel-unity)
- `/hooks-para-instagram-reels` — 7 tipos de hook combinados (primeiro frame + frase de abertura)
- `/legenda-para-carrossel` — legenda orientada a save com CTA específico
- `/legenda-para-reel` — legenda que complementa o vídeo sem repetir o script
- `/legenda-para-post-estatico` — 4 tipos de legenda para post estático
- `/carrossel-de-quebra-de-objecao` — carrossel de fundo de funil em 3 movimentos (nomeação → reframe → prova)
- `/1-conteudo-em-7-formatos` — repurposing: transforma 1 conteúdo em Reel, Carrossel, Story, Thread, LinkedIn, E-mail e Post estático

**Skills de imagem:**
- `/gerador-de-prompts-de-imagem` — prompt estruturado para gpt-image-1 (usar antes de gerar imagem)
- `/gerador-de-prompts-para-imagens-de-produto` — prompts para as estéticas de produto da empresa (estilos configurados em `marca/DESIGN.md`)

**Motores (usados internamente pelas skills de produção):**
- `/gpt-image2-unity` — gera foto de fundo via GPT Image 2 (motor de imagem do carrossel e post estático)
- `/ogilvy-copy` — copy de marca e conteúdo orgânico (motor do roteiro orgânico)
- `/schwartz-copy` — copy de resposta direta (motor do roteiro de tráfego pago)

---

## Fluxo principal de conteúdo

### Etapa 1 — Ideação e planejamento (sempre)

```
/gerador-de-angulos-para-um-tema   ← 10 lentes criativas para um tema
    ou
/gerador-de-angulos-de-conteudo    ← matrix perspectivas × audiência × formatos
    ↓ [escolhe ângulo]
/calendario-comercial              ← quando e o quê postar
    ↓ [aprova calendário]
/briefing-unity                    ← define objetivo, mensagem e formato
    ↓ [aprova briefing]
```

**REGRA OBRIGATÓRIA — Calendário de novo mês entrega SEMPRE 3 arquivos**

Toda vez que rodar `/calendario-comercial` para um mês (ou qualquer período fechado), gerar dentro de `conteudo/calendarios/[periodo]/`:

1. **`calendario-detalhado.md`** — post a post, numerado, com tema/formato/janela/status (alimenta os `/briefing-unity` posteriores)
2. **`_aprovado.md`** — memória da aprovação: tema narrativo, mix, apagões, picos, ajustes feitos, o que evitar
3. **`dashboard.html`** — grid visual do mês inteiro, derivado direto do `calendario-detalhado.md`, usando o template `templates/dashboard-calendario.html` (identidade visual da marca, canvas 1920×1080)

O dashboard **não é opcional** — é entrega obrigatória junto com o calendário, mesmo que o usuário não peça explicitamente. Após gerar o HTML, perguntar se renderiza o PNG via Playwright (esse passo sim é opcional).

A skill `/calendario-comercial` já tem a especificação completa na seção "8. ENTREGAS OBRIGATÓRIAS" — seguir literalmente.

---

### Etapa 2 — Produção (escolher o fluxo pelo formato)

**REGRA OBRIGATÓRIA — Confirmar o formato antes de produzir (exceto carrossel)**

Quando o conteúdo de um dia estiver marcado no calendário como **Reel, post estático, vídeo ou qualquer formato que NÃO seja carrossel**, SEMPRE perguntar ao usuário qual o formato do conteúdo antes de gerar qualquer coisa (hook, roteiro, briefing, prompt, imagem, HTML). Não assumir o formato do calendário automaticamente — ele é sugestão, a decisão final é do usuário. Quando o formato for **carrossel**, seguir direto o fluxo sem perguntar.

**REGRA OBRIGATÓRIA — Nomenclatura da pasta de produção pela DATA DE PUBLICAÇÃO**

A pasta de produção de cada conteúdo é nomeada pela **data de publicação** no formato `dia-DD-tema-curto` (ex.: conteúdo que publica em 17/07 → `dia-17-linhas-pvc-vao`). **Nunca usar o número do post do calendário** — em meses com domingos sem post ou apagões, o número do post deixa de coincidir com o dia do mês (ex.: Post 15 publica em 17/07). O `DD` é sempre o dia em que o conteúdo vai ao ar.

**REGRA OBRIGATÓRIA — PNGs finais renderizados vão SEMPRE para uma subpasta `posts prontos/`**

Ao renderizar as imagens, os **PNGs finais publicáveis** (os slides renderizados do carrossel, o card do post estático e o slide de CTA copiado de `CTA's/`) são gravados dentro de uma subpasta chamada **`posts prontos/`**, para não se misturarem com os HTMLs e imagens-fonte na hora de selecionar o que publicar. Estrutura:

- **Carrossel:** `conteudo/carrosseis/[periodo]/[dia]/instagram/posts prontos/slide-XX.png` (versão TikTok em `.../tiktok/posts prontos/`).
- **Post estático:** `conteudo/post-estatico/[periodo]/[dia]/posts prontos/post-01.png`.

Os **HTMLs** (`slide-XX.html`, `post-01.html`) e as **imagens-fonte** (`img-slideXX.png`, `img-post.png`) **permanecem na pasta do dia** — não movê-los para `posts prontos/`, senão os caminhos relativos (`./img-slideXX.png`, `../../../../marca/`) quebram na renderização. O Playwright lê o HTML da pasta original e só grava o PNG de saída em `posts prontos/`. As skills `/carrossel-unity` e `/estatico-unity` já têm essa regra na especificação — seguir literalmente.

#### Carrossel

**FLUXO PRINCIPAL ★ — usar SEMPRE este, a menos que o usuário peça explicitamente outro.** Quando o calendário já existe, começa no `/briefing-unity` (não nos hooks):
```
/briefing-unity                  ← ponto de partida (calendário já aprovado)
    ↓ [aprova briefing]
/gerador-de-prompts-de-imagem    ← FLUXO PRINCIPAL ★ — prompts da capa + de cada slide
    ↓ [aprova os prompts]
/gpt-image2-unity                ← gera todas as imagens (capa + slides)
    ↓ [aprova as imagens]
/carrossel-unity                 ← monta os HTMLs + renderiza PNG
    ↓ [aprova]
/legenda-para-carrossel
    ↓ [aprova o conteúdo final]
/publicar-social-unity           ← publicação
```

**Fluxo rápido (alternativa) — só quando o usuário pedir, ou para algo pontual sem controle granular de imagem:** `/carrossel-unity` cuida de tudo internamente (texto + prompt + imagem IA + HTML + PNG):
```
/carrossel-unity        ← texto + geração de imagem + HTML + PNG (tudo em um)
    ↓
/legenda-para-carrossel
```

> `/hooks-para-carrossel` é skill **auxiliar opcional** — usar só quando o usuário quiser explorar opções de capa antes. Não é etapa do fluxo principal.

**Origem das imagens — decisão do usuário, não é automática. SEMPRE oferecer 3 opções: IA, foto real (Drive) e mista.** A escolha é feita **ao final do `/briefing-unity`** (a skill pergunta e registra a resposta no `_briefing.md`/`_aprovado.md`). Nenhuma origem é default — as **três** são apresentadas lado a lado. Contexto da preferência: as imagens IA costumam integrar melhor à copy do post (composição pensada como peça única); as fotos do Drive entregam autenticidade de obra real; a mista combina as duas na mesma peça (ex.: capa IA + slides de obra real). Decidir caso a caso conforme o conteúdo.

- **Se a escolha for IA:** seguir o fluxo normal de prompts + `/gpt-image2-unity`.
- **Se a escolha for Drive:** buscar via MCP Drive (`search_files` com o ID da pasta em `_contexto/referencias.md`) e **curar criticamente** antes de usar (nunca a primeira; comparar; reprovar baixa qualidade — ver `.claude/memory/feedback_curadoria_fotos.md`); baixar com `download_file_content` só a(s) aprovada(s), converter HEIC → JPG, salvar como `img-slideXX.jpg` na pasta do carrossel.
- **Se a escolha for mista:** definir no briefing quais slides usam IA e quais usam foto real; produzir cada origem pelo seu fluxo (IA via prompts + `/gpt-image2-unity`; Drive via MCP + curadoria) e registrar o mapa slide→origem no `_aprovado.md`.
- **Fluxo rápido (sem briefing):** se o usuário começar direto pelo `/carrossel-unity` ou `/estatico-unity` sem origem registrada, a skill pergunta as 3 origens (IA / foto real / mista) antes de produzir.

---

#### Post estático

```
/gerador-de-prompts-para-imagens-de-produto   ← ou /gerador-de-prompts-de-imagem
    ↓ [aprova prompt]
/gpt-image2-unity                             ← gera foto de fundo
    ↓ [aprova imagem]
/estatico-unity                               ← monta HTML + renderiza PNG
    ↓
/legenda-para-post-estatico
```

---

#### Vídeo (Reels / TikTok)

```
/hooks-para-instagram-reels   ← hook do primeiro frame + frase de abertura
    ↓ [escolhe hook]
/roteiro-unity                ← roteiro completo (motor: ogilvy-copy ou schwartz-copy)
    ↓
/legenda-para-reel
```

---

### Etapa 3 — Distribuição (opcional)

```
/1-conteudo-em-7-formatos   ← transforma o conteúdo aprovado em 7 formatos diferentes
    ↓
/publicar-social-unity       ← publica no Instagram, TikTok, LinkedIn
```

---

### Fluxo alternativo — fundo de funil

```
/banco-de-objecoes-do-avatar      ← mapeia objeções por ICP
    ↓ [escolhe objeção]
/carrossel-de-quebra-de-objecao   ← carrossel em 3 movimentos: nomeação → reframe → prova
    ↓
/carrossel-unity  +  /legenda-para-carrossel
```

---

**Aprovação humana obrigatória** em cada etapa — o fluxo para e aguarda antes de avançar.

---

## Regras do sistema

- Antes de executar qualquer tarefa, verificar se existe uma skill relevante em `.claude/skills/`
- Se encontrar, seguir as instruções da skill
- Conteúdo da empresa: sempre manter o contexto definido em `_contexto/empresa.md`
- Arquivos de credenciais: nunca commitar (estão no .gitignore)

**REGRA OBRIGATÓRIA — CTA sempre definido pelo conteúdo.**

**Carrossel — usar SEMPRE um dos 5 modelos prontos de CTA como SLIDE FINAL** (pasta `CTA's/`, 1080×1350, **usados COMO ESTÃO, sem editar nada** — copiar o PNG como o último slide). NÃO montar mais o slide vermelho de CTA em HTML para carrossel. Escolher, a cada carrossel, o modelo cujo **assunto/mensagem melhor encaixa no tema** da peça (decisão por conteúdo, nunca por hábito, nunca por nome de arquivo):
> - `cta-branding.png` — institucional/autoridade/ecossistema ("a Fast ajudou a construir a evolução da construção" + mapa)
> - `cta-educativo.png` — educacional sobre Steel Frame/Drywall ("parceiro técnico → fale com especialista, WhatsApp")
> - `cta-educativo (2).png` — educacional de especificação técnica ("dúvida sobre especificação → fale com especialista")
> - `cta-franquia.png` — abastecimento/cobertura nacional/onde comprar ("comente sua cidade, unidade mais perto da obra" — pra quem executa)
> - `cta-franquia (2).png` — franquia/investimento ("disponibilidade da região, investimento, link na bio")

**Estático / reel / legenda** — CTA de **texto**, escolhido pelo conteúdo entre os 3 oficiais (fonte: `_contexto/estrategia.md`): **"Fale com um especialista"** (educacional/consideração) · **"Ver na loja"** (venda de produto) · **"Agende uma conversa estratégica"** (franquia).

Em qualquer caso: decidir conscientemente pelo conteúdo e justificar em uma linha; não repetir por inércia. Detalhe em [_contexto/preferencias.md](_contexto/preferencias.md).

---

## Fluxo de trabalho

Antes de executar qualquer tarefa, verificar se existe uma skill relevante em `.claude/skills/` ou `.claude/commands/`.
Se encontrar, seguir as instruções da skill.
Se não encontrar, executar a tarefa normalmente.

Ao concluir uma tarefa que não tinha skill mas parece repetível, perguntar:

> "Isso pode virar uma skill pra próxima vez. Quer que eu crie?"

Não perguntar pra tarefas pontuais ou perguntas simples. Só quando o padrão de repetição for claro.

---

## Aprender com correções

Quando o usuário corrigir algo ou dar instrução permanente ("na verdade é assim", "não faça mais isso", "sempre que...", "evita..."), perguntar:

> "Quer que eu salve isso pra não precisar repetir?"

Se sim, identificar onde salvar:

- **Sobre o negócio** → `_contexto/empresa.md`
- **Sobre preferências e estilo** → `_contexto/preferencias.md`
- **Sobre prioridades e foco atual** → `_contexto/estrategia.md`
- **Regra de comportamento nessa pasta** → `CLAUDE.md`

Salvar com uma linha nova clara, sem reformatar o arquivo inteiro.

---

## Criação de skills

Quando o usuário pedir pra criar uma nova skill:

1. Verificar se existe um template relevante em `templates/skills/`
2. Perguntar: "Essa skill é específica pra esse projeto ou vai ser útil em qualquer projeto?"
   - Específica desse negócio → `.claude/skills/nome-da-skill/SKILL.md` (local)
   - Útil em qualquer projeto → `~/.claude/skills/nome-da-skill/SKILL.md` (global)
3. Ler `_contexto/empresa.md` e `_contexto/preferencias.md` pra calibrar o conteúdo ao contexto
4. Se a skill precisar de arquivos de apoio, criar dentro da pasta da skill
