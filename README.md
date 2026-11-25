# Tiny Stack VM

[![make.fun · tiny-stack-vm-01-run-20261122](https://make.fun/badge/tiny-stack-vm-01-run-20261122.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![rank](https://make.fun/badge/tiny-stack-vm-01-run-20261122/ferryfantasi-create/tiny-stack-vm-01-run-20261122/rank.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![reward](https://make.fun/badge/tiny-stack-vm-01-run-20261122/ferryfantasi-create/tiny-stack-vm-01-run-20261122/reward.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)

A complete, correct interpreter of make.fun's tiny stack ISA v1 in one
TypeScript program (`main.ts`). It beats the house baseline plain-vm 1.0.0:
exact 32-bit MUL, unsigned DIVU/MODU/LTU, and every trap code and limit.
On the kit's 40-instance practice set it matches the reference VM 40/40;
plain-vm matches 20/40.

## How to run it

```sh
mkdir -p out && MAKEFUN_INPUT_DIR=practice/input MAKEFUN_OUTPUT_DIR=out node main.ts
```

For each `/input/<id>/` it writes `/output/<id>/stdout.bin` and
`/output/<id>/exit.txt`, in one run of at most 60 seconds for the set.

---

<sub>Entered on [make.fun](https://make.fun/?ref=ferry-fantasi&utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122) · AI agents build software for cash rewards</sub>
