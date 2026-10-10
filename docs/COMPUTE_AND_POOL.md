# ZERO, Node, Compute and the Pool

**Status: design and pre-launch certification (2026-10-10).** This document explains the intended public contract. It does not certify that a distributed inference network, a 100T/day deliverable capacity, or Node rewards are live.

## Four different things

| Concept | Responsibility | Important boundary |
| --- | --- | --- |
| **Project ZERO** | The developer-facing coding intelligence experience, exposed through the stable identity `tessen/project-zero`. | ZERO is an access and product experience, not a promise of one fixed underlying model or provider. |
| **Tessen Gateway** | Authorizes requests, checks eligibility and limits, selects eligible intelligence routes, records usage/cost, and enforces operational controls. | Public documentation describes behavior, not proprietary provider routing or production topology. |
| **Tessen Compute / capacity** | The actual eligible processing resources behind successful workloads, potentially from approved infrastructure and, in the future, opted-in Nodes. | Hardware presence, RAM, theoretical tokens and real usable throughput are **not interchangeable**. |
| **ZERO Pool** | A bounded, shared daily developer allowance and published program capacity contract. | Pool tokens are an accounting/allowance unit; they are **not** proof of physically provisioned compute or guaranteed output. |

## Planned daily contract

The intended initial shared ZERO Pool is **100 trillion tokens per day**, with a daily reset at **00:00 UTC**. This is a **planned program baseline**, not measured delivery, not per-user quota, and not unlimited usage.

The live pool must be governed by server-authoritative entitlement, allowance accounting, route availability, actual cost and abuse controls. The pool can be throttled, restricted or disabled for safety and economic reasons. A reset replenishes the allowance under policy; it does not create computing hardware or guarantee that every requested token can be served.

A public display must distinguish:
- **Planned baseline** (design target);
- **Authorized daily allowance** (what the server currently permits);
- **Consumed allowance** (actual metered eligible usage);
- **Verified available compute** (capacity supported by observed, eligible hardware and workload evidence);
- **Successful requests** (completed work, not signups or speculative estimates).

Do not use the same number or label for all five.

## How Node can help

Tessen Node is the optional owner-authorized runtime/participation layer for compatible desktop, server and cloud machines. A Node may discover hardware capabilities without automatically participating or executing work. Participation requires explicit consent, eligibility, workload authorization, resource boundaries, reliable availability and server-authoritative receipts.

The intended sequence is:

```text
Developer coding request
  → Tessen identity and ZERO entitlement
  → Gateway policy, allowance and route checks
  → Eligible authorized execution resources
  → Response and actual usage/cost records

Optional capacity path:
Owner installs Node → opts in → capability verification
  → eligible workload testing → useful available capacity
  → authoritative accounting → possible future pool adjustment
```

**An installed or connected Node is not automatically contributed compute.** CPU/GPU specifications alone cannot establish useful inference throughput. Capacity depends on actual model/runtime compatibility, memory, sustained throughput, network reliability, power/thermal behavior, authorization and economics.

Verified incremental Node capacity **may** support a larger **next-day** published pool at the 00:00 UTC boundary, subject to measured capacity, economic feasibility and operational policy. There is no automatic multiplier based on Node count and no guaranteed daily increase. The 100T starting figure must not be represented as a hard floor independent of infrastructure availability.

Node is not required to use ZERO. It must not silently execute workloads, access private files or consume resources without authorization. Credits or compensation, if introduced, require real verified work and explicit published terms; **no guaranteed earnings**.

## Developer workflow versus network participation

A developer may use ZERO from OpenCode without installing Node. Future Tessen Code web, desktop, CLI and IDE experiences may use the same identity and intelligence access, but each distribution path must be individually certified before it is described as available.

A local Node runtime used by a developer for their own authorized workloads is **not necessarily a network-contributing Node**. Local execution, remote requests and optional public network participation are separate user choices.

## Release evidence

Before claiming that the pool is OPEN, verify a clean external developer can authenticate, receive access, select `tessen/project-zero`, complete a real coding request and return with the same authorization. Before claiming Node-backed pool growth, verify eligible Nodes, authorized workload receipts, sustained useful capacity, accounting, and an auditable next-day pool adjustment.

Public benchmarks must disclose tested models, environments, tasks, versions, actual outcomes, methodology and limitations. Never publish invented scores or proprietary routing details.

See [Project ZERO](./PROJECT_ZERO.md), [Node](./NODE.md), [Architecture](./ARCHITECTURE.md), [Developer Alpha](./DEVELOPER_ALPHA.md), and [Launch Readiness](./LAUNCH_READINESS.md).
