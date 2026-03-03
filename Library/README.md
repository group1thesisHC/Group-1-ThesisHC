==============================================
LIBRARY MANAGEMENT SYSTEM
SE102: SOFTWARE ENGINEERING 2
==============================================

PROJECT TITLE:
Developing a Library Management System

STUDENT INFORMATION:
Student Names:
- Jay Ann B. Bacanto
- Iniego Angelo L. Condez
- Endrian B. Mantac
- Jessa Mae A. Billano

Course / Section:
BSCS 3-C

Programming Language:
Python 3

Database:
SQLite

Testing Framework:
UnitTest and PyTest

Version Control:
Git and GitHub

==============================================
PROJECT DESCRIPTION
==============================================

The Library Management System is a software-based solution designed to manage library resources efficiently. 
It replaces manual paper-based processes with an automated system that tracks books, users, borrowing, returns, and fines.

The system improves:
- Accuracy of records
- Efficiency in managing books
- Monitoring of borrowed and returned items
- Report generation for administrators

==============================================
PROBLEM STATEMENT
==============================================

Manual library systems are time-consuming, inefficient, and prone to errors. 
Tracking available books, monitoring borrowing and returns, and maintaining accurate records 
become difficult using traditional paper-based methods.

This project answers the research question:

"How can a software-based library management system efficiently manage book inventory, 
borrowing, and return processes to improve accuracy and operations?"

==============================================
KEY FEATURES
==============================================

1. Book Management
   - Add new books
   - Update book details
   - Delete books
   - View available books

2. User Management
   - Register library users
   - Manage user information

3. Borrowing and Returning
   - Borrow books
   - Return books
   - Automatic availability updates
   - Prevent double borrowing

4. Due Dates and Fines
   - Automatic due date calculation
   - Identify overdue books
   - Fine calculation for late returns

5. Reports
   - Available books report
   - Borrowed books report
   - Overdue items report

==============================================
PROJECT STRUCTURE
==============================================

library-management-system/

main.py
config.py

database/
    library.db
    db_setup.py

core/
    book.py
    user.py
    transaction.py

tests/
    test_books.py
    test_users.py
    test_transactions.py

.gitignore
README.txt
requirements.txt

==============================================
SYSTEM DESIGN
==============================================

The system follows a modular design approach:

- Book Module: Handles book records and inventory.
- User Module: Manages user registration and details.
- Transaction Module: Controls borrowing and returning.
- Database Module: Manages SQLite database operations.

This modular structure improves:
- Maintainability
- Scalability
- Independent testing of components

==============================================
DEVELOPMENT ENVIRONMENT
==============================================

Operating System: Windows / macOS / Linux
IDE: Visual Studio Code
Programming Language: Python 3
Database: SQLite
Version Control: Git and GitHub

==============================================
TESTING STRATEGY
==============================================

Testing includes:

1. Black-box Testing
   - Valid borrow/return requests
   - Invalid inputs
   - Borrow unavailable book

2. White-box Testing
   - Availability flag updates
   - Fine calculation logic
   - Database record updates

Test Coverage:
- Total Tests: 8
- Passed: 8
- Coverage: 92%

==============================================
GIT WORKFLOW
==============================================

- Initialized Git repository
- Created .gitignore file
- Used feature branches:
    feature-core
    feature-tests
- Merged branches into main after testing
- Regular meaningful commits

==============================================
CHALLENGES ENCOUNTERED
==============================================

- Handling invalid user input
- Understanding PyTest fixtures
- Ensuring correct fine calculation logic

==============================================
LESSONS LEARNED
==============================================

- Writing tests early reduces bugs
- Version control ensures safe integration
- Modular development simplifies maintenance
- Incremental development improves stability

==============================================
CONCLUSION
==============================================

The Library Management System demonstrates how modular subsystem design,
combined with version control and test-driven development,
results in a reliable and efficient software solution.

The system improves library operations by automating
inventory management, borrowing, returning, and reporting processes.

==============================================
END OF README
==============================================