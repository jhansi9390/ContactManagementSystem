# ContactManagementSystem
A simple Java Contact Management System that allows users to add, view, update, and delete contacts via a console menu. Contacts can be updated by searching with name or phone number. Uses ArrayList for storage and switch-case for menu operations. Easy to compile and run.

Overview
The Contact Management System is a console-based Java application that allows users to store, view, update, and delete contacts. Each contact consists of three main fields: Name, Phone Number, and Email. The program uses object-oriented principles with a Contact class to model contacts and an ArrayList to dynamically manage the list of contacts. The user interacts with the system through a menu controlled by a switch statement.

Working Process of the Contact Management System
The Contact Management System is a console-based program that helps users manage their contacts easily by adding, viewing, updating, and deleting contact information. Each contact includes a name, phone number, and email address.

Starting the Program and User Interaction
When the program starts, it presents a menu with several options for the user to choose from. The user interacts with the program by entering the number corresponding to their desired action, such as adding a new contact or viewing all saved contacts. This menu-driven approach repeats continuously until the user chooses to exit the program.

Adding Contacts
To add a new contact, the user selects the “Add Contact” option. The program then prompts the user to input the contact's name, phone number, and email address. These details are collected and stored as a single contact entity in an internal list, allowing the program to manage multiple contacts efficiently.

Viewing All Contacts
Choosing to view contacts displays a list of all the saved contacts. Each contact is shown with their associated details: name, phone number, and email. This gives the user a quick overview of all contacts currently stored in the system.

Updating a Contact
The update functionality is designed to be flexible and user-friendly. Instead of requiring the user to remember the exact index or position of the contact in the list, the program allows searching by either the contact’s name or phone number.
The user enters a name or phone number.
The system searches through the stored contacts to find a match.
If a matching contact is found, its details are displayed to the user.
The user is then prompted to enter new information for the name, phone number, and email.
If the user wants to keep any existing information, they can simply leave the input blank, and the program will retain the original details.
After entering the changes, the program updates the contact’s information accordingly and confirms the update.
If no matching contact is found, the program informs the user that the search was unsuccessful.

Deleting a Contact
Deleting a contact requires the user to select which contact they want to remove. The program first lists all saved contacts with assigned numbers. The user then inputs the number corresponding to the contact they want to delete.
The system checks that the input is valid.
If valid, the selected contact is removed from the list.
The program confirms the deletion.
If the input is invalid (for example, a number outside the list range), the program notifies the user and does not perform any deletion.

Loop and Exit
After completing any action (add, view, update, delete), the program returns to the main menu, allowing the user to perform additional operations. This loop continues until the user chooses the exit option, at which point the program terminates gracefully with a farewell message.

Behind the Scenes
Data Storage: All contacts are stored dynamically in a list structure, allowing easy addition and removal.
User Input Handling: The program uses input prompts to get information from the user and handles invalid or unexpected inputs carefully.
Search Mechanism: When updating contacts, the program performs a search to find the first contact matching either the name (ignoring case differences) or phone number.
Input Validation: Throughout the program, inputs are validated to prevent errors, such as updating or deleting contacts that do not exist.



