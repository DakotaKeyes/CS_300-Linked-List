# CS_300-Linked-List
Linked List .cpp
Requirements & Rubric

The focus of these problems will be working with information extracted from a municipal government data feed containing bids submitted for auction of property. All materials for this assignment can be found in the Supporting Materials section below. The data set is provided in two comma-separated files:

eBid_Monthly_Sales.csv (larger set of 12,023 bids)
eBid_Monthly_Sales_Dec_2016.csv (smaller set of 76 bids)
This assignment is designed to explore linked lists, so you will implement a singly linked list to hold a collection of bids loaded from a CSV file. We provide a starter console program that uses a menu to enable testing of the sort logic you will complete. In this version, the following menu is presented when the program is run:

Menu:

Enter a Bid
Load Bids
Display All Bids
Find Bid
Remove Bid
Exit
Enter choice:

The LinkedList.cpp program is partially completed. It contains empty methods representing the programming interface used to interact with the linked list. You will need to add logic to the methods to implement the necessary behavior. Here is the public API for LinkedList.cpp that you have to complete:

public:

LinkedList();
virtual ~LinkedList();
void Append(Bid bid);
void Prepend(Bid bid);
void PrintList();
void Remove(string bidId);
Bid Search(string bidId);

Prompt
You will need to perform the following steps to complete this activity:

Setup: Begin by creating a new C++ project with a project type of "Hello World C++ Project".

Name the project “LinkedList”. Remember to pick the correct compiler in Toolchains and click Finish. This will create a simple LinkedList.cpp source file under the /src directory.

Download the starter program files and copy them to the project’s /src directory, replacing the existing auto-generated ones. Remember to right-click on the project in the Project Explorer pane on the left and Refresh the project so it adds all the new files to the src folder underneath.
Because this activity uses C++ 11 features, you may need to add the -std=c++11 compiler switch to the miscellaneous settings.


**Task 1: Internal structure for list entries, housekeeping variables. Create the structure, internal to the class, that will hold the bid entries. Consider what other variables are needed to help manage the list.

**Task 2: Initialize housekeeping variables. Remember to initialize the housekeeping variables in the constructor.

**Task 3: Implement append logic. Create code to append a bid to the end of the list.

**Task 4: Implement prepend logic. Create code to prepend a bid to the front of the list.

**Task 5: Implement print logic. Create code to print all the bid entries in the list to the console.

**Task 6: Implement remove logic. Create code to remove the requested bid using the bid ID passed in.

**Task 7: Implement search logic. Create code to search for the requested bid using the bid ID passed in. Return the bid structure if found or an empty bid structure if not found.
