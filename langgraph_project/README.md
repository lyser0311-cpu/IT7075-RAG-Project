# LangGraph Alert Triage Agent

This project focuses on building a cybersecurity alert triage agent using LangGraph. The agent reviews security alerts and decides whether they should be escalated or closed. I tested the original agent using 12 security alerts, then added a context-checking node to improve how it handles routine activities. I also created a more cautious version to compare the results. Through testing, I was able to see how different decisions affect the number of real threats caught, missed incidents, and unnecessary escalations.

## Project Files

- **agent_notebook.ipynb** — Completed notebook containing the LangGraph agent, testing, and results.
- **my_alerts.json** — 12 labelled security alerts used for testing.
- **results_mine.csv** — Results comparing the three versions of the agent.
- **SOURCES.md** — References and course materials used for the project.
