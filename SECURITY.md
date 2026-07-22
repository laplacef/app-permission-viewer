# Security Policy

## Supported Versions

| Version | Supported |
|---------|-----------|
| latest  | Yes       |

Only the latest release receives security patches.

## Reporting a Vulnerability

**Do not open a public GitHub issue for security vulnerabilities.**

To report a vulnerability, use [GitHub's private vulnerability reporting](https://github.com/laplacef/app-permission-viewer/security/advisories/new). You can expect an initial response within 72 hours.

Please include:
- A description of the vulnerability
- Steps to reproduce the issue
- Potential impact assessment

## Scope

The following are considered security issues:
- Exposure of installed-application or permission data to other apps on the device
- Exported components, implicit intents, or debug settings that leak data
- Dependency vulnerabilities in direct dependencies

## Out of Scope

The following are **not** security issues:
- Vulnerabilities in Android's PackageManager or the platform itself
- Permission data Android already exposes to any app holding QUERY_ALL_PACKAGES
- Behavior of the third-party apps being listed
