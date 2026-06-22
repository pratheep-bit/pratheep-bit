### Pratheep S
AI/ML engineer · B.Tech AI & Data Science, final year · Tiruppur, India

I find permission and access-control bugs in large open-source codebases, then fix them.

---

**Merged security fixes**

→ [frappe/erpnext#56132](https://github.com/frappe/erpnext/pull/56132) — `import_coa` permission bypass. Any authenticated user could wipe a company's entire Chart of Accounts with no role check. Co-authored with maintainer [@diptanilsaha](https://github.com/diptanilsaha). Backported to v15 and v16.

→ [frappe/hrms#4738](https://github.com/frappe/hrms/pull/4738) — `allocate_leaves_manually` missing write-permission check, allowing unauthorized modification of leave allocation totals. Merged solo.

**Reported / in review**

→ [frappe/erpnext#55915](https://github.com/frappe/erpnext/issues/55915) — client-controllable `ignore_account_permission` flag bypassing read checks on financial accounts. Assigned to a maintainer within 20 hours.

→ [frappe/hrms#4739](https://github.com/frappe/hrms/pull/4739) · [#4740](https://github.com/frappe/hrms/pull/4740) · [#4741](https://github.com/frappe/hrms/issues/4741) — permission-type mismatches and unguarded mutation paths across attendance, shift, and leave-adjustment APIs.

---

**Stack**

Python · FastAPI · LangChain · LlamaIndex · CrewAI · n8n · Next.js · TensorFlow.js

**Building**

AIRA — in-browser ML learning platform for Grade 5–8 students, no backend, runs entirely on TensorFlow.js.

---

[pratheeps2024@gmail.com](mailto:pratheeps2024@gmail.com) · [LinkedIn](https://linkedin.com/in/pratheep2006)
