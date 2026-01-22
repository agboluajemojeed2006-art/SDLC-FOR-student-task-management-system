# SDLC-FOR-student-task-management-system
NAME:Ikeokwu praise chiamaka
DEPARTMENT:Cybersecurity
MATRIC NUMBER:24/16056
# Student Task Management System (STMS)

## Project Overview
The **Student Task Management System (STMS)** is a software application designed to help students efficiently manage their academic tasks. The system allows students to create, view, update, and delete tasks such as assignments, projects, quizzes, and exams, along with their deadlines and completion status.

This project was developed following the **Software Development Life Cycle (SDLC)** to ensure a structured, reliable, and maintainable system.

---

## Objectives of the Project
- To help students organize academic tasks in one system
- To reduce missed deadlines
- To improve time management and productivity
- To demonstrate proper application of the SDLC in software development

---

## Software Development Life Cycle (SDLC) Implementation

### 1. Requirement Analysis
At this stage, the system requirements were identified and documented.

#### Functional Requirements
- Students can add a new task
- Students can view all tasks
- Students can update task details
- Students can delete tasks
- Each task must include:
  - Task ID
  - Task Title
  - Task Description
  - Due Date
  - Task Status (Pending / Completed)

#### Non-Functional Requirements
- The system should be easy to use
- The system should store tasks reliably
- The system should be scalable for future improvements
- The system should respond quickly to user actions

---

### 2. System Design
The system design defines how the **Student Task Management System** works internally.

#### System Architecture
- User Interface (CLI / Web Interface)
- Application Logic (Task Management Functions)
- Data Storage (In-memory storage or database)

#### Data Design
**Task Entity**
- task_id
- task_title
- task_description
- due_date
- status

#### Use Case Design
- Add Task
- View Tasks
- Update Task
- Delete Task
- Mark Task as Completed

---

### 3. Implementation (Coding)
The **Student Task Management System** was implemented using programming concepts such as:
- Functions
- Conditional statements
- Loops
- Data structures (lists / dictionaries / database tables)

#### Key Modules Implemented
- `add_task()`
- `view_tasks()`
- `update_task()`
- `delete_task()`
- `mark_task_completed()`

All module names used in the design phase match the names used in the actual implementation.

---

### 4. Testing
Testing was carried out to ensure the system works as expected.

#### Types of Testing Performed
- **Unit Testing** – Testing individual functions such as task creation and deletion
- **Integration Testing** – Ensuring modules work together correctly
- **User Acceptance Testing (UAT)** – Confirming the system meets student requirements

#### Test Cases
- Adding a task with valid details
- Updating an existing task
- Deleting a task
- Viewing task list
- Handling invalid task IDs

---

### 5. Deployment
The **Student Task Management System** was deployed by pushing the source code to a **GitHub repository**, making it accessible for:
- Version control
- Collaboration
- Evaluation and grading

---

### 6. Maintenance
Maintenance ensures the system remains useful over time.

#### Maintenance Activities
- Fixing bugs
- Improving performance
- Adding new features (e.g., notifications, user login, database integration)
- Updating documentation

---

## Tools and Technologies Used
- Programming Language: (Python / Java / C++ / JavaScript – depending on your implementation)
- Version Control: Git & GitHub
- Development Environment: VS Code
- Documentation: Markdown (README.md)

---

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/student-task-management-system.git
