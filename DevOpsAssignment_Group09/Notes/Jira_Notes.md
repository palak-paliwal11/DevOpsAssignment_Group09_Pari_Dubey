# Jira Notes – DevOps Assignment

## 1. Introduction

**Jira** is a project management and issue-tracking tool developed by Atlassian. It is widely used by software development teams to plan projects, manage tasks, track bugs, and monitor project progress.

Jira supports Agile methodologies such as **Scrum** and **Kanban**.

---

## 2. Purpose of Using Jira

Jira can be used to:

* Create and manage project tasks
* Track bugs and issues
* Assign work to team members
* Set priorities and deadlines
* Track the status of tasks
* Organize work into sprints
* Monitor project progress
* Maintain a history of project activities

---

## 3. Important Jira Concepts

### Project

A project is a workspace where all tasks, bugs, and activities related to a particular project are managed.

### Issue

An issue represents a unit of work in Jira.

Common issue types include:

* **Task** – A specific piece of work
* **Bug** – A problem or error that needs to be fixed
* **Story** – A feature or requirement from the user's perspective
* **Epic** – A large feature or collection of related tasks

### Backlog

The backlog contains tasks and issues that are planned but have not yet been completed.

### Sprint

A sprint is a fixed period during which a team works on a selected set of tasks.

### Assignee

The person responsible for completing an issue.

### Priority

Priority indicates the importance of an issue.

Examples:

* Highest
* High
* Medium
* Low
* Lowest

---

## 4. Jira Workflow

A basic Jira workflow can be represented as:

**To Do → In Progress → Done**

### To Do

The task has been created but work has not started.

### In Progress

The task is currently being worked on.

### Done

The task has been completed.

---

## 5. Creating an Issue in Jira

The following steps can be used to create an issue:

1. Open the Jira project.
2. Click on **Create**.
3. Select the appropriate issue type.
4. Enter the issue summary.
5. Provide a detailed description.
6. Set the priority.
7. Assign the issue to a team member.
8. Add labels if required.
9. Set the due date if required.
10. Click **Create**.

---

## 6. Example Issues

The following issues can be created for a software project:

| Issue Type | Summary                     | Priority | Status      |
| ---------- | --------------------------- | -------- | ----------- |
| Task       | Create project repository   | High     | Done        |
| Task       | Design project structure    | High     | Done        |
| Task       | Implement frontend          | Medium   | In Progress |
| Task       | Configure deployment        | High     | To Do       |
| Bug        | Fix login validation        | High     | To Do       |
| Task       | Write project documentation | Medium   | To Do       |

---

## 7. Jira Board

A Jira board provides a visual representation of project tasks.

A basic board can contain:

**TO DO**

* Create repository
* Configure development environment
* Design UI

**IN PROGRESS**

* Implement application features

**DONE**

* Project setup
* Initial GitHub repository creation

The board helps team members understand what work is pending, what is currently being performed, and what has been completed.

---

## 8. Jira and GitHub Integration

Jira and GitHub can be used together in a DevOps workflow.

A developer can:

1. Create an issue in Jira.
2. Get the Jira issue key.
3. Create a Git branch using the issue key.
4. Make changes to the project.
5. Commit the changes.
6. Push the branch to GitHub.
7. Create a Pull Request.
8. Review and merge the Pull Request.
9. Update the Jira issue status.

### Example

Suppose the Jira issue key is:

`DEV-12`

A corresponding Git branch can be:

```bash
git checkout -b DEV-12-login-feature
```

A commit can reference the issue:

```bash
git add .
git commit -m "DEV-12 Add login feature"
git push origin DEV-12-login-feature
```

This makes it easier to connect development work with Jira tasks.

---

## 9. Agile Methodology

Jira supports Agile project management.

In the **Scrum** approach, work is divided into sprints.

A typical Scrum workflow is:

**Product Backlog → Sprint Planning → Sprint → Daily Updates → Sprint Review → Retrospective**

### Product Backlog

Contains all planned features, improvements, and bugs.

### Sprint Planning

The team selects issues that will be completed during the sprint.

### Sprint

The team works on the selected issues.

### Sprint Review

The completed work is demonstrated and reviewed.

### Retrospective

The team discusses what went well, what went wrong, and how the next sprint can be improved.

---

## 10. Benefits of Jira

Jira provides several benefits:

* Better task management
* Improved team collaboration
* Easy issue tracking
* Clear project visibility
* Sprint management
* Priority management
* Progress tracking
* Integration with development tools
* Better organization of software projects

---

## 11. Jira in DevOps

Jira can be integrated into a DevOps workflow along with tools such as GitHub and CI/CD platforms.

A simplified DevOps workflow is:

**Jira Issue → Git Branch → Code → Commit → GitHub → Pull Request → CI/CD → Deployment → Jira Update**

This provides traceability between project requirements, source code, testing, and deployment.

---

## 12. Conclusion

Jira is an effective tool for managing software development projects. It helps teams organize tasks, track bugs, manage sprints, assign responsibilities, and monitor project progress.

When Jira is combined with GitHub and CI/CD tools, it provides better visibility and traceability throughout the software development lifecycle.

---