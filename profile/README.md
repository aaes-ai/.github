# AAES

**The governance layer for enterprise AI agents.**

Let agents work. Keep your team in control.

Create agents in **Agent Studio** using your own model access, or connect agents
you already run. AAES checks permissions, required approvals, and spending limits
before authorizing actions routed through its governed paths, then records the
decision.

[Explore AAES](https://aaes.ai) · [Developer docs](https://aaes.ai/developers.html) · [Request an evaluation](https://aaes.ai/contact.html)

## What AAES helps you control

- **Agent permissions:** register an accountable human manager and allow specific actions on specific resources.
- **Approvals:** bind approval to an exact request, with human approval for actions registered as irreversible on enforced paths.
- **Task budgets:** reserve evaluated amounts before authorization and refuse requests above the configured limit.
- **Action records:** export signed records and check their integrity offline using separately trusted public keys.

Run AAES on your infrastructure alongside your existing identity provider,
credential stores, and monitoring. Enforcement requires AAES to control the
required credential path and the agent to have no bypass route. Observation-only
integrations record reported activity.

## Start with the public verifier

[**aaesverify**](https://github.com/aaes-ai/aaesverify) is the Apache-2.0 offline
verifier for `aaes.export/v2`. Inspect the source, download a release for macOS,
Linux, or Windows, and try the synthetic sample without a running AAES deployment.

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

The platform is available for customer-operated evaluation through a **paid
design partnership**. The core platform repository is private; public verifier
source and binaries are available separately under Apache-2.0.

[Request an evaluation](https://aaes.ai/contact.html) or contact
[hello@aaes.ai](mailto:hello@aaes.ai).

[LinkedIn](https://www.linkedin.com/company/aaes-ai/) · [X](https://x.com/aaes_ai)

*AAES stands for Autonomous Agentic Enterprise Systems.*
