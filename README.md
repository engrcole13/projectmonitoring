FACILITY & PROJECT MONITORING SYSTEM

The Facility & Project Monitoring System is a web-based platform designed to efficiently track, manage, and monitor facility operations and project progress in real time. It provides engineers, project managers, and administrators with clear visibility into ongoing projects, work statuses, and facility-related updates — all in one centralized system.

FEATURES

• Dashboard Overview – Displays project summaries, key performance indicators, and facility statistics.
• Project Tracking – Monitors project timelines, milestones, and completion percentages.
• Facility Monitoring – Lists active facilities, maintenance records, and ongoing activities.
• Task Management – Allows users to assign, update, and close tasks with progress tracking.
• Document Management – Enables uploading and organizing of project-related files for easy access.
• User Roles and Permissions – Provides Admin, Engineer, and Viewer roles for controlled access.
• Activity Logs – Records system updates, user actions, and project modifications.
• Responsive Design – Fully compatible with desktop, tablet, and mobile devices.

TECH STACK

Frontend: HTML, CSS, JavaScript (or your chosen framework such as React or Vue)
Backend: PHP / Node.js / Python (depending on implementation)
Database: MySQL / PostgreSQL / Firebase
Hosting: Vercel, Netlify, or a local server setup

INSTALLATION GUIDE

Clone the repository using:
git clone https://github.com/yourusername/facility-project-monitoring.git

Navigate to the project folder:
cd facility-project-monitoring

Install dependencies if applicable:
npm install

Configure the database connection in the .env or config.php file.

Run the development server:
npm run dev

Open your browser and go to:
http://localhost:3000

FOLDER STRUCTURE

facility-project-monitoring/
│
├── public/ – Static files
├── src/
│ ├── components/ – User interface components
│ ├── pages/ – Main website pages
│ ├── assets/ – Images, icons, and other media
│ ├── services/ – API and database connections
│ └── utils/ – Helper and configuration functions
│
├── config/ – Database and environment settings
├── .env – Environment variables
└── README.txt

USER ROLES

Admin – Full access to all modules and settings
Engineer – Can update project and facility data
Viewer – Read-only access for monitoring

FUTURE IMPROVEMENTS

• Integration with Google Maps for facility location tracking
• Automated report generation in PDF or Excel format
• Real-time notifications and alert system
• Mobile app version for on-site monitoring (React Native or Flutter)
