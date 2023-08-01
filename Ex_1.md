Make sure for this exercise the region selected is N Virginia or us-east-1.

Exercise 1: Creating an AWS Account
In this scenario, you work for a company that currently has no presence in the cloud. You have been tasked with creating the company’s employee directory application in AWS.

In this exercise, you will be creating and confirming a new AWS account. You will then log in to that account and do basic management tasks, such as choosing a support plan and setting up some account alerts.

Task 1: Signing up for an account
In this task, you will start the process of signing up for an AWS account.

Visit the Amazon Web Services home page.

Choose Create an AWS Account.

Note: If you signed in to AWS recently, choose Sign in to the Console. If Create a new AWS account isn’t available, first choose Sign in to a different account, and then choose Create a new AWS account.

Enter your account information, and then choose Continue.

Be sure that you enter your account information correctly, especially your email address. If you enter your email address incorrectly, you won’t be able access your account.

Choose Personal or Professional.

Note: These two account types are identical in functionality. You can choose personal for your personal projects. Choose professional for use within your company, an educational institution, or an organization.

Enter your company or personal information.

Read the AWS Customer Agreement, and then select the box.

Click Create Account and Continue.

Task 2: Adding a payment method
In this task, you will add a payment method to your account.

On the Payment Information page, add a payment method by entering the requested information about your payment method.

Choose Verify and Add.

Important: You can’t proceed with the signup process until you add a valid payment method.

Task 3: Verifying your identity
In this task, you will verify your identity for the account.

On the Identity Verification page, choose your country or region code from the list.

Enter a phone number where you can be reached in the next few minutes.

Enter the code that’s displayed in the CAPTCHA.

When you’re ready to receive a call or Short Message Service (SMS) text message, choose Contact me/Send SMS.

In a few moments, you should be contacted through the verification system.

Enter the verification code that you received and choose Verify Code.

Choose Continue.

Task 4: Choosing an AWS Support plan
In this task, you will select an AWS Support plan for your account.

On the Select a Support Plan page, select the Basic Plan that’s included in the AWS Free Tier.

Sign in to the AWS Management Console.

Task 5: Setting up an AWS Free Tier alert and custom billing alert
In this task, you will set up an alert for your AWS Free Tier usage. You will also set up a billing alert in Amazon CloudWatch.

First, you will create a usage alert.

In the search box, enter Billing and open it.

In the navigation bar, select Billing preferences.

Under the Alert preferences section choose Edit.

Verify Receive AWS Free Tier alerts is checked. If you would like an additional email address to receive the alerts. Enter that email address. The accounts root user email address is already set up to receive free tier alerts.

Choose Update if any changes were made.

You will now create a billing alert in CloudWatch.

In the services search box, enter CloudWatch and open the service.

If necessary, change the Region in the upper-right area of the console to US East (N. Virginia).

Billing metric data is stored in this Region, and this data represents worldwide charges.

In the navigation pane, choose Alarms and Billing, then choose Create alarm.

In the Metric box. It will have populated Namespace:AWS/Billing. Metric name:EstimatedCharges.

Under Conditions, choose Static.

For Whenever EstimatedCharges is, choose Greater.

For than, enter the monthly amount that must be exceeded to start the alarm.

The number you enter should be an amount that you’re comfortable with, such as 10.

Choose Next.

You will now configure notifications for the alarm by setting up and subscribing to an Amazon Simple Notification Service (Amazon SNS) topic. Amazon SNS is a service that publishes messages to a topic, which delivers the message to all topic subscribers.

For Alarm State Trigger, select In alarm.

For Select an SNS Topic, choose Create new topic.

Enter a topic name.

The name must be unique.

Enter the email address where you want to receive the notification.

Note: You will get an email in your inbox that asks you to confirm your subscription to this topic. By confirming, you should get notifications when your estimated billing charges go over your threshold.

Choose Create topic and then choose Next.

Enter an alarm name and description.

The name must contain only ASCII characters.

Choose Next. Finally choose Create alarm.

## Account Created Chalk and Feather

## Free Tier

## Payment Details added
