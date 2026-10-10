# ZERO Alpha — Public Launch Readiness

> Working checklist, updated 2026-10-10. This is **not** a declaration that ZERO Alpha is live. Mark an item complete only with direct verification and evidence.

## ZERO / Compute / Pool truth checks

- [ ] Review [Compute and Pool](./COMPUTE_AND_POOL.md) for consistency with the actual Gateway and Node implementation.
- [ ] Verify that allowance counters, measured usable compute, active Nodes and successful requests are separate authoritative metrics.
- [ ] Confirm that the 100T figure is a planned shared allowance baseline, not a hard physical-capacity guarantee.
- [ ] Verify Node-backed pool growth only after opt-in, eligible work, real receipts and measured sustainable capacity.

## Public discovery and offer

- [ ] Confirm https://tessen.ai/zero returns a public successful response, including mobile and unauthenticated browsing.
- [ ] Confirm the page links to this repository, accurate documentation, support, and the real onboarding entry point.
- [ ] Describe the developer Alpha offer accurately: free preview subject to eligibility, capacity, fair use, concurrency and operational controls.
- [ ] Keep the 100T tokens/day figure clearly labeled as a **planned shared-pool baseline**, not observed throughput, available capacity, individual allocation, or a guarantee.
- [ ] Do not publish simulated counters, fabricated user numbers, invented capacity, or unsupported uptime claims.
- [ ] Review page metadata, canonical URL, sitemap, robots rules, Open Graph preview, and machine-readable descriptions against actual product availability.

## External developer activation gate

- [ ] A developer with no internal assistance can sign up/sign in and receive authorized ZERO access.
- [ ] Verify documented API key/credential generation and revocation, if that is the supported access mechanism.
- [ ] Verify the real OpenCode setup and model identifier `tessen/project-zero` from a clean environment.
- [ ] Complete and record a real coding mission against a test repository, including tool permissions, results, errors and return-user experience.
- [ ] Confirm usage limits, accurate metering, fair-use enforcement, failure handling and operational disable controls.
- [ ] Publish installation and integration commands **only after** verifying them end to end.
- [ ] Do not say the pool is OPEN until this gate passes.

## Benchmarks and coding missions

- [ ] Run reproducible coding tasks against pinned versions, inputs, model configurations and test harnesses.
- [ ] Publish only measured results with environment, dates, methodology, costs where appropriate, comparisons and limitations.
- [ ] Disclose failed runs and meaningful exclusions; do not invent benchmark scores.
- [ ] Provide real example missions with the prompt, repository or reproducible fixture, expected outcome and observed outcome.
- [ ] Separate aspirational performance targets from verified measurements.

## Architecture, safety, privacy and Node

- [ ] Keep public architecture high-level; exclude proprietary provider routing, secrets, credentials and sensitive infrastructure.
- [ ] Explain what request content is sent to services, retention and logging boundaries, and what is or is not guaranteed.
- [ ] Document authentication, authorization, abuse protections, rate/concurrency limits, incident reporting and operational restrictions.
- [ ] Clearly label Node participation optional, owner-authorized and subject to hardware/workload validation.
- [ ] Do not imply Node capacity, contributions, earnings, certification or incentives exist without verification.
- [ ] Review SECURITY.md and CONTRIBUTING.md for accuracy.

## Launch and community

- [ ] Update README status from COMING to OPEN **only after** production certification.
- [ ] Link the verified public website, supported integrations, known limitations, roadmap, changelog and community contribution process.
- [ ] Validate links and documentation navigation on GitHub.
- [ ] Prepare individualized replies to technical contacts who requested details (including Atlarix and COTAL), after the public page and relevant claims are verified.
- [ ] Do not imply agent identity/handoff/tool interoperability with COTAL is implemented unless demonstrated.
- [ ] Announce the public page separately from Alpha access if those milestones happen on different dates.

## Evidence record

For each completed gate, capture: owner, verification date (UTC), test environment, commit or deployment identifier, reproducible steps, observed result, and links to non-sensitive evidence.

**Release rule:** Documentation can ship before the Alpha; claims of access, performance, capacity and interoperability must wait for evidence.
