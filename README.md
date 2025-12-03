# HELPLINK
a real time problem solving project

Figma link: https://www.figma.com/proto/6mGJdtpzE83sPwZwkw0BT3/HelpLink?node-id=4-35&t=Yxv4nydwg0ztK0DI-1

HelpLink bridges the gap between rural patients in distress and available volunteers using a simple, user-friendly digital platform.

Users can:
Request medical help
Share location & emergency details
View volunteer availability
Track help status

Volunteers can:
* Receive SOS requests
* Accept or decline help
* Navigate to the user's location
* Update status in real-time

🧩 Features
⭐ User (Rural People)
* Simple login/signup
* Emergency help request form
* Location sharing
* Real-time volunteer assignment
* Help status tracking

⭐ Volunteer
* Login/signup
* View incoming medical requests
* Accept/Decline requests
* Live status updates
* Support multiple users

⭐ System Features
* MERN stack full CRUD
* JWT Authentication
* Protected routes
* Role-based login (User/Volunteer switch)
* Responsive UI (Figma-based design)

🔒 Authentication Flow (JWT)
* User/Volunteer chooses login role
* Backend verifies credentials
* JWT token issued
* Protected routes require token
* Logout clears localStorage token

  📌 API Endpoints (Sample)
Auth
* POST /api/auth/register
* POST /api/auth/login

Emergency Requests
* POST /api/help/request
* GET /api/help/requests
* PATCH /api/help/update/:id

🌱 Future Enhancements
Real-time tracking (Socket.io)
Volunteer rating system
Push notifications
Mobile app version
Multi-language rural UI

❤️ Acknowledgments
MERN stack community
Open-source contributors
Figma design support
AI assistance for documentation
