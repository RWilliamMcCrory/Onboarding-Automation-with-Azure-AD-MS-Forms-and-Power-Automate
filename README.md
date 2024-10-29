<h1>Onboarding Automation with Azure AD, MS Forms, and Power Automate</h1>


<h2>Description</h2>
This project automates the joiner process using Azure AD, MS Forms, and Power Automate. New joiner details are captured through a form, and Power Automate handles user setup and group assignment in Azure. Dynamic group rules ensure new users are added to the right Azure AD groups automatically, making onboarding faster and easier for HR and IT teams. 
<br />


<h2>Languages and Utilities Used</h2>

- <b>Azure</b> 
- <b>MS Forms</b>
- <b>Power Automate</b>

<h2>Environments Used </h2>

- <b>Azure</b>

<h2>Project walk-through:</h2>


<p align="center">
Designing the Onboarding MS Form and Testing as HR:
 <br/>

![image](https://github.com/user-attachments/assets/bcccce91-8c1c-4a33-b81d-35abb19ba21d)

![image](https://github.com/user-attachments/assets/25ff2527-88f4-44c7-aeb3-0e3eaf7f694a)




<p align="center">
Setting Up Required Connections in Power Automate:
<br/>

![image](https://github.com/user-attachments/assets/2d120f7a-bece-48b7-a9cb-6f2fdcd79358)

<br />
<br />
<p align="center">
Designing the onboarding workflow
<br/>
</p>

![image](https://github.com/user-attachments/assets/1fec3716-9632-454a-9acd-659171e73a1e)

![image](https://github.com/user-attachments/assets/a204a9a6-2770-4955-a5ce-fc4f1a501e08)

![image](https://github.com/user-attachments/assets/77f22b85-04ce-4fc9-87e1-d5ca8bad5f32)

<p align="center">
Setting Up the Dynamic RBAC Group:
<br/>

![image](https://github.com/user-attachments/assets/301b9337-e64b-4f11-af97-338a21b5d6fa)

![image](https://github.com/user-attachments/assets/2a0c2da6-c854-4eb2-bcf4-c3c9e2ae1ea9)



<p align="center">
Validating the Workflow After Form Submission:

<br/>

![image](https://github.com/user-attachments/assets/355817e7-e224-4128-8c3e-0b0fb9e030e2)






<p align= "center">
Verifying User Account Creation in Entra:



![image](https://github.com/user-attachments/assets/7974ec0e-f095-4f7b-aaf8-eae2a45b830b)



<p align= "center">
Verifying Successful Addition to the Dynamic Group:

![image](https://github.com/user-attachments/assets/3d7f6e79-6675-47f4-b952-1ff3a48d0922)



<p align= "center">
Verifying Onboarding Emails Were Sent

![image](https://github.com/user-attachments/assets/cd3fc998-176d-4de9-bbfc-929a058e056d)






<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
