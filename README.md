This Bash script is designed for a food ordering system with two roles: customer and admin. Customers can place orders for various food items, while admins have access to an admin panel for managing the menu and viewing order details.

How to Use
When you run the script, you'll be prompted to select your role:

Enter 1 for Customer.
Enter 2 for Admin.
Customer Role:

Customers can order food items by entering the corresponding numbers.
They can specify the quantity and size (if applicable) of each item.
To finish ordering, enter 0.
After completing the order, a summary will be displayed, and the script will thank the customer.
Admin Role:

The admin role requires a password (default is "admin123").
Admins can perform the following actions:
Add a new food item to the menu.
View order details.
Menu Display
The script displays a menu with various food items, including their names, sizes, and prices. Customers can choose from the available options.

Menu File
The menu items are stored in a file called menu.txt. When an admin adds a new food item, it is appended to this file.

Order Details
Order details are stored in an array called order_details. Customers' orders are added to this array and can be viewed by the admin from the admin panel.

Admin Panel
The admin panel provides the following options:

Add Food Item: Allows admins to add a new food item to the menu.
View Order Details: Displays the order details, if any, placed by customers.
Exit: Exits the admin panel.
Password
The default admin password is "admin123." Admins need to enter this password to access the admin panel. You can change the password by modifying the admin_password variable in the script.

Notes
This script is a basic implementation and may require further enhancements for a real-world application.
Security considerations and data validation are not robust in this script and should be improved in a production system.
Remember to customize the script according to your specific requirements, including security and data validation, before using it in a production environment.
