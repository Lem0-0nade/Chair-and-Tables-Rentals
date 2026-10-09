# Chair We GO! - Event Rentals Management System

## Business Name and Description

Chair We GO! is a premier event rentals business specializing in high-quality seating and dining tables for discerning events ranging from intimate gatherings to grand formal banquets. The system serves two primary types of users:

* **Clients/Users:** Individuals who browse inventory, curate event selections, book reservations with flexible delivery or pickup options, track reservation statuses, and communicate with support.
* **Administrators:** Business managers who oversee product inventory, monitor event schedules via an interactive calendar, manage client records, update payment statuses (Pending to Paid), and handle customer support chats.

## Problem Being Solved

Manual event rental reservations are often disorganized, prone to double-booking inventory, and lack real-time visibility over payment collections and delivery logistics. Chair We GO! solves these challenges by providing a centralized cloud-synced web application that automates inventory stock tracking per date, provides secure user authentication, handles 50% downpayment workflows, maintains an interactive calendar, and offers real-time notifications and support chat.

## Feature List

* **Landing Page:** Professional hero section, business value propositions, and quick authentication triggers.
* **User Authentication:** Secure registration and login supporting password hashing for clients and administrators.
* **Inventory & Stock CRUD:** Admins can view and update stock capacities for items such as monoblock chairs, round banquet tables, and rectangular buffet tables.
* **Reservation & Cart Management:** Users can curate items, add optional fitted covers, select event dates with lead time validations, choose pickup or delivery logistics, and view calculated totals and receipts.
* **Interactive Event Calendar:** Admins can visualize daily bookings, inspect event details, mark payments as paid, or terminate reservations to automatically free up inventory.
* **Real-time Notifications:** Bell icon dropdown displaying interactive notification items with Philippine Standard Time (PST, UTC+8) timestamps. Clicking a notification opens reservation details for immediate review and status updates.
* **Support Chat System:** Real-time messaging widget allowing clients and admins to chat and exchange proof of payment attachments.

## Tech Stack Used

* **Frontend:** HTML5, CSS3, JavaScript (Vanilla ES6 modules).
* **Backend & Database:** Firebase Realtime Database.
* **Security:** Web Crypto API (SHA-256 password hashing).

## Setup and Run Instructions

1. Clone or download the project files to your local machine.
2. Ensure you have the `index.html` file and any corresponding image assets in your local directory structure.
3. Open `index.html` using a modern web browser (Google Chrome, Mozilla Firefox, Microsoft Edge, or Safari). Because the application utilizes Firebase JavaScript modules, running it through a local development server (such as Live Server in VS Code) or directly via a modern browser supporting ES modules is recommended.
4. Log in using the test credentials provided below.

## AI Tools Used

* **Gemini (Personal AI Collaborator):** Used to design, write, and iteratively refactor the front-end interface, implement Firebase cloud database integration, establish Philippine Standard Time formatting, build the real-time chat widget with image attachment support, and construct the interactive notification dropdown list.

## Test Accounts

* **Admin Account:**
* Identifier: `admin@chairwego.com` (or `admin`)
* Password: `admin`


* **Regular User Account:**
* You can register a new account directly through the registration portal on the landing page, or log in with any newly created client credentials.
