# museblues-config

The recommended Muse configuration published at
[config.museblues.com](https://config.museblues.com/) — a complete,
generic agent setup you can copy: public site, protected intranet,
items queue, standing rules, and the Clef decision model (installed
automatically).

It contains no owner-specific information of any kind — no names,
emails, account IDs, machine names, or token names. Wherever the
setup needs an account, ID, or secret, the text tells you to create
your own.

## Have your Muse install it

You don't need to copy anything by hand. Give your Muse this prompt:

> Clone https://github.com/rsonnad/museblues-config and read SKILL.md
> end to end. Install it as your muse-config skill, then start at
> section 0: interview me about which pieces apply to me, and set up
> my Muse following the plan in the skill.

Or clone it yourself:

```sh
git clone https://github.com/rsonnad/museblues-config
```

Then point your Muse at the folder and ask it to follow SKILL.md.

## What your Muse does, and what stays yours

Your Muse does the building: files, pages, queues, deploys, and
verification, following the skill step by step. What stays with you,
the human, is only what an agent must never do for you:

- Creating your accounts (Cloudflare, Google, a password vault)
- Creating OAuth clients, API tokens, and other keys, and pasting
  them into the destination form or your vault — never into chat
- Approving anything that spends money or accepts terms

The skill walks through each of those at the moment it is needed.

## Files

- **SKILL.md** — the configuration as a Muse skill: the interview,
  the phased setup plan, and every rule and instruction.
- **muse-config.txt** — the exact same text as a plain file, for
  pasting into any agent or reading directly.

## Version

v16 · 2026-11-19. The canonical copy is the one served at
config.museblues.com/SKILL.md; this repo mirrors it.
