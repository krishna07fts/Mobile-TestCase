## MWD Mobile Test case
 ### Helpdesk

| TestCaseID    |   Title |    Functionality |
| :--------: | :-------:   |  :-------:   |
| TC-01  | Login    |  Login the app using the User name password.   |
| TC-02 |  Dashboard      |     Verify that the Tickets, Task, Approvals counts and Helpdesk Overview are displays. And the Customer Support's Unassigned, Open, Inprogress counts  and Customer's Ticket Overview are displays. |
| TC-03    | Create Ticket (HD)    |  Verify that the user can create a request with or without an attachment here.   |
| TC-04    | BottomNavBar <br> (Ticket)  | **Unassigned Tab** - Verify that the Unassigned Tickest are displays here. <br> **Assigned Tab** - Verify that the Assigned tickets are display here. <br> **Sent Tab** - Verify that the tickets are created by is displays here.   |             
| TC-05    | Filter    |  Filter by Status, Created between date and Created By.   |
| TC-06    | Ticket details Page      |  Verify that its displays the details of the ticket like Title, Default status in New, Created date, Category and All the Actions ect..   |
| TC-07    | Pickup (Action)      |  **Pickup** - Verify that the user can pick up a ticket and it gets assigned to themselves.   |
| TC-08    | Assign (Action)      |  **Assign** - Allows the user to assign the ticket to another user.   |
| TC-09    | Sent Approval (Action)       |  **Verify that the** - <br> User can send approval. <br> Ticket Status changes into waiting for approval. <br> Approval requests are in the pending tab.   |
| TC-10    | (Approval) <br> Bottom Nav Bar <br> Take Approve Action for Approval Request      |  **Verify that the** - <br> Approver can take Action (Approve). Approval moves to the Complected tab. <br> Ticket status change to Approved.   |
| TC-11    | (Approval) <br> Bottom Nav Bar <br> Take Reject Action for Approval Request      |  **Verify that the** - <br>Approver can take Action (Reject). <br> Approval moves to the Complected tab. <br> Ticket status in waithing for approval.   |
| TC-12    | Add Comments in Approval details page      |  **Verify that the** - <br> User can add comments. <br> And the comments are displays in the conversation.   |
| TC-13    | Add Mentioned Comments in Approval details page      |  **Verify that the** - <br> User can add mentioned comments. <br> And the comments are displays in the conversation.   |
| TC-14    | Accept (Action) to Schedule the Ticket      |  **Verify that the** - <br> User can take Action. <br> Ticket status change into Schedule.   |
| TC-15    | Start (Action) to Inprogress the Ticket20      |  **Verify that the** - <br> User can take Action. <br> Ticket status change into Inprogress.   |
| TC-16    | Assign Task      |  **Verify that the** - <br> User can take Action.   |
| TC-17    | (More -> Task) <br> Bottom Nav Bar      |  **Pending Tab** - Verify that the Pending Task are displays here. <br> **Complected Tab** - Verify that the Complected Task are display here. <br> **Sent Tab** - Verify that the Task are created by is displays here.   |
| TC-18    | Take Action on Task <br> (Doing)      |  **Verify that the** - <br> Default status in Todo. <br> User can Take Doing Action on Task. <br> The status change to Doing.   |
| TC-19    | Close Validation      |  **Verify that the** - <br> When the ticket is In Progress and a task is in To Do or Doing, the ticket cannot be closed.   |
| TC-20    | Take Action on Task <br> (Done)      |  **Verify that the** - <br> Status in Doing. <br> User can Take Done Action on Task. <br> The status change to Done. <br> And the task moves to Completed Tab.   |
| TC-21    | Add Comments in Task details page      |  **Verify that the** - <br> User can add comments in the Task. <br> And the comments are displays in the Task Tab details conversation page.   |
| TC-22    | Add Mentioned Comments in Task details page      |  **Verify that the** - <br> User can add comments in the Task. <br> And the mentioned comments are displays in the Task Tab details conversation page.   |
| TC-23    | Add Comments in Ticket details page      |  **Verify that the** - <br> User can add comments in the Ticket. <br> And the comments are displays in the conversation.   |
| TC-24    | Add Mentioned Comments in Ticket details page      |  **Verify that the** - <br> User can add mentioned comments in the Task. <br> And the mentioned  comments are displays in the conversation.   |
| TC-25    | Add Notes in the Ticket details page      |  **Verify that the** - <br> User can add notes in Ticket. <br> And the notes are displays in the conversation.   |
| TC-26    | Cancel the Ticket      |  **Verify that the** - <br> User can able to cancel the ticket. <br> Status changes to Cancelled.   |
| TC-27    | Close Ticket      |  **Verify that the** - <br> User can able to close the ticket. <br> Status changes to Closed.   |
| TC-28    | ReOpen Ticket      |  **Verify that the** - <br> The status is in Closed. <br> The ticket create User can Reopen the ticket.   |
| TC-29    | Assigned Ticket details page <br> 'Activity Tab'      |  **Verify that** - <br> If User takes Actions (Status changes, Comments & Notes) they are displayed in the Activity tab.   | -->
| TC-30    | Assigned Ticket details page <br> 'File Tab' | **Verify that** - <br> If Users add any attachments it will displayed in File tab.   |
| TC-31 | Assigned Ticket details page <br>'Task Tab' | **Verify that** - <br> If task is assigned to the another user the task status is display in the Task tab |
| TC-32 | Assigned Ticket details page <br> 'Approval Tab' | If approval is sent, the approval status is display in the Approva tab. |
| TC-33 | Notification <br> All Tab | **Verify that the** - <br> Its Contains all the Notification including New, Status change, Assignment, Mentioned. |
| TC-34 | Notification <br> New Tab | **Verify that the** - <br> It contains the New Notifications. |
| TC-35 | Notification <br> Status change | **Verify that the** - <br> It contains the Status change Notifications. |
| TC-36 | Notification <br> Assignment | **Verify that the** - <br> It contains the Assignment Notifications. |
| TC-37 | Notification <br> Mentioned | **Verify that the** - <br> It contains the Mentioned  Notifications. |

### Email Notification

| TestCaseID    |   Title |    Functionality |
| :--------: | :-------:   |  :-------:   |
| TC-1 | Ticket create | **Email sent to** : <br> The category team & Ticket Creater. |
| TC-2 | Pickup/Assign | **Email sent to** : <br> The assigned person. |
| TC-3 | Send approval | **Email sent to** : <br> The Approver & Cc to Approval sender. <br> Status change mail send to Ticket creator. |
| TC-4 | Approve Action | **Email sent to** : <br> Approval Sender & Ticket creator. |
| TC-5 | Reject Action | **Email sent to** : <br> Approval Sender. |
| TC-6 | Add Comments in Approval details page | 	**Email sent to** : <br> Approval Sender & Assigned Approver. |
| TC-7 | Add Mentioned Comments in Approval details page | **Email sent to** : Mentioned User, Approval Sender & Assigned Approver. |
| TC-8 | Accept <br> (Schedule) | 	**Email Sent to** : <br> The Ticket Created User. |
| TC-9 | Start <br> (In progress) | 	**Email Sent to** : <br> The Request Created User. |
| TC-10 | Assign Task | **Email Sent to** : <br> The Task Assigned user. |
| TC-11 | Take Action on Task <br> (Doing) | **Email Sent to** : <br> The Task sender user. |
| TC-12 | Take Action on Task <br> (Done) | **Email Sent to** : <br> The Task sender user. |
| TC-13 | Add Comments in Task details page | **Email sent to** : <br> Task Created User & Task Assigned User. |
| TC-14 | Add Mentioned Comments in Task details page | **Email sent to** : <br> Mentioned User, Task Created User & Task Assigned User. |
| TC-15 | Add Comments in Ticket details page | - |
| TC-16 | Add Mentioned Comments in Ticket details page | **Email sent to** : <br> Mentioned User. |
| TC-17 | Cancel the Ticket | **Email sent to** : <br> Ticket Created User. |
| TC-18 | Close Ticket | **Email sent to** : <br> Ticket Created User. |
| TC-19 | ReOpen Ticket | **Email sent to** : <br> Ticket Created User & Ticket Assigned User. |
| TC-20 | Escalation Mail to Manager | If no action taken for 4 hours from ticket created. <br> **Email sent to** : <br> Manager of the Department. |
| TC-21 | Escalation Mail to Manager | 	If no action taken for 8 hours from ticket created. <br> **Email sent to** : <br> Manager of the Department. |

### Push Notification

| TestCaseID    |   Title |    Functionality |
| :--------: | :-------:   |  :-------:   |
| TC-1 | Ticket create |  Push Notification receive by the Request Created User & the category team. |
| TC-2 | Pickup/Assign | Push Notification receive by Assigned user. |
| TC-3 | Send Approval | Push Notification receive by -  Approver. <br> Status change (Waiting for approval) Push Notification goes to the - ticket creator. |
| TC-4 | Approve Action | Push Notification receive by Approval Sender. <br> Status change (Approved) Push Notification goes to the - ticket creator. |
| TC-5 | Reject Action | Push Notification receive by Approval Sender. |
| TC-6 | Add Comments in Approval details page | Push Notification receive by Approval Sender & Approver. |
| TC-7 | Add Mentioned Comments in Approval details page | Push Notification receive by Approval Sender & Approver. |
| TC-8 | Accept (Schedule) | Push Notification receive by Request Created User. |
| TC-9 | Start (Inprogess) | Push Notification receive by Request Created User. |
| TC-10 | Assign Task | Push Notification receive by Task assigned User. |
| TC-11 | Take Action on Task <br> (Doing) | Push Notification receive by Task Sender User. |
| TC-12 | Take Action on Task <br> (Done) | Push Notification receive by Task Sender User. |
| TC-13 | Add Comments in Task details page | Push Notification receive by : <br> Task Created User & Task Assigned User. |
| TC-14 | Add Mentioned Comments in Task details page | Push Notification receive by : <br> Mentioned User, Task Created User & Task Assigned User. |
| TC-15 | Add Comments in Ticket details page | - |
| TC-16 | Add Mentioned Comments in Ticket details page | Push Notification receive by : <br> Mentioned User. |
| TC-17 | Cancel the Ticket | Push Notification receive by : <br> Ticket Created User. |
| TC-18 | Close Ticket | Push Notification receive by : <br> Ticket Created User. |
| TC-19 | 	ReOpen Ticket | Push Notification receive by : <br> Ticket Created User & Ticket Assigned User. |
| TC-20 | Escalation Mail to Manager | If no action taken for 4 hours from ticket created Push Notification receive by : Manager of the Department. |
| TC-21 | Escalation Mail to Manager | 	If no action taken for 8 hours from ticket created Push Notification receive by : Manager of the Department. |