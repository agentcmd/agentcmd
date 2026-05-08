# agentcmd
Manage your AI agent configurations through code, structured configuration, and a CLI.

Agentcmd (Agent Command) enables you to configure & manage your AI agents like you would with code. Agent configurations live in structured JSON (or configuration-as-code), and are version-controlled. 
The `agentcmd` CLI allows you to create, publish, update & install agent configurations like you would with code. Configurations support all types of agentic concepts such as MCP, skills, context, steering files, SOPs, tool permissions, etc. 
Configurations are heirarchical, enabling you to sub-type agents from other agents. In addition to agents, `agentcmd` also allows for individually installing MCP configs, skills, and other AI capabilities. 

Supports [Claude Code](https://code.claude.com/docs/en/sub-agents) and [Kiro](https://kiro.dev/docs/cli/custom-agents/), and anything else through an extension interfacee.

Everything is local and non-priopriatary. Configuration is just code in github or whatever your choice of source control is. Use whatever AI vendor(s) you want. 
