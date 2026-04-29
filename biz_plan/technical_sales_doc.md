# Technical Sales Document (Sales Engineer)
*Focus: Discovery, Demo Engineering, and POC Scoping*

## 1. Technical Discovery Checklist
*   **Stack Analysis:** What is the current data residency (On-prem, Cloud, Hybrid)?
*   **Integration Points:** Are there legacy APIs or is it mostly structured SQL data?
*   **Aha Moment Target:** Identify the *one* manual process that, if automated, would convince the CTO. (e.g., "Automated RFP analysis in 30 seconds instead of 4 hours.")

## 2. Demo Storyboard: "The Agent in Action"
1.  **Quantify the Pain:** "You told us your legal team reviews 50 contracts a day manually."
2.  **Show the Outcome:** Show the "AI Auditor Dashboard" where 48 contracts are pre-flagged for risk.
3.  **Reverse into the How:** Only after they see the dashboard do we show the vector database and the RAG (Retrieval-Augmented Generation) pipeline.

## 3. AI POC Scoping Template
*   **Problem Statement:** Prove the AI Agent can categorize support tickets with 95% accuracy in 2 weeks.
*   **Success Criteria:** Must integrate with Zendesk API; must handle 500 tickets/hour; must have a "human-escalation" flag.
*   **Decision Gate:** GO / NO-GO meeting on Day 14 based on accuracy benchmarks.
