# Making Agents Work — Lab Completion

**Student:** Rishikesh Munnaluri  
**Course:** CS3235 — Working with LLMs  
**Source repository:** `svhari/AAI_primer`

## Work completed

The original Session 1–4 notebooks are preserved. My modified, executable versions are available in the `completed/` folder.

| Session | Topic | Modification |
|---|---|---|
| 1 | Prediction → Agentic Action | Completed the incomplete action flow with a runnable spam-classifier + action simulation. |
| 2 | Function / Tool Calling | Added a runnable JSON-schema tool-call simulation with a weather tool. |
| 3 | ReAct Loop | Implemented a multi-step Thought → Action → Observation → Final Answer workflow. |
| 4 | RAG | Extended the fixed-context example into a small retriever over multiple syllabus snippets. |

## Verification

All four modified notebooks were executed locally and completed successfully without external API keys.

### Session 1 result
`SPAM` was detected with high confidence and the agent selected `MOVE_TO_TRASH` with a generated reply.

### Session 2 result
The simulated agent selected `get_weather` for Bangalore and returned `27C, Sultry`.

### Session 3 result
The ReAct workflow called the weather tool for Mumbai and Delhi and concluded that Mumbai is warmer (`32C` vs `28C`).

### Session 4 result
The retriever selected the relevant syllabus snippet and answered that the ML midterm is on **March 15th, 2026**.

## Completed notebooks

- `completed/Session_1_Completed_Rishikesh.ipynb`
- `completed/Session_2_Completed_Rishikesh.ipynb`
- `completed/Session_3_Completed_Rishikesh.ipynb`
- `completed/Session_4_Completed_Rishikesh.ipynb`

> Note: The completed versions use deterministic offline simulations where appropriate so the repository contains no API keys or secrets and can be run by the evaluator directly.
