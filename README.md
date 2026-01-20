# Electric Bus Location Tracker

A real-time tracking system for electric buses in Mianwali, Pakistan, enabling passengers to track bus locations, view estimated arrival times, and manage routes efficiently.

## Overview

The Electric Bus Location Tracker is a comprehensive mobile application developed as part of a Software Engineering project at Namal University. The system provides real-time GPS tracking, duty management for drivers, and administrative monitoring tools while ensuring low latency, scalability, and security.

## Features

### For Passengers
- Real-time bus location tracking on interactive maps
- Estimated arrival time (ETA) calculations
- Route search and exploration
- Favorite routes management
- Live bus status updates

### For Drivers
- Duty assignment viewing and management
- Trip start/end functionality
- Continuous GPS location sharing during active duty
- Route and schedule information

### For Administrators
- Comprehensive bus fleet monitoring
- Driver and duty assignment management
- System analytics and reporting
- User management and oversight

## Technology Stack

**Frontend**
- Flutter (Cross-platform mobile development)
- Google Maps SDK (Map visualization)
- Socket.io Client (Real-time updates)

**Backend**
- Node.js (Server-side runtime)
- WebSockets (Real-time communication)
- JWT (Authentication and authorization)

**Database**
- MongoDB (Persistent data storage)
- Redis (Real-time location caching)

**External Services**
- Google Maps API (Routing and map services)
- GPS System (Location tracking)

## System Architecture

The application follows a **three-tier modular architecture**:

1. **Presentation Tier**: Flutter mobile application
2. **Business Logic Tier**: Node.js backend services (Authentication, Tracking, Route Management, Duty Management)
3. **Data Access Tier**: MongoDB and Redis with unified repository interface

## System Requirements

### Mobile Application
- Android 8.0 (Oreo) or above
- Working GPS capability
- Internet connectivity (minimum 256 kbps bandwidth)
- GPS accuracy within 10 meters

### Performance Specifications
- Battery usage limited to 5% per hour
- Low-latency real-time updates
- Scalable architecture for future expansion

## Design Assumptions

- All smartphones have functional GPS and stable internet connectivity
- Punjab Mass Authority (PMA) provides accurate route and bus data
- Google Maps API availability for map services
- Drivers maintain continuous location sharing during active duty

## Compliance

The system complies with the **Pakistan Personal Data Protection Bill** to ensure user privacy and data security.

## Project Team

**Namal University, Mianwali**  
Department of Computer Science

- **Mehroz Ali Khan** - NUM-BSCS-2024-34
- **Ali Abbas** - NUM-BSCS-2024-06
- **Laiba Taj** - NUM-BSCS-2024-31

## Documentation

For detailed system design documentation, including:
- Data Flow Diagrams (DFD Level 0, 1, 2)
- Activity Diagrams (Passenger, Driver, Admin workflows)
- Sequence Diagrams (Authentication, Real-time Tracking)
- Class Diagrams (Management and Information Providing)
- Component Diagrams (Client and Server architecture)
- Use Case Diagrams

### Design & Planning
- **Figma Design**: [View Prototype](https://www.figma.com/design/BoCShru8p7isvqPn427vHa/Untitled?node-id=13-6881&t=kgQ1WCa5wS2Oaihv-1)
- **Google Sheet**: [Project meeting minutes](https://docs.google.com/spreadsheets/d/1WLF0wPuELaKaJ0VSwRVZz3amFrkmuQfmRevP1YjB1oU/edit?usp=drivesdk)
 
## Installation & Setup

```

# Clone the repository
git clone https://github.com/Mehrozalikhan01/Electric-buses-location-tracker.git

# Navigate to project directory
cd Electric-buses-location-tracker

# Install dependencies
# (Add specific installation commands based on your setup)
```

## Contributing

This is an academic project developed for Software Engineering coursework. For suggestions or improvements, please open an issue or submit a pull request.

## License

This project is developed as part of academic coursework at Namal University.

## Acknowledgments

- Namal University, Department of Computer Science
- Punjab Mass Authority (PMA) for route data support
- Google Maps Platform for mapping services

