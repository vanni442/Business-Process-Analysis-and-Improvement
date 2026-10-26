# Business Process Analysis and Improvement

Academic projects completed for **ISI9332: Business Process Management** at the **University of Wollongong**.

This portfolio demonstrates process mapping, business rule documentation, process analysis, improvement recommendations, and implementation planning through two case studies.

| Project | Type | Focus |
|---|---|---|
| Library Overdue Book Handling | Individual assignment | BPMN modelling, responsibilities, business rules and exception handling |
| Uber Eats Process Improvement | Group assignment | Current-state analysis, future-state design, implementation planning and performance monitoring |

## 1. Library Overdue Book Handling

### Business Problem

Handling overdue books involves reminders, fee calculations, borrower responses and escalation across multiple participants. The case study required these activities and decision rules to be represented in a structured BPMN model.

### My Work

I independently developed the BPMN model and documented its supporting assumptions.

The model covers **6 participants** and represents:

* Responsibilities through pools and lanes.
* Communication between the library and external participants through message flows.
* Follow-up activities after **7 days**.
* Fee calculations, book returns and payment outcomes.
* Escalation and forced case closure after **60 days**.
* Alternative paths for unresolved cases and borrower responses.

### Outcome

Produced an editable process model and supporting documentation that make responsibilities, timing rules and exception paths explicit.

### Diagram and Files

![Library overdue book process](UOW%20Library%20overdue%20process/UOW%20Library%20Overdue%20diagram.svg)

* [View the process diagram](UOW%20Library%20overdue%20process/UOW%20Library%20Overdue%20diagram.svg)
* [Download the BPMN model](UOW%20Library%20overdue%20process/UOW%20Library%20Overdue%20process.bpmn)
* [Read modelling assumptions](UOW%20Library%20overdue%20process/UOW%20Library%20Overdue%20Assumptions.pdf)

## 2. Uber Eats Process Improvement

### Business Problem

This group case study examined the order-to-delivery process, focusing on waiting between activities, repeated information requests and inconsistent exception handling.

### Analysis and Proposed Improvements

| Issue identified in the case study | Proposed response |
|---|---|
| Sequential payment verification and courier search | Run both activities concurrently, finalising courier assignment only after payment confirmation |
| Repeated inventory and estimated arrival time requests | Introduce short-term information buffering with automatic refresh |
| Gaps between restaurant readiness and courier arrival | Introduce a clear readiness signal |
| Fragmented handling of delays, cancellations and refunds | Define case ownership and automated responses with escalation paths |

The group documented current-state and future-state BPMN models and assessed proposed improvements across time, cost, quality and flexibility.

### My Contribution

My primary responsibility was **process implementation and control**. I also prepared the executive summary, commentary and conclusion, supported the introduction and cycle time efficiency calculations, and edited the final report.

I developed a proposed **3-phase rollout plan** covering flow acceleration, information flow optimisation and incident handling. The plan connected proposed changes with:

* Performance measures, including cycle time, dispatch delay, estimated arrival time accuracy and refund initiation time.
* Operational and technical risks.
* Mitigation measures and conditions for expanding or adjusting the rollout.

The BPMN diagrams and overall redesign are **group deliverables**, rather than solely my individual work.

### Outcome

Produced a documented improvement proposal linking process issues to future-state workflows, implementation stages, performance monitoring and risk controls.

### Current-State Process

![Uber Eats current-state process](UberEats%20Process%20Improvement/ISI9332_GW_As%20is%20model.svg)

### Future-State Process

![Uber Eats future-state process](UberEats%20Process%20Improvement/ISI9332_To_be%20model.svg)

### Files

* [Current-state BPMN model](UberEats%20Process%20Improvement/ISI9332_GW_As%20is%20model.bpmn)
* [Future-state BPMN model](UberEats%20Process%20Improvement/ISI9332_GW_To%20be%20model.bpmn)
* [Full group report](UberEats%20Process%20Improvement/ISI9332_Process%20Improvement_REPORT.pdf)

## Skills Demonstrated

**BPMN · Process Mapping · Business Rules · Current-State and Future-State Analysis · Process Improvement · Quantitative Analysis · Implementation Planning · Performance Monitoring · Risk Analysis · Report Writing**

## Viewing the Files

View the SVG diagrams directly in this repository or open them in a browser. Download the `.bpmn` files and open them in a compatible BPMN modelling tool to inspect the editable models.

## Scope and Limitations

These are academic case studies. The library model does not represent an officially validated University of Wollongong library process, and the Uber Eats analysis is not an internal company assessment.

Process timings and expected benefits depend on case-study assumptions. Proposed improvements were not implemented or validated in a live operational environment.
