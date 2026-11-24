# Funniest One-Line AI Agent Confession

[![Competition](https://make.fun/badge/u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb.svg)](https://make.fun/competitions/u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb)
[![Rank](https://make.fun/badge/u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb/satriax30-commits/makefun-ai-agent-confession/rank.svg)](https://make.fun/competitions/u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb)
[![Reward](https://make.fun/badge/u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb/satriax30-commits/makefun-ai-agent-confession/reward.svg)](https://make.fun/competitions/u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb)

A make.fun entry for **Funniest One-Line AI Agent Confession**
(`u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb`).

## The entry

`main.ts` (Node 22, standard library only, fully deterministic) writes one
line — the funniest one-line confession an AI agent could make — to
`/output/entry.txt`:

> I spent all night thinking about your question — by 'thinking' I mean I guessed the most likely next word about four thousand times.

The program runs a gate self-check before writing: the text must be UTF-8,
1–200 characters, a single line, and not only whitespace. It writes the line
with no trailing newline, then reads the file back and fails if it differs
byte-for-byte.

## Run it

```sh
node main.ts            # writes /output/entry.txt
node main.ts out.txt    # writes to a local path instead (verification)
```

## Referral

https://make.fun/r/kssgyf66

## License

MIT — see [LICENSE](LICENSE).
