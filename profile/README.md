# Paranoco

**Publicly verifiable hosting on commodity bare metal.**

Every security claim a platform operator makes, from firmware to admission policy, checkable by anyone.

No need to _trust_ the operator.

---

## 🧩 The problem

Your host says *"we won't read your data."* What backs that up:

- 🧑 **Small host:** one person's habits
- 🏢 **Hyperscaler:** a lot of people on one payroll
- 📜 **Either:** at best, a contract

None is checkable. Honest operators can't prove they're honest either, so the market rewards whoever claims the most.

## 🎯 Why I'm building this

- 🖥️ I've run a multi-tenant Talos cluster, for 5+ years. My tenants have to trust *me*, and they can't check.
- 🏢 Big clouds spread trust across many employees, but they share one employer. That's one point of pressure without independent witnesses.
- 🤖 AI means more one-person companies. They're the hardest to trust: no separation of duties, no one else watching.
- 📉 Corporate promises last as long as the incentive to keep them. Quarterly targets, acquisitions and rewritten ToS don't need a villain.

## 🪜 The trust ladder

Every guarantee is placed on a rung, and never described as higher than it is.

|    | Rung                      | Example                            |
|----|---------------------------|------------------------------------|
| 🔐 | Cryptographic prevention  | tenant-held keys, multi-party root |
| 🧾 | Hardware-signed evidence  | TPM quote of boot state            |
| 👥 | Independent witnesses     | log operators, co-signers          |
| 📒 | Tamper-evident record     | append-only transparency logs      |
| 🤝 | A promise                 | where hosting is today             |

## 📐 Principles

1. 🔎 Every claim ships with a check a stranger can run
2. 😈 The operator is in the threat model
3. 🌍 Verifying needs no account
4. 🏷️ Name every trusted party; prefer replaceable ones
5. 📖 Nothing is secret except keys. The verifier is free software
6. 🎯 Transparency points at the operator, never the tenant
7. 👁️ Visibility, not immunity. No deniability
8. 🏠 Must work for one person renting commodity boxes
9. 📢 Failures are published as prominently as successes

## 🚧 Status

As of January 2026, Paranoco is at best a research project.
