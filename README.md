# Moodle Learning Management System (LMS) - Testing Project

## 📋 Project Overview

This repository contains the complete testing artifacts for the **Moodle LMS** (Version 5.1) project. The primary goal of this project is to rigorously test the core functional modules of Moodle, ensuring system stability, reliability, and adherence to the specified requirements for four distinct user roles: **Admin, Manager, Teacher, and Student**.

This project was conducted as a structured software testing initiative, covering test planning, test case design, execution, and result reporting.

## 🎯 Objectives

- To validate the functionality of key Moodle modules against the Software Requirements Specification (SRS).
- To ensure proper implementation of role-based access control and permission boundaries.
- To identify, document, and track software defects.
- To provide a clear and comprehensive summary of test execution results.
- To demonstrate a complete software testing lifecycle (STLC) process.

## 📁 Repository Structure

This repository is organized to provide a clear view of all testing phases and deliverables.

| File Name | Description |
| :--- | :--- |
| `SRS.pdf` | **Software Requirements Specification:** Details the business drivers, user roles (Admin, Manager, Teacher, Student), and their functional requirements. |
| `RTM for moodle.xlsx` | **Requirements Traceability Matrix:** Maps each functional requirement (`Req ID`) to its corresponding test cases (`Test Case ID`) and current status, ensuring complete test coverage. |
| `Test plan template for Moodle (1).pdf` | **Test Plan:** Outlines the overall testing strategy, scope (in-scope/out-of-scope), test levels (Functional, Smoke, Exploratory), resources, roles, responsibilities, assumptions, and risks. |
| `Test Cases for the Moodle .xlsx` | **Test Cases:** Contains detailed, step-by-step test cases for each user role across multiple sheets (`Admin`, `Manager`, `Teacher`, `Student`), including preconditions, test data, expected results, and actual results. |
| `Test summary Report.pdf` | **Test Summary Report:** Provides a high-level summary of the test execution results, including overall progress and key metrics (though some data filters need adjustment). |

## ✅ Test Coverage

The testing effort covers the following core functional areas:

- **User Management:** Creation, editing, deletion of users, and role assignment.
- **Course Management:** Creation, editing, deletion of courses, and user enrollment.
- **Content Management:** Uploading and managing course materials (files, videos).
- **Assessment Tools:** Creation and execution of assignments and quizzes, including grading.
- **Communication:** Messaging system and discussion forums.
- **System Configuration:** Site settings, language, and calendar events.

## 🛠️ Testing Approach & Tools

We followed a structured testing strategy incorporating multiple test levels:

- **Functional Testing:** To verify that all features work as per requirements.
- **Smoke Testing:** As a quick health check of the main system functions.
- **Exploratory Testing:** To creatively uncover unexpected issues.

### Project Management & Collaboration

To manage this project efficiently, we utilized the following tools:

- **[Trello](https://trello.com/b/89jQrKPx/moodle-functional-testing):** Used for **task management and workflow visualization**. We created boards to divide the project into phases (e.g., "Test Plan Creation", "Test Case Writing", "Test Execution", "Bug Reporting"). Cards were assigned to team members (Salah, Moonera, Rosan, Heba) to track individual responsibilities and progress.
- **[ Bug Reports on Jira ](https://salahpm46-1770580905899.atlassian.net/issues/?jql=project%20in%20%28SCRUM%29%20ORDER%20BY%20created%20DESC):** Served as our primary tool for **defect tracking and project management**. Detailed bug reports were logged as Jira issues, including steps to reproduce, severity, priority, and status. This centralized approach ensured no defect was overlooked.
-   [Zephyr Test Cases on Jira](https://salahpm46-1770580905899.atlassian.net/jira/software/projects/SCRUM/apps/628ce3d4-ed20-4ac9-91aa-6c6ab21a770a/1f1570b7-1896-4331-a997-66cd076264f1#/v2/testCases?projectId=10000): This app was integrated with Jira to manage our **test case library and test cycles**.  
  We used it to organize our 77 test cases, schedule test executions (cycles), and record results directly within Jira.  
  This provided real-time visibility into testing progress and traceability between test cases and defects.

This combination of tools allowed our team to stay organized, communicate effectively, and maintain a clear record of the entire testing process.

## 🚀 How to Use This Repository

1.  **Review the Documentation:** Start by reading the `SRS.pdf` to understand the system's requirements and the `Test plan template for Moodle (1).pdf` to grasp our testing strategy.
2.  **Explore the Traceability:** Open the `RTM for moodle.xlsx` to see how requirements are linked to test cases.
3.  **Examine the Test Cases:** Dive into `Test Cases for the Moodle .xlsx` to review the detailed test scenarios for each user role.
4.  **Check the Results:** Finally, look at the `Test summary Report.pdf` for a high-level overview of the test execution outcomes.

## 👥 Team

This testing project was successfully executed by the dedicated team:

- **Rosan AbuKwaik**
- **Salah Aldin**
- **Moonera Al-Mashni**
- **Heba Basil**

---

**Tags:** `Moodle`, `LMS`, `Software Testing`, `QA`, `Test Plan`, `Test Cases`, `RTM`, `SRS`, `Functional Testing`, `Jira`, `Trello`, `Zephyr`
