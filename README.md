# Ex.No.8 – Develop a Prompt-Based Automated Workflow

# Date: 16.09.2026

# Register no: 212224040141

## Aim

To develop an automated workflow using structured prompts and Large Language Models (LLMs) for solving practical engineering and organizational tasks such as email writing, meeting minutes, task planning, project scheduling, requirement documentation, and FAQ generation.

## AI Tools Required

* ChatGPT
* Gemini
* Microsoft Copilot
* Any other Generative AI tool

## Explanation

Prompt engineering can be used to automate repetitive technical and organizational activities by providing structured instructions to a Large Language Model.

In this experiment, structured prompts are designed to convert user-provided information into useful outputs such as emails, meeting minutes, task plans, schedules, requirement documents, and FAQs.

The workflow is demonstrated using the engineering example:

**College Symposium Management**

### Input Information

* **Symposium Name:** TechNova 2026
* **Date:** 15 October 2026
* **Venue:** Main Auditorium, Engineering Block
* **Theme:** Innovation for a Sustainable Future
* **Events:** Paper Presentation, Project Expo, Coding Challenge, Robotics Challenge
* **Registration Deadline:** 5 October 2026
* **Expected Participants:** 500 students
* **Organizing Teams:** Registration, Technical, Logistics, Hospitality, Documentation
* **Event Coordinator:** Symposium Organizing Committee

---

# Procedure

## Step 1 – Define the Workflow Requirements

The objective is to automate common symposium management activities using structured prompts.

The application accepts symposium information and generates the required documentation.

The workflow is:

**Input Information → Structured Prompt → LLM → Generated Output → Evaluation → Refinement → Final Output**

---

# Step 2 – Email Writing

### Prompt

> Act as a professional college event coordinator. Using the following verified information, write an announcement email for students about the TechNova 2026 symposium. Include the symposium name, theme, date, venue, major events, registration deadline, and important instructions. Keep the email concise, friendly, professional, and easy to read. Do not invent any information.

### Sample Generated Output

**Subject: TechNova 2026 – Registration Open**

Dear Students,

We are pleased to announce **TechNova 2026**, a college technical symposium based on the theme **“Innovation for a Sustainable Future.”**

The symposium will be conducted on **15 October 2026** at the **Main Auditorium, Engineering Block**.

The major events include:

* Paper Presentation
* Project Expo
* Coding Challenge
* Robotics Challenge

Students interested in participating are requested to complete their registration before the **registration deadline of 5 October 2026**.

The symposium is expected to bring together around **500 student participants** and provide an opportunity to demonstrate technical knowledge, creativity, and problem-solving skills.

For further information, students may contact the **Symposium Organizing Committee**.

We look forward to your active participation in TechNova 2026.

Regards,
**Symposium Organizing Committee**

### Evaluation

The structured prompt generated a complete announcement containing all the required event information. The output is suitable for student communication after verifying the final event details.

---

# Step 3 – Meeting Minutes

### Input

A planning meeting was conducted to discuss event finalization, registration, venue preparation, technical equipment, hospitality, and documentation.

### Prompt

> Convert the following symposium planning information into formal meeting minutes. Include meeting title, date, agenda, decisions made, assigned responsibilities, deadlines, and pending actions. Use a clear structured format and do not add information that is not provided.

### Sample Generated Output

# Minutes of Meeting – TechNova 2026

**Meeting:** TechNova 2026 Symposium Planning Meeting
**Purpose:** Planning and coordination of the technical symposium

### Agenda

1. Finalization of technical events
2. Student registration
3. Venue preparation
4. Technical equipment
5. Hospitality arrangements
6. Documentation

### Decisions Made

* The symposium will include Paper Presentation, Project Expo, Coding Challenge, and Robotics Challenge.
* The Main Auditorium in the Engineering Block will be used as the primary venue.
* Student registration will remain open until 5 October 2026.
* Technical equipment requirements will be coordinated by the Technical Team.
* Hospitality arrangements will be handled by the Hospitality Team.
* Event records and documentation will be maintained by the Documentation Team.

### Responsibilities

| Responsibility           | Assigned Team      |
| ------------------------ | ------------------ |
| Participant registration | Registration Team  |
| Venue arrangements       | Logistics Team     |
| Technical equipment      | Technical Team     |
| Hospitality              | Hospitality Team   |
| Event documentation      | Documentation Team |

### Pending Actions

* Finalize equipment requirements.
* Complete registration arrangements.
* Confirm venue setup requirements.
* Prepare documentation materials.

### Evaluation

The prompt successfully converted unstructured meeting information into organized meeting minutes with decisions, responsibilities, and pending actions.

---

# Step 4 – Task Planning

### Prompt

> Create a detailed task plan for managing TechNova 2026. Divide the activities into preparation, event-day, and post-event phases. Include task, priority, responsible team, dependency, and expected completion. Use only the provided symposium information.

### Sample Generated Output

# TechNova 2026 – Task Plan

| No. | Task                            | Phase       | Priority | Responsible Team     | Dependency          |
| --- | ------------------------------- | ----------- | -------- | -------------------- | ------------------- |
| 1   | Finalize event list             | Preparation | High     | Organizing Committee | —                   |
| 2   | Prepare registration process    | Preparation | High     | Registration Team    | Event list          |
| 3   | Promote symposium               | Preparation | High     | Organizing Committee | Event details       |
| 4   | Prepare venue                   | Preparation | High     | Logistics Team       | Venue confirmation  |
| 5   | Arrange technical equipment     | Preparation | High     | Technical Team       | Venue requirements  |
| 6   | Manage participant registration | Event Day   | High     | Registration Team    | Registration system |
| 7   | Coordinate technical events     | Event Day   | High     | Technical Team       | Equipment setup     |
| 8   | Manage hospitality              | Event Day   | Medium   | Hospitality Team     | Participant details |
| 9   | Record event activities         | Event Day   | Medium   | Documentation Team   | Event execution     |
| 10  | Prepare final documentation     | Post-event  | Medium   | Documentation Team   | Event completion    |

### Evaluation

The output clearly identifies responsibilities, priorities, and dependencies, making it useful for practical event management.

---

# Step 5 – Project Scheduling

### Prompt

> Develop a chronological project schedule for TechNova 2026 from initial preparation to post-event completion. Include activity, timeline, responsible team, and milestone. Use the known symposium dates and registration deadline without inventing specific dates for activities that were not provided.

### Sample Generated Output

# TechNova 2026 – Project Schedule

| Activity                 | Timeline               | Responsible Team     | Milestone               |
| ------------------------ | ---------------------- | -------------------- | ----------------------- |
| Event planning           | Before symposium       | Organizing Committee | Plan finalized          |
| Event finalization       | Before symposium       | Organizing Committee | Events confirmed        |
| Registration preparation | Before 5 Oct 2026      | Registration Team    | Registration opened     |
| Participant registration | Until 5 Oct 2026       | Registration Team    | Registration closed     |
| Venue preparation        | Before 15 Oct 2026     | Logistics Team       | Venue ready             |
| Technical preparation    | Before 15 Oct 2026     | Technical Team       | Equipment ready         |
| Hospitality preparation  | Before 15 Oct 2026     | Hospitality Team     | Hospitality ready       |
| Symposium execution      | 15 Oct 2026            | All Teams            | TechNova 2026 conducted |
| Documentation            | During and after event | Documentation Team   | Final records prepared  |

### Evaluation

The generated schedule provides a chronological overview of the symposium and clearly identifies important milestones.

---

# Step 6 – Requirement Documentation

### Prompt

> Act as a software requirements analyst. Prepare a Software Requirement Specification for a College Symposium Management System. Include system users, functional requirements, non-functional requirements, inputs, outputs, registration, event management, notifications, attendance, and reporting. Organize the information using appropriate headings and tables.

### Sample Generated Output

# Software Requirement Specification

## College Symposium Management System

### 1. System Objective

The system is designed to simplify the management of college symposium activities including participant registration, event management, communication, attendance, and report generation.

### 2. Users

The system supports the following users:

* Administrator
* Event Coordinator
* Volunteer
* Participant

### 3. Functional Requirements

**FR1 – User Registration**

The system shall allow participants to register for the symposium.

**FR2 – Event Registration**

The system shall allow participants to select available symposium events.

**FR3 – Event Management**

The administrator shall be able to create and manage symposium events.

**FR4 – Participant Management**

The system shall maintain participant information.

**FR5 – Notifications**

The system shall provide important event announcements and notifications.

**FR6 – Attendance**

The system should support participant attendance recording.

**FR7 – Reporting**

The system shall generate event-related reports.

### 4. Non-Functional Requirements

| Requirement | Description                                       |
| ----------- | ------------------------------------------------- |
| Usability   | The system should be easy to use                  |
| Performance | Common operations should respond efficiently      |
| Security    | Participant information should be protected       |
| Reliability | The system should operate consistently            |
| Scalability | The system should support increasing participants |

### 5. Inputs

* Participant details
* Event details
* Registration information
* Attendance information
* Event schedules

### 6. Outputs

* Registration confirmation
* Participant lists
* Event schedules
* Attendance records
* Event reports

### Evaluation

The prompt generates a structured starting point for software requirements. The requirements should be reviewed by the project team before implementation.

---

# Step 7 – FAQ Generation

### Prompt

> Generate frequently asked questions for TechNova 2026. Cover registration, date, venue, events, participation, registration deadline, and contact information. Provide short and clear answers. Use only the information provided.

### Sample Generated Output

# Frequently Asked Questions – TechNova 2026

### 1. What is TechNova 2026?

TechNova 2026 is a college technical symposium based on the theme **“Innovation for a Sustainable Future.”**

### 2. When will TechNova 2026 be conducted?

The symposium will be conducted on **15 October 2026**.

### 3. Where will the symposium be conducted?

The event will be conducted at the **Main Auditorium, Engineering Block**.

### 4. What events are available?

The symposium includes:

* Paper Presentation
* Project Expo
* Coding Challenge
* Robotics Challenge

### 5. When is the registration deadline?

The registration deadline is **5 October 2026**.

### 6. How many participants are expected?

Approximately **500 students** are expected to participate.

### 7. Who can provide further information?

Students can contact the **Symposium Organizing Committee** for further information.

### Evaluation

The prompt generated a concise FAQ that addresses common participant questions and can be used for an event website or information desk.

---

# Step 8 – Iterative Prompting

The generated outputs are improved through multiple prompting stages.

## Initial Prompt

> Write an email for a college symposium.

### Initial Output

> TechNova 2026 is a college symposium. Students are invited to participate in various technical events.

The output is too general and does not contain enough event-specific information.

---

## Improved Prompt

> Write an email announcing TechNova 2026. Include the theme, date, venue, events, registration deadline, and important instructions.

### Improved Output

The LLM generates a more detailed announcement containing the required event information.

---

## Final Refinement Prompt

> Review the generated email for grammar, clarity, completeness, readability, and factual consistency. Use only the information provided. Remove unnecessary repetition and maintain a friendly professional tone.

### Final Output

**Subject: TechNova 2026 – Registration Open**

Dear Students,

We are pleased to announce **TechNova 2026**, a college technical symposium based on the theme **“Innovation for a Sustainable Future.”**

The symposium will be conducted on **15 October 2026** at the **Main Auditorium, Engineering Block**.

The major events include:

* Paper Presentation
* Project Expo
* Coding Challenge
* Robotics Challenge

The registration deadline is **5 October 2026**. Students interested in participating are encouraged to complete their registration before the deadline.

For further information, please contact the **Symposium Organizing Committee**.

We look forward to your participation in TechNova 2026.

Regards,
**Symposium Organizing Committee**

---

# Step 9 – Complete Automated Workflow

The complete prompt-based workflow is:

```text
                 COLLEGE SYMPOSIUM INFORMATION
                            ↓
                   INPUT PROCESSING
                            ↓
                 SELECT REQUIRED TASK
                            ↓
              ┌─────────────┼─────────────┐
              ↓             ↓             ↓
           EMAIL       MEETING MINUTES   TASK PLAN
              ↓             ↓             ↓
          SCHEDULING → REQUIREMENTS → FAQ
              ↓
           LLM GENERATION
              ↓
        OUTPUT EVALUATION
              ↓
       ITERATIVE PROMPTING
              ↓
       FINAL VALIDATED OUTPUT
```

---

# Step 10 – Comparison of Prompting Approaches

| Prompt Type       | Example                                     | Output Quality |
| ----------------- | ------------------------------------------- | -------------- |
| Basic Prompt      | “Write an email for a symposium.”           | Moderate       |
| Structured Prompt | Specifies required sections and information | Good           |
| Role-Based Prompt | “Act as a professional event coordinator.”  | Very Good      |
| Iterative Prompt  | Generate → Review → Refine                  | Excellent      |

---

# Step 11 – Evaluation

The outputs are evaluated using the following criteria:

| Criterion    | Description                         |
| ------------ | ----------------------------------- |
| Accuracy     | Correctness of event information    |
| Completeness | Inclusion of required information   |
| Clarity      | Ease of understanding               |
| Readability  | Organization and language quality   |
| Usefulness   | Practical application of the output |

### Evaluation Table

| Automated Task            | Accuracy | Completeness | Clarity   | Readability | Usefulness |
| ------------------------- | -------- | ------------ | --------- | ----------- | ---------- |
| Email Writing             | Good     | Good         | Very Good | Very Good   | Very Good  |
| Meeting Minutes           | Good     | Very Good    | Very Good | Good        | Very Good  |
| Task Planning             | Good     | Very Good    | Very Good | Very Good   | Excellent  |
| Project Scheduling        | Good     | Very Good    | Very Good | Good        | Excellent  |
| Requirement Documentation | Good     | Excellent    | Good      | Good        | Excellent  |
| FAQ Generation            | Good     | Good         | Excellent | Very Good   | Very Good  |

---

# Observations

1. Basic prompts produce general responses with limited structure.
2. Structured prompts generate more complete and organized outputs.
3. Role-based prompts improve the suitability of content for a particular task.
4. Iterative prompting improves grammar, clarity, completeness, and readability.
5. Different technical tasks require different prompt structures.
6. Prompt-based automation reduces repetitive documentation work.
7. Generated outputs should be reviewed before being used in real-world situations.
8. The workflow can be reused for other engineering projects by changing the input information and prompts.

# Deliverable

## Automated Workflow Documentation

The final submission contains:

1. Engineering scenario description
2. Input information
3. Structured prompts
4. Complete AI-generated outputs
5. Initial and refined prompts
6. Workflow diagram
7. Evaluation table
8. Observations
9. Final validated outputs

# Conclusion

The experiment demonstrated the use of structured prompting and Large Language Models to automate common technical and organizational tasks. Using **College Symposium Management** as the engineering scenario, prompts were developed for email writing, meeting minutes, task planning, project scheduling, requirement documentation, and FAQ generation.

The experiment also demonstrated that iterative prompting can improve the quality, clarity, completeness, and readability of AI-generated content. The same workflow can be adapted to other engineering applications such as drone surveys and project management.

# Result

The prompt-based automated workflow was successfully developed and executed. The system generated complete outputs for email writing, meeting minutes, task planning, project scheduling, requirement documentation, and FAQ generation, resulting in a reusable **Automated Workflow Documentation**.
