# ManualTesting

1. **Introduction to Manual Testing**
   
Overview of Software Testing
Software testing is the process of evaluating software applications to ensure they function correctly, meet requirements, and are free of defects. The aim is to identify bugs, ensure reliability, verify performance, and confirm that the software behaves as expected when used by real-world users.

2. **Types of software testing include manual and automated approaches**.
   Both contribute to overall product quality.

a) **Manual Testing**: Definition and Approach
Manual testing requires human testers to execute test cases step-by-step without the use of automated scripts or tools. Testers interact with the application from the perspective of an end user, following predetermined scenarios, or exploring the system to find issues.

Manual functional testing ensures that each feature works as specified by actively using the product and comparing its actual behavior against requirements.

Examples of manual testing tasks include filling out web forms, clicking through application screens, and documenting whether expected outcomes are achieved.

**Importance of Manual Testing**
Human Insight: Testers provide context, intuition, and empathy—enabling them to notice subtle usability or visual issues that automation may overlook.

 i. Early Defect Detection: Manual testing helps uncover bugs early in development, especially in new or rapidly evolving features not yet suitable for automation.

 ii. Exploratory and Ad Hoc Testing: Essential for exploratory testing, where testers use creativity and domain knowledge to uncover unexpected issues.

 iii. Usability and UX Assessment: Only a real user can accurately judge whether an application's interface and overall experience is clear, logical, and pleasant to use.

 iv. Adaptability: Manual testing is flexible; testers can quickly adapt to evolving requirements or unexpected application changes, unlike scripted automation frameworks.

 v. Foundation for Automation: All new applications require some degree of manual testing before processes can be automated, validating the product's readiness and determining which tests are most valuable to automate.

3. **Roles and Responsibilities of a Manual Tester**
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

1. **Planning and Requirement Analysis**

Define the project scope, objectives, and feasibility.

Gather requirements from stakeholders (customers, users, business analysts).

Conduct cost-benefit and risk analysis.

Produce key documents like the Software Requirement Specification (SRS).**

Outcome: Approved project plan and requirements baseline.

2. **System Design**

Design overall system architecture (High-Level Design) and detailed component designs (Low-Level Design).

Define database schema, interfaces, modules, data flow, and user interface design.

Select technologies, tools, and hardware resources.

Outcome: Design documents, prototypes, and architecture diagrams.

3. **Implementation (Coding)**

Developers convert design into source code using chosen programming languages and tools.

Code is often developed in small, manageable units or iterations.

Unit tests may be created and executed at this phase.

Outcome: Functional software modules.

4. **Testing**

Comprehensive verification to detect defects. Includes manual and automated tests such as unit, integration, system, acceptance, regression, performance, and security testing.

Test results are documented; defects are logged and tracked.

Outcome: Verified and validated software ready for deployment.

5. **Deployment**

Software is deployed to production or live environments.

May involve staging and beta releases before full deployment.

Activities include packaging, installation, configuration, and user training.

Outcome: Software available to end-users.

6. **Maintenance**

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

1. **Waterfall Model**
Phases flow downwards linearly, without overlap.

Emphasis on documentation and upfront planning.

Testing happens after the entire coding phase is complete.

Not suitable for changing requirements because once a phase is done, it’s costly to revisit.

2. **Spiral Model**
Combines iterative development with systematic risk assessment.

Development proceeds in spirals or loops, each involving planning, risk analysis, engineering, and evaluation.

After each loop, a prototype or partial release is produced.

Very useful for complex, high-risk projects where requirements are unclear.

3. **V-Model (Validation and Verification Model)**
Represents each development phase with a corresponding testing phase forming a “V” shape.

For example, Requirements phase links to Acceptance Testing; Design phase links to System Testing.

Ensures testing is planned early and executed alongside development.

Widely used in regulated industries requiring high quality.

4. **Agile Model**
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

<img width="607" height="611" alt="image" src="https://github.com/user-attachments/assets/92845ce5-5351-45b9-9e60-637c2eff9bec" />


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


**Types of Testing:**
1. **Functional Testing**
Definition: Functional testing verifies that the software system operates according to the specified functional requirements. It focuses on "what" the system does.

Purpose: To ensure every feature works as expected from a user or business perspective.

Scope: Tests user commands, data manipulation, integrations, business processes, and system functionality.

**Typical Tests:**
Unit testing (individual components)

Integration testing (how components work together)

System testing (end-to-end validation)

User Acceptance Testing (final validation by users)

Example: Verifying if login functionality works with valid credentials, denies access with invalid ones, and handles password resets correctly.

Manual/Automated: Mostly manual, but can be automated especially for regression suites.

2. **Non-Functional Testing**
Definition: Testing non-functional requirements such as performance, usability, reliability, and security rather than specific behaviors.

Purpose: To validate attributes of the system that affect user experience and operational quality.

Key Types:

Performance Testing: Checks speed, responsiveness under load.

Load Testing: Measures system behavior under expected user load.

Stress Testing: Tests system limits under extreme conditions.

Security Testing: Identifies vulnerabilities or risks.

Usability Testing: Assesses ease of use and user-friendliness.

Compatibility Testing: Ensures proper operation across devices, browsers, OS.

Example: Testing how quickly a website loads with 1000 simultaneous users or validating the software’s encryption methods.

Manual/Automated: Mostly automated tools; some usability and compatibility tests are manual.

3. **Regression Testing**
Definition: Re-testing existing software functionality to ensure that recent code changes have not adversely affected previously working features.

Purpose: To catch new bugs or defects introduced by enhancements, patches, or fixes.

When: Performed after any code changes, bug fixes, or feature additions.

Scope: Can cover all or part of the software depending on changes.

Automation: Highly suited for automation due to repetitive nature.

Example: After fixing a bug in the payment module, rerunning tests for checkout, order confirmation, and account balance updates.

4. **Smoke Testing**
Definition: A shallow and wide approach to testing that checks basic system functionality to determine if it is stable enough for further testing.

Purpose: To verify the most critical functions work after a new build or deployment.

When: Often the first test run on a new build.

Scope: Focuses on major features, does not go deep.

Example: For an e-commerce app, verifying login, product search, and add-to-cart functionality before proceeding with detailed tests.

Automation: Can be automated for rapid feedback.

5. **Sanity Testing**
Definition: A focused run of tests verifying specific functionality after minor changes or bug fixes to ensure particular features work correctly.

Purpose: To quickly confirm that a specific bug fix or functionality change is working as intended.

When: After receiving a new build with minor updates or bug fixes.

Scope: Narrow; tests only the affected areas.

Example: After fixing the password reset flow, testing just that feature without touching unrelated features.

Automation: Usually manual but can be automated.

6. **Integration Testing**
Definition: Testing the interactions between integrated modules or components to ensure they work together correctly.

Purpose: To identify interface defects between modules.

Approaches:

Big Bang: Integrate all components and test at once.

Incremental: Integrate and test modules one by one.

Example: Testing payment processing module interaction with order management and notification systems.

Manual/Automated: Both, depending on complexity.

7. **System Testing**
Definition: Testing a completely integrated system to verify that it meets specified requirements.

Purpose: To validate the end-to-end system specifications and behavior.

Scope: Entire application including all modules, databases, interfaces, and network.

Types within System Testing: Functional, performance, security, usability testing within the system context.

Example: Testing an entire banking app’s fund transfer, account statements, and notifications as a single system.

Manual/Automated: Both.

8. **User Acceptance Testing (UAT)**
Definition: Formal testing performed by the end users or clients to confirm that the software meets business requirements and is ready for production.

Purpose: To validate the software from user perspective before release.

Scope: Real-world scenarios, workflows, and use cases.

Types: Alpha testing (internal users), Beta testing (selected external users).

Example: Business users validating reports generation and workflow in an ERP system.

Manual/Automated: Usually manual.


<img width="685" height="618" alt="image" src="https://github.com/user-attachments/assets/17efe361-1702-472d-b487-f7c4d2f322fc" />

4. **Testing Techniques**

**Black Box Testing**
Definition: Black Box Testing is a software testing technique where the tester evaluates the functionality of the application without any knowledge of its internal code or implementation. It focuses on testing the software from an end-user’s perspective, validating inputs against expected outputs.

Key Characteristics:

Tester does not need programming knowledge or access to source code.

Focuses on functionality, requirements, and behavior of the system.

Tests are based on requirements, use cases, and business logic.

**Common Black Box Testing Techniques:**

**Equivalence Partitioning:** Divides input data into classes or sets where test cases for one value represent the entire class. For example, for an age input range 18–65, testing one valid age (say 30) represents all valid ages.

**Boundary Value Analysis (BVA):** Tests the edge values just inside and outside input boundaries where defects often occur (e.g., test values 17, 18, 65, 66 for an age input 18–65).

**Decision Table Testing:** Uses tables mapping combinations of inputs (conditions) to outputs (actions), useful for complex business rules.

**State Transition Testing:** Tests different states of an application and transitions triggered by events (e.g., logged in, logged out states).

**Error Guessing:** Based on experience, testers anticipate common errors developers might make.

**Advantages:**

Tests software from user’s perspective.

Does not require knowledge of internal implementation.

Effective for validation and acceptance testing.

**Limitations:**

Limited coverage of internal code paths.

May miss some logical errors in code.

**White Box Testing**
Definition: White Box Testing (also called Clear Box or Glass Box Testing) involves testing the internal workings, structure, and logic of the software. The tester has knowledge of the source code and designs test cases to exercise specific code paths, branches, conditions, and loops.

Key Characteristics:

Requires programming knowledge.

Tests internal logic and structure.

Focus on code coverage (statement, branch, path coverage).

Common White Box Testing Techniques:

**Unit Testing:** Testing individual functions/methods/classes.

Statement Coverage: Ensuring every line of code is executed at least once.

Branch Coverage: Testing each possible branch (true/false) in control structures.

Path Coverage: Testing all possible execution paths.

Mutation Testing: Introducing small changes (mutations) to code to check if test cases detect bugs.

Advantages:

Ensures thorough code coverage.

Early detection of logical errors.

Optimizes and improves code quality.

Limitations:

Requires knowledge of code and programming.

Time-consuming for large applications.

May not catch missing functionality or integration issues.

**Grey Box Testing**
Definition: Grey Box Testing is a hybrid technique that involves testing with partial knowledge of the internal workings of the application. Testers have access to design documents, database schemas, or code structure but test primarily from a black box perspective.

Key Characteristics:

Tester has limited knowledge of internal logic.

Combines advantages of both black box and white box testing.

Focus on both functionality and some code or data structure verification.

**Common Grey Box Testing Approaches:**

Validate data flow between modules.

Test security vulnerabilities using knowledge of internal architecture.

Use internal knowledge to design more effective test cases than pure black box testing.

Perform regression testing more efficiently by understanding impact areas.

Advantages:

Better test coverage than pure black box testing.

Detects context-specific errors related to data flow or security.

Requires less code knowledge than white box testing, balancing complexity.

Limitations:

Not as thorough as white box testing.

May need test engineers with some programming or design background.

Partial access to code or architecture may limit testing depth.

<img width="707" height="351" alt="image" src="https://github.com/user-attachments/assets/0d342ada-3f91-4497-a479-c20f28124216" />

5. **Test Case Development**
Test Case Development is the process of identifying, documenting, and organizing the tests that will verify the software meets its requirements. It ensures systematic, repeatable testing and helps teams detect issues early.

**Steps for Test Case Development:**

Understand Requirements: Study the software requirements, user stories, or specifications thoroughly to clarify what should be tested.

Identify Test Scenarios: Break down requirements into specific functionalities or behaviors to be tested, covering both positive (expected use) and negative (error/exception) paths.

Define Inputs and Preconditions: Clearly describe the starting state and any required setup before test execution.

Specify Actions: List each step the tester must perform.

Document Expected Results: Clearly state the desired outcome for each step or the final state after test execution.

Assign Unique IDs and Traceability: Link test cases to requirements for coverage tracking

**Writing Test Cases**
Test Case Writing is about clear documentation so any tester can execute the test and verify results.

Standard Test Case Structure
Test Case ID: Unique identifier.

Title/Description: Brief description of what the test validates.

Preconditions: Initial state or configuration required.

Test Steps: Step-by-step actions for the test.

Test Data: Inputs to be used (usernames, passwords, input values, etc.).

Expected Result: The outcome that confirms the system works as intended.

Actual Result: (filled post-execution).

Status: Pass/Fail.

Remarks/Comments: Additional notes


<img width="780" height="475" alt="image" src="https://github.com/user-attachments/assets/d07839c9-0f1e-4086-b807-d84aada8fd98" />

**Best Practices for Writing Test Cases**
Be clear, concise, and unambiguous.

Ensure test cases are self-explanatory and can be run independently.

Include both positive and negative scenarios.

Maintain traceability to requirements.

Use consistent templates and formats for easy maintenance.

Prioritize risk and business impact in test selection.

Specify necessary test data and environment.

Review for coverage, completeness, and accuracy.

6. **Test Case Design Techniques**
Test case design techniques help ensure high-quality, high-coverage test cases. They can be broadly categorized as:

1. **Black Box Testing Techniques** (No code knowledge needed)
Equivalence Partitioning: Divide inputs into equivalent groups (e.g., valid usernames, invalid usernames). Test one value per group.

Boundary Value Analysis (BVA): Test at and around boundaries (e.g., minimum, maximum, just below, just above).

Decision Table Testing: Create tables to cover combinations of conditions and actions, suitable for features with business rules.

State Transition Testing: Test how the system transitions between states based on events or inputs.

Error Guessing: Rely on experience to guess areas likely to contain defects.

2. **White Box Testing Techniques** (Knowledge of code structure)
Statement/Branch/Path Coverage: Ensure tests execute all logical paths, branches, and statements in the code.

Loop Testing: Test the validity of different loop executions (zero, one, many times).

3. **Experience-Based/Exploratory Techniques**
Use tester experience to design ad hoc or exploratory tests in areas where traditional techniques might miss defects.

7. **Test Data Preparation**
Test Data Preparation involves identifying, creating, and managing the data needed to execute test cases. Good test data is realistic, represents the full range of input possibilities (valid, invalid, boundary cases), and helps uncover defects that otherwise might go unnoticed.

Typical Test Data Types:

Valid data: Expected, normal input values.

Invalid data: Out-of-range, incorrect, or malformed inputs for negative testing.

Boundary data: Values at the edges of allowable input ranges.

Null/Empty data: Blank or missing values.

Large/Complex data: For performance, stress, or security testing.

Sources and Methods:

Use data provided in requirements/user stories.

Generate synthetic data for edge cases (e.g., longest allowed string).

Copy anonymized production data for realistic scenarios (with approvals and privacy compliance).

Use automated tools to generate or manage data as needed.


8. **Introduction to Test Management Tools**
**Definition & Purpose**

Test Management Tools are software solutions designed to manage, organize, and control the testing process within the software development lifecycle. They streamline tasks like test case creation, execution scheduling, result tracking, defect management, and reporting.

Purpose is to improve efficiency, enable traceability, enhance collaboration, and ensure comprehensive test coverage.

**Key Features of Test Management Tools**

Central repository for test assets (cases, suites, plans)

Test scheduling and execution management

Defect/issue tracking integration

Real-time reporting and metrics dashboards

Requirements linkage and traceability (mapping tests to user stories or requirements)

User and permission management

Integration with CI/CD, automation frameworks, and issue trackers (e.g., JIRA)

Collaboration features for distributed teams

**Benefits**

Increased test coverage, transparency, and repeatability

Better defect tracking and faster resolution

Support for manual and automated testing

Data-driven decision making through comprehensive reporting

Some of the popular Test Management Tools are **JIRA, Quality Center (HP ALM), TestRail**


9. **Basics of Agile Methodology**

Agile is a flexible, iterative software development methodology designed to deliver customer value quickly and efficiently.

Focuses on adaptability to change, early and continuous delivery, collaboration, and continuous improvement

**12 Principles:**

Customer satisfaction by early and continuous delivery of valuable software.

Welcome changing requirements.

Deliver working software frequently.

Close daily collaboration between business and development.

Build projects around motivated individuals.

Face-to-face conversation is best.

Working software is the primary measure of progress.

Sustainable development pace.

Continuous attention to technical excellence.

Simplicity—the art of maximizing work not done—is essential.

Self-organizing teams.

Regularly reflect to become more effective.

**Characteristics of Agile**
Iterative and incremental development through short cycles called "sprints."

Regular feedback and adaptation.

Collaborative and cross-functional teams.

Focus on working software over exhaustive documentation.

Continuous improvement via sprint reviews and retrospectives.


**Scrum Framework**

**Introduction to Scrum**
Scrum is a popular Agile framework that structures development into fixed-length iterations called sprints (usually 2–4 weeks).

Designed for transparency, inspection, and adaptation.

**Scrum Roles**
Product Owner: Represents the customer, defines and prioritizes requirements (Product Backlog).

Scrum Master: Facilitates the process, removes impediments, ensures Scrum principles are followed.

Development Team: Cross-functional team responsible for delivering potentially shippable increments.

**Scrum Artifacts**
Product Backlog: Ordered list of all desired work on the product.

Sprint Backlog: Set of items to be completed in the current sprint.

Increment: The sum of all completed Product Backlog items in a sprint

**Scrum Events**
Sprint: Core development cycle (timeboxed iteration).

Sprint Planning: Meeting to decide what will be done in the upcoming sprint.

Daily Scrum: 15-minute standup for team synchronization.

Sprint Review: End-of-sprint demonstration and feedback session.

Sprint Retrospective: Meeting to reflect on process and identify improvements.


**Role of a Tester in Agile Projects**
**Tester’s Responsibilities in Agile**
Collaborate closely with developers, product owners, and business analysts from the start.

Participate in requirement reviews, sprint planning, and acceptance criteria definition.

Continuously design, execute, and update test cases throughout the sprint.

Provide quick feedback about quality, risks, and test results.

Automate repetitive and regression tests for rapid feedback cycles.

Embrace exploratory testing to identify potential gaps.

**Testing as a Continuous Activity**
Testing happens concurrently with development, not as a separate phase at the end.

Testers contribute to defining "done," acceptance criteria, and quality standards.

Involved in sprint retrospectives to suggest improvements in testing practices.

**Tester's Skills in Agile**
Strong communication and collaboration.

Flexibility, quick adaptation to change.

Automation tool proficiency is highly valued.

Business perspective—understand customer needs and priorities.



