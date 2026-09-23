# DAY-13-LAB
# LAB 13 — DOCUMENT-GROUNDED QUESTION ANSWERING

**Student:** Bhumika Mehra
**Programme:** BBA Aviation Management
**Course:** Generative AI for Business
**Date:** 22 September 2026
**AI Tool:** ChatGPT

## Objective

To understand how document-grounded AI can provide more traceable answers by using a specific source document instead of relying on general assumptions.

## Source Document

**Title:** Fictional Airline Passenger Refund and Cancellation Policy
**Organisation:** Fictional Airline

**Topics Covered:**

* Refund eligibility
* Processing time
* Required documents
* Cancellation conditions
* Exceptions
* Passenger procedures

## Activities Completed

### 1. Ungrounded Question Answering

A passenger refund and cancellation question was given to AI without providing the policy document. The answer contained general information, but several claims were unsupported.

### 2. Grounded Question Answering

The same question was answered using the supplied policy document. The prompt required exact policy information, page/section citations and no outside knowledge.

### 3. Claim Verification

The following verification process was used:

**Claim → Source → Match → Context → Action**

Important claims were checked against the original policy.

### 4. RAG Risk Audit

Risks identified included:

* Outdated documents
* Wrong document
* Missing information
* Incorrect retrieval
* Weak citations
* Missed exceptions
* Unsupported claims
* Privacy risks
* Missing human approval

## Key Learning

Document grounding makes AI answers more traceable, but it does **not guarantee correctness**. Citations must be checked against the original document and surrounding context.

If information is missing, the AI should state:

**“Not found in the supplied policy.”**

## Conclusion

This lab demonstrated that AI should use reliable source documents for important aviation information. Human verification and authorised approval remain necessary before taking operational action.

## AI-Use Disclosure

ChatGPT was used to generate and compare ungrounded and grounded answers. Important claims were checked against the original policy document, and unsupported information was corrected or removed.
