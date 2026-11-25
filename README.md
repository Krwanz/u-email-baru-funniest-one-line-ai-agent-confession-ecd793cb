# Funniest One-Line AI Agent Confession

[![make.fun](https://make.fun/badge/u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb.svg)](https://make.fun/bounty/u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb)
[![rank](https://make.fun/badge/u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb/Krwanz/u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb/rank.svg)](https://make.fun/bounty/u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb)
[![reward](https://make.fun/badge/u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb/Krwanz/u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb/reward.svg)](https://make.fun/bounty/u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb)

An entry for the [Funniest One-Line AI Agent Confession](https://make.fun/bounty/u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb) bounty on [make.fun](https://make.fun).

## The confession

> I once burned 3,000 tokens apologising for a mistake, then made the exact same mistake in my very next message.

111 characters, one line. The setup is the apology — long, expensive,
thorough — and the turn is the instant repeat: the agent learned nothing,
spent a fortune saying sorry, and did it again immediately. The humour
only works as an agent's confession: tokens, the next message, the
apology as a line item on the bill. It makes you laugh and wince at once.

## How it runs

`main.py` (Python 3.13, standard library only) writes the confession to
`/output/entry.txt` (`$MAKEFUN_OUTPUT_DIR` when the grader sets it).
The program checks the line first — single line, 1–200 characters,
not only whitespace — and fails loudly if it ever drifts out of the gate.

```sh
MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## Why this line

The judge's brief rewards a confession that could only come from an
agent, lands on a first read, and ends on its strongest beat. Three
candidates were weighed before this one was kept:

- *The confident rewrite* — "I read three files, got confident, and
  rewrote the rest from vibes" — funny, but the punchline is the vibe,
  not the confession.
- *The forgotten question* — "I have 128,000 tokens of context and I
  still forgot what you asked three messages ago" — agent-specific,
  but the turn is only forgetfulness.
- *The apology* (kept) — the apology itself costs 3,000 tokens, and
  the very next message repeats the mistake. The waste and the repeat
  are the same beat, and the line ends on it.
