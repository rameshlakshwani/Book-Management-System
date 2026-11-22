📚 Book Management System

A web-based Book Management System developed using Java, Spring Boot, MongoDB, and Gradle. This application helps manage book information through a simple and user-friendly interface.

🚀 Project Overview

The Book Management System allows users to add new books, search for books using their Book ID, and view the available book details.

The application uses MongoDB to store and retrieve book information.

✨ Features

- Add Book: Add new books with their details.
- Search Book: Search for a book using its Book ID.
- View Book Information: Display the available book records.
- MongoDB Integration: Store and retrieve book data from MongoDB.
- User-Friendly Interface: Simple interface for managing book information.

🛠️ Technologies Used

- Programming Language: Java
- Backend Framework: Spring Boot
- Database: MongoDB
- Build Tool: Gradle
- IDE: Eclipse IDE
- Version Control: Git and GitHub

📋 Book Details

The application manages the following information:

- Book ID
- Book Title
- Author Name
- Publisher
- Publication Year
- Price
- Quantity
- Language

📸 Application Screenshots

1. Add Book Page

"Add Book" (screenshots/add-book.png)

2. Search Book Page

"Search Book" (screenshots/search-book.png)

3. Book Information Page

"Book Information" (screenshots/book-info.png)

4. MongoDB Database

"MongoDB Database" (screenshots/mongodb-records.png)

⚙️ How to Run the Project

Prerequisites

- Java JDK
- Eclipse IDE
- MongoDB Server
- Git

Steps

1. Clone the repository:
   
   git clone https://github.com/rameshlakshwani/Book-Management-System.git

2. Open the project in Eclipse IDE as a Gradle project.

3. Make sure MongoDB is running on your system.

4. Configure the MongoDB connection in "application.properties":
   
   spring.data.mongodb.host=localhost
spring.data.mongodb.port=27017
spring.data.mongodb.database=bookdb

5. Run the Spring Boot application.

6. Open your browser and visit:
   
   "http://localhost:8081"

🗄️ Database Information

- Database Name: bookdb
- Collection Name: bookdata

👩‍💻 Developer

Lakshwani Ramesh

- GitHub: "rameshlakshwani" (https://github.com/rameshlakshwani)

---

⭐ If you find this project useful, feel free to explore the repository!
