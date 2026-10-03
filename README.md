# MalGEN

This repository contains the 120 adversarial intents used by the MalGEN framework for malware sample generation, along with agent prompt templates.

## Repository Contents

- [`malgen_adversarial_intents.csv`](malgen_adversarial_intents.csv): The complete list of 120 adversarial intents and their identifiers.
- [`PROMPTS/`](PROMPTS/): Prompt templates for the framework, described below.

| File | Description |
| --- | --- |
| `common_system.txt` | Shared instructions for all agents. |
| `planner_system.txt` | System instructions for the Task Planner Agent. |
| `planner_user.txt` | Input template for decomposing an intent into subtasks. |
| `developer_system.txt` | System instructions for the Developer Agent. |
| `developer_user.txt` | Input template for implementing individual subtasks. |
| `integrator_system.txt` | System instructions for the Code Integration Agent. |
| `integrator_user.txt` | Input template for integrating generated components. |
| `single_agent_system.txt` | System instructions for the single-agent baseline. |
| `single_agent_user.txt` | Input template for implementing an intent using a single agent. |
