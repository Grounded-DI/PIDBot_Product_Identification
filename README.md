# PIDBot - Product Identification / Exposure Classification Demonstration

## Overview

Three PIDBot visuals show how product identification and exposure analysis can be structured for legal review. An annotated vintage motor-control center, example exposure heat map, and trigger-chain diagram distinguish possible components, evidence inputs, scoring, party roles, and escalation points. The visuals use illustrative inputs and percentages.

## Key record

| Artifact | What it records | Status |
|---|---|---|
| [`PIDBot_Demo_Vintage_Control_Center_Possible_Asbestos_Components_Without_Brand_Specifics.jpg`](./PIDBot_Demo_Vintage_Control_Center_Possible_Asbestos_Components_Without_Brand_Specifics.jpg) | Annotated vintage industrial motor-control center with labels for possible asbestos-containing wire insulation, phenolic breaker components, arc suppressors, and back panels | **DEMONSTRATION** |
| [`Exposure_Heat_Map_Liability_Wheel_PIDBot_Demo.jpg`](./Exposure_Heat_Map_Liability_Wheel_PIDBot_Demo.jpg) | Example exposure-allocation matrix for asbestos gasket, asbestos packing, and pipe insulation across Defendants A, B, and C | **DISPLAYED EXAMPLE** |
| [`PIDBot_Logic_Chain_Diagram.JPG`](./PIDBot_Logic_Chain_Diagram.JPG) | Trigger chain linking evidence and product data to the PID score engine, role classifier, bankruptcy filter, liability wheel, hazard/override checks, and clear-output or escalation paths | **CONCEPTUAL VISUAL** |

## What the visuals demonstrate

### Product and incident review

The annotated motor-control-center image marks components for investigation using “possible” and “may contain.” Confirming their composition or manufacturer would require product records or testing.

### Exposure and role structure

The heat map displays illustrative percentages for three defendants and three product categories. A real allocation would require the underlying exposure record, a stated method, and attorney review.

### Controlled trigger path

The trigger-chain figure displays a proposed sequence:

`Depositions / Evidence` + `Product / Incident Data` → `PID Score Engine (Exposure Scoring 1-5)` → `Role Classifier` / `Bankruptcy Filter` → `Liability Wheel` → hazard, drift, hallucination-risk, and override checks → `Clear Output` or escalation.

The figure also displays the labels `Deterministic Entropy Governance | ΔH = 0.0042`, `Entropy Gatekeeper`, and `Trap ID: DI2-SCR-091`. Those are labels rendered in the public graphic; this repository does not provide an executable runtime or an independent measurement record for them.

## Recorded checks

The public release contains the three visuals. It provides no executable verifier or benchmark ledger. Broader product-identification performance remains unmeasured in this repository.

## Technical significance

The notable design choice is to make product identity, exposure linkage, role classification, and escalation visible as separate control points. That structure can help legal reviewers see which part of an exposure theory is supported, which part remains uncertain, and where specialist or attorney review is required.

## Scope and regulator-facing boundaries

The images are public-facing demonstrations and do not:

- identify a real product, manufacturer, facility, or worksite;
- establish that any pictured component contains asbestos;
- determine occupational exposure, medical causation, fault, bankruptcy status, liability, or damages;
- replace industrial-hygiene, engineering, medical, claims, or attorney review;
- establish a filing-ready or reliance-authorized legal conclusion; or
- demonstrate a production deployment, universal determinism, or model-wide accuracy.

The repository preserves the image bytes and their displayed annotations. It does not include the source evidence, laboratory testing, proprietary prompts, internal thresholds, or implementation code behind the visuals.

## How to review

1. Start with the [annotated motor-control-center image](./PIDBot_Demo_Vintage_Control_Center_Possible_Asbestos_Components_Without_Brand_Specifics.jpg).
2. Review the [exposure heat map](./Exposure_Heat_Map_Liability_Wheel_PIDBot_Demo.jpg) as a displayed example, not a live allocation.
3. Review the [trigger-chain diagram](./PIDBot_Logic_Chain_Diagram.JPG) for the proposed control path and its escalation points.

## Provenance

The public files are preserved at commit [`57c3e18aba1a56467fae8fed785b16e981a26f7b`](https://github.com/Grounded-DI/PIDBot_Product_Identification/commit/57c3e18aba1a56467fae8fed785b16e981a26f7b). The three Git blob identifiers are:

- motor-control-center image: `458fdb36fb3f3bdd9e75968cb4389c32f1805394`;
- exposure heat map: `974d9b7cd4fc1255ae7e0445e41eb76b74c99d2a`; and
- trigger-chain diagram: `298730257ba30c74445be799c5fdf97fee630ee1`.

These are repository object identifiers for the published files. They establish file identity within Git; they do not independently validate the displayed annotations or example percentages.

## Public status

**PUBLIC VISUAL DEMONSTRATION · PRODUCT IDENTIFICATION AND EXPOSURE WORKFLOW**

© 2026 Grounded DI LLC.
