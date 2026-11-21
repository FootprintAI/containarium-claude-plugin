# Containarium plugin marketplace

A Claude Code plugin that teaches an agent to get an isolated remote Linux
box on [Containarium Cloud](https://containarium.dev): it pairs with you
once (you approve and add a card on Stripe, never in chat), then runs or
tests code off your machine.

Works with Claude Code. Not affiliated with or endorsed by Anthropic.

```
claude plugin marketplace add FootprintAI/containarium-claude-plugin
claude plugin install containarium-cloud@containarium
```

Pairing is rolling out to pilot accounts; the skill falls back to the
self-hosted path if it is refused. Price and allowance:
https://containarium.dev/pricing. Agent-readable summary:
https://containarium.dev/llms.txt

License: Apache-2.0.
