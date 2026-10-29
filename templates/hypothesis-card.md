# Hunt Hypothesis Card — Hunt Loop Stage 2: Hypothesize

One card per testable hypothesis. A good hypothesis is **specific, falsifiable, and tied to data you actually have.**

---

## Header

| Field | Value |
|---|---|
| Hypothesis ID | HL-#### |
| Title | |
| Author | |
| Date | YYYY-MM-DD |
| Linked PIR / SIR | PIR-YYYY-### / SIR-## |
| TLP | |

## Intelligence basis

| Field | Value |
|---|---|
| Adversary / campaign | |
| Intel source(s) | report, advisory, internal incident, OSINT |
| Source reliability / info credibility | e.g., Admiralty B2 |
| ATT&CK tactic(s) | |
| ATT&CK technique(s) | e.g., T1059.001 — PowerShell |

## The hypothesis

> "If **[adversary / behavior]** is present in **[environment / asset group]**, we expect to observe **[specific observable]** in **[data source]** during **[time window]**."

**Hypothesis statement:**

**What would REFUTE it?** (What result lets us confidently say "not present"?)

## Data & scope

| Field | Value |
|---|---|
| Data source(s) | |
| Platform / table / index | |
| Asset scope | |
| Time window | |
| Data quality concerns | e.g., logging gaps, sampling, retention |

## Hunt approach

- [ ] Searching (IOC / string match)
- [ ] Clustering / stacking (least-frequency analysis)
- [ ] Grouping (co-occurring behaviors)
- [ ] Statistical / baseline deviation
- [ ] Visualization / timeline

**Query reference(s):**
- Sigma: `queries/sigma/`
- KQL: `queries/kql/`
- SPL: `queries/spl/`

## Expected noise

List known benign sources of the same behavior (admin tooling, software deployment, vendor agents) and how you will filter or triage them.

| Benign source | How to recognize | Handling |
|---|---|---|
| | | |

## Outcome (complete after the hunt)

- [ ] **Confirmed** — malicious activity found → open incident, complete hunt report
- [ ] **Refuted** — sufficient data, no evidence found
- [ ] **Inconclusive** — data gap or quality issue prevented a conclusion

**Follow-on actions:**
- [ ] New / tuned detection (`detections/`)
- [ ] Intel update (`templates/intel-feedback.md`)
- [ ] Data-source gap ticket
- [ ] Re-hunt scheduled for: ________

**Hunt report:** link
