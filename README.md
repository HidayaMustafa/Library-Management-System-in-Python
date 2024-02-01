# Linux_project_2
**Python project **
----------------------------------------
**Problem Overview:**  
This project involves creating a library management system (LMS) designed to assist libraries in effectively 
managing their collections. The LMS will provide the following functionalities: 
1. Adding new books to the library collection 
2. Searching for books within the library collection 
3. Editing the information of existing books 
4. Archiving books 
5. Removing books from the LMS 
6. Generating reports about the books available in the LMS 
7. Exit



**The specifications of each option in the LMS are as follows:**


**1. Adding new books to the library collection** 

1.1 The user will enter the name of the file containing the information about the new books after choosing this option. The LMS ought to make sure the file is available and accessible.  
  
1.2 While the other characteristics are optional (may be provided for some books but not for others), the Title, Publisher, and ISBNs must be provided for each book.
    
1.3 The LMS should display the book information on the screen, book after book, as it loads the book's information from the file.
   
1.4 The ISBNs on the LMS should be used to distinguish between different books. It is necessary to include a "number of copies" argument with the book information in the LMS. The "number of copies" must be set to 1 for each new book.
   
1.5 If any of the books that are being loaded from the book's information file already have a record in the LMS, the LMS should prompt the user to either replace the existing record or add a new copy of the book. The "number of copies" would be increased if the user wanted to add another copy of the book. 



**2. Searching for books within the library collection** 
The LMS should enable users to search for any registered book using any of the parameters (including the optional ones) and print the results on the screen. The user should be able also to store the result in a text file. 



**3. Editing the information of existing books**
When selecting this option, the LMS should prompt the user to provide the file's name or ISBN number before letting them update the file's details. Before saving the changed data, the LMS should ask the user for confirmation.



**4. Archiving books**
4.1 The LMS should allow the users to move some of the books that are rarely used to archive. To do this, the user will enter the name of the ISBNs of the book after selecting this option, the LMS should ask the user for confirmation. 

4.2 The user should be allowed to choose how many copies of a book should be archived if there are multiple copies of it available in the LMS. 


**5. Removing books from the LMS**
By selecting this option, the user can delete books from the LMS. Only archived books can be deleted from the LMS. Also, the LMS should ask the user for confirmation.


**7. Generating reports about the books available in the LMS.**
When this option is used, a report that includes the following will be printed on screen:

7.1. how many books are in the LMS.

7.2. how many different books are offered in the LMS.

7.3. the number of books archived in the LMS.

7.4. how many books in the LMS are newer than a particular year.

7.5. Book distribution by the publisher.

7.6. Books distribution by year. 


**7. Exit**
The LMS will be terminated upon execution of this command, and all books' data must be saved to an LMS file. The next time the LMS is launched, this file must be loaded. 



