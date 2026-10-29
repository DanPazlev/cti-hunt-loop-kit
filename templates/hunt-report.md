# Hunt Report — Hunt Loop Stages 3–5: Hunt, Analyze, Operationalize

Complete one report per executed hypothesis. Keep it short enough that a SOC lead can read the summary in two minutes.

---

## 1. Summary

| Field | Value |
|---|---|
| Hunt ID | HUNT-YYYY-### |
| Hypothesis ID | HL-#### |
| Linked PIR | PIR-YYYY-### |
| Hunter(s) | |
| Hunt window (data) | YYYY-MM-DD → YYYY-MM-DD |
| Execution dates | |
| Outcome | Confirmed / Refuted / Inconclusive |
| Severity (if confirmed) | Critical / High / Medium / Low |
| TLP | |

**Bottom line up front (2–3 sentences):**

## 2. Scope & data

| Data source | Platform / table | Assets covered | Coverage % | Notes |
|---|---|---|---|---|
| | | | | |

**Gaps that limited the hunt:**

## 3. Method

Queries executed (link to files in `queries/` and note any modifications):

| Query | Platform | Results returned | After filtering |
|---|---|---|---|
| | | | |

Analysis techniques used (stacking, timeline, pivoting, etc.):

## 4. Findings

| # | Host / identity | Observable | Assessment | Confidence | Action taken |
|---|---|---|---|---|---|
| 1 | | | Malicious / Suspicious / Benign | H / M / L | |

**Benign activity identified** (add to baseline / allow-list candidates):

| Source | Description | Recommended handling |
|---|---|---|
| | | |

## 5. Operationalize

| Action | Owner | Ticket | Status |
|---|---|---|---|
| New detection rule (`detections/`) | | | |
| Tune existing detection | | | |
| Logging / telemetry improvement | | | |
| Hardening / control change | | | |
| Incident opened | | | |

**Detection candidate details:**
- Logic summary:
- Expected alert volume / FP rate:
- Promoted to production? Y / N — date:

## 6. Feed back to CTI

- [ ] Intel feedback form completed (`templates/intel-feedback.md`)
- [ ] New IOCs / TTPs shared (internal / ISAC / MISP / OpenCTI) at TLP: ____

## 7. Metrics

| Metric | Value |
|---|---|
| Analyst hours | |
| Time from intel receipt to hunt start | |
| Events reviewed | |
| Detections created | |
| Data gaps identified | |

## 8. Lessons learned
