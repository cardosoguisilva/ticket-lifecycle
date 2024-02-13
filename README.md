<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket: Ticket Lifecycle Examples</h1>
In this last part of the tutorial, I will be showing you a few examples of how osTicket is used. We will simulate multiple ticket lifecycles. <br />

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
  <ul>
    <li>Log into your virtual machine and use this URL http://localhost/osTicket/ to make a ticket.  </li>
    </ul> 
</p>

![image](https://github.com/cardosoguisilva/ticket-lifecycle/assets/157248613/bfd02a28-a71b-46ff-a517-ac70e9452512)

- Click on "Open a New Ticket" and create the following tickets
- Sev-A (1 hour, 24/7) [entire mobile/online banking system is down] -> SysAdmins
- Sev-B (4 hours, 24/7) [accounting department needs Adobe upgrade, broken]
- Sev-B/C (2 hours, business hours) [CFO’s laptop seems a bit slow]

- Sev A example
![image](https://github.com/cardosoguisilva/ticket-lifecycle/assets/157248613/1772c206-044a-4f06-8374-f6d6148e8c5a)


<h4>Creating a ticket</h4>
<p>
  <ul>
    <li>Log into your virtual machine and use this URL http://localhost/osTicket/ to make a ticket.  </li>
    </ul> 
</p>

<h4>Step 2</h4>
<p>
  <ol type="1"> 
    <li> Configuring agent <a href="https://docs.osticket.com/en/latest/Admin/Agents/Roles.html">ROLES</a> </li>
  <ul> 
    <li> Go to Admin Panel -> Agents -> Roles</li>
    <li> Create "Supreme Admin" by selecting all boxes in Tickets, Tasks and Knowledgebase.</li> </ul> 
  <br> </ol> 
    
![image](https://github.com/cardosoguisilva/post-install-config/assets/157248613/8ce94b43-2a8d-40aa-b9fb-c2400b60ee7d)
</p>
<p>    
  <ol start="2">
    <li> Configuring <a href="https://docs.osticket.com/en/latest/Admin/Agents/Departments.html">DEPARTMENTS</a> </li>
  <ul> 
    <li> Go to Admin Panel -> Agents -> Departments </li>
    <li> Create a new department called System ADMIN with system default.</li>
<br> </ol>
  
![image](https://github.com/cardosoguisilva/post-install-config/assets/157248613/ce0ba838-c872-4675-b42d-546728800e3f)
</p>
<p>
<ol start="3">
<li>Configuring <a href="https://docs.osticket.com/en/latest/Admin/Agents/Teams.html">TEAMS</a> </li>
  <ul>
    <li>Go to Admin Panel -> Agents -> Teams</li>
    <li>Create a new team " LEVEL II Support"</li>
    </ol> <br>

![image](https://github.com/cardosoguisilva/post-install-config/assets/157248613/d779666d-8b9c-4c2a-99cb-bebd81332ef3)
</p>
<p>
<ol start="4">
<li>Allowing anyone to create a ticket.</li>
  <ul>
    <li>Admin Panel -> Settings -> User</li>
    <li>By default, "Registration Required: Require registration and login to create tickets" should be unchecked. This will allow people to make tickets anonymously.</li>
    </ol> <br>
 
![image](https://github.com/cardosoguisilva/post-install-config/assets/157248613/50b00f10-eff0-4da2-974c-eb0506641556)
</p>
<p>
<ol start="5">
<li>Creating <a href="https://docs.osticket.com/en/latest/Admin/Agents/Agents.html">AGENTS</a></li>
  <ul>
    <li>Admin Panel -> Agents -> Add New</li>
    <li>Add multiple agents create a username and password for each agent, write it down in case you forget.</li>
     <li>Make sure to select Access/Permissions/Teams for each agent.</li>

  ![image](https://github.com/cardosoguisilva/post-install-config/assets/157248613/15fe89c2-435b-48e1-9297-ed0da6c0a90d)
    <li>Unselect "Send the agent a password reset email" and "Require password change at next login"</li>
    
  ![image](https://github.com/cardosoguisilva/post-install-config/assets/157248613/c3ea4f16-68bb-44d5-971a-324673ca8790)
    </ol> <br>
    
</p>

<p>
<ol start="6">
<li>Configure <a href="https://docs.osticket.com/en/latest/Agent/Users/User%20Directory.html">USERS</a> </li>
  <ul>
    <li>Click on Agent Panel -> Users -> Add New </li>
    <li>Create two users.</li>
    
- Karen
- Ken

![image](https://github.com/cardosoguisilva/post-install-config/assets/157248613/b4b97d75-00e6-4ab9-9eb4-bb346924ab63)
  </ol> <br>
</p>    


<p>
<ol start="7">
<li>Configure <a href="https://docs.osticket.com/en/latest/Admin/Manage/SLA%20Plans.html">SLA</a> </li>
  <ul>
    <li>Admin Panel -> Manage -> SLA -> Add New SLA Plan</li>

- Sev-A (1 hour, 24/7)
- Sev-B (4 hours, 24/7)
- Sev-C (8 hours, business hours) 
    </ol> <br>
    
    ![image](https://github.com/cardosoguisilva/post-install-config/assets/157248613/33eb5d63-e335-4f84-94cd-9d977a1d35bf)
</p>  

<p>
<ol start="8">
<li>Configure <a href="https://docs.osticket.com/en/latest/Admin/Manage/Help%20Topic.html">HELP TOPICS</a> </li>
  <ul>
    <li>Admin Panel -> Manage -> Help Topics</li>
    <li>Create these four Help Topics</li>

  - Business Critical Outage
  - Personal Computer Issues
  - Equipment Request
  - Password Reset
  
    </ol> <br>
    
    ![image](https://github.com/cardosoguisilva/post-install-config/assets/157248613/996c8f99-b1b4-409a-88a7-e21f4e33cf2d)
</p>  
    
