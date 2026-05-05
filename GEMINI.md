# AI Consultant Team - Gemini Project Workspace

This workspace contains the strategic blueprint and agent definitions for an autonomous AI consulting agency focused on helping Taiwanese Small and Medium Businesses (SMBs) adopt AI technologies.

## Project Overview

The project aims to build an "AI-Only" consultant business where specialized AI agents handle lead generation, sales, strategy assessment, technical implementation, and operations.

- **Primary Blueprint:** `ai_consultant_team_plan_copilot.md` contains the comprehensive organizational plan and agent ecosystem definitions.
- **Target Market:** Taiwanese SMBs (Manufacturing, Retail, Logistics).
- **Core Technology:** Built to be executed using the Gemini CLI, leveraging specialized `SKILL.md` personas.

## Directory Structure

- `/agents/`: Contains subdirectories for each specialized agent in the ecosystem.
  - Each agent directory contains a `SKILL.md` file which defines the agent's **Identity**, **Core Mission**, **Critical Rules**, and **Technical Deliverables**.
- `/biz_plan/`: Contains business strategy, outreach templates, and planning documents.
- `README.md`: Basic startup instructions.

## Key Agents

| Agent | Purpose |
| :--- | :--- |
| **Lead Intelligence** | Web scraping and scoring for AI readiness in TW SMBs. |
| **Strategy Assessment** | Analyzing business processes and generating ROI roadmaps. |
| **POC Development** | Rapid prototyping and model validation ("Seeing is Believing"). |
| **Solution Design** | Architecting technical solutions and vendor selection. |
| **Cold Email Automation** | Personalized outreach and follow-up management. |

## Development & Usage Conventions

### 1. Working with Agents
When modifying or adding agents:
- Follow the structure defined in existing `SKILL.md` files (Frontmatter with `name` and `description`, followed by Markdown sections).
- Adhere to the specific cultural context (e.g., mentioning "老闆" - the boss, focusing on TWD, and traditional Taiwanese business values).
- Ensure "Critical Rules" are clearly defined to prevent hallucination and maintain business pragmatism.

### 2. Running the System
The project is designed to be interacted with via the Gemini CLI:
```bash
gemini --approval-mode=yolo
```
You can invoke specific agents by referencing their `SKILL.md` or by activating their skills if they are registered as such in the CLI configuration.

### 3. Documentation Style
- Use Markdown for all new strategy and technical documents.
- Maintain a professional, senior consultant tone that balances technical expertise with business value.

## Important Reference Files
- `ai_consultant_team_plan_copilot.md`: The "Source of Truth" for the entire agency structure.
- `agents/*/SKILL.md`: The behavioral definitions for every "employee" in the agency.
