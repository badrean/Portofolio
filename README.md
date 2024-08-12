# Portofolio
Welcome to my portfolio! Below, you'll find a collection of my pet projects showcasing different aspects of my software development skills. Each project demonstrates my proficiency in different areas of programming.

## Projects

### 1. [Simple Banking Application](https://github.com/badrean/SimpleBankingApplication)
A console-based banking application implemented in Java that demonstrates core concepts of object-oriented programming and database interaction.

#### Key Features:
* User and admin roles with distinct functionalities.
* User account management and transaction handling.
* Interaction with a MySQL database to store and retrieve user and account information.

#### What I Learned:
* **Object-Oriented Programming:** Applied principles like encapsulation, inheritance, and polymorphism to design a modular application.
* **Database Interaction:** Implemented CRUD operations with MySQL, handling data persistence and retrieval.
* **Design Considerations:** Recognized that a client-server architecture would be more suitable for such applications but opted for a simpler console-based design for this project.

### 2. [Group Chat Application](https://github.com/badrean/GroupChatApplication)
A terminal-based group chat application written in Java using network sockets. It enables multiple users to chat in real-time.

#### Key Features:
* User registration and real-time message broadcasting.
* Commands for viewing online users and sending private messages.
* Custom exception handling to manage server downtime.

#### What I Learned:
* **Sockets and Network Communication:** Implemented client-server communication using Java’s ServerSocket class for real-time messaging.
* **Multithreading:** Managed multiple client connections simultaneously to ensure a responsive chat experience.
* **Exception Handling:** Created custom exceptions to handle specific scenarios, such as server crashes.

### 3. [Multithreaded File Downloader](https://github.com/badrean/MultiThreadedDownloader)
A Java application for downloading files using multiple threads or a single thread based on server capabilities.

#### Key Features:
* Configurable number of download threads and destination directory.
* Dynamic decision-making to use multiple threads if the server supports byte-range requests.

#### What I Learned:
* **Multithreading:** Applied multithreading concepts to improve download speeds and efficiency.
* **File Transfer over Network:** Gained experience in handling large file downloads and network communication protocols.
* **Configuration Management:** Used a configuration class to manage settings.
