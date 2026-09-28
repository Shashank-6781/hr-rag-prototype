# HR Policy Q&A Prototype

This prototype integrates the Gemini API to demonstrate a Retrieval-Augmented Generation (RAG) pipeline for HR policies. API keys are strictly handled via environment variables (`GEMINI_API_KEY`).

## Example Execution
**Input:** How many PTO days do I get per month?
**Output:** Based on the provided context, employees accrue 1.5 days of Paid Time Off (PTO) per month.
----------------------------------------
**Input:** Can I work from home 4 days a week?
**Output:** No, based on the provided context, remote work is only allowed up to 2 days per week for standard employees.
----------------------------------------
**Input:** What is the company policy on traveling first class?
**Output:** I cannot answer this based on the provided HR policies.
----------------------------------------