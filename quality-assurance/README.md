# Quality Assurance Test

The purpose of this test is to gauge the your thought-process and creativity in testing various scenarios. 

You are given **1 hour** to complete the test on-premises.

Assume you are a quality assurance tester reading an actual brief for the task below.


# Project Brief: Implementation of 'Secret Phase' feature in Version 2

Note: Version 1 of the App will no longer work after the launch of Version 2. It is essentially a dead app. All Users will need to update their app in order to Sign in.

Take note of the two below differences as ‘Security Phrase’ is closed linked to MyKad Scanning:

*	**Version 1** – During registration, it was mandatory for Users to scan in their MyKad to successfully create an account.
*	**Version 2** – During registration, scanning of MyKad is not mandatory. Users are allowed to explore the app prior to deciding to scan in MyKad.

## Purpose

This new ‘Secret Phrase’ will be required during the Account Recovery process. 

Recovery Process: 
1. User forgets password.
2. Tap ‘Forgot Password’. 
3. System will require User to enter his previously set Secret Phrase. 
4. If correct, User can then proceed to create a new Password and Confirm Password and Save. Password successfully changed.
5. User can Sign in with new Password. 

## Requirements:

#### Existing Users of Version 1 who have updated their app to Version 2

1. All existing Users from Version 1 have their MyKad stored in the App. Force all existing Users (system to track by registration date prior to 1st Jan 2018) to create Security Phrase when they first Sign in to Version 2. They cannot proceed to successfully sign in if this is not done.

2.	Ensure Security Phrase is not required during Account Recovery Process for Users who do not have a Security Phrase. For instance, Users from Version 1 who upgraded to Version 2 and have forgotten their password. They will need to do ‘Forgot Password’ before they can sign in for the first time.

#### New Users who register in Version 2 of the app.

1. Users can register and navigate the app without scanning in their MyKad. (This differs from Version 1 where Users had to scan in their MyKad during the registration process).

2. At any time after registration, User can choose to add their Secret Phrase from the ‘Settings’ menu prior to scanning in the MyKad if they would like to quickly secure their account. 

3. It is mandatory for User to scan in their MyKad if they want to set up a payment account to make cashless payments.
	* When User scans in MyKad,  the System will show the ‘Set Secret Phrase’ screen. User must create their Secret Phrase at this point. The MyKad cannot be saved until Secret Phrase is successfully saved. 
4. Ensure Secret Phrase is not required during Account Recovery Process for Users who do not have a Security Phrase (i.e. Users who have not yet scanned in their MyKad/Passport into the app). 

## Question

Imagine you have been given log in credentials of **Test User A** who is an existing user from **App Version 1** and login credentials of **Test User B**, a new user who downloaded and successfully registered in **App Version 2**. 

List down as many important Test Case scenarios you would use to test this feature before it is released. Be creative! You have one hour to complete this assessment. Good luck!
