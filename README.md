This Java program, Telephone Directory, is a console-based application designed to manage contact information. Here's a professional explanation of its functionality:

### *Purpose*
The program allows users to create, retrieve, update, and delete (CRUD operations) contacts in a telephone directory. It uses a list to store contacts and provides functionality to save and load data from a file.

---

### *Key Components*

1. **Data Structure (List<Contact>):
   - Contacts are stored in a dynamic list, making it easier to add, delete, or iterate over them.

2. **Contact Class**:
   - Each contact has three attributes: name, age, and number. This class represents a single contact entry.

3. *Features*:
   - *Create Contacts*: Allows users to enter and store multiple contacts.
   - *Save to File*: Saves all contacts in a text file (contacts.txt) with a simple comma-separated format.
   - *Load from File*: Reads the saved contacts from the file and populates the list at startup.
   - *Retrieve by Index*: Displays a specific contact based on its index in the list.
   - *Display Range*: Displays contacts within a specified range of indices.
   - *Display All Contacts*: Shows all stored contacts with their details.
   - *Delete Contact*: Removes a contact based on the name provided.

4. *User Interaction*:
   - A menu-driven interface is provided to interact with the application. The menu options are numbered, and the user inputs the corresponding number to perform an operation.

5. *Error Handling*:
   - Ensures valid inputs using try-catch blocks.
   - Prevents actions when no contacts are available.
   - Handles file I/O errors gracefully.

6. *File Operations*:
   - Data persistence is achieved through reading from and writing to a text file (contacts.txt).

---

### *Workflow*

1. *Application Start*:
   - The program attempts to load existing contacts from the file using loadFromFile(). If no file exists, it notifies the user.

2. *Main Menu*:
   - Displays options such as creating contacts, saving data, retrieving specific entries, and deleting contacts.

3. *Performing Actions*:
   - Based on user input, the corresponding method is called to perform the desired operation.

4. *Data Persistence*:
   - When new contacts are added, the user can save them to a file for future use. On subsequent runs, these contacts are reloaded.

5. *Exiting*:
   - The user can exit the application through the menu. All unsaved changes will not persist.

---

### *Code Highlights*
- *Dynamic Storage*: Uses ArrayList for scalability instead of a fixed-size array.
- *File Operations*: Ensures that contact data is not lost between application runs.
- *User-Friendly Prompts*: Provides clear messages and error handling for invalid inputs.

This program is a practical implementation of basic Java concepts, including:
- Object-Oriented Programming (OOP),
- File handling,
- Exception management,
- Collections framework, and
- Console-based user interaction.
