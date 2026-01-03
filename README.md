# Digital-Notice-Board

📢 Digital Notice Board – Web Application
A modern, mobile-responsive Digital Notice Board system built using HTML, Tailwind CSS, JavaScript, and GSAP animations.
This project provides an admin dashboard for managing notices and complaints, along with a public-facing notice board accessible on smartphones via a shared link.

🔑 Key Features
👨‍💼 Admin Panel

Secure admin login (demo credentials)
Create, view, and delete notices
Set expiry dates for notices (auto-hide after expiry)
View and manage user complaints
Real-time complaint count badge
Smooth UI animations using GSAP

📱 Public Notice Board
Mobile-first, responsive design
View only active (non-expired) notices
Expiry countdown indicator for urgent notices
Clean card-based UI
Accessible via public link or QR code

💬 Complaint System
Users can submit complaints with name & email
Complaints stored locally and visible in admin panel
Admin can delete individual or all complaints

🛠️ Tech Stack
HTML5
Tailwind CSS
JavaScript (Vanilla)
GSAP (GreenSock Animation Platform)
LocalStorage (used as a lightweight database)

🧠 How It Works
Admin Dashboard → Stores data in LocalStorage → Public Notice Page fetches & displays notices

Admin manages notices from a private dashboard
Notices are automatically synced to the public page
Expired notices are hidden automatically
Public users cannot edit notices (read-only access)

🎯 Use Cases
Colleges & Universities
Societies & Clubs
Apartments & Communities
Offices & Institutions

🚀 Highlights
No backend required
Works on all modern browsers
Smartphone-friendly UI
Easy to deploy on GitHub Pages / Netlif
Ideal mini project for web development portfolios

🔐 Demo Credentials (for testing)
Username: admin
Password: admin123

📌 Future Improvements
Firebase / Backend integration
Role-based authentication
Push notifications
PWA support (install as app)
Cloud database instead of LocalStorage

📄 License
This project is open-source and free to use for learning and educational purposes.
