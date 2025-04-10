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
<img width="886" alt="screenshot1 - Copy" src="https://github.com/user-attachments/assets/2e59c527-3a3d-4b2d-82e2-d665a15662a7" />
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
<img width="668" alt="screenshot2 - Copy" src="https://github.com/user-attachments/assets/aeb64305-da91-4606-aa50-1b2cb5d3672c" />
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
<img width="874" alt="screenshot3 - Copy" src="https://github.com/user-attachments/assets/e9fdd1d7-794b-4613-a1af-f207dc341bf1" />
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
<img width="842" alt="screenshot4 - Copy" src="https://github.com/user-attachments/assets/2faeee34-c533-4a15-b1e5-405cc075bc29" />
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
<img width="666" alt="screenshot5 - Copy" src="https://github.com/user-attachments/assets/c1b199b1-6d70-411c-bfd6-7d29357d9112" />
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
