# COMSC Animal Expert System
DVC COMSC200 Animal Expert System class/group project

The aim of this project is to create a simple expert system, whose purpose is the identification of animals.  This system will provide 2 user personas, the expert user and the general user.  The system will enable a general user to react to system suggestions as to an animal's identification.  It will capture the general user's reaction and "learn" from these reactions in order to build a broader knowledge base for the identification of animals.  The expert user will be able to seed animal information and review/edit the information the system collects from general users.  Ultimately, the system should be able to guide a general user to the correct identity of a growing selection of animals, as vetted by the expert user.

This system will likely be implemented using a binary tree data structure.  This system will use the principles of least privilege, both through limiting access to root data members, as well as having tiered access identifiers during runtime which allow only expert users to input data and train the system. We will use inheritance to generate separate classes that will handle the scope of taxonomic orders, relying on polymorphism to simplify the program structure, and increase the flexibility and functionality of the root code.

Time permitting, we propose 2 stretch goals to accompany our implementation: 1) the use of a storage model other than the file system, such as an online object store, and 2) the use of a gang of four pattern in our design.  We believe we can use an abstract storage class with a concrete file based implementation to initially build and test our concept.  The abstraction will allow us to implement and use a different storage model later, such as an object store with little to no change through the rest of the program.
