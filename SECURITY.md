# Security Policy

## Reporting

Please use GitHub's Private vulnerability reporting:
<https://github.com/reflog-run/reflog/security/advisories/new>

Reports submitted there are private to the maintainer and not visible in the
public Issues tracker. Do not file public issues for security reports.

If GitHub Private vulnerability reporting is not an option for you (e.g., you
do not have a GitHub account), use the contact form at
<https://reflog.run/contact> with category **Security report**.

## Scope

In scope for this policy:

- The Reflog desktop application (Linux AppImage, Windows `.exe`, macOS
  `.dmg` / `.app.tar.gz`).
- The Tauri auto-updater path (`latest.json` manifest fetch + signature
  verification of update artifacts).
- The Cloudflare worker at `https://reflog-worker.ramon-4ce.workers.dev`
  (license fulfillment + Paddle webhook handling + Keygen license issuance).
- The marketing site at `reflog.run`.

## Out of scope

- Findings against third-party services we depend on (Paddle, Keygen.sh,
  Cloudflare, GitHub) -- please report those directly to the vendor.
- Social engineering of the maintainer or any contractor.
- Denial-of-service against `reflog.run` below sustained attack thresholds
  (volumetric attacks against our shared CDN are Cloudflare's responsibility).

## Response targets

Reflog is built and maintained by a single person (a sole entrepreneur), so the
timelines below are best-effort only and explicitly not a contractual
service-level commitment. They may run longer during periods of limited
availability:

- **Acknowledgement**: best-effort, typically within **10 business days** of
  report receipt.
- **Triage and severity classification**: best-effort, typically within **30
  calendar days**.
- A fix or mitigation timeline is shared with the reporter once triage is
  complete; coordinated public disclosure follows the agreed-upon timeline.

## Safe harbor

We will not pursue legal action against good-faith security research that:

- Avoids privacy violations, data destruction, and service disruption.
- Limits testing to accounts you own or have explicit written permission
  to test.
- Reports the issue to us before any public disclosure, and gives us a
  reasonable opportunity to remediate before disclosing.

If you follow these guidelines we consider your research authorized and
will work with you to understand and resolve the issue quickly.

## Hall of fame

We credit reporters in the release notes (`CHANGELOG.md`) of the version
that ships the fix, unless you ask us not to.
