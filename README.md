 # Placement Management System

![Placement Management System](https://img.shields.io/badge/Status-Active-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue.svg)
![Version](https://img.shields.io/badge/Version-1.0.0-orange)

A comprehensive web-based solution for managing the entire placement process for educational institutions. This system streamlines communication between students, recruiters, and placement officers while providing powerful analytics and reporting tools.

## 📋 Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Screenshots](#screenshots)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [API Documentation](#api-documentation)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## ✨ Features

### For Students
- Create and manage professional profiles
- Apply to job postings with single-click applications
- Track application status in real-time
- Access resources for interview preparation
- Receive notifications for new opportunities

### For Recruiters
- Post job openings with detailed requirements
- Filter and sort student applications
- Schedule interviews and send automated notifications
- Access student resumes and profiles
- Track recruitment progress

### For Placement Officers
- Comprehensive dashboard with placement statistics
- Generate detailed reports on placement activities
- Manage company relationships and recruitment drives
- Monitor student participation and performance
- Configure system settings and permissions

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Cloud Storage**: AWS S3 (for resume storage)
- **Deployment**: Docker, AWS/Heroku

## 📸 Screenshots

<details>
<summary>View Screenshots</summary>

### Dashboard
![Dashboard](https://via.placeholder.com/800x450?text=Dashboard+Screenshot)

### Student Profile
![Student Profile](https://via.placeholder.com/800x450?text=Student+Profile+Screenshot)

### Job Listings
![Job Listings](https://via.placeholder.com/800x450?text=Job+Listings+Screenshot)

### Analytics
![Analytics](https://via.placeholder.com/800x450?text=Analytics+Screenshot)

</details>

## 🚀 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/BalajiJangili/Placement-Management-website.git
   cd Placement-Management-website
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   ```bash
   cp .env.example .env
   # Edit .env file with your configuration
   ```

4. Set up the database:
   ```bash
   npm run db:setup
   ```

5. Start the development server:
   ```bash
   npm run dev
   ```

6. Access the application at `http://localhost:3000`

## 💻 Usage

### Admin Setup
1. Login with the default admin credentials:
   - Username: `admin@example.com`
   - Password: `admin123` (change this immediately after first login)

2. Configure system settings:
   - Set up academic year and placement season
   - Create user roles and permissions
   - Customize email templates

### Student Registration
1. Students register using their academic email
2. Complete profile with academic details and upload resume
3. Browse and apply for available job openings

### Recruiter Workflow
1. Register as a company representative
2. Post job opportunities with detailed requirements
3. Review applications and schedule interviews
4. Update hiring status and generate offer letters

## 📁 Project Structure

```
placement-management-website/
├── client/              # Frontend code
│   ├── public/          # Static assets
│   └── src/             # React components and styles
├── server/              # Backend code
│   ├── controllers/     # Request handlers
│   ├── models/          # Database models
│   ├── routes/          # API routes
│   └── middleware/      # Custom middleware
├── config/              # Configuration files
├── scripts/             # Utility scripts
├── tests/               # Test suites
└── docs/                # Documentation
```

## 📚 API Documentation

API documentation is available at `/api/docs` when running the development server, or you can view the [API Documentation](https://github.com/BalajiJangili/Placement-Management-website/wiki/API-Documentation) in the wiki.

### Key Endpoints:

- `/api/auth` - Authentication endpoints
- `/api/students` - Student management
- `/api/companies` - Company and recruiter management
- `/api/jobs` - Job postings and applications
- `/api/analytics` - Reporting and statistics

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

Please make sure to update tests as appropriate and follow the [code of conduct](CODE_OF_CONDUCT.md).

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact

Balaji Jangili - [@balaji_jangili](https://x.com/balu_031?t=ocXAC3IkNiVIfG7Ssn4LbQ&s=09) - balajiashok@gmail.com

Project Link: [https://github.com/BalajiJangili/Placement-Management-website](https://github.com/BalajiJangili/Placement-Management-website)

---

⭐️ **Star this repository if you find it useful!** ⭐️
