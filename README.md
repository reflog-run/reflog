<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/assets/logo-mint.svg">
    <img alt="Reflog" src=".github/assets/logo.svg" width="420">
  </picture>
</p>

<p align="center"><em>Time, recovered.</em></p>

## What is Reflog?

[Reflog](https://reflog.run) is a local-first desktop application that
turns Git commit history and `.ics` calendar exports into a reviewable,
editable timeline of billable sessions -- for solo developers, agencies,
and B2B teams who need defensible time reports without running a timer.

Your repositories never leave your machine: Reflog reads commit metadata
locally and produces evidence-grade PDF and CSV reports you can hand to
a client.

- Website and downloads: <https://reflog.run>
- Features: <https://reflog.run/features>
- Roadmap: <https://reflog.run/roadmap>
- Changelog: <https://reflog.run/changelog>

This repository is Reflog's public home on GitHub: the **issue tracker**
for bug reports and feature requests, plus security-reporting
instructions. **The Reflog application is closed-source**, distributed as
signed binaries under an End User License Agreement (EULA) published at
<https://reflog.run/eula>; no application source code is present here.

## Install

Linux and macOS:

```sh
curl -fsSL https://reflog.run/now | bash
```

Windows (PowerShell):

```powershell
irm https://reflog.run/now | iex
```

Prefer a manual download? Get the AppImage, `.exe`, or `.dmg` from
<https://reflog.run>.

## Reporting bugs

Open an issue using the **Bug report** template:
<https://github.com/reflog-run/reflog/issues/new?template=bug_report.md>

## Requesting features

Open an issue using the **Feature request** template:
<https://github.com/reflog-run/reflog/issues/new?template=feature_request.md>

If your request overlaps with an item already on the roadmap
(<https://reflog.run/roadmap>), linking it helps prioritization.

## Reporting a security vulnerability

Please use GitHub's Private vulnerability reporting:
<https://github.com/reflog-run/reflog/security/advisories/new>

Reports submitted there are private to the maintainer and not visible in
the public Issues tracker. See [SECURITY.md](SECURITY.md) for scope,
response targets, and safe-harbor terms.

## Other contact

For support, license issues, privacy / data-protection requests, or
anything else: <https://reflog.run/contact>

## macOS first-launch warning (alpha builds)

Until Apple notarization is complete, macOS Gatekeeper will block the
first launch with **"Reflog cannot be opened because the developer
cannot be verified."**

To open it:

1. Open **System Settings -> Privacy & Security**.
2. Scroll down to the **Security** section.
3. You'll see a notice that **"Reflog" was blocked**. Click **Open Anyway**.
4. Confirm in the prompt.

After this once, future launches and auto-updates work normally.

> **Note:** The right-click + Open trick *does not* bypass quarantine on
> apps extracted from a downloaded `.dmg`. The System Settings override
> is the correct path. We test this with each release on macOS 14 and 15.

## License

The files in this repository are display-only repository content; the
Reflog application itself is licensed under the EULA at
<https://reflog.run/eula>. See [LICENSE.md](LICENSE.md).
