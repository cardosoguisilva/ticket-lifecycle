<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket: Ticket Lifecycle Examples</h1>
In this last part of the tutorial, I will show you a few examples of how osTicket is used. We will simulate a ticket lifecycle. <br />

<h2>Video Demonstration</h2>

- ### [YouTube: Examples of Ticket Lifecycle](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

<ul>
<li>Microsoft Azure (Virtual Machines/Compute)</li>
<li>Remote Desktop</li>
</ul> 

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- osTicket Installed
- Configuration of osTicket

<h2>Ticket Lifecycle</h2>
<h4>Creating a ticket</h4>
<p>
  <ol>
    <li>Log into your virtual machine and use this URL http://localhost/osTicket/ to make a ticket.</li>
    <br>
    
  ![image](https://github.com/cardosoguisilva/ticket-lifecycle/assets/157248613/bfd02a28-a71b-46ff-a517-ac70e9452512)
    </ol> 
</p>
<p>
  <ol start="2">
    <li>Click on "Open a New Ticket" and create the following tickets</li>
<ul>
<li>Sev-A (1 hour, 24/7) [entire mobile/online banking system is down] -> SysAdmins</li>
<li>Sev-B (4 hours, 24/7) [accounting department needs Adobe upgrade, broken]</li>
<li>Sev-B/C (2 hours, business hours) [Department issues with slow tablets.]</li>
  <br>
  
 ![image](https://github.com/cardosoguisilva/ticket-lifecycle/assets/157248613/1772c206-044a-4f06-8374-f6d6148e8c5a)
</ul>   
  </ol> </p> 

<h4>Solving a Ticket </h4>
<p>
  <ol start= "1">
    <li>Log into osTicket as one of the HelpDesk agents we configured in the last tutorial. http://localhost/osTicket/scp/login.php  </li>
<br>
    
  ![image](https://github.com/cardosoguisilva/ticket-lifecycle/assets/157248613/8c122f54-66b9-49ac-8e59-43fd80f208c6)

  <li> If you can't see the tickets we created, log back into your account's admin panel and make sure the agent has access to edit/view tickets.</li>
  <li>Open the first ticket example and toy with it so you can get a feel for it, editing Status/Priority/Department/SLA, etc. Assign accordingly. </li>
<br>

  ![image](https://github.com/cardosoguisilva/ticket-lifecycle/assets/157248613/90e21a3e-3524-41c0-a79f-a859152fa762)
    </ol> 
</p>
<p>
<ol start= "4">
<li>After making changes on the main page of the tickets, the differences will be reflected.</li>
  <br>
  
![image](https://github.com/cardosoguisilva/ticket-lifecycle/assets/157248613/87cde957-8a7a-453a-9290-66c39c7739ab)

<li> Pretend the ticket has been resolved and change the ticket status to 'Resolved.' You will notice it disappears from the main ticket tab. If you want to view the solved ticket again, click 'Closed.'</li>

<li>There are another 2 examples of tickets for you to try on your own.</li>

</p>














