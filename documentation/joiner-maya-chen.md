Joiner Lab — Maya Chen

Scenario

Maya Chen joins Northstar Hospitality Group as a Revenue Analyst in Finance.

The objective is to create her identity, assign the planned department groups, and confirm that no administrative roles were assigned.

Configuration

Property

Value

Employee

Maya Chen (fictional)

Department

Finance

Job title

Revenue Analyst

Employee ID

NHG-001

User type

Member

Account status

Enabled

SG-All-Employees

Assigned

SG-Finance

Assigned

Applications

0

Directory roles

0

Licenses

0

Verification

The account was created in Microsoft Entra ID on October 17, 2026.

After provisioning, the account Overview showed zero group memberships. The intended groups were then assigned, and both appeared on the user's Groups page.

The account Overview subsequently displayed two group memberships and zero assigned roles.

The Global Administrator assignment list was checked separately and did not include Maya.

Troubleshooting Observation

The user's Assigned roles page repeatedly displayed an error retrieving directory roles.

Rather than treating the error as proof of missing permissions, I checked the Global Administrator role's assignment list and returned to the user's Overview to confirm the reported role count.

The alternative checks supported the intended configuration, although the error itself was not resolved.

Security Consideration

Group membership alone does not establish that the employee has appropriate access to protected resources.

The next stage will involve testing access to configured resources, including whether unauthorized access is denied.

Current Result

Identity creation and group assignment: verified.

Application permissions, MFA, and effective access: not yet tested.
