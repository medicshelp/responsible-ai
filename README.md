# Responsible AI at Medics Help

How the AI in [Medics Help](https://medics.help) is designed: what it does, what it does not do and the rules we follow.

> **Stage: in development.** Medics Help is not live yet. This document describes how we are building the product and the commitments we make before launch. Our first cohort starts in early 2027. Where something is planned rather than done, we say so.

## What the AI does

- Plays patients, colleagues and examiners in practice conversations, by voice.
- Scores answers against the criteria examiners use, and explains every score.
- Answers questions about recognition using only official sources, and shows each source.

## What the AI does not do

- It never decides who gets hired. People at the hospital make that decision.
- It never gives medical advice to patients.
- It never replaces the official exam or the decision of the authority.
- Medics Help is an education and career platform. It is not a medical device, and training scenarios must not be used for patient care.

## Who decides

**People decide, not the AI.**

- Hiring decisions are always made by people at the hospital.
- Scores are guidance, not decisions. Every score is explained, and candidates can dispute any result. A person reviews every flagged answer or score.
- Recognition is decided by the competent authority. Our guidance is general information based on official sources and does not replace that decision.
- Every AI conversation is clearly marked as AI.

## How we check quality

- Every case is written or reviewed by doctors or nurses who passed the exams themselves.
- Before launch we compare the trainer's scores with scores from experienced examiners on the same answers, and we will publish how often they agree.
- Navigator answers show their source and the date it was last checked.
- AI output may contain errors. It supports, and never replaces, human judgement.

## Data and consent

- Data is stored in data centres in the European Union, encrypted in transit and at rest, under the GDPR.
- We collect as little as we need. We do not collect patient data or candidates' own health records.
- Your data is never used to train third-party models.
- Profiles are private by default. A candidate's progress is shared with an employer only with the candidate's explicit consent, and that consent can be withdrawn at any time.
- Candidates can export their data, hide their profile or delete their account at any time, and decide whether voice recordings are kept.
- Every employer signs a data processing agreement.

## Technology

- Voices of the virtual patients: ElevenLabs text-to-speech.
- Conversation and scoring: large language models from established providers, with data processed in the EU wherever possible.
- We will publish the full list of service providers (sub-processors) before launch.

## Rules we are building for

| Rule | What it means for us |
|---|---|
| **EU AI Act** | AI that evaluates learning or supports hiring counts as high-risk. These obligations apply from 2 December 2027, and we build for them now: human oversight, documented risk management, logged model versions and the right to contest a result. |
| **GDPR** | EU hosting only, encryption, minimal data, clear legal bases (contract and consent), and the rights of access, correction, deletion, restriction, portability and objection. |
| **WHO Global Code of Practice on the International Recruitment of Health Personnel** | We do not run recruitment campaigns in countries on the WHO list of nations with critical health workforce shortages, and we support people who have already chosen to move. |
| **Employer pays principle** | Doctors and nurses never pay placement fees. Employers cover recruitment costs. |

## Contact

Questions, concerns or a score you think is wrong: [info@medics.help](mailto:info@medics.help).

Website: [medics.help](https://medics.help) · LinkedIn: [Medics Help](https://www.linkedin.com/company/medicshelp)

## Licence

This document is licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). See [LICENSE](LICENSE). You may share and adapt it with attribution to Medics Help.

The Medics Help name and logo are not covered by this licence.
