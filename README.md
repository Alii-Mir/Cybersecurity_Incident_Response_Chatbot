# Cybersecurity Incident Response Chatbot

## Overview

- Less than 30% of orgs have cyber incident response plans. We want to fill this gap by an AI Demo solution.

- Auto-generate cyber incident response playbooks using LLMs & customer + industry-standard data

## Public Cybersecurity Playbook Resources/Standards

- MITRE ATT&CK: attackers tactics techniques

- NIST SP 800‑61 Rev 2/3: Incident Response Guide: 6 IR lifecycle phases (Preparation → Lessons Learned)

- CISA IR Resources: US Gov advisories for incident scenarios and response playbooks

- UK NCSC Guidance: UK step‑by‑step incident management best practices

- Industry Compliance (SOC 2, ISO 27001, NIST CSF): Frameworks ShadowHQ aligns with to prove security & process rigor

## Data

* Reference: https://huggingface.co/datasets/agamage/incident-response-playbook-samples

<img width="1664" height="846" alt="image" src="https://github.com/user-attachments/assets/7e1c294e-3471-4b92-a775-5d7122678229" />


- Curated Data:

<img width="1653" height="281" alt="image" src="https://github.com/user-attachments/assets/5ae1a04a-d490-4582-beb9-78d4ecdc7390" />

### Model General Config:

-   Model: “llama-3.3-70b-versatile”
-   API URL: https://api.groq.com/openai/v1/chat/completions
-   Randomness (Temperature): 0.2
-   Timeout: 30 Sec.
-   No. of context examples: 5

The Chatbot Demo:

<img width="1856" height="889" alt="image" src="https://github.com/user-attachments/assets/f842ca5f-ba35-4f93-a189-8af029e20b68" />

 











