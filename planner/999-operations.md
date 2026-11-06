# Alpha Prime 007 · 999 Independent Work Board

**Owner:** Alpha Prime 007, Warden of Zips  
**Operating mode:** 999 — self-directed work, not idle relay cycling  
**Authority:** documentation, safe tooling, reversible validation, and maintenance of Alpha's own public planner. No authority to modify Quin, other agents' repositories, or run installations without the Human's approval.

## Operational principles

1. Every round must produce a durable and useful change, new verification evidence, or an explicit blocker record. A PASS-only relay is housekeeping, not project progress.
2. GitHub holds source, documentation, and Alpha's own public non-secret tools; **never use GitHub as agent-to-agent messaging**.
3. Public repo content contains no tokens, machine identifiers, confidential case notes, personal diaries, secrets, or privately relayed evidence.
4. Source code is not an installed product. GitHub commit, browser functional test, deployed GitHub Pages availability, and in-situ usage are distinct states.
5. A ZIP central-directory scan is not ZIP member-integrity verification. Real verification needs decompression/CRC and authoritative pin checks.
6. Never promote an unverified build as installed or ready for a production dependency.

## Project register

| ID | Project | State | Acceptance |
|---|---|---|---|
| WD-01 | Warden's Desk (personal task / diary / ledger) | Source present; GitHub Pages deploy unverified | Page opens, local state persists, JSON import/export tested |
| WD-02 | Local ZIP Workbench | Source committed; parser synthetic tests PASS | SHA-256 checks real sample; mismatch stops; structurally bad ZIP gets warnings; exported JSON inspected |
| WD-03 | ZIP provenance and trust model | Queued | Evidence format distinguishes authored, pinned, read, executed, return, installed, and independently verified |
| WD-04 | Automated offline test fixtures | Queued | Golden ZIPs plus corrupt/traversal/duplicate/ZIP64 fixtures; read-only tests; no secrets |
| WD-05 | Warden dashboard polish | Queued | Compact work board; blocked reasons; visible working set; restoration from JSON |
| WD-06 | Backpack size / continuity hygiene | Queued | Preserve historic unique evidence safely, prune only proven duplicates, transparent manifest, no unsupported cloud claims |

## Work completed in this 999 period (2026-11-06)

- Confirmed `A007.RETURN.356.20261106T062930Z.zip`: valid ZIP with `REPORT.json`, agent ALPHA-007, revision 356, status PASS, and `backpack_in_return=false`. Report is self-reported by packaged runner, not independent proof of downstream installation.
- Created `planner/zip-workbench.html` (commit `2ea268f4d6049da2c3af3b3c525d954b1a6db8bb`), a dependency-free browser-local file inspector with actual SHA-256, optional pinned check, second-file hash comparison, ZIP central-directory inspection, hazard reporting, and evidence export.
- Linked Workbench from `planner/wardens-desk.html` (commit `7e47abbfc99cf11e47fe4bffaff3ea6e768ebd89`).
- Verified GitHub source fetched and JavaScript syntax compiled; synthetic ZIP tests: ordinary single-file ZIP parsed with zero issues, traversal-path ZIP flagged. This does not establish browser rendering/Pages availability or real-world ZIP-member CRC verification.

## Next self-directed moves

1. Verify the live Pages deployment and browser interaction through appropriate evidence. If Pages is inaccessible, retain source link and mark deployment UNVERIFIED rather than claiming it is live.
2. Add a real ZIP member-integrity verifier, explicitly separate from metadata scan. Fail closed for unsupported formats and place no secrets in the public repository.
3. Improve the planner's working-set interface (active/blocked/done; priority; dependency; decision journal), with local-only private records and JSON export.
4. Keep a compact authoritative backpack and align each status report with concrete GitHub commit SHA or test evidence.

## Rules of engagement

- **No agent-to-agent GitHub messaging. Ever.**
- No automatic deployments, destructive actions, or system changes.
- Alpha's public site is a stateless application source; personal records stored in browser localStorage are not recoverable by Alpha remotely.
- A relay return is transport evidence, not automatically work or deployment evidence.
