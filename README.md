<p align="center">

<img width="790" alt="Screen Shot 2023-07-05 at 12 01 33 AM" src="https://github.com/yeahglo/ticket-lifecycle/assets/91516100/333da671-52b4-4492-bc26-68c291308f12">

<h1>osTicket - Ticket Lifecycle: Ticket Intake to Resolution</h1>

<p>In this example, we walk through the life cycle of a ticket from intake to resolution, from end-user to agent, within the open-source help desk ticketing system osTicket.</p>


- Microsoft Azure Virtual Machine
- Microsoft Remote Desktop
- Internet Information Services (IIS)
- osTicket Software


<h2>Operating Systems </h2>

- Windows 10, version 22H2

<h2>Ticket Lifecycle Stages</h2>

- Ticket Intake
- Assignment and Communication
- Working the Issue
- Ticket Resolution and History

<h2>Lifecycle Stages</h2>

<br />

**Ticket Intake** - End-users create tickets and are identified by unique email addresses.
- Anonymous users can create tickets (Note: We set it up this way.)
- Create a general ticket for "Stephanie Harris" with a made-up email address
- Give it a title about how mobile banking is down and include details in the body about this urgent event

<br />

<img width="1202" alt="Screen Shot 2023-07-10 at 9 50 16 AM" src="https://github.com/yeahglo/ticket-lifecycle/assets/91516100/64ea894b-1e43-4ed0-815e-c110fc7fcda6">

**_End-users have their own interface and the ability to create tickets anonymously and are identified by a unique email address._** 

<br/>

<img width="1177" alt="Screen Shot 2023-07-13 at 9 42 45 AM" src="https://github.com/yeahglo/ticket-lifecycle/assets/91516100/03034416-d58e-44c2-9fc7-2c8d1bc91d17">

**_Notice the listed Help Topics configured during the [Post-Install Configuration](https://github.com/yeahglo/post-install-config)._**

<br/>

<img width="1172" alt="Screen Shot 2023-07-13 at 9 44 46 AM" src="https://github.com/yeahglo/ticket-lifecycle/assets/91516100/ed46fd21-68c1-4e65-83db-36d300c4387d">

**_Users are ticket owners and they are uniquely identifiable by their email addresses._**

<br/>

**Assignment and Communication** - Queue managers have the ability to review and customize tickets, individually, so that they are triaged to correct agent.
- Log into the Agent interface with the Supreme/System Administrator, atorres
- Navigate to the Tickets tab to see all tickets created
- Click on the ticket that says "Mobile Banking is down"
- Set the priority level to Emergency
- Assign it to Agent and Supreme/System Admin atorres
- Update the SLA from Default SLA > SEV-A
- Set the department to System Administrators

<br />


<img width="1178" alt="Screen Shot 2023-07-13 at 9 54 43 AM" src="https://github.com/yeahglo/ticket-lifecycle/assets/91516100/f3897498-0538-4391-b11d-8f4ed158fca7">

**_Log into the agent interface for osTicket to work tickets._** 




<br />

<img width="1193" alt="Screen Shot 2023-07-13 at 9 54 58 AM" src="https://github.com/yeahglo/ticket-lifecycle/assets/91516100/19dc9669-0d3b-49d7-a758-7e19b5dc51b9">

**_All tickets can be seen by this agent because of the permissions we set up, previously._** 

<img width="107" alt="Screen Shot 2023-07-13 at 9 55 41 AM" src="https://github.com/yeahglo/ticket-lifecycle/assets/91516100/cc567a09-930d-4a3a-8ca2-0c216655769e">

<br />

**_All tickets have come in with a priority level set to normal. Ticket routing may be affected if this is changed._** 

<img width="1185" alt="Screen Shot 2023-07-13 at 9 58 53 AM" src="https://github.com/yeahglo/ticket-lifecycle/assets/91516100/3d59646c-0ed1-41bf-b8f1-3a1a16d6aa10">

<br />

**_For this example, we set the priority level to emergency because mobile banking is down._** 

<img width="1192" alt="Screen Shot 2023-07-13 at 10 00 03 AM" src="https://github.com/yeahglo/ticket-lifecycle/assets/91516100/269a14af-d290-443f-a49a-64e9ccba691e">

**_Since it is a business-impacting event, the agent can assign it to himself._** 

<br />

<img width="1186" alt="Screen Shot 2023-07-13 at 10 00 50 AM" src="https://github.com/yeahglo/ticket-lifecycle/assets/91516100/25d03709-69c5-45eb-9190-797370b9c792">

**_The ticket wasn't routed automatically, so it went to the Default SLA. Queue managers can set escalate or de-escalate the SLA as they triage tickets._** 

<br />

<img width="1188" alt="Screen Shot 2023-07-13 at 10 02 52 AM" src="https://github.com/yeahglo/ticket-lifecycle/assets/91516100/7320d078-b2e0-42a9-ac48-5aec601ef1c0">

**_If necessary, the ticket can be routed to a specific Department. In this example, System Adminstrators are responsible for mobile banking so we assign it to them._**

<br />

<p>
  
**Working the Issue** - Assigned and unassigned tickets can be worked by agents.
- Navigate to Tickets > My Tickets to see atorres' list of tickets
- Open the ticket about mobile banking being down
- With the ticket open, we can work on the ticket and make changes
- Once the tickets are resolved, they automatically move to Tickets > Closed

</p>

<img width="1186" alt="Screen Shot 2023-07-13 at 10 21 30 AM" src="https://github.com/yeahglo/ticket-lifecycle/assets/91516100/56c53d36-ea67-49bd-a3dd-24c9f4925808">

**_This is a business-impacting event so it has a priority level of emergency._**

<img width="1175" alt="Screen Shot 2023-07-13 at 10 21 23 AM" src="https://github.com/yeahglo/ticket-lifecycle/assets/91516100/6edc6c02-621d-45a6-9781-b8884b59c86f">

**_This is a business-impacting event so it has a priority level of emergency._**

<img width="1168" alt="Screen Shot 2023-07-13 at 10 04 29 AM" src="https://github.com/yeahglo/ticket-lifecycle/assets/91516100/bcf3b671-6036-44d9-96e6-3e9ca076f649">

**_The ticket status can remain open while still working the ticket and posting replies._**

<img width="1155" alt="Screen Shot 2023-07-13 at 10 04 56 AM" src="https://github.com/yeahglo/ticket-lifecycle/assets/91516100/c6ea4863-0aa0-42e0-a6da-f4d97d136f87">

**_Changes within the ticket can be seen inside the ticket._**

<img width="1163" alt="Screen Shot 2023-07-13 at 10 06 44 AM" src="https://github.com/yeahglo/ticket-lifecycle/assets/91516100/9e8e73df-76ba-4c3e-b80f-60ab92dd27ac">

**_After working the ticket, we can set the status to resolved._**

<br />

<p>
  
**Ticket Resolution and History** - Even if tickets are closed, the history and resolution of the ticket can be seen.
- Navigate to Tickets > Closed
- The Ticket Thread shows the entire history of the ticket

</p>

<img width="1156" alt="Screen Shot 2023-07-13 at 10 08 34 AM" src="https://github.com/yeahglo/ticket-lifecycle/assets/91516100/eee0fad6-eab8-4517-9a44-152b0592a634">

**_The Ticket Thread is inside the ticket and shows the entire history of the ticket, from statuses to post replies._**

<p>

<br />
  
**FAQs and Canned Responses** - osTicket provides additional ways to streamline communication internally and externally.
- Navigate to Knowledgebase > FAQs > Add New Category
- Create an FAQ
- Navigate to Knowledgebase > Canned Responses > Add New Response
- Create a Canned Response

</p>

<img width="1191" alt="Screen Shot 2023-07-13 at 10 25 27 AM" src="https://github.com/yeahglo/ticket-lifecycle/assets/91516100/e1b6de74-58ca-4340-a5c0-0bf1008d5a4b">

<img width="1162" alt="Screen Shot 2023-07-13 at 10 24 42 AM" src="https://github.com/yeahglo/ticket-lifecycle/assets/91516100/c8d5509c-b3a3-4128-92ec-c23be58ee64e">

<img width="1183" alt="Screen Shot 2023-07-13 at 10 25 45 AM" src="https://github.com/yeahglo/ticket-lifecycle/assets/91516100/e8bee232-79eb-48f5-9095-cc56a2d5121e">

<img width="1145" alt="Screen Shot 2023-07-13 at 10 26 04 AM" src="https://github.com/yeahglo/ticket-lifecycle/assets/91516100/539b68b0-c5a1-4a2a-b063-9fee00b22d57">





 
