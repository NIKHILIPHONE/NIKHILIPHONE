NAME:NIKHIL THAKUR
COMPANY:CODTECH IT SOLUTIONS
ID:CT08DS10320
DOMAIN:PYTHON PROGRAMMING 
DURATION:NOVEMBER TO DECEMBER 2024
MENTOR:NEELA SANTHOSH KUMAR 
OVERVIEW OF THE PROJECT 
PROJECT--- developing a python program to manage library resources such as books,
magazines, and DVDs. The system should support functionalities like
adding new items to the library, checking out and returning items,
managing overdue fines, and searching for items by title, author, or
category

overview of the code

Overview
LibraryItem Class:

Purpose: Represents an item in the library (book, magazine, DVD).

Attributes:

item_code: A unique code for each item.

title: Title of the item.

author: Author of the item.

category: Category of the item (e.g., Fiction, Sci-Fi).

item_type: Type of the item (e.g., Book, Magazine, DVD).

is_checked_out: Boolean indicating if the item is checked out.

due_date: The due date for returning the checked-out item.

Library Class:

Purpose: Manages the collection of library items and provides functionalities to interact with them.

Attributes:

items: A list to store all library items.

overdue_fines_per_day: The fine charged per day for overdue items.

Methods:

add_item(title, author, category, item_type): Adds a new item to the library with a unique item code.

search_items(**kwargs): Searches for items based on given attributes (e.g., title, author, category).

check_out_item(item_code): Checks out an item based on its unique code, setting its due date.

return_item(item_code): Returns an item based on its unique code, calculates and displays overdue fines if applicable.
![Screenshot 2024-11-22 180142](https://github.com/user-attachments/assets/c1b697af-e5ae-4336-8732-e384dd0350ad)
![Screenshot 2024-11-22 180203](https://github.com/user-attachments/assets/814c137b-c2fe-4d46-a141-392960e3ba87)
