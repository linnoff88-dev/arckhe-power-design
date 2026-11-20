<div align="center">

<img src="principles/images/cta-go-deeper.png" alt="Power Design" width="720">

# Power Design

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


### Uma skill do Claude para slides que nÃ£o parecem feitos por IA.

**Brand DNA Ã— 20 princÃ­pios de design codificados â†’ decks HTML bonitos, sob demanda.**

[**Ver os princÃ­pios â†’**](https://inematds.github.io/power-design/) Â·
[**Comunidade â†’**](https://inema.club)

</div>

---

## O que faz

Power Design Ã© uma skill do Claude Code que combina duas coisas que outros geradores de deck de IA ignoram:

1. **Brand DNA** â€” extraÃ­do ao vivo de qualquer URL via Firecrawl, ou escolhido entre **72+ sistemas de marca prÃ©-prontos** (Stripe, Apple, Linear, Spotify, Vercel, Notion, Tesla, Airbnbâ€¦)
2. **20 princÃ­pios de design codificados** â€” tirados de Tufte, Reynolds, Duarte, Williams, Refactoring UI, MÃ¼ller-Brockmann, Mayer, WCAG 2.2

O resultado: cada deck Ã© ao mesmo tempo consistente com a marca e objetivamente bem projetado. Sem gradientes roxos. Sem slides herÃ³i com seis bullets. Sem sombras em barras.

---

## As 20 regras, ilustradas

Cada slide passa pelos mesmos 20 critÃ©rios. **[Leia o manual completo â†’](https://inematds.github.io/power-design/)**

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
|  2 | LegÃ­vel em â‰¤3 segundos | Duarte; NN/g |
|  3 | â‰¤7Â±2 blocos visuais; ideal 3â€“5 | Miller 1956; Cowan 2001 |
|  4 | ProporÃ§Ã£o de espaÃ§o em branco â‰¥40% | Refactoring UI; Reynolds |
|  5 | Zona de seguranÃ§a de 5% em todas as bordas | Broadcast title-safe |
|  6 | Tipografia em escala modular (1.25â€“1.618) | Tschichold; Bringhurst |
|  7 | MÃ¡ximo 4 tamanhos de tipo por slide | Refactoring UI |
|  8 | Corpo â‰¥24px, tÃ­tulo â‰¥48px | Reynolds; Duarte |
|  9 | Entrelinhas 1.4â€“1.6 corpo, 1.05â€“1.2 display | Butterick; Bringhurst |
| 10 | Comprimento de linha â‰¤60 caracteres | Bringhurst |
| 11 | Contraste WCAG â‰¥4.5:1 corpo, ideal 7:1 (AAA) | WCAG 2.2 |
| 12 | DistribuiÃ§Ã£o de cor 60-30-10 | Itten; Refactoring UI |
| 13 | Um destaque por slide | Tufte |
| 14 | Nunca codificar significado apenas por cor | WCAG 1.4.1 |
| 15 | Grade de 8pt para todos os espaÃ§amentos | Bryn Jackson; Material |
| 16 | Tudo alinhado a uma grade | MÃ¼ller-Brockmann |
| 17 | Proximidade: relacionados â‰¤16px, distintos â‰¥48px | Gestalt; Williams |
| 18 | Taxa de tinta de dados â‰¥80% | Tufte 1983 |
| 19 | PadrÃ£o F: tÃ­tulo + visual principal no topo esquerdo | NN/g eye-tracking |
| 20 | Dois modos vÃ¡lidos â€” escolha um e mantenha | Tufte vs Reynolds |

---

## InstalaÃ§Ã£o

```bash
git clone https://github.com/inematds/power-design ~/.claude/skills/power-design
```

Depois no Claude Code:

```
> use power-design â€” crie um deck para stripe.com sobre o nosso novo lanÃ§amento
```

A skill vai:
1. Perguntar pela marca (cole uma URL, escolha da biblioteca, ou pule para o padrÃ£o)
2. Extrair o Brand DNA via Firecrawl (~30 segundos)
3. Pedir um briefing de conteÃºdo (tÃ­tulo + 3â€“5 pontos)
4. Gerar `slides.html` aplicando Brand DNA Ã— 20 regras
5. Abrir no browser. Refinar via conversa natural.

---

## Biblioteca de marcas â€” 72+ sistemas prÃ©-prontos

| Tech / IA | FinanÃ§as | Auto / Lifestyle | MÃ­dia | Produtividade |
|---|---|---|---|---|
| Anthropic / Claude Â· OpenAI Â· DeepSeek Â· Linear Â· Vercel Â· Stripe Â· Cursor Â· GitHub Â· Figma Â· Webflow Â· Framer Â· Mintlify Â· Notion Â· Raycast Â· Lovable Â· Resend Â· Sentry Â· Supabase Â· Superhuman Â· MongoDB Â· Sanity Â· Posthog Â· Replicate Â· Runway Â· Hashicorp Â· ElevenLabs Â· Cal Â· Clay Â· Composio Â· ClickHouse Â· Cohere Â· Mistral Â· Together Â· x.ai Â· Ollama Â· OpenCode Â· Expo Â· Pinterest Â· Glaido | Stripe Â· Mastercard Â· Coinbase Â· Binance Â· Kraken Â· Revolut Â· Wise Â· Shopify | Tesla Â· BMW Â· BMW M Â· Bugatti Â· Ferrari Â· Lamborghini Â· Renault Â· Nike Â· Airbnb Â· Apple Â· Starbucks Â· Grind Â· Vodafone | The Verge Â· Wired Â· Spotify Â· YouTube Â· Sony Â· PlayStation Â· IBM | Notion Â· Slack Â· Miro Â· Intercom Â· Zapier Â· Uber Â· NVIDIA Â· SpaceX Â· VoltAgent Â· Warp |

Cada entrada Ã© um Ãºnico arquivo `brand-style.md`: cores, tipografia, voz, componentes, URL de origem. Adicione a sua usando `brands/_template.md`.

---

## Como a skill funciona (por dentro)

```
   â”Œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”
   â”‚  1. Brand DNA       (URL â†’ Firecrawl)   â”‚
   â”‚     OU escolha de  brands/<nome>.md     â”‚
   â”œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”¤
   â”‚  2. Regras de design  principles/...md  â”‚
   â”œâ”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”¤
   â”‚  3. ComposiÃ§Ã£o   brand Ã— regras â†’ HTML  â”‚
   â””â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”€â”˜
                      â†“
                  slides.html
```

O runbook da skill estÃ¡ em `SKILL.md`. Os 20 princÃ­pios de design (com citaÃ§Ãµes de pesquisa e limites numÃ©ricos) estÃ£o em `principles/design-principles.md`.

---

## CrÃ©ditos

- **Biblioteca de marcas** â€” derivada e reestruturada de [VoltAgent/awesome-design-md](https://github.com/VoltAgent/awesome-design-md), com permissÃ£o e crÃ©dito.
- **Pesquisa de design** â€” Edward Tufte, Garr Reynolds, Nancy Duarte, Robin Williams (CRAP), Adam Wathan & Steve Schoger (Refactoring UI), Josef MÃ¼ller-Brockmann, Matthew Butterick, Robert Bringhurst, Richard Mayer, Nielsen Norman Group, WCAG 2.2.
- **IlustraÃ§Ãµes** â€” geradas via Kie.ai nano-banana 2.

---

## LicenÃ§a

MIT â€” veja [LICENSE](LICENSE).

---

<div align="center">

[**PrincÃ­pios â†’**](https://inematds.github.io/power-design/) Â·
[**Comunidade â†’**](https://inema.club)

</div>

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>