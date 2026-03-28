# ABOV3 EXODUS GUIDE/FAQ

## Introduction

The ABOV3 Exodus Agentic Development environment provides a full environment (including MCP) for air-gapped or connected development.  
1) It can work with local directories for code or document development
2) Utilize your inference source - or ABOV3's own models
3) Supports many agents and the Prism "swarm" where a problem can be submitted to multiple models simultaneously and then an arbiter merges them into a "best of breed" response.  You can also create customized agents and sub-agents if the stock agents aren't sufficient.
4) Flowcore supports development of agent-driven processes that are somewhat rigid and well defined.
5) Naphesh supports the development of true AGI - agents that are flexible and can perform a diverse set of tasks.  You can speak with them, or text them from your phone.  What they can do is entirely what you're willing to give them permission to do.

** Note - ABOV3 uses its own VOIP to ensure that caller-ID spoofing will not work, only the true and verified phone number can text its agent.

## Inference Source Integration

### Claude (Anthropic) Pro and Enterprise
Exodus supports both pre-paid API token accounts, as well as Claude Pro and Enterprise accounts.  If you intend to do code development, the Pro/Enterprise accounts will work well, but if you intend to develop long-running agents (Flow/Nephesh) the short lifespan of the Claude Pro/Enterprise tokens makes this almost impossible (they expire in about 6 hours).

To enable your Claude Pro/Enterprise with Exodus, follow [these steps](./claude_jwt_tokens.md)

