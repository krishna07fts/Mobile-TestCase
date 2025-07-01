### Customer Support

| TestID    |   Title |    Functionality |
| :--------: | :-------:   |  :-------:   |
| TC-1 | Login | Login the app using the User name password. |
| TC-2 | Dashboard | Verify that the Tickets, Task, Approvals counts and Helpdesk Overview are displays. <br> And the Customer Support's Unassigned, Open, Inprogress counts  and Customer's Ticket Overview are displays. |
| TC-3 | Create Ticket/Email | 	Send Email from Outlook to Support mail. |
| TC-4 | Create Ticket/Email | Send Email from Mobile. |
| TC-5 | (Customer Support) <br> Bottom Nav Bar | **Unassigned Tab** - <br> Verify that the Unassigned Tickest are displays here. <br> **Assigned Tab** - <br> Verify that the Assigned to me tickets are displays here. <br> **My Team Tab** - <br> Verify that the tickets my team are displays here. |
| TC-6 | Filter | Filter by Status, Created between date and Created By. |
| TC-7 | Ticket details Page | Verify that its displays the details of the ticket like Title, Default status in New, Created date, Type and All the Actions ect.. |
| TC-8 | Pickup (Action) | **Pickup** - Verify that the user can pick up a ticket and it gets assigned to themselves. |
| TC-9 | Assign (Action) | **Assign** - Allows the user to assign the ticket to another user. |
| TC-10 | Sent Approval (Action)  | **Verify that the** - <br> User can send approval. <br> **Approval Tab** - Approval status in pending. <br> Approval requests are in the pending tab. |
| TC-11 | Take Approve Action for Approval Request | **Verify that the** - <br> Approver can take Action (Approve). <br> Approval moves to the Complected tab. <br> Approval status change to Approved & its shows in the conversation. |
| TC-12 | Take Reject Action for Approval Request | **Verify that the** - <br> Approver can take Action (Reject). <br> Approval moves to the Complected tab. <br> Approval status to Rejected & its shows in the conversation. |
| TC-13 | Add Comments in Approval details page | **Verify that the** - User can add comments. <br> And the comments are displays in the conversation. |
| TC-14 | Add Mentioned Comments in Approval details page | **Verify that the** - <br> User can add mentioned comments. <br> And the comments are displays in the conversation. |
| TC-15 | Schedule (Action) | **Verify that the** - <br> User can take Action. <br> Ticket status change into Schedule. |
| TC-16 | Start (Action) | **Verify that the** - <br> User can take Action. <br> Ticket status change into Inprogress. |
| TC-17 | Ticket (Action) | **Verify that the** - <br> User can take Action. |
| TC-18 | Reply to Mail from Mobile | **Verify that the** - <br> Reply to Mail from Mobile without Attachment & Its display in the conversation tab. |
| TC-19 | Reply to Mail from Mobile | **Verify that the** - <br> Reply to Mail from Mobile with Attachment  & Its display in the conversation tab. |
| TC-20 | Reply to Mail from Outlook | **Verify that the** - <br> Reply to Mail from Outlook without Attachment  & Its display in the Activity Tab. |
| TC-21 | Reply to Mail from Outlook | **Verify that the** - <br> Reply to Mail from Outlook with Attachment & Its display in the Activity Tab. |
| TC-22 | Forward to Mail from Mobile | **Verify that the** - <br> Forward to Mail from mobile without Attachment & Its display in the Activity Tab. |
| TC-23 | Forward to Mail from Mobile | **Verify that the** - Forward to Mail from mobile with Attachment & Its display in the Activity Tab. |
| TC-24 | Add Comments in Ticket details page | **Verify that the** - <br> User can add comments in the Ticket. <br> And the comments are displays in the Activity Tab. |
| TC-25 | Add Mentioned Comments in Ticket details page | **Verify that the** - <br> User can add mentioned comments in the Ticket. <br> And the mentioned  comments are displays in the Activity Tab. |
| TC-26 | Add Notes in the Ticket details page | **Verify that the** - <br> User can add notes in Ticket. <br> And the notes are displays in the Activity Tab. |
| TC-27 | Close Ticket | **Verify that the** - <br> User can able to close the ticket. <br> Status changes to Closed. |
| TC-28 | ReOpen Ticket | **Verify that the** - The status is in Closed. <br> User can Reopen the ticket. |
| TC-29 | ReOpen Ticket (Automatic) | **Verify that the** - <br> Coordinator's Customer reply to the closed mail the ticket will reopen Automatically. |
| TC-30 | Assigned Ticket details page <br> 'Activity Tab' | *Verify that* - <br> If User takes Actions (Status changes, Comments, Notes & Mail with and without attachments) they are displayed in the Activity tab. |
| TC-31 | Assigned Ticket details page <br> 'File Tab' | **Verify that** - If Users add any attachments it will displayed in File tab. |
| TC-32 | Assigned Ticket details page <br> 'Ticket Tab' | If he user take Ticket(Action) It will displayed in Ticket tab. |
| TC-33 | Assigned Ticket details page <br> 'Approval Tab' | If approval is sent, the approval status is display in the Approva tab. |

### Email Notification

| Test Id |	Title |	Functionality |
| :--------: | :-------:   |  :-------:   |
| TC-1 | Ticket Create | Email sent to : <br> The Customer & Coordinator |
| TC-2 | Pickup/Assign | Email sent to : <br> Assigned User |
| TC-3 | Send Approval | Email sent to : <br> To: Approver, <br> CC: Approval sender. |
| TC-4 | Approve Action | Email sent to: <br> To: Approval Sender , <br> CC:  Approver. |
| TC-5 | Reject Action | Email sent to: <br> To: Approval Sender , <br> CC:  Approver. |
| TC-6 | Add Comments in Approval details page | Email sent to : <br> Approval Sender & Assigned Approver. |
| TC-7 | Add Mentioned Comments in Approval details page | Email sent to : <br> Mentioned User, Approval Sender & Assigned Approver. |
| TC-8 | Accept (Schedule) | - |
| TC-9 | Start (In progress) | - |
| TC-10 | Ticket | Email Received by the Assigned Category team. |
| TC-11 | Reply to Mail from Mobile without Attachment | Email Received by Test User(End User). |
| TC-12 | Reply to Mail from Mobile with Attachment | Email Received by Test User(End User) with Attachment. |
| TC-13 | Reply to Mail from Outlook without Attachment | Email Received by the Ticket Assigned User & its shows in the Activity tab. |
| TC-14 | Reply to Mail from Outlook with Attachment | Email Received with attachment  to the Ticket Assigned User & its shows in the Activity tab. |
| TC-15 | Forward to Mail from mobile without Attachment | Email Received by who are in the To & Cc, default its patch in 'To field' the who create the mail without attachment. |
| TC-16 | Forward to Mail from mobile with Attachment | Email Received by who are in the To & Cc, default its patch in 'To field' the who create the mail with attachment. |
| TC-17 | Add Mentioned Comments in Ticket details page | Email sent to : <br> Mentioned User & Ticket assigned user. |

### Push Notification

| Test Id | Title | Functionality |
| :--------: | :-------:   |  :-------:   |
| TC-1 | Ticket Create | Push Notification receive by : <br> The Customer's Coordinator. |
| TC-2 | Assign/Pickup | Push Notification receive by : <br> Ticket Assigned Coordinator. |
| TC-3 | Send Approval | Push Notification receive by - <br> Approver. |
| TC-4 | Approve Action | Push Notification receive by Approval Sender. |
| TC-5 | Reject Action | Push Notification receive by Approval Sender. |
| TC-6 | Approval page Mentioned comment | Push Notification receive by Mentioned User. |
| TC-7 | Ticket Mentioned comment | Push Notification receive by Mentioned User. |
| TC-8 | Reply | Push Notification receive by : <br> The Customer's Coordinator. |
| TC-9 | Forward | Push notifications are received by : <br> The system users who are in the 'To' and 'Cc' fields. |
