# AutoScaling_HandOn

## Overview
This repository documents a hands-on exercise on configuring Auto Scaling Groups (ASG) on AWS. The task involved creating an ASG, configuring a launch template, and observing dynamic scaling in action.

## Steps
### Step 1
![Step 1](https://github.com/RimshaAzmat/AutoScaling_HandOn/assets/144583193/9fa96352-3cfd-468a-a0f2-522390b97611)

### Step 2: Creating Launch Template
![Step 2](https://github.com/RimshaAzmat/AutoScaling_HandOn/assets/144583193/14d48dee-dbdd-4659-be18-0ff096f866e5)

### Step 3
![Step 3](https://github.com/RimshaAzmat/AutoScaling_HandOn/assets/144583193/5bc13b17-f5ad-4d44-a8b5-cb18f1c33141)

### Step 4: Adding Launch Template to ASG
![Step 4](https://github.com/RimshaAzmat/AutoScaling_HandOn/assets/144583193/e24e8c6f-fc84-40eb-9b1c-9f4d555f8337)

### Step 5: Automatic Instance Creation
![Step 5](https://github.com/RimshaAzmat/AutoScaling_HandOn/assets/144583193/47744635-5284-4630-98d7-5ed178577c0c)

### Step 6: ASG Activity Log
![Step 6](https://github.com/RimshaAzmat/AutoScaling_HandOn/assets/144583193/1f6bf7cd-bf99-4af1-a29f-f11961bf8c54_)

### Step 7
![Step 7](https://github.com/RimshaAzmat/AutoScaling_HandOn/assets/144583193/71c49000-f203-4fac-9871-31f17dfc5904)

### Step 8
![Step 8](https://github.com/RimshaAzmat/AutoScaling_HandOn/assets/144583193/68653a20-9617-47a0-a76e-1b638b9a1196)

### Step 9: EC2 Dashboard
![Step 9](https://github.com/RimshaAzmat/AutoScaling_HandOn/assets/144583193/fee7e609-c2de-47a7-83d2-88031847dbf2)

## Target Tracking Policy
- Edit the dynamic scaling configuration in the activity log.
- Connect to one instance and install stress to increase its workload.
- Observe in the activity history that new instances are created to handle the increased workload.
- Upon rebooting and removing the stress, notice that instances start deleting.

This README provides a visual walkthrough of configuring Auto Scaling Groups and demonstrates the dynamic scaling capabilities of AWS Auto Scaling.

Feel free to contribute or provide feedback! Happy scaling! 🚀
