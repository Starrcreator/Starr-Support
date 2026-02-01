Starr Support
Starr Support is a comprehensive care management application designed for supported living services. It streamlines medication tracking, task management, and person-centered care coordination for support workers and care managers.
🌟 Features
Core Functionality
Person-Centered Profiles - Detailed profiles for people we support (PWS) including medical conditions, allergies, and emergency contacts
Medication Management - Schedule tracking, administration logging, and due/overdue alerts
Task Management - Daily task lists with time-based tracking and completion status
Real-Time Notifications - Automatic alerts for due medications and missed tasks
Role-Based Access Control - Separate permissions for managers and support workers
Multi-Project Support - Staff can work across multiple houses/locations
User Roles
Support Workers
View assigned people we support
Track and mark medications as administered
Complete daily care tasks
Access person-specific care information
Receive real-time notifications
Managers
All support worker capabilities
Create and assign tasks
Add new medications
Manage staff assignments
View reports and analytics
Access all projects/houses
🚀 Getting Started
Demo Accounts
Try the application with these test credentials:
Manager Access:
Email: sarah@starrsupport.com
Password: manager123
Support Worker Access:
Email: mike@starrsupport.com
Password: worker123
Installation
Clone the repository:
git clone https://github.com/yourusername/starr-support.git
cd starr-support
Open index.html in your web browser, or serve it with a local web server:
# Using Python
python -m http.server 8000

# Using Node.js
npx http-server
Navigate to http://localhost:8000 in your browser
📱 Current Status
Version: 1.0.0 (Alpha)
This is a functional prototype built with:
React (via CDN)
LocalStorage for data persistence
Responsive CSS design
Planned Features
[ ] Backend database integration (PostgreSQL/MongoDB)
[ ] AI-powered care insights and pattern recognition
[ ] Fluid intake tracking with camera integration
[ ] Sleep monitoring via bed sensors
[ ] Photo documentation and timestamping
[ ] Incident reporting and logging
[ ] Family/advocate portal
[ ] Mobile app (iOS/Android)
[ ] Push notifications
[ ] Export reports (PDF/Excel)
[ ] Voice note transcription
[ ] Appointment scheduling
[ ] Goal tracking and progress monitoring
🏗️ Technical Architecture
Current Implementation
Frontend: React (vanilla JavaScript, no build process)
Storage: Browser LocalStorage
Styling: Custom CSS with CSS variables
State Management: React hooks (useState, useEffect)
Future Architecture
Backend: Node.js/Express or Python/Django
Database: PostgreSQL with encrypted patient data
Authentication: JWT tokens with role-based permissions
API: RESTful API or GraphQL
Real-time: WebSockets for live notifications
Hosting: Cloud deployment (AWS/Azure/GCP)
🔒 Security & Privacy
This application handles sensitive health information. Current security measures:
Role-based access control
Project-based data segregation
No real patient data in demo
For Production Deployment:
[ ] HTTPS/TLS encryption
[ ] HIPAA/GDPR compliance measures
[ ] Encrypted data at rest and in transit
[ ] Audit logging
[ ] Multi-factor authentication
[ ] Regular security audits
[ ] Data backup and recovery procedures
📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
👥 Contributing
This is currently a private project under active development. Contributions will be welcomed once the project reaches beta status.
📞 Contact
Project Maintainer: [Your Name]
Email: [Your Email]
Part of the Starr Suite: Starr Support is part of a family of care management applications.
🙏 Acknowledgments
Built to improve the quality of care for people with disabilities in supported living environments.
Note: This application is under active development. Features and functionality are subject to change. Always test thoroughly before deploying in a production care environment.
