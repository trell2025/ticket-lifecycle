<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to create, work, and resolves tickets within osTicket](https://youtu.be/6psdsiJ1U-c?si=r4AQDKUxxRlOxhmf)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>
<img src="https://miro.medium.com/v2/resize:fit:1400/0*Kcyvg6Iayow1EFLn" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Intake: When a customer submits a ticket (via email, web form, or phone), the system automatically captures ticket details such as the subject, description, priority, and customer information. If set up, osTicket can also automatically categorize the ticket based on the Help Topic selected by the customer or the content of the ticket.

Assignment: Once a ticket is created, osTicket can automatically assign it to the appropriate department or agent based on predefined rules (e.g., ticket type, priority, or keywords). You can also manually assign tickets to agents, ensuring the right team handles each issue. Triggers can be used to automatically assign tickets based on specific criteria.

Communication: Agents can communicate with customers through the ticketing system by posting updates, adding internal notes, or responding directly within the ticket. Email notifications are sent to customers for any updates or responses, keeping them informed throughout the ticket resolution process. Communication is tracked within the system for both agents and customers to review at any time.
</p>
<br />

<p>
<img src="https://forum.osticket.com/assets/files/2020-10-07/1602077771-745737-ostikcet.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Review Ticket Details: Agents view the ticket’s description, attachments, and customer information to understand the issue.

Update Ticket: Agents can post public responses to the customer or add internal notes for team collaboration without notifying the customer.

Request More Information: If needed, agents can ask customers for additional details via replies.

Resolve or Escalate: Once the issue is addressed, the agent can mark the ticket as resolved. If the issue requires further attention, it can be escalated to a higher priority or different department.
</p>
<br />

<p>
<img src="https://forum.osticket.com/assets/files/2023-06-27/1687883946-472177-osticket-queue-closed.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Customer's Issue: The customer reports being unable to access their account due to a "password incorrect" error message. This is the issue that the agent needs to resolve.

Agent's Response: The agent checks the details and decides that the issue is likely a result of incorrect login credentials. The agent responds by providing clear instructions for the customer to reset their password, including a link to the reset page and step-by-step guidance.

Customer’s Action: The customer follows the agent’s instructions to reset their password and successfully regains access to their account.

Ticket Status Update: After the agent provides the solution, the ticket is marked as "Resolved" in osTicket to indicate that the issue has been addressed. The agent records a short summary of the resolution, which is the password reset process.

Closing the Ticket: After confirming the issue is fixed (the customer is able to log in), the agent will change the ticket status to "Closed". This final status signifies that the problem has been fully resolved and no further action is required.
</p>
<br />
