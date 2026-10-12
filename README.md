# Cloud-Computing-Project

Christian Volunteer Service (CVS) is a national UK charity supporting vulnerable people across the country, employing 4,000 staff and operating 260 shops.

# Christian Volunteer Service (CVS) Cloud Migration

# Project Overview

Christian Volunteer Service (CVS) is a national UK charity with:

4,000 staff

260 retail shops

£25.7M annual IT spend

£7M legacy CRM cost

15 days downtime in 2016/17

£10M approved cloud modernisation budget

This repository documents the full cloud systems analysis, architecture, costing, SWOT, INaaS/BPaaS design, and sustainability evaluation for CVS’s migration to Microsoft Azure.

The content is based on:

Cloud Computing Systems Analysis Report

CVS Cloud Migration Presentation (Task 2)

# Table of Contents

Introduction

SWOT Analysis

Cloud Service Model Analysis (SaaS / PaaS / IaaS)

Commercial Provider & Cost Analysis

INaaS & BPaaS Development

Sustainability Evaluation

Conclusion

References

# Introduction

CVS operates a large national charity network but suffers from:

Failing legacy systems costing £7M/year

15 days downtime

5 incompatible payroll systems

No e-commerce capability

£6.4M annual hardware spend

Cloud migration transforms CVS’s IT into:

A scalable, resilient, cost-efficient, and environmentally sustainable cloud environment.

A unified digital ecosystem across CRM, HR, Payroll, E-commerce, and Analytics.

# SWOT Analysis

# Current IT Infrastructure

Strengths

40 IT staff

6.4GB donor database

260 shops nationwide

£10M board-approved investment

Existing CRM foundation

Weaknesses

£7M legacy CRM cost

15 days downtime

No e-commerce

5 incompatible payroll systems

£6.4M hardware spend

18 staff maintaining failing systems

Opportunities

SaaS reduces £7M licensing

Cloud analytics unlocks donor insights

E-commerce creates new revenue

CapEx → OpEx frees funds

Microsoft nonprofit pricing

Threats

Staff union resistance

UK GDPR compliance risks

Migration failure risk

Broadband dependency

Budget overrun risk

# Proposed Cloud Infrastructure

Strengths

Unified SaaS CRM

Single cloud payroll

Real-time donor analytics

Zero-downtime disaster recovery

Standardised systems reduce IT overhead

Weaknesses

Internet dependency

3-year migration disruption

Staff retraining required

Vendor lock-in risk

Ongoing subscription budgeting

Opportunities

£3,500/yr Azure nonprofit credits

AI-driven donation forecasting

National e-commerce platform

BPaaS automation

Reduced IT headcount pressure

Threats

Provider outage affects all shops

Larger cybersecurity surface

Staff redundancy reputation risk

Changing UK GDPR rules

Complex e-commerce logistics

# Cloud Service Model Analysis

# IaaS – Infrastructure as a Service

Azure Virtual Machines (UK South) recommended for:

Lift-and-shift of 6.4GB donor database

Eliminating £6.4M hardware spend

Reducing downtime via Azure Site Recovery

Virtualisation allows multiple VMs on one physical server, reducing cost and improving utilisation.

“IaaS depends on virtualization, which allows several virtual machines to run independently on one physical server.”

# PaaS – Platform as a Service

Azure App Service + Docker + Kubernetes (AKS) for:

National e-commerce portal

Automatic scaling for weekend donation spikes

Containerised deployment for speed and efficiency

“Containers are faster to deploy and lighter on resources… ideal for spikes across 260 shops.”

# SaaS – Software as a Service

Recommended SaaS stack:

| Service                     | Provider   | Benefit                    |
| --------------------------- | ---------- | -------------------------- |
| Salesforce NPSP             | Salesforce | 10 free charity licences   |
| Microsoft 365 + Dynamics HR | Microsoft  | Unified comms + HR         |
| Sage Business Cloud Payroll | Sage       | Replaces 5 payroll systems |

# Commercial Provider & Cost Analysis

Why Microsoft Azure?
Native integration with Windows, Office, Outlook

Nonprofit pricing

£2,660 free Azure credits/year

Up to 75% off Microsoft 365

UK data residency (Azure UK South)

Full UK GDPR compliance

AWS was rejected due to:

No UK charity programme

Weaker Microsoft 365 integration

# Cost Breakdown

| Service                    | Annual Cost    |
| -------------------------- | -------------- |
| Azure VMs + Storage        | £400,000       |
| Microsoft 365              | £211,200       |
| Salesforce NPSP            | £86,400        |
| Sage Payroll               | £48,000        |
| Azure App Service + AKS    | £220,000       |
| Azure Synapse              | £90,000        |
| Azure Integration Services | £120,000       |
| **Year 1 Migration**       | **£1,500,000** |

Post-migration annual cost: £1.2M/year  
Current cost: £14.9M/year  
Estimated savings: £4M+/year

# INaaS & BPaaS Development

# INaaS – Integration as a Service

Azure Integration Services:

Logic Apps

API Management

Service Bus

Use case:

“When a shop volunteer logs a donated item, the integration layer triggers pricing, records the donation in Salesforce, and notifies the regional manager.”

# BPaaS – Business Process as a Service

3-year BPaaS roadmap:

| Year  | BPaaS Process                          |
| ----- | -------------------------------------- |
| **1** | Legacy donation workflow automation    |
| **2** | Shopify Plus e-commerce fulfilment     |
| **3** | Volunteer onboarding & rota automation |

BPaaS market: $63.3B (2023) → $92.9B (2028)

# Sustainability Evaluation

Energy Efficiency

| Environment    | PUE         |
| -------------- | ----------- |
| CVS On-prem    | **1.8–2.0** |
| Azure UK South | **1.12**    |

Azure is 40% more efficient.

Microsoft Commitments
Carbon negative by 2030

Remove historical emissions by 2050

100% renewable energy matching

Emissions Impact Dashboard (Scope 1, 2, 3)

Critical Evaluation
“Renewable claims rely on market-based RECs… may overstate real-world impact.”

Even so:

Cloud utilisation: 60–80%

On-prem utilisation: 15–20%

Net environmental benefit is significant.

# Conclusion

CVS’s migration to Microsoft Azure is:

Financially sound

Operationally necessary

Environmentally responsible

It replaces £14.9M/year failing legacy IT with £1.2M/year cloud spend, enabling:

Unified CRM, HR, Payroll

National e-commerce

Automated donation workflows

Real-time analytics

Sustainable operations

Cloud migration is not just a technology upgrade—
It is the mechanism through which CVS funds the next chapter of its charitable mission.

# References

All references from your report and presentation are included here in standard academic format.
