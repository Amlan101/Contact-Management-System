##Contact-Management-System##

-> The code base consists of 4 files.

1. main.c:

Purpose: This is the main program file that provides the user interface and controls the overall flow of the contact management system.

Working: It initializes variables, displays the main menu, and enters a loop where the user can choose various options. It interacts with the user to add, search, update, delete, or display contacts based on their choice. The program runs until the user chooses to exit.

2. main.h:

Purpose: This header file defines data types, constants, global variables, and function prototypes that are shared among different parts of your program.

Working: It ensures consistency and clarity in data types and function definitions across the entire program. It's included in other source files to make these definitions available.

3. std_types.h:

Purpose: This header file defines standard types for data portability and consistency.

Working: It defines standard types like uint8, uint16, etc., which are used in your program. By including this file, you ensure that the same types are used consistently across your code.

4. functions.c:

Purpose: This source file contains the core functions that manipulate the contact list, including creating, adding, searching, updating, deleting, displaying contacts, and handling errors.

Working: It implements the functions for adding, searching, updating, and deleting contacts in the linked list, as well as for displaying contacts and handling errors. These functions are called from main.c based on the user's menu choices.
