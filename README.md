# Ex--10-IAM-working-overview
### Name: Visveswarran H
### Reg No: 212224110063
### Aim
**To explore and configure AWS Identity and Access Management (IAM) users, groups, and policies, and to verify permissions for accessing Amazon S3 and Amazon EC2 resources.**
### Procedure
1. Start the AWS Lab and open the **AWS Management Console**.
2. Open **IAM → Users** and verify `user-1`, `user-2`, and `user-3`.
3. Open **User groups** and verify the groups **S3-Support, EC2-Support, and EC2-Admin** and their attached policies.
4. Add:

   * `user-1` → **S3-Support**
   * `user-2` → **EC2-Support**
   * `user-3` → **EC2-Admin**
5. Open the IAM **Sign-in URL** and sign in as each user using the given lab credentials.
6. Test `user-1`: verify **S3 access** and confirm **EC2 access is denied**.
7. Test `user-2`: verify **EC2 read-only access** and confirm that stopping an EC2 instance is denied; verify **S3 access is denied**.
8. Test `user-3`: open **EC2**, select `LabHost`, and **stop the instance** successfully.
9. Submit the lab and check the **Grades/Submission Report**.
10. End the lab after completing all tasks.
### Output
<img width="1265" height="560" alt="image" src="https://github.com/user-attachments/assets/808988a9-87c1-45c4-89bb-f9413abb271b" />
<img width="1402" height="952" alt="Screenshot 2026-08-20 132443" src="https://github.com/user-attachments/assets/4f1f7a76-bfcb-45ce-bba0-993df0281d59" />
<img width="1415" height="969" alt="Screenshot 2026-08-20 132503" src="https://github.com/user-attachments/assets/65376ed6-97a5-48ed-9284-27ad98542009" />
<img width="1395" height="953" alt="Screenshot 2026-08-20 133317" src="https://github.com/user-attachments/assets/07ad7c0b-cc13-4403-8464-f3051af35695" />
<img width="1411" height="970" alt="Screenshot 2026-08-20 134444" src="https://github.com/user-attachments/assets/fa161fc3-226f-417f-ad74-a3469ec92392" />
<img width="1905" height="956" alt="Screenshot 2026-08-20 134607" src="https://github.com/user-attachments/assets/c0af8b89-18ab-4250-a7c5-66a9ebd81ab3" />
<img width="1862" height="962" alt="Screenshot 2026-08-20 134620" src="https://github.com/user-attachments/assets/2a6442ee-85f3-4bb0-88f8-7b17806901c1" />



### Result
The IAM users were successfully assigned to their respective groups, and the required permissions were verified. `user-1` received S3 read-only access, `user-2` received EC2 read-only access, and `user-3` received EC2 administrative access to start/stop instances. Thus, IAM users, groups, policies, and permissions were successfully explored and tested.
