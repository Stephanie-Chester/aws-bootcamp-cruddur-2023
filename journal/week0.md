# Week 0 — Billing and Architecture

# Homework/Tasks

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


## Create a Budget

I have setup my budget for my AWS user account I have designated that I will be using for the bootcamp. For now I have setup $30 as my intial budget, not quite sure how much setting up everything at the end will cost but will adjust as needed.


