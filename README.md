<p align="center">
  <a href="https://anyrouter.dev">
    <img src="https://anyrouter.dev/brand/anyrouter-logo.svg" alt="AnyRouter logo" width="220" />
  </a>
</p>

<h1 align="center">AnyRouter Issues &amp; Requests</h1>

<p align="center">
  <strong>One API key for hundreds of AI models, with automatic failover, free models, bring-your-own-key at $0 markup, and a shared key pool.</strong>
</p>

<p align="center">
  <a href="https://anyrouter.dev">Website</a> ·
  <a href="https://anyrouter.dev/docs">Docs</a> ·
  <a href="https://anyrouter.dev/models">Models</a> ·
  <a href="https://anyrouter.dev/dashboard">Dashboard</a> ·
  <a href="https://status.anyrouter.dev">Status</a>
</p>

---

## About AnyRouter

[AnyRouter](https://anyrouter.dev) is an OpenAI- and Anthropic-compatible LLM gateway. Point your existing SDK at one base URL, keep one API key, and switch models by changing the model ID.

- **One endpoint, many providers.** Use `https://anyrouter.dev/api/v1` with OpenAI-compatible clients, or the Anthropic-compatible Messages API, and reach models across many providers.
- **Automatic routing and failover.** Requests can move to healthy routes when a provider is slow or unavailable.
- **Free and paid options.** Try free models, use credits, bring your own provider keys at $0 AnyRouter markup, or participate in the shared key pool.
- **Built for developers and agents.** Works with common SDKs, coding agents, and tools through standard API formats.

```bash
curl https://anyrouter.dev/api/v1/chat/completions \
  -H "Authorization: Bearer $ANYROUTER_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "model": "openai/gpt-5.4-mini",
    "messages": [{"role": "user", "content": "Hello from AnyRouter"}]
  }'
```

## Purpose of this repository

This repository is the public tracker for AnyRouter requests and issue reports. Use it to start a conversation with the team and community about problems, integrations, and improvements.

## When to open an issue

| Use case | Template | Examples |
| --- | --- | --- |
| **Report a bug** | [Bug report](https://github.com/AnyRouterHQ/issues/issues/new?template=bug-report.yml) | API errors, incorrect routing, dashboard problems, billing or usage issues, broken docs links, CLI issues |
| **Request a new upstream/provider integration** | [Upstream provider integration](https://github.com/AnyRouterHQ/issues/issues/new?template=upstream-provider-integration.yml) | Add a new provider, add an OpenAI/Anthropic-compatible endpoint, add Decision or System One API support, request specific models from a provider |
| **Request a feature or improvement** | [Feature request](https://github.com/AnyRouterHQ/issues/issues/new?template=feature-request.yml) | Product ideas, API improvements, dashboard changes, documentation improvements, developer experience requests |

## Before you open an issue

- Check [AnyRouter Status](https://status.anyrouter.dev) for active incidents.
- Search [existing issues](https://github.com/AnyRouterHQ/issues/issues) to avoid duplicates.
- For account-specific, billing, or security-sensitive matters, contact [support@anyrouter.dev](mailto:support@anyrouter.dev) instead of posting private details publicly.
- Never include API keys, provider keys, tokens, passwords, or personal data in an issue.

## Upstream/provider integration requests

If you want AnyRouter to integrate a new upstream provider, please open the **Upstream provider integration** template and include as much detail as possible:

- Provider name, website, and description
- Logo (URL or SVG)
- Base URL and API compatibility (OpenAI-compatible, Anthropic-compatible, Decision/System One API, etc.)
- Model listing or catalog page
- The model IDs you want integrated

Complete information helps us verify the provider, match model IDs correctly, and evaluate the integration faster.

## Links

- Website: [https://anyrouter.dev](https://anyrouter.dev)
- Documentation: [https://anyrouter.dev/docs](https://anyrouter.dev/docs)
- Model catalog: [https://anyrouter.dev/models](https://anyrouter.dev/models)
- Dashboard: [https://anyrouter.dev/dashboard](https://anyrouter.dev/dashboard)
- Status: [https://status.anyrouter.dev](https://status.anyrouter.dev)
- Terms: [https://anyrouter.dev/terms](https://anyrouter.dev/terms)
- Privacy: [https://anyrouter.dev/privacy](https://anyrouter.dev/privacy)

---

<p align="center">
  Built for developers who want one simple gateway to many AI models.
</p>
