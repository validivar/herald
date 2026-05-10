# HERALD — Clinical Agent Network for Sepsis Early Warning

Four AI agents communicating over A2A protocols, reading FHIR R4 
data in real-time, detecting sepsis hours before conventional systems.

## Live Demo
[https://herald-five.vercel.app/]

## Prompt Opinion Marketplace
[https://app.promptopinion.ai/marketplace/agent/019e1321-03db-7629-a39b-90b5c15f43af]

## Stack
- Claude Sonnet — Orchestrator reasoning engine
- Prompt Opinion Platform — MCP + A2A infrastructure  
- FHIR R4 — Clinical data standard
- SMART on FHIR — EHR authentication
- A2A Protocol — Inter-agent communication

## Agents
| Agent | Type | Role |
|---|---|---|
| Vitals Surveillance | MCP-001 | FHIR vitals polling, SOFA/qSOFA/NEWS2 |
| Notes Analyzer | A2A-002 | Clinical NLP, infection source detection |
| Medication Safety | A2A-003 | Antibiotic gaps, vasopressor thresholds |
| Herald Orchestrator | A2A-004 | Claude-powered synthesis + alerts |

## Hackathon
Agents Assemble — Healthcare AI Endgame by Prompt Opinion, 2026
