Library-Management-System-using-Python

Completed on 13th October, 2024

Created a Library Management System where users can borrow and return books. The system manages the availability of books and track which books are borrowed by which users.
Implemented inheritance by creating a subclass PremiumUser that inherits from User. Premium users can borrow up to 5 books at a time, while regular users can only borrow 3.
Used polymorphism by overriding the borrow_book() method in the PremiumUser class to allow the extra borrowing capacity.
Handled file input/output by saving the list of books and users to a file and reading them back in the beginning. This ensures that the library retains its state between executions.
