# ManualTesting

1. Introduction to Manual Testing
   
Overview of Software Testing
Software testing is the process of evaluating software applications to ensure they function correctly, meet requirements, and are free of defects. The aim is to identify bugs, ensure reliability, verify performance, and confirm that the software behaves as expected when used by real-world users.

2. Types of software testing include manual and automated approaches. Both contribute to overall product quality.

a) Manual Testing: Definition and Approach
Manual testing requires human testers to execute test cases step-by-step without the use of automated scripts or tools. Testers interact with the application from the perspective of an end user, following predetermined scenarios, or exploring the system to find issues.

Manual functional testing ensures that each feature works as specified by actively using the product and comparing its actual behavior against requirements.

Examples of manual testing tasks include filling out web forms, clicking through application screens, and documenting whether expected outcomes are achieved.

Importance of Manual Testing
Human Insight: Testers provide context, intuition, and empathy—enabling them to notice subtle usability or visual issues that automation may overlook.

 i. Early Defect Detection: Manual testing helps uncover bugs early in development, especially in new or rapidly evolving features not yet suitable for automation.

 ii. Exploratory and Ad Hoc Testing: Essential for exploratory testing, where testers use creativity and domain knowledge to uncover unexpected issues.

 iii. Usability and UX Assessment: Only a real user can accurately judge whether an application's interface and overall experience is clear, logical, and pleasant to use.

 iv. Adaptability: Manual testing is flexible; testers can quickly adapt to evolving requirements or unexpected application changes, unlike scripted automation frameworks.

 v. Foundation for Automation: All new applications require some degree of manual testing before processes can be automated, validating the product's readiness and determining which tests are most valuable to automate.

3. Roles and Responsibilities of a Manual Tester
Key Roles:

Manual Tester / Test Engineer

QA Analyst

**Core Responsibilities:**

**Requirement Analysis:** Study requirement documents and specifications to understand what needs to be tested, clarifying expectations with stakeholders.

**Test Planning:** Help develop or review test strategies, plan test schedules, select test design techniques, and define test scope.

**Test Case Design and Documentation:** Create detailed, step-by-step test cases/scenarios that cover functional requirements, edge cases, and workflow variations. Maintain traceability between requirements and tests.

**Test Execution:** Carry out test cases manually—using the software as an end user would—recording results and deviations thoroughly.

**Defect Reporting:** Identify, log, and describe discovered bugs with clear steps to reproduce, expected vs. actual results, severity, and environment details.

**Regression Testing:** Rerun relevant test cases after bug fixes or feature changes to ensure no new defects are introduced.

**Collaboration:** Work closely with developers, product managers, and other QA professionals to clarify requirements and priorities, and to communicate test findings.

**Feedback and Improvement:** Suggest improvements to requirements, design, and usability based on testing experience.

**Test Closure:** Document results, lessons learned, and contribute to retrospectives or process improvement.

**Summary Table:** Key Responsibilities of a Manual Tester

**Responsibility	Description**
Requirement Analysis	Understand what and how to test.
Test Case Design	Write clear, traceable test scenarios or cases.
Test Execution	Manually run tests using software as an end user.
Defect Reporting	Log all bugs in detail with reproducible steps.
Regression Testing	Ensure bug fixes or new features do not break existing functionality.
Collaboration	Liaise with QA team, developers, stakeholders.
Documentation	Maintain organized records of tests and outcomes.
Note: Manual testers must be detail-oriented, analytical, and able to think from both technical and user perspectives.


**Software Development Life Cycle (SDLC)**
The Software Development Life Cycle (SDLC) is a structured process used by development teams to plan, design, build, test, deploy, and maintain high-quality software efficiently and cost-effectively. SDLC defines a series of clearly defined phases with specific deliverables to guide the project from inception to retirement, ensuring that software meets business requirements and quality standards.

**Phases of SDLC**
While the exact phase names can vary slightly across different methodologies, the typical SDLC consists of the following core phases:

1. Planning and Requirement Analysis

Define the project scope, objectives, and feasibility.

Gather requirements from stakeholders (customers, users, business analysts).

Conduct cost-benefit and risk analysis.

Produce key documents like the Software Requirement Specification (SRS).**

Outcome: Approved project plan and requirements baseline.

2. System Design

Design overall system architecture (High-Level Design) and detailed component designs (Low-Level Design).

Define database schema, interfaces, modules, data flow, and user interface design.

Select technologies, tools, and hardware resources.

Outcome: Design documents, prototypes, and architecture diagrams.

3. Implementation (Coding)

Developers convert design into source code using chosen programming languages and tools.

Code is often developed in small, manageable units or iterations.

Unit tests may be created and executed at this phase.

Outcome: Functional software modules.

4. Testing

Comprehensive verification to detect defects. Includes manual and automated tests such as unit, integration, system, acceptance, regression, performance, and security testing.

Test results are documented; defects are logged and tracked.

Outcome: Verified and validated software ready for deployment.

5. Deployment

Software is deployed to production or live environments.

May involve staging and beta releases before full deployment.

Activities include packaging, installation, configuration, and user training.

Outcome: Software available to end-users.

6. Maintenance

Ongoing support and updates to fix bugs, enhance features, and improve performance.

Monitoring for security vulnerabilities and user feedback incorporation.

Outcome: Sustained and evolving software product.

Visual summary:

text
Planning → Design → Implementation → Testing → Deployment → Maintenance
Models of SDLC
Several SDLC models exist to organize these phases. Choosing a model depends on project size, complexity, risk, customer needs, and flexibility of requirements. Common models are:

**Model	Description	Best for	Key Characteristics**
<img width="764" height="477" alt="image" src="https://github.com/user-attachments/assets/47ca42b0-f7e9-4518-834e-d98976f2bb34" />

1. Waterfall Model
Phases flow downwards linearly, without overlap.

Emphasis on documentation and upfront planning.

Testing happens after the entire coding phase is complete.

Not suitable for changing requirements because once a phase is done, it’s costly to revisit.

2. Spiral Model
Combines iterative development with systematic risk assessment.

Development proceeds in spirals or loops, each involving planning, risk analysis, engineering, and evaluation.

After each loop, a prototype or partial release is produced.

Very useful for complex, high-risk projects where requirements are unclear.

3. V-Model (Validation and Verification Model)
Represents each development phase with a corresponding testing phase forming a “V” shape.

For example, Requirements phase links to Acceptance Testing; Design phase links to System Testing.

Ensures testing is planned early and executed alongside development.

Widely used in regulated industries requiring high quality.

4. Agile Model
Development is broken into small iterations or sprints, typically 2-4 weeks long.

Each sprint produces a potentially shippable product increment.

Focus on customer collaboration, responding to change, and continuous improvement.

Common frameworks include Scrum, Kanban, and XP (Extreme Programming).

Encourages daily stand-ups, frequent demos, and retrospectives.

**Software Testing Life Cycle (STLC)**
The Software Testing Life Cycle (STLC) is a set of systematic phases that define the testing process applied during software development to ensure the product’s quality meets specified requirements. Each phase has specific objectives, deliverables, and exit criteria that drive the testing process forward efficiently.

STLC is closely aligned with the Software Development Life Cycle (SDLC) but focuses exclusively on testing activities to detect defects early and deliver a high-quality software product.

**Phases of STLC**
Most standard STLC models include the following six distinct phases:

**Requirement Analysis**

The QA team reviews and analyzes the software requirements from a testing perspective.

Clarify any ambiguities or gaps with stakeholders.

Evaluate testability of requirements including functional and non-functional aspects.

Assess opportunities for automation.

Deliverables: List of testable requirements, test coverage plan, automation feasibility report.

**Test Planning**

Define the overall testing strategy, scope, effort estimation, resource allocation, and schedule.

Decide testing types (manual, automation, performance).

Identify tools and environments needed.

Risk analysis and mitigation planning.

Assign roles and responsibilities.

Deliverables: Test plan document, test strategy, resource and cost estimates.

**Test Case Development / Test Design**

Create detailed test cases/scenarios based on requirements.

Prepare or update test data.

Design automation scripts if applicable.

Peer reviews of test cases and scripts.

Map test cases to requirements using a Requirements Traceability Matrix (RTM).

Deliverables: Approved test cases, test data sets, automation scripts, RTM.

**Test Environment Setup**

Prepare the hardware and software environments required for testing.

Install and configure the system under test and necessary tools.

Validate the test environment by performing smoke tests.

Coordinate environment setup with developers, system admins, and network teams.

Deliverables: Verified test environment ready for execution.

**Test Execution**

Execute planned test cases and record actual results.

Log defects for failed test cases with all necessary details.

Retest fixed defects and perform regression testing to ensure no new issues.

Track test progress, coverage, and defect status.

Deliverables: Test execution reports, defect logs, updated RTM.

**Test Closure**

Ensure that all critical defects have been resolved or accepted.

Evaluate the test cycle outcomes against exit criteria.

Prepare the test summary and closure report containing key metrics and learnings.

Archive test ware artifacts and documents.

Conduct retrospectives to identify process improvements.

Deliverables: Test closure report, lessons learned, archived documents.

**Entry and Exit Criteria in STLC**
Each phase in STLC has Entry Criteria (conditions to start the phase) and Exit Criteria (conditions to complete the phase successfully). This ensures systematic progression and quality control.

<img width="787" height="497" alt="image" src="https://github.com/user-attachments/assets/b2274a0c-ee51-46a4-8b90-b2295f65333c" />

Detailed Phases: Test Planning, Design, Execution, and Closure
1. **Test Planning**
This phase sets the foundation for successful testing.

Define what to test and how to test it.

Outline testing objectives, scope, schedule, and approach.

Identify any risks and mitigation options.

Assign test team roles and responsibilities.

Select tools for test management, execution, and automation.

Create a Test Plan Document describing:

Test objectives

Scope (in and out of testing)

Resource estimation

Schedule and milestones

Environment and tools requirements

Risk assessment

Entry and exit criteria for testing

2. **Test Case Development (Test Design)**
Design individual test cases or test scripts based on the requirements.

Test cases include clear input data, execution steps, expected results.

Develop test data required to execute test cases.

Automated scripts may be developed in parallel.

Review and baseline test cases to ensure coverage and quality.

Maintain traceability by linking test cases to requirements (RTM).

3. **Test Execution**
Execute test cases as per the plan.

Mark each test case as Passed, Failed, Blocked, or Deferred.

Record actual results versus expected results.

Log defects in a bug tracking system with reproduction steps and severity.

Communicate progress in daily stand-ups or status reports.

Re-test defects once fixed and perform regression testing to verify no side effects.

Continuously monitor coverage and progress against test plans.

4. **Test Closure**
Confirm all test activities are complete and criteria met.

Conduct a formal testing closure meeting to present results and challenges.

Prepare Test Closure Report including:

Summary of testing activities

Number and severity of defects found/resolved

Quality metrics like test coverage, pass/fail rate

Lessons learned and improvement suggestions

Archive test artifacts: test plans, cases, defect logs.

Release testing resources.

Transfer knowledge to maintenance/support teams if needed.



