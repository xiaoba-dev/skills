# skills

Public AI-agent skills by [xiaoba-dev](https://clawhub.ai/user/xiaoba-dev). Each folder under `skills/` is a byte-for-byte copy of what is published on [ClawHub](https://clawhub.ai) — this repo is the readable mirror, ClawHub is where releases happen.

| Skill | What it does | Registry | Version |
|---|---|---|---|
| [`solo-os`](skills/solo-os) | Expert-roundtable decision framework | [ClawHub](https://clawhub.ai/xiaoba-dev/solo-os) | 2.2.1 |
| [`adversarial-debate`](skills/adversarial-debate) | Cross-vendor adversarial review. | [ClawHub](https://clawhub.ai/xiaoba-dev/adversarial-debate) | 2.4.3 |
| [`foreman`](skills/foreman) | Dispatch-and-acceptance control desk for farming coding work out to background agents. | [ClawHub](https://clawhub.ai/xiaoba-dev/foreman) | 2.0.3 |
| [`distill`](skills/distill) | Session knowledge distillation | [ClawHub](https://clawhub.ai/xiaoba-dev/distill) | 2.0.2 |
| [`doc-governance`](skills/doc-governance) | Installs a documentation governance architecture in a project and diagnoses what it is missing. | [ClawHub](https://clawhub.ai/xiaoba-dev/doc-governance) | 2.0.10 |

## Install

```bash
npx clawhub install @xiaoba-dev/solo-os
```

Swap in any slug from the table. Each skill is a plain `SKILL.md` (plus helper files for some), so it also works if you copy the folder into your agent's skills directory by hand.

## How this repo is kept in sync

Every ClawHub release is followed by a copy here: the folder is reinstalled from ClawHub and committed, so the two never drift. Issues and suggestions are welcome; changes land through a new ClawHub release, then show up here.

## License

[MIT-0](LICENSE) — free to use, modify and redistribute, no attribution required (the same license ClawHub publishes them under).

---

**中文**：这里是 xiaoba-dev 在 ClawHub 上公开的 skill 的原样副本，每发一次 ClawHub 就同步一次。用 `npx clawhub install @xiaoba-dev/<名字>` 安装。欢迎提 issue。
