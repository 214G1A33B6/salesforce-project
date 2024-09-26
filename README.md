CRM Application to Manage the Booking of Co-Living:
Project Overview
This CRM application is designed to efficiently manage the booking of co-living spaces. It provides a platform for administrators to handle customer inquiries, manage reservations, track occupancy, and automate various operational tasks. Customers can browse available co-living spaces, book them seamlessly, and manage their bookings in real-time.

Features
Customer and Booking Management: Create and manage customer profiles and track their booking history.
Real-Time Availability Tracking: View the status of rooms and units at any time.
Automated Notifications: Send automated emails for booking confirmations, reminders, and payment updates.
Payment Integration: Track customer payments and generate invoices.
Analytics Dashboard: View metrics related to occupancy, revenue, and customer satisfaction.


Installation
1.Clone the repository:
git clone https://github.com/214G1A33B6/saleforce-project.git


2.Navigate to the project directory
cd saleforce-project
3.Install the dependencies:
pip install -r requirements.txt
4Set up the database (MySQL/PostgreSQL/SQLite):
python manage.py migrate
5.Create a superuser to access the admin dashboard:
python manage.py createsuperuser
6.Run the development server
python manage.py runserver

Usage
After starting the server, access the application in your browser at http://localhost:8000.
Use the admin dashboard to manage customers, bookings, and spaces.
Customers can log in, view available spaces, make bookings, and track their reservations.




