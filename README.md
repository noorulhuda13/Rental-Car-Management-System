# Rental-Car-Management-System
🏎️ Rental Car Management System
📘 Overview

The Rental Car Management System is a console-based program that helps manage a car rental business efficiently.
It keeps track of available cars, registered customers, bookings, and car returns using core data structures in C++.

⚙️ Features

Add Car – Add new cars to the system inventory.

Add Customer – Register new customers with name, ID, and wallet balance.

Book Car – Rent out cars to customers based on availability and wallet balance.

Return Car – Handle returns and mark cars as available again.

Display Data – Show complete car lists and customer details.

Discount System – Automatically applies discounts for frequent customers (10+ bookings).

🧩 Data Structures Used
Structure	Purpose
Array	Stores list of cars.
Vector	Stores list of customers dynamically.
Queue	Manages bookings in first-come-first-serve order.
Stack	Manages car returns (LIFO).
🧠 Core Components

Car: Stores model, price per day, and availability.

Customer: Stores name, ID, wallet balance, and booking count.

Booking: Stores customer index, car index, number of days, and total cost.

🏗️ Workflow

Initialization: System starts with 5 default cars.

Menu Interface: User can:

Add customers

Display cars/customers

Book or return cars

Exit: User exits when finished.

🧾 Error Handling

Verifies customer and car existence.

Checks sufficient balance before booking.

Ensures car availability before renting.

🚀 Future Enhancements

Database Integration: Replace arrays/vectors with SQL or file-based storage.

User Authentication: Role-based access for admin and customers.

Booking Management: Support for modifications and cancellations.

GUI Version: Develop a graphical interface using JavaFX or Python Tkinter.

🧑‍💻 Author

Noor ul Huda (FA23-BCE-082)
Department of Computer Engineerin
