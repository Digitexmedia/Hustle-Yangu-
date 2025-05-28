# Hustle-Yangu-

Hustle Yangu Dashboard

Overview

Hustle Yangu is a user dashboard interface designed to manage investments, earnings, and user profiles in a clean, responsive web app. It features a collapsible sidebar menu for navigation, wallet balance display, and quick links to key actions like deposit, withdraw, transactions, profile management, and more.

The interface is styled with a dark blue theme with orange accents and works well on both desktop and mobile devices.

Features

Responsive Sidebar Navigation:
Sidebar with all main sections — Home, VIP, Invites, Deposit, Withdraw, Transactions, Profile, App, and Logout.
On smaller screens, sidebar can be toggled by clicking the hamburger menu (three lines), and closed by clicking the "X" button or outside the menu.

Dashboard Content Area:
Displays wallet balance, quick action buttons for deposit, withdraw, and viewing transactions.

Dark Themed UI:
Easy on the eyes with a consistent color scheme and smooth transitions.

Local Storage Wallet Balance:
Wallet balance is saved and read from localStorage for demonstration purposes.


File Structure

index.html — Main dashboard page with sidebar navigation and wallet display.

vip.html — VIP membership page (to be developed).

invites.html — Invites/referral page (to be developed).

deposit.html — Deposit funds page (to be developed).

withdraw.html — Withdraw funds page (to be developed).

transactions.html — Transaction history page (to be developed).

profile.html — User profile management page (to be developed).

app.html — Application download or info page (to be developed).

logout.html — Logout logic or page (to be developed).


Setup & Usage

1. Download or clone the repository.


2. Open index.html in a modern web browser.


3. Navigate using the sidebar:

On desktop, the sidebar is visible by default.

On mobile/smaller screens, tap the hamburger icon to toggle sidebar.



4. Manage wallet balance:

Click the "Refresh Balance" button to update wallet display from localStorage.

You can manually set wallet balance in browser console for testing:

localStorage.setItem('wallet', '1000');



5. Expand other pages by developing the respective HTML files.





Technologies Used

HTML5, CSS3 (Flexbox & transitions)

Vanilla JavaScript for UI interactions and localStorage management

Responsive design for mobile and desktop


Future Improvements

Backend integration for user authentication, wallet transactions, and real data management.

Full implementation of deposit, withdrawal, transactions, and profile pages.

Real-time updates and notifications.

Enhanced accessibility and keyboard navigation support.



License

This project is open for personal and educational use. Feel free to adapt or extend it to suit your needs.

