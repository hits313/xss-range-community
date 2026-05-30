---
name: "Security report"
about: "Report a security bug in the live site (not a lab solve)."
title: "[Security] "
labels: ["security", "triage"]
assignees: ["hits313"]
---

> If your finding has real impact, please use the
> [private security advisory](https://github.com/hits313/xss-range-community/security/advisories/new)
> instead of this public issue. Use this form only for low-risk reports.
>
> The labs are intentionally vulnerable. Cross-site scripting and sanitizer
> bypasses inside `/labs/*` are out of scope. See
> [SECURITY.md](https://github.com/hits313/xss-range-community/blob/main/SECURITY.md)
> for the full scope.

## Summary

<!-- One sentence describing the bug. -->

## Severity (your estimate)

- [ ] Critical
- [ ] High
- [ ] Medium
- [ ] Low

## Affected area

- URL or page:
- Brief description of the affected feature:

## Reproduction

1.
2.
3.

```
# Optional minimal request. Redact your own session cookie.
```

## Impact

<!-- What can an attacker do. Be concrete. -->

## Suggested fix

<!-- Optional. -->

## Disclosure preferences

- Credit me as:
- OK with public disclosure after the fix lands: Yes / No

---

By submitting you confirm that tests were carried out against your own
account, that no other users' data was accessed beyond what was needed to
demonstrate impact, and that no destructive actions were taken. See
[SECURITY.md](https://github.com/hits313/xss-range-community/blob/main/SECURITY.md)
for the full policy.
