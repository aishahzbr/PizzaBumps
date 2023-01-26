# PizzaBumps
Team Members:
1. Muhammad Atif Hazim Bin Mohd Nasruddin (B032010040)
2. Darven A\L S.Madhavan (B032010179)
3. Aina Hazlin Binti Musa (B032010137)
4. Siti Aishah Binti Ahmad Zubir (B032010241)

PizzaBumps is an application where a pizza kiosk used to let customer order pizza
from their stall.
There are navigations for customer and admin which are Menu and Admin.

Database used is SQlite with 3 tables which are:

1. Pizza

column of: pizzaID, pizzaName,pizzaPrice

2. OrderPizza

column of: orderID, pizzaID, quantity

3. Admin

column of: usernameadmin, passwordadmin

This apps can be used by 2 Users
==================================================================================
1. Customer: Can enter quantity pizza that they want and click CALCULATE button
to see the total pizza that they order with total price. They can click CONFIRM ORDER 
to make order and will get their order number with the display of date time by REST API 
and click DONE when they are done with their order which will go back to the main order page.

2. Admin: Can access admin page to see the list of order that has been made in order page. 
They also can see the list of pizza in the database as there is button to click to show the list of pizza.



Step to execute the application
====================================================================================
1. Extract PizzaBumps zip file into android studio project directory
2. Open android file in android studio
3. Go to Device File Explorer > data > data > ftmk.bitp3453.labtest
4. Right click and select new > Directory
5. Name the folder as databases
6. Upload pizzabumps sqlite file into the databases by right click on databases > upload
7. Run the application 
8. You can test admin by entering username: aishah password: abc 123
