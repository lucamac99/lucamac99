### 🔐 Access & Payment Management System


Seamless Integration Between Access Control, Bookings & Invoicing
This system was built to centralize and automate the user and payment management for an organization handling physical access control and external booking software. It tracks user movements, synchronizes their status, and generates invoices and receipts—fully integrated and automated.

##### ⚙️ Key Features:

🔁 Sync with External Booking App – A background job (handled via RedwoodJS cron/worker setup) periodically syncs user data and attendance from the external booking system.
🛂 Access Control Integration – Connects with physical badge-based door systems to log entry events and associate them with registered users.
🧾 Invoicing & Receipts – Automatically generates and manages invoices based on activity, user category, and product type. Includes downloadable PDFs.
💳 Payment Tracking – Tracks payment statuses, unpaid balances, and links them to invoice records in real time.
📦 Product & Pricing Management – Dynamic handling of multiple product types and user categories (e.g. student, staff, visitor), each with configurable pricing.
👥 User Registry – Detailed user records with full history of bookings, access logs, and financial status.


##### 🖥️ Tech Stack:
RedwoodJS, PostgreSQL, Prisma, RedwoodJS Background Jobs, Docker, REST APIs


##### 🎥 Demo Video:
[Watch the video](https://drive.google.com/file/d/1UWqkK92kGknViQCbQWgyK0nMa93jPsfB/view?usp=share_link)
