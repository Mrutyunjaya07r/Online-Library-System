# Online-Library-System

The Online Library System built using PHP and SQL is a web-based application designed to manage library resources efficiently. It allows users to search, borrow, and return books while enabling administrators to manage book inventories, track lending records, and maintain user accounts. The system provides features like book catalog management, user registration, borrowing history, and real-time availability updates. It streamlines library operations, offering a user-friendly interface for both members and librarians.

The Online Library System developed using PHP and SQL features a well-structured relational database to manage various library operations. The database typically includes the following core tables:

Users Table:

Stores user details like user_id, name, email, password, role (member/admin), and contact information.

Ensures secure authentication and role-based access.

Books Table:

Contains attributes such as book_id, title, author, genre, ISBN, publisher, publication_year, quantity, and availability_status.

Supports efficient book search and inventory tracking.

Borrowing Records Table:

Tracks book lending with fields like record_id, user_id, book_id, borrow_date, due_date, return_date, and status (borrowed/returned).

Helps manage overdue books and calculate fines if applicable.

Categories Table:

Stores book categories with fields like category_id and category_name.

Facilitates organizing books based on genres or subjects.

Reservations Table (optional):

Handles book reservations with fields like reservation_id, user_id, book_id, reservation_date, and status.

Allows users to reserve books currently on loan.
