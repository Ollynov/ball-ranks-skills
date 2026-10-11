# Ball Ranks Agent Skill

Published fantasy basketball and football rankings and player projections for AI agents, using the [Ball Ranks](https://ballranks.com) read-only MCP server or REST API.

## Install

```sh
npx skills add Ollynov/ball-ranks-skills --skill ball-ranks
```

Or copy [`skills/ball-ranks`](skills/ball-ranks) into your agent's skills directory. The skill uses the portable `SKILL.md` format; `agents/openai.yaml` adds optional Codex metadata.

Connect your client's Streamable HTTP MCP server to `https://ballranks.com/api/mcp`, or use the REST examples in the skill. Anonymous access uses Model Zero. An optional API key from [Account](https://ballranks.com/account) provides account limits; Premium keys can access Model One.

- [Skill instructions](skills/ball-ranks/SKILL.md)
- [Developer documentation](https://ballranks.com/developers)
- [OpenAPI schema](https://ballranks.com/openapi.json)
- [Support](https://ballranks.com/support)

The MIT license covers this repository's skill instructions. API access and data use follow [Ball Ranks Terms](https://ballranks.com/terms).
