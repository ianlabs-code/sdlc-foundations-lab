# sdlc-foundations-lab
PART 2: REAL-WORLD ENGINEERING SCENARIOS 
Scenario A: SDLC & Framework Selection

Context: A fintech company wants to release a new peer-to-peer payment feature. A government regulatory agency requires complete compliance auditing before release, but competitors are rapidly capturing market share.
Task:
Compare Waterfall vs. Agile (Scrum) for this launch using the criteria below:
Adaptability & Time-to-Market


Regulatory & Compliance Risk Handling


Choose a hybrid or primary framework (e.g., Scrum vs. Waterfall vs. Spiral). Explain your reasoning in 2–3 sentences.

Framework Comparison Table


Criteria
Waterfall 
Agile (Scrum) 
Adaptability & Time-to-Market


Less flexible and usually slower because changes are difficult after planning.
More flexible and faster because work is completed in short sprints.
Regulatory & Compliance Risk Handling


Strong because it provides formal documentation, testing, approvals, and audit trails.
Can support compliance, but requires additional documentation and control measures.



2. Framework Recommendation & Justification:
Which primary or hybrid framework (e.g., Scrum, Waterfall, or Spiral) do you recommend for this fintech regulatory project? Explain your choice in 2–3 sentences.

Answer:
I recommend a hybrid Scrum-Waterfall approach. Scrum provides fast and flexible development, while Waterfall-style compliance gates ensure proper documentation, testing, approval, and regulatory auditing before release.



Scenario B: DevOps & CI/CD Pipeline Breakdown

Context: A team merges code, but the production app breaks during deployment because testing was done manually on individual laptops rather than in an automated pipeline.
Task:
Identify where the communication and process gap occurred between Dev and Ops.
Map out the automated CI/CD pipeline stages (Plan -> Code -> Build -> Test -> Release -> Deploy ->Operate -> Monitor) and state which stage would catch this bug before it reaches production.


1. Gap Analysis:
Identify where the communication and process breakdown occurred between Dev and Ops.
Answer:
The communication and process gap occurred because testing was done manually on individual laptops instead of being integrated into an automated CI/CD pipeline.


2. Pipeline Stage Identification:
Fill in the missing stages of the continuous assembly line and circle/bold the stage that catches local testing bugs before production release:

Plan -> Code -> BUILD ->  TEST  -> Release -> Deploy -> Operate -> Monitor









Scenario C: Git Lifecycle & Branching Strategy
1. Data Movement Command Mapping

Write the standard Git command used to transfer code between each environment:

Working Directory ->  Staging Area: git add_______________


Staging Area -> Local Repository: git commit______________


Local Repository -> Remote Repository (GitHub): git push__________


Remote Repository -> Working Directory: git pull_______________


2. GitFlow Collision Prevention:
Explain how utilizing Feature Branches and a Develop branch prevents two developers from overwriting each other's code on Main. ( 2 to 3 sentences)

Answer:
Feature branches allow developers to work separately without affecting Main directly. Their changes can be merged into Develop first, where conflicts can be resolved and the code can be tested before being merged into Main.
