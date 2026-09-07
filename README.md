# Serverless Inbound Lead Gateway & CRM Automation Pipeline

> An enterprise-grade, serverless lead capture gateway featuring client-side Google Identity Services (OAuth 2.0), an asynchronous AJAX ingestion mechanism, and an event-driven automation orchestration pipeline syncing records to Airtable and triggering transactional HTML communications.

**Live Gateway**: [sumitkannake.me](https://sumitkannake.me)  
**Author**: Sumit Kannake  
**Role**: Process Automation & Business Analytics Specialist  

---

## 1. Executive Summary & Problem Scope

Traditional website contact forms rely on standard HTTP redirects, create high conversion friction, and frequently ingest invalid or mistyped contact information. In addition, inbound inquiries frequently sit unattended in standard email inboxes rather than being structured immediately into a CRM.

This project implements an end-to-end operational architecture that resolves these bottlenecks:
* **Zero-Redirect Experience**: Frictionless client intake without page reloads using native JavaScript asynchronous `fetch()`.
* **Identity Verification**: One-click Google Identity OAuth 2.0, auto-populating validated lead metadata via client-side JWT decoding.
* **Immediate CRM Synchronization**: Event-driven webhook distribution into an operational relational database within seconds.
* **Instant Client Engagement**: Automated, branded transactional HTML confirmation receipts dispatched via the Gmail API.

---

## 2. System Architecture
