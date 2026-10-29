# PIR Worksheet — Hunt Loop Stage 1: Collect & Prioritize

Use this worksheet to turn stakeholder concerns into **Priority Intelligence Requirements (PIRs)** that can drive hunts. One worksheet per PIR.

---

## 1. PIR identification

| Field | Value |
|---|---|
| PIR ID | PIR-YYYY-### |
| Title | |
| Owner (intel) | |
| Requesting stakeholder(s) | e.g., CISO, SOC lead, IR, risk/compliance |
| Date opened | YYYY-MM-DD |
| Review cadence | e.g., quarterly |
| TLP of this document | TLP:CLEAR / GREEN / AMBER / AMBER+STRICT / RED |

## 2. The requirement

**PIR statement** (one question, decision-oriented):

> e.g., "Which threat actors are actively targeting aerospace suppliers' remote-access infrastructure, and what initial-access techniques are they using?"

**Decision it supports:** What will leadership or the SOC do differently based on the answer?

**Why now?** (trigger: new campaign, sector advisory, incident, audit finding, business change)

## 3. Scope

| Dimension | In scope |
|---|---|
| Business units / crown-jewel assets | |
| Environments | e.g., on-prem AD, M365, AWS, OT |
| Geographies | |
| Time horizon | |
| Out of scope | |

## 4. Threat landscape

| Adversary / campaign | Motivation | Relevant ATT&CK techniques | Confidence | Source(s) |
|---|---|---|---|---|
| | | T#### | High / Med / Low | |
| | | | | |

## 5. Specific Intelligence Requirements (SIRs)

Break the PIR into answerable questions. Each SIR should map to one or more hunts.

| SIR ID | Question | Linked technique(s) | Candidate hypothesis ID |
|---|---|---|---|
| SIR-01 | | | HL-#### |
| SIR-02 | | | |

## 6. Collection & data-source check

| Required data source | Available? | Retention | Platform / table | Gap ticket |
|---|---|---|---|---|
| Process creation (Sysmon 1 / 4688 / EDR) | Y / N / Partial | | | |
| PowerShell script block logging (4104) | | | | |
| Authentication logs | | | | |
| Network / proxy / DNS | | | | |
| Cloud audit logs | | | | |

## 7. Prioritization score

Score 1 (low) to 5 (high).

| Factor | Score | Notes |
|---|---|---|
| Likelihood of targeting | | |
| Business impact if successful | | |
| Detection coverage gap | | |
| Data-source readiness | | |
| **Total (max 20)** | | |

## 8. Status log

| Date | Update | Linked hunts |
|---|---|---|
| | PIR opened | |
