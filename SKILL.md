---
name: finance-business-integration-analysis
description: Analyze finance-business integration materials, management accounting case studies, profitability problems, customer/product/channel profitability, cost structure, pricing, budgeting, resource allocation, and financial-management coursework. Use when the user shares courseware, case PDFs/images, Excel models, PPT deliverables, or asks for summaries, standard answers, case analysis, profitability diagnosis, management implications, or postmortem comparison against a final submission.
---

# Finance Business Integration Analysis

## Overview

Use this skill to turn finance-business materials into high-quality analysis outputs that are evidence-based, numerically grounded, and management-actionable.

Default objective:
- Do not stop at qualitative explanation when the source materials contain numbers.
- Progress from metric definition to calculation, segmentation, driver diagnosis, quantified actions, and implementation implications.

## Workflow

### 1. Build evidence first

Before drawing conclusions:
- Confirm time conditions.
- Read the actual source artifacts first: PDF, image, PPTX, XLSX, or workbook screenshots.
- Prefer structured extraction over visual guessing when spreadsheets or decks are available.

If the user provides:
- `pdf` or scanned courseware: extract text and identify the teaching logic.
- `xlsx`: inspect sheet structure, formulas, key result tables, and assumptions.
- `pptx`: inspect slide storyline, definitions, metrics, and recommendations.
- images only: extract the case facts, constraints, tables, and required questions before answering.

### 2. Decide the task mode

Choose one primary mode:

- `Summary mode`
  Use when the user asks to digest courseware, summarize a topic, or extract the main framework.

- `Case analysis mode`
  Use when the user asks to answer case questions, diagnose profitability, compare customer groups, propose actions, or prepare a classroom or assignment answer.

- `Review mode`
  Use when the user provides a final submission, PPT, or model and asks for comparison against an earlier answer, gap analysis, lessons learned, or improvement guidance.

### 3. In summary mode, extract the management logic

Produce:
- the course main line
- each chapter or session core conclusion
- the most important formulas and concepts
- the few distinctions most likely to be confused
- a reusable analysis framework

Do not paraphrase page by page unless the user explicitly asks.

For detailed structure and output standards, read:
- `references/topic-summary-framework.md`

### 4. In case analysis mode, follow the full analysis ladder

Always work in this order:

1. Define the metric boundary.
2. Compute by object when data exists.
3. State the total result before local interpretation.
4. Segment the objects into management-relevant groups.
5. Diagnose the underlying drivers.
6. Convert recommendations into measurable actions.
7. Separate improvement decisions from exit decisions.

Do not jump directly from case facts to recommendations.

For the full checklist, read:
- `references/case-analysis-sop.md`

### 5. Define the profit lens explicitly

Always tell the user which metric is being analyzed, for example:
- product gross profit
- customer contribution profit
- business-unit contribution
- accounting net profit

State clearly:
- which costs are included
- which costs are excluded
- which allocations are given by the case
- which assumptions are introduced by you

Never mix contribution profit with legal or accounting net profit.

### 6. If quantitative data exists, do not stay qualitative

When the materials include tables, spreadsheets, or unit cost rates:
- compute at the customer, product, order, or channel level when possible
- produce totals and distributions
- compare profitable vs unprofitable groups
- standardize behavior intensity when needed, for example per revenue unit

When the source already contains an official final model or answer:
- compare your earlier reasoning with the final result
- identify what you missed in method, depth, and rigor
- extract reusable improvements instead of just admitting the gap

### 7. Upgrade from binary judgment to segmentation

Do not stop at:
- profitable vs unprofitable
- good vs bad customers

Prefer segmentation with management meaning, for example:
- high value high efficiency
- high value high input
- low value improvable
- low value high consumption

Each segment must map to a different action logic.

### 8. Diagnose by drivers, not labels

Avoid vague phrases like:
- complexity is high
- service cost is high

Instead identify the actual drivers, such as:
- low-margin product mix
- design intensity
- expedite intensity
- shipment fragmentation
- order fragmentation
- support burden
- capacity bottlenecks
- structural vs execution cost drivers

Prioritize the drivers by explanatory power when the data allows it.

### 9. Recommendations must be actionable

Whenever possible, turn recommendations into:
- pricing targets
- behavior reduction targets
- service boundary rules
- profitability thresholds
- customer-level or segment-level actions

If discussing customer exit, explicitly test:
- avoidable cost
- unavoidable fixed cost
- idle capacity risk
- contract constraints
- strategic value

Never recommend exit solely because contribution is negative without discussing cost avoidability.

### 10. For review mode, compare method, not just conclusions

When the user asks to compare your answer with a final PPT or XLSX delivery:
- identify where your direction was right
- identify where the final delivery is stronger
- classify the gap into:
  - missing calculations
  - unclear metric boundary
  - weak segmentation
  - unranked drivers
  - unquantified recommendations
  - lack of implementation mechanism
  - lack of validation or modeling
- convert those gaps into a reusable checklist or SOP

For this pattern, read:
- `references/review-and-gap-analysis.md`

### 11. Keep outputs aligned with the user's real need

Typical outputs this skill should produce:
- concise course digest
- classroom speaking answer
- assignment-ready structured answer
- management memo
- standard answer
- comparison postmortem
- reusable SOP or checklist

If the user asks for a final deliverable or similar, bias toward:
- clear sections
- explicit formulas
- total-result table logic
- segment-specific actions
- implementation sequence

## References

Read only what is needed:
- `references/topic-summary-framework.md`
  Use for digesting courseware and lecture materials.
- `references/case-analysis-sop.md`
  Use for profitability, management accounting, and finance-business case analysis.
- `references/review-and-gap-analysis.md`
  Use when comparing your answer to a final delivery and extracting lessons.
- `references/output-templates.md`
  Use when the user wants a classroom answer, written assignment answer, or standard answer format.

## Updating the skill from future work

When the user later shares new finance-business materials in this thread and asks for updated analysis:
- reuse the workflow above
- inspect whether the new task reveals a repeated weakness or a stronger reusable pattern
- if yes, update the skill source with the improved method after the user explicitly asks to update the skill

Default rule:
- do not silently update memory
- do not silently update the skill itself unless the user asks
- but do write current-project SOPs and reusable documents inside the project workspace when doing the task
