# Automated_Penetration_Tester Algorithm 
Start
 |
 V
Enter the target IP address
 |
 V
Check if SSH (port 22) is open on the target IP
 |
 V
If SSH is open:
 |----> Enter SSH username
 |       |
 |       V
 |     Enter SSH password
 |       |
 |       V
 |     Attempt SSH dictionary attack
 |       |
 |       V
 |     If attack successful:
 |       |----> Perform additional actions for SSH
 |       |
 |       V
 |     If attack unsuccessful:
 |           |
 |           V
 |         Continue or end the program
 |
 V
If RDP (port 3389) is open on the target IP
 |
 V
Enter RDP username
 |
 V
Enter RDP password
 |
 V
Attempt RDP dictionary attack
 |
 V
If attack successful:
 |----> Perform additional actions for RDP
 |
 V
If attack unsuccessful:
       |
       V
     Continue or end the program
 |
 V
End
