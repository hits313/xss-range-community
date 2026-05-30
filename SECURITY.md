# Security Policy

If you find a security bug that affects users of https://xss-range.vercel.app,
please tell us.

## Reporting

- **Preferred — private advisory.** Open a [private security advisory](https://github.com/hits313/xss-range-community/security/advisories/new).
  This is the right channel for anything with real impact.
- **Public report — non-sensitive only.** Open a [security issue](https://github.com/hits313/xss-range-community/issues/new?template=security-report.md).
  Do not include working PoCs or other users' data in a public issue.

If you need to reach the maintainer outside GitHub, mention `@hits313` in the
advisory thread and we will move the conversation to a private channel from
there.

## Scope

### In scope

Bugs in the live site that allow an attacker to do one of the following:

- Take over another user's account, session, or handle.
- Read, modify, or delete data that belongs to another user.
- Tamper with the integrity of solves, hints, or the leaderboard.
- Bypass the platform's anti-cheat controls in a way the labs do not intend.
- Achieve server-side impact: injection, code execution, server-side request
  forgery, mass-assignment, prototype pollution, or measurable timing oracles.
- Exfiltrate secrets or user data through hosting / infrastructure misconfiguration.

### Out of scope

- **The labs themselves.** Anything under `/labs/*` is intentionally vulnerable;
  popping XSS there is the curriculum, not a finding. If you discover a
  non-intended way to solve a lab, please open a bug report or lab suggestion
  instead — that helps us tighten the lab.
- Self-XSS, missing security headers on lab pages, payloads pasted into your
  own DevTools console.
- Public CVEs in third-party dependencies without a working proof of concept
  against this specific site.
- Volumetric denial of service, traffic floods, slowloris.
- Social engineering, physical attacks, attacks on your own network.
- Issues in the `.vercel.app` hosting layer itself. Report those to the hosting
  provider directly.

## Service level

| Severity | First response | Fix target |
|---|---|---|
| Critical | within 24 hours | 7 days   |
| High     | within 48 hours | 14 days  |
| Medium   | within 72 hours | 30 days  |
| Low      | within 72 hours | 60 days  |

Public disclosure is coordinated. The default embargo is 30 days after the
fix lands and may be extended for high-impact issues.

## Safe harbour

We will not pursue legal action against researchers who:

- Test only against accounts they themselves created.
- Stop and report as soon as impact is demonstrated.
- Do not access, retain, or share other users' data.
- Avoid destructive actions: no mass deletion, no defacement, no spam, no
  traffic floods.
- Disclose privately first and respect the embargo above.

Credit appears in the Hall of Fame below unless you ask us to omit it.

## Hall of Fame

<!-- - YYYY-MM-DD — @handle — short description (severity) -->

*Reserved for the first researcher to land a confirmed report.*

---

Policy version: 1.1 · Last updated: 2026-05-30
