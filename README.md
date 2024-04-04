<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.
<p></p>

[osTicket: Post-Installation Configuration](https://github.com/sirmichaelyoung/post-install-config) Continued


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- New Tickets
- Assignment, Communication, and Status Updates
- Resolving Tickets

<h2>Lifecycle Stages</h2>

<img width="410" alt="Screenshot 2024-04-04 at 1 43 25 PM" src="https://github.com/sirmichaelyoung/ticket-lifecycle/assets/163785883/9fbd55d4-6b11-415d-83fe-22c2555b00db">

Intake
- Agent
   - Tickets > New Ticket
- User  
    - Go to http://localhost/osTicket/
      - Create New Ticket
     
<img width="504" alt="Screenshot 2024-04-04 at 2 41 28 PM" src="https://github.com/sirmichaelyoung/ticket-lifecycle/assets/163785883/30a887fe-03c1-4224-add1-1d864a65942f">

Assignment and Communication

- Assigning a Ticket
  - [X] Select Ticket(s)
    - Assign to Agent
       
Tickets may also be assigned to a team for collaborations

<img width="511" alt="Screenshot 2024-04-04 at 3 00 06 PM" src="https://github.com/sirmichaelyoung/ticket-lifecycle/assets/163785883/bcae48d2-f7a9-4eb1-85d6-a6e9eecc76cf">
<p></p>
<img width="227" alt="Screenshot 2024-04-04 at 2 47 58 PM" src="https://github.com/sirmichaelyoung/ticket-lifecycle/assets/163785883/ab15e08e-bed3-4c1e-bf69-a7725e452be6">

  *Selecting the Ticket opens a menu where SLA, Status, Priority, Topic, etc. can be changed. 
- Responses can also be added from this interface

<img width="431" alt="Screenshot 2024-04-04 at 2 57 45 PM" src="https://github.com/sirmichaelyoung/ticket-lifecycle/assets/163785883/594468e4-769d-416d-a6c8-600430718d1b">

Resolving Tickets
- Once a ticket is resolved, the status can be updated on the same interface a reply is made.

<img width="260" alt="Screenshot 2024-04-04 at 3 21 59 PM" src="https://github.com/sirmichaelyoung/ticket-lifecycle/assets/163785883/e75900b9-e895-44e2-b56d-eb6fd5ce40a7">

This concludes the osTicket Lifecycle overview.
