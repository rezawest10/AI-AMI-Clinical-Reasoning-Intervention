# Custom GPT Setup and Reconstruction Guide

## Scope

This guide describes how the AI-supported AMI clinical reasoning intervention can be reconstructed as a Custom GPT using the standard ChatGPT configuration interface. It is intended to support methodological transparency and protocol-level reproducibility.

This repository does not contain the source code of ChatGPT, the underlying OpenAI model, or a separately developed web application. The reconstruction process described here reproduces the educational intervention architecture rather than the proprietary ChatGPT platform.

## Standard Configuration Workflow

1. Open ChatGPT in a web browser and navigate to the GPT creation and configuration interface available to the account.

2. Create a new GPT using the standard Custom GPT builder.

3. Enter the intervention instructions documented in the system-level prompt section of `Intervention_Protocol.md` into the GPT's Instructions field.

4. Make the six standardized AMI scenario cards available to the GPT. Depending on the reconstruction approach, these materials may be incorporated into the Instructions field or uploaded as knowledge files. The selected approach should preserve the scenario content and disclosure rules.

5. Configure the GPT to follow the three predefined intervention phases:
   - Phase 1: Simulated Patient and History-Taking.
   - Phase 2: Clinical Reasoning and Decision-Making.
   - Phase 3: Structured Feedback and Debriefing.

6. Ensure that only one standardized AMI scenario (S1–S6) is active during each simulated session, consistent with the intervention protocol.

7. Review the configuration against the operational constraints, clinical reasoning branches, feedback framework, and intervention fidelity checklist documented in `Intervention_Protocol.md`.

8. Test each scenario using standardized inquiry examples to assess progressive information disclosure, scenario consistency, prevention of fabricated clinical findings, appropriate reasoning prompts, and delivery of the predefined eight-section feedback.

9. Configure participant access and distribute the access route in accordance with the applicable institutional requirements and approved study procedures.

## Historical Accuracy and Interpretation

For retrospective reporting of the completed study, only configuration steps, settings, and implementation procedures supported by contemporaneous study records should be described as having been used.

This guide is a reconstruction aid intended to facilitate future implementation of the intervention. It must not be interpreted as evidence that every listed configuration step, access permission, knowledge-file arrangement, or publication setting was necessarily used during the original study.

Where historical configuration details cannot be verified, they should be explicitly reported as unavailable rather than inferred from the proposed reconstruction workflow.

## Original Implementation Details to Verify, If Records Are Available

The following information may be retrieved from contemporaneous study records, screenshots, or other available documentation:

- Exact Custom GPT name and description.
- Exact model or model version selected or displayed during the study.
- Method used to provide participants with access to the Custom GPT.
- Whether the scenario cards were entered into the Instructions field or uploaded as knowledge files.
- Access and privacy settings used during the intervention.
- Dates on which the Custom GPT was configured and used.

Unverified historical settings should not be presented as confirmed implementation details.

## Reproducibility Statement

The intervention can be reconstructed at the protocol level using the materials provided in this repository, including the intervention instructions, standardized AMI scenarios, inquiry–response matrices, clinical reasoning branches, structured feedback framework, and six-session implementation schedule.

Because ChatGPT is a hosted generative AI service and its underlying models and interface may change over time, exact replication of individual AI responses cannot be guaranteed. Reproducibility should therefore be evaluated according to adherence to the predefined educational architecture, scenario content, interaction sequence, timing, and feedback framework.
