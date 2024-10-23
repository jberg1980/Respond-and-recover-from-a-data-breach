<h1>Respond-and-recover-from-a-data-breach</h1>


<h2>Description</h2>
In this capstone project, I will examine the vulnerabilities and findings in Google Cloud Security Command Center to determine how the attackers gained access to the data, and which remediation steps to take:
Task 1. Analyze the data breach and gather information
Task 2. Fix the Compute Engine vulnerabilities
Task 3. Fix Cloud Storage bucket permissions
Task 4. Limit firewall ports access
Task 5. Fix the firewall configuration
Task 6. Verify compliance


<h2>Languages and Utilities Used</h2>

- <b>Google Cloud Security Command Center</b> 

<h2>Environments Used </h2>

- <b>Windows 11</b> (23H2)

<h2>Program walk-through:</h2>

<p align="center">

<img src="https://i.imgur.com/gSp9m5T.png" height="80%" width="80%" alt="Google Cloud Security Project"/>
<br />
<br />

<img src="https://i.imgur.com/iTY6bkg.png" height="80%" width="80%" alt="Google Cloud Security Project"/>
<br />
<br />

<img src="https://i.imgur.com/PmRBvdF.png" height="80%" width="80%" alt="Google Cloud Security Project"/>
<br />
<br />

<img src="https://i.imgur.com/TKL2ah2.png" height="80%" width="80%" alt="Google Cloud Security Project"/>
<br />
<br />

<img src="https://i.imgur.com/RI4X7f3.png" height="80%" width="80%" alt="Google Cloud Security Project"/>
<br />
<br />

<img src="https://i.imgur.com/fzMZZ7a.png" height="80%" width="80%" alt="Google Cloud Security Project"/>
<br />
<br />

<img src="https://i.imgur.com/RxHgK60.png" height="80%" width="80%" alt="Google Cloud Security Project"/>

<h2>Summary</h2>
•	First, I examined and analyzed the vulnerabilities and findings in Google Cloud Security Command Centre. The PCI DSS 3.2.1 report 85% compliant.
•	Next, I shut the old VM down and created a new VM from a snapshot taken before the malware infection.
•	Then, I fixed the cloud storage permissions by revoking public access to the storage bucket and switching to uniform bucket-level access control. I also removed all user permissions from the storage bucket.
•	Next, I fixed the firewall rules by deleting the default-allow-icmp, default-allow-rdp, and default-allow-ssh firewall rules, and enabling logging for the remaining firewall rules.
•	Finally, I run a compliance report to confirm that the vulnerability issues have been remediated. The PCI DSS 3.2.1 report 90% compliant.

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
