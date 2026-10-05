Curriculum Management System

A web-based Curriculum Management System developed to simplify, digitize, and manage academic curriculum and syllabus-related processes within an educational institution.

This project provides a centralized platform for managing curriculum structures, schemes, courses, electives, syllabus information, booklet generation, dashboards, and academic workflows.

«My Contribution: I worked on the development of this project as part of the team, with a primary focus on Laravel/PHP full-stack development, backend functionality, database integration, curriculum workflows, and UI implementation.»

---

📌 Overview

Managing academic curriculum manually can involve multiple documents, spreadsheets, approvals, and disconnected workflows.

The Curriculum Management System aims to provide a structured digital platform where curriculum-related information can be created, updated, reviewed, and managed from a centralized system.

The application includes dedicated modules for curriculum and scheme management, elective management, syllabus management, dashboards, academic progress tracking, and booklet generation.

---

🚀 Key Features

Curriculum & CDC Management

- Dynamic curriculum and CDC structure management
- Curriculum scheme definition and modification
- Course and subject management
- Curriculum structure organization
- CDC and elective pool integration
- Dynamic scheme selection

Elective Management

- Elective pool management
- CDC-to-elective-pool selection
- Dynamic elective allocation
- Structured elective subject management

Syllabus & Scheme Management

- Syllabus structure management
- Scheme definition and modification
- Academic scheme organization
- Syllabus-related administrative workflows

📄 Booklet Generation

- Automated curriculum/scheme booklet generation
- Structured academic information
- Improved booklet preparation workflow
- Document/report generation support

📊 Dashboards

- Role-based dashboard structure
- Academic progress tracking
- Workflow and pipeline tracking
- Centralized curriculum activity overview

---

🏗️ System Architecture

                    ┌──────────────────────────┐
                    │       Web Interface       │
                    │    Blade / JavaScript     │
                    └────────────┬─────────────┘
                                 │
                                 ▼
                    ┌──────────────────────────┐
                    │    Laravel Application    │
                    │                          │
                    │ Controllers              │
                    │ Services                 │
                    │ Models                   │
                    │ Routes                   │
                    └────────────┬─────────────┘
                                 │
                ┌────────────────┴────────────────┐
                ▼                                 ▼
       ┌──────────────────┐              ┌──────────────────┐
       │    Database      │              │ File Generation  │
       │                  │              │                  │
       │ Curriculum       │              │ Booklets         │
       │ Schemes          │              │ Documents        │
       │ Courses          │              │ Reports          │
       │ Electives        │              │                  │
       └──────────────────┘              └──────────────────┘

---

🛠️ Technology Stack

Layer| Technology
Backend| PHP / Laravel
Frontend| Blade, JavaScript, CSS
Database| MySQL / Relational Database
Package Manager| Composer
Frontend Build Tool| Vite
Testing| PHPUnit
Version Control| Git / GitHub

---

📂 Project Structure

Curriculum-Management-system/
│
├── app/
│   ├── Http/
│   ├── Models/
│   └── Services/
│
├── bootstrap/
├── config/
├── database/
│   ├── migrations/
│   └── seeders/
│
├── public/
├── resources/
│   ├── views/
│   ├── css/
│   └── js/
│
├── routes/
├── storage/
├── tests/
│
├── artisan
├── composer.json
├── package.json
└── vite.config.js

---

👨‍💻 My Contribution

I contributed to the development of this project as a Laravel/PHP Full-Stack Developer.

My work includes:

- Developing backend functionality using Laravel and PHP
- Working with Laravel MVC architecture
- Creating and modifying controllers, models, routes, and services
- Working with database structures and relationships
- Implementing curriculum and scheme-related workflows
- Working on elective pool functionality
- Developing and integrating Blade-based interfaces
- Implementing frontend functionality using JavaScript
- Working with dynamic forms and academic data
- Debugging and improving application functionality
- Working with Git and GitHub for version control
- Contributing to booklet/document generation functionality

---

⚙️ Installation

Prerequisites

Make sure the following are installed:

- PHP 8.3+
- Composer
- Node.js and npm
- MySQL or another supported relational database
- Git

Clone the Repository

git clone <YOUR-FORK-REPOSITORY-URL>
cd Curriculum-Management-system

Install PHP Dependencies

composer install

Install Frontend Dependencies

npm install

Environment Configuration

Copy the example environment file:

cp .env.example .env

On Windows, copy ".env.example" manually and rename it to ".env".

Configure the database credentials inside ".env".

Generate the Laravel application key:

php artisan key:generate

Database Setup

Run migrations:

php artisan migrate

If seed data is required:

php artisan db:seed

Build Frontend Assets

For development:

npm run dev

For production:

npm run build

Start the Application

php artisan serve

The application will normally be available at:

http://127.0.0.1:8000

---

🔄 Development Workflow

Requirement
     ↓
Curriculum / Scheme Design
     ↓
Database Structure
     ↓
Backend Development
     ↓
Dashboard / UI Development
     ↓
Testing & Debugging
     ↓
Booklet / Document Generation
     ↓
Academic Review

---

🎯 Project Goals

The main objectives of the system are to:

- Digitize curriculum management workflows
- Reduce manual curriculum-related work
- Centralize academic curriculum information
- Improve scheme and syllabus management
- Simplify elective management
- Improve visibility through dashboards
- Support automated academic document generation
- Provide a structured platform for future ERP integration

---

🔮 Future Scope

Potential future enhancements include:

- Institutional ERP/UMS integration
- Advanced role-based access control
- Curriculum approval workflows
- Curriculum scheme version control
- Advanced academic analytics
- Notification and communication systems
- Advanced reporting
- API integration with other academic systems
- Audit logs for curriculum modifications

---

📌 Project Status

Active Development

Current development areas include:

- Curriculum/CDC workflows
- Dynamic scheme management
- Elective pool integration
- Dashboard functionality
- Academic progress tracking
- Booklet generation

---

🤝 Team Project

This project was developed collaboratively.

The original project repository was maintained by Rushikesh Hake, and I contributed to the development and implementation of various modules.

---

👤 Contributor

Atharva Darade

Computer Engineering Student | Laravel / PHP Full-Stack Developer

- Laravel
- PHP
- MySQL
- Blade
- JavaScript
- Git & GitHub

---

📄 License

This project is developed for academic and institutional use.