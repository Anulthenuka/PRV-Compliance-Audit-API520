# Pressure Relief Valve (PRV) Compliance Audit — API 520, Unit 2

An engineering audit project evaluating the pressure relief and safety valves installed in the **Unit 2 turbine section in Norochcholai Coal Power Plant** against the requirements of **API Standard 520** (Sizing, Selection, and Installation of Pressure-Relieving Devices).

---

## Overview

Pressure relief valves (PRVs) are critical safety devices that protect pressure vessels, piping, and equipment from overpressure conditions. This project verifies whether the PRVs currently installed in the plant comply with:

- **API RP 520 Part I (2000)** — Sizing and Selection
- **API 520 Part II (2015)** — Installation

The audit combines documentation review, field inspection, and a compliance evaluation against key API 520 acceptance criteria, concluding with a corrective-action plan and a reusable inspection checklist for future audits.

## Objectives

1. Evaluate each installed pressure relief valve for compliance with API 520.
2. Identify any deviations that could affect safety or performance.
3. Recommend corrective actions where necessary.
4. Establish a standard inspection checklist for future audits.

## Scope

- Pressure relief and safety relief valves installed on process vessels, heat exchangers, and piping systems within the **Unit 2 turbine section**.
- Verification of documentation, physical inspection, and comparison against API 520 requirements.
- **Out of scope:** testing or recalibration of valves — handled by certified workshops.

---

A pressure relief valve (PRV) is a safety device that automatically opens when pressure exceeds a preset limit, releasing excess fluid or gas, and recloses once normal pressure is restored.

## What is API 520?

API 520 is a standard developed by the American Petroleum Institute that provides guidelines for the design, selection, sizing, and installation of pressure-relieving devices in refineries, chemical plants, and other process industries. It is divided into two parts:

- **Part I:** Sizing and selection of pressure-relieving devices
- **Part II:** Installation of pressure-relieving devices

Key provisions referenced in this audit:

- **Back pressure:** built-up back pressure should be limited to **≤ 10%** of set pressure for conventional valves, since excess back pressure reduces effective disc lift and relieving capacity.
- **Overpressure allowance:** up to 10% overpressure allowed in non-fire cases; up to 21% in fire scenarios.
- **Sizing:** valves must be sized for the worst credible overpressure scenario (blocked outlet, thermal expansion, runaway reaction, etc.).
- **Discharge coefficient (Kd):** typically 0.975 for gases/steam in conventional valves; lower for liquids due to two-phase flow effects.
- **Set pressure tolerance:** generally ±3%, depending on valve type and service.
- **Inlet piping:** total pressure loss in the inlet piping between the protected equipment and the PRV **shall not exceed 3%** of the valve set pressure; inlet piping must be at least the same size as the valve inlet.
- **Installation orientation:** valves must be installed upright and vertical.
- **Discharge/venting:** the discharge system must safely dispose of released fluid, directed away from personnel; piping should be self-draining.
- **Materials:** valve and piping materials must be compatible with the process fluid and rated for the same temperature/pressure conditions.
- Conventional valves should **not** be used where variable/high back pressure is expected, precise pressure control is required, or toxic/hazardous fluid may leak during operation.

---

## Methodology

**1. Data Collection** — For each valve: tag number, equipment served, fluid type, set pressure, diameter size, vessel MAWP, design/operating pressure and temperature, nameplate photographs, and test certificates.

**2. Field Inspection** — On-site visual inspection following the API 520 compliance checklist: valve location, inlet/discharge piping configuration, support, venting, and accessibility.

**3. Evaluation Criteria**

| Parameter | Acceptance Criteria (per API 520) |
|---|---|
| Set Pressure | ≤ Vessel MAWP |
| Inlet Pressure Loss | ≤ 3% of set pressure |
| Back Pressure | ≤ 10% (conventional), ≤ 30% (balanced) |
| Valve Type | Suitable for service (gas, vapor, liquid, or two-phase) |
| Installation | Close to protected equipment, free-draining piping |
| Isolation Valves | Lock-open, full-bore, properly tagged |
| Venting / Draining | Adequate, directed away from personnel |

**4. Documentation** — All findings recorded in an inspection checklist and summarized in a compliance matrix.

---

## Results

### Compliance Matrix

| # | Valve | Set P ≤ MAWP | Inlet Loss ≤ 3% | Back P ≤ 10% | Suitable for Service | Close to Equipment | Isolation Valves |
|---|---|:---:|:---:|:---:|:---:|:---:|:---:|
| 1 | BFP Booster Pump Inlet | ❌ | ❌ | ✅ | ✅ | ❌ | ✅ |
| 2 | Gland Steam Line (LP turbine side) | ❌ | ❌ | ❌ | ✅ | ✅ | ✅ |
| 6 | LP Heater 8/7 Vent Line | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| 7 | LP Heater 6 Vent Line | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| 8 | HP Heater 3 | ✅ | ❌ | ✅ | ✅ | ✅ | ✅ |
| 9 | LP Heater 6 | ✅ | ✅ | ❌ | ✅ | ✅ | ✅ |
| 10 | Condensate Extraction Pump Inlet | ❌ | ❌ | ❌ | ✅ | ✅ | ✅ |
| 12 | CCCW Heat Exchanger (Demin side) | ❌ | ✅ | ✅ | ✅ | ✅ | ✅ |
| 13 | CCCW Heat Exchanger (Sea water side) | ✅ | ❌ | ❌ | ✅ | ✅ | ✅ |
| 14 | LP Heater 5 | ✅ | ❌ | ❌ | ✅ | ✅ | ✅ |
| 15 | LPH 5 Vent | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| 16 | HP Heater 2 | ✅ | ❌ | ✅ | ✅ | ✅ | ✅ |
| 17 | HP Heater 1 | ✅ | ❌ | ✅ | ✅ | ✅ | ✅ |
| 18 | Auxiliary Header | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| 19 | Deaerator Tank and Deaerator | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| 20 | HP Heater 3 Feed Water Inlet | ✅ | ❌ | ✅ | ✅ | ❌ | ✅ |

### Findings & Recommendations Summary

| Safety Valve | Complied? | Remark | Recommendation |
|---|:---:|---|---|
| BFP Booster Pump Inlet | ❌ | Set P > MAWP; inlet P loss > 3%; not close to protected equipment | Decrease set P below **1.2 MPa** |
| Gland Steam Line | ❌ | Set P > MAWP; inlet P loss > 3%; back P > 10% | Decrease set P below **0.042 MPa**; recommend replacement |
| LP Heater 8/7 Vent Line | ✅ | Fully complied | — |
| LP Heater 6 Vent Line | ✅ | Fully complied | — |
| HP Heater 3 | ❌ | Inlet P loss > 3% | Increase set P |
| LP Heater 6 | ❌ | Back P > 10% | Decrease outlet P |
| Condensate Extraction Pump Inlet | ❌ | Set P > MAWP; inlet P loss > 3%; back P > 10% | Decrease set P below **0.2 MPa** |
| CCCW Heat Exchanger (Demin side) | ❌ | Set P > MAWP | Decrease set P below **1.25 MPa** |
| CCCW Heat Exchanger (Sea water side) | ❌ | Inlet P loss > 3%; back P > 10% | Increase set P near **1.25 MPa**; better to replace with new valve |
| LP Heater 5 | ❌ | Inlet P loss > 3%; back P > 10% | Increase set P near **0.6 MPa** |
| LPH 5 Vent Line | ✅ | Fully complied | — |
| HP Heater 2 | ❌ | Inlet P loss > 3% | Increase set P near **4.7 MPa** |
| HP Heater 1 | ❌ | Inlet P loss > 3% | Increase set P near **7.6 MPa** |
| Auxiliary Header | ✅ | Fully complied | — |
| Deaerator Tank and Deaerator | ✅ | Fully complied | — |
| HP Heater 3 Feed Water Inlet | ❌ | Inlet P loss > 3%; not close to protected equipment | Increase set P near **27 MPa** |

**Fully compliant valves:** LP Heater 8/7 vent line, LP Heater 6 vent line, LPH 5 vent line, Auxiliary header, and Deaerator tank/Deaerator. These installations can serve as models for corrective actions on other systems.

---

## Discussion

The evaluation shows a significant number of pressure relief valves in the plant are **not fully compliant** with API 520, presenting potential risks to equipment integrity and personnel safety. Non-compliant findings fall into three main categories:

### 1. Excessive Inlet Pressure Loss
The most common finding, affecting HP Heaters 1, 2, and 3, the BFP Booster Pump, the Condensate Extraction Pump, and others. API 520 requires inlet pressure loss ≤ 3% of set pressure. High inlet pressure loss can cause the valve to **chatter** (open/close rapidly), drastically reducing flow capacity and risking mechanical failure — preventing the valve from properly protecting the equipment. This is often linked to excessive pipe length between the vessel and the PRV or undersized inlet piping, consistent with the "not close to protected equipment" findings for the BFP Booster Pump and HP Heater 3 Feed Water Inlet valve.

**Back-pressure check formula:**

```
Back pressure % = (P_back / P_s) × 100%
```

**Inlet pressure loss check formula:**

```
(Pressure Drop / Set Pressure) × 100 ≤ 3%
```

If inlet loss exceeds 3% of set pressure: the valve may open late (since it sees less pressure at its inlet), may chatter/oscillate (reducing relieving capacity), and can suffer seat/spring damage that shortens valve life. Keeping inlet losses below 3% ensures correct opening pressure, stable full-lift operation, and accurate overpressure protection.

### 2. Set Pressure Exceeding MAWP
A critical safety failure observed in the BFP Booster Pump inlet, Condensate Extraction Pump, and CCCW Heat Exchanger (Demin side), where set pressure exceeded the vessel's Maximum Allowable Working Pressure (MAWP). For example, the BFP booster pump inlet valve (Serial 1) has a set pressure of **1.31 MPa**, exceeding the vessel's design pressure (MAWP) of **1.2 MPa** — meaning the equipment can be over-pressured before its safety device activates, defeating the primary purpose of the PRV.

### 3. Excessive Back Pressure
For conventional PRVs discharging to atmosphere, back pressure should not exceed 10% of set pressure. This limit was exceeded in the LP Heater 6 safety valve, Condensate Extraction Pump, CCCW Heat Exchanger (Sea water), and LP Heater 5 safety valve. Excessive back pressure reduces effective valve disc lift and relieving capacity — in a major overpressure event, the valve may not vent fluid fast enough to prevent dangerous pressure buildup.

### Fully Compliant Valves
The LP Heater 8/7 vent line, LP Heater 6 vent line, LPH 5 vent line, Auxiliary header, and Deaerator tank valves were fully compliant and can serve as models for corrective actions elsewhere.

---

## Conclusion

This project successfully evaluated the installed pressure relief valves in the Unit 2 turbine section for compliance with API 520. A significant portion of the valves are **non-compliant** and pose a risk to system integrity. Key deviations fall into three major categories:

1. Widespread excessive inlet pressure loss, often exceeding 3%.
2. Critically high set pressures, in some cases exceeding the MAWP of the protected equipment.
3. Excessive back pressure on conventional valves, reducing their capacity.

These findings indicate systemic issues in the initial design, installation, or management of changes for these PRV systems. A standard inspection checklist was established as a result of this audit, fulfilling all project objectives.

## Recommendations

### 8.1 Immediate Corrective Actions (High-Risk)

Valves with **Set P > MAWP** must be corrected immediately:

- **BFP Booster Pump Inlet:** adjust set pressure to ≤ 1.2 MPa
- **Condensate Extraction Pump:** adjust set pressure to ≤ 0.15 MPa
- **CCCW Heat Exchanger (Demin):** adjust set pressure to ≤ 1.25 MPa

These adjustments must be performed and certified by authorized workshops, as testing is outside the scope of this project.

### 8.2 Engineering Review and Modification

- **Inlet piping:** all valves failing the ≤ 3% inlet pressure loss criterion (HP Heaters 1, 2, 3, LP Heater 5, Condensate Pump, CCCW Sea water, and others) require a detailed hydraulic engineering review — likely relocating valves closer to equipment or increasing inlet piping diameter per API 520 Part II.
- **Outlet piping:** valves failing the ≤ 10% back pressure criterion (LP Heater 6, Condensate, CCCW Sea water) require review of discharge piping.
- **Valve type re-evaluation:**
  - CCCW Heat Exchanger (Sea water) — failed multiple criteria; recommend replacement with a correctly sized new valve.
  - Where high back pressure (>10%) is unavoidable due to discharge manifold design, consider replacing conventional PRVs with **balanced-bellows type valves**, which tolerate back pressure up to 30%.

### 8.3 Future Compliance

- Formally adopt the standard inspection checklist developed during this project for all future PRV procurement, installation, and routine audits, to prevent recurrence of non-compliance.

---

## References

- API Recommended Practice 520, Part I (2000) — *Sizing and Selection*
- API Standard 520, Part II (2015) — *Installation*
- Manufacturer datasheets and test certificates for each PRV

---
