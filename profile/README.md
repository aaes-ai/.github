# AAES

**The operating and governance layer for enterprise AI agents.**

AAES (Autonomous Agentic Enterprise Systems) makes two self-hosted products for enterprise AI agents. **AAES Operate** runs and coordinates agents on your infrastructure. **AAES Govern** checks and records supported actions routed through it. Use either product, or both.

[Explore AAES](https://aaes.ai/) · [Request an evaluation](https://aaes.ai/contact.html) · [Developer docs](https://aaes.ai/developers.html)

## AAES Operate

Run agent teams on your infrastructure with reporting lines, projects and a shared task board, a versioned skills library, connected tools, and recurring work. Choose models and runtimes for your agents.

Operate has its own approval steps, tool permissions, budgets, configuration history, and stop controls. Budgets pause work once recorded spend reaches a limit; in-flight work can overrun. You operate the infrastructure, keys, model-provider accounts, availability, and backups. Operate sends instructions, task context, and tool results to the model providers and runtimes you configure.

## AAES Govern

Connect agents you already run and check supported actions routed through Govern:

- **Permissions:** give each registered agent an accountable human manager and permission for specific capabilities.
- **Approvals:** require an authorized person's approval for capabilities registered as irreversible, bound to the exact request on enforced paths.
- **Spending reservations:** reserve evaluated amounts before authorization and refuse requests above configured limits. Final provider charges can differ.
- **Signed decision records:** export records and check their integrity offline using separately trusted public keys.

Govern can block an action when it controls the required credentials and the agent cannot bypass that path. Observation-only registrations record reported activity without stopping calls. Govern applies only to supported actions routed through it. Combined Operate–Govern workflow coverage is evaluated during the design partnership.

## Start with the public verifier

[**aaesverify**](https://github.com/aaes-ai/aaesverify) is the Apache-2.0 offline
verifier for `aaes.export/v2`. Inspect the source, download a release for macOS,
Linux, or Windows, and try the synthetic sample without a running AAES Govern deployment.

| Resource | Start here |
| --- | --- |
| Verifier source and sample | [aaesverify](https://github.com/aaes-ai/aaesverify) |
| Release binaries | [Current verifier release](https://github.com/aaes-ai/aaesverify/releases/latest) |
| Evidence format | [Export specification](https://aaes.ai/spec.html) |
| Verification scope | [Verification guide](https://aaes.ai/library/verification.html) |
| API and SDK integration | [Developer documentation](https://aaes.ai/developers.html) |
| Supported action packages | [Capability library](https://aaes.ai/capability-library.html) |

Offline verification establishes record integrity against trusted keys. It does
not establish complete capture, downstream execution, or compliance. Independent
corroboration requires separately configured witnesses or timestamp authorities.

## Evaluate one workflow

Both products are available for customer-operated evaluation through a **paid
design partnership**. The core platform repository is private; public verifier
source and binaries are available separately under Apache-2.0.

[Request an evaluation](https://aaes.ai/contact.html) or contact
[hello@aaes.ai](mailto:hello@aaes.ai).

[LinkedIn](https://www.linkedin.com/company/aaes-ai/) · [X](https://x.com/aaes_ai) · [YouTube](https://www.youtube.com/@aaes_ai)

*AAES stands for Autonomous Agentic Enterprise Systems.*
