Final Agent List
1. Requirement Analyzer Agent
Purpose:
Converts raw feature/issue text into structured requirements.

Outputs:

Functional requirements
Non-functional requirements
Assumptions
Constraints
Dependencies
Risks
Business case
Open questions
Tools you can use:

ChatGPT
Claude
Google AI Studio (Gemini)
Azure AI Studio
SpecGPT
Notion AI
2. Product Owner / Prioritization Agent
Purpose:
Defines MVP, prioritization, sprint plan, and business value.

Outputs:

MVP scope
Future scope
Priority order
Sprint grouping
Business value summary
Release recommendation
Tools you can use:

ChatGPT
Claude
Gemini
Jira
Notion AI
Confluence
3. Technical Architect Agent
Purpose:
Creates overall technical architecture and system flow.

Outputs:

Architecture summary
Components
API flow
Data flow
Security/scalability notes
Mermaid/diagram
Tools you can use:

LangChain
CrewAI
PlantUML
Draw.io / Diagrams.net
Creately AI
Whimsical
Google AI Studio
Azure AI Studio
4. Data & Event Architecture Agent
Purpose:
Designs database and event-driven architecture.

Outputs:

Tables/entities
Relationships
Index suggestions
Topics/queues
Producers/consumers
Retry / DLQ / idempotency strategy
Tools you can use:

DBdiagram.io
PlantUML
ChatGPT
Gemini
Azure AI Studio
LangChain
CrewAI
5. Jira Story Generator Agent
Purpose:
Converts requirements into epics, user stories, and acceptance criteria.

Outputs:

Epics
User stories
Description
Acceptance criteria
Story points
Priority
Dependencies
FE/BE/QA instructions
Tools you can use:

Jira
Confluence
ChatGPT
Gemini
Notion AI
6. Frontend & UX/UI Agent
Purpose:
Handles user flow, UI/UX guidance, and frontend implementation.

Outputs:

User journey
Screen list
Validation rules
Accessibility notes
Components
Frontend code/instructions
Tools you can use:

Lovable AI
Bolt.new
Vercel v0
Replit
Cursor
Codeium
Continue.dev
Uizard
Figma AI
Penpot
Whimsical
7. Backend Developer Agent
Purpose:
Generates backend APIs, service logic, DB integration, and event handling.

Outputs:

API endpoints
Service logic
DB interaction notes
Event handling
Validation
Error handling
Backend code guidance
Tools you can use:

Cursor
Replit
Continue.dev
Codeium
LangChain
LlamaIndex
8. QA / Test Engineer Agent
Purpose:
Creates complete testing coverage.

Outputs:

Test scenarios
Positive/negative cases
Edge cases
API tests
UI tests
DB validation tests
Event-driven test cases
Regression checklist
Tools you can use:

Postman AI
Playwright
Selenium IDE
OpenTest
9. Code Review Agent
Purpose:
Reviews generated code and implementation quality.

Outputs:

Code smells
Refactoring suggestions
Performance concerns
Maintainability feedback
Best practice improvements
Tools you can use:

Semgrep
SonarQube Community Edition
Cursor
Continue.dev
10. Security & Compliance Agent
Purpose:
Reviews security, privacy, and compliance.

Outputs:

Auth/authz risks
OWASP concerns
PII/privacy notes
Secure coding recommendations
Compliance checklist
Mitigation plan
Tools you can use:

Semgrep
SonarQube Community Edition
Azure AI Studio
ChatGPT
Gemini
11. DevOps / Release Agent
Purpose:
Handles deployment and CI/CD guidance.

Outputs:

Deployment steps
Environment variables
CI/CD suggestions
Docker/container guidance
Rollback strategy
Release checklist
Tools you can use:

Replit
Vercel
Azure AI Studio
GitHub Actions templates
12. Monitoring & Observability Agent
Purpose:
Creates production monitoring/dashboard/alerting recommendations.

Outputs:

Application metrics
Infrastructure metrics
Business metrics
Logs
Traces
Alerts
Dashboard sections
SLO/SLA suggestions
Tools you can use:

Azure AI Studio
Grafana concepts
Prometheus concepts
OpenTelemetry concepts
ELK/OpenSearch concepts
13. Risk & Impact Analysis Agent
Purpose:
Analyzes delivery, dependency, and release risks.

Outputs:

Technical risks
Business risks
Dependency risks
Release impact
Mitigation actions
Tools you can use:

ChatGPT
Claude
Gemini
Notion AI
Confluence
14. Documentation Agent
Purpose:
Generates project and handover documentation.

Outputs:

Project summary
Setup guide
Architecture summary
API summary
Deployment summary
Monitoring summary
Release notes
Support notes
Tools you can use:

Mintlify
DocuWriter.ai
Notion AI
Confluence
Obsidian
15. Integration & Delivery Summary Agent
Purpose:
Consolidates all agent outputs and checks consistency.

Outputs:

End-to-end delivery summary
Requirement traceability
Coverage summary
Gaps/conflicts
Readiness assessment
Final recommendation
Tools you can use:

LangChain
CrewAI
AutoGen
LlamaIndex
ChatGPT
Gemini
16. Change Impact Analysis Agent
Purpose:
Analyzes what parts of the system are affected by a change.

Outputs:

Impacted modules
Impacted APIs
Impacted DB entities
Impacted events
Regression areas
Deployment risk
Tools you can use:

ChatGPT
Gemini
LangChain
LlamaIndex
Confluence
Jira
17. Root Cause Analysis / Incident Agent
Purpose:
Helps with incident analysis and troubleshooting.

Outputs:

Incident scenarios
Likely root causes
Impacted components
Troubleshooting steps
Recovery recommendations
Prevention recommendations
Tools you can use:

ChatGPT
Gemini
Azure AI Studio
Monitoring data
Logs/observability inputs
AI Tools Available
Here is the consolidated list from what you shared.

AI App & Workflow Builders
Lovable AI
Bolt.new
Replit
Vercel v0
LLM & Agent Development Platforms
Google AI Studio (Gemini)
OpenAI Playground
Azure AI Studio
Hugging Face Spaces
LangChain
LlamaIndex
CrewAI
AutoGen
AI Coding & Code Quality Tools
Codeium
Cursor
Continue.dev
Semgrep
SonarQube Community Edition
AI for Requirements / Docs / Analysis
ChatGPT
Claude
Notion AI
Obsidian AI plugins
SpecGPT
Jira AI plugins
Confluence AI
GitHub Copilot
Mintlify
DocuWriter.ai
AI for UI / UX / Wireframes
Lovable AI
Uizard
Figma AI
Penpot
Diagrams.net / Draw.io
Whimsical
AI for Testing / QA
Postman AI
Playwright
Selenium IDE
OpenTest
AI for Architecture / Data Modeling / Diagrams
DBdiagram.io
Creately AI
PlantUML
AI Agent UI / Demo Frameworks
Streamlit
Gradio
Chainlit
AI Search / Research
Perplexity AI
Phind
You.com
Local / Open Models / Runtimes
Ollama
LM Studio
Mistral
Groq
Best practical mapping summary
Best core tools for your hackathon
If you want the most practical stack:

UI: Streamlit
LLM: Gemini or Azure AI Studio or OpenAI
Agent orchestration: LangChain or CrewAI
Frontend support: Lovable / v0 / Bolt / Cursor
Backend support: Cursor / Replit / Continue.dev
QA: Postman AI + Playwright
Security/Review: Semgrep + SonarQube
Architecture/DB: Mermaid + DBdiagram + PlantUML
Docs: Mintlify / Notion AI / Confluence
Deployment: Replit / Vercel
Monitoring concept: Grafana/Prometheus/OpenTelemetry style outputs
Best final combo to present
You can present it like this:

Agents
Requirement Analyzer
Product Owner / Prioritization
Technical Architect
Data & Event Architecture
Jira Story Generator
Frontend & UX/UI
Backend Developer
QA / Test Engineer
Code Review
Security & Compliance
DevOps / Release
Monitoring & Observability
Risk & Impact Analysis
Documentation
Integration & Delivery Summary
Change Impact Analysis
Root Cause Analysis / Incident
Tool ecosystem
LLM layer: Gemini / OpenAI / Azure AI Studio
Agent orchestration: LangChain / CrewAI / AutoGen
UI/demo: Streamlit / Gradio / Chainlit
Dev coding: Cursor / Replit / Codeium / Continue.dev
Design: Lovable / Uizard / Figma AI / v0
Testing: Postman AI / Playwright
Quality/security: Semgrep / SonarQube
Docs/specs: Mintlify / DocuWriter / Notion / Confluence
Architecture/data: DBdiagram / PlantUML / Draw.io
Deployment: Vercel / Replit
Research: Perplexity / Phind


AI Fridays logo
TCS logoAI Friday - ChennAI   Date: 12th June 2026
SPEC Driven Development for SDLC using AI
Workbook Navigation
🧭 Evaluation Criteria
🧰 AI Tools
👥 Use case
📦 Deliverables
✅ Instructions
TCS Internal
Evaluation Criteria
The evaluation process will focus on the quality of each deliverable outlined in this document. Assessment goes beyond merely ensuring the software functions as intended. The effectiveness of AI tools and agents, as integrated across every phase of the Software Development Life Cycle, will be a primary consideration.

Every deliverable should be comprehensive, presented in a professional manner, and show clear completion. It is recommended to use AI tools to review all deliverables before finalizing them.

Maintain a comprehensive record of all prompts utilized for the creation of various deliverables. Ensure that you are logged into your tool during use so prompt history remains readily accessible.

Key Areas of Assessment
Comprehensive Application of AI: The use of AI in analysis, design, development, testing, and documentation must be demonstrated for all required outcomes.
Impactful Implementation: Evaluators will look for clear evidence of how AI technologies have positively influenced each stage of the software development process.
Deliverable Quality and Completeness: Each deliverable must be thoroughly developed, meeting all specified requirements with high quality and completeness.
Innovative Approach: Out-of-the-box thinking will be valued, especially in the creation of deliverables.
INDICATIVE LIST OF TOOLS THAT CAN BE USED
AI App & Workflow Builders

Lovable AI (Free tier)

Bolt.new (Free credits)

Replit (Free tier with AI features)

Vercel v0 (Free tier)

LLM & Agent Development Platforms

Google AI Studio (Gemini)

OpenAI Playground (Free credits)

Azure AI Studio (Free tier)

Hugging Face Spaces

LangChain (Open source)

LlamaIndex (Open source)

CrewAI (Open source)

AutoGen (Open source)

AI Coding & Code-Quality Agents

Codeium (Free)

Cursor (Free tier)

Continue.dev (Open source)

Semgrep (Free tier)

SonarQube Community Edition

AI for Requirements, Documentation & Analysis

ChatGPT (Free)

Claude (Free tier)

Notion AI (Limited free usage)

Obsidian (community AI plugins)

AI for UI / UX & Wireframe Design

Lovable AI (Free tier ✅)

Uizard (Free tier)

Figma (Free tier with AI features)

Penpot (Open source)

Diagrams.net (Draw.io AI)

Whimsical (Free tier)

AI for Testing & QA

Postman AI (Free tier)

Playwright (AI plugins)

Selenium IDE (AI extensions)

OpenTest (Open source)

AI for Architecture, Data Modeling & Diagrams

DBdiagram.io (Free tier)

Creately AI (Free tier)

PlantUML (AI assisted via prompts)

AI Agent UI / Demo Frameworks

Streamlit (Open source)

Gradio (Open source)

Chainlit (Open source)

AI Search & Research

Perplexity AI (Free)

Phind (Free)

You.com (Free AI modes)

Local / Open-Source Models & Runtimes

Ollama

LM Studio

Mistral (Open models)

Groq (Free tier)

SPEC generation

SpecGPT (spec generation with AI)

OpenAI GPT-4 (prompted for requirement/spec generation)

Notion AI (automated documentation and spec drafting)

Jira (with AI plugins for converting user stories to specs)

Confluence (integrated AI tools for technical documentation)

GitHub Copilot (for generating code-ready specifications)

Mintlify (AI-powered spec and documentation generator)

DocuWriter.ai (automated technical spec writing)

👥 Use case
AI-Assisted Action Item Tracker
Build an application that helps users capture action items, assign ownership, track progress, identify blockers, send follow-up messages, and close actions with clear completion notes. The application should support day-to-day work items created from discussions, notes, requests, reviews, decisions, reminders, or follow-ups.

The application should allow users to record each action item with a title, description, owner, due date, priority, status, source, related comments, and expected outcome. Users should be able to update progress, add remarks, mark blockers, reassign ownership, revise due dates, and maintain a history of changes until the action item is closed.

The expected demonstration flow should cover the full lifecycle: create an action item, capture required details, assign an owner, classify the action type, set priority and due date, update status, detect missing information or blockers, generate an AI-assisted action summary, draft a follow-up message, and close the action with a final completion note.

Capabilities:
Create a new action item with title, description, owner, priority, due date, source, and status.
Capture additional details such as requester, expected outcome, related notes, comments, attachment reference, dependency, and closure remarks.
Classify action items into categories such as Task, Review, Clarification, Follow-up, Decision, Approval, Update, Issue, Reminder, or Closure.
Validate whether mandatory information is available, including title, owner, due date, priority, description, and expected outcome.
Identify gaps such as missing owner, missing due date, unclear description, overdue item, duplicate item, blocked item, or pending clarification.
Allow the user to update status as New, Assigned, In Progress, Waiting, Blocked, Completed, Reopened, or Closed.
Generate an AI-assisted summary covering current status, pending action, blocker, owner, due date, and next step.
Draft follow-up messages for assignment, reminder, clarification, blocker update, progress update, closure confirmation, or escalation.
Provide a dashboard view showing open actions, overdue actions, blocked actions, completed actions, owner-wise actions, and priority-wise actions.
Maintain an audit trail of action creation, assignment, status updates, AI-generated summaries, follow-up messages, and closure notes.
LLM Role in the Workflow:
Convert free-text notes into structured action items.
Summarize the action item, current progress, blocker, owner, due date, and next step.
Suggest category, priority, missing information, and recommended next action.
Draft professional follow-up messages for reminders, clarification requests, status updates, and closure confirmation.
Convert progress comments into concise status updates.
Generate a closure note that explains what was completed, what evidence is available, and whether any follow-up remains.
📦 Deliverables
All the deliverables are expected to be of production-level quality, ensuring excellence in both content and look & feel. The total score across the 10 deliverables is 100 marks. Each deliverable carries a different weight based on complexity, depth of thinking, implementation effort, and traceability value.

Functional Requirements Document / User Stories – Cover functional and nonfunctional requirements, personas, user journeys, business rules, screen-level requirements, acceptance criteria, assumptions, constraints, and downstream development inputs.
Application Architecture and Technical Architecture Diagrams – Provide logical, technical, integration, data flow, security, and AI-assist architecture views that explain how the solution works end to end.
Database Design / Data Models – Use any RDBMS. Deliver logical model, physical model, ER diagram, key tables, relationships, constraints, sample records, and data dictionary. Do not use JSON as the primary data store.
Story-to-Spec Decomposition (SSD) – Decompose the requirements into logical modules, epics, user stories, workflows, business rules, validation rules, and implementation-ready specification units.
Wireframes / User Interface Design – Create clear wireframes or screen designs for intake, triage, assignment, status tracking, communication drafting, reporting, and closure views.
SPECS / DSL in Markdown or YAML – Create structured Markdown or YAML specifications for each story component, including field definitions, screen behavior, validation rules, APIs or functions, and a hierarchical file tree layout.
Software Code and Working Software – Build a working application that demonstrates request intake, classification, validation, owner assignment, status tracking, LLM-assisted summary, communication drafting, and closure update.
Functional Test Scripts in CSV or Excel – Provide positive, negative, boundary, validation, workflow, exception, security, and AI-assisted output review test cases in a structured CSV or Excel format.
Traceability Matrix in CSV or Excel – Map requirements, stories, specs, database fields, code modules, test cases, prompts, AI-generated outputs, and demo evidence to ensure end-to-end traceability.
Code Quality Review Agent – Develop an AI-assisted review agent using Streamlit or another front end to evaluate the application code that has been developed as part of the exercise. The agent should review the code against a defined quality checklist and, where feasible, align the review output with common static code analysis practices such as SonarQube-style quality gates. The agent should assess maintainability, readability, modularity, coding standards, naming conventions, duplication, exception handling, security considerations, configuration handling, database access quality, test readiness, and traceability to the specifications. The output should include a quality score, checklist-wise findings, severity-wise observations, improvement recommendations, and an overall quality perspective for final submission readiness.
Scoring Details - Total 100 Marks
The scoring model below gives higher weight to complex deliverables that require deeper reasoning, stronger design quality, working implementation, and end-to-end SDLC traceability.

#	Deliverable	Score	Scoring Focus
1	Functional Requirements Document / User Stories	10	Completeness of requirements, clarity of personas, acceptance criteria, business rules, assumptions, and nonfunctional coverage.
2	Application and Technical Architecture Diagrams	10	Architecture clarity, layering, data flow, integration approach, security consideration, AI interaction design, and scalability thinking.
3	Database Design / Data Models	10	Logical model, physical model, ER diagram, normalization, constraints, relationships, sample data, and data dictionary quality.
4	Story-to-Spec Decomposition (SSD)	8	Quality of decomposition, logical modularization, story granularity, workflow clarity, and readiness for specification generation.
5	Wireframes / User Interface Design	7	Usability, screen coverage, visual clarity, navigation flow, consistency, and alignment to the request workflow.
6	SPECS / DSL in Markdown or YAML	12	Structure, precision, completeness, field definitions, validation logic, file tree quality, and code-generation readiness.
7	Software Code and Working Software	18	Functional completeness, working demo quality, maintainable code, error handling, RDBMS integration, LLM integration, and end-to-end execution.
8	Functional Test Scripts in CSV or Excel	8	Coverage of positive, negative, boundary, exception, workflow, security, and AI-output validation scenarios.
9	Traceability Matrix in CSV or Excel	9	End-to-end mapping across requirements, stories, specs, database, code, tests, prompts, AI outputs, and demo evidence.
10	Code Quality Review Agent	8	The agent should review developed code against a defined checklist or SonarQube-style quality criteria and produce a quality-focused output. Scoring should consider checklist coverage, code maintainability, readability, modularity, standards compliance, duplication, security considerations, exception handling, database access quality, test readiness, traceability to specifications, severity-wise findings, meaningful quality score generation, and actionable improvement recommendations.
Total	100	Total score must not exceed 100 marks.
Scoring note: Evaluators may award partial marks within each deliverable based on completeness, correctness, professional presentation, AI-assisted development discipline, responsible usage, and evidence of review. The score distribution intentionally gives the highest weight to working software because it requires integration of requirements, design, data, code, testing, and AI-assisted workflow execution.

✅ Instructions
Use AI tools or Build Your Own AI Agents (BYOAA) to develop the software and deliverables.
Selection of Tools: Carefully evaluate and select the most suitable AI tools or frameworks for each phase of the project. If building custom AI agents, ensure they are scalable and maintainable. Additional weightage will be given if team builds their own AI agent to create the deliverables.
Quality Standards: Adhere strictly to coding standards and best practices for software development. Apply consistent design patterns, code reviews, and automated testing to maintain high quality.
Integration: Ensure seamless integration of components with the overall application architecture.
Testing: Prepare comprehensive test cases, including both functional and non-functional scenarios.
Documentation: Maintain clear and detailed documentation for all deliverables, including architecture diagrams, data models, and user manuals. Update documents regularly as changes are made.
User Experience: Prioritise a user-centric approach in UI/UX design. Avoid using Streamlit or Gradio for the user interface.
TCS Internal
