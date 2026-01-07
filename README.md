# 🚀 Internal Systems Portfolio

A collection of internal web-based systems developed for Exelpack Corporation, focused on streamlining operations, improving productivity, and modernizing business processes.

[![React](https://img.shields.io/badge/React-18.x-61DAFB?style=for-the-badge&logo=react&logoColor=white)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Node.js](https://img.shields.io/badge/Node.js-18.x-339933?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-15.x-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)

---

## 📋 Table of Contents

- [Projects Overview](#-projects-overview)
  - [EMMC eSign System](#-emmc-esign-system)
  - [DPMS - Daily Production Monitoring System](#-dpms---daily-production-monitoring-system)
  - [Production Planning System](#-production-planning-system)
  - [EMMCRMS - Ticketing System](#-emmcrms---ticketing-system)
- [Tech Stack](#-tech-stack)
- [Features](#-features)
- [Installation](#-installation)
- [Environment Variables](#-environment-variables)
- [Database Setup](#-database-setup)
- [Running the Applications](#-running-the-applications)
- [Project Structure](#-project-structure)
- [Screenshots](#-screenshots)
- [Contributing](#-contributing)
- [License](#-license)
- [Contact](#-contact)

---

## 🎯 Projects Overview

### ✍️ EMMC eSign System

**Digital Signature & Document Management Platform**

A comprehensive digital signature solution that eliminates paper-based document workflows and provides secure, auditable electronic signatures.

#### Key Features
- 🖊️ **Digital signature capture** with canvas-based interface
- 📄 **PDF document generation** and manipulation using PDF-lib
- 👥 **Multi-user authentication** and role-based authorization
- 🔄 **Document workflow** and approval chains
- ✅ **Signature verification** and validation
- 📊 **Audit trail** and compliance logging
- 📁 **Centralized document tracking** and version control

#### Tech Stack
- Frontend: React, TypeScript, PDF-lib
- Backend: Node.js, Express
- Database: PostgreSQL
- Authentication: JWT

#### Impact
- ⏱️ Reduced document processing time by 70%
- 📉 Eliminated paper waste and storage costs
- 🔒 Enhanced security and compliance
- ✅ Improved audit trail transparency

---

### 📊 DPMS - Daily Production Monitoring System

**Real-time Production Tracking & Analytics Platform**

A data-driven system for monitoring daily production metrics, analyzing performance trends, and generating automated reports for management decision-making.

#### Key Features
- 📈 **Real-time production data** monitoring and visualization
- 📋 **Automated daily reports** generation
- 📊 **Performance analytics** and trend analysis
- 🏭 **Multi-department tracking** across production lines
- 📱 **Customizable dashboards** and KPI metrics
- 📥 **Export functionality** for reports (Excel, PDF)
- 🔐 **Role-based access control** for different departments

#### Tech Stack
- Frontend: React, TypeScript, Chart.js
- Backend: Node.js, Express
- Database: PostgreSQL
- Real-time: WebSocket

#### Impact
- 📈 Increased production visibility by 85%
- ⚡ Reduced report generation time from hours to minutes
- 🎯 Improved data-driven decision making
- 📊 Enhanced cross-department collaboration

---

### 📅 Production Planning System

**Manufacturing Workflow & Schedule Management**

An intelligent production planning tool that optimizes resource allocation, manages work orders, and identifies potential bottlenecks before they impact operations.

#### Key Features
- 📆 **Interactive production scheduling** with calendar view
- 🎯 **Capacity planning** and resource allocation
- 📦 **Material requirements planning (MRP)** integration
- 📋 **Work order management** and tracking
- ⚠️ **Bottleneck identification** and optimization suggestions
- 🔔 **Automated schedule conflict** detection
- 🔗 **Integration** with inventory and DPMS systems

#### Tech Stack
- Frontend: React, TypeScript, React Big Calendar
- Backend: Node.js, Express
- Database: PostgreSQL
- State Management: Zustand

#### Impact
- 🎯 Improved on-time delivery by 40%
- 📉 Reduced scheduling conflicts by 65%
- ⚡ Optimized resource utilization
- 📊 Enhanced production capacity planning

---

### 🎫 EMMCRMS - Ticketing System

**Internal IT Support Ticketing System**

A streamlined ticket management system designed to improve IT support response times and provide transparency in issue resolution across the organization.

#### Key Features
- 🎟️ **Ticket creation and tracking** system
- 👨‍💼 **Admin and technician dashboards** with role-specific views
- 📈 **Reporting and performance metrics**
- ⏱️ **Improved resolution time** tracking
- 📧 **Email notifications** and status updates
- 🔍 **Advanced search and filtering** capabilities

#### Tech Stack
- Frontend: PHP, JavaScript, CSS
- Backend: PHP
- Database: MySQL

#### Impact
- ⏱️ Reduced average ticket resolution time by 50%
- 📊 Improved IT support transparency
- 📈 Enhanced team performance tracking
- ✅ Replaced manual ticket handling processes

---

## 🛠️ Tech Stack

### Frontend
- **React 18.x** - UI library
- **TypeScript** - Type-safe development
- **Tailwind CSS** - Utility-first CSS framework
- **Chart.js** - Data visualization
- **React Big Calendar** - Calendar component
- **PDF-lib** - PDF generation and manipulation
- **Zustand** - State management

### Backend
- **Node.js 18.x** - Runtime environment
- **Express.js** - Web framework
- **JWT** - Authentication
- **WebSocket** - Real-time communication

### Database
- **PostgreSQL 15.x** - Primary database
- **MySQL** - Legacy system support

### DevOps & Tools
- **Git** - Version control
- **npm** - Package management
- **ESLint** - Code linting
- **Prettier** - Code formatting

---

## ✨ Features

### Common Features Across All Systems

- 🔐 **Secure Authentication** - JWT-based authentication with role-based access control
- 📱 **Responsive Design** - Mobile-first design that works on all devices
- ⚡ **Real-time Updates** - WebSocket integration for live data updates
- 📊 **Data Visualization** - Interactive charts and graphs
- 📥 **Export Capabilities** - PDF and Excel export functionality
- 🔍 **Advanced Search** - Powerful search and filtering options
- 📧 **Email Notifications** - Automated email alerts and updates
- 📈 **Audit Logging** - Comprehensive audit trails for compliance
- 🌐 **Multi-user Support** - Concurrent user access with conflict resolution
- 🎨 **Modern UI/UX** - Clean, intuitive interfaces

---

## 🚀 Installation

### Prerequisites

Before you begin, ensure you have the following installed:
- Node.js 18.x or higher
- npm or yarn
- PostgreSQL 15.x
- Git

### Clone the Repository

```bash
git clone https://github.com/yourusername/internal-systems-portfolio.git
cd internal-systems-portfolio
```

### Install Dependencies

For React/TypeScript projects (eSign, DPMS, Production Planning):

```bash
# Install frontend dependencies
cd frontend
npm install

# Install backend dependencies
cd ../backend
npm install
```

For PHP projects (EMMCRMS):

```bash
# Install dependencies using Composer
cd emmcrms
composer install
```

---

## 🔐 Environment Variables

Create a `.env` file in the backend directory:

```env
# Server Configuration
NODE_ENV=development
PORT=5000

# Database Configuration
DB_HOST=localhost
DB_PORT=5432
DB_NAME=your_database_name
DB_USER=your_database_user
DB_PASSWORD=your_database_password

# JWT Configuration
JWT_SECRET=your_jwt_secret_key
JWT_EXPIRE=7d

# Email Configuration (for notifications)
SMTP_HOST=smtp.gmail.com
SMTP_PORT=587
SMTP_USER=your_email@gmail.com
SMTP_PASS=your_email_password

# Frontend URL (for CORS)
CLIENT_URL=http://localhost:3000
```

---

## 🗄️ Database Setup

### PostgreSQL Setup

1. Create a new database:

```sql
CREATE DATABASE internal_systems;
```

2. Run migrations:

```bash
cd backend
npm run migrate
```

3. Seed initial data (optional):

```bash
npm run seed
```

### Database Schema

Each system has its own schema. Example for eSign System:

```sql
-- Users table
CREATE TABLE users (
  id SERIAL PRIMARY KEY,
  email VARCHAR(255) UNIQUE NOT NULL,
  password VARCHAR(255) NOT NULL,
  name VARCHAR(255) NOT NULL,
  role VARCHAR(50) NOT NULL,
  created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);

-- Documents table
CREATE TABLE documents (
  id SERIAL PRIMARY KEY,
  title VARCHAR(255) NOT NULL,
  content TEXT,
  status VARCHAR(50) NOT NULL,
  created_by INTEGER REFERENCES users(id),
  created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);

-- Signatures table
CREATE TABLE signatures (
  id SERIAL PRIMARY KEY,
  document_id INTEGER REFERENCES documents(id),
  user_id INTEGER REFERENCES users(id),
  signature_data TEXT NOT NULL,
  signed_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);
```

---

## ▶️ Running the Applications

### Development Mode

For React/TypeScript projects:

```bash
# Run backend server
cd backend
npm run dev

# In a new terminal, run frontend
cd frontend
npm start
```

The application will be available at:
- Frontend: `http://localhost:3000`
- Backend API: `http://localhost:5000`

### Production Build

```bash
# Build frontend
cd frontend
npm run build

# Start production server
cd ../backend
npm start
```

---

## 📁 Project Structure

```
internal-systems-portfolio/
├── esign-system/
│   ├── frontend/
│   │   ├── src/
│   │   │   ├── components/
│   │   │   ├── pages/
│   │   │   ├── services/
│   │   │   ├── types/
│   │   │   └── App.tsx
│   │   └── package.json
│   └── backend/
│       ├── src/
│       │   ├── controllers/
│       │   ├── models/
│       │   ├── routes/
│       │   ├── middleware/
│       │   └── server.ts
│       └── package.json
├── dpms/
│   └── [similar structure]
├── production-planning/
│   └── [similar structure]
├── emmcrms/
│   ├── includes/
│   ├── assets/
│   ├── dashboard.php
│   └── config.php
└── README.md
```

---

## 📸 Screenshots

### EMMC eSign System
![eSign Dashboard](./screenshots/esign-dashboard.png)
![Document Signing](./screenshots/esign-signing.png)

### DPMS
![Production Dashboard](./screenshots/dpms-dashboard.png)
![Analytics](./screenshots/dpms-analytics.png)

### Production Planning
![Planning Calendar](./screenshots/planning-calendar.png)
![Work Orders](./screenshots/planning-orders.png)

### EMMCRMS
![Ticket Dashboard](./screenshots/emmcrms-dashboard.png)
![Ticket Details](./screenshots/emmcrms-ticket.png)

---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Coding Standards

- Follow TypeScript/JavaScript best practices
- Use ESLint and Prettier for code formatting
- Write meaningful commit messages
- Add comments for complex logic
- Write unit tests for new features

---

## 📝 License

This project is proprietary software developed for Exelpack Corporation. All rights reserved.

For internal use only. Unauthorized copying, distribution, or modification is strictly prohibited.

---

## 📞 Contact

**Patrick Leimuel Aganos**

- 📧 Email: kingpatrickleimuel15@gmail.com
- 📱 Phone: 0991-378-2181
- 💼 Position: IT Support / Programmer
- 🏢 Company: Exelpack Corporation
- 📍 Location: Calamba City, Laguna

### Social Links
- GitHub: [@yourusername](https://github.com/yourusername)
- LinkedIn: [Patrick Leimuel Aganos](https://linkedin.com/in/yourusername)

---

## 🙏 Acknowledgments

- Exelpack Corporation for the opportunity to develop these systems
- The IT team for their continuous support and feedback
- All end-users who provided valuable input during development

---

## 📊 Project Statistics

- **Total Projects**: 4 major systems
- **Lines of Code**: 50,000+
- **Development Time**: 3 years (2021-2024)
- **Active Users**: 30+ concurrent users
- **Uptime**: 99.5%
- **Performance Improvement**: 60% average across all systems

---

## 🔮 Future Enhancements

### Planned Features

- [ ] Mobile applications for iOS and Android
- [ ] Advanced analytics with AI/ML predictions
- [ ] Integration with SAP/ERP systems
- [ ] Cloud deployment (AWS/Azure)
- [ ] API documentation with Swagger
- [ ] Automated testing suite
- [ ] Docker containerization
- [ ] CI/CD pipeline setup

---

## 📚 Documentation

For detailed documentation on each system:

- [eSign System Documentation](./docs/esign.md)
- [DPMS Documentation](./docs/dpms.md)
- [Production Planning Documentation](./docs/planning.md)
- [EMMCRMS Documentation](./docs/emmcrms.md)

---

## ⚠️ Troubleshooting

### Common Issues

**Issue**: Cannot connect to database
```bash
# Solution: Check your PostgreSQL service
sudo service postgresql status
sudo service postgresql start
```

**Issue**: Port already in use
```bash
# Solution: Kill the process using the port
lsof -ti:5000 | xargs kill -9
```

**Issue**: npm install fails
```bash
# Solution: Clear npm cache and reinstall
npm cache clean --force
rm -rf node_modules package-lock.json
npm install
```

---

## 🎯 Development Roadmap

### Q1 2025
- [ ] Implement automated testing
- [ ] Add dark mode support
- [ ] Improve mobile responsiveness

### Q2 2025
- [ ] API rate limiting
- [ ] Enhanced security features
- [ ] Performance optimizations

### Q3 2025
- [ ] Microservices architecture
- [ ] GraphQL API
- [ ] Advanced reporting features

### Q4 2025
- [ ] AI-powered insights
- [ ] Predictive analytics
- [ ] Mobile app launch

---

<div align="center">

**⭐ If you find these projects interesting, please give them a star! ⭐**

Made with ❤️ by Patrick Leimuel Aganos

</div>
