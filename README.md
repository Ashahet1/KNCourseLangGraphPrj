# LangGraph Projects Overview

## 1. Blog Generation from User Topics
This project leverages LangGraph to automate blog creation using open-source Large Language Models (LLMs). It structures blog generation into sequential steps:
- Initial content creation
- Iterative refinement
- Quality checking

Integrated LangSmith tracing ensures effective debugging and content quality assurance.

![image](https://github.com/user-attachments/assets/c19ceebd-2de1-4d2e-b9a3-39d172bebdfe)


## 2. AI Code Review Peer Reviewer
This tool helps developers by automatically reviewing their code using a structured workflow with LangGraph. Steps include:
- Code submission and language identification
- Structural analysis
- Issue detection (bugs, performance issues, style)
- Suggesting improvements
- Comprehensive review generation with scoring
Uses LangSmith for monitoring and optimization.

![image]([https://gemini.google.com/app/1befb3fe0cb140f8?is_sa=1&is_sa=1&android-min-version=301356232&ios-min-version=322.0&campaign_id=bkws&utm_source=sem&utm_source=google&utm_medium=paid-media&utm_medium=cpc&utm_campaign=bkws&utm_campaign=2024enUS_gemfeb&pt=9008&mt=8&ct=p-growth-sem-bkws&gclsrc=aw.ds&gad_source=1&gad_campaignid=20108148196&gclid=CjwKCAjwgb_CBhBMEiwA0p3oOMfXEFD-8z1AKmjl7NX2g0PUM2pu7HE0epfZI-tLDM5HA7K1lwCnXxoC4_8QAvD_BwE])

## 3. Technical Documentation Orchestrator & Synthesizer
This application creates technical documentation from high-level requirements through:
- Workflow orchestration (planning, content generation, reviewing, refining)
- Synthesizing detailed documentation sections, including code examples
- Iterative content refinement based on feedback (up to two iterations)

Utilizes Grok api to access open ai gpt-4o model with fallback options. LangSmith provides comprehensive debugging and performance analysis.

