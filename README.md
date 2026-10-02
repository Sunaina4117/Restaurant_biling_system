🍽️ Restaurant Billing System

A simple Restaurant Billing System built using Python. This beginner-friendly project allows users to view a restaurant menu, select food items, enter quantities, and generate a final customer bill.

📌 Features

Display restaurant menu

Select food items by item number

Enter quantity for each item

Calculate the total price for each item

Add multiple items to the cart

Generate a customer bill

Calculate the total amount

Exit the program after generating the bill

Validate that the quantity is greater than zero

🛠️ Technologies Used

Python 3

Jupyter Notebook (optional)

📋 Menu
No.	Item	Price
1	Pizza	₹200
2	Burger	₹100
3	Pasta	₹150
4	Coffee	₹80
5	Generate Bill and Exit	—
🚀 How to Run
1. Install Python

Make sure Python 3 is installed on your computer.

Check your Python version:

python --version

2. Run the Program

Save the Python code as:

restaurant_billing.py


Then run:

python restaurant_billing.py


You can also run the program inside Jupyter Notebook.

💻 How It Works

When the program starts, it displays the restaurant menu:

===== RESTAURANT MENU =====
1 Pizza - Rs. 200
2 Burger - Rs. 100
3 Pasta - Rs. 150
4 Coffee - Rs. 80
5. Generate Bill and Exit


The user selects an item and enters the required quantity.

For example:

Enter your choice: 1
Enter quantity: 2

Pizza added successfully!
Item Total: Rs. 400


The user can continue ordering multiple items.

To finish the order, select option 5.

🧾 Example Bill
====== CUSTOMER BILL ======
Pizza x 2 = 400
Burger x 3 = 300
Coffee x 1 = 80
---------------------------
Total Amount: Rs. 780
Thank you for visiting!

📂 Project Structure
Restaurant-Billing-System/
│
├── restaurant_billing.py
└── README.md


If you are using Jupyter Notebook:

Restaurant-Billing-System/
│
├── restaurant_billing.ipynb
└── README.md

🔑 Main Functions
show_menu()

Displays all available food items and their prices.

order_food(choice)

Takes the selected item, asks for quantity, calculates the item total, and adds it to the cart.

generate_bill()

Displays all ordered items and calculates the final bill amount.

main()

Controls the overall program using a continuous loop until the user chooses to generate the bill and exit.

🎯 Learning Objectives

This project demonstrates the use of:

Variables

Dictionaries

Lists

Tuples

Functions

if-else conditions

while loops

for loops

User input

Arithmetic operations

Basic data validation

🔮 Future Improvements

The project can be extended by adding:

Customer name and contact details

GST/tax calculation

Discount coupons

Payment methods

Order cancellation

Table number

Date and time on the bill

Saving bills to a file

Database integration

Graphical User Interface (GUI)

Admin menu for adding/updating food items

👨‍💻 Author

Your Name

📄 License

This project is created for educational and learning purposes.
