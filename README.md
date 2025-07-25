AEROSPACE TESTING SAAS PLATFORM: TestBedz

TestBedz is a comprehensive, turn-key web application designed to connect clients with aerospace testing facilities. It functions as a SaaS platform where users can submit detailed test campaigns, track their status in real-time, and view facility information. The platform also includes a complete administrative dashboard for facility managers to view and manage all incoming client requests.

This project is built as a dynamic Single-Page Application (SPA) using vanilla JavaScript, with a secure, real-time backend powered by Google Firebase.

Key Features
For Clients (Users)
Multi-Step Campaign Creation: An intuitive, multi-step form guides users through submitting all necessary details for a new test campaign.
Secure User Accounts: Users can sign up and log in with email and password, with all data securely managed by Firebase Authentication.
Persistent User Dashboard: Once logged in, users are presented with a dashboard that displays all their submitted campaigns, saved securely in the Firestore database.
Real-Time Status Updates: Campaign statuses update in real-time without needing a page refresh, reflecting changes made by the admin.
Detailed Form Logic: The "Add a New Test" form uses conditional logic to show relevant questions based on the selected test type (Vibration, Thermal, etc.).
Public Information Pages: Includes browseable pages for Facilities, FAQs, and Resources.

For Facility Administrators
Secure Admin Login: A dedicated admin role (e-mail: admin@testbedz.com) provides access to a separate, comprehensive dashboard.
Centralized Campaign Dashboard: Admins can view a real-time list of all test campaigns submitted by all users, sorted by date.
Campaign Management: Admins can click into any campaign to view the full details submitted by the user.
Status Control: Admins have the ability to update the status of any campaign (e.g., from "Awaiting Response" to "Planning"), which instantly updates the view for the client.

Tech Stack
Front-End:
HTML5
Tailwind CSS for styling
Vanilla JavaScript (ES6 Modules) for all client-side logic and DOM manipulation.

Back-End & Database:
Firebase Authentication: For secure user sign-up, login, and session management.
Firebase Firestore: A NoSQL, real-time cloud database used to store all user and campaign data.

📖 How to Use
Client Workflow
Use the multi-step form on the homepage to create an account and submit your first test campaign.
Log in using the email and password you created.
You will be directed to your dashboard, where you can see your campaign and its status.
Click on a campaign to view its details or to add more specific tests to it.

Admin Workflow
Click the "Log In" button.
Enter the email admin@testbedz.com and the password you created for it.
Check the "Log in as Admin" checkbox.
You will be directed to the admin dashboard, showing a list of all campaigns from all users.
Click on any campaign to view its details and use the buttons at the bottom to update its status. The user will see this status change in real-time.
