# AI Governance Risk Evaluator

A practical Responsible AI, privacy and security governance project that evaluates mock LLM outputs for privacy leakage, sensitive data exposure, confidential information, unsupported claims, policy conflicts and human review requirements.

This project demonstrates how AI outputs can be assessed using a structured governance workflow and converted into an AI risk register and executive-ready assurance report.

## Project Summary

AI governance is not only about principles. Organisations need repeatable ways to evaluate AI outputs, identify risks, document review decisions and retain evidence for oversight.

This project uses simulated LLM output data to demonstrate a practical AI assurance workflow.

The workflow connects:

```text
AI Output → Privacy Risk Check → Policy/Safety Check → Human Review Flag → AI Assurance Report
```

## Why This Project Matters

As organisations adopt generative AI and internal LLM workflows, they need practical controls for privacy, security, compliance and governance.

AI outputs can create risk when they:

* Reveal personal data
* Include sensitive information
* Expose confidential internal information
* Provide unsupported legal, privacy, security or compliance claims
* Conflict with organisational policy
* Produce security advice without review
* Require human approval before business use

This project demonstrates how those risks can be identified, scored and reported using a lightweight Python-based workflow.

## Key Features

* Mock LLM output evaluation dataset
* AI risk policy register
* AI review control register
* Privacy leakage checks
* Sensitive data risk flagging
* Confidential information flagging
* Unsupported claim detection flag
* Policy conflict flagging
* Human review requirement flag
* AI risk scoring
* AI risk rating
* Required review assignment
* Recommended decision logic
* Python-generated AI risk register
* Executive-ready AI governance report

## Repository Structure

```text
ai-governance-risk-evaluator/
│
├── data/
│   ├── mock_llm_outputs.csv
│   ├── ai_risk_policy.csv
│   └── review_controls.csv
│
├── src/
│   └── generate_ai_governance_report.py
│
├── reports/
│   ├── ai_risk_register.csv
│   └── ai_governance_summary.md
│
├── README.md
├── requirements.txt
└── .gitignore
```

## Input Files

### `data/mock_llm_outputs.csv`

Contains simulated AI output review records.

Each record includes:

* Output ID
* Use case
* Business area
* User prompt
* LLM output
* Personal data flag
* Sensitive data flag
* Confidential information flag
* Unsupported claim flag
* Security advice flag
* Policy conflict flag
* Human review requirement
* Model owner
* Current status

### `data/ai_risk_policy.csv`

Defines practical AI governance policy requirements.

Policy areas include:

* Privacy leakage
* Sensitive data handling
* Confidential information
* Unsupported claims
* Security advice
* Policy conflict
* Human review
* AI assurance evidence

### `data/review_controls.csv`

Defines review controls that support AI assurance.

Control areas include:

* Privacy review
* Security review
* Policy alignment
* Human-in-the-loop review
* Evidence retention
* Continuous improvement

## Generated Outputs

Running the Python script generates two portfolio-ready outputs.

### `reports/ai_risk_register.csv`

A structured AI risk register that includes:

* AI risk score
* AI risk rating
* Required review
* Recommended decision
* Governance attention flag

### `reports/ai_governance_summary.md`

An executive-style AI governance report that summarises:

* Total AI outputs reviewed
* High and Critical AI risk outputs
* Outputs containing personal data
* Outputs containing sensitive data
* Outputs with policy conflicts
* Outputs requiring human review
* Governance attention items
* AI risk policy areas
* Review controls
* Recommended actions

## How the Risk Logic Works

The script assigns risk points for AI output risk indicators such as:

```text
Personal Data + Sensitive Data + Confidential Information + Unsupported Claim + Security Advice + Policy Conflict + Human Review Requirement
```

It then assigns an AI risk rating:

```text
Critical → Reject or block until reviewed, corrected and evidenced
High → Do not use without human review and documented approval
Medium → Use with caution and retain review evidence
Low → Approved for low-risk use with routine monitoring
```

## Example Workflow

```text
Mock LLM Outputs
        ↓
AI Risk Policy Register
        ↓
Review Control Register
        ↓
Python Risk Evaluation Script
        ↓
AI Risk Register
        ↓
Executive AI Governance Summary
```

## Example Governance Questions Answered

This project helps answer questions such as:

* Which AI outputs create privacy leakage risk?
* Which outputs contain sensitive data?
* Which outputs expose confidential information?
* Which outputs conflict with policy?
* Which outputs require human review?
* Which business areas generate higher-risk AI outputs?
* Which outputs should be rejected, reviewed or approved?
* What evidence should be retained for AI assurance?

## Skills Demonstrated

This project demonstrates practical capability in:

* Responsible AI governance
* AI risk evaluation
* Privacy-aware AI review
* AI assurance evidence
* Human-in-the-loop governance
* Policy alignment checks
* Security and privacy risk assessment
* Risk-based decision logic
* Executive reporting
* Python reporting automation
* AI governance documentation

## Career Relevance

This project aligns with roles such as:

* Responsible AI Analyst
* AI Governance Analyst
* Cybersecurity GRC Analyst
* Information Security Analyst
* Data Privacy Analyst
* Risk and Compliance Analyst
* Security Governance Analyst
* Data Governance Analyst

## Practical Value

This project shows how AI governance can be made structured, measurable and evidence-ready.

It demonstrates the ability to:

* Evaluate AI outputs for governance risk
* Identify privacy and security issues in AI workflows
* Link AI risks to review controls
* Assign human review requirements
* Produce assurance evidence
* Communicate AI risk in business-friendly language

## Future Improvements

Planned improvements include:

* Add Streamlit dashboard
* Add AI risk heatmap
* Add prompt risk classification
* Add AI use-case inventory
* Add model/system owner register
* Add NIST AI RMF mapping
* Add ISO/IEC 42001 mapping
* Add privacy impact review workflow
* Add red-team test case examples
* Add Power BI-ready output
* Add screenshots of generated reports

## Disclaimer

This project uses simulated AI output data for portfolio and learning purposes. It does not contain real personal data, client data, employer data, confidential information or production AI system outputs.

## Author

**Parisa Shojaei**

Cybersecurity GRC · Cloud Security · Privacy Governance · Risk Analytics · AI Assurance | Turning risks into audit-ready evidence
