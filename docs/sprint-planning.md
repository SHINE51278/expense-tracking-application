# Sprint Planning and Execution
## Expense Tracking Application — Case Study 16

## 1. Sprint Overview

The project is planned across three one-week sprints. Each sprint has a defined goal, selected backlog items, development tasks, an expected increment, and a review and retrospective.

**Important:** The sprint plans below describe the intended work. Update the completion status and actual results after the corresponding work has been performed.

## 2. Sprint 1 — Authentication and Transaction Management

### Sprint Goal
Enable users to access the application and record income and expenses.

### Selected Product Backlog Items
- PB1: User registration and login
- PB2: Income recording
- PB3: Expense recording

### Sprint Backlog

| Task ID | Task | Expected Result |
|---|---|---|
| S1-T1 | Design the basic application interface. | A clear and usable interface. |
| S1-T2 | Implement registration and login. | Users can authenticate. |
| S1-T3 | Develop the income entry form. | Income can be recorded. |
| S1-T4 | Develop the expense entry form. | Expenses can be recorded. |
| S1-T5 | Store transaction data. | Transaction information is persisted. |
| S1-T6 | Test authentication and transaction entry. | Core functionality is verified. |

### Expected Increment
A working foundation that supports user authentication and income and expense recording.

### Sprint Review
Demonstrate registration, login, and transaction entry. Collect feedback on usability and missing fields.

### Sprint Retrospective
Discuss development progress, integration issues, and testing. Improve task estimation and test each feature as it is developed.

## 3. Sprint 2 — Categories and Financial Dashboard

### Sprint Goal
Help users organize their transactions and understand their financial position.

### Selected Product Backlog Items
- PB4: Transaction categorization
- PB5: Financial summary dashboard
- PB6: Transaction editing and deletion

### Sprint Backlog

| Task ID | Task | Expected Result |
|---|---|---|
| S2-T1 | Define expense categories. | Transactions can be organized. |
| S2-T2 | Implement transaction categorization. | Users can assign categories. |
| S2-T3 | Implement transaction editing. | Incorrect entries can be updated. |
| S2-T4 | Implement transaction deletion. | Unwanted entries can be removed. |
| S2-T5 | Calculate income, expenses, and balance. | Financial totals are correct. |
| S2-T6 | Build and test the dashboard. | Users can view a financial summary. |

### Expected Increment
A dashboard that displays categorized transactions, total income, total expenses, and remaining balance.

### Sprint Review
Demonstrate categories, transaction editing and deletion, and dashboard calculations. Collect feedback on the displayed information.

### Sprint Retrospective
Review calculation errors, interface improvements, and integration challenges. Add more frequent validation and testing to the workflow.

## 4. Sprint 3 — Reports and Visualization

### Sprint Goal
Provide spending insights and prepare the application for final demonstration.

### Selected Product Backlog Items
- PB7: Monthly reports
- PB8: Visual expense charts

### Sprint Backlog

| Task ID | Task | Expected Result |
|---|---|---|
| S3-T1 | Implement month selection. | Users can choose a reporting period. |
| S3-T2 | Calculate monthly income and expenses. | Reports show period-specific totals. |
| S3-T3 | Develop expense charts. | Spending patterns are visualized. |
| S3-T4 | Add date-based filtering. | Users can filter transactions by date. |
| S3-T5 | Perform functional and usability testing. | Defects are identified. |
| S3-T6 | Fix defects and prepare the demonstration. | A verified release candidate is available. |

### Expected Increment
An application that provides monthly financial summaries and charts of expenses by category.

### Sprint Review
Demonstrate monthly reports and charts. Gather stakeholder feedback and record any additional requirements.

### Sprint Retrospective
Evaluate the quality of the final increment, testing effectiveness, communication, and task estimation. Record lessons for future development.

## 5. Daily Scrum

The team conducts a 15-minute Daily Scrum on each working day during a sprint. Developers discuss progress toward the Sprint Goal, their next steps, and any impediments.

### Example
- Yesterday: Completed the expense entry form.
- Today: Integrate the form with transaction storage.
- Blocker: Database connection needs debugging.

The team coordinates to resolve the blocker without turning the Daily Scrum into a lengthy problem-solving meeting.

## 6. Definition of Done

A task is considered complete when:

1. The implementation meets its acceptance criteria.
2. Relevant tests pass.
3. The code is reviewed and integrated.
4. No critical defects remain.
5. Documentation is updated where necessary.
6. The feature is ready for demonstration.

## 7. Sprint Tracking

Use GitHub Issues to track each task and GitHub Projects to monitor its status.

Recommended workflow:
- **Todo:** Work has not started.
- **In Progress:** Work is underway.
- **Done:** The task meets the Definition of Done.

Move an issue to Done only after the work has actually been completed and verified.

## 8. Overall Reflection

This sprint plan demonstrates how a large application can be divided into manageable iterations. Each sprint builds on the previous increment, allowing the team to collect feedback, identify problems early, and adapt priorities. Daily coordination, testing, Sprint Reviews, and Retrospectives support transparency and continuous improvement.
