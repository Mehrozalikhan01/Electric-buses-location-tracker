# 🚌 Electric Bus Location Tracker App

> Real-time GPS tracking and management system for electric buses in Mianwali District, Punjab, Pakistan

---

## 📋 Project Overview

The **Electric Bus Location Tracker App** is a comprehensive mobile-based software system designed to revolutionize public transportation in Mianwali by providing real-time tracking and management capabilities for electric buses introduced by the Government of Punjab.

### 🎯 Key Features

- 🗺️ **Real-time Bus Tracking** - Live GPS location of all buses on interactive map
- ⏱️ **Estimated Arrival Time (EAT)** - Accurate predictions for bus arrivals at stops
- 🔍 **Route Search** - Find routes by name or bus stop
- ⭐ **Favorite Routes** - Save frequently used routes for quick access
- 📅 **Driver Duty Management** - Monthly schedule and duty tracking for drivers
- 📊 **Administrative Dashboard** - Complete bus fleet monitoring and management
- 📈 **Reports & Analytics** - Daily, weekly, and monthly operational reports

---

## 👥 Team Members

| Name | Roll Number | Email | Role |
|------|-------------|-------|------|
| **Ali Abbas** | NUM-BSCS-2024-06 | bscs24f06@namal.edu.pk | Team Lead |
| **Laiba Tajj** | NUM-BSCS-2024-31 | bscs24f31@namal.edu.pk | Developer |
| **Mehroz Ali Khan** | NUM-BSCS-2024-34 | bscs24f34@namal.edu.pk | Developer |

### 📍 Institution
**Namal University, Mianwali**  
Department of Computer Science  
Course: CSC-225 – Software Engineering

### 🤝 Stakeholder
**Asiya Batool** (Requirement Provider)  
Email: asia.batool@namal.edu.pk

---

## 🎓 Academic Project Information

This project is part of the **Software Engineering** course requirement, following a structured Software Development Life Cycle (SDLC):

### Project Milestones

| Milestone | Phase | Status | Deadline |
|-----------|-------|--------|----------|
| **Milestone 1** | Project Proposal | ✅ Completed | Nov 09, 2025 |
| **Milestone 2** | Software Requirements Specification (SRS) | ✅ Completed | Nov 28, 2025 |
| **Milestone 3** | Software Design Specification (SDS) | ⏳ Upcoming | TBD |
| **Milestone 4** | Software Testing Specification (STS) | ⏳ Upcoming | TBD |
| **Milestone 5** | Project Exhibition | ⏳ Upcoming | TBD |

---

## 🏗️ System Architecture

### Technology Stack

| Component | Technology | Purpose |
|-----------|-----------|---------|
| **Mobile Framework** | Flutter | Cross-platform Android app development |
| **Backend** | Node.js + Express.js | RESTful API and business logic |
| **Database** | MongoDB | Primary data storage |
| **Cache** | Redis | Real-time location data caching |
| **Mapping** | Google Maps API | Maps, routing, and ETA calculation |
| **Real-time Communication** | Socket.io | Live location updates via WebSocket |
| **Cloud Hosting** | AWS (EC2, S3) | Server and file hosting |
| **Authentication** | JWT + bcrypt | Secure user authentication |
| **Version Control** | GitHub | Code repository management |

### System Requirements

- **Android**: 8.0 (API level 26) or above
- **Internet**: Minimum 256 kbps bandwidth
- **GPS**: Enabled for location tracking
- **Storage**: Maximum 100MB app size

---

## 👤 User Roles

### 1. 🧑 Passengers
- View real-time bus locations on map
- Search routes and schedules
- Get estimated arrival times (EAT)
- Save favorite routes
- No authentication required

### 2. 🚗 Drivers (Registered by PMA, Mianwali)
- View monthly duty schedules
- Share live GPS location when on duty
- Mark duty as complete automatically
- View duty completion records
- Requires authentication

### 3. 👨‍💼 Administrators (Registered by PMA, Lahore)
- Monitor all buses in real-time
- Manage routes, schedules, and bus fleet
- Assign drivers to buses and duties
- Generate operational reports (daily/weekly/monthly)
- Manage user accounts
- Requires authentication

---

## 📁 Repository Structure

```
electric-bus-tracker/
├── 📄 README.md                          
├── 📄 LICENSE                           
├── 📁 Documentation/
├── 📁 Meeting Pics/              

---

## 📊 Requirements Summary

### Functional Requirements: 77
- **Authentication & Profile** (FR-001 to FR-009): 9 requirements
- **Passenger Functions** (FR-010 to FR-032): 23 requirements
- **Driver Functions** (FR-033 to FR-048): 16 requirements
- **Administrator Functions** (FR-049 to FR-077): 29 requirements

### Non-Functional Requirements: 69
- **Performance** (NFR-001 to NFR-007): 7 requirements
- **Security** (NFR-008 to NFR-017): 10 requirements
- **Reliability** (NFR-018 to NFR-027): 10 requirements
- **Availability** (NFR-028 to NFR-032): 5 requirements
- **Maintainability** (NFR-033 to NFR-040): 8 requirements
- **Portability** (NFR-041 to NFR-043): 3 requirements
- **Usability** (NFR-044 to NFR-051): 8 requirements
- **Scalability** (NFR-052 to NFR-056): 5 requirements
- **Compatibility** (NFR-057 to NFR-060): 4 requirements
- **Legal & Compliance** (NFR-061 to NFR-066): 6 requirements
- **Environmental** (NFR-067 to NFR-069): 3 requirements

### External Interfaces
- **Hardware Interfaces**: 4
- **Software Interfaces**: 8
- **Communication Interfaces**: 8

---

## 🎨 Design Philosophy

Following **Agile Scrum Methodology** for iterative development:

1. ✅ **Sprint 1**: Requirement gathering and analysis
2. ✅ **Sprint 2**: SRS documentation and validation
3. ⏳ **Sprint 3**: System modeling and UI/UX design
4. ⏳ **Sprint 4**: Prototype development
5. ⏳ **Sprint 5**: Testing and documentation

---

## 📝 Documentation

### Available Documents

1. **Project Proposal** - Defines problem, scope, and objectives
2. **Software Requirements Specification (SRS)** - Complete functional and non-functional requirements following IEEE 830 standard
3. **Use Case Diagram** - System interactions and actors
4. **Context Diagram** - System boundary and external entities
5. **Meeting Minutes** - Records of stakeholder meetings

### Standards Followed

- **IEEE 830-1998**: Software Requirements Specifications



## 🌟 Key Benefits

### For Passengers 🧑
- ⏰ Better time management - know exactly when bus arrives
- 🗺️ Easy route planning and navigation
- 📱 User-friendly mobile interface
- ⭐ Quick access to favorite routes

### For Drivers 🚗
- 📅 Clear monthly duty schedules
- ✅ Automatic duty completion tracking
- 📊 View duty history and records
- 🔐 Secure authentication system

### For Administrators 👨‍💼
- 📡 Real-time fleet monitoring
- 📈 Data-driven decision making
- 📊 Comprehensive reporting and analytics
- 🔧 Easy route and schedule management

### For PMA (Punjab Mass Transit Authority) 🏛️
- 🎯 Improved operational efficiency
- 💰 Reduced waiting times and costs
- 📊 Better resource allocation
- 🌱 Promotes eco-friendly electric transport

---

## 🤝 Collaboration

### Stakeholder Meetings

We maintain regular communication with our requirement provider through:
- ✅ Bi-weekly meetings (minimum 2 per milestone)
- 📝 Detailed meeting minutes documentation
- 🎥 Recorded video sessions
- 📧 Email correspondence for clarifications

### Team Collaboration

- 💬 Daily standups via WhatsApp


## 📜 License

This project is developed as an academic requirement for **Namal University, Mianwali**.  
All rights reserved © 2025

For educational purposes only. Not for commercial use.

---

## 🙏 Acknowledgments

- **Asiya Batool** - Requirement Provider and Project Supervisor
- **Namal University** - Academic support and resources

## 📞 Contact

For queries, suggestions, or collaboration:

**Project Lead**: Mehroz Ali Khan 
📧 Email: bscs24f34@namal.edu.pk  
🏫 Institution: Namal University, Mianwali  
🌐 GitHub: [Electric Bus Tracker Repository](https://github.com/YOUR_USERNAME/electric-bus-tracker)

---

## 📅 Project Timeline

```
November 2025      - Project Proposal & Requirement Gathering
December 2025      - SRS Documentation & Validation
January 2026       - System Design & Architecture
February 2026      - UI/UX Design & Prototyping
March 2026         - Development & Implementation
April 2026         - Testing & Quality Assurance
May 2026           - Final Documentation & Presentation
```

---


**Built with ❤️ by Team Electric Bus Tracker**

Link for our Meeting minutes and dates Google Spread Sheet: https://docs.google.com/spreadsheets/d/1WLF0wPuELaKaJ0VSwRVZz3amFrkmuQfmRevP1YjB1oU/edit?usp=drivesdk
