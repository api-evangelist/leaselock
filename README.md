# LeaseLock

LeaseLock is an insurtech platform for rental housing that replaces the traditional cash security deposit with lease insurance. Its Zero Deposit program embeds coverage into the lease through a signed addendum, LeaseLock Shield applies AI to ledger data and lease profiles to underwrite risk, and LeaseLock Central gives property teams a portal for claims, support tickets and training.

**No public API.** LeaseLock publishes no developer portal, API reference, OpenAPI description or client SDKs, and no `developer.`, `docs.` or `api.` subdomain resolves. Property management system integration is arranged as a managed engagement. This repo therefore carries identity, compliance and security artifacts rather than API artifacts — no spec-derived artifacts were fabricated.

Artifacts: `packages/` (first-party open-source PostgreSQL extensions pgasync and pgflow), `security/` (probed TLS/HSTS/DNS posture), `well-known/` (probed discovery surface, all 404), `llms/`.

Backed by: 500-global — https://leaselock.com
