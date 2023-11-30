# Homework: Advanced JDBC in Java - CRUD Application

## Introduction
In this homework, you will apply the concepts learned in Lecture #17 to create a simple CRUD (Create, Read, Update, Delete) application using Java Database Connectivity (JDBC). Your task is to build an application that interacts with a database, performing basic data manipulation and implementing advanced JDBC features.

## Task Requirements and Expected Outcomes

### Basic Requirements
- **Database Connectivity:** Create a Java application that connects to a database of your choice using JDBC.
- **CRUD Operations:**
    - **Create:** Insert new records into the database.
    - **Read:** Retrieve and display records from the database.
    - **Update:** Modify existing records in the database.
    - **Delete:** Remove records from the database.
- **Error Handling:** Implement appropriate error handling for all database operations.

### Advanced Features (Optional but Encouraged)
- **Transaction Management:** Implement transaction management to ensure data integrity.
- **Batch Processing:** Utilize batch processing for efficient handling of bulk data operations.
- **Connection Pooling:** Use connection pooling to manage database connections efficiently.

### Documentation
- **Code Comments:** Your code should be well-commented, explaining your implementation choices.
- **Report:** Write a brief report detailing your application's design, including any challenges you faced and how you addressed them.

### Example Structure
```java
public class CRUDApplication {
    public static void main(String[] args) {
        // Establish database connection
        // Implement methods for each CRUD operation
        // Close the connection
    }
}
