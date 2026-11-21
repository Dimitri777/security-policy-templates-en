# Data Classification and Handling Policy

**Document ID:** ISP-005  
**Version:** 1.0  
**Effective Date:** [Date]  
**Owner:** [CISO / Data Protection Officer]

## 1. Purpose

To define how information assets are classified and the corresponding handling requirements.

## 2. Classification Levels

| Level          | Description                                      | Examples                          |
|----------------|--------------------------------------------------|-----------------------------------|
| **Public**     | Information intended for public disclosure       | Marketing materials, public website |
| **Internal**   | Information for internal use only                | Internal procedures, org charts   |
| **Confidential** | Sensitive business or personal data            | Customer data, contracts, financials |
| **Restricted / Secret** | Highly sensitive, severe impact if disclosed | Authentication secrets, strategic plans, large volumes of PII |

## 3. Handling Requirements (Summary)

- **Public** — no special restrictions
- **Internal** — do not share outside the organization without approval
- **Confidential** — encrypt in transit and at rest, limited access, secure disposal
- **Restricted** — strong encryption, strict need-to-know, enhanced monitoring, secure disposal with certificate of destruction where required

## 4. Responsibilities

Data Owners are responsible for classifying the information under their control and ensuring appropriate handling.
