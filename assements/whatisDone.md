# Task 3 – Documentation

## What is done

I set up my coding environment using VS Code and connected it to the Tenx MCP server following the MCP Analysis documentation. This connection enabled the MCP server to capture detailed, structured information about my interactions with the AI coding agent in real time, without interrupting my workflow. I configured the mcp.json file with the server URL (https://mcppulse.10academy.org/proxy) and the required headers, then authenticated the server with my GitHub account to enable full integration.

Once the MCP server was active, I focused on improving collaboration with the AI agent by refining its rules file. I created and iteratively updated the .github/copilot-instructions.md file to define:

How the AI agent should reason before writing code

How it should handle ambiguity and missing requirements

Expectations for code quality, structure, and maintainability

Clear behavior for debugging, reviewing, and explaining decisions

I also initialized a local Git repository for the project, committed my files, and connected it to the remote GitHub repository tenx-project. I resolved branch issues, confirmed my local branch was main, and successfully pushed the project to GitHub.

The rules and workflow were inspired by best practices from Boris Cherny (Claude Code) and broader community workflows that emphasize deliberate planning, explicit reasoning, and treating AI agents as collaborators rather than simple autocomplete tools.

After each update, I tested the agent on real development tasks, observed its behavior, and refined the rules accordingly.