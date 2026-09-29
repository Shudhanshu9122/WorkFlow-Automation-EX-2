# 🚀 Workflow Automation EX-2

![Camunda 8](https://img.shields.io/badge/Camunda-8.x-blue?style=for-the-badge&logo=camunda)
![BPMN 2.0](https://img.shields.io/badge/BPMN-2.0-orange?style=for-the-badge)

Welcome to the **Workflow Automation EX-2** repository! This project contains a collection of BPMN 2.0 business process models designed for Camunda 8, demonstrating various real-world automation scenarios.

---

## 📂 Process Scenarios

### 1. 🏨 Hotel Room Reservation (`Scenario1_Hotel_Room_Reservation.bpmn`)
A process model handling hotel bookings. 
- **Start**: Reservation Request Received.
- **Tasks**: Checking room availability and processing payments.
- **Gateways**: Conditional routing based on room availability and payment success.
- **Outcomes**: Successful Booking Confirmation or Reservation Rejection.

### 2. 💰 Loan Application System (`Scenario2_Loan_Application.bpmn`)
A structured workflow for evaluating loan requests.
- **Automated Checks**: Performs initial credit validations.
- **Human-in-the-loop**: Routes complex or edge-case loans for manual review.
- **Outcome Logic**: Handles Approval, Rejection, and pathways based on credit eligibility.

### 3. 👔 Job Applicant Screening (`Scenario3_Job_Applicant.bpmn`)
An HR automation process for applicant tracking and interviewing.
- **Screening**: Initial review of applicant resumes.
- **Interview Stages**: Coordinated routing for technical and HR interviews.
- **Final Decision**: Consolidates feedback to either offer the candidate the position or send a rejection notice.

---

## 🛠️ Technology Stack
*   **Modeling Language**: BPMN 2.0
*   **Engine Target**: Camunda 8 (Zeebe)
*   **Tooling**: Camunda Desktop Modeler

## 🚀 Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/Shudhanshu9122/WorkFlow-Automation-EX-2.git
   ```
2. Open the `.bpmn` files using the [Camunda Desktop Modeler](https://camunda.com/download/modeler/).
3. Inspect the execution semantics (Service Tasks, User Tasks, Exclusive Gateways) applied to each diagram.
4. Deploy to your Camunda cluster via the Modeler's deployment tool to test the workflows.

---
*Developed as part of Workflow Automation coursework (Execution 2).*
