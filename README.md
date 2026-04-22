<h1>Active Directory Security Audit: Privileged Access Review</h1>

<h2>Description</h2>

This project demonstrates a security-focused audit of privileged access within an Active Directory environment. The lab simulates real-world administrative and security tasks used to identify, review, and remediate high-risk account permissions.

In this lab, I used PowerShell and Active Directory tools to audit Domain Admins and other high-privilege groups, remove unauthorized access, and generate CSV reports for compliance and security monitoring. This project highlights practical experience in access control, privilege management, and security auditing within a Windows Server environment.

<br />

<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b>
- <b>Active Directory Users and Computers (ADUC)</b>
- <b>Active Directory Domain Services (AD DS)</b>
- <b>CSV Reporting</b>

<br />

<h2>Environments Used</h2>

- <b>Windows Server 2019</b>
- <b>Windows 10</b>

<br />

<h2>Security Audit Walk-through:</h2>

<p align="center">

Open Active Directory Users and Computers<br/>
<i>Access the domain environment to manage and review user accounts.</i><br/>

<img src="step1-open-aduc.png" width="100%"/>
<br/><br/>

Identify Domain Admins Using PowerShell<br/>
<i>Retrieve members of the Domain Admins group to identify privileged users.</i><br/>

<img src="step2-domain-admins-powershell.png" width="100%"/>
<br/><br/>

Export Domain Admins to CSV Report<br/>
<i>Generate a report of privileged users for auditing and compliance purposes.</i><br/>

<img src="step3-export-domain-admins-csv.png" width="100%"/>
<br/><br/>

Verify CSV Report Output<br/>
<i>Confirm the report was successfully generated and stored.</i><br/>

<img src="step4-verify-csv-file.png" width="100%"/>
<br/><br/>

Remove User from Domain Admins Group<br/>
<i>Revoke unnecessary administrative privileges to enforce least privilege.</i><br/>

<img src="step5-remove-user-01.png" width="100%"/>
<br/>
<img src="step5-remove-user-02.png" width="100%"/>
<br/><br/>

Create PowerShell Script to Audit High-Privilege Groups<br/>
<i>Develop a script to audit multiple high-risk Active Directory groups.</i><br/>

<img src="step6-script-01.png" width="100%"/>
<br/>
<img src="step6-script-02.png" width="100%"/>
<br/>
<img src="step6-script-03.png" width="100%"/>
<br/><br/>

Execute Script and Review Output<br/>
<i>Run the audit script to identify members of high-privilege groups.</i><br/>

<img src="step7-script-test-01.png" width="100%"/>
<br/>
<img src="step7-script-test-02.png" width="100%"/>
<br/>
<img src="step7-script-test-03.png" width="100%"/>

<br/><br/>

</p>

<h2>Skills Demonstrated</h2>

• Privileged Access Auditing  
• Active Directory Security Management  
• PowerShell Scripting and Automation  
• Identity and Access Management (IAM)  
• Security Compliance Reporting  
• Least Privilege Enforcement  
