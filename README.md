Inventory Management System
Welcome to the Inventory Management System! This application is designed to help your business efficiently track, manage, and update inventory levels in real time. Built by our dedicated team, it’s tailored to provide reliability and scalability for growing businesses.
________________________________________

🔄 Roles and Process Flow
Roles Involved
1.	Sender: Person who initiates the sending of items.
2.	Sender's Project Manager: Reviews and approves or disapproves the sending process.
3.	Receiver: Person responsible for receiving the items at the destination.
4.	Receiver's Project Manager: Reviews and approves or disapproves the receipt of items.
________________________________________
📋 Process Stages
1.	Send Items
o	Action: Sender fills out a form with details about the items being sent.
o	Next Step: Form is submitted to the Sender's Project Manager for approval.
2.	Approve Send Items
o	Action: Sender’s Project Manager reviews the form and takes action:
	If Approved: Items are sent to the destination project.
	If Disapproved: Process stops, and the transaction moves to the 'Transaction History' tab.
3.	Receive Items
o	Action: Receiver accepts the parcel and fills out the corresponding form.
o	Next Step: Form is submitted to the Receiver’s Project Manager for approval.
4.	Approve Received Items
o	Action: Receiver’s Project Manager reviews the receipt form:
	If Approved: The transaction is completed and moved to the 'Transaction History' tab.
	If Disapproved: Process stops, and the transaction moves to the 'Transaction History' tab.
________________________________________
📊 Tracking Tabs
1.	Transaction Progress Tab
o	Purpose: Displays all transactions currently in progress.
o	Content: Shows ongoing transactions that have not reached a final approval or disapproval.
2.	Transaction History Tab
o	Purpose: Displays all completed or terminated transactions.
o	Content: Includes transactions that have been approved or disapproved at any stage.
o	Filter:
	For Employees: Displays transactions related to their involvement.
	For Managers: Displays transactions related to their project.
________________________________________
🔁 Process Flow Summary
1.	Sender fills in the form and submits it.
2.	Sender’s Project Manager approves or disapproves the form:
o	If Approved: Items are sent.
o	If Disapproved: The transaction moves to the 'Transaction History' tab.
3.	Receiver accepts the items and fills out the form.
4.	Receiver’s Project Manager approves or disapproves the form:
o	If Approved: The transaction is completed and moves to the 'Transaction History' tab.
o	If Disapproved: The transaction moves to the 'Transaction History' tab.
________________________________________
🚦 Actions
•	Approve: Moves the process to the next stage or completes it.
•	Disapprove: Stops the process and logs the transaction in the 'Transaction History' tab.

________________________________________
🚀 Getting Started
Prerequisites
•	Python 
•	MS SQL 
Installation
1.	Clone the Repository
2.	Install Dependencies
3.	Set Up Environment Variables
Create a .env file in the root directory with the following:
makefile
Copy code
DATABASE_URL=mongodb://localhost:27017/inventory
PORT=3000
JWT_SECRET=yourSecretKey
4.	Run the Application
________________________________________
🧩 Technologies Used
•	Frontend: HTML, CSS, Javascript
•	Backend: Python, Flask
•	Database: MS SQL
•	Deployment: On-Premise Infrastructure
________________________________________
📞 Support
For issues, please reach out at shaikhfahad687@gmail.com

