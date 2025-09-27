# Customer Support Project

A ClickUp-based workspace for triaging, routing, and closing customer tickets. This README documents the setup, workflow, and screenshots for quick onboarding.

## 📁 Structure
- **Space:** Customer Support  
- **List:** Inbox (all tickets are created and worked here)  
- **Views:** List, Board (Support Board), Table, Dashboard

## 🧭 Workflow (Statuses)


**Meaning**
- **NEW** — ticket just created.
- **ASSIGNED** — an owner is set (via rules).
- **IN PROGRESS** — being worked.
- **WAITING ON CUSTOMER** — follow-up info needed.
- **RESOLVED** — solution delivered.
- **CLOSED** — final state.

## 🧩 Custom Fields
- **Ticket Type**: Billing, Login/Access, Bug, Feature Request, Shipping/Delivery, General  
- **Priority**: Low, Normal, High, Urgent  
- **Channel**, **Customer Name**, **Source**  
- **SLA Due Date / SLA Due At** *(optional – currently not enforced)*

## ⚙️ Automations
- **Auto-assign by Ticket Type**: routes tickets (e.g., Billing) to the designated owner.  
- **(Optional)** Due date arrives → **Change status to CLOSED** (use if you want auto-closing).

## 👀 Screenshots

### Inbox – List & Columns
![Inbox List](assets/inbox_list_columns.png)

### Board – Drag & Drop by Status
![Board Status Flow](assets/board_status_flow.png)

### Dashboard – Overview (Top)
![Dashboard Top](assets/dashboard_top.png)

### Dashboard – Tasks & Activity (Bottom)
![Dashboard Bottom](assets/dashboard_bottom.png)

### Table View – Bulk Editing
![Table View](assets/table_view_bulk.png)

### Task Detail – Summary & Meta
![Task Detail Top](assets/task_detail_top.png)

### Task Detail – Custom Fields
![Task Detail Fields](assets/task_detail_fields.png)

### Automation – Auto-Assign (Example)
![Automation Assign](assets/automation_assign_billing.png)

### Automation – SLA Due (Example – optional)
![Automation SLA](assets/automation_sla_due_example.png)

### Inbox – NEW & ASSIGNED Buckets
![Inbox Buckets](assets/inbox_new_assigned.png)

### Board – Full Columns
![Board Columns](assets/board_all_columns.png)

## 📝 SOP (Daily)
1. Triage **NEW** → set **Ticket Type** & **Priority**, owner auto-assigns.
2. Start work → **IN PROGRESS**.
3. Need info → **WAITING ON CUSTOMER**.
4. Solution delivered → **RESOLVED**, then **CLOSED**.

## 📊 Dashboard Tips
- Add **Tasks by Ticket Type** and **Tasks by Priority** widgets for quick mix/urgency views.
- If an item doesn’t appear, edit the widget **Filters** to include the **NEW** status.

---

> Owner: You (temporary) · List: Customer Support / Inbox

# 📊 Customer Support Project Dashboard

This dashboard provides a visual summary and task breakdown for the Customer Support team. It tracks task statuses, assignments, workload distribution, and task progress over the week.

---

### 🖼️ Screenshot 1: Top Overview Section
![Dashboard Screenshot 1](dashboard-overview.png)

---

## 🧠 AI Executive Summary

### Executive Summary
> There are no updates or tasks recorded in the system for the past week.

### Key Efforts & Initiatives
> There are no active tasks.

---

## 📌 Task Overview

| Status       | Count |
|--------------|-------|
| 🟤 Unassigned | 0     |
| 🔵 In Progress | 1     |
| ✅ Completed   | 1     |

### 📊 Workload by Status
A progress bar displays workload distribution with color coding:
- Gray: Open
- Blue: In Progress
- Orange: Completed
- Red: Overdue or Closed

---

### 🖼️ Screenshot 2: Task Distribution by Assignee
![Dashboard Screenshot 2](tasks-by-assignee.png)

---

## 👤 Tasks by Assignee

### 📈 Total Tasks by Assignee
- 🟥 Mahnoor Naeem: **50%**
- ⬛ Ayesha: **50%**

### 📉 Open Tasks by Assignee
| Assignee       | Tasks |
|----------------|-------|
| Mahnoor Naeem  | 7     |
| Ayesha         | 6     |

### ✅ Tasks Completed This Week
> No results

---

### 🖼️ Screenshot 3: Tasks Due or Overdue List View
![Dashboard Screenshot 3](tasks-due.png)

---

## ⏳ Tasks Due This Week or Overdue

### 📅 Due Today

| Task Name                                          | Assignee | Priority |
|---------------------------------------------------|----------|----------|
| App crashing on startup                           | Ayesha   | 🔴 Urgent |
| Password reset request                            | Ayesha   | 🔵 Normal |
| Account locked due to multiple login attempts     | Mahnoor  | 🟠 High   |

### ✅ Done (Yesterday)

| Task Name                        | Assignee | Priority |
|---------------------------------|----------|----------|
| Customer cannot reset password  | Ayesha   | 🟢 Low    |

---

## 🛠 Dashboard Features

- **Auto Refresh:** Enabled
- **Filters:** 2 active filters (Due date, Closed status)
- **Edit Mode:** Enabled
- **Report Scheduling:** Available
- **Cards:** Customizable with charts and task lists

---

### 📌 Notes
- The dashboard is interactive and designed for real-time collaboration.
- Task assignment and priority help ensure quick resolution of customer issues.

