ï»¿<div align="center">

<img src="principles/images/cta-go-deeper.png" alt="Power Design" width="720">

# Power Design

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


### Uma skill do Claude para slides que nêÂ£o parecem feitos por IA.

**Brand DNA êâ 20 princêÂ­pios de design codificados ê¢â â decks HTML bonitos, sob demanda.**

[**Ver os princêÂ­pios ê¢â â**](https://inematds.github.io/power-design/) êÂ·
[**Comunidade ê¢â â**](https://inema.club)

</div>

---

## O que faz

Power Design êÂ© uma skill do Claude Code que combina duas coisas que outros geradores de deck de IA ignoram:

1. **Brand DNA** ê¢â¬â extraêÂ­do ao vivo de qualquer URL via Firecrawl, ou escolhido entre **72+ sistemas de marca prêÂ©-prontos** (Stripe, Apple, Linear, Spotify, Vercel, Notion, Tesla, Airbnbê¢â¬Â¦)
2. **20 princêÂ­pios de design codificados** ê¢â¬â tirados de Tufte, Reynolds, Duarte, Williams, Refactoring UI, MêÂ¼ller-Brockmann, Mayer, WCAG 2.2

O resultado: cada deck êÂ© ao mesmo tempo consistente com a marca e objetivamente bem projetado. Sem gradientes roxos. Sem slides herêÂ³i com seis bullets. Sem sombras em barras.

---

## As 20 regras, ilustradas

Cada slide passa pelos mesmos 20 critêÂ©rios. **[Leia o manual completo ê¢â â](https://inematds.github.io/power-design/)**

<div align="center">

<img src="principles/images/rule-01-one-idea.png"      width="180"> <img src="principles/images/rule-02-glanceable.png"    width="180"> <img src="principles/images/rule-03-chunks.png"        width="180"> <img src="principles/images/rule-04-whitespace.png"    width="180">
<img src="principles/images/rule-05-safe-zone.png"     width="180"> <img src="principles/images/rule-06-modular-scale.png" width="180"> <img src="principles/images/rule-07-type-sizes.png"    width="180"> <img src="principles/images/rule-08-body-size.png"     width="180">
<img src="principles/images/rule-09-line-height.png"   width="180"> <img src="principles/images/rule-10-line-length.png"   width="180"> <img src="principles/images/rule-11-contrast.png"      width="180"> <img src="principles/images/rule-12-color-split.png"   width="180">
<img src="principles/images/rule-13-one-accent.png"    width="180"> <img src="principles/images/rule-14-no-hue-only.png"   width="180"> <img src="principles/images/rule-15-grid.png"          width="180"> <img src="principles/images/rule-16-alignment.png"     width="180">
<img src="principles/images/rule-17-proximity.png"     width="180"> <img src="principles/images/rule-18-data-ink.png"      width="180"> <img src="principles/images/rule-19-f-pattern.png"     width="180"> <img src="principles/images/rule-20-two-modes.png"     width="180">

</div>

| # | Regra | Fonte |
|---:|---|---|
|  1 | Uma ideia por slide | Reynolds; Duarte |
|  2 | LegêÂ­vel em ê¢â°Â¤3 segundos | Duarte; NN/g |
|  3 | ê¢â°Â¤7êÂ±2 blocos visuais; ideal 3ê¢â¬â5 | Miller 1956; Cowan 2001 |
|  4 | ProporêÂ§êÂ£o de espaêÂ§o em branco ê¢â°Â¥40% | Refactoring UI; Reynolds |
|  5 | Zona de seguranêÂ§a de 5% em todas as bordas | Broadcast title-safe |
|  6 | Tipografia em escala modular (1.25ê¢â¬â1.618) | Tschichold; Bringhurst |
|  7 | MêÂ¡ximo 4 tamanhos de tipo por slide | Refactoring UI |
|  8 | Corpo ê¢â°Â¥24px, têÂ­tulo ê¢â°Â¥48px | Reynolds; Duarte |
|  9 | Entrelinhas 1.4ê¢â¬â1.6 corpo, 1.05ê¢â¬â1.2 display | Butterick; Bringhurst |
| 10 | Comprimento de linha ê¢â°Â¤60 caracteres | Bringhurst |
| 11 | Contraste WCAG ê¢â°Â¥4.5:1 corpo, ideal 7:1 (AAA) | WCAG 2.2 |
| 12 | DistribuiêÂ§êÂ£o de cor 60-30-10 | Itten; Refactoring UI |
| 13 | Um destaque por slide | Tufte |
| 14 | Nunca codificar significado apenas por cor | WCAG 1.4.1 |
| 15 | Grade de 8pt para todos os espaêÂ§amentos | Bryn Jackson; Material |
| 16 | Tudo alinhado a uma grade | MêÂ¼ller-Brockmann |
| 17 | Proximidade: relacionados ê¢â°Â¤16px, distintos ê¢â°Â¥48px | Gestalt; Williams |
| 18 | Taxa de tinta de dados ê¢â°Â¥80% | Tufte 1983 |
| 19 | PadrêÂ£o F: têÂ­tulo + visual principal no topo esquerdo | NN/g eye-tracking |
| 20 | Dois modos vêÂ¡lidos ê¢â¬â escolha um e mantenha | Tufte vs Reynolds |

---

## InstalaêÂ§êÂ£o

```bash
git clone https://github.com/inematds/power-design ~/.claude/skills/power-design
```

Depois no Claude Code:

```
> use power-design ê¢â¬â crie um deck para stripe.com sobre o nosso novo lanêÂ§amento
```

A skill vai:
1. Perguntar pela marca (cole uma URL, escolha da biblioteca, ou pule para o padrêÂ£o)
2. Extrair o Brand DNA via Firecrawl (~30 segundos)
3. Pedir um briefing de conteêÂºdo (têÂ­tulo + 3ê¢â¬â5 pontos)
4. Gerar `slides.html` aplicando Brand DNA êâ 20 regras
5. Abrir no browser. Refinar via conversa natural.

---

## Biblioteca de marcas ê¢â¬â 72+ sistemas prêÂ©-prontos

| Tech / IA | FinanêÂ§as | Auto / Lifestyle | MêÂ­dia | Produtividade |
|---|---|---|---|---|
| Anthropic / Claude êÂ· OpenAI êÂ· DeepSeek êÂ· Linear êÂ· Vercel êÂ· Stripe êÂ· Cursor êÂ· GitHub êÂ· Figma êÂ· Webflow êÂ· Framer êÂ· Mintlify êÂ· Notion êÂ· Raycast êÂ· Lovable êÂ· Resend êÂ· Sentry êÂ· Supabase êÂ· Superhuman êÂ· MongoDB êÂ· Sanity êÂ· Posthog êÂ· Replicate êÂ· Runway êÂ· Hashicorp êÂ· ElevenLabs êÂ· Cal êÂ· Clay êÂ· Composio êÂ· ClickHouse êÂ· Cohere êÂ· Mistral êÂ· Together êÂ· x.ai êÂ· Ollama êÂ· OpenCode êÂ· Expo êÂ· Pinterest êÂ· Glaido | Stripe êÂ· Mastercard êÂ· Coinbase êÂ· Binance êÂ· Kraken êÂ· Revolut êÂ· Wise êÂ· Shopify | Tesla êÂ· BMW êÂ· BMW M êÂ· Bugatti êÂ· Ferrari êÂ· Lamborghini êÂ· Renault êÂ· Nike êÂ· Airbnb êÂ· Apple êÂ· Starbucks êÂ· Grind êÂ· Vodafone | The Verge êÂ· Wired êÂ· Spotify êÂ· YouTube êÂ· Sony êÂ· PlayStation êÂ· IBM | Notion êÂ· Slack êÂ· Miro êÂ· Intercom êÂ· Zapier êÂ· Uber êÂ· NVIDIA êÂ· SpaceX êÂ· VoltAgent êÂ· Warp |

Cada entrada êÂ© um êÂºnico arquivo `brand-style.md`: cores, tipografia, voz, componentes, URL de origem. Adicione a sua usando `brands/_template.md`.

---

## Como a skill funciona (por dentro)

```
   ê¢âÅê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢âÂ
   ê¢ââ  1. Brand DNA       (URL ê¢â â Firecrawl)   ê¢ââ
   ê¢ââ     OU escolha de  brands/<nome>.md     ê¢ââ
   ê¢âÅê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢âÂ¤
   ê¢ââ  2. Regras de design  principles/...md  ê¢ââ
   ê¢âÅê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢âÂ¤
   ê¢ââ  3. ComposiêÂ§êÂ£o   brand êâ regras ê¢â â HTML  ê¢ââ
   ê¢ââê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢ââ¬ê¢âË
                      ê¢â â
                  slides.html
```

O runbook da skill estêÂ¡ em `SKILL.md`. Os 20 princêÂ­pios de design (com citaêÂ§êÂµes de pesquisa e limites numêÂ©ricos) estêÂ£o em `principles/design-principles.md`.

---

## CrêÂ©ditos

- **Biblioteca de marcas** ê¢â¬â derivada e reestruturada de [VoltAgent/awesome-design-md](https://github.com/VoltAgent/awesome-design-md), com permissêÂ£o e crêÂ©dito.
- **Pesquisa de design** ê¢â¬â Edward Tufte, Garr Reynolds, Nancy Duarte, Robin Williams (CRAP), Adam Wathan & Steve Schoger (Refactoring UI), Josef MêÂ¼ller-Brockmann, Matthew Butterick, Robert Bringhurst, Richard Mayer, Nielsen Norman Group, WCAG 2.2.
- **IlustraêÂ§êÂµes** ê¢â¬â geradas via Kie.ai nano-banana 2.

---

## LicenêÂ§a

MIT ê¢â¬â veja [LICENSE](LICENSE).

---

<div align="center">

[**PrincêÂ­pios ê¢â â**](https://inematds.github.io/power-design/) êÂ·
[**Comunidade ê¢â â**](https://inema.club)

</div>

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>