# Manuscript-ready Methods text

## AI-supported educational intervention

The AI-supported educational intervention was delivered through a researcher-configured Custom GPT accessed by students through a web browser in the ChatGPT environment. The Custom GPT was configured using the standard Custom GPT setup workflow. The intervention did not involve the development of a separate web application, a custom user interface, or a researcher-operated integration with the OpenAI API. The researcher entered the intervention instructions and educational content into the Custom GPT configuration fields using the standard setup interface.

The intervention consisted of six synchronous 90-minute sessions. During the first 60 minutes, students in both groups received the common educational component from the same instructor. During the final 30 minutes of each session, students in the intervention group interacted with the Custom GPT using one of six standardized acute myocardial infarction (AMI) scenarios. The AI-supported activity was organized into three phases: (1) simulated-patient role-play and history-taking, during which clinical information was disclosed progressively in response to students' questions; (2) clinical reasoning and decision-making, during which students summarized and interpreted findings, identified priorities, and justified their decisions; and (3) structured formative feedback and debriefing using a predefined eight-section framework.

The Custom GPT instructions constrained the interaction to the assigned scenario, prohibited the invention or alteration of clinical findings, discouraged premature diagnostic answers, and required unsafe or incomplete reasoning to be challenged through focused prompts. The six scenarios, system-level instructions, phase-specific prompt architecture, reasoning branches, feedback rubric, session schedule, and fidelity procedures are provided in the public repository [insert DOI/URL after release].

The AI-generated feedback was used solely for formative educational purposes. It was not used to calculate or replace any formal study outcome. Because the intervention was delivered through a hosted generative-AI service, exact wording may vary across sessions and over time; reproducibility was therefore defined at the level of the intervention configuration, scenario content, interaction sequence, timing, and feedback framework rather than identical token-by-token outputs.

## Technical details to verify before submission

Only add the following details if supported by contemporaneous study records:
- Exact model name/version displayed in the Custom GPT configuration during the intervention.
- Whether students accessed the Custom GPT through a shared link, institution-managed accounts, or individual ChatGPT accounts.
- Any account or subscription requirements that materially affected access.
- Whether the Custom GPT was published as private, link-accessible, or otherwise restricted.

Do not report API temperature, top-p, token limits, API usage, token counts, or a custom application architecture: these do not describe the implementation reported by the researcher.
