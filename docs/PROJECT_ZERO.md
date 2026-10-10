# Project Zero

Tessen is launching **Project Zero — ZERO**, its free developer intelligence preview for real coding work.

## Public contract

During the preview:

- access is planned at **$0** for participating developers;
- the Zero Pool is planned to start with **100 trillion (100T) shared tokens per day**;
- the shared pool resets every day at **00:00 UTC**;
- access is governed by a Project Zero entitlement;
- usage is metered even when the developer price is $0;
- allocations, concurrency limits and eligible routing may change to keep the pool reliable and sustainable;
- abuse controls and operational kill switches remain part of the service boundary.

Project Zero is not a promise of unlimited compute.

## The 100T daily pool

The launch model starts with a shared allowance of **100T tokens per day** across Project Zero. The pool is replenished every day at **00:00 UTC** for the next 24-hour cycle.

This makes the free preview concrete while keeping it bounded and measurable. Tessen can still apply per-developer allocations, concurrency controls, routing policy and abuse protections so a shared pool remains useful to the developer community.


## Growing the pool with Node

Developers can participate on both sides of Project Zero: consume intelligence for coding work and, optionally, run **Tessen Node** to contribute compatible available compute.

The launch baseline is **100T shared tokens per day**. It is a planned starting target for the launch pool, not a promise that every developer individually receives 100T.

As developers install Tessen Node and explicitly opt compatible compute into the network, Tessen can verify contributed capacity. Verified additional capacity can increase the **next day's published Zero Pool** above the 100T baseline at the **00:00 UTC** reset. The displayed pool must come from real capacity/accounting data, not a fixed marketing multiplier.

Any Node credits or participation benefits will be tied to real contributed work and server-authoritative accounting; this repository will not promise guaranteed earnings or fabricated capacity.

A shared token allowance does not itself certify physical serving capacity or guarantee request fulfillment. The live pool remains subject to measured route availability and economic safety controls. See [Compute and Pool](./COMPUTE_AND_POOL.md) for the distinction between allowance, verified compute and Node participation.

## Canonical model identity

The public model reference is:

```text
tessen/project-zero
```

This is the identity developer tools should use. Internal provider or model routing can evolve independently.

## Activation

A Project Zero developer is meaningfully activated when they complete a real successful request, not merely when an account exists.

The intended journey:

1. Discover Project Zero.
2. Sign in with a supported Tessen developer identity.
3. Receive/confirm Project Zero access.
4. Enter Tessen Console.
5. Connect OpenCode or Tessen CLI.
6. Use `tessen/project-zero`.
7. Complete a real coding task.
8. Return with the same identity and entitlement.
9. Optionally install Tessen Node.

## Economics

Project Zero can be free to the developer without being economically invisible.

Tessen intends to account for:

- requests;
- tokens or equivalent workload units;
- eligible route/provider;
- underlying cost;
- latency and failures;
- active and returning developers.

This allows the preview to grow without confusing a $0 user price with zero infrastructure cost.

## What we will not fake

We will not publish simulated values as real for:

- developer signups or activations;
- active developers;
- active Nodes;
- Node Pool capacity;
- requests served;
- uptime;
- earnings or rewards.

Public network statistics, if shown, will be backed by production telemetry.

## Status

**Pre-launch certification.**

Exact onboarding instructions will be published when the clean new-developer path is certified.
