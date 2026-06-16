# Invoice-Approval-Process-Improvement

Analysis of a manual invoice approval workflow at Northstar Manufacturing using business process analysis, root cause analysis, KPI design, and automation recommendations.

## Project Overview

This project was completed from the perspective of an Operations Analyst at Northstar Manufacturing, a mid-sized manufacturing company managing vendor invoices, purchase orders, department approvals, and payment processing.

The VP of Finance, Director of Operations, and Accounts Payable Manager requested an analysis of the invoice approval process due to recurring approval delays, manual follow-up, unclear routing, and limited visibility into invoice status.

The goal of this project was to identify approval bottlenecks, understand the root causes of processing delays, and recommend a future-state workflow that improves efficiency, visibility, compliance, and financial control.

## Business Problem

Northstar Manufacturing was experiencing delays in its invoice approval process. Invoices were received through email, reviewed manually by Accounts Payable, routed to department approvers through Outlook, and tracked using spreadsheets.

The Accounts Payable team often had to manually determine the correct approver, follow up on pending approvals, and resolve missing or incorrect invoice information before payment could move forward.

The VP of Finance needed better visibility into invoice aging, late payment risk, and approval compliance. The Director of Operations wanted to understand whether process delays were affecting department-level efficiency. The Accounts Payable Manager needed to reduce manual follow-up, rework, and time spent tracking approvals.

The goal of this analysis was to determine whether delays were caused by unclear approval ownership, missing invoice information, approval thresholds, non-PO invoice handling, system limitations, or lack of workflow automation.

## Project Objective

The objective of this project was to analyze Northstar Manufacturing’s current invoice approval workflow, identify process inefficiencies, document root causes, and recommend improvements that could reduce manual effort, improve approval turnaround time, and strengthen invoice processing controls.

The analysis focused on approval routing, exception handling, invoice tracking, approval thresholds, stakeholder responsibilities, and dashboard requirements for finance and operations leadership.

## Business Questions

* Where are invoices most likely to become delayed?
* What invoice issues create the most rework for Accounts Payable?
* Are approval rules clearly defined and consistently followed?
* How does manual routing affect invoice cycle time?
* Which departments or approval levels create the most bottlenecks?
* What visibility does the VP of Finance need to monitor invoice aging and late payment risk?
* What visibility does the Director of Operations need to monitor department-level approval performance?
* What does the AP Manager need to reduce manual follow-up and rework?
* What parts of the process should be automated first?

## Current-State Process

1. Vendor invoice is received by Accounts Payable.
2. AP reviews the invoice for required information.
3. AP validates vendor name, invoice number, invoice amount, invoice date, department ownership, purchase order information, and supporting documentation.
4. AP identifies the correct approver using a manually maintained approval matrix.
5. Invoice is routed to the approver by email.
6. Approver reviews the invoice and approves, rejects, or requests clarification.
7. AP follows up manually on pending approvals.
8. Approved invoice is sent for payment processing.
9. Invoice is paid and documentation is retained for audit purposes.

## Key Findings

* Invoice approval delays were largely caused by manual routing, missing information, and lack of real-time visibility.
* AP relied on an Excel approval matrix to determine the correct approver, which created delays when department ownership was unclear.
* Non-PO invoices required additional manual review, increasing processing time and exception handling.
* Missing purchase order numbers, supporting documentation, and incorrect vendor information created rework before invoices could be routed.
* Approval follow-up was handled manually through email, making it difficult to track aging, escalation status, and pending approvals.
* There was no standardized escalation process for invoices that exceeded expected approval timelines.
* Finance and operations leaders lacked a dashboard showing invoice volume, approval status, aging, exception trends, and SLA performance.

## Root Cause Analysis

### Process

* Approval routing was manual.
* Escalation rules were not standardized.
* Invoice follow-up depended on AP reminders.
* Non-PO invoices required additional review steps.

### People

* Approval ownership was sometimes unclear.
* Approvers did not always respond within expected timeframes.
* AP carried the burden of tracking and follow-up.

### Data

* Invoices were often missing purchase order numbers.
* Supporting documentation was not always included.
* Vendor or department information was sometimes incorrect.
* Duplicate invoices created payment risk.

### Systems

* The process relied heavily on Outlook and Excel.
* There was no automated workflow routing.
* There was limited reporting on invoice aging and approval performance.
* Audit trail visibility was limited.

## Recommendations

* Standardize invoice intake by requiring key invoice fields before routing, including vendor name, invoice number, amount, department, PO number, and supporting documentation.
* Automate approval routing based on department ownership, invoice amount, PO status, and approval authority.
* Create approval thresholds that automatically determine whether invoices route to a manager, director, procurement manager, or finance leader.
* Implement automated reminders and escalation rules for invoices approaching or exceeding approval deadlines.
* Create a centralized invoice tracking dashboard to monitor pending approvals, overdue invoices, exception types, and approval cycle time.
* Add duplicate invoice detection and validation controls to reduce payment risk.
* Separate PO and non-PO invoice workflows so exceptions can be reviewed more efficiently.
* Review and maintain the approval matrix regularly to prevent routing delays caused by outdated ownership information.

## Recommended KPIs

| KPI                         | Purpose                                                 |
| --------------------------- | ------------------------------------------------------- |
| Average Approval Cycle Time | Measures how long invoice approvals take                |
| Invoice Aging               | Tracks invoices waiting for approval                    |
| Approval SLA Compliance     | Measures whether approvals are completed on time        |
| First-Pass Approval Rate    | Tracks invoices approved without rework                 |
| Exception Rate              | Measures invoices with missing or incorrect information |
| Duplicate Invoice Rate      | Identifies duplicate payment risk                       |
| Non-PO Invoice Volume       | Tracks invoices requiring additional manual review      |
| Overdue Approval Count      | Identifies stalled approvals                            |
| AP Follow-Up Volume         | Measures manual effort required by AP                   |


## Future-State Process

1. Invoice is submitted through a centralized intake channel.
2. Required invoice fields are validated before submission.
3. The system checks for duplicate invoices.
4. The invoice is classified as PO or non-PO.
5. Approval routing is automatically assigned based on department, amount, and approval authority.
6. Approver receives a workflow notification.
7. Automated reminders are triggered before the SLA deadline.
8. Overdue invoices are escalated based on defined rules.
9. Approved invoices are sent to Accounting for payment.
10. Dashboard reporting updates invoice status, aging, and approval performance.

## Deliverables

* Current-State Process Analysis
* Root Cause Analysis
* Future-State Process Design
* KPI Framework
* Dashboard Requirements
* Business Requirements Document
* User Stories and Acceptance Criteria
* Implementation Roadmap
* Executive Summary

## Outcome

This project recommends a more scalable invoice approval process for Northstar Manufacturing. The future-state process reduces manual work, improves approval visibility, strengthens financial controls, and helps the VP of Finance, Director of Operations, and Accounts Payable Manager monitor invoice performance through operational KPIs.

The recommendations create a clearer workflow for Accounts Payable, department approvers, and finance leadership while reducing the risk of late payments, duplicate invoices, and unresolved approval bottlenecks.

## Author

Brenton Nelson
