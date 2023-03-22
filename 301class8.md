# Computer Network | AAA (Authentication, Authorization and Accounting)

* Explain each of the three A’s as you would to a non-technical family member. Use an analogy or a story.

    - Authentication: this is the process of verifying ones identity to access the network.  Is is like showing DOD ID before entering a military base. 

    - Authorization:This is the process of determining whether a user or device has the right to access a specific resource on a network after they have been authenticated.  Like pulling on a military base and having access to only specific buildings. 

    - Accountnig: This is the process of tracking and recording the usage of network resources by users or devices.  This is like being tracked everytime you use your card to enter or exit a facility.   

* What should the administrator do if the ACS server fails to authenticate a user during AAA implementation?

    - The administrator should mention using the local database of the device as a backup, in the method list, to implement AAA.

* What is the role of the NAS in the AAA implementation using an ACS server? Use a diagram.

    +----------------+            +----------------+           +----------------+
|                | 1. Request |                | 2. Send    |                |
|   User Device  |---------->|      NAS       |---------->|    ACS Server  |
|                |            |                | Request   |                |
+----------------+            +----------------+           +----------------+