




# <p align="center">
<img src="https://i.imgur.com/tUnlhRz.jpeg" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />

<h1>osTicket: Creating and Working Tickets</h1>

<h2>Description</h2>
Continuation of the <a href="https://github.com/AnthonydcHo/post-install-config"> post-installation of osTicket </a> . We will be simulating and work osTickets within a simulated organization. 
<br/>
<br/>

<h2>List of Prerequisites</h2>

- Microsoft Azure
- Virtual Machine
- <a href="https://github.com/AnthonydcHo/post-install-config"> Installation of osTicket 

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- Windows 10

<h2>Implementation/Program Walk-through:</h2>



<p align="center">
Navigate to http://localhost/osTicket to submit a ticket as a end user: <br/>
<img src="https://i.imgur.com/nBRpJkI.png" height="80%" width="80%" 
<br />
<br />
We can log in as Karen as the end user, with email: karen@gmail.com: with full name Karen and help topic can be Report a problem: <br/>
<img src="https://i.imgur.com/T7hx5L1.png" height="80%" width="80%" 
<br />
<br />
The issue with be entire mobile/online banking system is down with the issue summary saying: My employees are reporting that users are no longer able to access their banking portal. The ones can occasionally access it, cannot log in. (yes a real simulation):  <br/>
<img src="https://i.imgur.com/HTWdZVg.png" height="80%" width="80%" 
<br />
<br />
Next, I will log in as an agent (John/worker) we created:  <br/>
<img src="https://i.imgur.com/qjrN76Y.png" height="80%" width="80%" 
<br />
<br />
Main ticket page:  <br/>
<img src="https://i.imgur.com/QkWcRs4.png" height="80%" width="80%" 
<br />
<br />
The ticket shows priority, department, SLA, and who it assigned to:  <br/>
<img src="https://i.imgur.com/Vcty0XV.png" height="80%" width="80%" 
<br />
<br />
We can set SLA to Sev-A (1 hour, 24/7) and comment as wide impact, customers unable to do online banking. :  <br/>
<img src="https://i.imgur.com/F3WRduB.png" height="80%" width="80%" 
<br />
<br />
Change help topic to Report a Problem / Business Critical Change and comment "No customers able to access online banking":  <br/>
<img src="https://i.imgur.com/lFPb0K8.png" height="80%" width="80%" 
<br />
<br />
Assign to Online Banking Team:  <br/>
<img src="https://i.imgur.com/hWLx2sD.png" height="80%" width="80%" 
<br />
<br />
We will log out and work the ticket to completion as jane:  <br/>
<img src="https://i.imgur.com/1PuGLyf.png" height="80%" width="80%" 
<br />
<br />
In Jane account, assign to Jane with comment "I'll be assigning this ticket":  <br/>
<img src="https://i.imgur.com/ALvaR0D.png" height="80%" width="80%" 
<br />
<br />
Post a reply "I ﻿suspect the problem might be related to the recent updates. We tested them sufficiently, but I'm going to look into it further and roll the back if I determine that was the cause " for situation report > Post Reply:  <br/>
<img src="https://i.imgur.com/0bvT2D2.png" height="80%" width="80%" 
<br />
<br />
We are simulating that the issue was fixed. We can comment "It was determined, the root cause was the recent up date. We rolled it back, notified the vendor and waiting for proper fix. Online Banking should be up.:  <br/>
<img src="https://i.imgur.com/wZZ32NR.png" height="80%" width="80%" 
<br />
<br />
We can change the status of ticket to resolved:  <br/>
<img src="https://i.imgur.com/85ABjAk.png" height="80%" width="80%" 
<br />
<br />
Another ticket example: We can log in as Karen as the end user, with email: karen@test.com:  <br/>test X:  <br/>
<img src="https://i.imgur.com/nBRpJkI.png" height="80%" width="80%" 
<br />
<br />
Ken > General Inquiry/ Other and we can type in issue summary- accounting department needs adobe upgrade, broken and comment - Many people in the accounting department cannot use adobe software:  <br/>
<img src="https://i.imgur.com/RRSybWH.png" height="80%" width="80%" 
<br />
<br />
We can log back in as Help Desk agent john:  <br/>
<img src="https://i.imgur.com/BLN6PNT.png" height="80%" width="80%" 
<br />
<br />
In the ticket, we can assign it to John. We can change to SLA-C because of its the measured impact on the business :  <br/>
<img src="https://i.imgur.com/HDuN9uM.png" height="80%" width="80%" 
<br />
<br />
For the comments, we can put Customer states only two people in accounting department unable to open and use Adobe Reader (CX texting and restart) Will call back after lunch > post reply  <br/>
<img src="https://i.imgur.com/jfigi0L.png" height="80%" width="80%" 
<br />
<br />
We pretended that a few hours went by and the user states that restart fixed issue. we can put for the comments cx said restart fixed issue:  <br/>
<img src="https://i.imgur.com/kf6maEY.png" height="80%" width="80%" 
<br />
<br />
status: resolved!:  <br/>
<img src="https://i.imgur.com/vZPlZmI.png" height="80%" width="80%" 
<br />
<br />
<b> osTicket: Creating and Working Tickets is now Complete!
We've successfully gone through the life cycle of a ticket from creation to resolution, made changes to the tickets when necessary like assigning the tickets, changing the SLA (Service Level Agreement), and commenting to create a thread of clear communication!  <br/>
