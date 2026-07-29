# Logos da marca — Fast Sistemas Construtivos

Kit oficial (PNG com transparência) instalado em jul/2026. Todos com fundo transparente.

## Nomes usados pelo sistema (referenciados nos HTMLs de carrossel/estático)

| Arquivo | É cópia de | Uso |
|---|---|---|
| `logo-cor.png` | `fast-cor-horizontal.png` | **Primário** — sobre fundo claro/off-white (o padrão da Fast). Losango vermelho + "FAST" preto + "Sistemas Construtivos" vermelho |
| `logo-branco.png` | `fast-branco-horizontal.png` | Sobre painel/foto escura — versão toda branca (knockout) |
| `logo-simbolo.png` | `fast-simbolo-vermelho.png` | Símbolo isolado — avatar, favicon, marca d'água, ícone |

> **Regra de fundo (feed é CLARO):** o `logo-cor.png` é o mais usado, porque a linha visual da Fast é off-white claro. Use `logo-branco.png` só quando o logo cair sobre foto/painel escuro.

## Kit completo disponível (variações)

- `fast-cor-horizontal.png` / `fast-cor-vertical.png` — colorido (símbolo vermelho + texto preto/vermelho)
- `fast-branco-horizontal.png` / `fast-branco-vertical.png` — tudo branco (fundos escuros)
- `fast-cinza-vertical.png` — cinza (usos neutros/monocromáticos)
- `fast-simbolocor-textobranco-horizontal.png` / `-vertical.png` — símbolo colorido + "FAST" branco (foto/painel escuro mantendo o símbolo vermelho)
- `fast-simbolo-vermelho.png` — só o símbolo (losango "F/D")
- `fast-master-quadrado.jpg` — master 2000×2000 (referência, fundo sólido)

## Referência nos HTMLs
```html
<!-- Fundo claro (padrão Fast) -->
<img src="../../../../../marca/logos/logo-cor.png" style="height:48px;object-fit:contain;">

<!-- Sobre foto/painel escuro -->
<img src="../../../../../marca/logos/logo-branco.png" style="height:48px;object-fit:contain;">
```
Mínimo ~48px de altura no slide (o header usa 48px). Sempre preservar a área de respiro e nunca distorcer, recolorir fora da paleta ou aplicar efeitos (Manual de Marca).

> Os scripts `extrair-*.py` nesta pasta eram para extrair logo do PDF do Manual — ficaram obsoletos agora que o kit oficial está instalado.
