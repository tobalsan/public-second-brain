# Resources on AI and LLMs

## Prompts and System Instructions

- [Optimizing Coding Agent Rules (CLAUDE.md, agents.md, ./clinerulesm .cursor/rules) for Improved Accuracy - Arize AI](https://arize.com/blog/optimizing-coding-agent-rules-claude-md-agents-md-clinerules-cursor-rules-for-improved-accuracy/)
- [microsoft/agent-lightning: The absolute trainer to light up AI agents.](https://github.com/microsoft/agent-lightning) - Train your agents without the overhead of a classic full SFT/RL setup

## Memory
- [AgentDB - Ultra-Fast Vector Database for AI Agents | AgentDB](https://agentdb.ruv.io/) - Instant memory. Local learning.  Global coordination. A sub-millisecond memory engine built for autonomous agents with 29 MCP tools for seamless AI integration.
	- I think it would be very interesting to set up an agent with this and give it my personal "therapy" conversations I had with LLMs.

## Coding Agents Tooling
- [numman-ali/openskills: Universal skills loader for AI coding agents - npm i -g openskills](https://github.com/numman-ali/openskills) - Super cool, use Claude skills but with any coding agent.
- [cased/kit: The toolkit for AI devtools context engineering. Build with codebase mapping, symbol extraction, and many kinds of code search.](https://github.com/cased/kit) - Looks like a solid alternative to using AST-grep + Repomix or Gitingest to get an agent to know your codebase.
- [automazeio/vibeproxy: Native macOS menu bar app to use your Claude Code & ChatGPT subscriptions with AI coding tools - no API keys needed](https://github.com/automazeio/vibeproxy/tree/main?tab=readme-ov-file) - Useful app to proxy your existing subscriptions (Claude Max, ChatGPT) with CLI coding agents e.g. Factory Droid.
- [mrgoonie/claudekit-skills: All powerful skills of ClaudeKit.cc!](https://github.com/mrgoonie/claudekit-skills?tab=readme-ov-file) - This repo is a great source of inspiration for Claude Skills.

## Browser Control
- [remorses/playwriter: The better playwright MCP: works as a browser extension. No context bloat. More capable.](https://github.com/remorses/playwriter): Like Playwright MCP but via a Chrome extension. 90% less context window. 10x more capable (full playwright API).
- [SawyerHood/dev-browser: A Claude Skill to give your agent the ability to use a web browser](https://github.com/SawyerHood/dev-browser): Kind of a mix between full Claude Skill and the Playwright MCP. Fast execution while saving tokens.
- [hangwin/mcp-chrome: Chrome MCP Server](https://github.com/hangwin/mcp-chrome): Install the Chrome extension and it acts as an MCP server that your coding agent can connect to, so you can use it with your own sessions.

## Testing and Evals
- [Building an LLM-as-a-Judge System for AI (Customer Support) Agent - Portkey Docs](https://portkey.ai/docs/guides/prompts/llm-as-a-judge) - An A-to-Z guide on implementing LLM-as-a-Judge while leveraging Portkey's Prompt Engineering features.
- [Your AI Product Needs Evals – Hamel's Blog - Hamel Husain](https://hamel.dev/blog/posts/evals/#level-1-unit-tests)
- [Using LLM-as-a-Judge For Evaluation: A Complete Guide – Hamel's Blog - Hamel Husain](https://hamel.dev/blog/posts/llm-judge/#step-5-build-your-llm-as-a-judge-iteratively)
- [Testing for LLM Applications: A Practical Guide - Langfuse Blog](https://langfuse.com/blog/2025-10-21-testing-llm-applications) - Recent, simple, and straightforward guide to implement LLM testing with LangFuse
- [Test - Docs by LangChain](https://docs.langchain.com/oss/python/langgraph/test) - Basics of testing workflows when using Langgraph

## General Principles
- [Build to Last — Chris Lattner talks with Jeremy Howard - YouTube](https://www.youtube.com/watch?v=WJS2YDZO-vc) - Super interesting conversation. Chris Lattner (creator of LLVM, Swift, and Mojo) and Jeremy Howard (founder of Fast.ai, inventor of first LLM) discuss why rushing to AI-generated code might be destroying code craftsmanship.
- [X post - Notes on how @linear thinks about AI agents: "The best automation starts with manual processes". They went from keyword search → semantic search → full agentic loops](https://x.com/jxnlco/status/1980624372936159315)

## Utility

- [Trimmy — Paste once, run once](https://trimmy.app/) - Isn't it annoying when you copy an LLM's answer in the terminal and the formatting is completely broken? This fixes it.


