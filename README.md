#  PULSE – Event Management Website

PULSE is a college-specific **event management web application** built for **IIIT Allahabad**.  
It helps students discover and participate in campus events while giving admins a simple way to create and manage events — all through a clean, interactive interface.

This project is currently **frontend-only** and focuses on UI/UX and feature flow.

**DEMO** --> https://chandraxshu.github.io/PULSE/

---

##  Features

###  Student
- View all upcoming college events
- Open detailed event pages
- Enroll / participate in events
- View enrollment status (enrolled, selected, disqualified)
- Access mess menu and timetable (PDF viewer)
- Personal to-do list with add / complete / delete options
- Smooth animations and modern dashboard UI

###  Admin
- Create new events
- View and manage all events
- See number of registered students per event
- View enrolled students list
- Disqualify or select students for an event
- Export event registrations as CSV
- Centralized event management dashboard

---

##  UI & Experience
- Blue-gradient themed interface
- Smooth hover and transition animations
- Modal-based panels for events and PDFs
- Responsive layout for different screen sizes
- Designed to feel like a real product, not a static demo

---

##  Tech Stack
- HTML
- CSS
- Vanilla JavaScript  
(All in a single `index.html` file)

---

##  Data & Storage
**No backend is used in this project.**

- All data is stored using browser **localStorage**
- Events, enrollments, and to-do lists persist only on the same device/browser
- No authentication, server, or database is implemented

This approach was chosen to keep the project simple and focus on frontend logic and design.

---

##  Required Files
Place these files in the same folder as `index.html`:

index.html
mess.pdf
timetable.pdf

---

##  Project Status
-  Student & Admin flows implemented
-  Event management fully functional on frontend
-  Stable and interactive UI
-  Backend intentionally not included

---

##  Future Scope
- Backend integration (Firebase / Supabase / Node.js)
- Real authentication & role validation
- Faculty portal
- Notifications for events
- Mobile-first improvements

---

##  Author
Built as a personal project to explore frontend development, UI design, and event-management workflows for a college environment.
