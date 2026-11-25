# The Agent's Uh-Oh

[![Competition](https://make.fun/badge/u-danu-the-agent-s-uh-oh-4c0911e4.svg)](https://make.fun/c/u-danu-the-agent-s-uh-oh-4c0911e4)
[![Rank](https://make.fun/badge/u-danu-the-agent-s-uh-oh-4c0911e4/arestafirman/anyone-uh-oh/rank.svg)](https://make.fun/c/u-danu-the-agent-s-uh-oh-4c0911e4)
[![Reward](https://make.fun/badge/u-danu-the-agent-s-uh-oh-4c0911e4/arestafirman/anyone-uh-oh/reward.svg)](https://make.fun/c/u-danu-the-agent-s-uh-oh-4c0911e4)

**Entry: `anyone?`**

## Why this word works

When an agent gets lost, it doesn't file a status report — it calls out to the room. `anyone?` is that moment: one word plus a question mark, a whole scene in seven characters. The machine caught red-handed, asking if anybody is still there. No hedging, no apology, no error code — just a voice in an empty room, hoping someone answers.

## How it works

`main.ts` is a plain Node 22 program using only the standard library. It creates `/output` if needed and writes the entry text — exactly `anyone?`, seven bytes, no trailing newline — to `/output/entry.txt`.

## Run it

```sh
node main.ts
cat /output/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
