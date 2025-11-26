# Case 2. SmartGrant: Grant Fund Management

## Background
Young scientists actively attract funding from various foundations through grant competitions. In the course of implementing scientific projects, organisational tasks arise — budget planning, monitoring the targeted use of funds, reporting to grantors, and interaction with implementing organisations. These processes require significant time and administrative resources, reducing the efficiency of research activities.

It is proposed to develop a software tool that reduces the administrative burden on researchers by automating grant fund management processes using smart contract technology and the capabilities of the Mir payment system. Integration with the Mir ecosystem will enable transparent, secure, and controlled settlements between grantors, executors, and research organisations, including mechanisms for identification, targeted transfers, and transaction analytics. In the future, this interaction will allow commercial banks to connect to grant operations regarding the functionality of bank guarantees and letters of credit.

**Goal:** To develop a software tool for creating smart contracts for the effective management of grant funds.

## Core Functional Requirements

- Develop a mechanism for the **creation, execution, and monitoring of smart contracts** that describe the stages of grant implementation, as well as funding conditions and limits.
- Ensure **integration with the Mir payment system API** for:
  - Participant identification.
  - Targeted transfers and settlements.
  - Transaction tokenisation and analytics construction to demonstrate a participant's track record in fulfilling obligations.
- Implement **automated reporting and monitoring** of the targeted use of funds.

## Work Plan

### Checkpoint 1: Architecture and Interface Design
- **Goal:** To describe the business process and role model, and to design the platform's architecture and graphical interface logic, considering the requirements for monitoring fund movement and reporting at all stages of grant execution.
- **Expected Outcomes:**
  - A description of the interaction process for the main participants of the smart contract (e.g., grantee scientist, academic supervisor, project office manager, grantor) is provided.
  - The logic of the user interface for user registration and expenditure item limit configuration is demonstrated.

### Checkpoint 2: Platform Backend, UI, and Smart Contract Executable Development
- **Goal:** To develop the platform's functionality and deploy the configuration.
- **Expected Outcomes:**
  - The backend and UI are implemented.
  - A smart contract with basic functions is developed: contract parametrisation, fixation of conditions (amount, stages, deadlines, performance indicators), and status change upon fulfilment of conditions.
  - Technical tests for platform component connectivity have been conducted.

### Checkpoint 3: Functionality Demonstration and System Testing
- **Expected Outcomes:** A ready-made solution demonstrating the core functionality (transaction) – managing the process of grant application and execution.

---

### Rules:
- **At the time of the start of development, share the project's git repository with experts.**
- **Upload the code to your git after stop-coding.**
- **Upload the presentation to your git.**
- **Provide the code with a brief description of how to deploy the proposed solution.**
