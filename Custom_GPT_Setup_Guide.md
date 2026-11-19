#GPT setup and reconstruction guide

## Scope

This guide documents how the intervention can be reconstructed as a Custom GPT using the standard ChatGPT configuration interface. It does not claim that the original ChatGPT service or its underlying source code is included in this repository.

## Standard configuration workflow

1. Open ChatGPT in a web browser and navigate to the GPT creation/configuration area available to the account.
2. Create a new GPT using the standard builder/configuration interface.
3. Enter the intervention's system-level instructions from `Intervention_Protocol.md` into the GPT's instruction field.
4. Add the six standardized AMI scenario cards from the protocol as the reference knowledge/content available to the GPT, or place the relevant scenario content directly in the instructions if that matches the configuration being reconstructed.
5. Configure the GPT to follow the three intervention phases:
   - Phase 1: simulated patient and history-taking.
   - Phase 2: clinical reasoning and decision-making.
   - Phase 3: structured formative feedback and debriefing.
6. Review the configuration against the operational constraints and fidelity checklist in `Intervention_Protocol.md`.
7. Test each scenario with standardized test questions to confirm progressive disclosure, scenario consistency, prevention of invented findings, appropriate reasoning prompts, and the eight-section feedback format.
8. Restrict access and provide the access route to participants in accordance with the study's approved procedures and institutional requirements.

## Historical accuracy

For a retrospective description of the completed study, report only the steps and settings that were actually used. This guide is a transparent reconstruction aid; it must not be presented as proof that every listed setup step, access permission, knowledge-file arrangement, or publication setting was used in the original implementation.

## Items to document from original records, if available

- Exact GPT name and description.
- Exact model/version selected or displayed.
- Whether a shared GPT link was distributed or another access method was used.
- Whether scenario cards were entered in the instructions field or uploaded as knowledge files.
- Access/privacy setting used during the intervention.
- Dates on which the Custom GPT was configured and used.

If these details cannot be verified, state that they were not retained in the study records rather than inferring them.
