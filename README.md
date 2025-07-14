# Project Management Tool - Excel Template

## Overview

This Project Management Tool is a comprehensive Excel-based solution designed to help individuals and teams organize, track, and complete projects efficiently. It provides an integrated environment where you can manage project schedules, task assignments, progress tracking, and visualize project timelines—all within a single Excel workbook.

---

## Features

- **Project Settings:** Define multiple projects with start and end dates, set priorities, phases, and status categories.
- **Task Management:** Add tasks with detailed information such as project association, phase, priority, status, assignee, and start/end dates.
- **Overview Dashboard:** Get a snapshot of total, ongoing, past, and upcoming projects, along with progress summaries.
- **Timeline View:** Visualize project timelines in a calendar-like layout to track deadlines and milestones.
- **Dashboard:** Interactive project dashboard showing key information like completion percentage and task status breakdown.
- **Kanban Board:** Visual task management board with categorized columns such as Not Started, In Progress, Complete, On Hold, and Cancelled.
- **Data Validation:** Use of dropdown lists for consistent and error-free input of project phases, priorities, and statuses.
- **Instructions & Help:** A dedicated "READ ME" sheet providing clear usage instructions and tips to refresh data and maintain accuracy.

---

## How I Built This Tool

1. **Planning & Design:**
   - Identified core project management needs: task tracking, timeline visualization, project status monitoring, and easy data entry.
   - Designed the structure with separate sheets for Settings, Tasks, Overview, Dashboard, Timeline, and Kanban to keep the workbook organized.
   - Planned dropdown lists for statuses, priorities, and phases to maintain consistency and reduce errors in user inputs.

2. **Data Structure Setup:**
   - Created tables in Excel for Projects and Tasks, ensuring each has all necessary attributes.
   - Used Excel tables and structured references to enable dynamic ranges for dropdown menus and formulas.

3. **Data Validation & Dropdowns:**
   - Implemented dropdown menus for fields such as project name, task priority, status, and phase by linking them to predefined lists on the Settings sheet.
   - Used data validation to restrict inputs and guide users in selecting valid options.

4. **Formulas & Calculations:**
   - Developed formulas to calculate project duration, task counts, completion percentages, and categorize projects into ongoing, past, or upcoming.
   - Used conditional formatting to visually differentiate project statuses and highlight important dates.

5. **Visual Dashboards:**
   - Created overview and dashboard sheets with clear, at-a-glance summaries of projects and tasks.
   - Implemented timeline visualization using cell formatting and date formulas to display project phases across calendar weeks.

6. **Kanban Board Setup:**
   - Structured the Kanban board to dynamically reflect task statuses, enabling users to track progress visually.
   - Linked Kanban columns to task data using Excel formulas or filters.

---

## How to Use

1. **Start with the Settings Sheet:**
   - Enter your project names along with start and end dates.
   - Customize project statuses, priorities, and phases as needed in the respective lists.

2. **Add Tasks:**
   - Go to the Tasks sheet and input tasks.
   - Use dropdowns to select the project, phase, priority, status, and assignee.
   - Fill in task descriptions and date fields.

3. **Refresh Data:**
   - After entering or modifying tasks or project data, go to the `Data` tab in Excel and click `Refresh All` to update dashboards and calculations.
   - This step is crucial for ensuring all visualizations and summaries are current.

4. **Explore Dashboards and Views:**
   - Use the Overview sheet for a summary of your projects.
   - Check the Dashboard for detailed project info and task breakdowns.
   - View the Timeline for a visual calendar of project phases.
   - Utilize the Kanban board for a quick look at task progress by status.

---

## Tips & Recommendations

- Save a backup before making major changes.
- Use consistent naming conventions for projects and tasks to avoid confusion.
- Regularly refresh data after updating any entries to keep all sheets synchronized.
- Customize dropdown lists in the Settings sheet to match your team's terminology or project methodology.
- Share the Excel file with your team through a shared drive or collaboration platform for collective updates.

---

## Future Enhancements

- Automate task status updates with VBA macros for smoother workflow.
- Add conditional formatting to highlight overdue tasks and milestones.
- Integrate with external data sources or project management APIs.
- Build reports and charts for deeper analytics.

---

## Contact

Created by Yukta Chavan  
---

Thank you for checking out this tool! I hope it helps you manage your projects more effectively.
