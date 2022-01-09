# SNOW-Change-Management

Change Management helps organizations understand and work to minimize risks of changes to the IT environment. It is essentially a process for managing the people-side of change. ServiceNow helps implement your Change Management process by providing on-demand capabilities for creating, assessing, approving and implementing changes to your environment. 


Within the platform, changes are handled using the task record system. Each change is generated through a variety of means as a task record, populated with the pertinent information in individual fields. These tasks can be assigned to appropriate change management team members, who will deal with the task as appropriate. Once the change has been properly implemented, it is closed.

## Flowchart
![image](https://user-images.githubusercontent.com/12488769/148667875-6762fb08-1e34-48b6-9aa3-36232a6d2796.png)

## Process
1. Raising and Recording Changes - A new change record can be generated in a number of ways:
An IT team member (role: itil) can generate a change by hand through Change   Create New or clicking New from the change record list. 
An IT team member (role: itil) can request a change through the Service Catalog. 
A change can be requested from an incident.
A change can be requested from a problem.  
If an assignment rule applies, the change will be assigned to the appropriate user or group. Otherwise, it can be assigned by hand. 
Email Notifications will keep involved parties informed about updates to the change request.

2. Assessing and Evaluating Changes - Once a change request is in place, the change management team must populate the change request with as much information as possible in order to fully assess the requested change. 

3. Planning Changes: Changes can be planned directly in the change record, but for complex, multi-step changes, Project Management allows specificity of planning. Projects in the Project plugin can organize many layers of tasks, and present the tasks as a Gantt Chart timeline. 

4. Authorizing Changes:
Specified by hand, using the Approvers related list 
Generated using an Approval Rule
Generated using a workflow. 
Using automated approvals, emails will be sent out informing the appropriate user that they need to approve the change. They can either update the Approval field on the form, or can simply respond to the email if the appropriate inbound email action is configured.

5. Closing Changes: Once the change has come to an end, and the change has been tested and confirmed, the change can be closed by changing the state. If the change was generated from an incident or problem, a business rule can be configured to automatically close them upon closing the change.
\



