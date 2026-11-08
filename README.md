# TRADER

Skills de trading para o Claude Code.

## Instalado
- `.claude/skills/` — 74 skills de [tradermonty/claude-trading-skills](https://github.com/tradermonty/claude-trading-skills) (MIT, ver `vendor/LICENSE-claude-trading-skills`)
- `.claude/agents/` e `.claude/commands/` — agentes e comandos do mesmo projeto
- `trade`, `trade-*` — 16 skills de [zubair-trabzada/ai-trading-claude](https://github.com/zubair-trabzada/ai-trading-claude) (análise técnica, fundamentalista, sentimento, risco, opções, PDF)
- `trader-*` — 11 skills de [Jakeschincariol/day-trader-skill](https://github.com/Jakeschincariol/day-trader-skill) (day trade, dados grátis, paper trading por padrão)
- `vendor/workflows`, `vendor/skillsets` — roteiros prontos (rotina diária, revisão semanal etc.)

Comece pela skill `trading-skills-navigator` ou pelo workflow `market-regime-daily`.
Várias skills usam APIs (FMP, Alpaca, Finviz); as chaves vão em variáveis de ambiente.

Aviso: material educacional, não é recomendação de investimento.
