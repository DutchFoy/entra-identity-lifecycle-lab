# Microsoft Entra ID | Identity Lifecycle Lab

### Joiner–Mover–Leaver Management · Access Control · Security Validation

## About This Project

I'm building this lab as part of my transition into Identity and Access Management (IAM), with a particular interest in identity governance and how organizations manage employee access.

The project follows a fictional hospitality company, Northstar Hospitality Group, through three common identity events: hiring an employee, moving someone into a different role, and removing access when they leave.

I'm using Microsoft Entra ID to learn the administrative side of those processes, along with the security decisions that come with them.

What interests me most is what happens beyond the initial configuration.

Removing someone from a security group, for example, is straightforward. But does that change actually remove the access they no longer need? What happens if another group still grants the same permission, or an application manages its own accounts?

Those are the kinds of questions I want to explore as I build this project.

## What I'm Building

The lab is organized around three workflows:

### Joiner — New Employee
Create an identity, assign appropriate access, and verify that the employee receives what their role requires without unnecessary privileges.

### Mover — Employee Transfer
Update job-related access, remove permissions that are no longer needed, and check for access that may have carried over from the previous role.

### Leaver — Employee Separation
Disable access, address existing sessions and connected resources, and verify that the expected restrictions are in place.

## How I'm Approaching It

I'm starting with established IAM practices, learning why they're used, and testing how well they work.

For each workflow, I want to answer a few practical questions:

- What is supposed to happen?
- What could be overlooked?
- How can I verify the result?
- What would I do if part of the process failed?

I'm also interested in what happens when an administrative task reports success but the underlying security issue isn't fully resolved.

The goal isn't to create a more complicated process. It's to understand the existing one well enough to recognize its limitations and improve it where needed.

## Lab Environment

**Fictional organization:** Northstar Hospitality Group

**Planned technologies:**
- Microsoft Entra ID
- Microsoft 365, where available
- PowerShell
- Microsoft Graph
- GitHub for documentation and version control

The lab uses fictional employees and resources. Some scenarios may be simulated where licensing or environment limitations prevent full implementation.

## Project Progress

| Component | Status |
|---|---|
| Project repository | Created |
| Microsoft Entra lab environment | Setup in progress |
| Identity and group design | Planned |
| Joiner workflow | Planned |
| Mover workflow | Planned |
| Leaver workflow | Planned |
| PowerShell automation | Planned |
| Failure testing and validation | Planned |
| Final documentation | Planned |

## Documentation and Evidence

As the lab develops, I'll add the configuration steps, scripts, screenshots, test cases, and results.

I'll distinguish between configurations I've actually tested, scenarios I've simulated, and improvements I've identified but haven't implemented.

I also plan to document mistakes and unexpected results. They're part of the learning process, and understanding why something didn't work is often as useful as getting it right the first time.

---

**Project type:** Independent educational lab  
**Focus:** Identity and Access Management / Identity Governance  
**Status:** In development
