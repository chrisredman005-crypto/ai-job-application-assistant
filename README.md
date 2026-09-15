[Project 1 — AI Job Application Assistant README.md](https://github.com/user-attachments/files/32253149/Project.1.AI.Job.Application.Assistant.README.md)
# AI Job Application Assistant

**Portfolio Project 1 | AI & Automation**

**Status:** Completed — Version 2 tested

## Overview

I built an evidence-based AI Job Application Assistant that analyses a job or apprenticeship advert against a candidate CV.

The workflow identifies:

- Job requirements
- Existing candidate experience
- Transferable skills
- Relevant courses and training
- Development gaps
- Evidence of career development
- Interview preparation
- Areas for further development

The main goal was to create a reusable AI workflow rather than rely on a one-off AI response.

---

## The Problem

Job applicants may have useful professional experience that does not exactly match the wording of a job advert.

For example, someone may have experience with:

- CRM systems
- customer communication
- research
- data management
- sales or marketing
- Excel
- financial services

while still lacking technical skills such as Python, SQL or automation.

The assistant was designed to identify both the candidate's existing strengths and genuine development gaps.

---

## How I Built It

### Version 1

I first created a basic prompt that compared a job advert with a candidate CV.

It identified:

1. Job requirements
2. Candidate experience
3. Relevant courses and training
4. Matching skills
5. Transferable skills
6. Missing skills
7. Overall suitability
8. Development areas
9. Interview preparation
10. Application recommendation

### Test #001 — Mizuho Data & AI Apprentice

I tested Version 1 against a Data & AI apprenticeship in financial services.

The test identified existing transferable experience including:

- Financial-services experience
- Salesforce CRM
- Customer communication
- Research
- Email marketing
- Excel forecasting
- AI training

It also identified technical areas that were not demonstrated on the CV, including:

- Python
- SQL
- Machine learning
- Power BI/data visualisation
- Professional data-analyst experience

This showed that the assistant needed clearer rules for distinguishing different types of evidence.

---

## Version 2

I improved the workflow by introducing explicit evidence classifications:

| Classification | Meaning |
|---|---|
| **Direct Match** | The CV clearly demonstrates the required skill |
| **Transferable** | Related experience could transfer to the role |
| **Relevant Learning** | The subject has been studied but practical/professional experience is limited |
| **Development Gap** | The required skill is not demonstrated |
| **Not Enough Evidence** | There is insufficient information to make a reliable assessment |

I also added rules to:

- Separate courses from professional experience
- Recognise transferable experience
- Avoid inventing qualifications or achievements
- Assess career development using observable evidence
- Avoid penalising candidates for skills an apprenticeship is designed to teach
- Explain potential business value of transferable experience

---

## Test #002 — AI Digital Growth Apprentice

I then tested Version 2 against a different AI-related apprenticeship focused on AI, automation, digital growth, CRM and marketing.

The assistant identified strong existing evidence in areas such as:

- Sales
- Business development
- Salesforce CRM
- Email marketing
- Lead generation
- Prospect research
- Customer relationships
- Campaign and lead monitoring

It also identified development areas including:

- Practical AI automation
- Workflow implementation
- Automation platforms and integrations
- HubSpot
- Practical AI implementation
- AI/data governance
- Measuring automation outcomes

This demonstrated that the improved workflow could adapt its analysis to a different type of AI role.

---

## What This Project Demonstrates

This project demonstrates practical experience with:

- Generative AI
- Prompt design
- AI-assisted workflows
- Requirement analysis
- Evidence-based reasoning
- Transferable-skills analysis
- Workflow iteration
- Testing and evaluation
- Responsible handling of uncertainty
- Identifying AI and automation opportunities

It also demonstrates that I understand the difference between **learning about AI** and having **professional AI implementation experience**.

---

## What I Learned

The main lesson was that useful AI output requires more than simply asking an AI model a question.

The workflow became more reliable when I introduced:

**Clear instructions → Evidence rules → Classification → Testing → Evaluation → Improvement**

Testing the workflow against two different roles also showed why an AI solution needs to be tested against different real-world situations.

---

## Limitations

The current project is a **prompt-based AI workflow**, not a fully automated software application.

Current limitations include:

- It depends on the quality of the supplied CV and job advert.
- It does not independently verify every CV claim.
- It does not replace an employer's recruitment decision.
- It currently requires the user to provide the relevant information.

These limitations are intentionally documented rather than hidden.

---

## Future Development

The next technical version could turn this workflow into an actual application using:

- Python
- Structured CV/job inputs
- Automated requirement extraction
- APIs
- Data storage
- Workflow automation
- Automated scoring
- Document generation

This would move the project from a prompt-based workflow toward a more complete AI/automation application.

---

## Evidence

The development process is documented in the following files:

| File | Purpose |
|---|---|
| `01_Project_Brief.pdf` | Project purpose and objectives |
| `04_Version_1_Prompt.txt` | Original workflow |
| `05_Test_001_Mizuho.pdf` | First real-world test |
| `06_Version_2_Prompt.txt` | Improved workflow |
| `07_Test_002_AI_Digital_Growth.pdf` | Second real-world test |
| `08_Testing_and_Evaluation.pdf` | Testing, improvements and limitations |
| `09_Final_Portfolio_Case_Study.pdf` | Employer-facing case study |

---

## Final Outcome

**Project 1 is complete at the prompt/workflow stage.**

I designed an AI application, tested it against two different real-world apprenticeship roles, evaluated the results, identified weaknesses and improved the workflow.

The next stage of my portfolio will focus on building a more technical AI/automation project and developing practical skills in areas such as Python, data and automation.
