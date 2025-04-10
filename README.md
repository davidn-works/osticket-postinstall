<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Installation Setup</h1>
Building upon the initial lab work, the next step is to configure and define roles, departments, Service Level Agreements (SLAs), and various help topics. To begin this configuration, you must first remotely connect to the Virtual Machine established during the preceding lab.<br />

<h2>Utilized Environments and Software</h2>

- Microsoft Azure (Virtual Machines/Compute)
- [Remote Desktop](https://apps.apple.com/us/app/microsoft-remote-desktop/id1295203466?mt=12)

<h2>Operating System Platform</h2>

- Windows 10</b> (21H2)

<h2>Goals for Post-Installation Setup</h2>

- [Roles](https://docs.osticket.com/en/latest/Admin/Agents/Roles.html)
- [Departments](https://docs.osticket.com/en/latest/Admin/Agents/Departments.html)
- [Teams](https://docs.osticket.com/en/latest/Admin/Agents/Teams.html)
- [Agents](https://docs.osticket.com/en/latest/Admin/Agents/Agents.html)
- [Users](https://docs.osticket.com/en/latest/Agent/Users/User%20Directory.html)
- [SLA](https://docs.osticket.com/en/latest/Admin/Manage/SLA%20Plans.html)
- [Help Topics](https://docs.osticket.com/en/latest/Admin/Manage/Help%20Topic.html)

<h2>Configuration Procedure</h2>


<p>
The majority of necessary configurations are accessible from one central area. To reach these settings, navigate to the Admin Panel located in the upper-left portion of the interface. Once there, go into the "Agents" area. This section contains the settings for managing Roles, Departments, Teams, and Agents.
</p>
<br />

<p>
<img width="886" alt="screenshot1 - Copy" src="https://github.com/user-attachments/assets/d9467061-a4f5-452e-b0a2-114b2d3f6896" />
</p>
<p>
We will now create a new role named "Supreme Admin". This role is designed to provide broad permissions, giving an administrator significant flexibility to execute and alter various system functions.

- Navigate to the "Roles" area within the Admin Panel.
- Select the option to "Add New Role" or a similar button to initiate role creation.
- Assign a name to the role, for instance, "Supreme Admin" or your preferred identifier.
- Under the "Permissions" tab, enable the checkboxes for "Tickets," "Tasks," and "Knowledgeable" to assign comprehensive access rights.
- After setting all desired permissions, save the new role.
</p>
<br />

<p>
<img width="668" alt="screenshot2 - Copy" src="https://github.com/user-attachments/assets/ecda4bb1-8a68-43a5-a888-48b6230e3814" />
</p>
<p>
  To establish a new department called "System Administrators," adhere to the following instructions:

  - Remaining in the same area, go to the "Departments" section.
  - Find and click the button labeled "Add New Department" or similar.
  - Enter the name for the department, like "System Administrators."

    - Keep in mind that this screen offers further configuration possibilities, such as assigning managers, defining outgoing email parameters, setting up auto-responses, and configuring alerts/notices. These additional options will be bypassed for this particular exercise.

  - When you have made all required selections and entries, click "Create Department" to complete the department setup.
</p>
<br />

<p>
<img width="874" alt="screenshot3 - Copy" src="https://github.com/user-attachments/assets/6febb3dd-7a5a-436a-9f9f-f9bdb33ced3a" />
</p>
<p>Accessing Service Level Agreements (SLAs) and Help Topics.

  Adhere to these guidelines:

    - Inside the Admin Panel, locate the "Manage" area.
    - Select "SLA" or "Service Level Agreements" to enter the SLA configuration settings.
    - Proceed to create three distinct SLAs. You can name them as needed; for this guide, we'll use "SEV-A," "SEV-B," and "SEV-C" corresponding to their intended timeframes and coverage:
       - "SEV-A": 1-hour response timeframe, 24/7 coverage.
       - "SEV-B": 4-hour response timeframe, 24/7 coverage.
       - "SEV-C": 8-hour response timeframe, applicable during standard business hours.
    - Save the settings for each SLA to finalize their creation.

To establish Help Topics, follow this procedure:

    - Staying within the "Manage" section of the Admin Panel, find and select "Help Topics."
    - Create the following four help topics:
        - "Business Critical Outage"
        - "Personal Computer Issues"
        - "Equipment Request"
        - "Password Reset"
    - Save each Help Topic after creating it.
</p>
<br />

<p>
<img width="842" alt="screenshot4 - Copy" src="https://github.com/user-attachments/assets/37a659e8-0057-4f5a-8dfc-63f51da6171f" />
</p>
<p>
Excellent! Now, let's configure some Users (representing customers) by following these instructions:

- Navigate to the "Admin Panel".
- Inside the Admin Panel, find the control to switch over to the Agent Panel view.
- After switching to the Agent Panel, locate the "Users" area.
- Select "Add User" or a comparable option to begin creating new user profiles.
- Employing the same method used previously for creating items, generate two User profiles with the names Karen and Kevin (or other names if you prefer).
- Adjust any other settings for each user as needed, like contact details or specific preferences.
- Save the profiles to add Karen and Kevin as Users in the system.

<p>
<img width="666" alt="screenshot5 - Copy" src="https://github.com/user-attachments/assets/ad7fec42-0ea2-41fa-baaa-465d1e9d3ac9" />
</p>
<p>
Since the process for creating these elements is now familiar, we can use a comparable method to establish Teams and Agents. Follow these instructions:

Setting up a Second Team ("Level II Support"):

1. In the Admin Panel, go to the "Teams" section.
2. Select the option to "Add New Team" or similar to start.
3. Enter "Level II Support" or your chosen name for the team.
4. Adjust any specific settings for this team if necessary.
5. Save the team to create the "Level II Support" team.

Setting up Two Agents ("Jane Doe" and "John Doe"):

1. Go to the "Agents" area within the Admin Panel.
2. Find the "Add New Agent" button or equivalent.
3. Enter the names "Jane Doe" and "John Doe" (or names of your choice).
4. Configure pertinent details for each agent, like contact info or assigned roles.
5. Save the profiles to add "Jane Doe" and "John Doe" as agents.

Following these instructions will result in the successful creation of a second team called "Level II Support" and two agents named "Jane Doe" and "John Doe" (or your chosen names).
</p>
<br />

<p>
Well done! You have now successfully configured the osTicket software, including roles, departments, SLAs, help topics, and more.

</p>
<br />
