# Security Policy

This is the default security policy for repositories in the Fortemate organization.
If the repository you are looking at has its own `SECURITY.md`, that one takes
precedence.

## Reporting a vulnerability

Please **do not** open a public issue for security problems.

- Preferred: use GitHub's private vulnerability reporting on the affected repository
  (*Security* tab → *Report a vulnerability*), if it is enabled there.
- Otherwise: email **security@fortemate.com** with a description, reproduction steps,
  and the affected repository or service.

## What to expect

Fortemate is maintained by a very small team. We aim to acknowledge reports within
a few days and to fix confirmed issues promptly, prioritized by impact on players
and on the fairness guarantees of the platform. Please allow reasonable time for a
fix before public disclosure.

There is no bug bounty program; credit in the release notes is gladly given if you
want it.

## Scope

- The game platform and its services (`play.jc.id.lv` / `fortemate.com`, the game
  backend, the Bot API).
- Code in the repositories of this organization.
- Especially welcome: anything affecting the **provably-fair dice** guarantees, the
  integrity of ratings, or account security.

Out of scope: vulnerabilities in third-party platforms we run on (report those to
the respective vendors), and volumetric denial-of-service findings.
