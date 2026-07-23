<h1 align="center">Hi, I'm Pratheep</h1>
<h3 align="center">Security-focused Open Source Contributor · Frappe / ERPNext / HRMS</h3>

<p align="center">
  I find the bugs that don't show up until production does.
</p>

---

### What I do

I dig into large, real-world Python codebases and find the gaps that matter most: swallowed exceptions, missing permission checks, and broken cancellation/lifecycle logic — the kind of issues that don't fail loudly, they just quietly corrupt data or open a door. My focus is the Frappe ecosystem (ERPNext & HRMS), where I've built a consistent track record of finding and fixing real, reproducible bugs — not cosmetic ones.

All of the work below was done in a single 30-day window.

### Track record (30 days)

**frappe/hrms**
- 9 PRs merged into production
- Fixed missing/incorrect permission checks across whitelisted endpoints (shift assignment, leave allocation, attendance, salary slips)
- Fixed cancellation-state bugs — cancelled records (Leave Allocation, Attendance, Vehicle Log, Shift Assignment) leaking into reports, timelines, or blocking new actions
- Fixed a MariaDB reserved-word bug breaking date filters
- 1 PR open, 8 additional PRs submitted and closed after review

**frappe/erpnext**
- 1 issue resolved and merged
- 5 additional issues currently open, covering silently swallowed exceptions in pricing rules, bank transaction rules, RFQ to Supplier Quotation flow, and statement-of-accounts email resolution
- Reported a subtle falsy-zero bug in bank statement import mapping logic

### How I work

- I read code like an attacker and a maintainer at the same time — every fix is grounded in the actual contract/behavior of the system, not a guess.
- I don't just report a bug — I ship a fix, a reproducer, and a clean PR that respects existing architecture and review standards.
- Permission and authorization bugs are my specialty: whitelisted functions that skip `frappe.has_permission()` checks are exactly the kind of gap I go looking for.

### Tech I work with

`Python` · `Frappe Framework` · `MariaDB` · `ERPNext` · `HRMS` · Static & runtime security analysis

---

<p align="center">
  <i>Quiet bugs. Loud fixes.</i>
</p>
