# Smart-Parking-Assisstant-

🚗 Smart Parking Assistant System (C++ Console App)

A simple and efficient console-based Smart Parking System developed in C++, using Object-Oriented Programming (OOP) concepts and file handling. This system allows users to book, view, cancel, and exit parking slots, while providing an admin interface for management and reporting.


📌 Features


👤 User Module

🔐 Login with User ID

🅿️ Book Slot Manually (via admin) or Automatically (nearest slot)

🔍 View Current Booking Info

💸 Exit & Generate Parking Bill (hourly rate based)

🚫 One slot per user (no double booking)

📁 Ticket logs saved to tickets.txt

🛠️ Admin Module

🔓 Admin login (default password: admin123)

🗺️ View real-time parking map with [A]/[B] status

❌ Cancel Booked Slot

🧹 Clear Ticket History

🔎 Search Tickets by Date (e.g., "Jun 06")


🧠 Tech Stack

Language: C++


Concepts Used:


Classes & Objects

File Handling (fstream)

Date/Time (ctime)

Console I/O

Conditional Logic & Loops


💾 Data Files

tickets.txt
Stores entry, exit, and fee records for each parking activity.


⚙️ How It Works

Run the application from a C++ IDE or command line.

Choose login as Admin or User.

Book parking slot, view status, or exit.

Admin can monitor the lot, cancel bookings, or search logs.


🚧 Future Enhancements

GUI version using Qt or C++ CLI

Vehicle number plate integration

Real-time dashboard via web interface

Database support instead of flat files


📷 Preview (Console View)

===== SMART PARKING MAP =====
        Col 1  Col 2  Col 3  Col 4  Col 5
Row 1   [ ]    [X]    [ ]    [ ]    [ ]
Row 2   [ ]    [ ]    [ ]    [ ]    [ ]
...
Legend: [ ] = Available, [X] = Occupied

The Smart Parking Assistant System provides a practical simulation of a real-world parking lot using C++. It combines core OOP principles with file handling and date-time functions to manage parking operations efficiently. While console-based, it lays a solid foundation for future expansion into graphical or web-based systems. Ideal for students and developers looking to understand system design, user roles, and data persistence in C++.
