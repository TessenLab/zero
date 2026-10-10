# Tessen CLI

Tessen CLI is Tessen's terminal-native developer interface.

## Availability

**Tessen CLI has been reported as online as of 2026-10-10.** This documentation update reflects that product milestone; the precise public installation endpoint, package versions and supported-platform matrix have not been independently verified in this review.

**Tessen CLI availability and Project ZERO access are distinct.** A working CLI does not by itself establish that `tessen/project-zero` is enabled for every external developer.

## ZERO integration

The intended public developer-facing model identity is:

```text
tessen/project-zero
```

The certified ZERO terminal flow should cover authentication, entitlement, model invocation, real coding-task completion, usage/error visibility and returning-user continuity. Publish tested commands and version requirements only after checking the actual released CLI.

## Documentation still needed

- Verified official install/update/uninstall instructions and supported operating systems
- Exact authentication and logout commands
- Tested ZERO model selection and example coding request
- API credential handling and revocation
- Limits, troubleshooting and privacy/security guidance

See [Developer Alpha](./DEVELOPER_ALPHA.md), [Compute and Pool](./COMPUTE_AND_POOL.md), and [Launch Readiness](./LAUNCH_READINESS.md).
