# osTicket Help Desk Lab

## Overview

This is an in-progress help desk ticketing lab built with osTicket in a local Docker environment.

The goal is to show practical entry-level IT support skills: working inside a ticketing system, documenting user requests, organizing issues by type, communicating clearly, and building a realistic support workflow.

This repository is being built as a portfolio project for Help Desk, IT Support Specialist, Technical Support, and SaaS Support roles.

## Current Status

**Status:** In progress  
**Current phase:** osTicket is running locally with Docker and the first proof screenshot has been captured.  
**Next step:** Log in as an agent/admin, capture the dashboard, configure departments/help topics, then create and resolve realistic support tickets.

## Skills Demonstrated

- Help desk ticketing workflow
- Ticket intake and categorization
- IT support documentation
- User communication
- Troubleshooting note-taking
- Status and resolution tracking
- Screenshot-based technical documentation
- Docker-based local lab setup
- Git and GitHub project presentation

## Tools Used

- osTicket
- Docker Desktop
- Docker Compose
- MySQL container
- Windows PowerShell
- Git
- GitHub
- ShareX / screenshot capture tool
- Markdown documentation

## Lab Progress

| Step | Status | Description |
|---|---|---|
| Create local project repo | Complete | Created the local Git repository and project folder structure. |
| Set up screenshot and ticket folders | Complete | Added folders for setup screenshots, ticket screenshots, notes, and ticket writeups. |
| Install osTicket locally | Complete | osTicket is running locally through Docker. |
| Capture login proof | Complete | Captured the osTicket Agent Login page. |
| Capture agent dashboard | Complete | Log in and capture the staff dashboard. |
| Configure departments/help topics | Complete | Add realistic support categories for the help desk lab. |
| Create realistic tickets | Planned | Build and resolve six support-ticket scenarios. |
| Polish final documentation | Planned | Add screenshots, case study notes, and resume-ready project bullets. |

## Screenshot Walkthrough

### 1. osTicket Agent Login Page

![osTicket Agent Login](screenshots/setup/01-osticket-agent-login.jpg)

**What was completed:**  
osTicket was launched locally in a Docker-based lab environment and the staff login page loaded successfully.

**What this proves:**  
The local ticketing system is running and accessible through the browser. This is the foundation for the rest of the help desk workflow lab.


### 2. osTicket Agent Dashboard

![osTicket Agent Dashboard](screenshots/setup/02-osticket-agent-dashboard.png)

**What was completed:**  
Logged into the osTicket staff portal and captured the agent dashboard.

**What this proves:**  
The staff account can access the working ticketing environment. This confirms the lab is ready for configuration work, ticket creation, and ticket resolution documentation.

### 3. osTicket Admin System Settings Page

![osTicket Admin System Settings](screenshots/admin-config/01-osticket-admin-system-settings.png)

**What was completed:**  
Opened the osTicket Admin Panel and captured the System Settings and Preferences page.

**What this proves:**  
The lab has working admin access and is ready for help desk configuration work, including departments, help topics, agents, users, tickets, and system preferences.

### 4. osTicket Departments Configured

![osTicket Departments Configured](screenshots/admin-config/02-osticket-departments-configured.png)

**What was completed:**  
Created and confirmed multiple departments in the osTicket Admin Panel, including IT Support, Hardware / Software Support, Account Support, and Maintenance.

**What this proves:**  
The lab now has department structure in place for ticket routing and future help desk workflow configuration.

### 5. osTicket Help Topics Configured

![osTicket Help Topics Configured](screenshots/admin-config/03-osticket-help-topics-configured.png)

**What was completed:**  
Configured realistic help topics in the osTicket Admin Panel, including Login Issue, Password Reset, Shared Folder Access, Slow Computer, Software Install Request, and New User Setup.

**What this proves:**  
The lab now has support request categories that can be used to route and document realistic help desk tickets.

### 6. osTicket Test User Created

![osTicket Test User Created](screenshots/admin-config/04-osticket-test-user-created.png)

**What was completed:**  
Created a test customer/user account named Taylor Morgan for future ticket scenarios.

**What this proves:**  
The lab now has a realistic end user/customer profile that can be used to create and document support tickets.

### 7. Ticket 01 Created - User Cannot Log In

![Ticket 01 Created Confirmation](screenshots/tickets/01-ticket-created-confirmation.png)

**What was completed:**  
Created the first realistic support ticket for a user who cannot log in to their company account.

**What this proves:**  
The lab now shows ticket intake from an end user, including the request summary, help topic, and ticket creation confirmation.

### 8. Ticket 01 Detail View Opened

![Ticket 01 Detail Opened](screenshots/tickets/02-ticket-detail-opened.png)

**What was completed:**  
Opened the newly created login issue ticket inside the osTicket staff panel.

**What this proves:**  
The agent can access the ticket queue, open a user request, and begin documenting troubleshooting work inside the ticketing system.

### 9. Ticket 01 Internal Note Posted

![Ticket 01 Internal Note Posted](screenshots/tickets/03-ticket-internal-note-posted.png)

**What was completed:**  
Posted an internal troubleshooting note documenting the first triage step for the login issue.

**What this proves:**  
The ticket includes professional internal documentation, showing how an IT support agent records troubleshooting context before resolving the issue.

### 10. Ticket 01 Reply Posted and Resolved

![Ticket 01 Reply Posted and Resolved](screenshots/tickets/04-ticket-reply-posted-resolved.png)

**What was completed:**  
Posted a customer-facing reply and resolved the first login issue ticket.

**What this proves:**  
The lab now demonstrates the full ticket lifecycle: intake, triage, internal note, user communication, and resolution.

### 11. Ticket 02 Created - Password Reset Request

![Ticket 02 Created Confirmation](screenshots/tickets/05-ticket-02-created-confirmation.png)

**What was completed:**  
Created the second realistic support ticket for a user requesting help with a password reset.

**What this proves:**  
The lab now includes another common help desk scenario showing ticket intake, help topic categorization, and user request documentation for an account access issue.

## Next Screenshots To Capture

- [x] Agent dashboard
- [x] Admin dashboard
- [x] Department and help topic configuration
- [ ] Ticket queue
- [ ] Ticket detail page
- [ ] Internal note example
- [ ] Resolved ticket example

## Ticket Scenarios Planned

The finished lab will include six realistic support tickets:

1. **User Cannot Log In**  
   Simulates a common access issue where a user cannot log in and needs support triage.

2. **Password Reset Request**  
   Demonstrates identity-aware support workflow and password reset documentation.

3. **Shared Folder Access Request**  
   Shows how access issues can be documented and resolved through permissions/group access concepts.

4. **Slow Computer / Basic Triage**  
   Demonstrates basic troubleshooting questions, user communication, and escalation-style thinking.

5. **Software Install Request**  
   Simulates a request involving approval, installation, and documentation.

6. **New User Onboarding Request**  
   Shows how a help desk technician might document account setup, access needs, and onboarding tasks.

## What This Project Proves

This project shows that I can build and document a realistic help desk workflow using a professional ticketing platform.

For a hiring manager, this lab is meant to demonstrate that I understand the basics of working in an IT support queue: receiving tickets, documenting user issues, organizing work, communicating clearly, tracking progress, and closing tickets with useful resolution notes.

The project is still in progress, but the goal is to turn it into a clear screenshot-based case study that shows practical readiness for entry-level Help Desk or IT Support work.

## Planned Final Deliverables

- Complete osTicket setup screenshots
- Six realistic ticket scenarios
- Ticket queue screenshots
- Ticket detail screenshots
- Internal note examples
- Resolved ticket examples
- Written ticket case studies
- Resume-ready bullet points
- Final polished README for portfolio use

## Repository Structure

- `README.md`
- `case-study.md`
- `resume-bullets.md`
- `PROJECT_STATE.md`
- `SESSION_LOG.md`
- `docker-compose.yml`
- `screenshots/setup/`
- `screenshots/admin-config/`
- `screenshots/tickets/`
- `tickets/`

## Next Step

The next step is to log into osTicket, capture the staff dashboard, and continue building the lab configuration.








