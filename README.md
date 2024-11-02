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
Designing the Onboarding MS Form:
 <br/>

![image](https://github.com/user-attachments/assets/a74f322c-ecae-48a1-915f-6d19dc87ee5c)




<p align="center">
Setting Up Required Connections in Power Automate:
<br/>

![image](https://github.com/user-attachments/assets/efe09596-ee9b-4d21-979c-a79015ff76e1)


<br />
<br />
<p align="center">
Designing the onboarding workflow
<br/>
</p>

![image](https://github.com/user-attachments/assets/8e77032e-694f-4a67-9e9e-7095e07f5abe)


![image](https://github.com/user-attachments/assets/187b2d54-2780-480c-96f2-10a0e0d9a18c)


![image](https://github.com/user-attachments/assets/8e8a6204-5b79-48fb-990c-f9583dbd8486)


<p align="center">
Setting Up the Dynamic RBAC Group:
<br/>

![image](https://github.com/user-attachments/assets/1a1a6b5f-42c7-464c-999c-9b6b0e80134a)


![image](https://github.com/user-attachments/assets/03611ee1-fd64-48ee-bc6e-ab703420feed)




<p align="center">
Validating the Workflow After Form Submission:

<br/>

![image](https://github.com/user-attachments/assets/c1b188af-0494-4bd3-8b1b-e9cce8bfe020)







<p align= "center">
Verifying User Account Creation in Entra:



![image](https://github.com/user-attachments/assets/665146f1-02eb-431f-80d8-e6f0eb1fe9dc)



<p align= "center">
Verifying Successful Addition to the Dynamic Group:

![image](https://github.com/user-attachments/assets/8ded5f68-f93a-4561-acc9-00630b64c2ca)



<p align= "center">
Verifying Onboarding Emails Were Sent

![image](https://github.com/user-attachments/assets/bd78f3ca-4045-4eb9-82e4-0376e58d5182)







<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
