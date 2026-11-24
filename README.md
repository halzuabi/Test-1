# Test-1

Project-local install of the [Day Trader skill pack](https://github.com/Jakeschincariol/day-trader-skill) (MIT, by Jake Schincariol).

The 11 skills live in `.claude/skills/` and load automatically when Claude Code opens this repo:
`/trader-scanner`, `/trader-news`, `/trader-entry`, `/trader-exit`, `/trader-timemachine`,
`/trader-risk`, `/trader-budget`, `/trader-broker`, `/trader-alerts`, `/trader-analyst`, `/trader-pelosi`.

Requires Python 3.8+. SEC tools need `SEC_USER_AGENT` set (or `sec_user_agent` in `trader/config.json`).
Paper trading is the default; nothing places an order without your explicit yes. Not financial advice.
