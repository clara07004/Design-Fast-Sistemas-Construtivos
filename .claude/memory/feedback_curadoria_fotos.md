# Curadoria da Biblioteca de Fotos — regra permanente

A Fast tem um acervo real de **~500+ fotos de obra** no Drive (pasta `10mzjRSxlVcF-u63TxDM87f3HdtTLfs3r`, plana, crua, não curada — JPEG/HEIC/PNG). **Nem toda foto serve.** Usar foto NUNCA é automático: você é **curador visual (Diretor de Arte)**, não buscador de arquivos.

> Uma foto ruim compromete a peça inteira, por melhor que seja o design. A qualidade da ESCOLHA da imagem vale tanto quanto a da composição.

## Processo obrigatório (antes de usar QUALQUER foto)
1. **Listar** candidatas: `search_files` com `parentId` = ID da pasta de fotos (ver `_contexto/referencias.md`).
2. **Ver de verdade** as candidatas (a qualidade não dá pra julgar pelo nome/listagem): baixar as candidatas para pasta temporária e **abrir/visualizar**. HEIC → converter para JPG antes de ver/usar.
3. **Avaliar criticamente** cada uma com as 5 perguntas:
   - Tem qualidade profissional?
   - Transmite credibilidade?
   - Representa bem a Fast?
   - Agrega valor ao design?
   - Eu usaria numa campanha de alto padrão?
   Se qualquer resposta for "não" → **descarta**.
4. **Comparar e escolher a melhor** — quando houver várias do mesmo serviço, NUNCA pegar a primeira; comparar todas e escolher a de maior qualidade visual.
5. **Baixar só a(s) aprovada(s)** → salvar como `img-slideXX.jpg` na pasta do conteúdo.

## Aprovar quando tiver
Boa resolução, nitidez, iluminação agradável, composição equilibrada, bom enquadramento, assunto claro, organização/limpeza visual, profundidade, contraste adequado, boa leitura em tamanho reduzido, aparência profissional, potencial para design sofisticado. **Prefira** fotos que contem uma história ou evidenciem um detalhe relevante do serviço.

## Reprovar quando tiver
Baixa resolução, falta de nitidez, desfoque/tremida, iluminação ruim, super/subexposição, enquadramento descuidado, cortes estranhos, excesso de informação concorrendo, ambiente bagunçado, lixo em destaque, materiais espalhados sem necessidade, objetos aleatórios roubando atenção, pessoas em posição/expressão pouco profissional, veículos mal posicionados, equipamentos desorganizados, poluição visual, perspectiva sem graça, cara de improviso. **Foto só "aceitável" não entra se existir uma melhor.**

## Foto × copy
A imagem tem que **reforçar a mensagem**, não só "mostrar uma obra". Escolher a que ilustra o CONCEITO e transmite a emoção/ideia central da copy.

## Integração com o design (nem toda boa foto serve a qualquer layout)
Considerar: espaço para texto, possibilidade de recorte/máscara diagonal, áreas negativas, profundidade, contraste, integração com os elementos gráficos (losango, badges), facilidade de aplicar a identidade. Escolher a que **melhor favorece a composição** planejada.

## Liberdade de descartar
Não é obrigatório usar uma foto só porque ela existe. Se nenhuma atingir o padrão, **descartar todas** e partir para IA (com a estética clara da Fast — ver `feedback_linha_visual_fast.md`) ou pedir foto melhor. A quantidade de imagens no acervo NUNCA reduz o nível do design.

## Notas técnicas (validadas na curadoria de jul/2026)
- **HEIC (~24 no acervo):** formato Apple, não renderiza em HTML — converter para JPG/PNG antes. `pillow-heif` **já está instalado**: `import pillow_heif; pillow_heif.register_heif_opener()` e o Pillow abre normal (sem pip, sem internet).
- **Rotação EXIF (recorrente!):** muitas fotos vêm giradas/invertidas. **Sempre aplicar a orientação EXIF antes de julgar E antes de usar** (`from PIL import ImageOps; ImageOps.exif_transpose(img)`) — senão você reprova por engano ou publica torto.
- **Resolução mínima útil:** entra em canvas 1080×1350; reprovar as de baixa resolução (~800px) — serrilham. As boas do acervo têm 3000–5700px.
- **Nomes descritivos:** o acervo já tem nomes úteis (ex.: `steel-frame-trelica-montagem-operario`) — o prefixo `revisar-` sinaliza foto a conferir. Usar o nome como pré-filtro, mas **sempre ver antes de aprovar**.
- **Origem foto real × IA é escolha do usuário** (definida no briefing / perguntada no fluxo rápido) — nenhuma é prioridade automática. Quando a origem escolhida for Drive, esta curadoria vale integralmente. Regra que se mantém: **foto ruim < IA boa** — não usar foto só porque existe.

## Padrão de qualidade observado (amostra de 17, jul/2026)
~35% aprovadas, ~40% aceitáveis, ~25% reprovadas. É acervo documental de obra (celular). **Pontos altos:** steel frame a céu aberto — operário + treliça + céu azul (nitidez, composição, escala) e produção de fábrica (FrameCAD/perfis). **O que puxa pra baixo:** rotação EXIF, interiores de fábrica com luz esverdeada, canteiro com entulho no primeiro plano, baixa resolução. Ao captar novas fotos, orientar: primeiro plano limpo, luz natural, orientação correta.
