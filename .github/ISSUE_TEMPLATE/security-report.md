---
name: "🛡️ Security report"
about: "Report a real bug in the XSS Range platform (NOT a lab solve)."
title: "[Security] "
labels: ["security", "triage"]
assignees: ["hits313"]
---

> **Before filing:** if the impact is genuinely sensitive (full RCE, secret/PII
> leak, total ATO), please use the
> [private GHSA advisory](https://github.com/hits313/xss-range-community/security/advisories/new)
> instead of a public issue. For everything else, public is fine.
>
> **The 14 labs are intentionally vulnerable** — XSS / sanitizer bypass inside
> any `/labs/*` route is **out of scope**. The platform shell (auth, profile,
> solve, hint, leaderboard, cron, Vercel config) is **in scope**.

## Summary
<!-- One-line description of the bug. -->

## Severity (your guess)
- [ ] P0 — RCE, full account takeover, mass cross-user data access
- [ ] P1 — single-user ATO, cross-user data read/write, solve mass-mint
- [ ] P2 — privacy regression, anti-cheat bypass, rate-limit bypass
- [ ] P3 — misconfig, info-leak, header-policy issue

## Affected surface
- URL / endpoint:
- Component (e.g. `src/app/api/profile/route.ts`, Vercel project config, blob ACL):
- Vercel config issue? (env, blob, cron, build)  Yes / No

## Reproduction steps
1.
2.
3.

```http
# Minimal request showing the bug. Redact your real session cookie.
```

## Impact
<!-- What an attacker can actually do. Concrete, not theoretical. -->

## Suggested fix
<!-- Optional. One-line patch idea is enough. -->

## Disclosure preferences
- Credit me as: <!-- handle / name / anonymous -->
- I'm OK with public disclosure after fix: Yes / No
- Embargo requested: <!-- e.g. 45 days -->

---

> By submitting you confirm: tests were only against your own account, no
> destructive PoCs, no traffic floods, no other users' data accessed beyond
> what was needed to demonstrate the issue. See
> [SECURITY.md](https://github.com/hits313/xss-range-community/blob/main/SECURITY.md)
> for the full policy.
