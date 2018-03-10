# UNSWbook
UNSWbook is a simple version of social media which contains four modules as below.
1. User Profile.
2. Friend and Search:
    1. Friend: Friending someone is the act of sending another user a friend request on UNSWBook.
    2. Search: It enables the users to search for all the users in the UNSWBook and send them friend request.
3. Wall and Like:
    1. Wall: It allows the posting of messages for the user to see while displaying the time and date the message was written.
    2. Like: It enables users to easily interact with the posted messages.
4. Admin Functionality.


There are more details about these four modules.
1. User Registration
A user visits a profile page and enters the following details: a username, a password, an email address, and personal details (e.g. Name, Gender, DoB, Photo, etc).
On submitting this information, the system sends an email containing a confirmation URL to the supplied address.
The user reads the email, goes to the confirmation URL; the system confirms the registration.
Every detail other than the username can be changed at any time by the user.
2. Search for users and add them as friends
User A logs into his/her account.
User A can search for the users registered in UNSWBook. You should think about a basic (only search ny name) and an advanced search (search by Gender, DoB, etc.).
User can select a user and see his/her details. User can send a friend request.
The user clicks a button to send friendship request to User B. On submitting this information, the system sends an email containing a confirmation URL to the supplied address.
User B reads the email and accept the request. A notification (on UNSWBook) will be send to User A tell him that User B accepted the friends request.
Note: You have to ensure to implement the system such that it will enable multiple users use the system simultaneously.
3. Wall and Like
This functionality works as follows:
 User A login to the system.
 User A should be able to post a message (include text, URL, image, etc).
 All the users who are the friend of User A, should be able to see this message (include content, date and time the message posted) on    the user's UNSWBook Wall. The wall can be as simple as a list group (EXAMPLE).
 The user should be able to like/unlike a post. A notification (on UNSWBook) will be send to User A tell him that User B liked the posted message.
4. Admin Functionality
The admin is a special account in the system which can only be accessed via a separate page (that is, not the usual user login page). The admin has the following functions:
 Ban a user from the site.
 Monitor customer activities:
 The admin should be able to search for and select a user.
 The admin should be able to see the user activity report. This report includes a timeline from the time the user joined the UNSWBook     Website, Added Friends, Posted Messages, etc. To achieve this you will need to trace the user activities and store them in a table(s).
