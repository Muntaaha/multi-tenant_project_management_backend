**Multi-tenant Project Management System**

# Tech Stack

# Key Features 

## Subscription System
 - Plan-based access (Free, Pro, Enterprise).
 - Feature limitations based on plan.
 - Admin view to upgrade plan.
 - Superadmin manages plans (CRUD).

## Multi-Tenant Architecture
 - Superadmin has full system access.
 - Each tenant (Group/Organization) operates in isolated data scope.
 - Users cannot access data outside their tenant.
 - Role-based data access within each tenant.

## Authentication & User Management
 - JWT and OAuth2 (Role Based Access Controll)
 - Registratin
    - Individual User (later join/create Group or Organization).
    - Group (the one who creates is the admin, later can be passed on).
    - Organization (while registration will be mentioned if wanna work in group or organization).
 - Basic Profile management (photo, bio, contact, etc.)
 - Emain Verfication & password functionalities (change password/forget password)

## Group/Organization Management
 - Admin creates group/organization
 - Invite other members via email or internal system
 - No join requests if no internal system
 - Admin assigns access to users 
    - user can contribute 
    - user can review 

## Project Management
 - Admin creates/updates Projects, project archive (based on status project goes to archive)
 - One project can belong to
    - One or more Groups.
    - One or more Organizations.
 - Projects must have title, dealine, status(on-progress, on-hold, completed)

## Task Management
 - Milestones or Modeules based on timelines
 - Tasks under each milestone/module
 - Subtasks under Tasks
 - Task/Subtask Assignment with deadline
 - File Attachment under Tasks (Multiple File Attachment)
 - Task/Subtask deadline 
 - Task Status(in-progress, under-review,completed)
 - Task priority (low, medium, high)
 - comment section

## Collaboration & Communication
- Task-based comments.
- Mention users in comments.
- Project discussion boards or threads.
- Real-time notifications (email + in-app). *not sure*

## Notifications
- Task assignment or update.
- Member joined/left/invited.
- Deadlines approaching.

## Activity Logs and Audit
 - Record
    - Project creation/edits.
    - Member joined/left.
    - task logs task status

## Reporting & Analytics
 - Project progress summary.
 - Task completion stats.
 *need more discussion*

## Superadmin 
*need discussion*

# User Stories