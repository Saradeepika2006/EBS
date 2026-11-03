## WORKING WITH EBS
## Name: Mopuri Saradeepika
## Reg no: 212224040201
## AIM:

In this lab environment, access to AWS services and service actions might be restricted to the ones that are needed to complete the lab instructions. You might encounter errors if you attempt to access other services or perform actions beyond the ones that are described in this lab.

## OBJECTIVE:

*Create an Amazon EBS volume
*Attach and mount your volume to an EC2 instance
*Create a snapshot of your volume
*Create a new volume from your snapshot
*Attach and mount the new volume to your EC2 instance
## ALGORITHM

# STEP 1:
In this step, you will create and attach an Amazon EBS volume to a new Amazon EC2 instance.You will see an existing volume that is being used by the Amazon EC2 instance. This volume has a size of 8 GiB, which makes it easy to distinguish from the volume you will create next, which will be 1 GiB in size.
# STEP 2:
In this step, you will connect to the Lab EC2 instance using Session Manager.You can now attach your new volume to the Amazon EC2 instance.
# STEP 3:
In this step, you will add the new volume to a Linux instance as an ext3 file system under the /mnt/data-store mount point.
# STEP 4:
You can create any number of point-in-time, consistent snapshots from Amazon EBS volumes at any time. Amazon EBS snapshots are stored in Amazon S3 with high durability. New Amazon EBS volumes can be created out of snapshots for cloning or restoring backups. Amazon EBS snapshots can also be easily shared among AWS users or copied over AWS regions.

## OUTPUT:
<img width="1920" height="1200" alt="Screenshot (92)" src="https://github.com/user-attachments/assets/308f7486-7ceb-489d-802a-19a33f54a46f" />

<img width="1920" height="1200" alt="Screenshot (93)" src="https://github.com/user-attachments/assets/509e99fe-75a3-4313-b50e-71868a671c7b" />

<img width="1920" height="1200" alt="Screenshot (94)" src="https://github.com/user-attachments/assets/853a5446-fdb8-4e07-96b2-ae5a896d3ee1" />

<img width="1920" height="1200" alt="Screenshot (95)" src="https://github.com/user-attachments/assets/5937952f-9da1-4c94-8385-3f0a7fd891f1" />

<img width="1920" height="1200" alt="Screenshot (96)" src="https://github.com/user-attachments/assets/6f0e65ee-7446-4a28-ae6f-cb1861405aa3" />

<img width="1920" height="1200" alt="Screenshot (97)" src="https://github.com/user-attachments/assets/f1f8383e-02ee-4bc3-b658-db427f8e4353" />

<img width="1920" height="1200" alt="Screenshot (98)" src="https://github.com/user-attachments/assets/211ccf1b-8171-4236-8a9f-a11c96fe56e3" />

<img width="1920" height="1200" alt="Screenshot (99)" src="https://github.com/user-attachments/assets/4ba475f1-60ac-43b1-9773-60128446a239" />

<img width="1920" height="1200" alt="Screenshot (100)" src="https://github.com/user-attachments/assets/b1227787-9460-4379-81bf-d74ffb9eed68" />

<img width="1920" height="1200" alt="Screenshot (103)" src="https://github.com/user-attachments/assets/4c660aaf-0622-4d5a-9d65-ca24fcd270f1" />

<img width="1920" height="1200" alt="Screenshot (105)" src="https://github.com/user-attachments/assets/030e2ba1-79d8-4893-b6a9-f5a323c6b14f" />

<img width="1920" height="1200" alt="Screenshot (107)" src="https://github.com/user-attachments/assets/1ce0c532-0bb6-4369-8079-3083cdc6e461" />

## RESULT:
Successfully created, managed, and deleted an EBS bucket on AWS, demonstrating the ability to upload, access, and control objects within Amazon EBS.
