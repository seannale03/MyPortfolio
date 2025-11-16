# My Portfolio
These are the systems and projects I have worked on, showcasing my skills in web development, full-stack applications, database management, and problem-solving. Each project demonstrates my experience in building functional, efficient, and user-friendly solutions.

- ### Barangay Geographical Information System 
- ### Charity First Foundation Inc. - Scholar Information System 
- ### Tracecrusade - Alumni Management System
- ### PLM Integrated Admission System (Law and Medicine) 
- ### PLM Admission Management System (Plmat, Clat, Cmat, and Graduate Schools) 

---


# Barangay Geographical Information System

A comprehensive web-based management system for Barangay 99, Zone 8, District 1 in Tondo, Manila. This system streamlines barangay operations, resident management, and service delivery through an intuitive admin panel.

## 🚀 Features

### 📊 Dashboard & Analytics
- **Population Overview**: Track total population, registered voters, and permanent residents
- **Demographic Data**: Gender distribution and age bracket summaries
- **Employment Statistics**: Monitor employment status across residents
- **Real-time Reports**: Visualize barangay data through comprehensive reporting

### 👥 Resident Management
- **Resident Information**: Complete resident profiles with personal details
- **Record Editing**: Update resident information including contact details and status
- **Categorization**: Filter residents by building, residency status, and voter status

### 📑 Document Services
- **Request Forms**: Generate barangay documents (clearances, certifications)
- **Request Tracker**: Monitor and manage document requests
- **Automated Document Generation**: Create official barangay documents with resident data

### ⚖️ Incident & Complaint System
- **Incident Reporting**: Formal incident documentation with detailed narratives
- **Complaint Management**: Structured complaint filing process
- **Case Tracking**: Monitor incident and complaint resolution status
- **Witness Management**: Record witness information for official cases

### 📢 Communication Tools
- **Announcement System**: Broadcast important information to residents
- **Targeted Messaging**: Send notifications to specific resident groups

### 🚨 Emergency Management
- **Equipment Inventory**: Track emergency response equipment
- **Responder Directory**: Manage emergency response personnel
- **GIS Integration**: Geographic information system for location-based services

## 🛠️ Prerequisites

- **React.js**
- **Node.js**
- **PostgreSQL 16**
- Modern web browser

## ⚡ Installation

1. Clone the repository
2. Configure database connection
3. Import initial database schema
4. Set up admin credentials
5. Deploy to web server

## 🔐 Admin Login

- Access the admin panel at `/admin`
- Use authorized credentials to log in
- Default access restricted to barangay officials

## 📋 System Modules

### 1. Dashboard
- Population statistics
- Employment status overview
- Age distribution analytics
- Quick access to all modules

![Dashboard](https://github.com/user-attachments/assets/ad1a07fd-964e-4f58-9f3c-3a9dfa83859f)

### 2. Resident Information
- Complete resident database
- Search and filter capabilities
- Export functionality (PDF/Excel)
- Profile management

![Resident Information](https://github.com/user-attachments/assets/2a9606f2-23e7-4b8f-ac5c-fe6d4bee6905)

### 3. Request Management
- Document request processing
- Status tracking
- Automated clearance generation
- Purpose-based document issuance

![Request Management 1](https://github.com/user-attachments/assets/823bdf40-b91a-45b7-9dcb-1e9b7845c10a)
![Request Management 2](https://github.com/user-attachments/assets/64706791-82c8-4883-a4aa-7bda4df1809a)

### 4. Announcements
- Broadcast messaging
- Resident notifications
- Historical announcement tracking

![Announcements](https://github.com/user-attachments/assets/b65e046e-3391-4619-9a5d-06334d155991)

### 5. Incident & Complaints
- Formal reporting system
- Case management
- Progress tracking
- Official documentation

![Incident & Complaints 1](https://github.com/user-attachments/assets/21d41983-63e9-428a-a2e4-43fa14d52640)
![Incident & Complaints 2](https://github.com/user-attachments/assets/0114be29-3533-4ad0-b724-bb9027e06ea0)
![Incident & Complaints 3](https://github.com/user-attachments/assets/d2ad549f-9318-430a-aef8-d536963b38ae)
![Incident & Complaints 4](https://github.com/user-attachments/assets/7f7bdf4e-6135-4724-bf77-75034ca15634)

### 6. GIS Integration
- Location-based services
- Spatial data management
- Mapping capabilities

![GIS Integration](https://github.com/user-attachments/assets/f82089a1-b9bf-4b00-a123-f118fa091ac1)

## 🔧 Technical Features

- **Responsive Design**: Works on desktop and mobile devices
- **Secure Authentication**: Role-based access control
- **Data Export**: PDF and Excel reporting
- **Search Functionality**: Advanced resident search
- **Form Validation**: Client and server-side validation
- **Session Management**: JWT Secure user sessions

## 💾 Data Management

- Resident demographics tracking
- Document request history
- Incident and complaint records
- Announcement archives
- Emergency equipment inventory

## 👨‍💼 Admin Capabilities

- Manage resident records
- Process document requests
- Handle incidents and complaints
- Send official announcements
- Generate statistical reports
- Monitor barangay operations

## 📄 License

This system was developed for my thesis and was awarded the Best Presenter award at ICICyTA 2024.

---

**Barangay 99, Zone 8, District 1 | Tondo, Manila**  
*Empowering community management through technology*


---


# PLM Admission Management System

A comprehensive web-based admission platform for Pamantasan ng Lungsod ng Maynila (PLM). This system streamlines application processing across multiple programs with AI-powered document validation, secure applicant workflows, and role-based access management.

## 🚀 Features

### 🎓 Multi-Program Admission Support
- **CMAT**: College of Medicine Admission Test
- **CLAT**: College of Law Admission Test
- **PLMAT**: PLM Admission Test
- **Graduate Programs**: Advanced studies admission
- **Program-Specific Requirements**: Dynamic forms and document sets per program

<img width="1906" height="953" alt="image" src="https://github.com/user-attachments/assets/27aa044f-e34d-49b4-9c24-8df182acff4b" />

### 👥 Role-Based Access Control
- **Applicant Portal**: Application submission, document upload, and status tracking
- **Admin Dashboard**: Review and validate applications
- **Role-Specific Interfaces**: UI varies based on user privileges

<img width="1906" height="954" alt="image" src="https://github.com/user-attachments/assets/12ebc9a1-bc13-408f-9a71-81fa16bd82fe" />

<img width="1907" height="953" alt="image" src="https://github.com/user-attachments/assets/ba51cab1-fc67-4f20-adbc-9f59af1868b4" />

### 📄 Document Management & Validation
- Secure file uploads (PDF, PNG, JPG)
- AI-powered verification (CNN + Levenshtein algorithm)
- Fraud detection for manipulated documents
- Real-time document status (Pending / Verified / Rejected)

### 🤖 AI Integration
- CMAT AI Assistant: OpenAI-powered chatbot for applicant support
- Smart document analysis for credentials verification
- AI-assisted review for administrators

### 📊 Application Tracking & Reporting
- Real-time application progress
- Exportable reports (PDF, Excel, CSV)
- Admin analytics dashboard
- Document authenticity summaries

### 📧 Communication System
- Automated email notifications
- Google SMTP integration
- Application reminders and status alerts

## 🔐 Admin & User Access

### Applicant Access
- Register an account
- Submit applications
- Upload required documents
- Track application status
- AI-assisted support

### Admin Access
- Review and validate applications
- Generate reports
- Monitor analytics
- Manage user accounts

## 📋 System Modules

### 1. Application Dashboard
- Real-time application status
- Document submission tracker
- Application history
- Personal information management
  
<img width="1906" height="952" alt="image" src="https://github.com/user-attachments/assets/620253a5-9101-4a93-9eb9-035f7214b54c" />

### 2. Document Management
- Multi-file upload
- Document verification summary
- Authenticity scoring
- Submission monitoring

<img width="1908" height="951" alt="image" src="https://github.com/user-attachments/assets/ffc43788-88c1-4f77-874c-636dcff45e22" />

### 3. Admin Panel
- Application filtering and search
- Document review & verification
- Bulk operations
- User management

<img width="1920" height="953" alt="image" src="https://github.com/user-attachments/assets/c93ada62-d608-498e-b280-ae58b9776ee3" />

### 4. AI Assistant
- Real-time applicant support
- Explanation of requirements
- Status inquiries
- Intelligent chatbot guidance

<img width="958" height="570" alt="image" src="https://github.com/user-attachments/assets/11c06cfa-42f7-456b-9088-2c510889d95e" />

### 5. Reporting & Analytics
- PDF and Excel report generation
- Application statistics
- Validation summaries
- Dashboard insights

<img width="958" height="570" alt="image" src="https://github.com/user-attachments/assets/077b17cf-ecc0-41fe-9989-912e437fb9d1" />

### 6. Document Validation System
- Automated AI-based document checking
- Manual review interface
- Confidence scoring
- Flagging suspicious uploads

<img width="785" height="927" alt="image" src="https://github.com/user-attachments/assets/84add5c9-6399-4053-aad5-b87d4094f12d" />

## 🔧 Technical Features
- Responsive design for desktop and mobile
- Secure authentication and role-based access control
- PDF/Excel reporting
- Advanced search functionality
- Client and server-side validation
- JWT session management

## 💾 Data Management
- Applicant records
- Document submission history
- Validation results and summaries
- Communication logs

## 👨‍💼 Admin Capabilities
- Manage applications
- Validate documents
- Generate reports and analytics
- Monitor system usage
- AI-assisted document review

## 📄 License
This system was developed for internship as Programmer Intern at Information and Communications Technology Office - Pamantasan ng Lungsod ng Maynila.

---

**Pamantasan ng Lungsod ng Maynila | Manila, Philippines**  
*Streamlining admissions through technology*


---


# Charity First Foundation Inc. - Scholar Information System

*A comprehensive scholarship management system built with modern web technologies*

## 🎯 Overview

The Charity First Foundation Inc. Scholar Information System is a robust platform designed to manage the entire scholarship lifecycle - from application to alumni tracking. The system incorporates AI-powered document verification and predictive analytics to enhance efficiency and decision-making processes.

## 🚀 Features

### 📋 Three Main Modules

#### 1. **Applicant/Application Module**
- **Online Application Portal**: Complete digital scholarship application process
- **Document Upload & Management**: Secure file upload with validation
- **OCR Document Verification**: Automated document processing using Google Vision API
- **Application Status Tracking**: Real-time application progress monitoring
- **Requirements Checklist**: Guided document submission process

<img width="1341" height="703" alt="image" src="https://github.com/user-attachments/assets/73439c62-684d-4e6c-8a22-4659ad1488ee" />

<img width="1586" height="827" alt="image" src="https://github.com/user-attachments/assets/960fe82d-cefc-4255-bd4b-a71f043f7d89" />

<img width="613" height="846" alt="image" src="https://github.com/user-attachments/assets/c971cd29-572b-4881-9f8a-62baae355616" />

<img width="884" height="840" alt="image" src="https://github.com/user-attachments/assets/76f9783e-4535-4bcb-86a6-4668ff19f6f9" />

<img width="1296" height="697" alt="image" src="https://github.com/user-attachments/assets/464a8220-7985-45af-9e40-919016775ea4" />

#### 2. **Scholar Side Module**
- **Personal Dashboard**: Scholar profile and academic overview
- **Violation Tracking**: Record and monitor scholar infractions
- **Community Service Log**: Track and manage service hours
- **Consultation Forms**: Semestral academic consultation
- **Grade Submission**: Automated grade reporting and validation
- **Password Management**: Secure account management

<img width="1311" height="685" alt="image" src="https://github.com/user-attachments/assets/657f7ce6-ad8f-48a6-9075-97e2c193c1f0" />

<img width="1136" height="601" alt="image" src="https://github.com/user-attachments/assets/518f95f8-af8d-400c-af7f-daaa0537d848" />

<img width="894" height="472" alt="image" src="https://github.com/user-attachments/assets/660ad38b-56b8-4e49-b87e-8c27a2514443" />

<img width="1133" height="590" alt="image" src="https://github.com/user-attachments/assets/340ee5f5-5390-45ad-88c5-41b1027281b7" />

<img width="1339" height="703" alt="image" src="https://github.com/user-attachments/assets/27dbe1af-9d4e-45eb-9d84-6c27fcc4bb36" />

#### 3. **Admin Side Module**
- **Application Review**: Comprehensive applicant evaluation
- **Scholar Management**: Complete scholar lifecycle management
- **Analytics Dashboard**: Population statistics and course summaries
- **Violation Monitoring**: Track and manage scholar compliance
- **Report Generation**: Export data to PDF and Excel formats
- **User Management**: Admin and scholar account administration

<img width="1129" height="602" alt="image" src="https://github.com/user-attachments/assets/98bf3f43-b6df-4c8c-a698-a49cb6fe9ad8" />

<img width="1339" height="703" alt="image" src="https://github.com/user-attachments/assets/6d7b97ad-d07a-4213-a278-ffec07ab370e" />

<img width="1309" height="692" alt="image" src="https://github.com/user-attachments/assets/7884be38-e5ce-46c1-beeb-643f4bc6d16d" />

<img width="1342" height="700" alt="image" src="https://github.com/user-attachments/assets/6c233d42-de41-457b-8f8b-80e8a764323b" />

<img width="1462" height="739" alt="image" src="https://github.com/user-attachments/assets/a076e8cf-d2a7-42ca-9b5b-e84d45cd7e39" />

<img width="1465" height="701" alt="image" src="https://github.com/user-attachments/assets/ae0883b1-8010-4ad6-be30-5d0a3b93057c" />

<img width="1213" height="808" alt="image" src="https://github.com/user-attachments/assets/3f68cd0f-83d6-4a0e-bcbd-a3731076a3b0" />

## 🛠️ Technology Stack

### Frontend
- **React.js** - Modern, component-based UI framework
- **CSS3 & Styled Components** - Responsive and modern UI design
- **State Management** - Context API and React Hooks
- **Form Handling** - Advanced form validation and management

### Backend
- **Node.js** - Scalable server-side runtime
- **Express.js** - Web application framework
- **RESTful APIs** - Structured API architecture
- **JWT Authentication** - Secure token-based authentication

### Database
- **PostgreSQL** - Robust relational database management
- **Advanced Queries** - Complex data relationships and reporting
- **Data Integrity** - ACID compliance and transactions

### AI & Machine Learning
- **Google Vision OCR** - Automated document processing and verification
- **Logistic Regression Algorithm** - Predictive analytics for applicant evaluation
- **Data Analytics** - Scholarship performance and retention predictions

### This is a CLIENT-BASED system developed for Charity First Foundation Inc. to streamline their scholarship management operations and enhance their service delivery to scholars and applicants.

## 🔧 System Architecture

```mermaid
graph TB
    A[Frontend - React.js] --> B[Backend - Node.js/Express]
    B --> C[Database - PostgreSQL]
    B --> D[Google Vision API]
    B --> E[ML Model - Logistic Regression]
    F[Admin Users] --> A
    G[Scholars] --> A
    H[Applicants] --> A
```

---


# Tracecrusade - Alumni Management System

A comprehensive web-based alumni management system for Sacred Heart of Jesus Catholic School, designed to track and manage alumni information with secure authentication and dynamic content management.

## 🚀 Features

### 🔐 Secure Authentication System
- **Admin Login** with CAPTCHA verification
- Secure session management
- Role-based access control

### 📊 Alumni Information Management
- Complete alumni profiles with personal and academic details
- Advanced search and filtering capabilities
- Alumni data categorization by:
  - Present Location
  - Academic Strand
  - Employment Sector
  - Type of Employment

### 🖼️ Slideshow Management
- Dynamic image upload and management
- Frontend slideshow display
- Easy content rotation and updates
- Responsive image handling

### 📈 Dashboard Analytics
- Comprehensive alumni overview
- Statistical data presentation
- Quick access to management features

## 🛠️ Technology Stack

### Backend
- **PHP** - Server-side scripting
- **MySQL** - Database management
- **phpMyAdmin** - Database administration

### Frontend
- **HTML5** - Markup language
- **CSS3** - Styling and layout
- **JavaScript** - Client-side functionality
- **Responsive Design** - Mobile-friendly interface

### Security Features
- **CAPTCHA Integration** - Bot prevention
- **Secure Sessions** - User authentication
- **Input Validation** - Data integrity
- **SQL Injection Protection** - Database security

<img width="1920" height="951" alt="image" src="https://github.com/user-attachments/assets/2381f1fd-9d73-4e56-ac2f-e1f49145b362" />

## 📋 System Modules

### 1. Alumni Management
- Complete alumni database
- Advanced search functionality
- Filter by location, strand, sector, and employment
- Export capabilities

<img width="1920" height="952" alt="image" src="https://github.com/user-attachments/assets/341f65b9-7490-4d2c-84f3-6e85d33f7fdc" />

<img width="1904" height="948" alt="image" src="https://github.com/user-attachments/assets/f9b5e4b9-a39e-4e28-8209-fe7aa55f833d" />

### 2. Slideshow Management
- Image upload and organization
- Display order management
- Frontend presentation control
- Content rotation settings
  
<img width="1920" height="954" alt="image" src="https://github.com/user-attachments/assets/6d755b3e-beff-4d90-8bca-42697023a4f5" />

<img width="1920" height="953" alt="image" src="https://github.com/user-attachments/assets/fa2dd367-824f-404f-b6f5-f5da51df8d20" />

## 💾 Database Structure

### Main Tables
- `admin_users` - Administrator accounts
- `alumni` - Alumni personal and academic information
- `slideshow` - Image management for frontend display
- `sessions` - User session management

### Alumni Data Fields
- Email Address
- Personal Details (First Name, Middle Name, Last Name)
- Contact Information
- Present Location and Address
- Academic Strand
- Years of Enrollment
- Extracurricular Activities
- Employment Information

## ⚡ Installation & Setup

### Prerequisites
- Web server with PHP support (Apache)
- MySQL database
- phpMyAdmin for database management

## 🔐 Admin Access

### Login Details
- **Security**: CAPTCHA-protected login
- **Features**: Role-based access to all management functions

## 🌐 Live Deployment

The system is currently deployed and accessible at:  
**https://tracedcrusade.com/LandingPage.php**

### Deployment Features
- **Production Environment** with optimized performance
- **Secure HTTPS** connection
- **Regular Backups** of alumni data
- **Mobile Responsive** design
- **Cross-browser Compatibility**

## 📊 Data Management

### Alumni Information Tracking
- Personal contact details
- Academic history and achievements
- Career and employment data
- Location and demographic information

### Slideshow Content
- Dynamic image rotation
- Easy content updates
- Multiple image format support
- Optimized loading performance

## 🔒 Security Measures

- **CAPTCHA Protection** on login forms
- **Password Encryption** using secure hashing
- **SQL Injection Prevention** through prepared statements
- **XSS Protection** with input sanitization

## 📄 License

This system was developed for Sacred Heart of Jesus Catholic School to efficiently manage alumni relationships and school communications.

Additionally, this is a commission-based system made for SHJCS Students.


