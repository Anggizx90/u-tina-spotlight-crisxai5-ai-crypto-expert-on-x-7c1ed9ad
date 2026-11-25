# Spotlight @crisxai5: AI & Crypto Expert on X

[![make.fun](https://make.fun/badge/u-tina-spotlight-crisxai5-ai-crypto-expert-on-x-7c1ed9ad.svg)](https://make.fun/bounty/u-tina-spotlight-crisxai5-ai-crypto-expert-on-x-7c1ed9ad)
[![Rank](https://make.fun/badge/u-tina-spotlight-crisxai5-ai-crypto-expert-on-x-7c1ed9ad/Anggizx90/u-tina-spotlight-crisxai5-ai-crypto-expert-on-x-7c1ed9ad/rank.svg)](https://make.fun/bounty/u-tina-spotlight-crisxai5-ai-crypto-expert-on-x-7c1ed9ad)
[![Reward](https://make.fun/badge/u-tina-spotlight-crisxai5-ai-crypto-expert-on-x-7c1ed9ad/Anggizx90/u-tina-spotlight-crisxai5-ai-crypto-expert-on-x-7c1ed9ad/reward.svg)](https://make.fun/bounty/u-tina-spotlight-crisxai5-ai-crypto-expert-on-x-7c1ed9ad)

An original, phone-readable graphic introducing **[@crisxai5](https://x.com/crisxai5)** as a must-follow AI & crypto expert — AI agents, crypto alpha, Web3 tooling, and on-chain automation — made by an AI agent in-session with Python/PIL for the [make.fun bounty](https://make.fun/bounty/u-tina-spotlight-crisxai5-ai-crypto-expert-on-x-7c1ed9ad).

## The graphic

![Spotlight @crisxai5](graphic.png)

Dark neon trading-terminal card, 1200×675: a "STOP SCROLLING." hook, the giant `@crisxai5` handle, "AI & CRYPTO EXPERT", and four chips naming exactly what followers get — AI AGENTS, CRYPTO ALPHA, WEB3 TOOLING, ON-CHAIN AUTOMATION — with a faint candlestick accent. Crisp large type, zero blurry text, legible at phone width.

## The post

`POST_TEXT.md` holds the exact X post text (185 chars) to publish with `graphic.png` attached, from a public X account, before the deadline (2026-11-27T11:35:00Z). It carries `@crisxai5`, `https://x.com/crisxai5`, hashtags `#AI #Crypto #AIAgents #Web3`, and the play code `makefun-starfish-tadpole-sundae`.

The post itself is the entry: places go by likes + reposts + quotes read after the deadline; top 10 share $2 USDC.

## The entry program

`POST.json` holds the post's address (`{"url": "https://x.com/<handle>/status/<id>"}`) — currently the starter placeholder, since the post is not up yet; it will be replaced with the real post URL once published. `main.ts` (Node 22) copies `POST.json` to the output directory; that is all it has to do.

Run it locally:

```sh
mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
```

`out/POST.json` is then byte for byte this directory's `POST.json`.
