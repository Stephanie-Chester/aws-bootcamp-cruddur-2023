# Week 0 — Billing and Architecture

# Homework/Tasks

I setup the following:

### 1. Created AWS Organization
### 2. Setup OU for this Cloud BootCamp
### 3. Created root user for the OU
### 4. Setup MFA for the root user
### 5. Created admin user
### 6. Tried out AWS CloudShell
### 7. Installed AWS Cli in Gitpod and set environmental variables

## GitPod AWS CLI

I intially had some problems with GitPod recognizing my user id after restarting the workspace. And then I realized that I had to stop, and delete the workspace and relaunch it from the GitPod button from within my GitHub repo.

https://github.com/Stephanie-Chester/aws-bootcamp-cruddur-2023/blob/main/_docs/assets/week0/Inked2023-02-18%2010_39_17-Welcome%20-%20aws-bootcamp-cruddur-2023%20%5BSSH_%20stephaniech-awsbootcamp-6rky64ck8rv.ss.jpg

## Create a Billing Alarm

I created a billing alarm with CloudWatch, I set the threshold to alert me the estimated spend is more than $30 dollars. I did for a 6 hour period, I tried to do 1 day but I received an error that it wouldn't trigger so I have to troubleshoot that.

<img width="1284" alt="Screenshot 2023-02-16 at 2 01 40 PM" src="https://user-images.githubusercontent.com/37819313/219479726-2c1902a3-f736-45e3-b734-ce0dd8bdaf55.png">

## Create an admin user

I created an admin user for the purposes of the assignment to demonstrate my proficiency with it.

<img width="1003" alt="Screenshot 2023-02-16 at 2 29 22 PM" src="https://user-images.githubusercontent.com/37819313/219480284-3a6a64d9-0660-4ff5-9a93-caac1b76b2fb.png">


## Generate AWS Credentials

I setup AWS Organizations so I could have separate OU for this bootcamp, and also created a user account for the bootcamp. I used the + suffix trick to create the account but still have it go to an existing email address that I already have instead of creating a whole new email address. I used the forgot password option to generate credentials for the account, I entered the accout email address in the root user field and selected forgot password.

<img width="1018" alt="Screenshot 2023-02-16 at 2 04 51 PM" src="https://user-images.githubusercontent.com/37819313/219480430-1cc4cae5-5574-482c-9cd9-a60fe11bc89f.png">


I also created an IAM user under this organization so I wouldn't be using the root user account for cli access, I generated credentials for the account

<img width="1003" alt="Screenshot 2023-02-16 at 2 29 22 PM" src="https://user-images.githubusercontent.com/37819313/219480460-4fbd9062-06cf-41f6-b829-b91fce5419c6.png">

<img width="609" alt="Screenshot 2023-02-16 at 2 53 37 PM" src="https://user-images.githubusercontent.com/37819313/219483494-6296d0df-0189-4d58-8740-24c75d0c7cec.png">

## Create a Budget

I have setup my budget for my AWS user account I have designated that I will be using for the bootcamp. For now I have setup $30 as my intial budget, not quite sure how much setting up everything at the end will cost but will adjust as needed.

<img width="1190" alt="Screenshot 2023-02-16 at 3 51 14 PM" src="https://user-images.githubusercontent.com/37819313/219484052-355f5199-e281-40ef-a462-daf02c1b2c7d.png">

## Napkin design

![20230217_160530](https://user-images.githubusercontent.com/37819313/219819089-9e60d85d-47ad-4964-9258-97cddb85a770.jpg)
