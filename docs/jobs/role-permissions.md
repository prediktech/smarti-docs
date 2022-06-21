# Role Permissions

These are permissions that a user has that apply system-wide.

- System Admin
- Assessment Admin
- Checklist Admin
- Documentation Admin
- Risk Admin
  
### System Admin
- can do all that the other roles can

### Assessment Admin
- create, update and delete assessments in the assessment catalog.
- create, update and delete qualities
- create, update and delete maturity scales
- create, update and delete permission on questions
- must be able to manage metadata without any other permissions
- add assessments to companies (Assessment scheduler permission on the company is needed to actually schedule assessments)

### Checklist Admin
- create, update and delete checklist structures
- checklist scheduler permission on the company required to schedule checklists
- can view checklist schedules
- create, update and delete permission on questions
- must be able to manage metadata without any other permissions

### Documentation Admin
- create, update and delete documentation (standards)
- create, update and delete permission on questions
- must be able to manage metadata without any other permissions

### Risk Admin
[ currently under development ]


## Company role permissions
These are permissions which, in addition to the system-wide permissions, apply at a company level only.

- Company Admin
- Team Admin
- Assessment Scheduler
- Assessor
- Planner
- Checklist Scheduler

### Company Admin
- Can edit the current company from the change company menu option
- can create, edit and delete company "Status List"
- can create, edit and delete company "Status Workflows"
- can create, edit and delete company "Report Templates"

### Team Admin
- can create, edit and delete company teams
- can create, edit and delete company users

### Assessment Scheduler
- can create, edit and delete versions
- can create, edit and delete submissions

### Checklist Scheduler
- can create, edit and delete checklist schedules

### Assessor
- can be added to assessor teams

### Planner
- can create, edit and delete objectives
- can create, edit and delete initiatives
- can create, edit and delete actions on generic initiatives
- can view maturity plans and actions even if the user is not accountable or assessor on the submission
- can only create, edit and delete actions on a maturity plan if the user also has permissions on the submission