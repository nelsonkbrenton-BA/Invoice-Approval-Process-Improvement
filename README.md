# Invoice Approval Process Improvement

Operations analysis project focused on improving invoice approval workflow efficiency, visibility, controls, KPI reporting, and automation readiness at NorthStar Manufacturing.

## Project Overview

This project was completed from the perspective of an Operations Analyst at NorthStar Manufacturing, a mid-sized manufacturing company managing vendor invoices, purchase orders, department approvals, and payment processing.

The VP of Finance, Director of Operations, and Accounts Payable Manager requested an analysis of the invoice approval process due to recurring approval delays, manual follow-up, unclear routing, late-payment risk, and limited visibility into invoice status.

The goal of this project was to identify approval bottlenecks, understand the root causes of processing delays, analyze workflow performance, and recommend a future-state process that improves efficiency, visibility, compliance, and financial control.

## Business Problem

NorthStar Manufacturing was experiencing delays in its invoice approval process. Invoices were received through email, reviewed manually by Accounts Payable, routed to department approvers through Outlook, and tracked using spreadsheets.

The Accounts Payable team often had to manually determine the correct approver, follow up on pending approvals, and resolve missing or incorrect invoice information before payment could move forward.

The VP of Finance needed better visibility into invoice aging, late-payment risk, approval compliance, and financial control. The Director of Operations wanted to understand whether approval delays were affecting department-level efficiency. The Accounts Payable Manager needed to reduce manual follow-up, rework, and time spent tracking approvals.

The analysis focused on determining whether delays were caused by unclear approval ownership, missing invoice information, approval thresholds, non-PO invoice handling, system limitations, or lack of workflow automation.

## Project Objective

The objective of this project was to analyze NorthStar Manufacturing’s current invoice approval workflow, identify process inefficiencies, document root causes, and recommend improvements that could reduce manual effort, improve approval turnaround time, strengthen invoice processing controls, and prepare the process for future automation.

## Business Questions

* Where are invoices most likely to become delayed?
* What invoice issues create the most rework for Accounts Payable?
* Are approval rules clearly defined and consistently followed?
* How does manual routing affect invoice cycle time?
* Which departments or approval levels create the most bottlenecks?
* What visibility does the VP of Finance need to monitor invoice aging and late-payment risk?
* What visibility does the Director of Operations need to monitor department-level approval performance?
* What does the AP Manager need to reduce manual follow-up and rework?
* What parts of the process should be standardized before automation?

## Current-State Process

1. Vendor invoice is received by Accounts Payable.
2. AP reviews the invoice for required information.
3. AP validates vendor name, invoice number, invoice amount, invoice date, department ownership, purchase order information, and supporting documentation.
4. AP identifies the correct approver using a manually maintained approval matrix.
5. Invoice is routed to the approver by email.
6. Approver reviews the invoice and approves, rejects, or requests clarification.
7. AP follows up manually on pending approvals.
8. AP updates invoice status in the tracker.
9. Approved invoice is sent to Accounting for payment processing.
10. Invoice is paid and documentation is retained for audit purposes.

## Process Map

<img width="2898" height="1638" alt="Process Map" src="https://github.com/user-attachments/assets/b5d315b9-bad7-4114-9044-c8b76b2bd209" />

## Key Findings

* Invoice approval delays were largely caused by manual routing, missing information, and lack of real-time visibility.
* AP relied on an Excel approval matrix to determine the correct approver, which created delays when department ownership was unclear.
* Non-PO invoices required additional manual review, increasing processing time and exception handling.
* Missing purchase order numbers, supporting documentation, and incorrect vendor information created rework before invoices could be routed.
* Approval follow-up was handled manually through email, making it difficult to track aging, escalation status, and pending approvals.
* There was no standardized escalation process for invoices that exceeded expected approval timelines.
* Finance and operations leaders lacked a dashboard showing invoice volume, approval status, aging, exception trends, and SLA performance.

## Root Cause Analysis

The root cause was not simply that approvers were slow to respond. The deeper issue was that NorthStar did not have a standardized, system-supported invoice approval workflow with current approval rules, centralized tracking, automated routing, reminders, escalations, and reliable audit evidence.

| Category   | Root Cause                                                                                                     |
| ---------- | -------------------------------------------------------------------------------------------------------------- |
| Process    | Approval routing, tracking, follow-up, and escalation were manual                                              |
| People     | Approval ownership was sometimes unclear and AP carried the coordination burden                                |
| Data       | Missing PO numbers, missing documentation, incorrect vendor information, and duplicate invoices created rework |
| Systems    | The process relied heavily on Outlook and Excel, with limited workflow automation                              |
| Visibility | Finance and Operations lacked real-time insight into invoice aging, approval delays, and workload              |
| Controls   | Approval evidence was fragmented across email, spreadsheets, shared drives, and accounting systems             |

## Data & Workbook

The Excel workbook uses a representative synthetic sample of NorthStar invoice approval records to model a monthly operating environment of approximately 1,200 vendor invoices.

The workbook includes:

* Invoice tracker sample
* KPI dashboard
* Approval matrix
* Exception log
* Stakeholder register
* Requirements
* User stories
* Implementation roadmap
* Data dictionary

[NorthStar Invoice Approval Optimization Workbook.xlsx ](https://view.officeapps.live.com/op/view.aspx?src=https%3A%2F%2Fraw.githubusercontent.com%2Fnelsonkbrenton-BA%2FInvoice-Approval-Process-Improvement%2Frefs%2Fheads%2Fmain%2FNorthStar%2520Invoice%2520Approval%2520Optimization%2520Workbook.xlsx&wdOrigin=BROWSELINK)

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
| Late Payment Count          | Measures payment risk and financial impact              |

## Future-State Process

1. Invoice is submitted through a centralized intake channel.
2. Required invoice fields are validated before routing.
3. The system checks for duplicate invoices.
4. The invoice is classified as PO or non-PO.
5. Exceptions are flagged and categorized.
6. Approval routing is automatically assigned based on department, invoice amount, and approval authority.
7. Approver receives a workflow notification with invoice details and due date.
8. Automated reminders are triggered before or after SLA breach.
9. Overdue invoices are escalated based on defined rules.
10. Approved invoices are sent to Accounting with required documentation.
11. Dashboard reporting updates invoice status, aging, exceptions, and approval performance.

## Recommendations

* Standardize invoice intake by requiring key invoice fields before routing, including vendor name, invoice number, amount, department, PO number, and supporting documentation.
* Update and govern the approval matrix to prevent routing delays caused by outdated department ownership.
* Define approval SLAs so approvers understand expected turnaround times.
* Automate approval routing based on department ownership, invoice amount, PO status, and approval authority.
* Implement automated reminders and escalation rules for invoices approaching or exceeding approval deadlines.
* Create a centralized invoice tracking dashboard to monitor pending approvals, overdue invoices, exception types, approval cycle time, and late-payment risk.
* Add duplicate invoice detection and validation controls to reduce payment risk.
* Separate PO and non-PO invoice workflows so exceptions can be reviewed more efficiently.
* Evaluate Microsoft Dynamics 365 workflow capability or AP automation software after the process has been standardized.

## Skills Demonstrated

* Operations Analysis
* Workflow Optimization
* Process Improvement
* Bottleneck Identification
* Root Cause Analysis
* Current-State Process Mapping
* Future-State Process Design
* KPI Development
* Dashboard Requirements Planning
* Financial Operations Analysis
* Automation Readiness Assessment
* Implementation Roadmap Planning
* Change Management Planning

## Tools & Methods

* Microsoft Excel
* Microsoft Outlook
* Microsoft Dynamics 365 process review
* Process mapping
* Swimlane analysis
* Root cause analysis
* Five-why analysis
* KPI framework design
* Workflow automation planning
* 30-60-90 day implementation planning

## Project Outcome

This project recommends a more scalable invoice approval process for NorthStar Manufacturing. The future-state process reduces manual AP coordination, improves approval visibility, strengthens financial controls, and helps the VP of Finance, Director of Operations, and Accounts Payable Manager monitor invoice performance through operational KPIs.

The recommended path is to standardize approval rules, tracking, SLAs, exceptions, and KPI reporting first. Once the process foundation is stable, NorthStar can automate routing, reminders, escalations, approval queues, audit trail capture, and dashboard reporting.

## Author

Brenton Nelson
