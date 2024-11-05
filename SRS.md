## Promise of Inspiration

The iDiscover Project endeavors to harmoniously merge creativity and technology, fostering innovative solutions that inspire exploration and learning. We firmly believe in the power of collaboration and the potential of every idea to bring about a meaningful impact.

### Goals

1. **User-Centric Design:** Develop an application that prioritizes user experience and intuitive navigation.
2. **Sustainable Practices:** Incorporate eco-friendly practices in project development and operations.
3. **Collaborative Innovation:** Partner with creative minds and organizations to enhance the project's offerings.

### Get Involved

Join our mission to inspire and explore! Whether you're a developer, designer, or enthusiast, there are numerous ways to contribute to the iDiscover APP.

- **Collaborate:** Work with us on exciting projects.
- **Share Ideas:** Contribute your thoughts and suggestions.
- **Follow Our Journey:** Stay updated on our progress and upcoming events.


# Software Requirements Specification (SRS)

## Table of Contents

1. [Introduction](#1-introduction)
2. [Purpose](#2-Purpose)
3. [Scope](#3-Scope)
4. [Definitions, Acronyms, and Abbreviations](#4-Definitions-Acronyms-and-Abbreviations)
5. [References](#5-References)
6. [Overview](#6-Overview)
7. [Overall Description](#7-Overall-Description)
8. [Vision](#8-Vision)
9. [Use Case Diagram](#9-Use-Case-Diagram)
10. [Technology Stack](#10-Technology-Stack)
11. [Specific Requirements](#11-Specific-Requirements)
 

    11.1 [Functionality](#111-Functionality)

    11.2 [Usability](#112-Usability)

    11.3 [Reliability](#113-Reliability)

    11.4 [Performance](#114-Performance)

    11.5 [Supportability](#115-Supportability)
    
12. [Design Constraints](#12-Design-Constraints)
13. [Online User Documentation and Help System Requirements](#13-Online-User-Documentation-and-Help-System-Requirements)
14. [Purchased Components](#14-Purchased-Components)
15. [Interfaces](#15-Interfaces)
16. [Licensing Requirements](#16-Licensing-Requirements)
17. [Legal, Copyright, and Other Notices](#17-Legal-Copyright-and-Other-Notices)
18. [Applicable Standards](#18-Applicable-Standards)
19. [Supporting Information](#19-Supporting-Information)

## 1. Introduction
This document provides a detailed Software Requirements Specification (SRS) for the development of a mobile application designed to offer users a seamless experience with three main modes: FLOW, PLAN, and FUN.

## 2. Purpose
The purpose of this document is to outline the requirements for the mobile application, ensuring a clear understanding of its functionalities and constraints.

## 3. Scope
This application will allow users to explore their current location, plan trips, and engage in fun activities. It will include features such as interactive maps, social media integration, and personalized recommendations.

## 4. Definitions, Acronyms, and Abbreviations
- **SRS**: Software Requirements Specification
- **GPS**: Global Positioning System
- **UI**: User Interface
- **API**: Application Programming Interface

## 5. References
- User feedback and requirements
- Industry standards for mobile application development

## 6. Overview
This document is structured to provide a comprehensive understanding of the mobile application's requirements, including functional and non-functional aspects.

## 7. Overall Description

### Product Perspective
The app is a standalone mobile application available on both iOS and Android platforms. It will integrate with various external services such as social media platforms, GPS, and public transport APIs.

### Product Functions
- **FLOW Mode**: Allows users to explore their current location with an interactive map, set durations, specify activities, and connect with friends.
- **PLAN Mode**: Enables users to plan trips, select dates and times, choose activities, and make reservations.
- **FUN Mode**: Provides a treasure hunt experience, touristic mode, and learning options with rewards for achievements.

### User Classes and Characteristics
- **Primary User**: General users who want to explore, plan, and engage in activities.
- **Secondary User**: Admins who manage content, users, and settings.

### Operating Environment
The app will operate on mobile devices running iOS and Android operating systems.

### Design and Implementation Constraints
- Compliance with data protection regulations (e.g., GDPR)
- Integration with third-party services and APIs

### Assumptions and Dependencies
- Users have access to mobile devices with internet connectivity.
- Availability of third-party services and APIs.

## 8. Vision
To create a mobile application that provides users with a seamless and engaging experience for exploring, planning, and participating in activities.

## 9. Use Case Diagram
![UCD drawio](https://github.com/NiKu-24/Deneme-IDiscover/blob/main/assets/UCD.drawio.png)

## 10. Technology Stack
- **Frontend**: React Native
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **APIs**: Integration with social media platforms, GPS, and public transport APIs

## 11. Specific Requirements

### 11.1. Functionality
1. **User Profile Management**
   - Users can create and manage their profiles, including setting user names, passwords, emails, avatars, notification settings, and preferences.

2. **Location and Mode Selection**
   - Users can select their current location and choose between FLOW, PLAN, and FUN modes.

3. **FLOW Mode**
   - Users can specify activities, set durations, choose transportation, and view road alternatives.
   - Users can see who is around them, read feedback, send messages, and receive notifications about benefits.

4. **PLAN Mode**
   - Users can set time and duration, specify activities, choose program alternatives, make changes, fix programs, see event options, buy passes and tickets, and make reservations.

5. **FUN Mode**
   - Users can specify activities, set durations, choose transportation, select road alternatives, choose levels, engage in touristic and learning modes, participate in treasure hunts, share achievements and photos, earn points and badges, and receive free gifts.

6. **Admin Functions**
   - Admins can manage users, update content, view analytics, and configure settings.

### 11.2. Usability
- The app should have an intuitive and user-friendly interface.
- Provide accessibility features for users with disabilities.

### 11.3 Reliability
- The app should have 99.9% uptime.
- Implement regular backups of user data.

### 11.4 Performance
- The app should load within 3 seconds.
- The app should handle up to 10,000 concurrent users.

### 11.5 Supportability
- The app should be modular to facilitate updates and maintenance.
- Provide comprehensive documentation for developers.

## 12. Design Constraints
- Compliance with data protection regulations (e.g., GDPR)
- Integration with third-party services and APIs

## 13. Online User Documentation and Help System Requirements
- Provide detailed user guides and FAQs.
- Include in-app help and support features.

## 14. Purchased Components
- Integration with third-party APIs and services as required.

## 15. Interfaces

### User Interfaces
- **Profile Management UI**: Interface for users to manage their profiles.
- **Mode Selection UI**: Interface for selecting location and mode.
- **FLOW Mode UI**: Interface for exploring locations and activities.
- **PLAN Mode UI**: Interface for planning trips and activities.
- **FUN Mode UI**: Interface for engaging in fun activities and treasure hunts.
- **Admin UI**: Interface for administrative functions.

### Hardware Interfaces
- **Mobile Devices**: The app will run on iOS and Android mobile devices.

### Software Interfaces
- **APIs**: Integration with social media platforms, GPS, and public transport APIs.

### Communications Interfaces
- **Internet Connectivity**: The app requires internet connectivity for most features.

## 16. Licensing Requirements
- Ensure compliance with all relevant software licenses for third-party components.

## 17. Legal, Copyright, and Other Notices
- Include all necessary legal disclaimers and copyright notices.

## 18. Applicable Standards
- Adhere to industry standards for mobile application development and data protection.

## 19. Supporting Information
- Additional information and resources to support the development and maintenance of the application.
