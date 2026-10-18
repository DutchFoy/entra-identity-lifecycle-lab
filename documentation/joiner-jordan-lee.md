# Joiner Lab — Jordan Lee

## Scenario

Jordan Lee is a fictional HR Coordinator at Northstar Hospitality Group.

I created Jordan's account in Microsoft Entra ID, added the two security groups associated with the position, and checked the account settings afterward.

The goal was straightforward: establish the employee's identity and confirm that the intended group memberships were assigned without adding administrative privileges.

## Account Configuration

| Property | Verified value |
|---|---|
| Employee | Jordan Lee |
| Employee ID | NHG-002 |
| Job title | HR Coordinator |
| Department | Human Resources |
| Company | Northstar Hospitality Group |
| Employee type | Employee |
| Office location | Palm Springs |
| User type | Member |
| Account status | Enabled |

## Group Assignments

| Security group | Result |
|---|---|
| SG-All-Employees | Assigned |
| SG-HR | Assigned |
| SG-Finance | Not assigned |
| SG-Managers | Not assigned |

I created the account without any initial group assignments, then added the two required memberships.

Afterward, I checked Jordan's Groups page. Both groups appeared as expected, and neither Finance nor Managers was listed.

The account Overview also reported zero assigned directory roles, applications, and licenses.

## What I Verified

The account was enabled, the employment information matched the planned HR Coordinator position, and both intended group memberships were present.

I also checked that Jordan hadn't been added to the Finance or Managers groups.

These checks confirm the account configuration and group memberships. They don't establish what Jordan can actually access yet.

## Something Worth Testing

Jordan belongs to HR, but that doesn't necessarily mean every HR resource should be available to an HR Coordinator.

For example, onboarding documents may be appropriate while compensation records or employee investigations require more restrictive permissions.

Right now, `SG-HR` is a department-level group. We haven't assigned it access to any protected resources.

Once those resources are available, I want to test whether the group provides the right level of access or whether certain HR permissions should be separated by job responsibility.

## Current Status

**Verified:** Account creation, account status, employment properties, and group memberships.

**Reported by Entra:** Zero assigned directory roles, applications, and licenses.

**Not yet tested:** Resource-level permissions, sign-in behavior, MFA enforcement, and access restrictions.

The next step is to test how these group memberships affect access to actual resources rather than relying on group membership alone.
