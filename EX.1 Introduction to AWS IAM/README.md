# Lab 1 - Introduction to AWS Identity and Access Management (IAM)

## Title
Introduction to AWS Identity and Access Management (IAM)


## Objective
The objective of this lab is to understand how AWS Identity and Access Management (IAM) controls authentication and authorization in AWS. The lab focuses on exploring IAM users and groups, analyzing attached policies, assigning users to appropriate groups based on organizational roles, and validating permissions by testing service access.


## Prerequisites
- Basic understanding of cloud computing concepts  
- AWS Academy Lab access  
- Web browser with internet connectivity  


## Tools Used
- AWS Management Console  
- AWS Identity and Access Management (IAM)  
- Amazon EC2  
- Amazon S3  


## Tasks Performed

### Task 1: Explore IAM Users and Groups
- Reviewed pre-created IAM users: user-1, user-2, user-3  
- Explored IAM groups: EC2-Admin, EC2-Support, S3-Support  
- Inspected managed and inline policies attached to groups  
**Screenshot:**
  
<img width="1907" height="983" alt="image" src="https://github.com/user-attachments/assets/4ccc636b-377a-4658-84f3-0c201a3bb23b" />



### Task 2: Add Users to Groups
- Added user-1 to the S3-Support group  
- Added user-2 to the EC2-Support group  
- Added user-3 to the EC2-Admin group  
**Screenshot:**  
<img width="1916" height="976" alt="image" src="https://github.com/user-attachments/assets/18e98e7d-c3ca-4ca0-8d31-6b5d850d94cd" />
<img width="1913" height="977" alt="image" src="https://github.com/user-attachments/assets/953fb49b-cc80-44bb-b73c-1e3cd30bea72" />
<img width="1917" height="987" alt="image" src="https://github.com/user-attachments/assets/e475eeba-0338-44a2-9457-8d072a715199" />

### Task 3: Test IAM User Permissions
- Logged in using IAM sign-in URL  
- Verified S3 access for user-1  
- Verified EC2 read-only access for user-2  
- Verified EC2 administrative access for user-3  
**Screenshot:**
<img width="1917" height="983" alt="image" src="https://github.com/user-attachments/assets/6bf1bf75-8685-477c-b336-52429fb4ce5b" />
<img width="1917" height="992" alt="Screenshot 2026-08-03 153619" src="https://github.com/user-attachments/assets/771ca1b7-9dc3-457f-8a9a-1ec939d146ad" />
<img width="1917" height="985" alt="Screenshot 2026-08-03 154431" src="https://github.com/user-attachments/assets/4730bbc3-9b14-46a4-a2d1-271ae4dcdc3e" />

## Workflow
1. Accessed IAM console and reviewed users and groups.  
2. Inspected policy permissions attached to groups.  
3. Assigned users to groups based on their roles.  
4. Logged in as each IAM user using the sign-in URL.  
5. Validated permissions by accessing AWS services.  


## Learning Outcomes
- Understood the role of IAM in AWS security.  
- Learned how IAM users, groups, and policies interact.  
- Gained practical experience implementing role-based access control.  
- Verified permission enforcement through real-time service testing.  


## Conclusion
This lab provided hands-on experience with AWS IAM by demonstrating how organizations manage secure access to cloud resources. Assigning users to groups with predefined policies simplified permission management and ensured role-based access control across AWS services.


## Author
**Name:** Your Name and (Reg No)
**Course:** Introduction to Cloud Computing  

