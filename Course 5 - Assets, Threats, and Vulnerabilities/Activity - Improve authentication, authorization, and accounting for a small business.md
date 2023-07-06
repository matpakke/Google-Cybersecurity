# Activity Overview

In this activity, you will assess the access controls used by a business. You’ll analyze their current process, identify issues, and make recommendations to improve their security practices.

Previously, you learned that access controls are security controls that manage access, authorization, and accountability of information. Authentication controls are used to verify who someone is, whereas authorization controls are used to grant a user permissions and set limits on the things they’re allowed to do. When done well, access controls are the key to decreasing the likelihood of a security risk.

Be sure to complete this activity before moving on. The next course item will provide you with a completed exemplar to compare to your own work.

## Scenario

Review the scenario below. Then complete the step-by-step instructions.

You’re the first cybersecurity professional hired by a growing business.

Recently, a deposit was made from the business to an unknown bank account. The finance manager says they didn’t make a mistake. Fortunately, they were able to stop the payment. The owner has asked you to investigate what happened to prevent any future incidents.

To do this, you’ll need to do some accounting on the incident to better understand what happened. First, you will review the access log of the incident. Next, you will take notes that can help you identify a possible threat actor. Then, you will spot issues with the access controls that were exploited by the user. Finally, you will recommend mitigations that can improve the business' access controls and reduce the likelihood that this incident reoccurs.

## Step-By-Step Instructions

Follow the instructions and answer the question below to complete the activity. Then, go to the next course item to compare your work to a completed exemplar.

### Step 1: Access the template

To use the template for this course item, click the link below and select Use Template. 

Link to template:
[Access control worksheet](https://docs.google.com/document/d/1Uhz4yTKO_tB5i1SS8OX9VTrc8pX6A9xE6__OwOAHUhs/template/preview?resourcekey=0-SzdtvOMbRvB1b-VD6d0Sog#heading=h.7nlk2ynsm6vx)



### Step 2: Access supporting materials
The following supporting materials will help you complete this activity. Keep them open as you proceed to the next steps. 

To use the supporting materials for this course item, click the link below and select “Use Template.”

Note: The spreadsheet for this supporting resource has two tabs.

Link to template: 
[Accounting exercise](https://docs.google.com/spreadsheets/d/1-WuEnbCzejBOR5833otgbkeolkxjvhG5qDTKMuKkyYo/template/preview?resourcekey=0-5JZRiXznziLl1teGdlyMEg#gid=253432744)


### Step 3: Review the event log of this payroll incident
Event logs contain information related to the operation and usage of a system. They can be utilized to identify suspicious activity, detect vulnerabilities, and track users.

Find the Event log tab of the Accounting exercise spreadsheet. Carefully review the event log of this incident to start your investigation. Notice the Event Type, Date, Time, and IP Address of the user in the log details.

Make 1-2 notes of information that you learned about the user from reviewing the Event log details. Add your notes to the Notes column of the access control worksheet.

### Step 4: Identify access control issues that led to the incident
Log details tell you a lot about a specific moment in time. You can find other useful details about an event by cross referencing that information with other sources.

This business has a range of different employees. They all currently manage company resources using a shared cloud drive.

Find the Employee directory tab of the Accounting exercise spreadsheet. Compare the information found in the Employee directory tab with the information in the Event log tab. Notice any similarities between the details in the Event log and the details in the Employee directory.

Then, list 1-2 issues that you discover with how the business handles employee access in the Issues column of the Access control worksheet.

### Step 5: Recommend mitigations that can prevent a future breach
You’ve completed your accounting of the strange payment and discovered flaws with how the business handles their information.

Find the Recommendation(s) column of the Access control worksheet. Make at least 2 recommendations of mitigations the business can implement to prevent incidents like this in the future.

For example, one recommendation might be to have procedures in place to revoke access to files when an employee is no longer with the company.

## What to Include in Your Response

Be sure to include the following elements in your completed activity: 

- 1-2 notes about the user

- 1-2 access control issues

- 2 recommendations for access control mitigations

# Activity Exemplar: Improve authentication and authorization for a small business
Here is a completed exemplar along with an explanation of how the exemplar fulfills the expectations for the activity. 

Completed Exemplar

To review the exemplar for this course item, click the link below and select Use Template. 

Link to exemplar: 
[Access control worksheet exemplar](https://docs.google.com/document/d/1_jyynRjMBkeKW70f3P9EV9BAi7Wd1eoNYu01OyLtBkw/template/preview)

## Assessment of Exemplar

Compare the exemplar to your completed asset inventory. Review your work using each of the criteria in the exemplar. What did you do well? Where can you improve? Use your answers to these questions to guide you as you continue to progress through the course. 

Note: The exemplar represents one possible way to complete the activity. Yours will likely differ in certain ways. What’s important is that your review of the security incident considers effective access controls that can be implemented and how a lack of controls can put information at risk.


Let's review the details of the completed access control worksheet:

### Note(s) about the user:

- The event took place on 10/03/23.

- The user is Legal/Administrator.

- The IP address of the computer used to login is 152.207.255.255.

Event logs can often help you identify the who, what, and why of a security incident.

### Access control issue(s):

- Robert Taylor, Jr. is not an admin.

- His contract ended in 2019, but his account accessed payroll systems in 2023.

Oftentimes, incidents like this occur because systems are misconfigured or misused. That is the case with how this business is sharing information among its employees.

### Recommendations:

- User accounts should expire after 30 days.

- Contractors should have limited access to business resources.

- Enable multi-factor authentication (MFA).

It appears as though a former employee is potentially the threat actor. However, it's possible that they were not the person responsible for this security incident.

It is common for people to reuse login credentials across many services. And if those credentials are compromised on one platform then an attacker can use them to gain access to others. In this case, implementing access controls, like password policies, limited file permissions, and MFA can protect the business from incidents like this.


### Key Takeaways
This activity highlights how easy it can be to lose track of users, which  can leave a business open to unnecessary risk if effective access controls are not in place. The activity also demonstrates the risk of operating a business with open, shared access to resources. Setting boundaries around who can access information and what they are allowed to do should be the starting point of any security plan.