# Primekeeper Backend Test

Points to consider:

* This is an open-book test. You may use any reference, including the Internet.

These frameworks/tools/languages are mandatory for this test. You may add additional framework/languages if you require them:

* Spring Boot
* Java / Kotlin
* MySQL / MariaDB
* Gradle
* Any database versioning/migration tool

Scenario:

The client wants to create a site with two type of users: customers and merchants.

A customer may send money to any merchant or customer. The merchants may also do the same: they may send money to any customer or merchant.

With this in mind:
1. Create a registration API that requires the user to send in their username, password, and their account type for registration. Each user gets RM 100 upon registration.
2. Create a login API that logs the user into the system.
3. Create an API that allows a user to send money to another user.
4. **Optional:** The client's requirements have changed, merchants may not send money to other merchants.
5. **Optional:** They've added yet another requirement. Now, the users may not send more than RM 10 per transaction.

Lastly:

1. Make sure to have instructions in a `README.md` file on how to run the project.
2. Send us a link to your github repo of the test to clayton@primekeeper.my and michael@primekeeper.my.