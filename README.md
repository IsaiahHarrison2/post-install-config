<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Installation Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />






<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>Post-Install Objectives</h2>

- Configure Roles
- Configure Department
- Configure Users
- Configure SLA
- Congfigure Help Topics

<h2>Installation Steps</h2>


![Screenshot 2025-07-05 at 3 52 03 PM](https://github.com/user-attachments/assets/b3da59de-2f82-46a3-8b13-a74e99ab612a)
In your web browser, the first thing you want to do is load up osTicket and login.



![Screenshot 2025-07-05 at 3 52 15 PM](https://github.com/user-attachments/assets/58129d5d-5943-4700-827e-aefe60cfe9b1)
Click the Admin Panel in the right hand corner next to your name.



![Screenshot 2025-07-05 at 3 53 48 PM](https://github.com/user-attachments/assets/f3715fb9-83b6-44d4-848e-42e58d42a30e)

Click The "Agents" tab next to email.Once you click that you'll then click Roles.


![Screenshot 2025-07-05 at 3 54 36 PM](https://github.com/user-attachments/assets/bfce53aa-3867-4961-9d73-cb9c32f42fe1)


Once you are in the roles tab, Click on "Add New Role"

![Screenshot 2025-07-05 at 3 55 27 PM](https://github.com/user-attachments/assets/a2a57377-ce2f-4cb6-8d1f-7a6037d85d4e)

If you want, you can assign permissions to the agents that way they can either interact with them or view only.

![Screenshot 2025-07-05 at 3 55 34 PM](https://github.com/user-attachments/assets/f246e955-93b5-4423-9db8-88e4df7fd2bc)

This is what it'll look like once you've assigned a role. The role I assigned was CFO. (somethins just for practice)

![Screenshot 2025-07-05 at 3 57 38 PM](https://github.com/user-attachments/assets/2a491163-64ab-41df-95d8-2e746cfa7a64)

In the Admin panel still, You want to then click departments

![Screenshot 2025-07-05 at 3 57 45 PM](https://github.com/user-attachments/assets/f8cd7d90-2725-4402-a83b-a9bd17bf30a0)

Click "Add New Department"

![Screenshot 2025-07-05 at 3 58 36 PM](https://github.com/user-attachments/assets/33c254ac-a7c2-48ea-ad6f-2ce7712fc9f1)

Through the Add Department feature, you can also assign SLA's and assign access. I chose Networking as the name.

![Screenshot 2025-07-05 at 3 59 49 PM](https://github.com/user-attachments/assets/599e7596-61f8-4bc9-8f0b-eaf02aaa129b)

You've now added a Department within osTicket.


![Screenshot 2025-07-05 at 4 03 28 PM](https://github.com/user-attachments/assets/11ff535b-8227-4716-83cc-7d089ea9bc8e)

Now switch into the agent panel of your login and locate Users and press the tab.


![Screenshot 2025-07-05 at 4 03 54 PM](https://github.com/user-attachments/assets/65a29fc4-d6ca-4eb5-8192-f8dcc9e99ccc)


Click "Add User"


![Screenshot 2025-07-05 at 4 05 54 PM](https://github.com/user-attachments/assets/81c516a4-36c8-44c2-94f2-f6d5fbb64f3f)

Add Their name and email and then click add but make sure they are added to the users list.


![Screenshot 2025-07-05 at 4 06 05 PM](https://github.com/user-attachments/assets/06274cbf-f488-4eba-8893-26f39b3a7ceb)


This is what the users description will look like once finished.



![Screenshot 2025-07-05 at 4 06 58 PM](https://github.com/user-attachments/assets/76ad2caa-ca76-422e-b91e-4c169398d44c)

Switch back to the Admin panel, click on the manage tab and then click SLA.


![Screenshot 2025-07-05 at 4 07 52 PM](https://github.com/user-attachments/assets/d69fb812-a1ad-4cc2-b25b-848b6701579f)


Click "Add New SLA Plan"

![Screenshot 2025-07-05 at 4 08 14 PM](https://github.com/user-attachments/assets/4c0b4b33-8101-4806-a02c-c39356400fa6)

 Make the proper adjustments you need for your SLA and then add plan.




![Screenshot 2025-07-05 at 4 08 22 PM](https://github.com/user-attachments/assets/80945c30-0870-48fe-9931-26d93bf8a0f9)

Sev-C is now created



![Screenshot 2025-07-05 at 4 10 57 PM](https://github.com/user-attachments/assets/86764159-92d2-4040-ae65-cf535db5d5ab)

From that same manage tab, switch over to Help Topics



![Screenshot 2025-07-05 at 4 11 42 PM](https://github.com/user-attachments/assets/3c5d22fd-995f-43ab-ae3b-eae155e8148e)

CLick "Add New Help Topic"


![Screenshot 2025-07-05 at 4 12 12 PM](https://github.com/user-attachments/assets/f5286915-cc09-4d3d-8184-65c5a86d74ff)

Once you pick the create the help topic and review everything within it, click Add topic and youll be good to go.

