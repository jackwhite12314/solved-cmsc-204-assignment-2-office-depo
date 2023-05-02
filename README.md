Download Link: https://assignmentchef.com/product/solved-cmsc-204-assignment-2-office-depo
<br>
<p class="ui header product-top-header" title=" CMSC 204 Assignment #2 Office Depo Solution"> Office Depo an office supply retailing company donates its surpluses to colleges at the end of each year. Volunteers will help deliver packages of supplies to representative of colleges (Recipient of supplies). Write an application to simulate delivering packages from the container of packages by the volunteers to recipients.

Concepts tested:

Generic Queue, co

Generic Stack,

Exception handling,

Data Elements

Volunteer- Holds the relevant information for a Volunteer:  name

DonationPackage- Holds the information of the package to be donated: description, weight

Recipient- Holds the information of the recipients: name

Data Structures

1.      Create a generic queue class called MyQueue to implement the queue of volunteers and recipients line.  MyQueue will implement the QueueInterface given you.

2.      Create a generic stack class called MyStack to place the DonationPackage on a Container.  MyStack will implement the Stack Interface given you.

There will be a VolunteerLine class, a RecipientLine Class and a Container class   The VolunteerLine class will implement the VolunteerLineInterface , the RecipientLine class will implement the RecipientLineInterface  class and the Container class will implement the ContainerInterface class

Limit the size of each collection to 5.

Data ManagerThe DonationManager class  will manage adding a new package to the container, a new volunteer to the volunteer queue line , a new recipient to the recipient queue and donating  package by the volunteer to the recipient.  DonationManager   will implement the interface DonationManager Interface.

You may add additional methods and attributes to your classes

GUI Driver

1.      Initially there is no package on the container, any volunteers and recipients on the queue.

2.      Allow the user to load new package to the container and add new volunteers to volunteer’s line and new recipient to recipients’ line.

3.      Do not allow packages heavier than 20lbs to be added to the container.

4.      Allow the user to simulate process of donating the package from the container by volunteer on the queue to the recipient on the queue. When a volunteer helps donating the package to the recipient, he/she will be back to the queue of volunteers to continue the process of donation.

5.      Provide three exception classes:

a.       RecipientException:  If the user attempts to add new Recipient and the recipient line is full (5 recipients).

b.      VolunteerException – If the user attempts to add new Volunteer and the volunteer line is full (5 volunteers).

c.       ContainerException – If the user attempts to add new Donation Package and the Container line is full (5 packages).

Examples:

At startup

After selecting “Stack New Package”

Pen(first) and Books (second).

After adding new Volunteers John (first),          after adding new Recipient MC,

Nicole (second)                                                   Maryland

After selecting Donate Package                                                  After selecting Donate Package Second time

First Time

After selecting Donate Package Third time

If the user tries to add a new volunteer:

5/5 - (4 votes)