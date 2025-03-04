
# REV's Grill Point-of-Sales System

## Overview
REV's Grill Point-of-Sales System is an innovative, responsive platform developed specifically for REV's Grill. This system integrates real-time data processing with an intuitive user interface to streamline transactions, manage inventory, and enhance customer service.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Sprint & Scrum Documentation](#sprint--scrum-documentation)
- [License](#license)
- [Contact](#contact)

## Features
- **Real-Time Processing:** Live transaction data is processed instantly.
- **Responsive Design:** The interface adapts seamlessly across devices.
- **Inventory Management:** Dynamic tracking and management of inventory.
- **Supplier & Employee Modules:** Streamlined supplier orders and employee management.
- **Customizable Settings:** Users can adjust accessibility and other UI preferences.
- **Reporting & Analytics:** Detailed reporting for sales, inventory, and trends.

## Technologies Used
- **Frontend:** React, JavaScript, HTML, CSS  
- **Backend:** Node.js, Express  
- **Database:** PostgreSQL  
- **APIs & Authentication:** RESTful APIs, OAuth  
- **Deployment:** Vercel/Heroku  
- **Additional Tools:** Git, Git LFS

## Installation

### Install Dependencies:
For the backend:
```bash
npm install
```
For the frontend (if separate):
```bash
cd client
npm install
```
**Configure Environment Variables:**  
Create a `.env` file based on the provided `.env.example` and set your database connection string, OAuth credentials, and other configuration values.

## Usage

### Development:
Start the backend server:
```bash
npm run dev
```
Start the frontend server (if applicable):
```bash
cd client
npm start
```

### Production:
Build and deploy the application using your preferred deployment platform (e.g., Vercel or Heroku).

## Project Structure
```
REV-s-Grill-Point-of-Sales-System-
├── client/                  # Frontend code (React)
├── server/                  # Backend code (Express, Node.js)
├── database/                # Database schemas and migration files
├── docs/                    # Sprint documentation, meeting notes, and reports
├── README.md                # This file
└── package.json             # Project metadata and dependencies
```

## Sprint & Scrum Documentation
The repository includes detailed documentation on our sprint planning, daily standups, and retrospective meetings. Key highlights include:

### Sprint Meeting Scheduling:
1. **Sprint #1 Planning Meeting:** Sunday 7:00 PM, March 24th, Zachry Engineering Building  
2. **Sprint #1 Standup #1 Meeting:** In Class (Monday)  
3. **Sprint #1 Standup #2 Meeting:** In Class (Tuesday)  
4. **Sprint #1 Standup #3 Meeting:** In Class (Thursday)  
5. **Sprint #1 Retrospective Meeting Agenda**  
6. **Sprint #1 Retrospective Meeting:** Saturday 7:00 PM, March 30th, Zachry Engineering Building

### Meeting Minutes

#### (1) Sprint #1 Planning Meeting Notes
- **Takeaways from Project 2:**
  - Ensure everyone is familiar with both front-end and back-end.
  - Adhere to good version control practices.
  - Plan more rigorously.
- **Main Project Components:**
  - Landing Customer Order, Check Out, Accessibility/Settings, Employee Login, Manager Page (Trends, Supplier Order, Menu Settings, Employees), Cashier Page, Menu Board.
- **Division of Labor:**
  - *Alyan:* Supplier Order, Scrum/PM  
  - *Brandon:* General, Landing, Accessibility  
  - *Keeley:* Employee, Inventory  
  - *Vittoria:* Trends, Menu (Manager)  
  - *Joanne:* Menu Board, Customer  
- **User Stories & Backlog:** Detailed in the project management board.
- **Scheduling:** Agreed on the meeting schedule and set an initial goal to have an MVP by Friday afternoon.

#### (2) Sprint #1 Standup #1 Notes
- **Alyan:** Learned React, HTML, CSS; setting up page architecture.
- **Vittoria:** Worked on React basics; setting up Menu Manager page architecture.
- **Keeley:** Learned about EJS and project setup.
- **Joanne:** Designed screen layout; working on UI.
- **Brandon:** Researched tech stack options.

#### (3) Sprint #1 Standup #2 Notes
- **Alyan:** Continued page architecture; worked on Trends translation from Java to JS.
- **Vittoria:** Set up Menu Manager page architecture; worked on Menu Item management.
- **Keeley:** Worked on Inventory page for manager.
- **Joanne:** Worked on Customer and Cashier Ordering.
- **Brandon:** Finalized tech stack; worked on Accessibility settings and Landing Page.

#### (4) Sprint #1 Standup #3 Notes
- **Alyan:** Continued working on Trends.
- **Vittoria:** Continued Menu Item editing.
- **Keeley:** Finished ingredient screen for manager; assisted others.
- **Joanne:** Completed Ordering Interface implementation.
- **Brandon:** Finished Accessibility and Settings; worked on local caching of accessibility settings.

#### (5) Sprint #1 Retrospective Meeting
- **What Went Well:**
  - Effective role distribution.
  - Good collaboration and knowledge sharing.
  - Smooth deployment and system setup.
  - MVP achieved for each screen.
- **What Went Wrong:**
  - Time constraints close to deadlines.
  - Overly ambitious backlog with large tasks.
- **Changes & Backlog Edits:**
  - Start working earlier.
  - Reassign tasks as needed.
  - Break down large tasks into smaller, manageable ones.
  - Plan for a button linking to the settings page, customizations for order screen, trends ingredient dropdown, and visual component improvements.

#### (6) Sprint #2 & Sprint #3 Planning and Scrum Meetings
- Detailed agendas, task assignments, and retrospective notes are maintained in the project documentation.
- **Key Discussions:**
  - Reallocation of tasks from previous sprints.
  - Database updates, UI improvements, and additional functionality enhancements.
  - Regular evaluations of sprint goals and progress, along with adjustments to the product backlog as needed.

_All sprint and scrum documentation is organized under the `docs/` folder._

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for further details.

## Contact
For questions, feedback, or support, please contact:  
**Alyan Tharani:** [alnotha@tamu.edu](mailto:alnotha@tamu.edu)
```
